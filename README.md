# SIX (six-group)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

SIX operates the financial market infrastructure of Switzerland and Spain, including SIX Swiss Exchange, BME, and Swiss interbank clearing and securities services, alongside SIX Financial Information, one of the largest global market data vendors. It sells real-time, intraday, end-of-day, and historical pricing, reference data, corporate actions, and regulatory/ESG datasets from more than 900 price sources, delivered via the SIX Web API (REST/JSON, GraphQL, WebSocket), the SIX Bulk API, streaming Market Data Feed, SIX Flex and Valordata Feed files, and Snowflake cloud shares. A public developer portal at developer.six-group.com fronts the bLink open banking platform, the debiX debit card API, and a shared Kong-based API catalog with Swiss interbank clearing and settlement APIs.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/six-group/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/six-group/refs/heads/main/apis.yml)

## Tags

- Financial
- Market Data
- Stocks
- Reference Data
- Corporate Actions
- Real-Time
- Exchange
- Open Banking
- Payments
- Switzerland

## Timestamps

- **Created:** 2026-07-21
- **Modified:** 2026-07-21

## APIs

### SIX Web API

Single API onto the SIX financial data universe - real-time, intraday, end-of-day, and historical pricing across asset classes, reference data, corporate actions, tax, and ESG datasets from 900+ price sources - using REST/JSON, GraphQL, and WebSocket streaming with MTLS certificate authentication. Access is sales-gated with demo access by request.

