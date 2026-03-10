# Base Rates and Reference Class Forecasting

## Purpose

This framework provides a disciplined approach to making predictions by starting with the outside view — what actually happened in similar situations — before adjusting for the specifics of the current case. Humans are systematically overconfident when forecasting from the inside view (their specific situation). Reference class forecasting corrects this by anchoring predictions to empirical base rates from comparable cases. Daniel Kahneman calls this the single most important corrective to planning fallacy and overconfidence.

## When to Use

- When forecasting timelines, budgets, revenues, or growth rates
- When evaluating a startup's probability of success
- When a founder says "but we're different" (they usually aren't)
- During fundraising to set realistic milestones
- When calibrating confidence in any prediction
- Before accepting any projection that feels optimistic
- When building financial models or projections for board review

## Core Model

### The Inside View vs. The Outside View

**Inside View (Default):** You examine the specific details of your situation — your team, your product, your market — and construct a narrative about what will happen. This feels thorough but systematically produces overconfident, optimistic forecasts.

**Outside View (Reference Class):** You identify a class of similar situations, look at the distribution of actual outcomes, and use that distribution as your starting point. This feels impersonal but is dramatically more accurate.

### Reference Class Forecasting Process

1. **Identify the reference class**: What is the relevant category of similar past situations?
2. **Obtain the base rate**: What is the statistical distribution of outcomes in that reference class?
3. **Anchor on the base rate**: Start your forecast at the base rate, not at your inside-view estimate.
4. **Adjust for specifics**: Move from the base rate only when you have strong, specific evidence for adjustment.

### Key Base Rates Every Advisor Should Know

**Startups:**
- ~90% of startups fail
- Median time to Series A from seed: 18-24 months
- Median time from founding to acquisition: 7 years
- Median time from founding to IPO: 8-11 years
- ~75% of venture-backed startups return $0 to investors

**Projects:**
- Software projects average 2.5x original timeline estimates
- Construction projects average 1.5x original budget
- Large IT projects: 45% over budget, 7% over time, 56% deliver less value than predicted

**Markets:**
- New product categories take 5-7 years to mature
- Most market forecasts by analysts are wrong by 40%+
- The average company in the S&P 500 stays for ~20 years (down from 60 years in 1960)

## Steps

1. **Define what you are forecasting.** Be precise: "Time to reach $1M ARR" not "when we'll be successful." Vague forecasts cannot be calibrated.

2. **Identify the reference class.** What category of similar efforts should you compare to? Be specific but not so narrow that the sample size is meaningless. "B2B SaaS companies targeting mid-market" is better than "companies" or "B2B SaaS companies targeting mid-market healthcare in Southeast Asia."

3. **Research the base rate.** Find empirical data on the distribution of outcomes in your reference class. Use industry reports, academic research, portfolio data, or historical records. If exact data doesn't exist, use the closest available proxy.

4. **Anchor your forecast on the base rate.** Write down the base rate prediction before considering any inside-view information. This is your starting point.

5. **List your specific adjustments.** What concrete, verifiable factors make your situation different from the reference class? Each adjustment should be:
   - Specific (not "we have a great team")
   - Evidenced (not assumed)
   - Directional (does it push the forecast up or down?)
   - Sized (by how much?)

6. **Adjust conservatively.** The research is clear: people over-adjust from base rates. Make your adjustments smaller than they feel. A good rule: cut your adjustment in half.

7. **Express as a range, not a point.** Provide a 50% confidence interval and a 90% confidence interval. If your 90% range is too narrow, you are overconfident.

8. **Track and calibrate.** Record your forecasts and compare them to outcomes. Over time, you can calibrate your adjustment process. The goal is to be right 50% of the time on your 50% confidence intervals and 90% of the time on your 90% intervals.

## Application Guidelines

### For Board Advisors
- When a founder presents projections, ask: "What's the base rate for companies at your stage in your category?" If they don't know, help them find it.
- Use base rates to set milestone expectations. "80% of seed-stage companies take 18-24 months to reach Series A — let's plan for that, not for your optimistic 9-month timeline."
- Maintain a personal database of base rates across your advisory portfolio. Your pattern recognition is one of the most valuable things you offer.

### For Financial Planning
- Build financial models with base-rate scenarios as the default case. Let the optimistic case be the inside-view projection. This creates a natural range.
- When reviewing projections, apply the "outside view test": Would you bet your own money on this projection at even odds?

### For Hiring
- Reference class: What is the typical success rate for this type of hire at this stage of company? What is the typical ramp time? Use these as defaults.

## Common Mistakes

1. **Ignoring the base rate entirely.** The most common error. Most forecasts are pure inside-view narratives with no empirical grounding.

2. **Choosing a flattering reference class.** Selecting only successful comparables ("We're like Slack in 2015") instead of the full distribution (most enterprise messaging tools failed).

3. **Over-adjusting from the base rate.** Everyone believes their situation is special. Usually it isn't. The research shows that adjustments from base rates should be much smaller than people's instincts suggest.

4. **Using base rates for situations that are truly unprecedented.** Some situations genuinely have no reference class. In those cases, acknowledge radical uncertainty rather than forcing a false base rate.

5. **Confusing conditional and unconditional base rates.** The base rate for "startup success" is ~10%. The base rate for "startup success given $10M ARR at 150% growth" is much higher. Use the most specific conditional base rate available.

6. **Point estimates instead of distributions.** The base rate is not a single number — it is a distribution. Report the full range: 10th percentile, median, 90th percentile.

7. **Anchoring on a single data point.** "My friend's company took 6 months to hit Series A" is an anecdote, not a base rate. Base rates require sample sizes.

## Output Format

```markdown
# Reference Class Forecast: [What We Are Forecasting]

**Date:** YYYY-MM-DD
**Forecaster:** [Name]

## Forecast Target
[Precise statement of what is being forecasted and the timeframe]

## Reference Class Selection
- **Reference class:** [Description of comparable situations]
- **Sample size:** [How many cases in the reference class]
- **Data source:** [Where the base rate data comes from]

## Base Rate Distribution
| Percentile | Value |
|------------|-------|
| 10th       |       |
| 25th       |       |
| 50th (median) |    |
| 75th       |       |
| 90th       |       |

## Inside-View Adjustments

| Factor | Direction | Magnitude | Evidence |
|--------|-----------|-----------|----------|
|        | +/-       | Small/Med/Large | |

## Adjusted Forecast
- **50% confidence interval:** [Low] to [High]
- **90% confidence interval:** [Low] to [High]
- **Point estimate (median):** [Value]

## Comparison to Inside-View Forecast
- **Inside-view estimate:** [What the team/founder predicted]
- **Base-rate estimate:** [What the reference class predicts]
- **Gap:** [Difference and likely explanation]

## Calibration Record
[Track actual outcomes vs. forecasts over time]
```

## Related Frameworks

- **Scenario Planning** — Use base rates to bound scenario ranges
- **Expected Value and Asymmetry** — Base rates provide the probability inputs for EV calculations
- **Pre-Mortem Framework** — Base rates reveal the most common failure modes
- **Second-Order Thinking** — Base rates help predict second-order effects more accurately
- **Munger Psychology of Misjudgment** — Overconfidence bias is the primary reason people ignore base rates
- **Decision Memo Framework** — Every Decision Memo should include a base-rate check on key assumptions
