# Task: Pricing Model Review

## Objective
Evaluate the effectiveness of the current pricing model — its structure, metrics, and mechanics — to ensure it captures fair value, drives desired customer behavior, supports growth, and remains competitive. Distinct from pricing strategy review in that this focuses on the model architecture itself rather than specific price points.

## Trigger
- Annual review as part of the strategic planning cycle
- Unit economics trending unfavorably for two or more consecutive quarters
- Customer feedback indicating pricing model friction or confusion
- Competitive shift toward a different pricing model (e.g., industry moving to usage-based)
- Product evolution that makes the current pricing metric less relevant
- Expansion into a new segment where the current model may not fit

## Agents Involved
- **Lead:** CFO or CPO
- **Support:** Head of Sales, Head of Customer Success, Product Marketing, Data/Analytics team
- **Advisory:** Board members with pricing, revenue model, or SaaS expertise


## Agent Assignment
> Routing: see `config.yaml → routing → capital-allocation-review`

- **Lead:** capital-allocator (Charlie Munger)
- **Support:** strategic-advisor (Peter Thiel), growth-navigator (Naval Ravikant)
- **Review:** board-chair (Board Chair)

## Pre-Requisites
- [ ] Current pricing model fully documented — metric, tiers, packaging, discounting rules
- [ ] Revenue data by pricing metric, tier, and segment
- [ ] Customer usage data mapped to pricing metric
- [ ] Churn and expansion data with pricing model attribution
- [ ] Competitive pricing model intelligence
- [ ] Customer feedback on pricing model (surveys, interviews, support tickets)

## Steps

1. **Model Architecture Assessment (Days 1-5)**
   - Document the current pricing model — what is the pricing metric (seats, usage, flat fee, hybrid)?
   - Assess how well the pricing metric aligns with customer value realization
   - Analyze the relationship between customer usage and what they pay — are high-value customers paying proportionally?
   - Evaluate model simplicity — can customers understand and predict their costs?
   - Review billing mechanics — frequency, transparency, flexibility

2. **Customer Behavior Analysis (Days 5-10)**
   - Analyze how the pricing model drives or inhibits customer adoption and usage
   - Identify gaming or workaround behaviors — are customers artificially managing usage to reduce cost?
   - Assess expansion friction — does the model naturally expand with customer growth?
   - Evaluate land motion — does the model enable easy initial adoption?
   - Review segment-specific model fit — does one model work across all segments?

3. **Financial Impact Assessment (Days 8-12)**
   - Model revenue under the current model vs. alternative models using actual customer data
   - Calculate revenue predictability — how volatile is revenue under the current model?
   - Assess revenue recognition implications of model changes
   - Evaluate billing and collection efficiency — DSO, failed payments, billing disputes
   - Model the transition costs and risks of a model change

4. **Alternative Model Evaluation (Days 12-18)**
   - Evaluate 2-3 alternative pricing models against current model
   - For each alternative: model revenue impact, customer impact, competitive positioning, and operational complexity
   - Assess hybrid models that combine elements (e.g., platform fee + usage)
   - Evaluate the transition path from current to proposed model
   - Assess infrastructure and tooling requirements for model changes

5. **Board Recommendation (Days 18-22)**
   - Prepare a recommendation with supporting analysis
   - Present the trade-offs between model options clearly
   - Define the migration strategy for existing customers if a model change is recommended
   - Obtain board direction on pricing model evolution
   - Define success metrics and review cadence for any approved changes

## Frameworks to Apply
- **Value Metric Alignment:** Ensure the pricing metric scales with the value customers receive
- **Pricing Model Canvas:** Evaluate who pays, what for, how much, and when
- **Land-Expand-Retain Analysis:** Assess model through the full customer lifecycle
- **Revenue Quality Assessment:** Predictability, retention, expansion characteristics

## Checklists

### Quality Gate
- [ ] Current model fully mapped with data on revenue by metric, tier, and segment
- [ ] Customer behavior under the current model analyzed with data
- [ ] Alternative models evaluated with financial modeling using actual customer data
- [ ] Customer migration plan defined for any proposed model change
- [ ] Revenue recognition and compliance implications reviewed
- [ ] Board has clear view of model effectiveness and any strategic decisions needed

## Output
- Pricing model assessment report
- Alternative model comparison with financial modeling
- Customer impact and migration analysis
- Pricing model recommendation with implementation roadmap
- Board briefing on pricing model health and proposed evolution

## Handoffs
- Model changes feed into pricing-strategy-review for price point optimization
- Revenue projections feed into budget-review and capital-allocation-review tasks
- Customer impact assessment feeds into team-health-check (customer success)
- Billing and infrastructure requirements feed into technology-stack-review
- Competitive model insights feed into competitive-response-plan

## Metrics
| Metric | Target | Measurement |
|---|---|---|
| Revenue predictability | Month-over-month variance <[%] | Financial reporting |
| Pricing metric alignment with value | Customer satisfaction with pricing model >4/5 | Customer survey |
| Expansion revenue from model mechanics | >[%] of customers naturally expand | Revenue analytics |
| Billing dispute rate | <[%] of invoices | Billing system |
| Time from model change to steady state | <[N] quarters | Revenue trend analysis |
