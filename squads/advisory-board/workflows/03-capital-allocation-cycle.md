# 03 — Capital Allocation Cycle

## Overview

A rigorous process for evaluating how the company deploys financial resources across competing opportunities. Covers expected-value analysis, scenario modeling, decision-making, and post-allocation review. Runs quarterly with a major annual cycle tied to the strategy refresh.

## Trigger

- Quarterly capital review on the standing calendar.
- Annual budget cycle (aligned with strategy refresh, workflow 02).
- Ad-hoc request exceeding the delegated authority threshold (e.g., >$X investment, new market entry, acquisition).

## Agents

| Agent | Role |
|---|---|
| Board-Chair | Facilitates decision, ensures discipline |
| Strategy-Analyst | Builds financial models, scenarios, EV calculations |
| Devil's-Advocate | Stress-tests assumptions, argues the counter-case |
| Risk-Analyst | Assesses downside scenarios, tail risks, correlation effects |
| Execution-Tracker | Monitors post-allocation performance against projections |

## Phases

### Phase 1 — Opportunity Inventory (Days 1-5)

1. Collect all capital requests from business units and squads. Each request uses the standard capital request template:
   - What is the opportunity?
   - What is the expected return (quantified)?
   - What is the required investment (amount, timing, duration)?
   - What are the key assumptions?
   - What is the opportunity cost?
2. Strategy-Analyst categorizes requests: growth investments, maintenance/infrastructure, defensive/risk-mitigation, optionality/experiments.
3. Rank requests by expected value using a consistent framework (NPV, IRR, or payback period depending on type).
4. Identify any requests that are mutually exclusive or have significant dependencies.

### Phase 2 — Scenario Modeling (Days 5-10)

1. For each material request (top 5-7 by size or strategic importance):
   a. Build three scenarios: base case, upside, downside.
   b. Assign probability weights to each scenario (explicit, documented).
   c. Calculate expected value = Σ(probability × outcome) for each request.
   d. Model the portfolio effect: how do requests interact? What is the total portfolio risk?
2. Risk-Analyst runs stress tests: what if two downside scenarios hit simultaneously? What is the maximum drawdown?
3. Devil's-Advocate identifies the "hidden assumptions" in each model — the inputs that, if wrong, invalidate the case.
4. Package the analysis into a capital allocation brief (5-page max + appendix with model details).

### Phase 3 — Decision Session (Day 12-14)

1. Board-Chair convenes a dedicated capital allocation session (90 minutes).
2. Strategy-Analyst presents the portfolio view: all requests ranked, scenarios summarized, portfolio risk assessed.
3. For each material request:
   a. Presenter states the ask and recommendation (3 min).
   b. Devil's-Advocate presents the strongest counter-case (3 min).
   c. Risk-Analyst highlights the key risk factors (2 min).
   d. Board discussion (10 min).
   e. Decision: fund, reject, defer, or fund with conditions.
4. Board-Chair confirms the total allocation stays within the capital budget envelope.
5. Record all decisions with rationale, conditions, dissenting views, and review dates.

### Phase 4 — Post-Allocation Monitoring (Ongoing)

1. Execution-Tracker sets up tracking for each funded initiative:
   - Milestone schedule with go/no-go gates.
   - Key metrics that map back to the assumptions in the original model.
   - Variance reporting: actual vs. projected at each milestone.
2. Monthly async update from each initiative owner to Execution-Tracker.
3. Quarterly portfolio review: which initiatives are on track, ahead, behind, or should be killed?
4. Kill criteria are defined at allocation time, not invented later when sunk costs create bias.

### Phase 5 — Retrospective Review (Annually)

1. Strategy-Analyst pulls the last 12 months of capital allocation decisions.
2. For each decision: what did we project? What actually happened? Why?
3. Calculate the portfolio's realized return vs. expected return.
4. Identify systematic biases: are we consistently over-optimistic on timelines? Under-estimating costs? Over-weighting growth vs. maintenance?
5. Document learnings and update the capital allocation framework accordingly.
6. Board reviews the retrospective and approves framework updates.

## Quality Gates

| Gate | Criteria | Owner |
|---|---|---|
| G1 — Requests complete | All requests use standard template, assumptions explicit | Strategy-Analyst |
| G2 — Scenarios built | Top 5-7 requests modeled with three scenarios and probability weights | Strategy-Analyst |
| G3 — Stress-tested | Devil's Advocate and Risk-Analyst have reviewed every material request | Devil's-Advocate |
| G4 — Decisions recorded | Every decision logged with rationale, conditions, kill criteria, review date | Board-Chair |
| G5 — Tracking live | Execution-Tracker has milestone schedule and metrics for every funded initiative | Execution-Tracker |

## Outputs

- Capital request inventory (ranked).
- Scenario models with probability-weighted expected values.
- Capital allocation brief (5 pages + appendix).
- Decision log entries for each request.
- Initiative tracking dashboards.
- Annual capital allocation retrospective.

## Timeline

| Milestone | Timing |
|---|---|
| Requests collected | Day 3 |
| Scenario models complete | Day 10 |
| Capital allocation brief distributed | Day 10 |
| Decision session | Day 12-14 |
| Tracking dashboards live | Day 21 |
| Annual retrospective | Q4 each year |

## Metrics

| Metric | Target |
|---|---|
| Requests with complete templates | 100 % |
| Scenario coverage for material requests | 100 % (three scenarios each) |
| Decision session duration | ≤90 minutes |
| Variance reporting cadence | Monthly, no exceptions |
| Kill decision turnaround | ≤7 days from kill criteria being met |
| Annual portfolio return vs. projection | Within ±20 % of expected value |

## Common Failures

| Failure Mode | Symptom | Mitigation |
|---|---|---|
| Peanut-butter spreading | Capital spread thinly across too many initiatives | Force-rank and fund the top N; set a minimum allocation threshold |
| Sunk cost paralysis | Failing initiatives never get killed | Define kill criteria upfront; Execution-Tracker flags automatically |
| Optimism bias | Every model shows a hockey stick | Require a "what would have to be true" section; Devil's Advocate challenges inputs |
| Maintenance neglect | Growth investments crowd out infrastructure | Reserve a fixed percentage for maintenance; make it non-negotiable |
| Missing opportunity cost | Requests evaluated in isolation | Strategy-Analyst presents the portfolio view, including what gets deferred if X is funded |
| Retrospective skip | Annual review never happens | Board-Chair blocks the Q4 session; it is a standing agenda item |
