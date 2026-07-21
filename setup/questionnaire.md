# Setup — what still needs configuring

Answers get written into `_shared/`. Once answered, no run should re-ask them. Status as of the build handover (2026-07-21).

## Decisions locked (from Aaron)

- **ICM method** — follow the icm-architect skill (installed). ✓
- **Google scoping** — full cross-account calendar view is intended for Aaron's insight; the wall is content-only. Written into `_shared/tools.md`. ✓
- **Calendar role** — Full: blocks are "Free" themes for open office time, not hard holds. Claude surfaces block-themed work, proposes/drafts scheduling, all gated. Written into `_shared/weekly-blocks.md`. ✓
- **Existing partners** — light-touch tracking: surface who has gone quiet, prompt check-ins, no auto-drafting. ✓

## Still open — needed to finish the factory

1. **Roster role lines** (`_shared/team.md`). Confirm the role and "what Aaron calls on them for" for **Perry Sandoval, Micah Liwanag, Bella Young, Mehdi Soltani**. Confirm whether **Colin Saddington** is a direct report or a separate team. Confirm whether **Ben Young** (likely the Pulse/Lovable builder) and any other head-office staff belong in the roster.
2. **Speaking scope** (`_shared/weekly-blocks.md`). Confirm Tuesday speaking/presenting is Premrest thought-leadership as GM only, kept separate from personal LGBTQ+ speaking.
3. **Existing relationship management** — light-touch is chosen. Confirm where existing partners live in Pulse (which list/pipeline) so Claude knows what to scan for "gone quiet".

## Tool setup Aaron does himself

4. **Firmable** — paste the API key into the MCP/env config (Claude guides to the right place, never handles the raw key). Replicate Nick's working Claude/Firmable setup. Have "the code" ready.
5. **Gmail** — authorise the Gmail connector for the **Premrest account only**, in connector settings. Currently unauthorised.

## Deliberately deferred (do NOT build yet)

- **Scheduled nudges** — after state-on-open is proven accurate (needs the always-on Mac task).
- **Gamified loop view** — phase two, a layer on top of `loops/open-loops.md`.
- **Pulse outreach module spec** — only after sequences have run enough to know their real shape.
- **Cross-life command deck** — only after all five workspaces exist.
- **Podcast + everyday-ops folders** — scaffold when each job first actually runs.
