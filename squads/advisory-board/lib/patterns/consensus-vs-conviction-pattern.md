# Consensus vs. Conviction Pattern

## Pattern Name

Consensus vs. Conviction — a decision-routing pattern that matches the decision-making method to the decision type, preventing both tyranny of the majority and tyranny of the individual.

## When to Use

- The team or board is unsure whether a decision should be made by consensus, majority vote, or individual conviction.
- Decisions are consistently slow because consensus is the default for everything.
- A strong leader is overriding the group on decisions that should be collaborative.
- There is confusion or resentment about how decisions get made.
- The organization is growing and the informal decision-making culture is breaking down.

Do NOT use when:
- The decision-making authority is already clearly defined and accepted by all parties.
- Legal or regulatory requirements dictate the decision process (e.g., board votes).

## Structure

```
1. CLASSIFY   → Determine the decision type and appropriate method
2. MATCH      → Assign the right process to the right decision
3. EXECUTE    → Run the matched process
4. DOCUMENT   → Record the method used and why
5. CALIBRATE  → Review whether the method matched well
```

## Steps

### Step 1: Classify the Decision

Map the decision along two axes:

**Axis 1 — Reversibility:**
- **Reversible (two-way door):** Can be undone with manageable cost.
- **Irreversible (one-way door):** Cannot be meaningfully undone once executed.

**Axis 2 — Information Distribution:**
- **Concentrated knowledge:** One person or small group has significantly more relevant information.
- **Distributed knowledge:** The relevant information is spread across many people.

This creates a 2x2 matrix:

| | Concentrated Knowledge | Distributed Knowledge |
|---|---|---|
| **Reversible** | Conviction — Fast individual call | Consent — Quick group check |
| **Irreversible** | Conviction + Advisory — Leader decides with structured input | Consensus — Full alignment required |

### Step 2: Match the Method

**Method 1: Conviction (Individual Decision)**
- Used when: One person has the most context, and the decision is reversible.
- Process: The person with the most context decides and informs. No meeting needed.
- Speed: Minutes to hours.
- Example: Product manager choosing which feature to build next sprint.
- Risk to watch: Overconfidence. Even conviction-based decisions benefit from one sanity check.

**Method 2: Consent (No Objections)**
- Used when: Knowledge is distributed and the decision is reversible.
- Process: Propose a decision. Ask "Does anyone have a material objection?" If no objections, proceed. Objections must be substantive (not preference-based).
- Speed: Hours to 1 day.
- Example: Changing the team's meeting schedule, adopting a new tool.
- Risk to watch: Silence taken as consent when people are actually disengaged.

**Method 3: Conviction + Advisory (Informed Individual Decision)**
- Used when: One person has the most context, but the decision is irreversible.
- Process: The decision-maker actively solicits input from 3-5 advisors, then decides alone. Input is advisory, not binding.
- Speed: Days.
- Example: CEO deciding to enter a new market after consulting the board.
- Risk to watch: Collecting input as theater — the decision-maker must genuinely consider the advice.

**Method 4: Consensus (Full Alignment)**
- Used when: Knowledge is distributed and the decision is irreversible.
- Process: Structured discussion until all parties can live with and commit to the decision (not necessarily their first choice).
- Speed: Days to weeks.
- Example: Choosing the company's strategic direction for the next 3 years.
- Risk to watch: Consensus degenerating into compromise that pleases no one. True consensus means everyone can commit fully, not that everyone got part of what they wanted.
- Fallback: If consensus cannot be reached within the time box, escalate to Conviction + Advisory with the most senior leader as decision-maker.

### Step 3: Execute the Matched Process
- Announce the method before beginning: "This is a conviction decision — I will make the call after hearing your input" or "This requires consensus — we need everyone aligned before we move."
- Setting expectations about the method prevents process frustration. Most decision conflict is actually process conflict: people disagree about how the decision should be made, not just what the decision should be.
- Run the process according to its rules. Do not switch methods mid-stream without acknowledging it.

### Step 4: Document the Method
- In the decision registry, record:
  - The decision type classification (reversibility + knowledge distribution).
  - The method used (conviction, consent, conviction + advisory, consensus).
  - Whether any method override occurred and why.
  - The outcome and participant satisfaction with the process.

### Step 5: Calibrate Over Time
- Quarterly, review the decision registry for patterns:
  - Are we using consensus for decisions that should be conviction-based? (Symptom: slow decisions on reversible issues.)
  - Are we using conviction for decisions that need consensus? (Symptom: frequent reversals, team resentment.)
  - Are the right people being designated as decision-makers for conviction-based decisions?
  - Is consent being used authentically or is silence being misread?
- Adjust the classification framework based on organizational learning.

## Anti-Patterns

| Anti-Pattern | Description | Consequence |
|-------------|-------------|-------------|
| Consensus on everything | Every decision requires full alignment | Decision paralysis; speed collapses |
| Conviction on everything | One person decides everything regardless of type | Team disengagement; blind spots; single point of failure |
| False consensus | Agreement is declared but participants did not truly commit | Decisions are undermined in execution |
| Consensus as compromise | Everyone gets a piece of what they want, no one gets what is needed | Mediocre outcomes that satisfy no one |
| Method ambiguity | No one knows how a decision will be made until after it is made | Frustration, political maneuvering, relitigating |
| Conviction without advisory | Irreversible decisions made without structured input | Avoidable mistakes; team feels excluded |

## Examples

### Example 1: Mapping Real Decisions

| Decision | Reversibility | Knowledge | Method |
|----------|--------------|-----------|--------|
| Sprint priorities | Reversible | Concentrated (PM) | Conviction |
| Office snack selection | Reversible | Distributed | Consent |
| VP Engineering hire | Irreversible | Concentrated (CEO) | Conviction + Advisory |
| Company mission change | Irreversible | Distributed | Consensus |
| Pricing tier experiment | Reversible | Distributed | Consent |
| $10M acquisition | Irreversible | Concentrated (CEO + CFO) | Conviction + Advisory |
| Remote work policy | Semi-reversible | Distributed | Consent (with trial period) |

### Example 2: Method Selection in Action

**Situation:** The board is debating whether to raise a Series B now or wait 6 months.

**Classification:**
- Reversibility: Largely irreversible (dilution cannot be undone; market timing is not controllable).
- Knowledge: Distributed — the CEO understands operational needs, the CFO understands financial position, the board advisor understands market conditions, the investors have pattern recognition.

**Method selected:** Consensus with a time box of one board meeting cycle. If consensus is not reached, fallback to Conviction + Advisory with CEO as decision-maker.

**Process:** Board meeting with structured input from each perspective. CFO presents financial scenarios. CEO presents operational needs. Advisor presents market conditions. Discussion targets alignment. Board reaches consensus to raise in Q3 with a bridge note to cover Q2. All members commit.
