# Scenario Table

## Purpose

A structured tool for mapping multiple future scenarios against current decisions. Scenario tables force decision-makers to think through how their choices perform across a range of plausible futures rather than optimizing for a single predicted outcome. This reduces fragility and surfaces hedging opportunities.

## How to Use

### Step 1: Define the Decision Context
State the decision being evaluated and the time horizon over which scenarios are relevant.

### Step 2: Identify Key Uncertainties
List the 2-3 most impactful uncertainties that could shape outcomes. These should be factors outside your control that meaningfully affect the decision's success. Use only 2-3 to keep the table manageable — more creates combinatorial explosion without proportionate insight.

### Step 3: Define Scenario Columns
Create 3-5 scenarios, each representing a distinct, internally consistent combination of the key uncertainties. Each scenario should be plausible, not just possible. Include at least one optimistic, one pessimistic, and one surprising scenario.

### Step 4: Define Option Rows
List the decision options being considered (including "do nothing").

### Step 5: Fill the Matrix
For each option-scenario combination, describe the likely outcome. Include both quantitative estimates (revenue, cost, timeline) and qualitative impact (strategic position, team morale, customer trust).

### Step 6: Evaluate Robustness
Look across columns: which option performs reasonably well in the most scenarios? This is the robust option. The option that performs best in one scenario but catastrophically in another is the fragile option.

## Scale/Criteria

### Scenario Plausibility Scale
| Rating | Description |
|--------|-------------|
| Highly plausible (> 30%) | Could easily happen based on current trends |
| Plausible (10-30%) | Requires some things to change but within reason |
| Low probability but high impact (< 10%) | Unlikely but if it happens, everything changes |

### Outcome Rating per Cell
| Rating | Meaning |
|--------|---------|
| Strong Win | Option thrives in this scenario — significant upside captured |
| Moderate Win | Option performs well — positive but not transformative |
| Neutral | Option neither gains nor loses materially |
| Moderate Loss | Option underperforms — manageable but painful setback |
| Severe Loss | Option fails badly — significant damage to company |

## Scoring Guide

### Interpreting the Completed Table

**Dominant option:** One option is equal or better than alternatives in every scenario. Choose it. (Rare in practice.)

**Robust option:** One option avoids severe losses in all scenarios, even if it does not win big in any. Preferred for irreversible decisions and organizations with limited runway.

**High-variance option:** One option wins big in some scenarios and loses big in others. Preferred only when: (a) the organization can absorb the downside, (b) the upside is transformative, (c) the probabilities favor the upside scenarios.

**Hedged portfolio:** No single option is robust. Consider combining options (e.g., invest in Option A at 70% and Option B at 30%) or sequencing (start with Option A, switch to B if Scenario 3 materializes).

### Template

```
Decision: [What are we deciding?]
Time horizon: [Over what period?]
Key uncertainties: [U1], [U2]

| Option / Scenario | S1: [Name] (prob%) | S2: [Name] (prob%) | S3: [Name] (prob%) | S4: [Name] (prob%) |
|---|---|---|---|---|
| Option A: [Name] | [Outcome] | [Outcome] | [Outcome] | [Outcome] |
| Option B: [Name] | [Outcome] | [Outcome] | [Outcome] | [Outcome] |
| Option C: Do Nothing | [Outcome] | [Outcome] | [Outcome] | [Outcome] |
```

### Worked Example

**Decision:** Whether to launch in the European market in Q3 2026
**Time horizon:** 18 months
**Key uncertainties:** (1) EU data regulation tightening, (2) Competitor entry timing

| Option / Scenario | S1: Stable regulation, no competitor (35%) | S2: Stable regulation, competitor enters Q4 (25%) | S3: Tighter regulation, no competitor (20%) | S4: Tighter regulation, competitor enters Q4 (20%) |
|---|---|---|---|---|
| A: Launch Q3 full-scale | Strong Win: First-mover capture, $2M ARR by Q4 2027 | Moderate Win: Established before competitor, $1.2M ARR | Moderate Loss: Compliance costs consume margin, $400K ARR | Severe Loss: Compliance + competitive pressure, -$300K |
| B: Launch Q3 limited pilot | Moderate Win: Learn fast, $600K ARR, scale in Q1 2027 | Moderate Win: Some learning, pivot if competitor wins | Neutral: Small exposure to compliance costs, $200K ARR | Moderate Loss: Limited traction, -$100K, but contained |
| C: Wait until Q1 2027 | Moderate Loss: Window may close, competitor builds lead | Severe Loss: Competitor has 6-month head start | Moderate Win: Regulation clarifies, enter with certainty | Neutral: Both delayed, level playing field |

**Analysis:** Option B (limited pilot) is the most robust — it avoids severe losses in every scenario while preserving the ability to scale quickly in favorable scenarios. Option A is higher variance with a severe loss in S4 (20% probability). Option C has a severe loss in S2 (25% probability).

**Recommendation:** Launch limited pilot in Q3 (Option B). Set scaling trigger: if S1 or S2 materializes, scale by Q1 2027. Set kill trigger: if S4 materializes and pilot losses exceed $100K, exit.
