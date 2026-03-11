# Annual Planning Pattern

## Pattern Name

Annual Strategic Planning Cycle — a structured approach to setting annual strategic priorities, resource allocation, and operating plans that connects board-level strategy to quarterly execution while maintaining adaptability to changing conditions.

## When to Use

- Every year, 8-12 weeks before the start of the new fiscal year, to set the annual plan.
- When the company is transitioning between stages (seed to growth, growth to scale) and needs a comprehensive planning reset.
- After a major strategic pivot, acquisition, or leadership change that requires replanning.
- When the current year's plan has been materially invalidated by market conditions.

Do NOT use when:
- The company is pre-product-market-fit — planning in 12-month cycles is premature; use 90-day sprint cycles instead.
- Mid-year, unless a triggering event makes the current plan irrelevant. Mid-year adjustments should use the quarterly review process, not a full annual replanning exercise.

## Structure

```
1. REFLECT    → Assess the prior year's performance and learnings (Week 1-2)
2. SCAN       → Analyze external environment and internal capabilities (Week 2-4)
3. PRIORITIZE → Select 3-5 strategic priorities for the year (Week 4-6)
4. RESOURCE   → Allocate people, capital, and leadership attention (Week 6-8)
5. PLAN       → Build quarterly operating plans with milestones (Week 8-10)
6. ALIGN      → Board review, team alignment, and communication (Week 10-12)
```

## Steps

### Step 1: Reflect on the Prior Year (Weeks 1-2)

**Inputs:** Prior year's strategic plan, OKR/goal achievement data, financial actuals vs. plan, customer and employee survey results.

- **Performance review:** For each priority from the prior year, assess: achieved, partially achieved, or not achieved. For each, document why.
- **Assumption audit:** Which assumptions from last year's plan proved correct? Which were wrong? What did we learn that should change our thinking?
- **Wins to amplify:** What worked well that should be continued or expanded?
- **Failures to learn from:** What did not work and what is the honest diagnosis? Use `lib/patterns/postmortem-pattern.md`.
- **Unplanned events:** What significant events occurred that were not in the plan? How did the company respond? What does this tell us about our adaptability?

**Board role:** Review the reflection summary. Challenge management's interpretation of results — the tendency is to over-credit internal action for wins and over-blame external forces for failures.

### Step 2: Environmental and Capability Scan (Weeks 2-4)

**External scan:**
- **Market trends:** Use `data/research/` files relevant to the company's sector for industry benchmarks and trend data.
- **Competitive landscape:** Update competitive intelligence using `data/research/competitive-intelligence-template.md`. Identify competitive moves expected in the next 12 months.
- **Customer signals:** Aggregate customer feedback themes, NPS trends, churn reasons, and expansion patterns.
- **Regulatory and macro environment:** Identify regulatory changes, economic conditions, or macro trends that affect planning assumptions.

**Internal scan:**
- **Capability assessment:** What can the company do well today? What capabilities are missing for the intended strategy?
- **Team assessment:** Headcount, skills, engagement levels, key person dependencies. Reference `data/research/talent-market-trends.md`.
- **Financial position:** Cash, runway, unit economics trajectory, capital efficiency. Reference `data/metrics/burn-rate-and-runway.md`.
- **Technology and product health:** Technical debt, platform scalability, product roadmap status.

**Board role:** Provide pattern recognition from other companies and industries. Challenge blind spots in the management team's environmental scan.

### Step 3: Select Strategic Priorities (Weeks 4-6)

- Generate candidate priorities from the reflection and scan outputs. Typically 8-15 candidates emerge.
- Evaluate each candidate against criteria:
  - **Strategic impact:** How much does this move the company toward its long-term vision?
  - **Feasibility:** Can we realistically accomplish this with available resources in 12 months?
  - **Urgency:** What is the cost of delay? Does this have a time window?
  - **Dependencies:** Does this enable or block other priorities?
- Select 3-5 priorities. The discipline is in what is excluded. Use `lib/components/strategy-blocks.md` Block 3 to document what the company will NOT do.
- For each priority, define:
  - **Outcome statement:** What does success look like in 12 months? (Measurable, specific)
  - **Key assumptions:** What must be true for this priority to succeed?
  - **Owner:** Single accountable executive
  - **Kill/pivot triggers:** Under what conditions would we abandon or redirect this priority mid-year?

**Board role:** Challenge the priority list. Ask: "If you could only do two of these five, which two?" This reveals the true ranking and tests conviction.

### Step 4: Allocate Resources (Weeks 6-8)

- Map each priority to required resources:
  - **People:** Headcount and specific talent by priority. Identify gaps requiring hiring.
  - **Capital:** Budget allocation by priority. Include a 10-15% strategic reserve for mid-year opportunities.
  - **Leadership attention:** Which executive owns each priority? No executive should own more than 2 priorities.
- Perform the "strategy reveals budget" test: does the budget allocation match the stated priorities? If Priority #1 receives only 10% of resources, it is not actually Priority #1.
- Build the financial plan: revenue forecast, cost plan, hiring plan, cash flow projection.

**Board role:** Verify resource-strategy alignment. Review the financial plan and stress-test assumptions. Ensure runway is sufficient to execute the plan.

### Step 5: Build Quarterly Operating Plans (Weeks 8-10)

- Decompose each annual priority into quarterly milestones.
- For Q1: detailed operating plan with specific initiatives, owners, and success metrics.
- For Q2-Q4: directional milestones with the understanding that plans will be refined as Q1 learning emerges.
- Establish the quarterly review rhythm:
  - End of each quarter: performance review against milestones, plan adjustment for next quarter.
  - Quarterly board meeting: strategic priority progress review with go/no-go decisions.

### Step 6: Board Review and Team Alignment (Weeks 10-12)

- **Board review:** Present the full annual plan to the board for feedback and approval. Include: reflection summary, environmental scan highlights, strategic priorities, resource allocation, financial plan, and Q1 operating plan.
- **Team alignment:** All-hands presentation of the annual plan to the full company. Use `lib/patterns/stakeholder-communication-pattern.md` to structure the communication.
- **Documentation:** Finalize the annual plan document and distribute to all relevant stakeholders.

## Anti-Patterns

| Anti-Pattern | Description | Consequence |
|-------------|-------------|-------------|
| Planning theater | Elaborate planning process that produces a document nobody references | Wasted leadership time; plan and execution diverge immediately |
| Annual rigidity | Treating the annual plan as immutable for 12 months | Fails to adapt to changing conditions; opportunity cost |
| Bottom-up aggregation | Letting each team set goals independently and aggregating into a "plan" | No strategic coherence; resource conflicts; everything is "priority" |
| Everything is P0 | Refusing to make tradeoffs; 10+ "strategic priorities" | Resource fragmentation; nothing gets done well |
| Skipping reflection | Jumping to new priorities without learning from the prior year | Repeating mistakes; missing compounding opportunities |

## Related Patterns

- `lib/components/strategy-blocks.md` — structural blocks for strategy documents
- `lib/patterns/stakeholder-communication-pattern.md` — for communicating the plan to stakeholders
- `lib/patterns/kill-decision-pattern.md` — for abandoning priorities that are not working mid-year
- `data/metrics/strategic-alignment-score.md` — metric tracking execution against strategic priorities
- `data/metrics/forecast-accuracy.md` — metric tracking planning accuracy over time