- **Human URL:** [https://www.six-group.com/en/products-services/financial-information/delivery-methods/api/web.html](https://www.six-group.com/en/products-services/financial-information/delivery-methods/api/web.html)

#### Properties

- [Documentation](https://www.six-group.com/en/products-services/financial-information/delivery-methods/api/web.html)
- [Portal](https://web.apiportal.six-group.com/portal/bfi/catalog)

### SIX Bulk API

REST/JSON bulk retrieval of the entire SIX financial data catalog - corporate actions, equities and fixed income reference data, and end-of-day pricing - as full extracts or delta updates, with MTLS certificate authentication. Fixed-fee packages, sales-gated with trial access by request.

- **Human URL:** [https://www.six-group.com/en/products-services/financial-information/delivery-methods/api/bulk.html](https://www.six-group.com/en/products-services/financial-information/delivery-methods/api/bulk.html)

#### Properties

- [Documentation](https://www.six-group.com/en/products-services/financial-information/delivery-methods/api/bulk.html)

### SIX bLink API

Switzerland's open banking platform connecting banks and third-party service providers over RESTful JSON/XML APIs with OAuth consent flows - AIS, PSS, OpenWealth, and consent base modules. Publicly documented; participation requires bLink admission.

- **Human URL:** [https://docs.blink.six-group.com/api-reference/introduction](https://docs.blink.six-group.com/api-reference/introduction)

#### Properties

- [Documentation](https://docs.blink.six-group.com/)
- [API Reference](https://docs.blink.six-group.com/api-reference/introduction)
- [Downloads](https://docs.blink.six-group.com/docs/downloads)
- [Website](https://blink.six-group.com/)

### SIX debiX API

REST API for card issuers on the debiX debit and mobile payment platform - transactions, card token lifecycle, push notifications, bulk operations - with publicly downloadable OpenAPI 3.1 definitions.

- **Human URL:** [https://docs.debix.six-group.com/](https://docs.debix.six-group.com/)
- **Base URL:** `https://api.six-group.com/api/debix/bank/v2`

#### Properties

- [Documentation](https://docs.debix.six-group.com/)
- [API Reference](https://docs.debix.six-group.com/api/debix/v2)
- [OpenAPI](openapi/six-group-debix-bank-api-v2-bank-to-six-openapi.yml)
- [OpenAPI - cardtoken](openapi/six-group-debix-bank-api-cardtoken-v2-bank-to-six-openapi.yml)

### SIX debiX Auth Provider API

Bidirectional authentication API pair between SIX and auth providers supporting the 3DS out-of-band authentication flow for debiX debit cards.

- **Human URL:** [https://docs.debix.six-group.com/debix-auth-v2/](https://docs.debix.six-group.com/debix-auth-v2/)
- **Base URL:** `https://api.six-group.com/api/debix-auth/provider-auth/v2`

#### Properties

- [Documentation](https://docs.debix.six-group.com/debix-auth-v2/)
- [OpenAPI - SIX-to-provider](openapi/six-group-debix-auth-provider-api-v2-six-to-provider-openapi.yml)
- [OpenAPI - provider-to-SIX](openapi/six-group-debix-auth-provider-api-v2-provider-to-six-openapi.yml)

### Swiss Bank Master API

Master data required for electronic payments in Switzerland - bank master records in JSON and CSV plus IBAN tooling. Documented production endpoints respond without registration (healthcheck HTTP 200 on 2026-07-21).

- **Human URL:** [https://apiportal.six-group.com/apis/swiss-bank-master-api-ch-v3/docs](https://apiportal.six-group.com/apis/swiss-bank-master-api-ch-v3/docs)
- **Base URL:** `https://api.six-group.com/api/epcd/bankmaster/v3`

#### Properties

- [Documentation](https://apiportal.six-group.com/apis/swiss-bank-master-api-ch-v3/docs)
- [OpenAPI](openapi/six-group-swiss-bank-master-openapi.json)

### SIC Service Status API

Current operational status of the electronic payment services run by SIX Interbank Clearing Ltd. GET /servicestatus returned HTTP 200 without authentication on 2026-07-21.

- **Human URL:** [https://apiportal.six-group.com/apis/sic-service-status-api-v1-ch-v1/docs](https://apiportal.six-group.com/apis/sic-service-status-api-v1-ch-v1/docs)
- **Base URL:** `https://api.six-group.com/api/sic/pci_p/status/v1`

#### Properties

- [Documentation](https://apiportal.six-group.com/apis/sic-service-status-api-v1-ch-v1/docs)
- [OpenAPI](openapi/six-group-sic-service-status-openapi.json)

### SIC Clearing Day Calendar API

Scheduling information for the electronic payment services provided by SIX Interbank Clearing Ltd.

- **Human URL:** [https://apiportal.six-group.com/apis/sic-clearing-day-calendar-api-v1-ch-v1/docs](https://apiportal.six-group.com/apis/sic-clearing-day-calendar-api-v1-ch-v1/docs)
- **Base URL:** `https://api.six-group.com/api/epcd/clearingday/v1`

#### Properties

- [Documentation](https://apiportal.six-group.com/apis/sic-clearing-day-calendar-api-v1-ch-v1/docs)
- [OpenAPI](openapi/six-group-sic-clearing-day-calendar-openapi.json)

### Settlement Info Reporting API

Security settlement information reporting from the SIX custody cockpit for the Swiss market (OpenAPI licensed CC BY-ND 4.0).

- **Human URL:** [https://apiportal.six-group.com/apis/settlement-info-reporting-ch-v1/docs](https://apiportal.six-group.com/apis/settlement-info-reporting-ch-v1/docs)
- **Base URL:** `https://api.six-group.com/custody/cockpit/setlInfo/v1`

#### Properties

- [Documentation](https://apiportal.six-group.com/apis/settlement-info-reporting-ch-v1/docs)
- [OpenAPI](openapi/six-group-settlement-info-reporting-openapi.json)

## Common Properties

- [Website](https://www.six-group.com/)
- [Portal](https://developer.six-group.com/en/home.html)
- [Documentation](https://apiportal.six-group.com/)
- [GitHub Organization](https://github.com/six-group)
- [LinkedIn](https://www.linkedin.com/company/sixgroup)
- [Blog](https://www.six-group.com/en/newsroom.html)
- [Terms of Service](https://www.six-group.com/en/services/legal/terms-of-use.html)
- [Privacy Policy](https://www.six-group.com/en/services/legal/privacy-statement.html)
- [Support](https://www.six-group.com/en/contacts.html)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
