# Dalio Believability-Weighted Voting

## Purpose

Believability-weighted voting is Ray Dalio's method for resolving disagreements by weighting each person's opinion according to their demonstrated competence in the relevant domain. Unlike democratic voting (one person, one vote) or autocratic decision-making (the boss decides), believability-weighted voting gives more weight to people who have a proven track record and can logically explain their reasoning. This produces better decisions than either consensus or hierarchy while maintaining the benefits of diverse input.

## When to Use

- When a group disagrees on a significant decision and needs a resolution mechanism
- When expertise varies widely among decision participants
- During board discussions where different advisors have different domains of expertise
- When avoiding both the tyranny of the majority (bad consensus) and the tyranny of the HiPPO (Highest Paid Person's Opinion)
- When building a culture of meritocratic decision-making
- When the quality of the decision matters more than the speed

## Core Model

### Believability Criteria
A person is "believable" on a topic when they meet at least two of three criteria:
1. **Track record**: They have repeatedly succeeded in the domain in question
2. **Logic**: They can articulate a clear, logical reasoning chain for their position
3. **Openness**: They have demonstrated the ability to change their mind when presented with better arguments

### The Voting Process
1. Each person states their position with reasoning
2. Each person's vote is weighted by their believability score on the specific topic
3. The believability-weighted result is calculated
4. If the result conflicts with the unweighted result, discuss why — the gap reveals important information
5. The decision-maker considers the weighted result alongside other factors

### Believability Is Topic-Specific
A person who is highly believable on financial strategy may have low believability on technical architecture. Believability scores must be assessed per topic, not per person globally.

### The Spectrum of Decision Methods

| Method | How It Works | Best When |
|--------|-------------|-----------|
| Autocratic | Boss decides | Speed critical, boss is expert |
| Democratic | Equal votes | Symbolic alignment, low stakes |
| Consensus | Everyone agrees | Commitment critical, small group |
| **Believability-weighted** | **Expert votes count more** | **Quality critical, expertise varies** |

## Steps

1. **Define the question.** State the specific decision to be made. It must be precise enough to vote on.

2. **Identify voters.** Who has relevant knowledge or stake in this decision?

3. **Assess believability for each voter on this specific topic.** Score each person 1-5 on:
   - Track record in this domain
   - Quality of their reasoning on this topic
   - Demonstrated openness to being wrong

4. **Each voter states their position and reasoning.** Reasoning is mandatory — a vote without reasoning gets zero weight. The reasoning must be auditable.

5. **Calculate the believability-weighted result.** Sum (voter's believability score × their vote) / Sum (all believability scores).

6. **Compare weighted and unweighted results.** If they differ, examine why. The difference often reveals that less-experienced people have a blind spot OR that more-experienced people have an outdated mental model.

7. **Decision-maker decides.** The weighted vote is a strong input but not binding. The decision-maker can override but must document their reasoning for doing so.

8. **Track outcomes.** Over time, compare decisions to outcomes to calibrate believability scores. This is how the system gets smarter.

## Application Guidelines

### For Board Advisors
- Advisory boards are natural environments for believability-weighted voting. Each advisor has different domains of expertise — weight their input accordingly.
- When advising a founder, be transparent about where your believability is high (your domain of expertise) and where it is low (areas outside your experience).
- Use believability weighting to resolve advisor disagreements productively rather than deferring to seniority or volume.

### For Leadership Teams
- Implement believability-weighted voting for major strategic decisions. It requires cultural investment upfront but produces dramatically better decisions over time.
- Make believability scores transparent. Secret scores breed resentment. Public scores create accountability and motivation to build expertise.
- Update believability scores based on outcomes. A track record of correct predictions increases believability. Repeated errors decrease it.

### For Hiring Committees
- Weight interview feedback by each interviewer's track record of predicting hire success. An interviewer who has accurately predicted 80% of outcomes should carry more weight than one with 50% accuracy.

## Common Mistakes

1. **Conflating seniority with believability.** Seniority and believability are correlated but not identical. A junior data scientist may have higher believability on an analytics question than the VP of Sales.

2. **Static believability scores.** Believability must be reassessed for each topic and updated based on outcomes. Frozen scores become a political tool.

3. **No reasoning requirement.** If votes don't require reasoning, the system degrades to popularity voting. Reasoning is what makes the weight justified.

4. **Using it for values decisions.** Believability-weighted voting works for factual and strategic questions. For values and culture decisions, equal voice matters more.

5. **Weaponizing believability.** Using low believability scores to silence dissent. Even low-believability voters should be heard — their reasoning might reveal something the experts missed.

6. **Ignoring the dissent.** When a low-believability voter disagrees with high-believability consensus, investigate why. Outsiders sometimes see what insiders cannot.

## Output Format

```markdown
# Believability-Weighted Decision: [Question]

**Date:** YYYY-MM-DD
**Decision-maker:** [Name]

## Question
[Specific decision to be made]

## Voter Assessments

| Voter | Track Record (1-5) | Reasoning Quality (1-5) | Openness (1-5) | Believability Score | Position | Key Reasoning |
|-------|-------------------|------------------------|-----------------|--------------------:|----------|---------------|
|       |                   |                        |                 |                     |          |               |

## Results
- **Unweighted result:** [Position A: X votes, Position B: Y votes]
- **Believability-weighted result:** [Position A: X.X, Position B: Y.Y]
- **Gap analysis:** [If results differ, why?]

## Decision
- **Chosen position:** [A or B]
- **Aligned with weighted vote?** [Yes/No]
- **If no, reasoning for override:** [Explanation]

## Outcome Tracking
- **Review date:** [Date]
- **Actual outcome:** [To be filled]
- **Believability calibration:** [Scores adjusted based on outcome]
```

## Related Frameworks

- **Dalio Idea Meritocracy** — Believability-weighted voting is the decision mechanism of an idea meritocracy
- **Dalio Radical Transparency Protocol** — Transparency enables honest believability assessment
- **Dalio Principles OS** — Believability-weighted voting is an operational principle
- **Decision Memo Framework** — Use the memo as the reasoning input for believability-weighted decisions
- **Operating System of Meetings** — Integrate believability-weighted voting into Decision Meetings
- **Principal-Agent Framework** — Believability weighting reduces information asymmetry in group decisions
