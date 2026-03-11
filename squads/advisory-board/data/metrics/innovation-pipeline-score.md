# Innovation Pipeline Score

## Definition

A composite metric measuring the health and throughput of the company's innovation portfolio — from early-stage ideas through validated experiments to shipped products. The innovation pipeline score ensures the board has visibility into the company's future growth engine, not just current operations. A healthy pipeline balances incremental improvements (sustaining innovation) with bets on new capabilities or markets (disruptive innovation). Companies with empty or unbalanced pipelines face a revenue growth cliff 18-36 months out.

## Formula

```
Innovation Pipeline Score = (Pipeline Fullness x 0.25) + (Stage Progression x 0.25) + (Portfolio Balance x 0.20) + (Time to Validation x 0.15) + (Resource Allocation Alignment x 0.15)

Where:
- Pipeline Fullness (0-100): Number of active initiatives relative to target (e.g., 15 active ideas, 5 experiments, 2 builds = scored against company targets)
- Stage Progression (0-100): % of initiatives that advanced at least one stage in the quarter (idea → experiment → build → ship)
- Portfolio Balance (0-100): Distribution across horizon categories:
    H1 (core improvements): 50-60% of resources
    H2 (adjacent expansion): 25-35% of resources
    H3 (transformational bets): 10-20% of resources
  Score penalizes >80% in any single horizon
- Time to Validation (0-100): Median days from idea to first experiment result (lower is better; target <30 days for H1, <60 for H2, <90 for H3)
- Resource Allocation Alignment (0-100): % of innovation budget actually spent vs. allocated (underspend signals neglect; overspend signals poor planning)
```

## Target Range

| Rating | Score | Status |
|--------|-------|--------|
| Strong Pipeline | 75-100 | Innovation engine is fueling future growth |
| Adequate Pipeline | 55-74 | Pipeline exists but needs acceleration or rebalancing |
| Weak Pipeline | 35-54 | Innovation is under-invested; future growth at risk |
| Critical | 0-34 | No meaningful innovation pipeline; strategic risk is high |

**Target: Maintain score above 60. Flag for board discussion if score drops below 55 or if H3 allocation drops to 0%.**

## Data Sources

- Product management tool (Jira, Linear, Productboard) — initiative tracking and stage progression
- Innovation or experiment tracking system — hypothesis, test, result logs
- Financial data — innovation budget allocation vs. actual spend
- Engineering capacity data — % of engineering time on innovation vs. maintenance
- Customer feedback systems — demand signals for new capabilities

## Frequency

- **Pipeline inventory update:** Monthly (product leadership)
- **Score calculation:** Quarterly
- **Board reporting:** Quarterly — present score, pipeline visualization (funnel by stage), and portfolio balance chart
- **Annual innovation review:** Annually — deep-dive on innovation ROI, pipeline health trends, and strategic alignment

## Owner

- **Primary:** VP of Product or Chief Product Officer
- **Board sponsor:** Board member with product/technology oversight
- **Data steward:** Product Operations or Strategy team

## Related Metrics

- `data/metrics/execution-throughput.md` — innovation throughput vs. operational throughput balance
- `data/metrics/strategic-alignment-score.md` — innovation priorities should align with strategic plan
- `data/research/ai-disruption-landscape.md` — external innovation threats that the pipeline should address
- `lib/patterns/innovation-portfolio-pattern.md` — pattern for managing the innovation portfolio
