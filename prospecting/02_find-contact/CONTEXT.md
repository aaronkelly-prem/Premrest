# 02_find-contact — find the right firm-level exec

One job: for a chosen candidate firm, find the firm-level executive to approach and their contact details.

## Inputs
- Working (this run): ../01_spot-concentration/output/candidates-{date}.md (the chosen firm)
- Working (this run): Firmable — exec contacts, emails, mobiles for that firm
- Reference (every run): ../../_shared/prospecting-model.md (who counts as the right exec — firm-level, above account contacts)

Do NOT load: other candidate firms not chosen, drafting references (that is stage 03).

## Process
1. Take the firm Aaron approved in stage 01.
2. Use Firmable to find the right firm-level decision-maker — the exec who owns the partnership relationship, not an account or site contact.
3. Capture name, title, email, mobile, and why they are the right entry point.
4. Cross-check against Pulse so Aaron is not approaching someone already in an active Premrest relationship at cross purposes.

## Outputs
- contact-{firm}.md → output/  (person, title, email, mobile, why them, any Pulse context)

## Human check
Aaron confirms this is the right person to reach. If not, adjust the target before any drafting. The confirmed contact goes to stage 03.
