# Risk Types Taxonomy

## Types

1. **Strategic Risk** — Threats to the company's competitive position, market relevance, or long-term viability from external forces or internal strategic errors.
2. **Operational Risk** — Threats arising from internal processes, systems, people, or organizational design failures.
3. **Financial Risk** — Threats to the company's financial health including liquidity, solvency, and capital allocation errors.
4. **Reputational Risk** — Threats to the company's brand, trustworthiness, or public standing.
5. **Legal and Regulatory Risk** — Threats from lawsuits, regulatory changes, compliance failures, or intellectual property disputes.
6. **Technology Risk** — Threats from technical debt, platform dependencies, security vulnerabilities, or technology disruption.
7. **People Risk** — Threats from talent loss, cultural degradation, leadership gaps, or organizational dysfunction.
8. **Market Risk** — Threats from market shifts, economic cycles, customer behavior changes, or demand volatility.
9. **Existential Risk** — Threats that could end the company entirely — not just damage it, but kill it.
10. **Concentration Risk** — Threats from over-dependence on a single customer, supplier, technology, or market.

## Definitions

| Type | Definition | Common Sources | Typical Velocity |
|------|-----------|----------------|-----------------|
| Strategic | Fundamental threat to competitive position or business model viability | Disruption, market shifts, failed strategy, competitor moves | Slow to medium (months to years) |
| Operational | Failure in day-to-day execution capability | Process breakdowns, system failures, supply chain issues, quality problems | Fast (days to weeks) |
| Financial | Threat to cash flow, solvency, or return on capital | Burn rate, revenue concentration, bad debt, currency exposure, capital misallocation | Variable (sudden for liquidity, gradual for margin erosion) |
| Reputational | Damage to how stakeholders perceive the company | PR incidents, product failures, ethical lapses, social media, executive misconduct | Very fast (hours to days) |
| Legal/Regulatory | Legal liability or regulatory non-compliance | Lawsuits, regulation changes, IP disputes, data privacy, employment law | Slow to sudden (regulatory change can be abrupt) |
| Technology | Technical systems fail, become obsolete, or are compromised | Security breaches, technical debt, vendor lock-in, platform risk, scalability failures | Variable (breaches are instant; debt accumulates gradually) |
| People | Loss of critical talent or cultural degradation | Key-person dependency, burnout, toxic culture, hiring failures, succession gaps | Medium (weeks to months for individual; months for cultural) |
| Market | External market conditions shift unfavorably | Economic downturn, demand shifts, pricing pressure, new entrants, commoditization | Slow to medium (quarters to years, though shocks occur) |
| Existential | Company-ending events | Running out of cash, catastrophic legal judgment, total loss of customer trust, founder departure without succession | Variable — can be sudden or the culmination of other risks |
| Concentration | Over-dependence on a single point of failure | Single large customer (> 25% revenue), sole supplier, one technology platform, one market | Sudden when the concentration point fails |

## Examples

| Risk Type | Example | Probability-Impact Profile |
|-----------|---------|---------------------------|
| Strategic | A well-funded competitor launches a free tier that commoditizes our core product | Medium probability, Major impact |
| Operational | Deployment pipeline has no rollback capability; bad deploys require manual recovery | High probability, Moderate impact |
| Financial | Three customers represent 60% of revenue; loss of any one creates a cash crisis | Medium probability, Catastrophic impact |
| Reputational | Customer data is exposed in a breach; trust evaporates overnight | Low probability, Major impact |
| Legal/Regulatory | New EU regulation requires architectural changes costing $500K+ and 6 months | Medium probability, Moderate impact |
| Technology | AWS region outage takes our product offline for 8+ hours with no multi-region failover | Low probability, Major impact |
| People | CTO is the only person who understands the payment system architecture | High probability (eventual), Major impact |
| Market | Economic recession reduces customer spending on our category by 30% | Medium probability, Major impact |
| Existential | Runway drops below 3 months with no fundraising pipeline and declining revenue | Low probability (with good management), Catastrophic impact |
| Concentration | Largest customer (35% of revenue) is acquired and new parent uses a competing product | Medium probability, Catastrophic impact |

## When to Use Each

**Strategic Risk Assessment** — Use during annual strategic planning, competitive reviews, and when evaluating major strategic decisions. Review quarterly at the board level.

**Operational Risk Assessment** — Use during process design, system architecture reviews, and post-incident analysis. Review monthly at the operational level.

**Financial Risk Assessment** — Use during fundraising planning, budget cycles, and capital allocation reviews. Review monthly by CFO, quarterly at board level.

**Reputational Risk Assessment** — Use before any public-facing decision (product launch, pricing change, policy change, executive action). Review as events occur.

**Legal/Regulatory Risk Assessment** — Use when entering new markets, launching new products, changing data practices, or when regulatory environment shifts. Review quarterly with legal counsel.

**Technology Risk Assessment** — Use during architecture reviews, vendor evaluations, and security audits. Review quarterly by CTO, annually at board level.

**People Risk Assessment** — Use during organizational planning, succession planning, and culture health assessments. Review quarterly at leadership level.

**Market Risk Assessment** — Use during strategic planning and scenario analysis. Review quarterly with market intelligence updates.

**Existential Risk Assessment** — Use during board-level risk reviews. Maintain a standing list of existential risks with mitigations. Review quarterly at board level.

**Concentration Risk Assessment** — Use when any single dependency exceeds 20% of revenue, capacity, or critical function. Review monthly if any concentration threshold is breached.

**Cross-cutting note:** Most real risks span multiple types. A key-person departure (People Risk) can trigger an operational failure (Operational Risk) that causes a customer-facing outage (Reputational Risk) that leads to customer churn (Financial Risk). Risk assessments should always consider cascading effects across types.
