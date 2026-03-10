# Decision Lead Time

## Definition

The elapsed time between when a decision need is identified (trigger event) and when the decision is formally made and communicated. Measured in calendar days. Tracks the organization's decision velocity and identifies bottlenecks in the decision process.

## How to Measure

1. Record the trigger date for each decision in the decision registry (when the need for a decision was first identified).
2. Record the decision date (when the decision was formally made and communicated).
3. Calculate the difference in calendar days.
4. Segment by decision type:
   - One-way door decisions: measured separately from two-way door decisions.
   - Strategic vs. operational vs. tactical: measured separately by scope.
5. Calculate monthly and quarterly averages for each segment.
6. Track the distribution (median, P75, P90) rather than just the average to identify outliers.

## Target Range

| Decision Type | Target Lead Time | Concern Threshold |
|--------------|------------------|-------------------|
| Two-way door, tactical | 0-2 days | > 5 days |
| Two-way door, operational | 1-5 days | > 10 days |
| One-way door, operational | 5-15 days | > 25 days |
| One-way door, strategic | 10-30 days | > 45 days |
| Crisis decisions | 0-1 day | > 3 days |

**Overall target: Median decision lead time decreasing or stable quarter-over-quarter. P90 lead time not exceeding 2x the target for its category.**

## Data Sources

- Decision registry (trigger dates and decision dates)
- Meeting agendas ([DECIDE] items and their resolution dates)
- Action item tracker (decision-dependent actions and their start dates)
- Qualitative assessment: monthly leadership retrospective on "what decisions are we waiting on?"

## Update Cadence

- **Calculation:** Monthly, based on all decisions recorded in the decision registry that month
- **Trend reporting:** Quarterly — presented with segmentation by decision type
- **Outlier review:** Monthly — any decision exceeding 2x target is reviewed for root cause (was the delay justified or systemic?)
- **Benchmark comparison:** Annually — compare to industry benchmarks and year-over-year self-comparison
