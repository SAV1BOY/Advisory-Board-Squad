# Task: Pricing Strategy Review

## Objective
Review and optimize the company's pricing strategy to ensure it maximizes revenue capture, reflects the value delivered to customers, remains competitive, and supports the overall business strategy.

## Trigger
- Annual pricing review cycle (typically aligned with annual strategy refresh)
- Significant change in competitive pricing landscape
- New product launch or major feature release
- Customer churn analysis indicates pricing as a factor
- Unit economics review reveals margin concerns
- Market expansion into a new segment or geography

## Agents Involved
- **Lead:** CEO or CPO
- **Support:** CFO, Head of Sales, Head of Customer Success, Product Marketing
- **Advisory:** Board members with pricing, revenue, or market strategy expertise


## Agent Assignment
> Routing: see `config.yaml → routing → capital-allocation-review`

- **Lead:** capital-allocator (Charlie Munger)
- **Support:** strategic-advisor (Peter Thiel), growth-navigator (Naval Ravikant)
- **Review:** board-chair (Board Chair)

## Pre-Requisites
- [ ] Current pricing structure documented (all plans, tiers, add-ons, discounting policies)
- [ ] Revenue and margin data by plan, segment, and cohort
- [ ] Competitive pricing intelligence current
- [ ] Customer willingness-to-pay data (surveys, interviews, or revealed preference data)
- [ ] Churn and expansion revenue data with pricing-related attribution
- [ ] Unit economics by customer segment

## Steps

1. **Current State Analysis (Days 1-5)**
   - Document the complete current pricing architecture — plans, tiers, features, add-ons
   - Analyze revenue distribution across pricing tiers and customer segments
   - Calculate effective price per unit across segments (accounting for discounts)
   - Assess discount prevalence — how often and how much are sales teams discounting?
   - Review pricing-related customer feedback and churn reasons

2. **Value and Willingness-to-Pay Assessment (Days 5-10)**
   - Map features to customer value — which features drive purchasing decisions?
   - Analyze usage data — which features are most and least used by tier?
   - Assess willingness-to-pay through customer research (Van Westendorp, Gabor-Granger, or conjoint analysis)
   - Identify value gaps — areas where we deliver more value than we capture in price

3. **Competitive Benchmarking (Days 8-12)**
   - Map competitor pricing — models, price points, packaging, and positioning
   - Assess competitive positioning — are we priced as premium, mid-market, or value?
   - Identify pricing trends in the market — usage-based, PLG, hybrid models
   - Evaluate win/loss data for pricing-related patterns

4. **Pricing Model Optimization (Days 12-18)**
   - Develop 2-3 pricing scenarios — e.g., tier restructuring, metric change, packaging revision
   - Model revenue impact of each scenario across the customer base
   - Assess migration impact — how will existing customers be affected by changes?
   - Define the transition plan for existing customers (grandfathering, migration timeline)
   - Evaluate operational complexity of each pricing model

5. **Board Review and Approval (Days 18-25)**
   - Prepare the pricing strategy recommendation with financial modeling
   - Present trade-offs between revenue optimization, customer satisfaction, and competitive positioning
   - Obtain board direction on pricing strategy and any material changes
   - Define the implementation timeline and communication plan

## Frameworks to Apply
- **Value-Based Pricing:** Price based on customer value delivered, not cost-plus
- **Price Sensitivity Meter (Van Westendorp):** Determine acceptable price range
- **Packaging and Bundling Theory:** Good-Better-Best tier design
- **Price Elasticity Analysis:** Understand demand response to price changes

## Checklists

### Quality Gate
- [ ] Current pricing fully documented with revenue impact by tier
- [ ] Customer willingness-to-pay assessed with data (not assumptions)
- [ ] Competitive pricing benchmarked with current data
- [ ] Revenue impact modeled for all proposed changes (including downside scenarios)
- [ ] Migration plan for existing customers defined with churn risk assessment
- [ ] Board has reviewed and approved material pricing changes

## Output
- Pricing strategy document with recommendation
- Revenue impact model with sensitivity analysis
- Competitive pricing benchmark
- Customer migration plan (if pricing changes recommended)
- Updated pricing page and sales collateral (post-approval)

## Handoffs
- Revenue projections feed into capital-allocation-review and budget-review tasks
- Competitive pricing insights update competitive-landscape-report
- Customer impact assessment feeds into team-health-check (customer success)
- Pricing changes feed into go-to-market-review task

## Metrics
| Metric | Target | Measurement |
|---|---|---|
| Revenue per customer trend | Increasing YoY | Revenue analytics |
| Gross margin | At or above target | Financial reporting |
| Pricing-related churn | <[%] of total churn | Churn analysis |
| Average discount from list | <[%] | Sales analytics |
| Expansion revenue rate | >[%] of existing customers | Revenue analytics |
