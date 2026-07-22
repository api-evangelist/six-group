---
name: Order and manage a debiX debit card
description: Issuer-side happy path on the debiX platform - order a card, read its
  details, and manage its status - over mTLS-certificated access.
api: openapi/six-group-card-management-api-openapi.yml
operations: [orderCard, getCardDetails, updateCardStatus, getCardToken, startSetPin, setPin]
generated: '2026-07-22'
method: generated
---

# Order and manage a debiX debit card

Access requires an X.509 client certificate registered with SIX per environment
(test: `api-preprod.np.six-group.com`, production: `api.six-group.com`, base path
`/api/debix/bank/v2` or `/api/debix/bank/cardtoken/v2`) — see
`authentication/six-group-authentication.yml` and `sandbox/six-group-sandbox.yml`.

1. **Verify connectivity first** on the test system by calling the healthcheck
   surface with all verbs (`healthcheckForGet` and friends in
   `openapi/six-group-health-check-api-openapi.yml`).
2. **Order a card** with `orderCard` (`POST /cards`).
3. **Resolve the tokenized identifier** with `getCardToken`
   (`POST /cards/card-token`) — prefer `CardToken`/`CardInstanceToken` over the
   deprecated `ShortCardId`/`CardId` identifiers.
4. **Read card details** with `getCardDetails` (`POST /cards/{cardToken}`).
5. **Set the PIN** via `startSetPin` (`POST /cards/{cardToken}/start-set-pin`)
   then `setPin` (`POST /cards/{cardToken}/set-pin`).
6. **Manage status** (block/unblock etc.) with `updateCardStatus`
   (`PUT /cards/{cardToken}/status`).

Rules:
- Errors use the `BankApiError` envelope (`applicationError` + numeric int32
  `errorCode`, e.g. `4469 PIN_DELIVERY_NOT_ALLOWED_FOR_VIRTUAL_CARD`); consult
  `errors/six-group-problem-types.yml` and the release notes for new codes.
- Avoid endpoints grouped under the Deprecated tag
  (`openapi/six-group-deprecated-api-openapi.yml`); use the CardToken variants.
- Subscribe to debiX PUSH events (card lifecycle, token lifecycle, transactions)
  to keep issuer systems in sync (`asyncapi/six-group-debix-push-webhooks.yml`).
- No idempotency keys are supported — deduplicate retries client-side
  (`conventions/six-group-conventions.yml`).
