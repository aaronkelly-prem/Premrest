# 04_review-send-log — send, log the loop, track in Pulse

One job: turn an approved draft into a sent approach that is tracked and cannot quietly disappear.

## Inputs
- Working (this run): ../03_draft-outreach/output/draft-{firm}.md (Aaron-approved)
- Reference (every run): ../../loops/CONTEXT.md (how loops are logged)
- Reference (every run): ../../_shared/tools.md (the human gate)

Do NOT load: earlier stages' working files beyond the approved draft.

## Process
1. **Aaron sends** the email from the Premrest Gmail account. Claude prepares it as a Gmail draft; Aaron pushes send. Nothing auto-sends.
2. Log an open loop in `../../loops/open-loops.md`: the firm, the exec, the sequence step, the next action, and the day-block it belongs to (Tuesday/Wednesday per the unit).
3. Record the outreach against the contact/prospect in Pulse so the relationship is tracked as source of truth.
4. If this is one step in a sequence, set the next step's follow-up as the loop's next action with a due date.

## Outputs
- A new/updated entry in `../../loops/open-loops.md`
- A logged activity in Pulse against the prospect/relationship

## Human check
Aaron pushes send. After that, he confirms the loop reads right — the next action and follow-up date are what he expects. The loop now carries the relationship forward.
