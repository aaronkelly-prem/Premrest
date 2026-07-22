# Setting up the Cleaning Academy project

A one-time setup. ~10 minutes.

## 1. Create the project

New Claude project. Suggested name: **Premrest Cleaning Academy**. Description: "Developing the Premrest Cleaning Accreditation — training modules for floor-cleaning technicians, housed in Pulse."

## 2. Paste the instructions

Open `PROJECT-INSTRUCTIONS.md`, copy everything below the `---`, and paste it into the project's custom-instructions box.

## 3. Attach the knowledge files

Upload these four to the project's knowledge (drag in from this folder):

- `modules-map.md` — the locked module map
- `module-production-kit.md` — templates + the development loop
- `lms-spec.md` — the Pulse course-engine spec (for Ben)
- `sources.md` — the source index

(No need to upload `PROJECT-INSTRUCTIONS.md` or this `SETUP.md` — the first goes in the instructions box, this one is just for you.)

## 4. Connect the tools

- **Google Drive** — so the project can read the Actichem handbook (`Carpet-Handbook-_-March-2026.pdf`) and the onboarding handbook. Links are in `sources.md`.
- **Pulse** — so the project can pull SDS per chemical for the WHS & Chemical Safety module.

Keep everything else disconnected. This project only needs Drive and Pulse.

## 5. First task to give it

Paste this as the opening message:

> Let's build the Foundations spine in order. Start with **Welcome to Premrest** (Mini Module). Draft the full video script with shot markers, the knowledge-test bank, and the practical sign-off checklist, against the module blueprint. Use the Cleaning Tech Onboarding Handbook in Drive as a source. Show me the outline first, then the full draft.

From there it runs module by module down the map: Welcome → WHS & Chemical Safety → Understanding Chemicals → Machine Competency → Understanding Carpet → Encapsulation 101, then the specialist stamps.

## Note on the two homes

Source PDFs and video live in **Drive** (big files). The **project** holds the thinking, scripts and tests as text. This `training/` folder in the Premrest repo is the master copy of the project pack — if the instructions or map change, update them here and re-upload.
