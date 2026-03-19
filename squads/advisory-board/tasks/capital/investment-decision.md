# Task: Investment Decision

## Objective
Evaluate a specific investment proposal (new product, market, technology, or capability) through the board's capital allocation lens. Ensure the investment is justified, well-structured, and properly governed.

## Trigger
- Any proposed investment exceeding management's delegated spending authority
- Any investment that creates a new ongoing cost commitment exceeding defined threshold
- Any investment that materially changes the company's strategic direction

## Agents Involved
- **Lead:** Investment proposer (functional leader or CEO)
- **Support:** CFO (financial analysis), Legal (contract review)
- **Advisory:** Board finance committee or full board


## Agent Assignment
> Routing: see `config.yaml → routing → investment-decision`

- **Lead:** capital-allocator (Charlie Munger)
- **Support:** board-chair (Board Chair), risk-sentinel (Ray Dalio), strategic-advisor (Peter Thiel)
- **Review:** ethics-compass (Yvon Chouinard)

## Pre-Requisites
- [ ] Business case developed with financial projections
- [ ] Alternative approaches evaluated (build vs. buy vs. partner)
- [ ] Runway impact assessed
- [ ] Technical feasibility confirmed (if applicable)

## Steps

1. **Business Case Preparation**
   - Proposer develops the investment thesis with quantified problem statement
   - Build financial model with revenue projections, cost structure, and sensitivity analysis
   - Identify and evaluate alternatives (minimum 3 options including do nothing)
   - CFO reviews model for accuracy, reasonableness, and cash impact

2. **Risk Assessment**
   - Identify execution, market, technology, and financial risks
   - Quantify maximum downside exposure (worst-case loss scenario)
   - Develop mitigation plans for top risks
   - Assess reversibility: what does it cost to unwind if the investment fails?

3. **Governance Structure Design**
   - Define phase gates with go/no-go criteria
   - Define kill criteria (conditions that trigger automatic pause)
   - Set reporting cadence (monthly to board or management, depending on size)
   - Define delegation: what decisions can management make within the investment vs. what returns to the board

4. **Board Presentation and Approval**
   - Prepare capital-allocation-memo using the template
   - Present at board meeting or submit for async approval
   - Board deliberates, asks questions, and decides
   - If approved: confirm budget, gates, reporting, and kill criteria

5. **Post-Approval Tracking**
   - Execution owner reports monthly against milestones and budget
   - Gate reviews at defined checkpoints
   - Board receives quarterly update as part of regular review
   - Any gate failure or kill criteria breach triggers immediate board notification

## Frameworks to Apply
- **NPV / IRR Analysis:** Standard financial return metrics
- **Real Options:** Value of optionality and staged investment
- **Pre-Mortem:** Before approving, assume failure and identify likely causes

## Checklists

### Quality Gate
- [ ] Financial model includes sensitivity analysis across 4 scenarios
- [ ] Maximum downside exposure quantified
- [ ] At least 3 options evaluated (including do nothing)
- [ ] Phase gates with measurable criteria defined
- [ ] Kill criteria established
- [ ] Cash runway impact modeled
- [ ] Delegation authority clear

## Output
- Capital Allocation Memo (approved or rejected)
- Decision log entry
- Investment tracking dashboard (post-approval)
- Gate review schedule

## Handoffs
- Approved investments enter execution-30-60-90 tracking
- Financial impact updates the runway model monthly
- Outcomes feed into capital-allocation-review at quarter end

## Metrics
| Metric | Target | Measurement |
|---|---|---|
| Decision timeline | <30 days from proposal to board decision | Calendar |
| Financial model accuracy | Actuals within 30% of base case at 12 months | Variance analysis |
| Gate review compliance | 100% of gates reviewed on schedule | Gate tracking |
| Kill criteria responsiveness | <48 hours from breach to board notification | Response time |
