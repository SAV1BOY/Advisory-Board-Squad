# Expected Value and Asymmetry Framework

## Purpose

This framework provides a rigorous approach to evaluating decisions through the lens of expected value (EV), probability distributions, and payoff asymmetry. Most people evaluate decisions based on the most likely outcome. Sophisticated decision-makers evaluate the full distribution of outcomes weighted by their probabilities, then look for convex opportunities (limited downside, unlimited upside) and avoid concave traps (limited upside, unlimited downside).

## When to Use

- When evaluating investments, bets, or resource allocation under uncertainty
- When comparing options with different risk profiles
- When the downside and upside are not symmetric
- During fundraising decisions (how much to raise, at what valuation)
- When choosing between "safe" and "risky" options
- For portfolio-level decisions (hiring pipeline, product bets, market entries)
- When team members disagree about risk tolerance

## Core Model

### Expected Value (EV)
EV = Sum of (Probability of each outcome × Value of each outcome)

A positive EV decision is one where the probability-weighted sum of all outcomes is favorable. Critically:
- A decision can be correct even if the outcome is bad (good process, bad luck)
- A decision can be wrong even if the outcome is good (bad process, good luck)
- Over many decisions, good EV thinking compounds; outcome-based thinking does not

### Distribution Shape Matters
Two bets can have the same EV but radically different risk profiles:
- **Normal distribution**: Outcomes cluster around the mean. Most business-as-usual decisions.
- **Fat-tailed distribution**: Extreme outcomes are more common than expected. Startups, venture, innovation.
- **Skewed distribution**: The mean and median diverge. Venture capital (most fail, a few 100x).

### Asymmetry: The Key Insight
The most important concept is payoff asymmetry:
- **Convex (positive asymmetry)**: Small downside, large upside. You want these. Examples: angel investing, learning a new skill, running small experiments.
- **Concave (negative asymmetry)**: Small upside, large downside. You want to avoid these. Examples: cutting corners on compliance, ignoring technical debt, over-leveraging.
- **Linear (symmetric)**: Upside and downside are proportional. Most routine decisions.

### The Barbell Strategy
Nassim Taleb's insight: combine extreme safety with extreme risk. Put 85-90% of resources in very safe positions, and 10-15% in maximally convex bets. Avoid the middle — moderate risk with moderate return often has hidden concavity.

## Steps

1. **Define the decision and enumerate possible outcomes.** List at least five outcomes ranging from worst case to best case. Do not cluster around the expected case — stretch the tails.

2. **Assign probabilities.** Use base rates where available. Be explicit: "I believe there is a 20% chance of outcome X." This forces precision and enables calibration over time.

3. **Assign values to each outcome.** Use dollars, time, strategic value, or a composite score. Be honest about the negative outcomes — most people under-weight the downside.

4. **Calculate expected value.** Multiply probability × value for each outcome and sum. This is your EV.

5. **Examine the distribution shape.** Is this a normal distribution or a fat-tailed one? If fat-tailed, the EV calculation is less reliable — focus on the tails.

6. **Assess asymmetry.** Map the payoff curve: Is the upside capped or uncapped? Is the downside bounded or unbounded? What is the maximum loss? What is the maximum gain?

7. **Apply the Kelly Criterion (optional).** For repeated decisions, the Kelly Criterion tells you the optimal bet size: f* = (bp - q) / b, where b = odds, p = probability of winning, q = probability of losing. Never bet more than Kelly — and most practitioners bet half-Kelly for safety.

8. **Make the portfolio-level decision.** Individual decisions should be evaluated at the portfolio level. A single negative-EV bet can be correct if it provides diversification or optionality at the portfolio level.

## Application Guidelines

### For Board Advisors
- When a founder presents a binary decision, ask: "What's the expected value of each path?" This reframes emotional decisions into analytical ones.
- Help founders identify convex bets — opportunities where they can invest small amounts to learn before committing large amounts.
- Push back on concave decisions disguised as "playing it safe." Not investing in growth can be the riskiest decision of all.

### For Fundraising
- Raising capital is a convex bet if the dilution cost is small relative to the acceleration potential. It is concave if the company takes money it doesn't need at terms that constrain future options.
- Model three fundraising scenarios: under-raise, target-raise, over-raise. Calculate the EV of each.

### For Hiring
- A great hire is a convex bet: bounded downside (salary + severance), potentially unbounded upside (transformative contribution). This is why the bar should be high — the asymmetry only works with exceptional candidates.

## Common Mistakes

1. **Confusing expected value with the most likely outcome.** The EV of a startup may be very high even though the most likely outcome is failure, because the successes are so large.

2. **Ignoring fat tails.** Standard business planning assumes normal distributions. Startups, pandemics, and market crashes live in fat-tailed distributions where extreme events dominate.

3. **Treating all risk as bad.** Convex risk is good. The goal is not to minimize risk but to maximize the ratio of upside to downside.

4. **Failing to size bets appropriately.** Even positive-EV bets can be ruinous if sized too large. The Kelly Criterion provides mathematical discipline.

5. **Anchoring on sunk costs.** Prior investment does not change the EV of future decisions. Evaluate each decision fresh based on current probabilities and payoffs.

6. **Neglecting the portfolio view.** A single decision may look bad in isolation but be correct in the context of the overall portfolio. Venture capitalists understand this; operators often don't.

7. **Precision bias.** Calculating EV to two decimal places when probability estimates are barely accurate to one significant figure. The framework is for directional clarity, not false precision.

## Output Format

```markdown
# EV Analysis: [Decision Name]

**Date:** YYYY-MM-DD
**Analyst:** [Name]

## Decision
[What is being decided]

## Outcome Distribution

| Outcome | Description | Probability | Value ($) | EV Contribution |
|---------|-------------|-------------|-----------|-----------------|
| Best    |             | %           |           |                 |
| Good    |             | %           |           |                 |
| Base    |             | %           |           |                 |
| Bad     |             | %           |           |                 |
| Worst   |             | %           |           |                 |
| **Total EV** |        | 100%        |           | **$X**          |

## Asymmetry Assessment
- **Maximum downside:** $X (probability: Y%)
- **Maximum upside:** $X (probability: Y%)
- **Asymmetry ratio:** Upside/Downside = X:1
- **Classification:** Convex / Concave / Linear

## Distribution Shape
- [ ] Normal — use EV directly
- [ ] Fat-tailed — focus on tail scenarios
- [ ] Skewed — note divergence between mean and median

## Bet Sizing
- **Recommended allocation:** $X (Y% of available resources)
- **Kelly fraction:** Z%
- **Rationale:** [Why this size]

## Decision
[Go / No-Go / Conditional, with reasoning]
```

## Related Frameworks

- **Power Law Thinking** — Most startup outcomes follow power laws, not normal distributions
- **Reversible-Irreversible Decisions** — Irreversible decisions require more rigorous EV analysis
- **Scenario Planning** — Use to generate the outcome distribution for EV calculation
- **Base Rates and Reference Class** — Source of probability estimates for EV calculation
- **Opportunity Cost Framework** — The "value" in EV must account for what you are not doing
- **Regret Minimization Framework** — Complements EV with an emotional/long-term check
- **Thiel Power Law Portfolio** — Portfolio-level application of asymmetric thinking
