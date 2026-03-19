# Task: Executive Compensation Review

## Objective
Review executive compensation and equity packages to ensure they are competitive, aligned with performance, consistent with company values, and sufficient to attract and retain top leadership talent. Ensure the total compensation philosophy supports the company's strategic goals.

## Trigger
- Annual compensation review cycle (typically aligned with performance review cycle)
- Before extending an offer to a new executive
- When retention risk is identified for a key executive
- After a funding round that resets company valuation
- Market compensation data indicates material misalignment
- Board-mandated review of compensation philosophy

## Agents Involved
- **Lead:** CHRO or CEO
- **Support:** CFO (for financial modeling), external compensation consultant (if engaged)
- **Advisory:** Board compensation committee or full board


## Agent Assignment
> Routing: see `config.yaml → routing → exec-hiring`

- **Lead:** talent-advisor (Patrick Lencioni)
- **Support:** capital-allocator (Charlie Munger), board-chair (Board Chair)
- **Review:** ethics-compass (Yvon Chouinard)

## Pre-Requisites
- [ ] Current compensation data for all executives — base, bonus, equity, benefits
- [ ] Market compensation benchmarks from reputable sources (Radford, Carta, Option Impact, etc.)
- [ ] Performance review data for all executives
- [ ] Current equity plan — pool size, utilization, remaining pool, vesting schedules
- [ ] Company valuation (latest 409A or funding round)
- [ ] Peer group defined for benchmarking (by stage, size, industry, geography)

## Steps

1. **Market Benchmarking (Days 1-5)**
   - Compile current total compensation for each executive — base, variable, equity value, benefits
   - Benchmark each role against market data for the defined peer group
   - Calculate percentile positioning for each executive (25th, 50th, 75th, 90th)
   - Identify roles that are significantly above or below market
   - Assess geographic and industry-specific adjustments where relevant

2. **Pay-for-Performance Alignment (Days 5-8)**
   - Map each executive's compensation to their performance rating
   - Assess internal equity — are compensation differences justified by performance differences?
   - Review variable compensation effectiveness — is the incentive structure driving desired behaviors?
   - Evaluate the relationship between company performance and total executive compensation
   - Identify misalignments between pay and performance

3. **Equity Assessment (Days 8-12)**
   - Review the total equity pool — size, utilization, and remaining capacity
   - Assess each executive's equity position — vested vs. unvested, percentage of pool
   - Evaluate equity as a retention tool — are unvested equity holdings sufficient to retain?
   - Model equity dilution under various scenarios (new hires, refreshes, fundraising)
   - Review vesting schedules and cliff timing for retention risk
   - Assess whether the equity structure aligns with long-term value creation

4. **Compensation Philosophy Review (Days 10-14)**
   - Review the stated compensation philosophy — does it still fit the company stage and strategy?
   - Assess the mix between base, variable, and equity — is it appropriate?
   - Evaluate the alignment between compensation design and company values (e.g., team vs. individual)
   - Review clawback provisions, change-of-control terms, and severance policies
   - Benchmark the philosophy against peer companies

5. **Recommendations and Board Approval (Days 14-20)**
   - Develop specific compensation recommendations for each executive
   - Prepare a total compensation cost model — current vs. proposed, with budget impact
   - Document the rationale for any changes, linked to market data and performance
   - Present recommendations to the board compensation committee
   - Obtain board approval for compensation changes and equity grants

## Frameworks to Apply
- **Total Rewards Framework:** Evaluate all forms of compensation, not just cash
- **Pay Equity Analysis:** Ensure fairness across demographics and roles
- **Retention Risk Matrix:** Cross-reference compensation position with flight risk and business criticality
- **Long-Term Incentive Alignment:** Ensure equity structure incentivizes long-term value creation

## Checklists

### Quality Gate
- [ ] Market benchmarks from at least two reputable sources
- [ ] All executives benchmarked against the defined peer group
- [ ] Pay-for-performance correlation assessed with data
- [ ] Equity pool analysis includes dilution modeling
- [ ] Internal pay equity reviewed for fairness and consistency
- [ ] Total cost of proposed changes modeled against budget
- [ ] Board compensation committee or full board has approved all changes

## Output
- Executive compensation benchmarking report
- Individual compensation recommendations with rationale
- Equity pool analysis and grant recommendations
- Updated compensation philosophy (if changes recommended)
- Total compensation cost model
- Board approval recorded in decision log

## Handoffs
- Budget impact feeds into budget-review task
- Equity pool changes feed into capital-allocation-review (dilution impact)
- Retention actions feed into succession-planning task
- New hire compensation parameters feed into exec-hiring task
- Compensation philosophy feeds into culture-code-update task

## Metrics
| Metric | Target | Measurement |
|---|---|---|
| Executive retention rate | >[%] annually | HR data |
| Comp-to-market ratio | Within target percentile range for each role | Benchmarking report |
| Pay-for-performance correlation | >0.7 correlation between rating and total comp | Statistical analysis |
| Equity pool utilization | Within board-approved targets | Cap table analysis |
| Offer acceptance rate | >[%] for executive roles | Recruiting data |
