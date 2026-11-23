# The value of a reversible change

**Aaron Michael Weis** · Oneiron Holdings LLC · [ORCID](https://orcid.org/0009-0002-1906-148X)  
Concept paper · source draft dated 10 November 2026 · public research edition v0.1.0

## Abstract

A tool can produce a first draft in seconds and still make the whole job take longer. Preparing the request, checking the output, correcting it, and recovering from an unwanted change all consume time. This paper proposes measuring the labor for one accepted, reversible change. An illustrative calculation separates ongoing costs from setup. The example is arithmetic with assumed inputs. A matched-task study would be needed to establish how much time a real team saves.

## The unit of work

Start with an artifact, a requested modification and a written acceptance rule. For a design task, that might mean changing one region in an illustration while preserving the rest. Record the initial state and identify how the operator could return to it. This makes an unsuccessful change observable. An output can satisfy the visible request and still leave the operator unable to recover the original.

The basic comparison is the complete baseline task against the complete assisted task. Count active minutes in preparation, production, review, correction, intervention, and rework once each. Keep elapsed waiting time as a separate quantity if it matters to the operator. Use the same acceptance rule for both conditions. Record whether the requested work is correct, whether recovery is demonstrated, and whether the operator needed to intervene. Someone reviewing a failed trial should be able to see what happened.

## An illustrative calculation

For matched pair *i*, define *dᵢ* as baseline active minutes minus assisted active minutes. A negative value records extra work. If a team expects *N* comparable tasks per month, assigns labor a rate of *R* per hour, and expects an average difference of *d* minutes per task, the implied gross monthly value is *N × d × R / 60*. Subtract the other recurring monthly cost to obtain an ongoing estimate. Subtract setup cost separately when considering the first month.

| Quantity | Assumed or calculated value |
|---|---:|
| Monthly tasks | 20 |
| Difference in active time per task | 15 minutes |
| Labor rate | $60/hour |
| Gross monthly labor value | $300 |
| Other recurring monthly cost | $50 |
| One-time setup cost | $200 |
| Ongoing monthly net value | $250 |
| First-month net value | $50 |

Under precisely these assumptions the ongoing break-even difference is 2.5 minutes per task. Recovering setup in the first month raises it to 12.5 minutes. A different task mix, review burden, or labor cost changes the result. The numbers in the table were invented to show the accounting and do not estimate anyone’s earnings or savings.

## A test a team could actually run

Choose three to five matched task pairs with comparable expected outputs and review effort. Fix the acceptance and recovery rules before starting. Preserve the failed and slower cases. Report time for each pair alongside its acceptance result. An observer can then see whether apparent speed came from postponing work to the reviewer or skipping a recovery check.

With a small pilot, the observed minimum, mean, and maximum describe the tasks in the room. They do not give a confidence interval or a reliable forecast for next month. A useful adverse result would be a consistent drop in production time coupled with more correction effort or failed recoveries. It would direct attention to the part of the workflow that needs work.

## Contributions and scope

Aaron Michael Weis developed the research question, measure and illustrative scenario. The original concept draft was prepared with AI assistance. Codex edited this paper-only edition and checked the arithmetic. The paper makes no measured productivity or demand claim. [Paper license](LICENSE)
