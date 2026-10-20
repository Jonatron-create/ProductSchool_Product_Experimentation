# The Validation · FinWise

> Module 5 · Experimentation Methods. The experiment brief that tests the bet.

## Method

**Method:** A/B Test

**Why:** the question is causal: does saving a plan make people come back? We control the experience, the change is easy to switch off, and about 235 trial users a month reach a what-if, which is enough to power a test in under 4 months. A standard A/B test answers it. Nothing more complex earns its cost.

_____

## Hypothesis + primary metric

If trial users who run a what-if can save it as a plan, then see plan vs. actual and get alerts before the events that affect it, then more of them will come back to FinWise on their own a month later, because the plan keeps changing, so their question never stays answered.

**Primary metric:** unprompted return rate, days 31–60. That's the % of users who open FinWise at least once in days 31–60 after their first what-if, in a session not started from a FinWise email or notification., target: Target: from about 20% to 28% or more (+8 points).

_Experiment: Saved plans, EXP-01, The business objective: stop FinWise losing customers faster than it gains them. Right now 60% of paid customers leave within a year, and 2.5 churn for every new one. The aim is to lift one-year retention above today’s 40%.

This experiment’s objective: find out whether saved plans cause more users to keep coming back after their first question is answered. Success means unprompted returns in days 31–60 rise from about 20% to at least 28% in the variant compared with control, with no increase in notification opt-outs._

_Testing We’re testing one change against today’s experience. When a trial user runs their first what-if, the variant turns it from a one-off answer into an ongoing plan. on The target segment is new trial users who run their first what-if on their own connected data during their 2-week trial. That’s about 235 users a month: roughly 48% of the ~490 monthly trials.. Current experience: a 2-week reverse trial with full premium features, then the free tier. A what-if shows its answer once and can’t be saved, and nothing follows it up. Emails and notifications stay exactly as they are today.._

_Predicted outcome: We predict that unprompted returns in days 31–60 rise from about 20% in control to 28% or more in the variant, an increase of at least 8 points, with notification opt-outs no more than 2 points above control.. If successful: Save rate of at least 15% by the early check on 5 January. Below that, users don’t want plans, and the main result won’t move.
The lift comes from users who save a plan. Variant users who never save should return at about the control rate. If the whole variant group lifts evenly, something other than plans is driving it, most likely the extra alerts acting as a nudge.
Time to first forecast doesn’t change. The save prompt comes after the Aha moment, so it shouldn’t slow it.
Later: better 6-month paid retention in the 10% holdout after launch. This is the outcome we actually care about.. If unsuccessful: An unsuccessful result is one where the variant doesn’t lift unprompted returns by 8 points or more, or where it does but the guardrail fails. The reason it fails changes what we do next.._

_____

## Guardrail + read date

- **Guardrail:** notification opt-out rate. The variant may be no more than 2 points above control. Event alerts are the part most likely to backfire as spam, and a user who mutes FinWise has turned off the trigger the whole loop depends on.
- **Read date:** 60 days after the last user enrols. No early calls on the primary metric.

_____
