# Pre-Read Pack Builder

## Purpose

Assembles and distributes pre-read materials for upcoming board and leadership meetings. Ensures every meeting participant receives the right materials in the right format with enough lead time to prepare, so meetings start at the analysis level rather than the information level.

## Input

- **Meeting agenda:** The planned agenda with item types and owners.
- **Supporting documents:** Decision memos, financial reports, dashboards, strategic updates.
- **Registry updates:** Latest entries from decision, risk, experiment, and forecast registries.
- **Meeting type:** Classification per `lib/taxonomies/meeting-types.md` which determines pack composition.
- **Distribution list:** Meeting attendees with roles and email/channel.
- **Meeting date:** To calculate distribution deadline (48+ hours before meeting).

## Process Steps

1. **Determine pack composition based on meeting type:**
   - Decision Session: decision memos, relevant registry extracts, scenario analyses
   - Strategic Review: strategy document, metrics dashboard, competitive landscape, risk registry
   - Board Meeting: CEO update, financial review, key decisions pending, risk register, strategic update
   - Operational Review: scorecard, action item status, blocker list
   - Crisis Meeting: situation report, containment plan draft (expedited — may be distributed 1-2 hours before)

2. **Assemble materials per agenda item:** For each agenda item, gather:
   - Primary document (memo, report, or analysis)
   - Supporting data (charts, models, research)
   - Related registry entries (decisions, risks, experiments referenced)
   - Framing questions (3-5 questions to guide the reader's preparation)

3. **Structure the pack:** Organize materials in agenda order with:
   - Cover page: meeting date, type, duration, attendees, quorum requirement
   - Table of contents with page/section references
   - Executive summary: 1-page overview of the meeting's key questions and decisions
   - Materials organized by agenda item with clear section breaks
   - Appendix for detailed supporting data

4. **Calculate reading time:** Estimate total reading time based on document length and complexity. Target: under 60 minutes total. If over 60 minutes, trim or move items to appendix.

5. **Add preparation prompts:** For each section, include:
   - "Key question to consider:" — focuses the reader on what matters
   - "Decision needed:" — for [DECIDE] items, states what the reader should come prepared to decide
   - "Your input requested on:" — for [DISCUSS] items, states what specific input is sought

6. **Distribute:** Send the pack to all attendees with:
   - Distribution timestamp
   - Estimated reading time
   - Explicit request to confirm receipt and review
   - Deadline for submitting pre-meeting questions or concerns

7. **Track acknowledgment:** Monitor which attendees have confirmed they reviewed the materials. Follow up with non-responders 24 hours before the meeting.

## Output

- Assembled pre-read pack in a single document or organized folder.
- Distribution confirmation log.
- Reading time estimate.
- Acknowledgment tracker.
- List of pre-meeting questions received from attendees.

## Automation Notes

- Distribution should occur automatically 48-72 hours before the meeting.
- Acknowledgment tracking can use a simple form or message reaction system.
- For recurring meetings, maintain a template pack that auto-populates with latest data.
- Integrates with memo-generator.md (decision memos), scorecard-updater.md (metrics), and risk-register-updater.md (risk data).
- Pack should be version-controlled — if materials are updated after distribution, resend with change log.
