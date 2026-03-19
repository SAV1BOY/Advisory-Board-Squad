# Task: Run Board Meeting

## Objective
Facilitate an effective board meeting that produces clear decisions, actionable guidance, and efficient use of every participant's time. The Chair leads; Board Ops supports.

## Trigger
- Board meeting start time (day-of execution)

## Agents Involved
- **Lead:** Board Chair (facilitation)
- **Support:** Board Ops (minutes, time management, logistics)
- **Participants:** Board members, CEO, invited management presenters


## Agent Assignment
> Routing: see `config.yaml → routing → board-meeting-run`

- **Lead:** board-chair (Board Chair)
- **Support:** governance-clerk (Simon Sinek), simplicity-czar (Derek Sivers)

## Pre-Requisites
- [ ] All meeting-prep.md steps completed
- [ ] Quorum confirmed
- [ ] Technology tested and working
- [ ] Minute-taker ready with templates
- [ ] Chair briefed on agenda flow and time allocation

## Steps

1. **Pre-Meeting Setup (15 minutes before start)**
   - Open video room or physical room
   - Display agenda on screen
   - Board Ops prepares decision tracking sheet and action item log
   - Chair and CEO have a final 5-minute alignment check

2. **Opening (5 minutes)**
   - Chair calls meeting to order and confirms quorum
   - Chair asks for agenda modifications
   - Chair asks for conflict of interest declarations on today's items
   - Chair calls for approval of prior meeting minutes (motion, second, vote)

3. **CEO Update (allocated time — typically 20 minutes)**
   - CEO presents update assuming pre-read has been completed (no re-reading the deck)
   - Chair manages Q&A — ensures questions are distributed, not dominated by one voice
   - Board Ops captures key data points shared verbally that supplement pre-read

4. **Financial Review (allocated time — typically 20 minutes)**
   - CFO highlights variances and forward guidance only (pre-read covered the detail)
   - Chair directs questions to focus on material variances and strategic implications
   - Board Ops notes any financial commitments or concerns raised

5. **Strategic / Decision Items (allocated time — typically 40+ minutes each)**
   - Presenter provides 10-minute context (not a re-read of the brief)
   - Chair opens with: "What questions do we need answered before deciding?"
   - Structured discussion — Chair ensures all voices are heard
   - If decision required: Chair summarizes options, calls for recommendation, facilitates vote
   - Board Ops reads back the decision as captured for confirmation
   - Chair confirms owner, timeline, and reporting requirements for the decision

6. **Discussion Management Techniques**
   - If discussion goes off-track: "Let me park that for follow-up and bring us back to the decision at hand."
   - If one person dominates: "Thank you, [Name]. I want to hear from others. [Name], what is your perspective?"
   - If discussion is circular: "I am hearing two positions. Let me summarize them and ask: what data would resolve this?"
   - If time is running out: "We have 5 minutes left on this item. Can we reach a decision, or do we need to schedule a follow-up?"
   - If the board is not ready to decide: "I propose we table this, request [specific additional information], and decide at [next meeting / async by date]."

7. **Committee Reports (allocated time — typically 15 minutes)**
   - Each committee chair provides a brief verbal update
   - Chair asks if any committee recommendations require full board action

8. **Action Item Review (10 minutes)**
   - Board Ops reads through open action items with status updates
   - Board Ops reads new action items created during today's meeting for confirmation
   - Chair assigns owners and deadlines for any unassigned items

9. **Executive Session (15 minutes — board members only)**
   - Management is excused
   - Chair facilitates open discussion
   - Any outcomes are communicated to CEO by Chair after the meeting

10. **Closing (5 minutes)**
    - Chair summarizes: decisions made, key action items, next meeting date
    - Chair asks: "Is there anything we should add to the next agenda?"
    - Chair adjourns the meeting

## Frameworks to Apply
- **Structured Decision Making:** For each decision item — clarify the question, discuss options, capture the decision, assign the owner
- **Round-Robin:** Ensure every board member speaks on critical items
- **Parking Lot:** Capture off-topic but important items for follow-up without derailing the agenda
- **Time Boxing:** Strict adherence to agenda time allocations with 5-minute warnings

## Checklists

### During-Meeting Quality Gate
- [ ] Quorum maintained throughout decision items
- [ ] Each decision is clearly stated, voted on, and captured in real-time
- [ ] All board members had opportunity to speak on major items
- [ ] Time allocation was respected (no item exceeded 150% of allotted time)
- [ ] Parking lot items were captured for follow-up
- [ ] Executive session was held

### Post-Meeting Immediate (within 1 hour)
- [ ] Chair and CEO debrief on executive session outcomes
- [ ] Board Ops confirms action item list is complete
- [ ] Any urgent follow-ups are initiated

## Output
- Real-time decision record (confirmed by board during meeting)
- Action items list (confirmed by board during meeting)
- Parking lot items for follow-up
- Executive session summary (Chair's notes)

## Handoffs
- Board Ops transitions to minutes-and-followups.md task immediately after meeting
- CEO communicates executive session feedback to management team as appropriate
- Action item owners begin execution

## Metrics
| Metric | Target | Measurement |
|---|---|---|
| Meeting duration vs. planned | Within 10% of planned duration | Time tracking |
| Decision items resolved | >80% of planned decision items decided | Decision tracking |
| Board member participation | All members spoke on decision items | Observation |
| Action items clarity | 100% have owner and deadline | Action item review |
| Post-meeting satisfaction | >4/5 average from board members | Periodic survey |
