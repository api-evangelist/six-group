---
name: Check Swiss interbank clearing status and clearing days
description: Verify whether SIC electronic payment services are up and look up
  clearing-day scheduling, using the open SIC Service Status and Clearing Day
  Calendar APIs.
api: openapi/six-group-status-api-openapi.yml
operations: [getServiceStatusJson, getClearingDayCalendarJson, getClearingDayCalendarCsv]
generated: '2026-07-22'
method: generated
---

# Check Swiss interbank clearing status and clearing days

Both APIs are publicly documented and answer without authentication.

1. **Check service status** with `getServiceStatusJson`
   (`GET https://api.six-group.com/api/sic/pci_p/status/v1/servicestatus`) — the
   response carries `serviceIdentification`, `status` (e.g. `UP`), and a
   `timestamp` (verified live HTTP 200 on 2026-07-22).
2. **Look up clearing days** with `getClearingDayCalendarJson`
   (`GET https://api.six-group.com/api/epcd/clearingday/v1/calendar`), or
   `getClearingDayCalendarCsv` (`GET /calendar.csv`) for the file variant
   (`openapi/six-group-calendar-api-openapi.yml`).

Rules:
- Treat any non-`UP` status as a signal to defer payment submission workflows.
- Calendar errors use the RFC 7807-shaped `Problem` envelope
  (`errors/six-group-problem-types.yml`).
- There is no human status page — this API is the operational-status surface for
  SIX Interbank Clearing (`lifecycle/six-group-lifecycle.yml`).
