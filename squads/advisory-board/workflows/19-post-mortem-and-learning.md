# 19 — Post-Mortem & Learning

## Overview

A structured retrospective process for significant events — both failures and successes. The goal is to extract actionable learnings, update mental models and frameworks, and share insights across the organization. This workflow prioritizes learning over blame.

## Trigger

- Material failure: project failure, missed target by >30 %, customer loss, system outage, process breakdown.
- Material success: outcome significantly exceeded expectations — learn what worked and why.
- Crisis aftermath (complements the crisis retro in workflow 07).
- Decision quality review (workflow 12) identifies a decision worth deep analysis.
- Any team or board member requests a post-mortem for an event they believe has learning value.

## Agents

| Agent | Role |
|---|---|
| board-chair (Board Chair) | Sponsors the post-mortem, ensures it happens |
| strategic-advisor (Peter Thiel) | Facilitates the investigation, produces the report |
| capital-allocator (Charlie Munger) | Challenges superficial explanations, pushes for root causes |
| governance-clerk (Simon Sinek) | Archives findings, updates relevant frameworks and policies |
| culture-steward (Brene Brown) | Ensures blameless culture is maintained throughout |

## Phases

### Phase 1 — Event Documentation (Days 1-3)

1. strategic-advisor initiates the post-mortem process:
   - Define the event: what happened? When? Who was involved?
   - Collect factual data: timelines, metrics, communications, decisions made.
   - Identify the affected parties: customers, employees, partners, investors.
   - Establish the scope: what is this post-mortem trying to learn?
2. culture-steward sets the tone: this is a blameless investigation. The goal is to understand what happened and why, not to assign fault.
3. Participants are notified and asked to prepare their perspective in writing before the investigation session.

### Phase 2 — Investigation (Days 3-10)

1. strategic-advisor conducts the investigation:
   - Timeline reconstruction: map every significant event, decision, and communication in chronological order.
   - Structured interviews (30-45 min each) with key participants:
     - "Walk me through what happened from your perspective."
     - "At each decision point, what information did you have?"
     - "What would you do differently with the same information?"
     - "What would you do differently with the information you have now?"
   - Data analysis: what do the metrics show? Where did reality diverge from expectations?
2. capital-allocator pushes beyond the first explanation:
   - Apply "5 whys" to every causal chain.
   - Distinguish between proximate causes (what directly happened) and root causes (what systemic conditions allowed it to happen).
   - Ask: "Was this a people problem, a process problem, or a system problem?"
3. Identify contributing factors:
   - Information: did the right people have the right information at the right time?
   - Decision-making: were decisions made with appropriate rigor?
   - Communication: did communication happen effectively across teams and levels?
   - Process: did existing processes help or hinder?
   - Resources: were there adequate resources (time, money, people)?
   - Culture: did cultural factors (fear, groupthink, over-confidence) play a role?

### Phase 3 — Document Learnings (Days 10-15)

1. strategic-advisor produces the Post-Mortem Report:
   - Executive summary (1 page): what happened, why it matters, key learnings.
   - Timeline of events.
   - Root cause analysis: the chain of causation from root to outcome.
   - Contributing factors analysis.
   - What went well (even in failures, some things worked).
   - What went wrong (specific, evidence-based).
   - Lessons learned: specific, actionable insights.
   - Recommendations: changes to prevent recurrence or replicate success.
2. Each recommendation specifies:
   - What changes: framework, process, policy, behavior, system.
   - Who is responsible for implementing it.
   - Timeline for implementation.
   - How we will know it worked.
3. capital-allocator reviews: "Are the learnings specific enough to be actionable? Or are they generic platitudes?"

### Phase 4 — Update Principles & Frameworks (Days 15-20)

1. For each recommendation, identify which existing document or framework should be updated:
   - Decision policy (`docs/decision-policy.md`).
   - Risk register (workflow 16).
   - Escalation policy (`docs/escalation-policy.md`).
   - Workflow playbooks (relevant workflow files).
   - Pre-read standards (`docs/pre-read-standards.md`).
   - Any other relevant framework or template.
2. governance-clerk makes the updates. Each update is tracked and linked to the post-mortem.
3. board-chair reviews the updates to ensure they are proportionate (not over-correcting for a single event).
4. culture-steward checks: do the updates reinforce the right cultural values?

### Phase 5 — Share & Embed (Days 20-30)

1. strategic-advisor presents the post-mortem findings to the appropriate audience:
   - Board: summary of learnings and framework updates (15 min at next meeting).
   - Executive team: full report and recommended changes.
   - Affected teams: relevant findings and what changes for them.
   - Cross-squad: if the learnings have organization-wide relevance (workflow 15 handoff).
2. Add the post-mortem to the organizational learning library (searchable archive).
3. Create a "one-page learning" card: the single most important insight from this event, written for someone with no context.
4. Schedule a 6-month follow-up: did the recommended changes actually get implemented? Are they working?
5. Archive the full post-mortem package in `archive/post-mortems/`.

## Quality Gates

| Gate | Criteria | Owner |
|---|---|---|
| G1 — Event documented | Factual data collected, scope defined, participants notified | strategic-advisor (Peter Thiel) |
| G2 — Investigation complete | Timeline reconstructed, interviews done, root causes identified | strategic-advisor (Peter Thiel) |
| G3 — Report produced | Post-mortem report with root causes, learnings, recommendations | strategic-advisor (Peter Thiel) |
| G4 — Frameworks updated | Relevant documents and policies updated based on recommendations | governance-clerk (Simon Sinek) |
| G5 — Shared and embedded | Findings presented to appropriate audiences, learning card created | strategic-advisor (Peter Thiel) |

## Outputs

- Post-mortem report (executive summary, timeline, root cause analysis, contributing factors, learnings, recommendations).
- Framework and policy updates (linked to the post-mortem).
- One-page learning card.
- Presentation to board and relevant teams.
- 6-month follow-up review.

## Timeline

| Milestone | Day |
|---|---|
| Event documentation complete | Day 3 |
| Investigation complete | Day 10 |
| Report produced | Day 15 |
| Frameworks updated | Day 20 |
| Findings shared | Day 25 |
| 6-month follow-up | Day 180 |

## Metrics

| Metric | Target |
|---|---|
| Post-mortem initiation time | ≤3 days from event |
| Investigation thoroughness | ≥5 interviews, root cause chain documented |
| Report turnaround | ≤15 days from event to published report |
| Framework updates | Every recommendation produces a specific document update |
| Recurrence rate | ≤10 % of post-mortem-ed failures recur within 12 months |
| Follow-up completion | 100 % of post-mortems get a 6-month follow-up |

## Common Failures

| Failure Mode | Symptom | Mitigation |
|---|---|---|
| Blame culture | People withhold information to avoid consequences | culture-steward enforces blameless norms; focus on systems, not individuals |
| Superficial analysis | "We need to communicate better" — no specific changes | capital-allocator rejects recommendations that are not specific and actionable |
| Post-mortem avoidance | Nobody wants to revisit painful events | board-chair makes it a requirement, not a suggestion |
| Over-correction | Single event causes sweeping changes that create new problems | board-chair reviews updates for proportionality |
| Learning library graveyard | Reports filed but never read | One-page learning cards are designed for discoverability; reference in relevant workflows |
| Missing the success post-mortem | Only failures get analyzed | Actively schedule post-mortems for unexpected successes |
