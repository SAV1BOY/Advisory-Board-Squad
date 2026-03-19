# Task: Insurance and Liability Review

## Objective
Review the organization's insurance coverage and liability exposure to ensure adequate protection against material risks. Verify that coverage limits, deductibles, and policy terms are appropriate for the company's current size, stage, and risk profile.

## Trigger
- Annual insurance renewal cycle (typically 60-90 days before policy expiration)
- After a significant business change (fundraising, acquisition, new market entry, headcount growth)
- Following an incident or claim that tests existing coverage
- After a risk register update identifies new or increased exposures
- When entering into contracts that impose insurance requirements (enterprise customers, partnerships)
- Board-directed review as part of governance best practices

## Agents Involved
- **Lead:** CFO or General Counsel
- **Support:** Insurance broker, CHRO (for employment practices coverage), CTO (for cyber coverage), operations leads
- **Advisory:** Board members with risk management or insurance expertise


## Agent Assignment
> Routing: see `config.yaml → routing → capital-allocation-review`

- **Lead:** risk-sentinel (Ray Dalio)
- **Support:** capital-allocator (Charlie Munger), governance-clerk (Simon Sinek)
- **Review:** board-chair (Board Chair)

## Pre-Requisites
- [ ] Current insurance policy schedule — all active policies with terms, limits, and premiums
- [ ] Claims history for the past 3-5 years
- [ ] Current risk register and risk assessment report
- [ ] Revenue, headcount, and asset data for coverage adequacy assessment
- [ ] Contractual insurance requirements from customers, partners, and investors
- [ ] Industry benchmarks for coverage levels at comparable companies

## Steps

1. **Policy Inventory and Review (Days 1-5)**
   - Compile complete inventory of all active insurance policies:
     - Directors and Officers (D&O)
     - Errors and Omissions (E&O) / Professional Liability
     - Cyber Liability and Data Breach
     - General Commercial Liability
     - Employment Practices Liability (EPLI)
     - Key Person / Key Man
     - Property and Business Interruption
     - Workers Compensation
     - Umbrella / Excess Liability
   - For each policy, document: insurer, limits, deductible, premium, expiration date, key exclusions
   - Review policy terms for material exclusions or conditions that could limit coverage
   - Verify that all policies are current and premiums paid

2. **Exposure Assessment (Days 5-10)**
   - Map current business risks to insurance coverage categories
   - Assess whether coverage limits are adequate given current exposure:
     - D&O: Is coverage sufficient given company valuation, board size, and litigation climate?
     - Cyber: Does coverage match data volumes, customer contractual requirements, and regulatory exposure?
     - E&O: Does coverage reflect current revenue and customer contract values?
     - EPLI: Does coverage reflect current headcount and jurisdictions?
   - Identify exposures that are not currently insured — gap analysis
   - Review contractual insurance obligations — are we meeting customer and partner requirements?
   - Assess adequacy of coverage relative to industry benchmarks

3. **Claims and Loss History Review (Days 8-12)**
   - Review claims history — frequency, severity, types
   - Assess whether claim trends indicate areas needing additional coverage or risk mitigation
   - Evaluate claims handling experience with current insurers — responsiveness, fairness
   - Identify any claims denied and reasons for denial
   - Assess the impact of claims history on future premium expectations

4. **Coverage Optimization (Days 12-16)**
   - Identify gaps between current coverage and current exposure
   - Develop recommendations for coverage changes:
     - Increase limits where exposure has grown beyond coverage
     - Add new coverage types for emerging risks
     - Adjust deductibles to optimize premium vs. out-of-pocket balance
     - Consolidate policies where possible for efficiency
   - Obtain competitive quotes from multiple insurers for any material changes
   - Model total insurance cost under various coverage configurations

5. **Board Review and Approval (Days 16-20)**
   - Prepare insurance and liability review summary for the board
   - Present coverage gaps and recommended changes with cost implications
   - Highlight any material uninsured or underinsured risks
   - Obtain board approval for coverage changes and premium budget
   - Document the board's risk acceptance decisions for any knowingly uninsured exposures

## Frameworks to Apply
- **Risk Transfer Matrix:** Map risks to insurance (transfer), mitigation (reduce), acceptance (retain), or avoidance
- **Coverage Adequacy Assessment:** Compare limits to realistic worst-case exposure scenarios
- **Total Cost of Risk:** Premium + deductibles + uninsured losses + risk management costs
- **Peer Benchmarking:** Compare coverage levels to companies of similar size, stage, and industry

## Checklists

### Quality Gate
- [ ] All active policies inventoried with current terms, limits, and premiums
- [ ] Coverage limits assessed against current exposure levels
- [ ] Gap analysis identifies uninsured or underinsured risks
- [ ] Contractual insurance obligations verified as met
- [ ] Claims history reviewed and trends assessed
- [ ] Competitive quotes obtained for material coverage changes
- [ ] Board has reviewed coverage posture and approved the insurance program
- [ ] Any knowingly accepted uninsured risks documented with board acknowledgment

## Output
- Insurance coverage summary and gap analysis
- Coverage adequacy assessment by risk category
- Recommendations for coverage changes with cost analysis
- Competitive quote comparison (if renewal or new coverage)
- Updated insurance policy schedule
- Board approval of insurance program recorded in decision log

## Handoffs
- Insurance gaps feed into risk-register-update task
- Premium costs feed into budget-review task
- D&O coverage assessment feeds into board-effectiveness-review
- Cyber insurance review feeds into cyber-and-fraud-gate task
- Contractual requirements feed into deal-terms-review and partner-eval tasks
- Claims history insights feed into crisis-response planning

## Metrics
| Metric | Target | Measurement |
|---|---|---|
| Coverage adequacy | All material risks insured at adequate limits | Gap analysis |
| Policy currency | Zero lapsed policies | Policy schedule |
| Contractual compliance | 100% of insurance obligations met | Contract review |
| Premium cost as % of revenue | Within industry benchmark range | Financial reporting |
| Claims response satisfaction | >4/5 | Post-claim assessment |
