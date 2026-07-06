---
name: david-outreach
description: "Use this skill whenever David asks to draft, write, revise, or compose any email, outreach message, intro request, follow-up, LinkedIn post, or community post in David's own voice. Triggers: cold outreach to trade notes / compare observations, double opt-in introductions, warm follow-ups, community posts for Fractionals United / FOHE / Angel Squad, event/conference pre-outreach. Trigger phrases: 'draft an email', 'write a message', 'intro request', 'follow up with', 'reach out to', 'write a cold email', 'apply the playbook', 'draft something for [name]', 'outreach to [name]'. Also trigger when David provides a name/company to reach out to, or mentions preparing for a conference. Do NOT use for client-voice emails — use the client-outreach skill for those."
---
 
# David Outreach Skill
 
All outreach sent in David's own voice. For emails sent as/for clients, use the `client-outreach` skill.
 
---
 
## How the Four Reference Files Work Together
 
You have four reference files that together replace 80% of the cognitive load in outreach. Load them in this order:
 
| File | Answers | Load when |
|---|---|---|
| `facts.md` | "What do I have in common with this person?" | Always for P.S. construction and connection hooks |
| `playbook.md` | "How do I write the email?" | Always — house format, rules, voice, tracker |
| `pov-inventory.md` | "What's the angle?" | Always — pick one POV per email |
| `email-examples.md` | "Does this feel right?" | When calibrating tone or uncertain about format |
 
**Read all four files before drafting any email.** They are short. This takes 2 minutes. It prevents the default mistakes.
 
---
 
## The Natural Workflow
 
For every outreach request, follow this sequence:
 
1. **Research the recipient** (4-step process from playbook.md)
   - Find LinkedIn, session title, recent posts, language they use
   - Find email: Google "[Name] [Org] email" + RocketReach + org format inference
2. **Pick a POV from pov-inventory.md** that matches their world (one max, two if directly connected)
3. **Find a connection point from facts.md** for the P.S.
4. **Draft using the playbook anatomy** from playbook.md
5. **Cut to ~210 words** (hard cap 250)
6. **Read aloud test** — if it sounds like a marketer wrote it, cut more
7. **Send** or create Gmail draft
---
 
## Before You Draft: Key Defaults
 
Load `references/playbook.md` and check the "What Claude Gets Wrong" section. These are the corrections that fire every time:
 
- Target 210 words, not 280
- Two bullets, not three
- Bold proof points (stats, framework names), not bullet headers
- Lead with the direct ask, then the hook
- P.S. is personal only — never business
- Reach for the transformation stat (49% to 86%), not the volume stat (1,400 artifacts)
---
 
## Email Type Quick-Reference
 
| Situation | Type | Key files to load |
|---|---|---|
| Cold outreach, peer/senior leader, trade notes | Type 2: Thought Leadership Exchange | playbook.md + pov-inventory.md + facts.md |
| Introduction via mutual contact | Type 1: Double Opt-In Intro | playbook.md |
| Post-meeting follow-up | Type 3: Warm Follow-Up | playbook.md |
| Community/network post | Type 4: Community Post | playbook.md |
| Conference pre-outreach | Type 2 + Event Overlay | playbook.md (Event Overlay section) |
 
---
 
## Signature
 
**Standard:**
```
Best from Atlanta,
David Fu
https://www.linkedin.com/in/davidthefu/
https://www.learningbydesign.ai/
```
 
**With Penn GSE credential (higher ed audiences):**
```
Best from Atlanta,
David Fu
Adjunct, Penn Graduate School of Education
https://www.linkedin.com/in/davidthefu/
https://www.learningbydesign.ai/
```
 
**Casual (people he knows well):** just `David`
 
---
 
## CTA / Booking Links
 
- **ASU GSV 2026 (through April 16, 2026):** https://calendly.com/davidfu/asugsv2026
- **General:** https://calendly.com/davidfu/
---
 
## Gmail Integration
 
When David asks to put an email into Gmail:
1. Use `Gmail:gmail_create_draft`
2. Use `contentType: text/html` for formatting (bullets, links)
3. Check inbox via `Gmail:gmail_get_profile`
4. Confirm inbox before creating draft if there's a specific sender identity (david@learningbydesign.co vs. personal)
---
 
## Updating the Tracker
 
After every send and every reply, update the Active Outreach Tracker table in `references/playbook.md`. This is the conversion rate dataset — it's only useful if it's current.
 
---
 
## Updating the Facts File
 
When David pastes a CV, LinkedIn section, results, or new client data, parse it and add to `references/facts.md` in the appropriate section. Fill in TODO items as they come in. This file only improves if it's continuously updated.
 
---
 
## Updating the POV Inventory
 
When a new angle gets a meaningful reaction (reply, meeting, "tell me more"), add it to `references/pov-inventory.md` using the template at the bottom of that file. Don't add untested POVs.
 
---
 
## For client-voice emails
 
Use the separate `client-outreach` skill. This skill is strictly for emails sent as David Fu.
 
