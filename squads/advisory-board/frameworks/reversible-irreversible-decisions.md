# Reversible vs. Irreversible Decisions Framework

## Purpose

This framework, inspired by Jeff Bezos's Type 1/Type 2 decision model, provides a systematic method for classifying decisions by their reversibility and calibrating the appropriate level of analysis, speed, and authority for each. The core insight: most organizations apply heavyweight processes to all decisions, creating bottlenecks. The solution is to match decision process intensity to decision reversibility. Type 1 (irreversible) decisions deserve deep analysis. Type 2 (reversible) decisions deserve speed.

## When to Use

- When deciding how much analysis a decision requires before committing
- When teams are stuck in analysis paralysis on decisions that could be easily reversed
- When a leader needs to determine whether to delegate a decision or make it personally
- During board discussions to calibrate the appropriate level of governance oversight
- When building organizational decision-making culture and norms

## Core Model

### Type 1 Decisions (Irreversible — One-Way Doors)
- Cannot be undone or can only be undone at enormous cost
- Consequences persist for years or permanently
- Require careful, deliberate analysis
- Should involve senior leadership and diverse perspectives
- Examples: Major acquisitions, selling the company, entering regulated markets, key executive hires, fundamental architecture choices

### Type 2 Decisions (Reversible — Two-Way Doors)
- Can be reversed with minimal cost and friction
- Consequences are temporary or easily modified
- Should be made quickly by empowered individuals or small teams
- Bias should be toward action and learning
- Examples: Pricing experiments, feature launches with kill switches, hiring contractors, A/B tests, most marketing campaigns, process changes

### The Reversibility Spectrum
Most decisions are not purely Type 1 or Type 2. They exist on a spectrum:

```
Fully Irreversible ←————————————————→ Fully Reversible
     Type 1          Mostly 1    Mostly 2      Type 2
     |                  |            |              |
  Acquisition    Key hire     Pricing change   A/B test
  Market exit    Platform     New channel      Blog post
  Major debt     migration    Vendor switch    Meeting format
```

### The Speed-Quality Tradeoff
- Type 1 decisions: Optimize for quality. Take the time needed. Gather diverse input. Sleep on it.
- Type 2 decisions: Optimize for speed. Decide with ~70% of the information you wish you had. The cost of delay exceeds the cost of a wrong decision.

## Steps

1. **State the decision clearly.** Write it in one sentence. Ambiguous decisions cannot be classified.

2. **Assess reversibility.** Ask five questions:
   - Can we undo this decision within 90 days?
   - What is the financial cost of reversal?
   - What is the reputational cost of reversal?
   - What organizational disruption does reversal cause?
   - Are there contractual or legal barriers to reversal?

3. **Classify the decision.** Based on the reversibility assessment, place it on the spectrum. When in doubt, classify it as more reversible than you think — most people overestimate irreversibility.

4. **Match the process to the classification.**

   | Aspect | Type 1 | Type 2 |
   |--------|--------|--------|
   | Decision maker | CEO/Board | Team lead or individual |
   | Analysis depth | Full Decision Memo | Verbal or one-paragraph |
   | Stakeholder input | Broad, diverse | Narrow, relevant |
   | Timeline | Days to weeks | Hours to days |
   | Approval layers | Multiple | Zero to one |
   | Documentation | Formal, archived | Lightweight, optional |

5. **For Type 1 decisions:** Apply the full Decision Memo Framework. Run a Pre-Mortem. Seek dissenting views. Set a review trigger.

6. **For Type 2 decisions:** Decide now. Set a check-in date to evaluate results. Empower the person closest to the information to make the call.

7. **Build reversibility into decisions when possible.** Can you structure a Type 1 decision as a series of Type 2 decisions? Phased rollouts, pilot programs, and options-based approaches convert irreversible decisions into reversible ones.

## Application Guidelines

### For Board Advisors
- Most board time should be spent on Type 1 decisions. If the board is debating Type 2 decisions, the governance model is broken.
- Help founders distinguish between the two types. First-time founders often treat every decision as Type 1 (analysis paralysis) or every decision as Type 2 (recklessness).
- When a founder brings a Type 2 decision to the board, redirect: "This is a two-way door. You don't need our input — go decide and tell us what you learned."

### For Founders
- Default to Type 2 unless proven otherwise. Most decisions are more reversible than they feel in the moment.
- Use Type 1 classification sparingly — it should apply to fewer than 10% of your decisions.
- Build a culture where Type 2 decisions are delegated deep into the organization. Your competitive advantage is decision speed.

### For Teams
- Before escalating a decision, ask: "Is this a one-way door?" If not, make the call yourself.
- Document Type 1 decisions rigorously. Document Type 2 decisions lightly — a Slack message or brief note suffices.

## Common Mistakes

1. **Treating all decisions as Type 1.** This is the most common organizational failure. It leads to bottlenecks, slow execution, and learned helplessness.

2. **Treating Type 1 decisions as Type 2.** Less common but more dangerous. Moving too fast on irreversible decisions causes catastrophic, unrecoverable errors.

3. **Confusing emotional weight with irreversibility.** A decision can feel heavy (laying off a team member) while being structurally reversible (you can rehire). Classify based on structural reversibility, not emotional intensity.

4. **Ignoring partial reversibility.** Most decisions can be partially reversed. A bad hire can be let go. A bad product launch can be pivoted. The question is the cost and friction of reversal, not whether reversal is theoretically possible.

5. **Failing to build reversibility in.** Many Type 1 decisions can be restructured as Type 2 through pilots, options, sunset clauses, or phased approaches.

6. **Centralizing Type 2 decisions.** If the CEO must approve every Type 2 decision, the organization cannot move faster than the CEO's calendar. Delegate aggressively.

## Output Format

```markdown
# Decision Classification: [Decision Name]

**Date:** YYYY-MM-DD
**Decision:** [One sentence]

## Reversibility Assessment

| Question | Answer | Score (1-5) |
|----------|--------|-------------|
| Can we undo within 90 days? | | |
| Financial cost of reversal? | | |
| Reputational cost of reversal? | | |
| Organizational disruption of reversal? | | |
| Legal/contractual barriers to reversal? | | |
| **Average Score** | | **X.X** |

## Classification
- [ ] Type 1 (Irreversible) — Score 4-5
- [ ] Mostly Type 1 — Score 3-4
- [ ] Mostly Type 2 — Score 2-3
- [ ] Type 2 (Reversible) — Score 1-2

## Prescribed Process
- **Decision maker:** [Name/role]
- **Analysis required:** [Full memo / Brief writeup / Verbal]
- **Timeline:** [Decide by date]
- **Input needed from:** [Names]

## Can We Increase Reversibility?
- [ ] Pilot or phased approach possible?
- [ ] Sunset clause or kill switch available?
- [ ] Options-based structure feasible?
```

## Related Frameworks

- **Decision Memo Framework** — The full process for Type 1 decisions
- **Expected Value and Asymmetry** — Irreversible decisions with asymmetric payoffs need the most care
- **Pre-Mortem Framework** — Essential companion for Type 1 decisions
- **Regret Minimization Framework** — Particularly useful for Type 1 decisions with long time horizons
- **Operating System of Meetings** — Type 1 decisions should have dedicated decision meetings
- **Second-Order Thinking** — Apply to Type 1 decisions to trace downstream consequences
