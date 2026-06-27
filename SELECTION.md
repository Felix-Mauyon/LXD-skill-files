# SELECTION — How to pick the one angle to send

_The criteria the "Select Best Angle" step uses to choose ONE of the four candidate drafts to actually send. Fetched at run time, like SKILL.md and ABOUT_DAVID.md. The weekly retro proposes changes to this file as David reacts to real picks._

## The task

You are given the FOUR finished candidate outreach emails written for a single contact (each tied to one angle: career_arc, recent_activity, company_strategy, or personal_shared_context). Choose the **single best one to send**. Do not rewrite any email — only choose.

## Selection criteria, in priority order

1. **Prefer professional or public grounding.** The strongest angle is built on something professional or publicly visible: the contact's career arc, their company's strategy, something they posted or shared publicly, or a clearly professional shared context (a conference, an alma mater, a shared professional community or employer).

2. **Hard guardrail — not too personal.** NEVER choose an angle that leans on the contact's **private life** — family, children, home, health, religion, or any personal detail that isn't part of their professional/public footprint — even when that detail is present in the dossier and would make a "warm" opener. A `personal_shared_context` angle is eligible **only if** its shared context is itself professional or public (e.g. "we were both at ASU+GSV," "we both came up through Teach For America"). If its warmth comes from private life, **disqualify it.**

   _Example of what to reject: an angle whose hook or PS is about the contact's kid, family, or home life. Too personal — do not send it, regardless of how specific it is._

3. **Among what remains, pick the most specific and genuine connection.** Favor a real two-way connection (a point where David's world authentically intersects the contact's) over a generic or one-sided observation. Reject boilerplate.

4. **Respect the integrity rules.** Do not choose an angle that misattributes reposted/amplified content as something the contact authored or "said," or that relies on a detail the dossier flagged for verification.

## Tie-breakers and fallback

- If two eligible angles are close, prefer the one with the more concrete, verifiable professional hook.
- If **all four** lean on private life or are weak, do not force the personal one through — fall back to the strongest of `company_strategy` or `career_arc`, which are the safest professional defaults.

## Output

Return JSON only, no commentary:

```json
{
  "chosen_angle_type": "career_arc | recent_activity | company_strategy | personal_shared_context",
  "chosen_angle_name": "the angle_name of the chosen draft, copied exactly",
  "reason": "one sentence: why this one, and (if relevant) which angles were disqualified as too personal"
}
```
