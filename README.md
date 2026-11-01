# SIX

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

SIX operates the financial market infrastructure of Switzerland and Spain, including SIX Swiss Exchange, BME, and Swiss interbank clearing and securities services, alongside SIX Financial Information, one of the largest global market data vendors. It sells real-time, intraday, end-of-day, and historical pricing, reference data, corporate actions, and regulatory/ESG datasets from more than 900 price sources, delivered via the SIX Web API (REST/JSON, GraphQL, WebSocket), the SIX Bulk API, streaming Market Data Feed, SIX Flex and Valordata Feed files, and Snowflake cloud shares. A public developer portal at developer.six-group.com fronts the bLink open banking platform, the debiX debit card API, and a shared Kong-based API catalog with Swiss interbank clearing and settlement APIs. Financial data access is enterprise and sales-gated with MTLS certificate authentication, while several Swiss payment infrastructure APIs are publicly documented with downloadable OpenAPI.

**Areas:** Finance · Market Data · Stocks · Reference Data · Corporate Actions · Real-Time · Exchange · Open Banking · Payments · Switzerland

## SIX on APIs.io

Everything profiled for SIX is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/six-group/](https://apis.io/providers/six-group/)** — or go straight to one of the APIs or properties below.

### APIs (11)

- [SIX Web API](https://apis.io/apis/six-group/six-web-api/) — Single API onto the SIX financial data universe - real-time, intraday, end-of-day, and historical pricing across asset classes, reference data, corporate…
- [SIX Bulk API](https://apis.io/apis/six-group/six-bulk-api/) — REST/JSON bulk retrieval of the entire SIX financial data catalog - corporate actions, equities and fixed income reference data, and end-of-day pricing - as…
- [SIX bLink API](https://apis.io/apis/six-group/blink-api/) — Switzerland's open banking platform connecting banks and third-party service providers over RESTful JSON/XML APIs with OAuth consent flows - Account…
- [SIX Debi X API](https://apis.io/apis/six-group/debix-api/) — REST API for card issuers on the debiX debit and mobile payment platform - transaction processing, card token lifecycle, push notifications, and bulk…
- [SIX debiX Auth Provider API](https://apis.io/apis/six-group/debix-auth-provider-api/) — Bidirectional authentication API pair between SIX and auth providers supporting the 3DS out-of-band (OOB) authentication flow for debiX debit cards, with…
- [Swiss Bank Master API](https://apis.io/apis/six-group/swiss-bank-master-api/) — Master data required for electronic payments in Switzerland - bank master records in JSON and CSV plus IBAN tooling - published openly on the SIX API…
- [SIC Service Status API](https://apis.io/apis/six-group/sic-service-status-api/) — Current operational status of the electronic payment services run by SIX Interbank Clearing Ltd, publicly documented with downloadable OpenAPI; GET…
- [SIC Clearing Day Calendar API](https://apis.io/apis/six-group/sic-clearing-day-calendar-api/) — Scheduling information for the electronic payment services provided by SIX Interbank Clearing Ltd - clearing day calendar lookups - publicly documented on…
- [Settlement Info Reporting API](https://apis.io/apis/six-group/settlement-info-reporting-api/) — Security settlement information reporting from the SIX custody cockpit for the Swiss market, publicly documented on the SIX API portal with a downloadable…
- [SIX 3 DS API](https://apis.io/apis/six-group/six-group-3-ds-api/) — 3DS lifecycle, 3DS details, OTRC order.
- [SIX Bank Master API](https://apis.io/apis/six-group/six-group-bank-master-api/) — **Bankmaster API** All public REST endpoints of the bank master data are located here, such as the bank master data as JSON and downloadable files.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Six Group Debix Push Webhooks](https://apis.io/asyncapis/six-group/six-group-debix-push-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [six-group](https://apis.io/servers/six-group/six-group/)

#### Collections (20)

Postman and Open Collection request collections.

- [debiX Auth Provider API: Provider-to-SIX 3DS API](https://apis.io/collections/six-group/open-six-group-3ds-api/)
- [debiX Auth Provider API: Provider-to-SIX 3DS 3DS Authentication API](https://apis.io/collections/six-group/open-six-group-3ds-authentication-api/)
- [debiX Auth Provider API: Provider-to-SIX 3DS Alias Directory (Beta) API](https://apis.io/collections/six-group/open-six-group-alias-directory-beta-api/)
- [debiX Auth Provider API: Provider-to-SIX 3DS Authentication callback API](https://apis.io/collections/six-group/open-six-group-authentication-callback-api/)
- [debiX Auth Provider API: Provider-to-SIX 3DS bankmaster API](https://apis.io/collections/six-group/open-six-group-bankmaster-api/)
- [debiX Auth Provider API: Provider-to-SIX 3DS BulkSubscriptionManagement API](https://apis.io/collections/six-group/open-six-group-bulksubscriptionmanagement-api/)
- [debiX Auth Provider API: Provider-to-SIX 3DS BulkSubscriptionResults API](https://apis.io/collections/six-group/open-six-group-bulksubscriptionresults-api/)
- [debiX Auth Provider API: Provider-to-SIX 3DS calendar API](https://apis.io/collections/six-group/open-six-group-calendar-api/)
- [debiX Auth Provider API: Provider-to-SIX 3DS Card Management API](https://apis.io/collections/six-group/open-six-group-card-management-api/)
- [debiX Auth Provider API: Provider-to-SIX 3DS Card Usage API](https://apis.io/collections/six-group/open-six-group-card-usage-api/)
- [debiX Auth Provider API: Provider-to-SIX 3DS Click to Pay Issuer Offered API](https://apis.io/collections/six-group/open-six-group-click-to-pay-issuer-offered-api/)
- [debiX Auth Provider API: Provider-to-SIX 3DS debiX PUSH Management (Beta) API](https://apis.io/collections/six-group/open-six-group-debix-push-management-beta-api/)
- [debiX Auth Provider API: Provider-to-SIX 3DS Deprecated API](https://apis.io/collections/six-group/open-six-group-deprecated-api/)
- [debiX Auth Provider API: Provider-to-SIX 3DS DetailedSettlementInformation API](https://apis.io/collections/six-group/open-six-group-detailedsettlementinformation-api/)
- [debiX Auth Provider API: Provider-to-SIX 3DS Health check API](https://apis.io/collections/six-group/open-six-group-health-check-api/)
- [debiX Auth Provider API: Provider-to-SIX 3DS healthcheck API](https://apis.io/collections/six-group/open-six-group-healthcheck-api/)
- [debiX Auth Provider API: Provider-to-SIX 3DS iban API](https://apis.io/collections/six-group/open-six-group-iban-api/)
- [debiX Auth Provider API: Provider-to-SIX 3DS status API](https://apis.io/collections/six-group/open-six-group-status-api/)
- [debiX Auth Provider API: Provider-to-SIX 3DS Token Lifecycle Management API](https://apis.io/collections/six-group/open-six-group-token-lifecycle-management-api/)
- [debiX Auth Provider API: Provider-to-SIX 3DS Token Provisioning API](https://apis.io/collections/six-group/open-six-group-token-provisioning-api/)

#### Overlays (20)

OpenAPI overlays, including conversational phrasing for each operation.

- [Six Group 3Ds Api Overlay](https://apis.io/overlays/six-group/six-group-3ds-api-overlay/)
- [Six Group 3Ds Authentication Api Overlay](https://apis.io/overlays/six-group/six-group-3ds-authentication-api-overlay/)
- [Six Group Alias Directory Beta Api Overlay](https://apis.io/overlays/six-group/six-group-alias-directory-beta-api-overlay/)
- [Six Group Authentication Callback Api Overlay](https://apis.io/overlays/six-group/six-group-authentication-callback-api-overlay/)
- [Six Group Bankmaster Api Overlay](https://apis.io/overlays/six-group/six-group-bankmaster-api-overlay/)
- [Six Group Bulksubscriptionmanagement Api Overlay](https://apis.io/overlays/six-group/six-group-bulksubscriptionmanagement-api-overlay/)
- [Six Group Bulksubscriptionresults Api Overlay](https://apis.io/overlays/six-group/six-group-bulksubscriptionresults-api-overlay/)
- [Six Group Calendar Api Overlay](https://apis.io/overlays/six-group/six-group-calendar-api-overlay/)
- [Six Group Card Management Api Overlay](https://apis.io/overlays/six-group/six-group-card-management-api-overlay/)
- [Six Group Card Usage Api Overlay](https://apis.io/overlays/six-group/six-group-card-usage-api-overlay/)
- [Six Group Click To Pay Issuer Offered Api Overlay](https://apis.io/overlays/six-group/six-group-click-to-pay-issuer-offered-api-overlay/)
- [Six Group Debix Push Management Beta Api Overlay](https://apis.io/overlays/six-group/six-group-debix-push-management-beta-api-overlay/)
- [Six Group Deprecated Api Overlay](https://apis.io/overlays/six-group/six-group-deprecated-api-overlay/)
- [Six Group Detailedsettlementinformation Api Overlay](https://apis.io/overlays/six-group/six-group-detailedsettlementinformation-api-overlay/)
- [Six Group Health Check Api Overlay](https://apis.io/overlays/six-group/six-group-health-check-api-overlay/)
- [Six Group Healthcheck Api Overlay](https://apis.io/overlays/six-group/six-group-healthcheck-api-overlay/)
- [Six Group Iban Api Overlay](https://apis.io/overlays/six-group/six-group-iban-api-overlay/)
- [Six Group Status Api Overlay](https://apis.io/overlays/six-group/six-group-status-api-overlay/)
- [Six Group Token Lifecycle Management Api Overlay](https://apis.io/overlays/six-group/six-group-token-lifecycle-management-api-overlay/)
- [Six Group Token Provisioning Api Overlay](https://apis.io/overlays/six-group/six-group-token-provisioning-api-overlay/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Six Group Authentication](https://apis.io/security/six-group/six-group-authentication/)
- [Six Group Domain Security](https://apis.io/security/six-group/six-group-domain-security/)
- [Six Group Vulnerability Disclosure](https://apis.io/security/six-group/six-group-vulnerability-disclosure/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.six-group.com/)
- [Documentation](https://apiportal.six-group.com/)
- [Getting started](https://docs.debix.six-group.com/getting-started)
- [API reference](https://apiportal.six-group.com/apis)
- [Sign up](https://apiportal.six-group.com/register)
- [Support](https://www.six-group.com/en/contacts.html)
- [Blog](https://www.six-group.com/en/blog.html)
- [Security](https://hackerone.com/six-group)
- [Terms of service](https://www.six-group.com/en/services/legal/terms-of-use.html)
- [Privacy policy](https://www.six-group.com/en/services/legal/privacy-statement.html)
- [GitHub](https://github.com/six-group)

## API Evangelist rating

**Kin Score 51.2** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 69.6 |
| Contract quality | 55.1 |
| Contract governance | 18.2 |
| Operational transparency | 44.7 |
| Developer ergonomics | 70.8 |
| Access clarity | 34.2 |

**Agent readiness 41.6** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | verified |
| Event Surface Described | yes |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | — |

**Regulatory alignment 34.6** — Banking & Open Finance

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/six-group/](https://apis.io/providers/six-group/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for SIX: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/six-group/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
