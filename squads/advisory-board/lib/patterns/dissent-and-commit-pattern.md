# Dissent and Commit Pattern

## Pattern Name

Dissent and Commit — structured disagreement followed by unified execution.

## When to Use

- A decision must be made and reasonable people disagree on the best path.
- The cost of delayed decision exceeds the cost of a suboptimal choice.
- The team needs alignment on execution even when consensus on direction is impossible.
- A leader must override majority opinion based on conviction or information asymmetry.
- Post-decision undermining or passive resistance is a known cultural risk.

Do NOT use when:
- The decision is easily reversible and experimentation is possible (use `reversible-decision-pattern.md` instead).
- The dissenter has information that has not been fully heard — that is a process failure, not a dissent situation.
- The stakes are existential and the dissenter may be right — run a pre-mortem first.

## Structure

```
1. FRAME    → Define the decision and why it must be made now
2. VOICE    → Structured opportunity for all perspectives to be heard
3. RECORD   → Capture dissenting views in writing
4. DECIDE   → Decision-maker makes the call with rationale
5. COMMIT   → Dissenters explicitly commit to execution
6. MONITOR  → Track conditions that would vindicate the dissent
```

## Steps

### Step 1: Frame the Decision
- State the decision clearly: "We are deciding whether to [X] or [Y]."
- State the deadline: "This decision must be made by [date] because [reason]."
- State the decision authority: "After discussion, [Name] will make the final call."
- State the stakes: "This is a [reversible/irreversible] decision with [time horizon] impact."

### Step 2: Voice All Perspectives
- Each participant states their position in 2-3 minutes, uninterrupted.
- Facilitator ensures the strongest version of each argument is heard (steelmanning, not strawmanning).
- Ask explicitly: "Who disagrees and has not yet spoken?"
- No rebuttals during the voicing round — this is about surfacing views, not winning arguments.

### Step 3: Record the Dissent
- Dissenting views are captured in writing with the dissenter's name attached.
- The record includes: (a) the dissenting position, (b) the key evidence or reasoning, (c) the predicted consequence of ignoring the dissent.
- The dissenter reviews the written record for accuracy before the decision is finalized.
- This record is stored in the decision registry, not buried.

### Step 4: Make the Decision
- The decision-maker states the decision and the rationale.
- The rationale must explicitly address the dissent: "I heard [Name]'s concern about [X]. I am proceeding because [Y]."
- If the decision-maker agrees with the dissent but overrides it, they explain why (e.g., "I agree this is risky but the cost of inaction is higher").

### Step 5: Commit to Execution
- Each participant, including dissenters, states: "I commit to executing this decision fully."
- Commitment means: no public or private undermining, no "I told you so" if it fails, full effort in execution.
- If someone cannot commit, that is escalated immediately — it does not fester.
- The commit statement is recorded alongside the decision.

### Step 6: Monitor for Dissent Vindication
- Define specific, observable conditions under which the dissenter's concern would be validated.
- Schedule a review at a predetermined date to check these conditions.
- If conditions are met, the original dissent is reopened and the decision is reconsidered — no stigma, no blame.
- This step is what makes the pattern trustworthy: dissenters commit because they know their view has a fair path back.

## Anti-Patterns

| Anti-Pattern | Description | Consequence |
|-------------|-------------|-------------|
| Performative dissent | Dissent is "allowed" but everyone knows it will be ignored | People stop raising concerns; groupthink sets in |
| Commit without voice | Decision is announced and compliance is demanded without hearing views | Passive resistance, execution sabotage |
| Dissent without commit | People voice disagreement but never actually commit to execution | Decisions are relitigated endlessly |
| Anonymous dissent | Dissent is recorded but not attributed | No accountability, no ability to follow up |
| Missing the monitor step | Decision is made, dissent is recorded, but no review is scheduled | Dissenters feel their views are captured but never acted on |
| Weaponized dissent | "I dissented" is used as political insurance rather than genuine disagreement | Trust erodes; pattern becomes cynical |

## Examples

### Example 1: Product Direction Disagreement

**Frame:** "We must decide by Friday whether to build AI features in-house or integrate a third-party API. CTO will make the final call."

**Voice:**
- VP Product: "Third-party API gets us to market 4 months faster. Speed matters more than control right now."
- CTO: "Building in-house gives us a defensible moat. The API creates a dependency that will cost us later."
- CEO: "I lean toward speed but want to hear both sides fully."

**Record:** VP Product dissents from building in-house. Predicts: "We will miss the market window and a competitor will ship first. The moat argument assumes we have 18 months of runway; we have 13."

**Decision:** CTO decides to build in-house with a 90-day checkpoint. Rationale: "VP Product's timeline concern is valid. If we have not shipped v1 in 90 days, we pivot to the API integration."

**Commit:** VP Product commits: "I will execute the in-house plan fully and give the team every resource they need for the next 90 days."

**Monitor:** At day 90, if v1 is not shippable, VP Product's dissent is reopened and the API path is executed.

### Example 2: Board-Level Strategic Disagreement

**Frame:** "The board must decide whether to accept the $45M acquisition offer or continue operating independently. CEO recommends declining."

**Dissent recorded:** Board member A believes the offer is fair given market conditions and runway. Predicts: "If we decline and the market turns, we will raise at a lower valuation within 12 months."

**Decision:** Board votes 4-1 to decline. CEO acknowledges the risk and commits to hitting $8M ARR within 12 months as the validation milestone.

**Monitor:** If ARR is below $6M at the 9-month mark, the board reopens the conversation about strategic alternatives.
