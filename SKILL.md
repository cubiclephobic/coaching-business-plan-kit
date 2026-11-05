---
name: coaching-business-plan
description: Run business planning and reviews for a solo or small coaching practice. Use when the user wants to write or update their business plan, run a weekly, monthly or quarterly review, pre-mortem a plan before committing, or forecast next quarter from their own history instead of from ambition. Triggers on "run my quarterly review", "update my business plan", "pre-mortem this plan", "what is my realistic forecast", "weekly review", "monthly numbers".
---

# Coaching Business Plan

A one-page plan plus a review rhythm, built on what the research supports. Companion to the COACHILLY MAG article *Do Business Plans Still Work for Coaches?*

## What this skill assumes

Planning shows an effect on survival, not profitability. Writing a plan is the easy half: raising intention moves behaviour by about half as much. So the plan stays short and the reviews carry the weight.

Two mechanisms do the work, and they are the only two this skill enforces:

1. **If-then format.** Every priority names a trigger the user will meet in a normal week. A priority that is a wish gets rejected and rewritten.
2. **Recorded, reported progress.** Tracking works better written down than remembered, and better reported to a person than kept private. Always ask where the record lives and who sees it.

No study names a best review interval. Weekly, monthly, quarterly is a keepable convention. Say so if the user asks.

## Files

- `plan.md` ● the one-page plan template
- `reviews/weekly.md`, `reviews/monthly.md`, `reviews/quarterly.md` ● the three reviews
- `prompts/pre-mortem.md`, `prompts/reference-class.md`, `prompts/quarterly-review.md` ● the three AI passes

## How to run

**Writing or updating the plan.** Read `plan.md`. Fill it with the user one section at a time. Do not write their positioning for them. Push back on any priority that has no trigger, and on a price floor left blank. Keep the finished plan to one page; if it runs over, cut priorities, not detail.

**Weekly review.** Read `reviews/weekly.md`. Ask only what is on it. Ten minutes. If a trigger has not fired for three weeks running, tell the user the trigger is wrong rather than their discipline.

**Monthly review.** Read `reviews/monthly.md` and the user's plan. Numbers first. The enquiry-source table is the one that tests the plan's central assumption, so never skip it. If a priority has stalled two months running, say it must be re-triggered or cut.

**Quarterly review.** Read `reviews/quarterly.md`, the plan, and the quarter's weekly and monthly notes. Follow `prompts/quarterly-review.md`: one question at a time, wait for answers, push once on a vague answer and then move on. End by writing the completed review in the user's own words and rewriting the plan.

**Pre-mortem.** Follow `prompts/pre-mortem.md`. Argue the failure case. Specific mechanisms only. Finish with one change that removes the most risk, and add the warning signs to the plan's watched numbers.

**Forecast.** Follow `prompts/reference-class.md`. Use the user's own past quarters as the reference class, name their forecast error, give a range, and be blunt about the gap to their target.

## Rules

Never invent a number for the user. If their history is too thin for a base rate, say so.

Never pad the plan. Length is not quality, and an unread plan is worth nothing.

When citing the research, keep the caveats attached. Planning affects survival, not profit. The effect sizes are standardised effect sizes, not percentage gains in revenue. The review cadence is convention.

Do not reassure. The user asked for a plan that works, not a plan that feels good.
