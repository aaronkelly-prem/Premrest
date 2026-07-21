# Premrest — the workspace shape

An **umbrella**: a hub over a fat shared-context core. Most of the value is Claude sitting on a well-organised context layer (`_shared/`) with Premrest tools wired in. A few jobs are real pipelines; the rest is the agent answering from context.

The flow is not one sequence. It is: read the shared core, then route to the job.

| Area | Type | What it is |
|---|---|---|
| `_shared/` | factory | Business, prospecting model, voice, team, weekly blocks, tools, governed rules. Stable across runs. |
| `prospecting/` | pipeline | The meaty repeatable job: top-down partnership outreach. 4 stages, human gate before send. |
| `loops/` | state surface | The completion system. One open-loops file + the state-on-open protocol. Runs continuously, not a sequence. |
| `setup/` | config | Open items still to be answered before the factory is fully configured. |

Factory (stable, every run): everything in `_shared/`.
Product (new each run): `prospecting/output/`, and entries appended to `loops/open-loops.md`.

Status of prospecting is whatever exists: a stage is done when its `output/` holds files other than `.gitkeep`. Status of the day is whatever `loops/open-loops.md` says.

## The walls this workspace lives inside

Premrest is one of several separate workspaces (personal brand, Queerfully Made, LinkedIn). They never read each other. Separation is enforced by folder scope and tool scope, and — most importantly — by the content wall in `_shared/tools.md`: nothing from another part of Aaron's life is ever surfaced in Premrest output.
