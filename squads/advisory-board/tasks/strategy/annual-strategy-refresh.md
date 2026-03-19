# Task: Annual Strategy Refresh

## Objective
Run a comprehensive annual strategy refresh cycle that reassesses the company's strategic direction, competitive position, growth priorities, and resource allocation for the coming year. Produce an updated strategic plan endorsed by the board.

## Trigger
- Annual planning cycle (typically Q4 for the following year)
- Major market disruption requiring strategic reassessment outside the normal cycle
- Post-acquisition or post-funding event that materially changes the company's position

## Agents Involved
- **Lead:** CEO
- **Support:** CFO, CTO, CPO, functional leaders, Strategy Lead
- **Advisory:** Full board, with deep engagement from members with relevant domain expertise


## Agent Assignment
> Routing: see `config.yaml → routing → quarterly-board-review`

- **Lead:** strategic-advisor (Peter Thiel)
- **Support:** board-chair (Board Chair), capital-allocator (Charlie Munger), risk-sentinel (Ray Dalio)
- **Review:** growth-navigator (Naval Ravikant)

## Pre-Requisites
- [ ] Prior year strategy document and OKRs with actuals
- [ ] Competitive landscape report current
- [ ] Financial performance data and forecasts available
- [ ] Customer and market research up to date
- [ ] Moat assessment current
- [ ] Input collected from all functional leaders

## Steps

1. **Retrospective and Performance Review (Weeks 1-2)**
   - Assess performance against prior year strategic goals and OKRs
   - Identify what worked, what did not, and root causes for misses
   - Review forecast accuracy — where did assumptions prove wrong?
   - Document key learnings to inform the refresh

2. **Environmental Scan (Weeks 2-4)**
   - Update competitive landscape analysis using competitive-landscape-report template
   - Conduct customer research — shifting needs, satisfaction trends, emerging demands
   - Assess market and industry trends — TAM evolution, regulatory changes, technology shifts
   - Review macroeconomic factors that could impact the business

3. **Strategic Diagnosis (Weeks 3-5)**
   - Reassess company mission, vision, and long-term direction — any adjustments needed?
   - Evaluate current moat strength and trajectory using moat-assessment-brief
   - Identify the 3-5 most critical strategic questions for the coming year
   - Conduct SWOT analysis refreshed with current data

4. **Strategy Development (Weeks 5-8)**
   - Define or refine strategic priorities for the coming year (maximum 3-5)
   - For each priority: articulate the thesis, success metrics, resource requirements, and risks
   - Develop financial scenarios tied to strategic choices
   - Align innovation portfolio with strategic direction
   - Draft the strategy memo using the strategy-memo-2pager template

5. **Resource and Capital Alignment (Weeks 7-9)**
   - Map budget allocation to strategic priorities
   - Identify capability gaps and hiring plan
   - Develop capital allocation recommendations using capital-allocation-memo template
   - Ensure innovation portfolio allocation reflects strategy

6. **Board Strategy Offsite (Week 9-10)**
   - Present the strategic refresh at the quarterly offsite using quarterly-offsite-agenda template
   - Facilitate board debate on strategic priorities and trade-offs
   - Capture board direction, modifications, and approvals
   - Align on key metrics and review cadence

7. **Finalization and Cascade (Weeks 10-12)**
   - Incorporate board feedback into the final strategic plan
   - Cascade strategic priorities into functional OKRs and quarterly plans
   - Communicate the updated strategy to the full organization
   - Set up the execution tracker for board-level monitoring

## Frameworks to Apply
- **Playing to Win (Lafley/Martin):** Where to play, how to win, capabilities required, management systems
- **Strategic Diagnosis:** Define the challenge before jumping to solutions
- **Scenario Planning:** Develop multiple futures and stress-test the strategy against each
- **Jobs to Be Done:** Ground strategic choices in customer needs, not internal assumptions

## Checklists

### Quality Gate
- [ ] Retrospective is honest — failures analyzed, not just successes celebrated
- [ ] Environmental scan uses external data, not just internal assumptions
- [ ] Strategic priorities are specific enough to guide resource allocation decisions
- [ ] Each priority has clear success metrics and an owner
- [ ] Financial plan is aligned with strategic priorities
- [ ] Board has formally endorsed the strategic direction
- [ ] Strategy is communicable in a single page (the strategy-memo-2pager is complete)

## Output
- Updated annual strategic plan
- Strategy memo (2-pager) for board and organizational communication
- Updated OKRs and success metrics
- Capital allocation plan aligned to strategy
- Execution tracker populated with strategic initiatives
- Board endorsement recorded in decision log

## Handoffs
- Strategic priorities feed into quarterly board reviews
- Capital allocation feeds into budget-review task
- Capability gaps feed into exec-hiring and team-health-check tasks
- Innovation alignment feeds into innovation-portfolio-review task
- Execution tracking feeds into execution-30-60-90 plans

## Metrics
| Metric | Target | Measurement |
|---|---|---|
| Strategy refresh completion | Completed before fiscal year start | Calendar |
| Board endorsement | Unanimous or supermajority approval | Decision log |
| Priority clarity | 100% of employees can name top 3 priorities | Quarterly survey |
| Strategy-budget alignment | >80% of incremental spend maps to top priorities | Budget audit |
| Quarterly strategy review cadence | 4 reviews per year | Board calendar |
