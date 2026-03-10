# Meeting Types Taxonomy

## Types

1. **Decision Session** — The primary purpose is to make one or more specific decisions.
2. **Strategic Review** — The primary purpose is to evaluate strategic progress and adjust course.
3. **Operational Review** — The primary purpose is to review execution metrics and resolve blockers.
4. **Working Session** — The primary purpose is collaborative problem-solving or document creation.
5. **Crisis Meeting** — An unscheduled meeting to respond to an urgent threat or incident.
6. **Information Briefing** — The primary purpose is one-way information transfer with Q&A.
7. **Ceremony** — A ritualized meeting that reinforces culture (all-hands, retrospective, celebration).
8. **One-on-One** — A private meeting between two people for coaching, feedback, or relationship building.
9. **Board Meeting** — A formal governance meeting with the board of directors or advisors.
10. **Pre-Mortem / Postmortem** — A structured analytical meeting examining a future or past decision/event.

## Definitions

| Type | Purpose | Ideal Duration | Ideal Cadence | Key Output |
|------|---------|---------------|---------------|------------|
| Decision Session | Make specific, named decisions | 60-90 min | As needed | Recorded decisions with rationale and dissent |
| Strategic Review | Evaluate strategy execution and adjust | 90-120 min | Quarterly | Updated strategic priorities, pivots or kill decisions |
| Operational Review | Track execution metrics, resolve blockers | 30-60 min | Weekly or biweekly | Updated scorecard, blocker resolutions, escalations |
| Working Session | Collaborative creation or problem-solving | 60-120 min | As needed | Draft document, solution design, or analysis |
| Crisis Meeting | Respond to urgent threat | 30-60 min | Unscheduled | Containment plan, communication plan, action items |
| Information Briefing | Transfer important information efficiently | 30-45 min | As needed | Shared understanding, Q&A resolution |
| Ceremony | Reinforce culture and build connection | 30-60 min | Weekly to monthly | Engagement, recognition, alignment |
| One-on-One | Coaching, feedback, relationship building | 30-45 min | Weekly | Development actions, relationship health |
| Board Meeting | Governance, strategic oversight, accountability | 2-4 hours | Monthly or quarterly | Board decisions, strategic guidance, accountability |
| Pre-Mortem / Postmortem | Structured prospective or retrospective analysis | 60-90 min | Event-driven | Lessons learned, mitigations, or action items |

## Examples

| Meeting Name | Type | Attendees | Cadence | Duration |
|-------------|------|-----------|---------|----------|
| Q1 Strategy Review | Strategic Review | Leadership team + board advisors | Quarterly | 2 hours |
| Weekly Leadership Standup | Operational Review | CEO, VPs | Weekly | 30 min |
| M&A Go/No-Go | Decision Session | CEO, CFO, Legal, Board | As needed | 90 min |
| Pricing Model Workshop | Working Session | Product, Finance, Sales | As needed | 90 min |
| Data Breach Response | Crisis Meeting | CEO, CTO, Legal, Comms | Unscheduled | 45 min |
| Investor Update Briefing | Information Briefing | CEO, CFO, Investors | Quarterly | 45 min |
| All-Hands Town Hall | Ceremony | Entire company | Monthly | 45 min |
| CEO / VP Eng 1:1 | One-on-One | CEO, VP Eng | Weekly | 30 min |
| Board of Directors Meeting | Board Meeting | Board members, CEO, CFO | Quarterly | 3 hours |
| Product Launch Pre-Mortem | Pre-Mortem / Postmortem | Product, Eng, Design, QA | Pre-launch | 60 min |

## When to Use Each

**Decision Session** — When you have a specific decision that requires input from multiple stakeholders and cannot be made asynchronously. If the decision can be made by one person with advisory input, use the `delegation-pattern.md` or `consensus-vs-conviction-pattern.md` instead of scheduling a meeting.

**Strategic Review** — At the end of each quarter and when significant external events (market shift, competitor move, regulatory change) invalidate current assumptions. Do not use for operational topics.

**Operational Review** — Weekly for teams in execution mode. Biweekly for stable operations. Should be the shortest recurring meeting. If it consistently runs long, the underlying execution system needs improvement, not the meeting.

**Working Session** — When collaborative creation is genuinely more efficient than async work (complex analysis, multi-stakeholder document, design review). Do not use for work that one person could do alone.

**Crisis Meeting** — Only for genuine crises (see `lib/components/crisis-blocks.md` for classification). Overuse devalues the urgency signal.

**Information Briefing** — When information is complex, sensitive, or benefits from live Q&A. If the information can be consumed asynchronously, send a document instead.

**Ceremony** — When cultural reinforcement, celebration, or community building is the goal. Should not include decision-making or operational review.

**One-on-One** — Weekly for direct reports. This is the most important meeting a manager has. Never cancel.

**Board Meeting** — Monthly for early-stage companies, quarterly for later stages. Formal governance should not be skipped even during calm periods.

**Pre-Mortem / Postmortem** — Before every major irreversible decision (pre-mortem) and after every significant outcome, positive or negative (postmortem).

**Meeting hygiene rule:** Before scheduling any meeting, ask: "What type of meeting is this, and is a meeting the best format for this purpose?" If the answer is information sharing, write a document. If the answer is a reversible decision, use the `reversible-decision-pattern.md` asynchronously.
