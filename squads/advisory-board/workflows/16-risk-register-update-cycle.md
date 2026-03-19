# 16 — Risk Register Update Cycle

## Overview

A recurring process to identify new risks, reassess existing risks, validate mitigations, and ensure the board has a current, actionable view of the company's risk landscape. The risk register is a living document, not an annual compliance exercise.

## Trigger

- Monthly standing update (async, lightweight).
- Quarterly board review (dedicated 15-minute agenda block).
- Annual comprehensive review (60-minute dedicated session).
- Material event: new risk identified, existing risk materializes, or external shock.

## Agents

| Agent | Role |
|---|---|
| risk-sentinel (Ray Dalio) | Maintains the register, conducts assessments |
| board-chair (Board Chair) | Reviews the register, ensures board engagement |
| strategic-advisor (Peter Thiel) | Links risks to strategic priorities |
| capital-allocator (Charlie Munger) | Challenges risk ratings, identifies blind spots |
| governance-clerk (Simon Sinek) | Manages the update process and archiving |

## Phases

### Phase 1 — Risk Identification (Ongoing + Monthly)

1. Sources for new risk identification:
   - Executive team submissions (any executive can flag a risk at any time).
   - Board meeting discussions and observations.
   - External monitoring: regulatory changes, competitive moves, market shifts, technology disruptions.
   - Internal monitoring: operational metrics, customer complaints, employee concerns, audit findings.
   - Post-mortem findings (workflow 19).
   - Cross-squad feedback (workflow 15).
2. For each new risk, capture in the register:
   - Risk ID and title.
   - Description: what could happen? Under what conditions?
   - Category: strategic, operational, financial, regulatory, reputational, technology, people.
   - Risk owner: the person accountable for monitoring and mitigation.
3. Monthly: risk-sentinel reviews all inputs and updates the register with new risks.

### Phase 2 — Risk Assessment (Monthly + Quarterly)

1. For each risk in the register, assess:
   - Likelihood (1-5): how probable is this in the next 12 months?
   - Impact (1-5): if it materializes, how severe is the consequence?
   - Velocity: how fast would this risk materialize once triggered?
   - Detectability: how much warning would we get?
   - Risk score = Likelihood × Impact (used for prioritization).
2. Categorize risks by score:
   - Critical (20-25): requires active mitigation and board attention.
   - High (12-19): requires mitigation plan and regular monitoring.
   - Medium (6-11): monitored, mitigation optional.
   - Low (1-5): accepted, reviewed periodically.
3. capital-allocator challenges:
   - "Are we rating this too low because we don't want to deal with it?"
   - "What risk are we not seeing because it hasn't happened yet?"
   - "Which risks are correlated — if one materializes, which others become more likely?"

### Phase 3 — Mitigation Planning (For critical and high risks)

1. For each critical and high risk, define the mitigation strategy:
   - Avoid: can we eliminate the risk entirely by changing our approach?
   - Reduce: what actions decrease likelihood or impact?
   - Transfer: can we share the risk (insurance, contracts, partnerships)?
   - Accept: if we choose to accept, is the rationale documented?
2. Each mitigation has:
   - Specific actions with owners and deadlines.
   - Cost of mitigation (some mitigations are more expensive than the risk).
   - Residual risk after mitigation (what remains even after we act).
   - Trigger for escalation: what would cause this risk to jump to a higher category?
3. risk-sentinel validates that mitigation plans are realistic, resourced, and tracked.

### Phase 4 — Board Review (Quarterly)

1. risk-sentinel prepares the quarterly risk report:
   - Risk heat map: all risks plotted on a likelihood × impact matrix.
   - Changes since last review: new risks, re-rated risks, materialized risks, retired risks.
   - Top 5 risks with mitigation status.
   - Emerging risks: early signals that don't yet meet the threshold for the register.
2. board-chair allocates 15 minutes of the quarterly meeting for risk review.
3. Board discussion: are we focused on the right risks? Are mitigations adequate? What are we missing?
4. Board decisions: accept current risk posture, or direct specific changes to mitigation plans.
5. Record the board's risk posture decisions in the meeting minutes.

### Phase 5 — Annual Comprehensive Review (Annually)

1. risk-sentinel conducts a full review of the risk register:
   - Every risk re-assessed from scratch (not just incremental updates).
   - Review the past year: which risks materialized? Were we prepared?
   - Review risk categories: are the categories still relevant? Any new categories needed?
   - Benchmark against industry risk reports and peer company disclosures.
2. capital-allocator leads a "black swan" exercise: brainstorm risks that are unlikely but catastrophic.
3. strategic-advisor links the risk register to the strategic plan: are the biggest risks to our strategy adequately captured?
4. Board dedicates a 60-minute session to the annual risk review.
5. Update the register, retire resolved risks, add new risks, recalibrate scoring criteria.
6. Archive the annual risk review package in `archive/risk-reviews/YYYY/`.

## Quality Gates

| Gate | Criteria | Owner |
|---|---|---|
| G1 — Register current | Monthly update completed, no stale risks | risk-sentinel (Ray Dalio) |
| G2 — Assessments valid | All critical/high risks assessed within the last quarter | risk-sentinel (Ray Dalio) |
| G3 — Mitigations active | Every critical/high risk has a mitigation plan with owners | risk-sentinel (Ray Dalio) |
| G4 — Board reviewed | Quarterly risk report presented and discussed | board-chair (Board Chair) |
| G5 — Annual review complete | Full register re-assessment, black swan exercise, strategy linkage | risk-sentinel (Ray Dalio) |

## Outputs

- Risk register (living document, always current).
- Quarterly risk report with heat map.
- Mitigation plans for critical and high risks.
- Annual risk review package.
- Black swan exercise output.
- Board risk posture decisions.

## Timeline

| Milestone | Cadence |
|---|---|
| New risk capture | Continuous |
| Monthly register update | Monthly (by 5th of each month) |
| Quarterly risk report | Quarterly (aligned with board meetings) |
| Annual comprehensive review | Annually (Q4) |

## Metrics

| Metric | Target |
|---|---|
| Register freshness | No risk unreviewed for >90 days |
| Critical/high risk mitigation coverage | 100 % have active mitigation plans |
| Quarterly report delivery | On time for every board meeting |
| Risk surprise rate | ≤1 material risk per year that was not in the register |
| Mitigation effectiveness | ≥70 % of materialized risks had their impact reduced by mitigations |
| Annual review completion | Complete by end of Q4, no exceptions |

## Common Failures

| Failure Mode | Symptom | Mitigation |
|---|---|---|
| Stale register | Risks haven't been updated in months | Monthly update cycle enforced by governance-clerk |
| Risk inflation | Everything rated critical; nothing is actually prioritized | Enforce the scoring rubric; capital-allocator challenges ratings |
| Risk deflation | Real threats rated low to avoid board scrutiny | Annual review re-assesses from scratch; benchmark against industry |
| Mitigation theater | Plans exist on paper but no one is executing | risk-sentinel verifies action progress monthly |
| Missing correlations | Risks assessed individually but correlated risks not considered | capital-allocator explicitly asks about risk interactions |
| Black swan avoidance | Only incremental risks considered; catastrophic risks ignored | Annual black swan exercise is mandatory |
