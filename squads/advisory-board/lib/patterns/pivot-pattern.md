# Pivot Pattern

## Pattern Name

Pivot — structured redirection of strategy, product, or business model when evidence shows the current path will not reach the destination, but the core insight or asset has value applied differently.

## When to Use

- Core metrics are persistently below targets despite strong execution (the thesis is wrong, not the effort).
- Customer feedback consistently points toward a different value proposition than the one being built.
- A new market opportunity has emerged that the team's existing capabilities can serve better.
- The business model is not working but the product has engaged users (monetization pivot).
- The product is not gaining traction but the underlying technology has alternative applications (technology pivot).
- Runway is shrinking and the current trajectory does not reach sustainability.

Do NOT use when:
- Execution problems are being misdiagnosed as strategy problems (fix execution first).
- The team is simply impatient — meaningful strategies need time to compound.
- The pivot is driven by a shiny new idea rather than evidence against the current path.
- Use `kill-decision-pattern.md` if no viable pivot target exists.

## Structure

```
1. DIAGNOSE  → Confirm the current path is failing and understand why
2. PRESERVE  → Identify what is working and must be carried forward
3. DISCOVER  → Generate and evaluate pivot directions
4. SELECT    → Choose the pivot direction with the best evidence
5. PLAN      → Design the pivot with speed and clarity
6. EXECUTE   → Move decisively with the full team committed
```

## Steps

### Step 1: Diagnose the Current State
- Assemble the evidence that the current path is failing:
  - Quantitative: metrics trending below targets, unit economics not converging, growth decelerating.
  - Qualitative: customer feedback themes, team morale signals, competitive dynamics.
- Distinguish between three failure modes:
  - **Product-market fit failure:** The product does not solve a problem people will pay for.
  - **Market timing failure:** The market is not ready or has already been won.
  - **Business model failure:** The product works but the economics do not.
- Be brutally honest. The hardest part of a pivot is admitting the current path is wrong. Partial honesty leads to partial pivots, which are worse than no pivot at all.

### Step 2: Identify What to Preserve
- Pivots are not restarts. Identify the assets worth carrying forward:
  - **Team:** Who has skills and motivation that transfer to the new direction.
  - **Technology:** What technical infrastructure, IP, or capabilities can be repurposed.
  - **Customers:** Which existing users or customers would follow to the new direction.
  - **Relationships:** Partnerships, investor relationships, brand equity.
  - **Knowledge:** Customer insights, market understanding, domain expertise.
  - **Revenue:** Any existing revenue streams that can sustain operations during the pivot.
- What to leave behind: features built for the old thesis, partnerships tied to the old strategy, team members whose skills do not transfer (handle with care and generosity).

### Step 3: Generate Pivot Directions
- Use structured ideation, not brainstorming:
  - **Customer pivot:** Same product, different customer segment.
  - **Problem pivot:** Same customer, different problem.
  - **Solution pivot:** Same problem, different solution approach.
  - **Channel pivot:** Same product, different distribution method.
  - **Revenue model pivot:** Same product and customer, different monetization.
  - **Technology pivot:** Repurpose core technology for a different application.
  - **Platform pivot:** Convert a single application into a platform (or vice versa).
- For each direction, answer:
  - What evidence supports this direction? (Not "I think" but "We observed that...")
  - What is the smallest experiment that could validate or invalidate this direction?
  - How much of our preserved assets does this direction leverage?
  - What is the time to first meaningful signal?

### Step 4: Select the Pivot Direction
- Score each direction on:
  - **Evidence strength:** How strong is the signal pointing to this direction (1-5).
  - **Asset leverage:** How much of what we have built can be repurposed (1-5).
  - **Market size:** Is the destination market large enough to justify the company (1-5).
  - **Time to validation:** How quickly can we get a definitive signal (1-5, where 5 is fastest).
  - **Team excitement:** Does the team have energy for this direction (1-5).
- The winning direction should score highest on evidence strength and time to validation. Team excitement matters but should not override evidence.
- Apply the "disagree and commit" pattern if the leadership team is split. Commitment to one direction beats half-hearted pursuit of two.

### Step 5: Plan the Pivot
- Design the pivot to be fast and focused:
  - **Pivot brief:** One-page document covering: where we are, where we are going, what we are preserving, what we are leaving behind, first 30-day plan.
  - **Resource reallocation:** Who moves to what, effective when.
  - **Communication plan:** How the pivot is communicated to team, investors, customers, and partners.
  - **Minimum viable pivot:** The smallest version of the new direction that produces a meaningful signal.
  - **Validation criteria:** What must be true within 60-90 days for the pivot to be confirmed.
  - **Abort criteria:** What signals would indicate the pivot direction is also wrong.
- Do not over-plan. A pivot plan longer than 2 pages is stalling, not planning.

### Step 6: Execute the Pivot
- Move within 1-2 weeks of the decision. Pivots lose momentum the longer they take to start.
- Communicate with radical honesty: "We learned that X is not working. We are redirecting to Y because of evidence Z."
- Preserve team dignity: the old direction was a reasonable bet that did not pay off, not a mistake.
- Monitor validation criteria weekly. If the pivot direction shows strong early signal, accelerate. If it shows weak signal, assess whether to adjust or abort.
- Update all registries: decision registry, experiment registry, lessons learned.

## Anti-Patterns

| Anti-Pattern | Description | Consequence |
|-------------|-------------|-------------|
| Pivot without diagnosis | Jumping to a new direction without understanding why the old one failed | The same failure mode reappears in the new direction |
| Partial pivot | Half-committing to the new direction while maintaining the old | Resources are split; neither direction succeeds |
| Pivot of the week | Changing direction so frequently that no strategy gets a fair test | Team exhaustion; loss of credibility with investors and customers |
| Ego-driven pivot resistance | Founder or leader refuses to pivot because the current direction was "their idea" | Company runs out of runway pursuing a disproven thesis |
| Pivot without communication | Direction changes without telling the team, customers, or investors | Confusion, broken trust, misaligned execution |
| Restart disguised as pivot | Abandoning everything and starting fresh while calling it a pivot | Wastes the assets that could have been leveraged |

## Examples

### Example 1: Customer Segment Pivot

**Diagnosis:** B2C language learning app has 50K free users but conversion to paid is 0.3% (target was 3%). User interviews reveal individuals will not pay but HR departments are buying for employee teams.

**Preserve:** Core product, content library, team, 50K-user base for social proof.
**Leave behind:** B2C marketing spend, consumer brand positioning, app store optimization effort.

**Pivot direction:** B2B2C — sell to companies for employee development. Evidence: 8 inbound requests from HR teams in the last quarter. Time to signal: 60 days (pilot with 3 companies).

**Result:** 3 pilots closed in 45 days. Average contract: $15K/year. Pipeline of 22 companies by day 90. Pivot confirmed.

### Example 2: Revenue Model Pivot

**Diagnosis:** SaaS project management tool has strong engagement (daily active users growing 15% MoM) but churns at the free-to-paid boundary. Users love the product but will not pay $29/month.

**Preserve:** Product, user base, engagement metrics, engineering team.
**Leave behind:** Per-seat SaaS pricing model, sales team.

**Pivot direction:** Freemium with usage-based pricing. Core product free; charge for storage, integrations, and advanced analytics above thresholds.

**Result:** Paid conversion increased from 1.2% to 7.8%. Revenue per paying user decreased from $29 to $18/month but total revenue increased 4x due to volume. Unit economics turned positive at month 3.
