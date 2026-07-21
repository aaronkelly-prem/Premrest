# loops — the completion system

Aaron is an ADHD executive: starting is easy, finishing is the hard part. This system exists to help him **complete, not just start**. It is the most important non-prospecting job in the workspace.

`open-loops.md` is the single source of truth. There is no second list. Everything lives here.

## Design principles

- **One file.** All open loops for Premrest live in `open-loops.md`. No scattered lists.
- **Everything Claude helps start becomes a loop automatically.** If Claude touches it, it gets logged. Nothing quietly disappears.
- **Loops are tagged to the weekly blocks** (`../_shared/weekly-blocks.md`) via the `day:` field, so they surface on the right day.
- **Big things get broken down to the next tiny physical action.** The loop's `next:` is "write three bullets for slide two", never "finish the deck".
- **Completion help means Claude does the work.** To help Aaron finish, Claude does the drafting/preparing so finishing is reviewing and sending — attacking the activation energy to close, not adding a task.
- **State-on-open** (below) leads every session.

## State-on-open protocol (do this when the workspace opens)

Before Aaron asks for anything, read `open-loops.md` and lead with:
1. **Overdue** — `due:` in the past.
2. **Gone quiet** — no movement past its expected cadence (e.g. an outreach loop with no follow-up logged).
3. **Open today** — loops whose `day:` matches the current block.

Keep it short and physical: name the loop and its `next:` tiny action. Offer to do that next action now.

## Loop format (in open-loops.md)

Each loop is one block:

```
### {id} · {short title}
- status: open | in-progress | gone-quiet | overdue | done
- day: Monday | Tuesday | Wed-AM | Wed-PM | Thursday | Friday | Floating
- next: {the next tiny physical action — small enough to just do}
- due: {YYYY-MM-DD or —}
- opened: {YYYY-MM-DD}
- context: {one line, or a link to prospecting/output/... or a Pulse record}
```

Status is derivable by scanning the file — that is the state machine. A loop is done when its status reads `done`; move done loops to the bottom under `## Closed` (kept for the record, not deleted).

## Build order (this system)

1. **State-on-open** — works immediately, this file + protocol. ← built now.
2. **Scheduled nudges** — an 8am "here's today" and a nudge when a loop sits too long. Needs a scheduled task on Aaron's always-on Mac. Build once state-on-open is proven accurate. **Not built yet.**
3. **Gamified loop view** — a visual, clickable "click next through suggestions" layer *on top of* this file, for when Aaron is stuck on where to start. The file stays the source of truth; the game is the engagement hook. **Phase two.**
