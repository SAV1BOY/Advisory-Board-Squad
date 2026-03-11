# Customer Health Score

## Definition

A composite metric that measures the overall health of the customer base by combining product usage, satisfaction, support burden, and expansion signals. The score predicts customer retention and expansion likelihood, enabling proactive intervention before churn signals become terminal. Scored on a 0-100 scale per customer, with portfolio-level aggregation for board reporting.

## Formula

```
Customer Health Score = (Usage Score x 0.30) + (Satisfaction Score x 0.25) + (Support Score x 0.20) + (Engagement Score x 0.15) + (Expansion Score x 0.10)

Where:
- Usage Score (0-100): DAU/MAU ratio, feature adoption depth, login frequency vs. contract entitlement
- Satisfaction Score (0-100): NPS response (detractor=20, passive=50, promoter=90) or CSAT average scaled to 100
- Support Score (0-100): Inverse of support ticket volume and severity (fewer tickets = higher score)
- Engagement Score (0-100): Executive sponsor responsiveness, QBR attendance, community participation
- Expansion Score (0-100): Seat utilization vs. contract (>80% = high), upsell conversation receptivity, multi-product adoption
```

## Target Range

| Rating | Score | Action |
|--------|-------|--------|
| Healthy | 75-100 | Monitor quarterly; prioritize for case studies and referrals |
| Stable | 55-74 | Monitor monthly; identify and address declining sub-scores |
| At Risk | 35-54 | Immediate intervention plan; escalate to CS leadership |
| Critical | 0-34 | Executive-level save plan; board visibility if top-20 customer |

**Portfolio target: 70% of customers in Healthy or Stable range. No more than 5% of ARR in Critical range.**

## Data Sources

- Product analytics platform (usage metrics, feature adoption, login data)
- NPS/CSAT survey responses (quarterly or transactional)
- Support ticketing system (volume, severity, resolution time)
- CRM (executive engagement, QBR records, expansion pipeline)
- Billing system (seat utilization, contract value, renewal dates)

## Frequency

- **Per-customer score calculation:** Monthly (automated)
- **Portfolio summary for leadership:** Monthly
- **Board-level reporting:** Quarterly — present distribution chart (% in each health band) and trend
- **Deep-dive on At Risk/Critical accounts:** Bi-weekly in CS team meetings

## Owner

- **Primary:** VP of Customer Success or Head of Customer Experience
- **Board sponsor:** Board member with customer/revenue oversight responsibility
- **Data steward:** Revenue Operations or Business Intelligence team

## Related Metrics

- `data/metrics/strategic-alignment-score.md` — customer health contributes to strategic execution assessment
- `data/research/industry-benchmarks-saas.md` — NRR and churn benchmarks for context
- `data/metrics/revenue-growth-rate.md` — customer health is a leading indicator of revenue retention
- `data/metrics/stakeholder-satisfaction-score.md` — customers are a key stakeholder group
