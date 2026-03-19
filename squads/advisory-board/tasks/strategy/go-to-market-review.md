# Task: Go-to-Market Strategy Review

## Objective
Evaluate the effectiveness of the company's go-to-market strategy across sales, marketing, partnerships, and customer success. Identify what is working, what is not, and recommend adjustments to improve customer acquisition, expansion, and retention.

## Trigger
- Quarterly as part of the strategic review cycle
- When customer acquisition cost trends unfavorably for two consecutive quarters
- When win rates decline below target thresholds
- Before entering a new market segment or geography
- After a significant product launch requiring GTM adjustment
- When competitive dynamics shift materially

## Agents Involved
- **Lead:** CEO or CRO / Head of Sales
- **Support:** Head of Marketing, Head of Customer Success, Head of Partnerships, Product Marketing
- **Advisory:** Board members with GTM, sales, or market development expertise


## Agent Assignment
> Routing: see `config.yaml → routing → strategic-diagnosis`

- **Lead:** strategic-advisor (Peter Thiel)
- **Support:** growth-navigator (Naval Ravikant), partnership-broker (Reid Hoffman)
- **Review:** board-chair (Board Chair)

## Pre-Requisites
- [ ] Sales pipeline and conversion data current
- [ ] Marketing funnel metrics and attribution data available
- [ ] Customer acquisition cost (CAC) and lifetime value (LTV) data current
- [ ] Win/loss analysis up to date
- [ ] Customer segmentation and ICP definition current
- [ ] Partnership and channel performance data available
- [ ] Competitive positioning and messaging assessment current

## Steps

1. **Funnel and Pipeline Analysis (Days 1-5)**
   - Map the complete customer acquisition funnel — awareness through close
   - Analyze conversion rates at each stage and identify the biggest drop-off points
   - Assess pipeline coverage ratio against revenue targets
   - Review sales cycle length trends by segment and deal size
   - Evaluate lead source effectiveness and marketing channel ROI

2. **Unit Economics Review (Days 5-8)**
   - Calculate blended and segmented CAC (by channel, segment, deal size)
   - Calculate LTV by customer segment and cohort
   - Assess LTV:CAC ratio and payback period trends
   - Compare unit economics to industry benchmarks
   - Identify segments where economics are strongest and weakest

3. **Win/Loss and Competitive Analysis (Days 8-12)**
   - Review win/loss data — reasons for wins, losses, and no-decisions
   - Assess competitive positioning — where we win and where we lose
   - Evaluate messaging effectiveness — does our value proposition resonate?
   - Identify objection patterns and gaps in sales enablement
   - Review competitive battle cards and their effectiveness

4. **Channel and Partnership Assessment (Days 10-14)**
   - Evaluate direct vs. channel/partner sales mix and effectiveness
   - Assess partnership pipeline and partner engagement levels
   - Review partner economics — margins, incentives, and sustainability
   - Identify new channel or partnership opportunities
   - Assess self-serve / PLG motion effectiveness (if applicable)

5. **Customer Expansion and Retention Review (Days 12-16)**
   - Analyze net revenue retention and expansion revenue trends
   - Review upsell and cross-sell conversion rates
   - Assess customer success effectiveness — time to value, health scores, churn predictors
   - Evaluate customer advocacy — referrals, case studies, community engagement
   - Identify the highest-leverage retention and expansion initiatives

6. **GTM Strategy Recommendations (Days 16-20)**
   - Synthesize findings into 3-5 actionable GTM recommendations
   - Model the revenue impact of proposed changes
   - Define resource requirements and trade-offs for each recommendation
   - Align GTM recommendations with the overall strategic plan
   - Prepare board briefing on GTM health and recommended adjustments

## Frameworks to Apply
- **SaaS Metrics Framework:** CAC, LTV, payback, NRR, magic number
- **Ideal Customer Profile (ICP) Alignment:** Score GTM activities against ICP fit
- **MEDDPICC or Similar:** Evaluate sales qualification rigor
- **Land and Expand:** Assess the effectiveness of the expansion motion

## Checklists

### Quality Gate
- [ ] Funnel analysis based on complete, accurate data (not anecdotal)
- [ ] Unit economics calculated by segment, not just blended averages
- [ ] Win/loss analysis includes customer voice, not just sales rep perspective
- [ ] Competitive positioning assessed with external data
- [ ] Recommendations include revenue impact modeling and resource requirements
- [ ] Board has clear view of GTM health and any strategic decisions needed

## Output
- GTM performance dashboard and analysis
- Win/loss analysis summary
- Unit economics report by segment
- GTM strategy recommendations with financial modeling
- Updated ICP and segmentation (if changes recommended)

## Handoffs
- Pricing recommendations feed into pricing-strategy-review task
- Resource requests feed into budget-review and capital-allocation-review tasks
- Competitive insights feed into competitive-response-plan and moat-review tasks
- Customer retention findings feed into team-health-check and culture-audit tasks
- Partnership recommendations feed into partner-eval and deal-terms-review tasks

## Metrics
| Metric | Target | Measurement |
|---|---|---|
| CAC payback period | <[N] months | Financial reporting |
| LTV:CAC ratio | >[N]x | Cohort analysis |
| Win rate (qualified pipeline) | >[%] | CRM data |
| Net revenue retention | >[%] | Revenue analytics |
| Sales cycle length | <[N] days | CRM data |
