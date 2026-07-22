# Training — the Premrest Cleaning Accreditation

The system that turns a floor-cleaning technician into a signed-off, certified operator. Online modules housed in Pulse — click-through video + written content, a knowledge test, then a supervisor practical sign-off, then a stamp. Each stamp is a micro-credential; together they make the **Premrest Cleaning Accreditation**.

Internal accreditation only (not RTO / nationally recognised) — for now. Design it as if it *could* be, because the records are worth gold in FM tenders and client audits.

## The two things that make this more than a video library

1. **Competency, not just knowledge.** A click-next quiz proves a tech *knows*. It doesn't prove they *can*. Every module that touches a machine or a chemical ends with a **practical sign-off** — a supervisor observation checklist — before the stamp issues. Knowledge test unlocks the practical; the practical earns the stamp.
2. **Refresh, not one-and-done.** Stamps carry an expiry. The accreditation matrix flags who is due, which is exactly the hole we are filling — most existing staff have had no refresher in 5+ years.

## Two rollout tracks (same modules, different order)

| Track | Who | What they do |
|---|---|---|
| **Refresh** | All existing staff | The **whole** accreditation — Core + every specialist stamp — ASAP. |
| **Onboard** | New hires | **Core** during onboarding; specialist stamps issued on a needs-basis as they hit that work. |

## Module types (by runtime)

| Type | Runtime | Role |
|---|---|---|
| Mini Module | 15–30 min | One tight skill or concept. An extra stamp. |
| Module | 30–45 min | A surface or a body of theory. The workhorse. |
| Course | 1–3 hr | Flagship / broad competency. Chaptered. |

## The module blueprint (every module, same skeleton)

Learning outcomes → Why it matters (safety / quality / cost) → Chemistry & theory → Kit & machine → Method (step-by-step, filmed) → Do's & don'ts & troubleshooting → Knowledge test → Practical sign-off → Stamp.

Same skeleton every time so production is a factory line and the learner experience is consistent.

## Factory vs product

- **Factory (stable):** this file, `lms-spec.md`, `modules/CONTEXT.md` (the map), `sources/CONTEXT.md`, the blueprint above.
- **Product (new per module):** each `modules/<module>/` folder — script, test bank, practical checklist, shot list.

## Route by the task

| Task | Go to |
|---|---|
| The locked module map + build status | `modules/CONTEXT.md` |
| The Pulse course-engine feature spec (for Ben) | `lms-spec.md` |
| Where source material lives (handbook, SDS, Actichem guides) | `sources/CONTEXT.md` |
| Build/script a specific module | `modules/<module>/` |

## The wall & the gate (inherited, non-negotiable)

- Nothing personal / Queerfully Made / Let's Talk surfaces here. See `../_shared/tools.md`.
- No script, test, or certificate goes live without Aaron's review.
