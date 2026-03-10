# Decision Quality Rubric

## Purpose

A scoring rubric for evaluating the quality of decisions independent of their outcomes. Good decisions can have bad outcomes and bad decisions can have good outcomes. This rubric measures the quality of the decision process so the organization can improve its decision-making capability over time rather than rewarding luck and punishing thoughtful risk-taking.

## How to Use

Apply this rubric to any significant decision after it has been made (but ideally before the outcome is known, to avoid outcome bias). Score each dimension independently. Use the results to identify systematic weaknesses in organizational decision-making.

## Scale/Criteria

Score each dimension on a 1-5 scale:

### Dimension 1: Problem Framing (Weight: 20%)
| Score | Description |
|-------|-------------|
| 5 | Decision was framed precisely with the right scope, clear decision type classification, and explicit constraints. The framing itself was questioned and validated. |
| 4 | Decision was well-framed with clear scope and constraints. Minor ambiguity in boundaries. |
| 3 | Decision was framed but with some scope creep or unclear boundaries. Decision type was not explicitly classified. |
| 2 | Decision framing was vague. Multiple problems were conflated. Constraints were assumed, not stated. |
| 1 | No conscious framing. The team jumped from "we have a problem" to "let's do X" without defining what they were actually deciding. |

### Dimension 2: Options Considered (Weight: 15%)
| Score | Description |
|-------|-------------|
| 5 | Multiple genuine options were generated including creative alternatives. The null option ("do nothing") was explicitly evaluated. Options were designed to be distinct, not variations of the same approach. |
| 4 | Three or more options were considered including the null option. Options were meaningfully different. |
| 3 | Two options were considered (the proposed action and one alternative). Null option was mentioned but not seriously evaluated. |
| 2 | Only one option was seriously considered. Alternatives were token inclusions. |
| 1 | No alternatives were generated. The decision was "should we do X?" rather than "what should we do?" |

### Dimension 3: Information Quality (Weight: 20%)
| Score | Description |
|-------|-------------|
| 5 | Decision was informed by relevant data, diverse perspectives, and base rates. Information gaps were explicitly identified and their impact on the decision was assessed. Disconfirming evidence was actively sought. |
| 4 | Good data and multiple perspectives informed the decision. Some information gaps were identified. |
| 3 | Reasonable data was available. Perspectives were somewhat limited. Information gaps were not explicitly called out. |
| 2 | Decision was based primarily on one person's judgment or one data source. Contradicting information was available but not considered. |
| 1 | Decision was made on gut instinct without data, or with data that was cherry-picked to support a predetermined conclusion. |

### Dimension 4: Reasoning Process (Weight: 20%)
| Score | Description |
|-------|-------------|
| 5 | Explicit reasoning linking evidence to conclusion. Assumptions were stated and tested. Second-order effects were considered. Pre-mortem was conducted. Cognitive biases were actively checked. |
| 4 | Clear reasoning with stated assumptions. Some second-order effects considered. At least one bias check performed. |
| 3 | Reasoning was present but informal. Assumptions were implicit. Limited consideration of downstream effects. |
| 2 | Reasoning was superficial or post-hoc (decided first, rationalized after). Key assumptions went unexamined. |
| 1 | No visible reasoning process. Decision appears arbitrary or politically driven. |

### Dimension 5: Dissent and Stress-Testing (Weight: 15%)
| Score | Description |
|-------|-------------|
| 5 | Dissent was actively solicited. Dissenting views were recorded with specificity. The recommendation was stress-tested against the dissent. Conditions for revisiting the dissent were defined. |
| 4 | Dissent was welcomed and considered. Dissenting views were noted. Some stress-testing occurred. |
| 3 | Dissent was tolerated but not actively sought. Recording was informal. No structured stress-test. |
| 2 | Dissent was discouraged through social pressure or leader behavior. Token acknowledgment only. |
| 1 | No dissent was possible or expressed. Groupthink or authority-driven compliance. |

### Dimension 6: Execution Readiness (Weight: 10%)
| Score | Description |
|-------|-------------|
| 5 | Decision included specific action items with owners, deadlines, success criteria, kill criteria, and a communication plan. Dependencies were identified. |
| 4 | Action items were defined with owners and deadlines. Success criteria were stated. |
| 3 | Action items were listed but lacked specificity on owners or deadlines. Success criteria were vague. |
| 2 | Decision was made but translation to action was left for "later." No clear owners. |
| 1 | Decision was made with no action plan. It was unclear what would happen next. |

## Scoring Guide

### Calculating the Overall Score
Multiply each dimension score by its weight and sum:

**Overall = (Framing x 0.20) + (Options x 0.15) + (Information x 0.20) + (Reasoning x 0.20) + (Dissent x 0.15) + (Execution x 0.10)**

### Interpretation
| Score Range | Rating | Interpretation |
|-------------|--------|----------------|
| 4.5 - 5.0 | Excellent | Best-practice decision-making. Outcome variance is due to external factors, not process. |
| 3.5 - 4.4 | Good | Solid process with minor gaps. Focus on the weakest dimension for improvement. |
| 2.5 - 3.4 | Adequate | Functional but with meaningful blind spots. Two or more dimensions need attention. |
| 1.5 - 2.4 | Poor | Process deficiencies are likely contributing to bad outcomes. Systematic improvement needed. |
| 1.0 - 1.4 | Failing | Decision-making is essentially random or political. Urgent cultural and process intervention required. |

### Tracking Over Time
- Score every significant decision (those entered in the decision registry).
- Track the weighted average score monthly and quarterly.
- Identify which dimensions are consistently weakest — this reveals the organization's decision-making blind spot.
- Feed aggregate scores into `data/metrics/board-effectiveness-score.md`.

### Worked Example

**Decision evaluated:** Whether to acquire DataCo for $45M.

| Dimension | Score | Evidence |
|-----------|-------|----------|
| Problem Framing | 4 | Clear decision type (irreversible), good constraints, but trigger was reactive rather than strategic |
| Options Considered | 5 | Four options evaluated including counter-offer, pass, and deferred interest. Null option priced. |
| Information Quality | 3 | Financial data was strong but customer diligence was limited. No disconfirming evidence sought. |
| Reasoning Process | 4 | NPV analysis, scenario table completed. Assumptions stated. No formal pre-mortem. |
| Dissent and Stress-Testing | 4 | CFO's dissent was recorded and addressed. Review trigger established. |
| Execution Readiness | 5 | Detailed action cascade with owners, dates, and communication plan. |

**Overall: (4x0.20) + (5x0.15) + (3x0.20) + (4x0.20) + (4x0.15) + (5x0.10) = 0.80 + 0.75 + 0.60 + 0.80 + 0.60 + 0.50 = 4.05 (Good)**

**Improvement focus:** Information Quality scored lowest. For future acquisition decisions, add a structured customer diligence process and assign a team member to specifically seek disconfirming evidence.
