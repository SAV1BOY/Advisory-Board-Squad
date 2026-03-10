# 12 — Decision Quality Review

## Overview

A systematic retrospective on the quality of past decisions — not just their outcomes. Good decisions can have bad outcomes and vice versa. This workflow separates decision process quality from outcome luck, identifies systematic biases, and improves the board's decision-making over time.

## Trigger

- Quarterly standing agenda item (15-minute review).
- Annual deep-dive (dedicated 90-minute session).
- After a decision produces a significantly unexpected outcome (positive or negative).

## Agents

| Agent | Role |
|---|---|
| Board-Chair | Facilitates the review, ensures intellectual honesty |
| Strategy-Analyst | Compiles decision data, calculates accuracy metrics |
| Devil's-Advocate | Challenges outcome-bias and hindsight-bias in the review |
| Decision-Tracker | Maintains the decision log with outcomes and annotations |
| Governance-Ops | Archives review findings and updates the decision framework |

## Phases

### Phase 1 — Decision Inventory (Days 1-5)

1. Decision-Tracker pulls all decisions from the decision log for the review period.
2. For each decision, compile:
   - Date, question, options considered, decision made, rationale, dissenting views.
   - Projected outcome at time of decision.
   - Actual outcome to date.
   - Confidence level at time of decision (1-5).
   - Reversibility classification at time of decision (reversible, partially reversible, irreversible).
3. Categorize decisions: strategic, financial, operational, personnel, partnership, risk.
4. Flag decisions where actual outcome deviated significantly from projection (>30 % variance).
5. Flag decisions where the board's advice differed from the executive team's initial recommendation.

### Phase 2 — Process Quality Assessment (Days 5-10)

1. For each flagged decision, Strategy-Analyst evaluates the decision process (not the outcome):
   - Information quality: did we have the right information? Was it complete? Was it accurate?
   - Option generation: did we consider enough alternatives? Were they genuinely distinct?
   - Assumption testing: were key assumptions identified and tested?
   - Dissent quality: was dissent encouraged? Were contrarian views genuinely considered?
   - Decision criteria: were criteria clear and applied consistently?
   - Reversibility awareness: did we correctly assess how reversible the decision was?
2. Score each decision's process quality on a 1-5 scale independent of outcome.
3. Devil's-Advocate challenges: "Are we rating this process poorly because the outcome was bad (outcome bias)? Would we rate it the same if the outcome had been good?"

### Phase 3 — Bias Identification (Days 10-15)

1. Strategy-Analyst analyzes the full decision set for systematic patterns:
   - Optimism bias: are projections consistently too optimistic? By how much?
   - Anchoring: are decisions disproportionately influenced by the first option presented?
   - Status quo bias: how often does the board endorse the existing approach when change was warranted?
   - Groupthink: how often does the board reach unanimous decisions? (Some unanimity is fine; 100 % unanimity is a red flag.)
   - Recency bias: are recent events over-weighted in risk assessments?
   - Sunk cost: are failing initiatives continued because of prior investment?
2. Compare to prior review periods: are biases improving, stable, or worsening?
3. Devil's-Advocate presents the findings with specific examples. No abstractions — concrete instances.

### Phase 4 — Learning Integration (Days 15-20)

1. Board-Chair convenes the review session (90 minutes for annual; 15 minutes for quarterly):
   - Present decision accuracy metrics (15 min).
   - Walk through 2-3 case studies: one good process/good outcome, one good process/bad outcome, one bad process (15 min each).
   - Present bias analysis with trends (15 min).
   - Discussion: what should we change? (20 min).
2. For each identified improvement:
   - Update the decision framework (decision-policy.md) with specific changes.
   - Update the pre-read template if information quality was a recurring issue.
   - Adjust the Devil's Advocate protocol if dissent quality was weak.
3. Document the review findings and changes in the decision quality log.

### Phase 5 — Framework Update & Monitoring (Days 20-30)

1. Governance-Ops updates the decision policy and related templates.
2. Strategy-Analyst recalibrates any scoring rubrics or evaluation frameworks based on findings.
3. Decision-Tracker adds new annotation fields to the decision log if the review revealed missing data.
4. Board-Chair communicates the key learnings and framework changes to the executive team.
5. Set the calibration question for the next review: "We predicted that [X]. Let's check at the next review whether [X] materialized."
6. Archive the review package in `archive/decision-reviews/`.

## Quality Gates

| Gate | Criteria | Owner |
|---|---|---|
| G1 — Decision inventory complete | All decisions compiled with projections and outcomes | Decision-Tracker |
| G2 — Process scored | Each flagged decision scored for process quality (1-5) | Strategy-Analyst |
| G3 — Bias analysis complete | Systematic patterns identified with specific examples | Strategy-Analyst |
| G4 — Review session held | Board discusses findings and agrees on changes | Board-Chair |
| G5 — Framework updated | Decision policy and templates updated based on findings | Governance-Ops |

## Outputs

- Decision inventory with projections vs. outcomes.
- Process quality scores for flagged decisions.
- Bias analysis with trend data.
- Case study write-ups (2-3 per review).
- Updated decision policy and templates.
- Decision quality log entry.
- Calibration questions for the next review period.

## Timeline

| Milestone | Day |
|---|---|
| Decision inventory complete | Day 5 |
| Process quality assessment | Day 10 |
| Bias analysis | Day 15 |
| Review session | Day 18 |
| Framework updates published | Day 25 |

## Metrics

| Metric | Target |
|---|---|
| Decision accuracy rate | ≥65 % of decisions produce outcomes within 30 % of projection |
| Process quality average | ≥3.5 / 5.0 |
| Bias trend | No bias worsening year-over-year |
| Dissent frequency | ≥20 % of decisions have recorded dissenting views |
| Framework update rate | ≥1 meaningful change per annual review |
| Calibration question accuracy | Improving trend over time |

## Common Failures

| Failure Mode | Symptom | Mitigation |
|---|---|---|
| Outcome bias | Rating process quality based on outcome, not process | Devil's Advocate explicitly challenges this; score process before revealing outcome |
| Hindsight bias | "We should have known" — applying current knowledge to past decisions | Review only the information available at the time of the decision |
| Cherry-picking | Only reviewing decisions that went well | Review all flagged decisions, including uncomfortable ones |
| Abstract learnings | "We need to be better at X" without specific changes | Every learning must produce a specific framework, template, or process change |
| Review fatigue | Quarterly reviews become perfunctory | Annual deep-dive is the main event; quarterly reviews are brief calibration checks |
| Missing the pattern | Reviewing individual decisions without seeing systematic biases | Bias analysis looks at the full set, not just individual cases |
