# Meeting Blocks

## Purpose

Reusable structural blocks for planning, running, and documenting board-level meetings. These blocks enforce discipline around preparation, time allocation, decision capture, and follow-through so meetings produce decisions rather than discussions.

## Structure

### Block 1 — Meeting Header

Establishes the meeting's identity and accountability.

**Fields:**
- **Meeting type:** Classify per `taxonomies/meeting-types.md` (decision session, review, working session, crisis, ceremony).
- **Date and time:** ISO 8601 format with timezone.
- **Duration:** Planned length in minutes.
- **Chair:** Person responsible for running the meeting and enforcing the agenda.
- **Scribe:** Person responsible for capturing minutes and action items.
- **Attendees:** Names and roles; mark required vs. optional.
- **Quorum requirement:** Minimum attendees needed for decisions to be binding.

### Block 2 — Pre-Read Package

Defines what participants must review before attending.

**Fields:**
- **Required reading:** List of documents with links, ordered by priority.
- **Estimated reading time:** Total minutes needed.
- **Distribution date:** When pre-reads were sent (minimum 48 hours before meeting).
- **Key questions to consider:** 3-5 framing questions that focus preparation.
- **Acknowledgment tracker:** Check-boxes for each attendee confirming they read the materials.

### Block 3 — Agenda Structure

Time-boxed agenda that distinguishes information, discussion, and decision items.

**Fields per agenda item:**
- **Item number and title:** Sequential identifier.
- **Type tag:** [INFO] / [DISCUSS] / [DECIDE] / [REVIEW].
- **Time allocation:** Minutes assigned.
- **Presenter/Owner:** Who leads this item.
- **Desired outcome:** One sentence describing the specific deliverable (e.g., "Vote on Option A vs. B").
- **Pre-read reference:** Link to relevant document.

### Block 4 — Decision Capture

Records decisions made during the meeting with full context.

**Fields per decision:**
- **Decision ID:** Links to `data/registries/decision-registry.yaml`.
- **Decision statement:** Clear, unambiguous statement of what was decided.
- **Vote or consensus method:** How the decision was reached (unanimous, majority, chair's call after dissent).
- **Dissenting views:** Names and substance of disagreement.
- **Confidence level:** Board's collective confidence (High / Medium / Low).
- **Conditions or constraints:** Any caveats attached to the decision.
- **Expiry or review date:** When the decision should be revisited.

### Block 5 — Action Item Register

Captures commitments with enough specificity to track.

**Fields per action:**
- **Action ID:** Format `AI-YYYYMMDD-NNN`.
- **Description:** Verb-noun task description.
- **Owner:** Single accountable person (never a group).
- **Due date:** Specific date, not "soon" or "next week."
- **Dependencies:** Other actions or external events this depends on.
- **Status:** Not Started / In Progress / Blocked / Complete.
- **Verification:** How completion will be confirmed.

### Block 6 — Meeting Health Check

Brief retrospective on meeting quality, completed in the last 5 minutes.

**Fields:**
- **Decisions made:** Count of [DECIDE] items resolved vs. deferred.
- **Time discipline:** Did we stay within time boxes? (Y/N with notes).
- **Preparation quality:** Were pre-reads consumed? (1-5 scale).
- **Engagement quality:** Did all voices contribute? (1-5 scale).
- **One improvement:** Single actionable improvement for the next meeting.
- **Overall effectiveness:** Score per `utilities/meeting-effectiveness-rubric.md`.

## Usage

1. **Every meeting** gets Block 1 + Block 3 + Block 5.
2. **Decision sessions** must include Block 2 (pre-reads) and Block 4 (decision capture).
3. **Block 6** is used for recurring meetings to track improvement over time. Data feeds `data/metrics/board-effectiveness-score.md`.
4. **Crisis meetings** may skip Block 2 but must still produce Block 4 and Block 5.
5. The Chair owns agenda design; the Scribe owns capture fidelity.

## Example

```markdown
# Board Decision Session — Q1 Strategic Review

## Header
- **Type:** Decision Session
- **Date:** 2026-03-15T14:00:00-05:00
- **Duration:** 90 minutes
- **Chair:** CEO
- **Scribe:** Chief of Staff
- **Attendees:** CEO (R), CFO (R), CTO (R), VP Product (R), Board Advisor (O)
- **Quorum:** 3 of 4 required members

## Agenda
| # | Title | Type | Time | Owner | Desired Outcome |
|---|-------|------|------|-------|-----------------|
| 1 | Q1 financial review | [INFO] | 15 min | CFO | Shared understanding of cash position |
| 2 | LATAM expansion decision | [DECIDE] | 30 min | CEO | Go / No-Go vote |
| 3 | CTO succession risk | [DISCUSS] | 20 min | VP Eng | Agreed mitigation approach |
| 4 | Fundraising timeline | [DECIDE] | 15 min | CFO | Commit to Q2 or defer to Q3 |
| 5 | Meeting health check | [REVIEW] | 10 min | Chair | One improvement identified |

## Decisions Captured
1. **DEC-2026-012:** Approved LATAM expansion — Mexico City office Q3.
   Vote: 3-1 (CTO dissented on timing). Confidence: Medium.
2. **DEC-2026-013:** Fundraising moves to Q2.
   Vote: Unanimous. Confidence: High.

## Action Items
| ID | Action | Owner | Due |
|----|--------|-------|-----|
| AI-20260315-001 | Draft LATAM hiring plan | VP People | 2026-03-29 |
| AI-20260315-002 | Update financial model for Q2 raise | CFO | 2026-03-22 |
| AI-20260315-003 | Document CTO succession options | VP Eng | 2026-04-01 |
```
