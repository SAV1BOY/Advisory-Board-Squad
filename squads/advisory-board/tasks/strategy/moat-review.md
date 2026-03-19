# Task: Moat Review

## Objective
Assess the strength and trajectory of the company's competitive moat across all relevant dimensions. Identify erosion risks and investment priorities to strengthen defensibility.

## Trigger
- Quarterly as part of the strategy review cycle
- When a competitor makes a significant move (funding round, product launch, acquisition)
- When customer churn increases unexpectedly
- When win rates decline against a specific competitor

## Agents Involved
- **Lead:** Strategy Lead / CEO
- **Support:** Product, Engineering, Sales, Customer Success
- **Advisory:** Board members with competitive strategy expertise


## Agent Assignment
> Routing: see `config.yaml → routing → moat-review`

- **Lead:** strategic-advisor (Peter Thiel)
- **Support:** capital-allocator (Charlie Munger), board-chair (Board Chair)

## Pre-Requisites
- [ ] Current moat tracker populated with latest data
- [ ] Competitive intelligence current
- [ ] Customer retention and win/loss data available
- [ ] Product usage and engagement data available

## Steps

1. **Data Collection (Days 1-5)**
   - Pull current metrics for each moat dimension from the moat-tracker template
   - Collect competitive intelligence: product launches, funding, hiring, partnerships
   - Gather customer switching data: who left, who considered leaving, why
   - Assess technology differentiation: time-to-replicate estimates, patent status, data advantage metrics

2. **Dimension-by-Dimension Assessment (Days 5-10)**
   - For each moat type (network effects, switching costs, scale economies, brand, proprietary tech, data advantage):
     - Score current strength (1-10) with supporting evidence
     - Assess trend: strengthening, stable, or weakening
     - Identify the #1 threat to this moat dimension
     - Identify the #1 investment that would strengthen this dimension
   - Compare scores to last review period and explain changes

3. **Competitive Benchmarking (Days 8-12)**
   - Score each significant competitor on the same moat dimensions
   - Identify where competitors are stronger and where we have advantage
   - Assess competitor trajectory: are they building moat faster or slower than us?
   - Identify any competitor with a strengthening moat that could become a dominant threat

4. **Investment Prioritization (Days 12-15)**
   - Rank moat dimensions by: importance to our strategy, current gap, investment required, time to impact
   - Propose specific investments to strengthen the top 2-3 moat dimensions
   - Estimate cost and timeline for each investment
   - Define success metrics for each moat-strengthening initiative

5. **Board Presentation (Day 15-20)**
   - Update the moat tracker dashboard
   - Prepare a moat review brief highlighting changes, threats, and investment recommendations
   - Present at the quarterly strategy discussion or dedicated moat review session
   - Capture board direction on moat investment priorities

## Frameworks to Apply
- **7 Powers (Hamilton Helmer):** Scale economies, network effects, switching costs, counter-positioning, cornered resource, process power, branding
- **Moat Erosion Analysis:** For each moat dimension, identify specific mechanisms that could erode it
- **Competitive Response Modeling:** For each investment, predict how competitors will respond

## Checklists

### Review Quality Gate
- [ ] All relevant moat dimensions assessed with data (not just opinion)
- [ ] Competitor benchmarking uses observable evidence
- [ ] Erosion risks are specific (not generic "competition increases")
- [ ] Investment recommendations include cost, timeline, and success metrics
- [ ] Customer perspective included (not just internal view)
- [ ] Board has clear decision to make or direction to give

## Output
- Updated moat tracker dashboard
- Moat review brief for board
- Investment recommendations with prioritization
- Competitive moat comparison matrix

## Handoffs
- Investment decisions feed into capital-allocation-review.md
- Competitive insights update the competitive-landscape-report template
- Product implications feed into product-strategy-review.md

## Metrics
| Metric | Target | Measurement |
|---|---|---|
| Moat dimensions assessed | 100% of relevant dimensions | Tracker completeness |
| Data freshness | All metrics <90 days old | Data timestamp review |
| Competitor coverage | All Tier 1 competitors benchmarked | Tracker review |
| Investment recommendations actioned | >60% of board-approved recommendations funded | Action tracking |
| Overall moat score trend | Stable or improving YoY | Annual comparison |
