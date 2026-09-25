repo: Rookledger/GroundworkOS
branch: main

## Last sync

date: 2026-09-06T00:35:07Z

### Updated in this project

- Stack migrated: Railway/Express/Postgres/Clerk → Cloudflare Pages + Workers (Hono), D1 + Drizzle, R2 storage, KV rate limiting, Better Auth. Deployment section and stats rewritten (was "1 service to deploy", now "2 Cloudflare projects").
- Confirmed no social/OAuth sign-in exists (Better Auth is email + password only, invite-only) — matches the earlier softened "invite-only, three roles" copy.
- Accounting syncs (Xero, QuickBooks, Sage, FreeAgent) and CIS300-as-manual-CSV claim unchanged — still accurate.
- Same updates applied to the print copy (GroundworkOS Site-print.dc.html).

## Screen map

| Screen | Built from |
| --- | --- |
| GroundworkOS Site.dc.html | README.md, DEPLOYMENT.md, artifacts/groundworkos/src/pages/* (18 modules), src/hooks/useRole.ts |
| GroundworkOS Site-print.dc.html | Same as above |

## Sync history

- 2026-08-21T10:19:08Z — initial build of the marketing site from README.md + repo screenshots (repo then at lauhonyanhk123-creator/groundworkos-railway).
- 2026-08-21T10:33:01Z — audited claims against source; softened auth copy; fixed CIS300 wording; removed Resend from sync strip.
