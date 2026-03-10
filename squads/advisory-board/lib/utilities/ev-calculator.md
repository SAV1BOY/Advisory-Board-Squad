# Expected Value Calculator

## Purpose

A structured tool for calculating the expected value (EV) of decisions under uncertainty. Expected value forces rigorous thinking about probabilities and outcomes, preventing both over-optimism and analysis paralysis. Use this when a decision involves multiple possible outcomes with different probabilities and magnitudes.

## How to Use

### Step 1: Define the Decision
State the decision and the options being evaluated. Each option will get its own EV calculation.

### Step 2: Map Outcomes for Each Option
For each option, identify 3-5 realistic outcomes (not just best and worst case):
- **Best realistic case:** The upside if things go well (not a fantasy scenario).
- **Base case:** The most likely outcome given available information.
- **Downside case:** A plausible negative outcome.
- **Worst realistic case:** The floor — what happens if nearly everything goes wrong (not an apocalypse scenario).

### Step 3: Assign Probabilities
Assign a probability to each outcome. All probabilities for one option must sum to 100%.
- Use base rates when available (industry averages, historical data from your company).
- Adjust base rates for specific factors you know about this situation.
- If you cannot assign probabilities with any confidence, that itself is information — you need more data before deciding.

### Step 4: Quantify Outcomes
Express each outcome in the same unit (dollars, users, months of runway, etc.).
- Include both direct financial impact and quantified indirect impact where possible.
- For non-financial outcomes, use a consistent scoring scale (e.g., 1-10 impact score).

### Step 5: Calculate EV
For each option: EV = Sum of (Probability x Outcome Value) for all outcomes.

### Step 6: Adjust for Risk Tolerance
Raw EV may not tell the whole story. Adjust for:
- **Asymmetric downside:** If the worst case is existential (company dies), discount the EV heavily regardless of probability.
- **Optionality:** If an option preserves future flexibility, add value for that optionality.
- **Irreversibility:** Irreversible decisions with negative EV are much worse than reversible ones.

## Scale/Criteria

### Probability Confidence Scale
| Level | Description | How to Assign |
|-------|-------------|---------------|
| High confidence | Probabilities based on large datasets or repeated experience | Historical data, industry benchmarks, 50+ observations |
| Medium confidence | Probabilities based on limited data and informed judgment | Small sample data, expert estimates, 5-49 observations |
| Low confidence | Probabilities are educated guesses with wide uncertainty | No direct data, analogies from other domains, < 5 observations |

### Outcome Sizing Scale (when financial quantification is not possible)
| Score | Impact Description |
|-------|-------------------|
| +5 | Transformative positive — changes the company's trajectory |
| +3 | Strong positive — meaningful improvement to key metrics |
| +1 | Modest positive — noticeable but not strategic |
| 0 | Neutral — no material change |
| -1 | Modest negative — noticeable setback, recoverable |
| -3 | Strong negative — significant damage to key metrics |
| -5 | Catastrophic — threatens company survival |

## Scoring Guide

### EV Interpretation
| EV Result | Guidance |
|-----------|---------|
| Strongly positive (> 2x investment) | Proceed with confidence; main risk is not acting fast enough |
| Moderately positive (1-2x investment) | Proceed but monitor closely; have a kill plan |
| Marginally positive (0-1x investment) | Proceed only if option value is high or learning is valuable |
| Negative | Do not proceed unless there are unquantified strategic benefits that credibly offset |
| Strongly negative | Reject immediately; look for what bias was pushing toward this option |

### Common EV Pitfalls to Avoid
1. **Neglecting the null option:** Always calculate the EV of doing nothing.
2. **Overweighting the best case:** Most people assign the best case a higher probability than warranted.
3. **Ignoring correlation:** If multiple risks are correlated, the downside is worse than independent analysis suggests.
4. **False precision:** An EV of $1,247,333 implies precision that does not exist. Use ranges.
5. **Ignoring EV of information:** Sometimes the highest-EV action is to gather more data before deciding.

### Worked Example

**Decision:** Should we sponsor the industry conference for $50K?

| Outcome | Probability | Value | Weighted Value |
|---------|------------|-------|----------------|
| 3+ enterprise leads close ($300K+) | 15% | +$300,000 | +$45,000 |
| 1-2 leads, one closes ($80K) | 30% | +$80,000 | +$24,000 |
| Brand awareness, no direct leads | 35% | +$10,000 | +$3,500 |
| Poor execution, no ROI | 15% | -$50,000 | -$7,500 |
| Negative brand impression | 5% | -$100,000 | -$5,000 |

**EV = $45,000 + $24,000 + $3,500 - $7,500 - $5,000 = +$60,000**

**EV minus cost = $60,000 - $50,000 = +$10,000**

**Interpretation:** Marginally positive. Proceed only if the team executing has a strong track record at events. Consider a smaller presence ($20K) to improve the risk-reward ratio.

**EV of doing nothing:** $0 direct, but -$20,000 if competitors gain visibility advantage. Adjusted null EV: -$20,000.

**Comparative decision:** $10K EV of sponsoring vs. -$20K EV of not sponsoring. Net advantage of sponsoring: $30K. Proceed.
