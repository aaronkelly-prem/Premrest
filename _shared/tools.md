# Tools, scoping, and the wall

What Premrest connects to, how it is scoped, and the one rule that governs all of it.

## Connected tools

| Tool | Use | Scope / status |
|---|---|---|
| **Pulse** (MCP) | Contacts, prospects, leads, Nick's account spread, quotes, service orders, pricing | Source of truth for Premrest contacts and account activity. Connected. |
| **Firmable** (API) | Find target exec contacts — emails, mobiles | **Not connected yet.** Aaron enters the API key himself (see setup). Nick has a working Claude/Firmable setup to replicate. |
| **Gmail** | Read + draft email | **Premrest account only.** Needs authorising in connector settings before use. Never auto-send. |
| **Google Calendar** | Calendar management (Full role — see `weekly-blocks.md`) | See account note below. |
| **Slack** (premrest.slack.com) | Live reference for staff/service/hiring/accountability context, on request | Governed — see `governed/CONTEXT.md`. Live read when asked, not standing surveillance. |

Ignore Apollo, HubSpot, Attio. Google Drive and Canva are connected but not part of the Premrest tool set unless Aaron says otherwise — do not reach into them for Premrest work without a reason.

## The Google account note (read carefully)

The connected Google login can see three of Aaron's calendars: `aaron.kelly@premrest.com.au`, `aaron@queerfullymade.com`, and `psaaronkelly@gmail.com` (personal).

**This is intended, not a leak.** Aaron keeps the full calendar view because personal and Queerfully Made commitments land on his Premrest day and he needs to see them to plan. Visibility is for Aaron's insight only.

## The wall (non-negotiable)

The wall is about **content and messaging, not visibility.**

- Claude may **see** cross-account calendar entries so Aaron can plan his real day.
- Claude **never surfaces, references, names, or hints at** personal, Queerfully Made, or Let's Talk Media content in any Premrest output — no email, no draft, no calendar invite, no podcast note, no message, internal or external.
- When drafting anything that leaves the workspace, the content comes only from Premrest sources. Personal-side commitments may shape *when* Aaron is free; they are never *mentioned*.

Enforced for real by connector auth and folder scope, but the content wall above holds regardless of what a connector can technically see.

## The human gate

Claude writes full, ready-to-send drafts. **Nothing outbound sends without Aaron's review** — email, calendar invites, anything. Drafts wait for him to push send.
