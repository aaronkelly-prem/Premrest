# Pulse Course Engine — feature spec (for Ben)

What the training modules assume Pulse can do. Anything not already in Pulse, Ben builds in Lovable. Written to be industry-leading, not minimum-viable — the module design leans on all of it, especially captions, mixed question types, the practical sign-off gate, and the accreditation matrix.

## 1. Delivery

- Sequential click-through ("Next"), with **save & resume** — a tech can stop mid-module and return where they left off.
- **Chaptered video** hosting: chapters map to method steps, so a tech can jump back to one step. Playback speed control.
- **Captions / subtitles + full transcript** on every video. Non-negotiable — mixed literacy and on-site noise in our workforce.
- Written content interleaved between video chapters (not just a wall of text at the end).

## 2. Assessment (knowledge test)

- Mixed question types: single-answer MCQ, multi-select, true/false, **image-based "identify this"** (fibre / stain / finish — hotspot or drag-to-label), **ordering** (put method steps in sequence), and short scenario / branching ("wool, alkaline spill — what first?").
- **Question pool + shuffle** — pull N from a larger bank, randomise order and options, so answers can't be shared between techs.
- Configurable **pass mark** per module (default 80%).
- **Remediation loop** — a fail sends the tech back to the specific chapter the missed questions map to, then a re-attempt. Attempts logged.

## 3. Practical sign-off (competency gate)

- After the knowledge test passes, the module unlocks a **practical sign-off** — not the tech's to complete.
- A supervisor/trainer completes a **mobile observation checklist**: pass/fail against listed criteria, photo evidence, date, assessor name + digital signature.
- Certificate does **not** issue until *both* knowledge test passed **and** practical signed off. (Pure-knowledge modules like "Welcome" or "Understanding Chemicals" can be flagged knowledge-only.)

## 4. Certificate & stamp

- Auto-issued on completion. Carries: module name, tech name, issue date, **expiry / refresh-due date**, unique ID + QR code for verification.
- Each completed module = a **stamp** (micro-credential badge) on the tech's profile.

## 5. Accreditation matrix (the management layer)

- **Skills matrix**: every tech × every module — held / in-progress / expired / not-started.
- **Expiry tracking + auto-reminders** to tech and supervisor when a stamp is due for refresh.
- **Reporting / export**: who is accredited on what; gaps by team or site. Exportable as a clean PDF/CSV — this is what we hand to a client or drop into an FM tender to prove a trained workforce.
- Track assignment by **rollout track** (Refresh = all-now; Onboard = core-then-needs-based).

## Priority for a first build

If Ben stages it: (1) click-through + chaptered video + captions, (2) mixed-type test with pass mark + remediation, (3) practical sign-off gate, (4) auto-cert with expiry, (5) accreditation matrix + export. Modules can pilot on 1–2 while 3–5 are built.
