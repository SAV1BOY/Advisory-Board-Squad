# 00 — Board Setup Flow

## Overview

Establishes the Advisory Board from scratch: ratifies the charter, locks the operating cadence, defines document formats, and runs the inaugural meeting. This workflow executes once at formation and again whenever the board undergoes a material composition change (>30 % new members).

## Trigger

- Founding team decides to create an Advisory Board.
- Existing board undergoes a composition reset (mergers, pivots, governance overhaul).
- Annual effectiveness review recommends a structural reboot.

## Agents

| Agent | Role |
|---|---|
| board-chair (Board Chair) | Drives charter drafting, sets agenda for Meeting Zero |
| governance-clerk (Simon Sinek) | Prepares templates, logistics, access permissions |
| strategic-advisor (Peter Thiel) | Supplies market context and competitive landscape brief |
| culture-steward (Brene Brown) | Validates that charter aligns with stated values |

## Phases

### Phase 1 — Charter Drafting (Days 1-5)

1. board-chair pulls the charter template from `templates/board-charter-template.md`.
2. Fill in: purpose statement, scope of authority, composition requirements, term lengths, quorum rules, decision-rights matrix, confidentiality obligations.
3. strategic-advisor attaches a one-page market context brief so advisors understand the operating environment.
4. culture-steward reviews the charter for alignment with company values and flags any tension points.
5. Circulate the draft to all prospective advisors for async comment (48-hour window).
6. board-chair resolves comments and produces Charter v1.0.

### Phase 2 — Cadence Design (Days 3-7)

1. Define meeting rhythm: quarterly full-board sessions, monthly chair check-ins, ad-hoc crisis calls.
2. Set standing agenda blocks: strategy review (30 min), decision queue (20 min), risk register (15 min), open floor (15 min).
3. Assign recurring pre-read deadlines: materials due 5 business days before each session.
4. Lock the calendar for the next 12 months. Send calendar holds immediately.
5. Choose communication channels: primary (email + shared drive), secondary (encrypted messaging for urgent items).

### Phase 3 — Format Standards (Days 5-10)

1. governance-clerk finalizes document templates:
   - Pre-read memo (2-page max, structured: context → question → options → recommendation).
   - Meeting minutes (decisions, action items, dissenting views, next steps).
   - Decision log entry (date, question, options considered, decision, rationale, owner, review date).
   - Risk register row (risk, likelihood, impact, mitigation, owner, status).
2. Store all templates in `templates/` with version numbers.
3. Distribute a one-page "How We Work" guide covering naming conventions, file storage, and access rules.
4. Validate that every advisor can access the shared drive, templates, and calendar.

### Phase 4 — Inaugural Meeting (Day 12-14)

1. board-chair sends the agenda 5 days in advance along with the charter and market context brief.
2. Meeting Zero agenda:
   - Introductions and expectations alignment (15 min).
   - Charter walkthrough and ratification vote (20 min).
   - Cadence and format review (10 min).
   - First strategic topic: top three risks and opportunities (30 min).
   - Decision-rights exercise: walk through a hypothetical decision to test the process (15 min).
   - Wrap-up: confirm next meeting date, assign first pre-read owners (10 min).
3. governance-clerk records minutes using the standard template.
4. Within 24 hours, distribute minutes, ratified charter, and first action items.

### Phase 5 — Post-Setup Hardening (Days 15-21)

1. board-chair conducts a 15-minute 1:1 with each advisor to capture initial impressions and concerns.
2. governance-clerk archives Meeting Zero artifacts in `archive/`.
3. strategic-advisor updates the risk register with items surfaced during the meeting.
4. culture-steward logs any value-alignment observations for the first effectiveness review.
5. board-chair writes a brief retrospective memo: what worked, what to adjust for Meeting One.

## Quality Gates

| Gate | Criteria | Owner |
|---|---|---|
| G1 — Charter Complete | All required sections filled, no open comments, ratified by quorum | board-chair (Board Chair) |
| G2 — Calendar Locked | 12-month calendar holds sent, confirmed by >80 % of advisors | governance-clerk (Simon Sinek) |
| G3 — Templates Validated | All four core templates reviewed, version-numbered, accessible | governance-clerk (Simon Sinek) |
| G4 — Meeting Zero Done | Minutes distributed within 24 hours, action items assigned | board-chair (Board Chair) |
| G5 — Post-Setup Retro | Retrospective memo filed, 1:1 feedback collected | board-chair (Board Chair) |

## Outputs

- `docs/board-charter.md` — Ratified charter v1.0.
- `templates/` — Pre-read, minutes, decision log, risk register templates.
- `archive/meeting-zero/` — Agenda, minutes, attendance, first decision log entries.
- 12-month calendar with all sessions, pre-read deadlines, and chair check-ins.
- Retrospective memo stored in `archive/retros/`.

## Timeline

| Milestone | Target Day |
|---|---|
| Charter draft circulated | Day 3 |
| Charter comments resolved | Day 5 |
| Cadence and calendar locked | Day 7 |
| Templates finalized | Day 10 |
| Meeting Zero | Day 12-14 |
| Post-setup hardening complete | Day 21 |

Total elapsed time: **3 weeks** from kickoff to fully operational board.

## Metrics

| Metric | Target |
|---|---|
| Charter ratification vote | Unanimous or supermajority (≥75 %) |
| Calendar confirmation rate | ≥80 % of advisors confirm within 48 hours |
| Template usability score | No advisor requests clarification on format after Meeting Zero |
| Meeting Zero NPS (internal) | ≥8/10 average from post-meeting pulse |
| Time to first substantive decision | ≤60 days from Meeting Zero |

## Common Failures

| Failure Mode | Symptom | Mitigation |
|---|---|---|
| Charter bloat | Document exceeds 5 pages; advisors don't read it | Enforce 3-page max; move details to appendices |
| Calendar drift | Meetings slip within the first quarter | Lock dates 12 months out; treat moves as exceptions requiring Chair approval |
| Template ignorance | Advisors submit free-form memos | Reject non-compliant pre-reads; governance-clerk returns with template link |
| Passive inaugural meeting | No substantive debate in Meeting Zero | Seed the agenda with a genuine strategic tension, not a softball topic |
| Access gaps | Advisors can't find shared drive or templates | Test access for every advisor before Meeting Zero; keep a checklist |
| Skipping the retro | Post-setup retrospective never happens | board-chair blocks 30 minutes on Day 15; governance-clerk enforces |
