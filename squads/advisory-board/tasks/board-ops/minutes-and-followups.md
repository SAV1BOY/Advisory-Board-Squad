# Task: Minutes and Follow-Ups

## Objective
Produce accurate board meeting minutes, update all tracking systems, and ensure every decision and action item from the meeting is properly recorded and assigned for follow-up.

## Trigger
- Immediately after every board meeting concludes

## Agents Involved
- **Lead:** Board Ops / Secretary
- **Reviewer:** Board Chair (approves draft minutes)
- **Contributors:** CEO (validates management commitments), Action item owners (confirm assignments)


## Agent Assignment
> Routing: see `config.yaml → routing → board-meeting-run`

- **Lead:** governance-clerk (Simon Sinek)
- **Support:** board-chair (Board Chair), simplicity-czar (Derek Sivers)

## Pre-Requisites
- [ ] Meeting has concluded
- [ ] Real-time notes captured during the meeting
- [ ] Decision record confirmed during the meeting
- [ ] Action items confirmed during the meeting

## Steps

1. **Draft Minutes (Within 24 hours of meeting)**
   - Using minutes-template.md, draft the full meeting minutes
   - Focus on decisions, rationale, and actions — not verbatim transcription
   - For each decision: record the resolution text, mover, seconder, vote count, and any conditions
   - For discussions: capture the range of views expressed and the conclusion, not who said what (unless attribution is requested)
   - Mark any confidential sections appropriately

2. **Update Decision Log (Within 24 hours)**
   - Add every decision to the decision-log.md with full detail
   - Assign decision IDs following the naming convention
   - Include: decision statement, options considered, rationale, conditions, execution owner, review date
   - Cross-reference the decision ID in the minutes

3. **Update Action Item Tracker (Within 24 hours)**
   - Add all new action items to action-items-tracker.md
   - Assign action item IDs
   - Update status of prior action items based on meeting discussion
   - Close completed items with outcome notes
   - Send action item assignments to owners with due dates

4. **Chair Review (Within 48 hours)**
   - Send draft minutes to Chair for review
   - Chair reviews for accuracy, tone, and completeness
   - Chair may request additions or modifications
   - Incorporate Chair feedback and finalize draft

5. **Distribution (Within 5 business days)**
   - Send Chair-approved draft minutes to all board members
   - Include: action item summary, next meeting date, any immediate follow-up items
   - Note that minutes are "draft" pending approval at the next meeting
   - Upload to board portal

6. **Follow-Up Execution (Ongoing)**
   - Send weekly reminders to action item owners with approaching deadlines
   - Escalate overdue items per the escalation protocol
   - Collect status updates from owners for the next meeting's action item review
   - Prepare the action item status report for the next meeting prep cycle

7. **Board Scorecard Update (Within 5 business days)**
   - Update the board scorecard with any new data shared at the meeting
   - Incorporate any changes to strategic priorities or targets decided at the meeting
   - Flag metrics that changed direction based on board discussion

## Frameworks to Apply
- **Minutes Standard:** Record decisions and rationale, not discussions. Attribution only when specifically requested by a member.
- **Action Item Standard:** Every action must have a single owner (not a team), a specific deliverable (not an activity), and a deadline (not "ongoing").

## Checklists

### Minutes Quality Gate
- [ ] All decisions are captured with resolution text and vote
- [ ] All action items are listed with owners and deadlines
- [ ] No verbatim quotes without the speaker's approval
- [ ] Confidential sections are marked
- [ ] Attendance is accurately recorded
- [ ] Prior minutes approval is noted
- [ ] Chair has reviewed and approved the draft

### Follow-Up Quality Gate
- [ ] Decision log updated with all new decisions
- [ ] Action item tracker updated with all new items and status changes
- [ ] Action item assignments sent to owners
- [ ] Board scorecard updated
- [ ] Minutes distributed to all board members
- [ ] All materials uploaded to board portal

## Output
- Approved draft minutes (pending formal approval at next meeting)
- Updated decision log
- Updated action item tracker
- Action item assignment notifications to owners
- Updated board scorecard

## Handoffs
- Minutes are formally approved at the next board meeting (opening agenda item)
- Action items are tracked through the next meeting-prep cycle
- Decision outcomes are reported in the next quarterly board review

## Metrics
| Metric | Target | Measurement |
|---|---|---|
| Draft minutes to Chair | Within 48 hours of meeting | Timestamp tracking |
| Minutes distributed to board | Within 5 business days | Timestamp tracking |
| Decision log updated | Within 24 hours | Timestamp tracking |
| Action items assigned | Within 24 hours | Notification timestamps |
| Action item completion rate | >85% on time | Tracker analysis |
