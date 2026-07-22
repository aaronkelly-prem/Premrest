# Module production kit

The factory line. Every module is produced the same way and delivered as the same four files, so quality is consistent and Ben can load them into Pulse predictably.

## The development loop

1. **Scope** — pull the module's row from the map: type, runtime, tier, prerequisites, machine. State the target runtime and how many chapters that buys.
2. **Research** — read the cited sources for that surface (handbook sections, Actichem guides, SDS). List what you're drawing on before writing. No claim without a source.
3. **Outline** — map the blueprint onto chapters. Confirm outline with Aaron before scripting a long Course.
4. **Script** — write the full video script with shot markers.
5. **Test** — build the test bank.
6. **Practical** — write the sign-off checklist.
7. **Shot list** — produce the filming plan.
8. **Review** — Aaron reviews; revise; mark the map row drafted.

## The four deliverables (per module folder)

```
modules/<module>/
  script.md              # full video script + on-screen text + shot markers
  test-bank.md           # questions, answers, mapping, pass mark, remediation
  practical-checklist.md # supervisor observation sign-off
  shot-list.md           # filming plan for production
```

---

## 1. script.md — template

```
# <Module name> — video script
Type / runtime: ____   Prerequisites: ____   Machine(s): ____

## Learning outcomes (what the tech can do after this)
- ...

## Cold open / hook (15–30 sec)
Why this matters on a real Premrest job. A concrete consequence of getting it wrong (callback, damaged floor, safety).

## Chapter 1 — <title>
[TALKING HEAD] spoken script, plain language, short sentences...
[ON-SITE DEMO] what the camera shows the tech doing...
[B-ROLL] supporting footage...
[ON-SCREEN TEXT] key term / dilution / dwell time as a caption...
[SAFETY] PPE / SDS / hazard callout where relevant...

## Chapter 2 — ...
(repeat)

## Recap
The 3–5 things that must stick.

## Into the test
One line handing off to the knowledge check.
```

Rules: speak to the technician, not about them. Real product and machine names, real dilutions and dwell times. Every hazard gets a [SAFETY] callout. Mark every shot type so production knows what to film.

---

## 2. test-bank.md — template

```
# <Module name> — knowledge test
Pass mark: 80% (default)   Draw: N of M (pool + shuffle)   Attempts: logged, remediation on fail

## Q1  [type: MCQ | multi | true-false | image-identify | ordering | scenario]
Stem: ...
Options: A / B / C / D
Answer: ...
Maps to outcome: ...
Remediation chapter (on fail): Chapter X
Why (feedback shown): ...
```

Rules: assess competence, not reading speed. Use image-identify for fibre/stain/finish recognition and ordering for method steps. Every item maps to a learning outcome and to the chapter a fail sends them back to. Write more items than the draw size so the pool can shuffle.

---

## 3. practical-checklist.md — template

```
# <Module name> — practical sign-off
Assessor: ____  Technician: ____  Date: ____  Location/job: ____

Observed against criteria (each: Competent / Not yet competent + note):
[ ] Correct PPE and site set-up (signage, ventilation)
[ ] Correct chemical, dilution and dwell
[ ] Correct machine set-up and technique
[ ] <module-specific criteria...>
[ ] Result meets the Premrest finished standard
[ ] Pack-down, waste and equipment care

Evidence: photo(s) attached
Outcome: Competent / Not yet competent (re-observe)
Assessor signature: ____
```

Rules: criteria are observable and binary. This gate issues the stamp; a knowledge-only module (e.g. Welcome, Understanding Chemicals) can skip it, flagged in the map.

---

## 4. shot-list.md — template

```
# <Module name> — shot list
Format mix: talking head / on-site demo / b-roll
Presenter(s): ____   Location(s): ____   Kit & chemicals needed: ____

| # | Chapter | Shot type | What we see | Location | Kit | On-screen text | Notes |
|---|---|---|---|---|---|---|---|
| 1 | Cold open | ... | ... | ... | ... | ... | ... |
```

Rules: one row per shot, in filming order (not script order) so a day's filming at one site is grouped. Flag anything needing a specific floor type or a live soil/stain to demo.
