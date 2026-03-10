# Crisis Statement Examples — Swipe File

## Purpose
This swipe file contains structures and examples for crisis communications at the board and executive level. These are structural patterns for crafting honest, effective crisis statements under time pressure — not templates to copy verbatim.

## The Immediate Acknowledgment Statement
**Use within:** First 2-6 hours of a crisis becoming public.
**Goal:** Establish that leadership is aware, taking responsibility, and acting.

### Structure
1. Name what happened — plainly, without minimizing
2. State what you know and what you do not yet know
3. Describe the immediate actions being taken
4. Commit to a timeline for the next update

### Example (Product / Service Incident)
"On [date], we identified [specific issue] affecting [scope]. We immediately [actions taken]. [Number] customers were impacted. We understand the impact this has on [their operations / their trust]. Here is what we are doing: [Action 1], [Action 2], [Action 3]. We will provide updates every [timeframe]. Our [CEO/CTO] is personally overseeing the response. If you have been affected, please [specific instructions]."

### Example (Data Breach)
"We discovered unauthorized access to a database containing customer account information. We immediately engaged our security team, shut down the access vector, and notified law enforcement. We are still determining the scope of affected accounts. We will notify all potentially affected customers directly within 48 hours with specific guidance on protective steps. We take full responsibility for the security of your data."

### Anti-Patterns for Initial Statements
- "We take security seriously" — empty phrase that signals nothing
- "A small number of users were affected" — minimizing language that will be contradicted by facts
- "There is no evidence that data was misused" — absence of evidence is not evidence of absence
- "We are confident this is an isolated incident" — premature certainty destroys credibility if wrong

## The Root Cause Explanation
**Use within:** 48-72 hours after the initial statement.
**Goal:** Demonstrate understanding and systematic response.

### Structure
1. Recap what happened (for people encountering the issue for the first time)
2. Explain the root cause in accessible language
3. Describe the immediate fix already deployed
4. Describe systemic changes being implemented to prevent recurrence
5. Acknowledge impact on affected stakeholders specifically

### Example (Operational Failure)
"On March 3, a configuration error in our payment processing system caused 12,400 transactions to be charged twice. The root cause was a retry mechanism that failed to check for completed transactions before reissuing charges. We have refunded all duplicate charges as of March 4. To prevent recurrence, we are implementing idempotency checks at every payment endpoint, adding real-time anomaly detection for duplicate charge patterns, and requiring two-person review for all payment system configuration changes. We understand that unexpected charges cause real financial stress, and we apologize to every customer who was affected."

## The Leadership Accountability Statement
**Use when:** The crisis involves leadership failure, cultural issues, or governance breakdown.
**Goal:** Signal genuine accountability without defensive language.

### Structure
1. Acknowledge the failure at the leadership level — not "mistakes were made" but "I/we failed to..."
2. Name the specific systemic failures (incentives, oversight, culture)
3. Describe structural changes (not just personnel changes)
4. Commit to third-party review or external accountability

### Example (Culture / Conduct Crisis)
"The experiences described by our former employees are unacceptable, and they happened on my watch. We failed to create adequate reporting channels, failed to act on early warning signs, and failed to hold leaders accountable when concerns were raised. Effective immediately, we are engaging an independent firm to conduct a thorough review of our workplace culture, reporting structures, and HR practices. Their findings and recommendations will be shared with the full company. We are also establishing an independent ombudsman role reporting directly to the board, not to management."

### Anti-Patterns for Accountability Statements
- "This does not reflect our values" — if it happened under your leadership, it reflects your operational values
- "We are terminating the individuals responsible" — scapegoating individuals without addressing systems
- "We have zero tolerance for..." — if you had zero tolerance, it would not have happened
- "Mistakes were made" — passive voice that avoids naming who is accountable

## The Strategic Pivot Statement
**Use when:** Business results require a significant change in direction (layoffs, market exit, product discontinuation).
**Goal:** Communicate the change honestly while maintaining confidence in the path forward.

### Structure
1. State the decision clearly in the first sentence
2. Explain the business reality that drove the decision
3. Describe what changes for whom
4. Describe what does not change (mission, core commitments)
5. Acknowledge the human impact
6. Outline the path forward with specific next steps

### Example (Layoffs)
"Today we are reducing our team by 120 people, approximately 18% of the company. This decision reflects a fundamental shift in our market: enterprise budgets contracted 30% this year, and our sales cycle has lengthened from 45 to 120 days. We over-hired against growth projections that did not materialize, and that was a leadership failure in planning. Every affected team member will receive 16 weeks of severance, 6 months of healthcare continuation, and dedicated outplacement support. We will publish an opt-in talent directory to help affected colleagues find their next role. For the team going forward: our product serves a real need, our customers depend on us, and we now have the cost structure to reach profitability within three quarters."

## The Board-to-Stakeholder Statement
**Use when:** The board itself must communicate during a governance crisis.

### Example (Governance Crisis)
"The Board of Directors has concluded its independent review of the matters reported on March 15. The review, conducted by outside counsel with forensic accounting support, found that financial controls were insufficient to prevent the misstatements identified. The Board has taken the following actions: the CFO has been terminated for cause, the audit committee charter has been revised to require quarterly independent verification of material balances, and we have engaged a new external auditor. Restated financials will be filed within 60 days. The Board takes full responsibility for the governance failures that allowed this to occur."

## The HEARD Framework for Crisis Communication

| Step | Action |
|------|--------|
| **Hear** | Acknowledge that you understand the concern |
| **Empathize** | Demonstrate that you feel the impact on affected parties |
| **Apologize** | If warranted, apologize specifically — not "sorry if anyone was offended" |
| **Resolve** | State specifically what you are doing to fix the problem |
| **Diagnose** | Explain what you are doing to prevent recurrence |

## Crisis Communication Principles

| Principle | Application |
|-----------|-------------|
| Speed over completeness | Say what you know now. Update later. Silence is interpreted as hiding. |
| Specificity over generality | "12,400 customers" is credible. "A small number" is evasive. |
| Accountability over blame | "We failed to..." not "Mistakes were made by..." |
| Actions over promises | Describe what you have already done, not just what you plan to do. |
| Empathy over defense | Acknowledge impact before explaining cause. |
| One voice | Designate a single spokesperson. Contradictory statements multiply the crisis. |

## Board Application
- Approve crisis statement templates as part of the crisis communication playbook before a crisis occurs
- In real-time crisis, the board should review the statement before release but not wordsmith it to death — speed matters
- Ensure the statement is honest and empathetic, not defensive and legalistic
- After the crisis, review the statement's effectiveness and update templates based on lessons learned

## Cross-References
- See `swipe-sources/crisis-case-library-index.md` for historical crisis case studies
- See `workflows/07-crisis-response-72h.md` for the operational crisis response workflow
- See `swipe/crisis-playbooks/` for detailed playbooks by crisis type
- See `templates/briefs/crisis-brief.md` for the crisis brief template
- See `frameworks/postmortem-and-learning-loop.md` for post-crisis review structure
