# Postmortem and Learning Loop Framework

## Purpose

This framework establishes a systematic process for extracting institutional learning from both failures and successes. A postmortem is not a blame session — it is a structured investigation into what happened, why it happened, and what the organization will change as a result. The learning loop ensures that insights are captured, disseminated, and embedded into future processes. Organizations that learn systematically outperform those that repeat mistakes.

## When to Use

- After any significant failure, miss, or unexpected outcome
- After major successes (to understand what actually drove the result)
- After completing major projects, launches, or milestones
- When the same type of problem recurs more than twice
- After crises, incidents, or near-misses
- At regular intervals (quarterly) even without specific triggers

## Core Model

### The Learning Loop (Four Phases)

#### Phase 1: Capture — What Happened?
Build a factual, chronological timeline of events. No interpretation yet — just facts.
- What was the expected outcome?
- What was the actual outcome?
- What is the gap between expected and actual?
- What was the sequence of events (timeline)?

#### Phase 2: Analyze — Why Did It Happen?
Use the "5 Whys" technique to move from symptoms to root causes.
- What were the proximate causes (immediate triggers)?
- What were the contributing causes (enabling conditions)?
- What were the root causes (systemic factors)?
- Were there early warning signals that were missed or ignored?

#### Phase 3: Learn — What Do We Now Know?
Distill the analysis into actionable insights.
- What assumptions were wrong?
- What did we learn about our processes, people, or market?
- Was this a one-time event or a systemic pattern?
- What would we do differently if we could rewind?

#### Phase 4: Change — What Will We Do Differently?
Convert learning into specific, measurable changes.
- What process changes will we make?
- What new checks, reviews, or safeguards will we implement?
- Who owns each change?
- How will we verify the change is working?

### The Blameless Postmortem Principle
The goal is to fix systems, not punish people. Key rules:
- Focus on processes and systems, not individuals
- Assume everyone was acting with the best information they had at the time
- Ask "what" and "how" questions, not "who" questions
- Make the postmortem psychologically safe — learning requires honesty, and honesty requires safety
- Separate the postmortem from performance evaluation

## Steps

1. **Schedule the postmortem within 72 hours.** Memory fades fast. Conduct the postmortem while events are fresh. Never skip it because people are "too busy."

2. **Assign a facilitator.** Someone not directly involved in the event. Their job is to keep the conversation fact-based and forward-looking.

3. **Build the timeline collaboratively.** Each participant adds their perspective to the timeline. Discrepancies are noted — they often reveal the most important insights.

4. **Run the 5 Whys for each contributing factor.** For each significant gap between expected and actual, ask "Why?" five times to reach the root cause.

5. **Identify patterns.** Is this the first time this type of failure occurred? If not, what previous postmortems said and why the fixes didn't work.

6. **Generate action items.** Each action item must have: a specific change, an owner, a deadline, and a verification method.

7. **Distribute the postmortem document.** Share it broadly. Learning that stays in one team's head is not institutional learning.

8. **Follow up on action items.** 30 days later, review whether the changes were implemented and whether they are working.

9. **Build a postmortem library.** Maintain a searchable archive of all postmortems. New employees should read relevant postmortems as part of onboarding.

## Application Guidelines

### For Board Advisors
- Insist that every major miss or failure triggers a postmortem. If the organization does not do postmortems, it is not learning.
- Review postmortem action items at the next board meeting. Ask: "What did we change as a result?"
- Model the behavior: when advisory recommendations go wrong, do a postmortem on the advice itself.

### For Founders
- Make postmortems a cultural norm, not a punishment. Celebrate teams that run thorough postmortems. The goal is to make it safe to fail and learn.
- Personally attend postmortems for major events. Your presence signals that learning matters.
- Run success postmortems too. "Why did this work?" is as important as "Why did this fail?" — success often masks lucky breaks that won't repeat.

### For Engineering and Product
- Adopt SRE-style incident postmortems for production issues. The blameless postmortem culture pioneered by Google SRE is the gold standard.
- Track Mean Time to Detect (MTTD), Mean Time to Resolve (MTTR), and Mean Time Between Failures (MTBF) as learning metrics.

## Common Mistakes

1. **Blame culture.** If people fear punishment, they will hide failures, and the organization will not learn. Blamelessness is non-negotiable.

2. **Postmortem without action items.** Understanding what went wrong without changing anything is intellectual entertainment, not learning.

3. **Action items without follow-up.** The most common failure: action items are generated, documented, and then forgotten. Build a follow-up review into the process.

4. **Proximate cause only.** Stopping at "the server crashed" instead of asking "why did we have a single point of failure?" The root cause is always systemic.

5. **Skipping success postmortems.** Organizations only examine failures. But attributing success to skill when it was luck is equally dangerous.

6. **Postmortem fatigue.** If you do postmortems for everything, people stop taking them seriously. Reserve formal postmortems for significant events. Use lightweight "retros" for routine matters.

7. **Waiting too long.** A postmortem conducted weeks after the event is a memory reconstruction exercise, not a factual analysis.

## Output Format

```markdown
# Postmortem: [Event Name]

**Date of Event:** YYYY-MM-DD
**Date of Postmortem:** YYYY-MM-DD
**Facilitator:** [Name]
**Participants:** [Names]
**Severity:** Critical / Major / Minor

## Summary
[2-3 sentences: What happened and what was the impact]

## Timeline
| Time | Event | Source |
|------|-------|--------|
|      |       |        |

## Expected vs. Actual Outcome
- **Expected:** [What should have happened]
- **Actual:** [What did happen]
- **Gap:** [The difference and its impact]

## Root Cause Analysis (5 Whys)
1. Why? [Proximate cause]
2. Why? [Contributing cause]
3. Why? [Deeper cause]
4. Why? [Systemic cause]
5. Why? [Root cause]

## What Went Well
- [Things that worked, even in failure]

## What Went Wrong
- [Things that failed or contributed to the negative outcome]

## Lessons Learned
1. [Lesson]
2. [Lesson]

## Action Items
| # | Action | Owner | Deadline | Verification Method | Status |
|---|--------|-------|----------|--------------------|---------|
|   |        |       |          |                    | Open    |

## Pattern Check
- Has this type of failure occurred before? [Yes/No]
- If yes, link to previous postmortem: [Link]
- Why didn't the previous fix work? [Explanation]

## Follow-up Review Date: [30 days from postmortem]
```

## Related Frameworks

- **Pre-Mortem Framework** — Pre-mortem prevents; postmortem learns. Use both.
- **Inversion Framework** — Inversion identifies failure modes before they happen; postmortem analyzes them after
- **Second-Order Thinking** — Root cause analysis is a form of second-order thinking applied retrospectively
- **Dalio Pain Plus Reflection Equals Progress** — Dalio's principle that growth comes from reflecting on failures
- **Culture as Operating System** — A learning culture requires a postmortem practice
- **Decision Log Framework** — Postmortem insights should flow back into the decision log
