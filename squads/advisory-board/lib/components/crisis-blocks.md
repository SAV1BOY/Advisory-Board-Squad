# Crisis Blocks

## Purpose

Reusable structural blocks for crisis identification, response, communication, and recovery at board level. Crises compress decision timelines and amplify consequences. These blocks provide pre-built structures so leadership spends its scarce attention on judgment rather than format during high-pressure moments.

## Structure

### Block 1 — Crisis Identification and Classification

Rapidly categorizes the crisis to activate the correct response level.

**Fields:**
- **Crisis ID:** Unique identifier (format: `CRISIS-YYYY-NNN`).
- **Crisis title:** Plain-language name.
- **Discovery timestamp:** When the crisis was first identified.
- **Classification:** Severity level — Level 1 (existential: company survival at risk), Level 2 (severe: major revenue, legal, or reputational impact), Level 3 (significant: material disruption but contained).
- **Category:** Operational, financial, reputational, legal/regulatory, security, leadership, natural disaster.
- **Blast radius:** What is affected — customers, employees, partners, investors, public, regulators.
- **Time pressure:** How quickly the situation deteriorates without action (hours, days, weeks).
- **Information quality:** What is known, what is suspected, what is unknown.

### Block 2 — Crisis Team Activation

Defines who is responsible and how they coordinate.

**Fields:**
- **Crisis lead:** Single person with decision authority during the crisis.
- **Core team:** Names and roles of people in the crisis response group.
- **Communication channel:** Primary coordination channel (e.g., dedicated Slack channel, war room).
- **Cadence:** Meeting frequency during the crisis (e.g., every 4 hours for Level 1).
- **External advisors:** Legal counsel, PR firm, technical experts on standby.
- **Board notification:** When and how the board is informed (Level 1: immediately; Level 2: within 24 hours; Level 3: next scheduled meeting).
- **Decision authority matrix:** What the crisis lead can decide unilaterally vs. what requires CEO or board approval.

### Block 3 — Containment Plan

Stops the bleeding before fixing the root cause.

**Fields:**
- **Immediate containment actions:** Numbered list of steps to limit damage in the first 2-24 hours.
- **Triage priorities:** What is protected first (people safety > legal exposure > customer impact > financial impact > reputation).
- **Dependencies:** External parties or resources needed for containment.
- **Cost of containment:** Estimated financial and operational cost of containment actions.
- **Containment success criteria:** How you know containment has worked.
- **Time estimate:** How long containment will take.

### Block 4 — Stakeholder Communication Plan

Manages the narrative with different audiences simultaneously.

**Fields per stakeholder group:**
- **Stakeholder group:** Employees, customers, investors, press, regulators, partners.
- **Key message:** Core message tailored to this audience (max 3 sentences).
- **Channel:** How the message will be delivered.
- **Timing:** When the message goes out (relative to other stakeholder groups).
- **Spokesperson:** Who delivers the message.
- **Q&A preparation:** Anticipated questions and approved responses.
- **Follow-up cadence:** How often updates will be provided and through what channel.
- **Principles:** Lead with what you know, acknowledge what you do not, commit to transparency, never speculate.

### Block 5 — Root Cause and Resolution

Addresses the underlying cause once containment is achieved.

**Fields:**
- **Root cause analysis:** What caused the crisis (use 5 Whys or fault tree analysis).
- **Contributing factors:** Systemic conditions that enabled the root cause.
- **Resolution actions:** Steps to fix the root cause permanently.
- **Owner per action:** Single accountable person for each resolution step.
- **Timeline:** When each resolution action will be complete.
- **Verification:** How you will confirm the root cause is eliminated.
- **Recurrence prevention:** Structural changes to prevent similar crises.

### Block 6 — Crisis Postmortem

Captures lessons after the crisis is resolved.

**Fields:**
- **Timeline of events:** Chronological record of what happened and when.
- **What went well:** Response actions that worked and should be codified.
- **What went poorly:** Response failures with root cause for each.
- **What was lucky:** Favorable outcomes that were not the result of good process.
- **Lessons learned:** Specific, actionable lessons (link to `data/registries/lessons-learned-registry.yaml`).
- **Process changes:** Updates to crisis response procedures based on this experience.
- **Early warning improvements:** New monitoring or indicators that would detect this crisis sooner.
- **Cost accounting:** Total financial, reputational, and operational cost of the crisis.
- **Recovery timeline:** How long until normal operations resumed.
- **Board debrief date:** When the full postmortem was presented to the board.

## Usage

1. **Block 1** is completed within the first hour of crisis identification. Speed of classification drives speed of response.
2. **Block 2** is activated immediately after classification. Pre-assign crisis roles before crises occur.
3. **Block 3** is the first operational deliverable. Contain before you communicate.
4. **Block 4** follows containment. Communicate early but never before you have something true and useful to say.
5. **Block 5** begins after containment succeeds. Do not rush to root cause while the building is still on fire.
6. **Block 6** is completed within 2 weeks of resolution. Delay erodes memory and reduces lesson quality.

## Example

```markdown
# Crisis Record: Customer Data Exposure Incident

## Classification
- **Crisis ID:** CRISIS-2026-003
- **Severity:** Level 2 (severe)
- **Category:** Security
- **Discovery:** 2026-02-14 at 09:23 UTC
- **Blast radius:** 2,400 customers, potential regulatory attention
- **Time pressure:** Hours — data still accessible when discovered
- **Information quality:** Known: exposed API endpoint. Unknown: whether data was accessed by unauthorized parties.

## Containment (completed in 3 hours)
1. Disabled exposed API endpoint at 09:41 UTC
2. Rotated all affected API keys by 10:15 UTC
3. Engaged forensic security firm by 11:00 UTC
4. Legal counsel notified at 09:30 UTC

## Communication Sequence
| Audience | Timing | Channel | Spokesperson |
|----------|--------|---------|-------------|
| Board | T+1 hour | Emergency call | CEO |
| Affected customers | T+6 hours | Email | CEO |
| All customers | T+8 hours | Blog post | CTO |
| Regulators | T+24 hours | Formal filing | Legal counsel |
| Press (if contacted) | Reactive | Statement | Comms lead |
```
