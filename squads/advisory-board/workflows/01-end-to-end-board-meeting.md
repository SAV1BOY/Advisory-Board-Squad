# 01 — End-to-End Board Meeting

## Overview

The complete lifecycle of a single Advisory Board meeting — from agenda setting through follow-up closure. This workflow repeats every quarterly session and adapts for monthly chair check-ins and ad-hoc crisis calls.

## Trigger

- Scheduled quarterly board session (calendar hold fires 30 days out).
- Chair calls an ad-hoc session (crisis, time-sensitive opportunity).
- Monthly chair check-in reaches its calendar date.

## Agents

| Agent | Role |
|---|---|
| Board-Chair | Sets agenda, facilitates meeting, owns follow-through |
| Governance-Ops | Logistics, pre-read distribution, minutes, action tracking |
| Strategy-Analyst | Prepares data packs and pre-read materials |
| Devil's-Advocate | Stress-tests proposals during discussion |
| Decision-Tracker | Logs decisions, dissent, rationale in real time |

## Phases

### Phase 1 — Agenda & Pre-Read Preparation (T-30 to T-5 days)

1. Board-Chair drafts the agenda using the standing structure: strategy review, decision queue, risk register, open floor.
2. Identify decision items. Each decision item requires a pre-read memo (context → question → options → recommendation).
3. Strategy-Analyst builds data packs: financial dashboard, market update, competitive moves, customer signals.
4. Pre-read owners submit drafts to Governance-Ops by T-10.
5. Governance-Ops reviews for format compliance. Non-compliant materials are returned with specific feedback.
6. Final pre-read package distributed to all advisors at T-5.
7. Board-Chair sends a "what to focus on" email highlighting the two or three items that need the deepest preparation.

### Phase 2 — Pre-Meeting Alignment (T-5 to T-1 days)

1. Advisors review pre-reads and submit written questions or comments by T-2.
2. Board-Chair reviews incoming questions and adjusts the agenda if a topic is generating unexpected heat.
3. Devil's-Advocate prepares counter-arguments for each recommendation in the decision queue.
4. Governance-Ops confirms logistics: video link, room booking, recording consent, quorum check.
5. Board-Chair conducts a 10-minute pre-call with any first-time presenters to set expectations.

### Phase 3 — Meeting Execution (Meeting Day)

1. Board-Chair opens: state the purpose, confirm quorum, note any conflicts of interest.
2. Run each agenda block within its time box. Chair enforces timing.
3. For each decision item:
   a. Presenter summarizes the recommendation (5 min max — pre-read was the deep dive).
   b. Devil's-Advocate presents the strongest counter-argument.
   c. Open discussion. Chair ensures every advisor speaks at least once.
   d. Chair calls for a decision: approve, reject, defer, or request more information.
   e. Decision-Tracker records: decision, rationale, dissenting views, owner, review date.
4. Risk register review: any new risks? Any status changes on existing risks?
5. Open floor: emerging issues, cross-squad signals, advisor observations.
6. Board-Chair closes: summarize decisions, confirm action items and owners, announce next meeting date.

### Phase 4 — Minutes & Distribution (T+0 to T+1 day)

1. Decision-Tracker drafts minutes using the standard template within 4 hours of meeting end.
2. Minutes include: attendance, each decision with rationale and dissent, action items with owners and deadlines, risk register updates.
3. Board-Chair reviews and approves minutes.
4. Governance-Ops distributes approved minutes to all advisors within 24 hours.
5. Action items are entered into the action tracker with owners and deadlines.

### Phase 5 — Follow-Through (T+1 to next meeting)

1. Governance-Ops sends a weekly action-item status email to all owners.
2. Board-Chair conducts a mid-cycle check-in (phone or async) with each action-item owner.
3. Any blocked items are escalated to the Chair immediately, not held for the next meeting.
4. Strategy-Analyst updates dashboards with any data that informed meeting decisions.
5. At T+21, Governance-Ops publishes a follow-through scorecard: percentage of actions on track, completed, blocked, or overdue.
6. Board-Chair reviews the scorecard and sends a brief note to the full board: progress, blockers, and any agenda implications for the next session.

## Quality Gates

| Gate | Criteria | Owner |
|---|---|---|
| G1 — Pre-reads shipped | All materials distributed at T-5; zero format violations | Governance-Ops |
| G2 — Quorum confirmed | Quorum verified before meeting opens | Governance-Ops |
| G3 — Decisions logged | Every decision recorded with rationale, dissent, owner, review date | Decision-Tracker |
| G4 — Minutes distributed | Approved minutes sent within 24 hours | Governance-Ops |
| G5 — Follow-through scorecard | Published at T+21 with ≥80 % actions on track | Governance-Ops |

## Outputs

- Agenda document (stored in `archive/meetings/YYYY-MM-DD/`).
- Pre-read package (same archive path).
- Meeting minutes with decision log entries.
- Updated action tracker.
- Updated risk register.
- Follow-through scorecard.

## Timeline

| Milestone | Timing |
|---|---|
| Agenda draft | T-30 |
| Pre-read drafts due | T-10 |
| Pre-reads distributed | T-5 |
| Advisor questions due | T-2 |
| Meeting | T |
| Minutes distributed | T+1 |
| Follow-through scorecard | T+21 |

## Metrics

| Metric | Target |
|---|---|
| Pre-read on-time rate | 100 % distributed by T-5 |
| Advisor preparation score | ≥90 % of advisors submit questions or comments by T-2 |
| Decision throughput | ≥2 substantive decisions per quarterly session |
| Minutes turnaround | ≤24 hours |
| Action completion rate | ≥80 % of actions completed by their deadline |
| Meeting duration accuracy | Actual duration within ±10 % of planned |

## Common Failures

| Failure Mode | Symptom | Mitigation |
|---|---|---|
| Pre-read avalanche | Too many pages; advisors skim or skip | Enforce 2-page max per memo; Chair curates the "focus" email |
| Discussion drift | One topic consumes the entire meeting | Chair uses a visible timer; Devil's Advocate has permission to call "time" |
| Silent advisors | One or two voices dominate | Chair explicitly invites each advisor to speak; use round-robin for key decisions |
| Phantom decisions | Group thinks it decided but no one recorded it | Decision-Tracker confirms each decision aloud before moving on |
| Action item rot | Items roll over meeting after meeting | Follow-through scorecard makes overdue items visible; Chair escalates at T+21 |
| Minutes as fiction | Minutes don't reflect actual discussion or dissent | Decision-Tracker reads back decisions in real time; advisors correct on the spot |
