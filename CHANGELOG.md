# Changelog

## [fix] - 2026-10-07

### Fixed
- Nightclub payouts are recomputed server-side from the database (metadata, employee counts, food/poster missions); client-sent percentage and employee tables are ignored.
- Nil-guards added so clubs with missing employee rows no longer error the payout event.
