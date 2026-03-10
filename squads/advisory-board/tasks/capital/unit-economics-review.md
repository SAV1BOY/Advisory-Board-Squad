# Task: Unit Economics Review

## Objective
Analyze the company's unit economics to ensure the business model is fundamentally sound and improving. Identify levers for improvement and alert the board to any concerning trends.

## Trigger
- Quarterly as part of the financial review cycle
- When CAC increases by more than 20% quarter-over-quarter
- When churn rate increases significantly
- Before any fundraise (investors will scrutinize unit economics)
- When considering a pricing change

## Agents Involved
- **Lead:** CFO
- **Support:** VP Sales (acquisition costs), VP Product (retention metrics), VP Customer Success (expansion and churn)
- **Advisory:** Board members with relevant operating experience

## Pre-Requisites
- [ ] Customer acquisition data by channel and cohort available
- [ ] Revenue retention data by cohort available
- [ ] Fully loaded cost data by function available
- [ ] Pricing data and discount patterns available

## Steps

1. **Data Assembly (Days 1-3)**
   - Calculate CAC by channel: paid, organic, referral, partner, outbound
   - Calculate LTV by segment, cohort, and channel
   - Calculate gross margin by product and customer segment
   - Calculate payback period by channel and segment
   - Pull retention curves by monthly/quarterly cohort

2. **Cohort Analysis (Days 3-5)**
   - Analyze retention by cohort: are newer cohorts retaining better or worse than older ones?
   - Analyze expansion revenue by cohort: are customers growing their spend over time?
   - Analyze churn reasons by cohort: are churn patterns changing?
   - Compare acquisition channel performance: which channels produce the highest-LTV customers?

3. **Trend and Benchmark Analysis (Days 5-7)**
   - Plot 6-quarter trends for all key unit economics metrics
   - Benchmark against industry comparables and best-in-class
   - Identify inflection points: where did metrics improve or deteriorate, and why?
   - Model forward trajectory: where will unit economics be in 4 quarters at current trends?

4. **Lever Identification (Days 7-9)**
   - For each metric below target, identify the top 3 improvement levers
   - Quantify the impact of each lever (if we improve X by Y%, what happens to unit economics?)
   - Assess feasibility and cost of pulling each lever
   - Prioritize levers by impact-to-effort ratio

5. **Board Report (Days 9-12)**
   - Prepare unit economics dashboard for the board scorecard
   - Highlight trends, benchmarks, and areas of concern or opportunity
   - Present improvement recommendations with expected impact
   - Flag any unit economics issues that affect strategic viability

## Frameworks to Apply
- **Cohort Analysis:** Measure by time-based cohorts to reveal true trajectory
- **Contribution Margin Waterfall:** Break down the path from gross revenue to contribution margin
- **Channel Efficiency:** Compare acquisition channels on fully-loaded LTV:CAC

## Checklists

### Quality Gate
- [ ] CAC is fully loaded (includes all sales, marketing, and onboarding costs)
- [ ] LTV uses actual retention data, not projections from assumed retention rates
- [ ] Cohort analysis covers at least 6 cohorts
- [ ] Metrics are segmented by meaningful dimensions (channel, segment, product)
- [ ] Trends are compared to benchmarks
- [ ] Improvement recommendations are quantified

## Output
- Unit Economics Dashboard update
- Cohort analysis report
- Trend and benchmark analysis
- Improvement recommendations with quantified impact

## Handoffs
- Pricing changes feed into product-strategy-review
- CAC issues feed into competitive-response or market-expansion decisions
- LTV issues feed into product and customer success priorities
- Overall unit economics health informs fundraising narrative and valuation

## Metrics
| Metric | Target | Measurement |
|---|---|---|
| LTV:CAC ratio | >3:1 | Quarterly calculation |
| CAC payback | <18 months | Quarterly calculation |
| Net revenue retention | >110% | Quarterly cohort analysis |
| Gross margin | Improving QoQ | Quarterly P&L |
| Contribution margin | Positive and improving | Quarterly analysis |
