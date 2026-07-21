# Setup — what still needs configuring

Answers get written into `_shared/`. Once answered, no run should re-ask them. Status as of the build handover (2026-07-21).

## Decisions locked (from Aaron)

- **ICM method** — follow the icm-architect skill (installed). ✓
- **Google scoping** — full cross-account calendar view is intended for Aaron's insight; the wall is content-only. Written into `_shared/tools.md`. ✓
- **Calendar role** — Full: blocks are "Free" themes for open office time, not hard holds. Claude surfaces block-themed work, proposes/drafts scheduling, all gated. Written into `_shared/weekly-blocks.md`. ✓
- **Existing partners** — light-touch tracking chosen, but **there are no partners yet** (prospecting creates the first ones), so this is dormant until a relationship exists. Written into `_shared/weekly-blocks.md`. ✓
- **Speaking** — Tuesday block is sourcing/booking speaking spots that represent Premrest, for Aaron or team members (Tim Bradbury, Colin Saddington). Separate from personal LGBTQ+ speaking. Written into `_shared/weekly-blocks.md`. ✓

- **Roster** — roles and reporting lines confirmed by Aaron; formal role docs stored in `_shared/roles/`. Aaron reports to **Ben Young (MD)**; Special Projects (Colin Saddington, with Jack Collins under him) sits under Cleaning; Perry currently covers both client-service roles with no reports; Micah is in a new Operations & Process Improvement Coordinator role. Written into `_shared/team.md`. ✓

## Still open — needed to finish the factory

_All handover open items are now closed. Remaining work is the tool setup below and the deferred phases._

## Tool setup Aaron does himself

4. **Firmable** — paste the API key into the MCP/env config (Claude guides to the right place, never handles the raw key). Replicate Nick's working Claude/Firmable setup. Have "the code" ready.
5. **Gmail** — authorise the Gmail connector for the **Premrest account only**, in connector settings. Currently unauthorised.

## Deliberately deferred (do NOT build yet)

- **Scheduled nudges** — after state-on-open is proven accurate (needs the always-on Mac task).
- **Gamified loop view** — phase two, a layer on top of `loops/open-loops.md`.
- **Pulse outreach module spec** — only after sequences have run enough to know their real shape.
- **Cross-life command deck** — only after all five workspaces exist.
- **Podcast + everyday-ops folders** — scaffold when each job first actually runs.
