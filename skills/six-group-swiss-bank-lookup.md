---
name: Look up Swiss bank master and IBAN data
description: Resolve Swiss bank master records and IBAN information from the open,
  unauthenticated Swiss Bank Master API on api.six-group.com.
api: openapi/six-group-bankmaster-api-openapi.yml
operations: [getBankmaster, getBankmasterJson, getBankmasterCsv, getIbanInformation]
generated: '2026-07-22'
method: generated
---

# Look up Swiss bank master and IBAN data

Base URL: `https://api.six-group.com/api/epcd/bankmaster/v3` — no authentication
required (documented production endpoints answer HTTP 200 anonymously).

1. **Fetch the bank master** with `getBankmaster` (`GET /bankmaster`) or
   `getBankmasterJson` (`GET /bankmaster.json`) for the full JSON snapshot of
   Swiss bank master records (IID, BIC, names) required for electronic payments.
2. **Prefer the CSV file** for bulk/offline use: `getBankmasterCsv`
   (`GET /bankmaster_V3.csv`).
3. **Resolve an IBAN** with `getIbanInformation` (`GET /iban`) from the IBAN API
   surface (`openapi/six-group-iban-api-openapi.yml`).

Rules:
- Errors come back as RFC 7807-shaped `Problem` objects (`type`, `title`,
  `status`, `detail`) served as `application/json` — see
  `errors/six-group-problem-types.yml`.
- The data is a snapshot product: cache it and re-pull rather than hammering the
  endpoint; no rate limits are published (`conventions/six-group-conventions.yml`).
- Content is CC BY-ND licensed on the SIX API portal; attribute SIX when
  redistributing.
