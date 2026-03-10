# Risk Blocks

## Purpose

Reusable structural blocks for identifying, assessing, and communicating risks in board-level documents. These blocks standardize how risk surfaces across memos, reviews, and registries so the board develops a shared risk vocabulary and consistent severity calibration.

## Structure

### Block 1 — Risk Identification Card

Captures a single risk with enough precision to act on.

**Fields:**
- **Risk ID:** Unique identifier (format: `RISK-YYYY-NNN`).
- **Risk title:** Plain-language name (e.g., "Key-person dependency on CTO").
- **Risk type:** Classify per `taxonomies/risk-types.md` (strategic, operational, financial, reputational, legal, existential).
- **Description:** 2-3 sentences explaining the risk in concrete terms.
- **Source:** Where the risk originates (market, team, technology, regulation, partner).
- **Affected area:** Which business function, product line, or stakeholder group bears the impact.

### Block 2 — Probability-Impact Matrix Entry

Quantifies the risk for prioritization.

**Fields:**
- **Probability:** Very Low (< 5%) / Low (5-20%) / Medium (20-50%) / High (50-80%) / Very High (> 80%).
- **Impact severity:** Negligible / Minor / Moderate / Major / Catastrophic.
- **Time horizon:** When could this risk materialize (immediate, 1-3 months, 3-12 months, 1-3 years).
- **Velocity:** How quickly damage accumulates once the risk materializes (sudden, fast, gradual).
- **Composite score:** Probability rank (1-5) x Impact rank (1-5) = score out of 25.

### Block 3 — Mitigation Plan

Defines what the organization will do about the risk.

**Fields:**
- **Strategy:** Accept / Mitigate / Transfer / Avoid.
- **Mitigation actions:** Numbered list of concrete steps.
- **Owner:** Person accountable for executing mitigation.
- **Cost of mitigation:** Estimated time, money, or opportunity cost.
- **Residual risk:** What risk remains after mitigation is complete.
- **Review cadence:** How often this risk is re-assessed (weekly, monthly, quarterly).

### Block 4 — Early Warning Indicators

Defines observable signals that the risk is materializing.

**Fields:**
- **Leading indicators:** Metrics or events that precede the risk event.
- **Trigger thresholds:** Specific values that escalate the risk status.
- **Monitoring owner:** Who watches these indicators.
- **Escalation path:** Who is notified and through what channel when a threshold is breached.

### Block 5 — Contingency Envelope

Pre-planned response if the risk fully materializes despite mitigation.

**Fields:**
- **Contingency actions:** What the organization does if the risk event occurs.
- **Decision authority:** Who can activate the contingency plan.
- **Resource pre-allocation:** Budget, people, or assets reserved for contingency.
- **Communication template:** Pre-drafted stakeholder message (internal and external).
- **Recovery timeline:** Estimated time to return to normal operations.

### Block 6 — Risk Interconnection Map

Identifies how this risk links to other risks in the registry.

**Fields:**
- **Correlated risks:** Other Risk IDs that tend to co-occur.
- **Cascading risks:** Risks that this one triggers if it materializes.
- **Offsetting risks:** Risks that decrease if this one materializes (natural hedges).
- **Portfolio effect:** How this risk changes the overall risk profile.

## Usage

1. **Use Block 1 + Block 2** for every risk entry in the risk registry.
2. **Add Block 3** for any risk scoring 9 or above on the composite scale.
3. **Add Block 4** for risks scoring 15 or above, or any risk classified as existential.
4. **Add Block 5** for catastrophic-impact risks regardless of probability.
5. **Use Block 6** during quarterly risk reviews to surface hidden correlations.

## Example

```markdown
## Risk: Key-Person Dependency on CTO

### Identification
- **Risk ID:** RISK-2026-017
- **Type:** Operational
- **Description:** CTO holds sole architectural knowledge of the payments engine. No documentation exists, and the backup engineer joined 3 weeks ago.
- **Source:** Team / organizational design
- **Affected area:** Engineering, Product delivery, Revenue

### Probability-Impact
| Dimension | Rating |
|-----------|--------|
| Probability | Medium (30%) |
| Impact | Major |
| Time horizon | Immediate to 3 months |
| Velocity | Sudden |
| **Composite** | **3 x 4 = 12** |

### Mitigation
- **Strategy:** Mitigate
- **Actions:**
  1. Begin architecture documentation sprint (2 weeks)
  2. Assign backup engineer to shadow CTO on all critical systems
  3. Negotiate 12-month retention bonus with 6-month cliff
- **Owner:** VP Engineering
- **Cost:** $80K retention bonus + 2 weeks eng time
- **Residual risk:** Medium — documentation reduces but does not eliminate dependency

### Early Warning
- **Leading indicators:** CTO engagement scores, recruiter outreach volume, missed 1:1s
- **Trigger:** CTO declines retention offer or engagement score drops below 6/10
- **Escalation:** VP Eng notifies CEO within 24 hours
```
