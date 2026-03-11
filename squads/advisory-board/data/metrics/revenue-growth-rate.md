# Revenue Growth Rate

## Definition

The percentage increase in revenue over a defined period, measured across multiple dimensions: total revenue, recurring revenue (ARR/MRR), new business revenue, and expansion revenue. Revenue growth rate is the primary indicator of market traction and is the numerator in most valuation frameworks. The board should track growth rate trajectory (acceleration or deceleration) rather than point-in-time growth, as trajectory predicts future fundraising capacity and strategic optionality.

## Formula

```
Revenue Growth Rate (YoY) = ((Current Period Revenue - Prior Year Period Revenue) / Prior Year Period Revenue) x 100

Revenue Growth Rate (QoQ) = ((Current Quarter Revenue - Prior Quarter Revenue) / Prior Quarter Revenue) x 100

MRR Growth Rate (MoM) = ((Current Month MRR - Prior Month MRR) / Prior Month MRR) x 100

Growth Decomposition:
  New Business Growth = New customer MRR added in period
  Expansion Growth = Upsell + cross-sell MRR from existing customers
  Contraction = Downgrades from existing customers
  Churn = Lost MRR from churned customers
  Net New MRR = New Business + Expansion - Contraction - Churn
```

## Target Range

| Stage | YoY Growth Target | Context |
|-------|-------------------|---------|
| Pre-PMF (< $1M ARR) | Not applicable — track qualitative PMF signals | Growth rate is noise at this stage |
| Early Growth ($1-5M ARR) | 150-300% | Tripling annually is the benchmark for top-tier |
| Growth ($5-20M ARR) | 100-200% | T2D3 framework: triple, triple, double, double, double |
| Scale ($20-50M ARR) | 60-100% | Doubling annually positions well for growth-stage funding |
| Late Stage ($50M+ ARR) | 30-60% | Rule of 40 applies: growth + margin > 40% |

**Key signal: Growth deceleration of >15 percentage points quarter-over-quarter warrants board-level root cause analysis.**

## Data Sources

- Billing/subscription management system (Stripe, Chargebee, Zuora)
- CRM pipeline data (new business forecast, expansion pipeline)
- Financial model and actuals (controller/FP&A reporting)
- Cohort analysis (revenue retention by customer cohort)

## Frequency

- **MRR tracking:** Weekly (leadership team)
- **Monthly growth reporting:** Monthly (management and investors)
- **Board-level growth review:** Quarterly — include growth decomposition, cohort trends, and forward forecast
- **Annual growth trajectory analysis:** Annually — multi-year growth rate trend with benchmark comparison

## Owner

- **Primary:** CFO or VP Finance
- **Board sponsor:** Lead investor or finance committee chair
- **Data steward:** FP&A or Revenue Operations

## Related Metrics

- `data/metrics/burn-rate-and-runway.md` — growth rate relative to burn determines capital efficiency
- `data/metrics/customer-health-score.md` — customer health is a leading indicator of expansion and retention revenue
- `data/research/industry-benchmarks-saas.md` — stage-appropriate growth benchmarks
- `data/metrics/forecast-accuracy.md` — ability to predict growth rate reflects operational maturity
