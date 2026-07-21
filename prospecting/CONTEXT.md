# Prospecting — the pipeline

Top-down, exec-level partnership outreach. Read `../_shared/prospecting-model.md` first — the model is the point; these stages just run it. The trigger is Nick having multiple accounts going well inside one firm.

The flow in one line: spot the firm, find the exec, draft the approach, review and send and log.

| Stage | Job | Input | Output | Human check |
|---|---|---|---|---|
| `01_spot-concentration` | Find firms where Nick has concentration + traction | Pulse account data | `output/candidates-{date}.md` | Aaron agrees the firm is worth a top-down approach |
| `02_find-contact` | Find the right firm-level exec + details | a chosen candidate firm | `output/contact-{firm}.md` | Aaron confirms it is the right person to reach |
| `03_draft-outreach` | Draft the partnership approach | the contact + chosen sequence | `output/draft-{firm}.md` | Aaron reads the full draft, edits in place |
| `04_review-send-log` | Send, log the loop, track in Pulse | the approved draft | loop in `../loops/open-loops.md` + Pulse activity | Aaron pushes send himself |

Factory (stable, every run): `../_shared/prospecting-model.md`, `../_shared/voice.md`, `sequences/`.
Product (new each run): each stage's `output/`, plus the loop and Pulse record from stage 04.

Status is whatever exists: a stage is done when its `output/` holds files other than `.gitkeep`. Prospecting is not "done" — it runs continuously; each firm is one pass through the four stages.

Nothing moves to the next stage until Aaron has read the output of the last one. The heaviest gate is stage 03 → 04: no draft becomes an email without his review.
