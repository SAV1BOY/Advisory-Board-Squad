# Cross-Squad Integration Guide

## Purpose

The Advisory Board does not operate in isolation. Its decisions affect other squads, and other squads generate information the board needs. This guide defines the integration points, communication channels, and handoff protocols between the Advisory Board and other squads.

## Integration Model

The Advisory Board integrates with other squads through three mechanisms:

1. **Strategic Handoffs** (board → squads): Board decisions that require squad execution.
2. **Intelligence Feeds** (squads → board): Information from squads that informs board decisions.
3. **Escalations** (squads → board): Issues that require board attention per the escalation policy.

## Strategic Handoffs

When the board makes a decision that affects a squad's work, the cross-squad strategic handoff workflow (15) is triggered.

### Handoff Package
Every handoff includes:
- **Decision:** What was decided (one paragraph).
- **Intent:** Why it was decided (strategic reasoning).
- **Scope:** What is in scope and out of scope.
- **Constraints:** Budget, timeline, resources.
- **Success criteria:** Measurable outcomes.
- **Authority:** What the squad can decide vs. what requires escalation.

### Handoff Process
1. Strategy-Analyst drafts the handoff brief.
2. Board-Chair reviews for accuracy and clarity.
3. 30-minute handoff meeting with the receiving squad.
4. Squad-Lead signs off on understanding.
5. Bi-weekly status updates flow back to the board.

### Common Handoff Failures
- Brief is vague: squad interprets differently than intended.
- Brief micro-manages: removes squad autonomy on implementation.
- No feedback loop: squad sends updates but hears nothing back.
- No resources: strategic direction without the capacity to execute.

## Intelligence Feeds

The board needs current information to make good decisions. Other squads provide this through structured feeds.

### Standard Feeds

| Feed | Source Squad | Frequency | Recipient |
|---|---|---|---|
| Customer health metrics | Customer Success | Monthly | Strategy-Analyst |
| Product roadmap status | Product | Monthly | Strategy-Analyst |
| Engineering velocity | Engineering | Monthly | Execution-Tracker |
| Market intelligence | Marketing / BD | Quarterly | Strategy-Analyst |
| Financial dashboard | Finance | Monthly | Strategy-Analyst |
| Talent pipeline | People / HR | Quarterly | Culture-Guardian |
| Competitive intelligence | Product / Strategy | Quarterly | Strategy-Analyst |

### Feed Standards
- Each feed has a defined format and delivery date.
- Feeds are delivered to the designated board agent, not the full board.
- The receiving agent synthesizes and surfaces relevant information to the board.
- If a feed reveals something material, escalate per the escalation policy.

## Escalations from Squads

Any squad can escalate an issue to the board per `docs/escalation-policy.md`. The most common cross-squad escalation scenarios:

| Scenario | Escalation Path |
|---|---|
| Strategic conflict between two squads | Squad leads → Board-Chair for resolution |
| Resource contention across squads | Squad leads → Board-Chair for prioritization |
| Execution blockers from board decisions | Squad lead → Strategy-Analyst → Board-Chair |
| Customer or market signal requiring strategic response | Squad lead → Strategy-Analyst (L1 or L2) |
| Risk identified by a squad that affects company-wide strategy | Squad lead → Risk-Analyst (L1 or L2) |

## Squad-Board Communication Norms

### Squads communicating to the board
- Use the structured feed formats. Do not send raw data without interpretation.
- Include a "so what" for every data point: what does this mean for the board's priorities?
- Flag items that require board action separately from routine updates.
- Respect the board's time: compress information. One page is ideal.

### Board communicating to squads
- Every board decision that affects a squad gets a formal handoff (workflow 15).
- The board does not issue ad-hoc directives outside the handoff process.
- Board-Chair and Strategy-Analyst are the primary communication channels.
- Feedback on squad performance goes through the CEO, not directly to squad leads (unless Board-Chair and CEO agree on direct communication).

## Integration Calendar

| Activity | Frequency | Responsible |
|---|---|---|
| Intelligence feed delivery | Monthly | Source squads |
| Cross-squad dashboard update | Monthly | Strategy-Analyst |
| Strategic handoff execution | As needed (post-decision) | Strategy-Analyst |
| Cross-squad coordination review | Quarterly (board meeting) | Board-Chair |
| Integration process review | Annually | Governance-Ops |

## Measuring Integration Quality

| Metric | Target |
|---|---|
| Feed delivery on-time rate | ≥90 % |
| Handoff sign-off time | ≤5 days from board decision |
| Squad feedback reaching the board | Monthly during active handoffs |
| Escalation response time | Per escalation policy levels |
| Cross-squad conflict resolution | ≤2 weeks from escalation |
