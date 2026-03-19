# Task: Budget Review

## Objective
Review and approve the annual or quarterly operating budget to ensure spending aligns with strategic priorities, maintains financial health, and provides adequate runway. Identify areas of over- or under-investment and recommend reallocation.

## Trigger
- Annual budget cycle (typically Q4 for the following fiscal year)
- Quarterly budget reforecast and variance review
- Material deviation from approved budget (>10% in any category)
- Significant business change requiring budget reallocation (acquisition, restructuring, new product line)
- Cash position or runway falling below board-approved thresholds

## Agents Involved
- **Lead:** CFO
- **Support:** CEO, functional leaders (each presenting their budget area), FP&A lead
- **Advisory:** Board finance committee or full board (for annual budget approval)


## Agent Assignment
> Routing: see `config.yaml → routing → capital-allocation-review`

- **Lead:** capital-allocator (Charlie Munger)
- **Support:** board-chair (Board Chair), strategic-advisor (Peter Thiel)
- **Review:** risk-sentinel (Ray Dalio)

## Pre-Requisites
- [ ] Prior period actuals finalized and reconciled
- [ ] Revenue forecast current with scenario analysis
- [ ] Departmental budget requests compiled with justifications
- [ ] Strategic priority list current (from annual strategy refresh)
- [ ] Headcount plan aligned with functional leaders
- [ ] Capital expenditure requests compiled
- [ ] Cash position and runway model current

## Steps

1. **Revenue and Forecast Review (Days 1-3)**
   - Review revenue actuals vs. prior forecast and budget
   - Assess pipeline and leading indicators for forward revenue confidence
   - Develop revenue scenarios — base, upside, downside — with probability weights
   - Identify key assumptions and risks in the revenue forecast
   - Compare forecast methodology accuracy over time

2. **Departmental Budget Review (Days 3-8)**
   - Review each department's budget request against strategic priorities
   - Assess budget vs. actual performance for the prior period by department
   - Challenge each material line item — is this spend necessary and optimally sized?
   - Identify zero-based budget opportunities — spend that continues by inertia rather than strategic value
   - Evaluate headcount requests against productivity metrics and strategic needs

3. **Investment and CapEx Review (Days 6-10)**
   - Review all capital expenditure and investment requests
   - Prioritize investments by strategic alignment, ROI, and risk
   - Assess build vs. buy decisions for significant investments
   - Ensure innovation portfolio allocation aligns with board-approved targets
   - Evaluate multi-year investment commitments and their flexibility

4. **Cash and Runway Analysis (Days 8-12)**
   - Model cash position under each revenue and spending scenario
   - Calculate runway under base, optimistic, and conservative scenarios
   - Verify compliance with board-approved minimum runway thresholds
   - Identify triggers for fundraising or spending cuts
   - Assess working capital requirements and seasonal cash flow patterns

5. **Budget Consolidation and Optimization (Days 10-15)**
   - Consolidate departmental budgets into a company-level financial plan
   - Map spend to strategic priorities — identify alignment gaps
   - Develop 2-3 budget scenarios if total requests exceed available resources
   - Identify specific reallocation recommendations with trade-offs
   - Prepare the budget presentation for board review

6. **Board Approval (Days 15-20)**
   - Present the proposed budget with strategic alignment narrative
   - Highlight key trade-offs and decisions for board input
   - Obtain board approval for the annual budget and delegation thresholds
   - Document approved budget, conditions, and variance reporting requirements

## Frameworks to Apply
- **Zero-Based Budgeting:** Challenge every line item from zero, not just incremental changes
- **Strategic Alignment Mapping:** Every dollar mapped to a strategic priority
- **Scenario Planning:** Budget built for flexibility across revenue scenarios
- **Rule of 40:** Balance growth rate and profit margin for SaaS companies

## Checklists

### Quality Gate
- [ ] Revenue forecast includes scenario analysis with explicit assumptions
- [ ] Each departmental budget reviewed against strategic priorities and prior performance
- [ ] Investment requests prioritized with ROI and strategic alignment scoring
- [ ] Runway analysis completed under multiple scenarios
- [ ] Budget maps to strategic priorities with alignment percentage calculated
- [ ] Board-approved minimum thresholds for cash reserves maintained
- [ ] Delegation authority and variance reporting rules defined

## Output
- Approved annual or quarterly budget
- Revenue forecast with scenarios
- Cash and runway model
- Strategic alignment scorecard (spend vs. priorities)
- Variance reporting framework and thresholds
- Board approval recorded in decision log

## Handoffs
- Approved budget cascades to all departmental leaders for execution
- Revenue assumptions feed into capital-allocation-review task
- Headcount plan feeds into exec-hiring and team-health-check tasks
- Investment priorities feed into execution-30-60-90 plans
- Runway concerns feed into fundraising-plan task
- Innovation allocation feeds into innovation-portfolio-review task

## Metrics
| Metric | Target | Measurement |
|---|---|---|
| Budget approval timing | Approved before fiscal period start | Calendar |
| Budget variance (aggregate) | Within 10% of approved budget | Monthly financial reporting |
| Revenue forecast accuracy | Within 15% of actuals | Quarterly comparison |
| Strategic alignment ratio | >80% of spend maps to top priorities | Alignment audit |
| Runway maintenance | Always >6 months at current burn | Cash model |
