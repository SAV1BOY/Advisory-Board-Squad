# Escalation Pattern

## Pattern Name

Escalation — structured elevation of decisions, risks, or conflicts to higher authority when local resolution fails or stakes exceed local authority.

## When to Use

- A decision exceeds the decision-maker's authority (financial threshold, strategic impact, irreversibility).
- Two peers or teams cannot resolve a disagreement after a good-faith attempt.
- A risk materializes that exceeds the risk owner's mitigation authority.
- Information surfaces that changes the strategic context and leadership must be informed.
- A timeline is at risk and the delay has cross-functional or customer-facing impact.
- Ethical concerns arise that require senior judgment.

Do NOT use when:
- The issue can be resolved by the people directly involved with reasonable effort (escalation should not replace collaboration).
- Escalation is being used to avoid making a difficult decision that is within your authority.
- The purpose is political — to get a senior person to overrule a peer without attempting direct resolution.

## Structure

```
1. ATTEMPT    → Try to resolve at the current level first
2. RECOGNIZE  → Identify that escalation is needed
3. PACKAGE    → Prepare the escalation with sufficient context
4. ROUTE      → Send to the right person through the right channel
5. RESOLVE    → The escalation recipient makes a decision
6. CLOSE      → Communicate the resolution and capture lessons
```

## Steps

### Step 1: Attempt Local Resolution
- Before escalating, make a genuine attempt to resolve the issue directly.
- Document the attempt: who was involved, what was tried, why it failed.
- Minimum expectation: one direct conversation (not just a Slack message) between the parties.
- If the issue is time-critical (safety, legal, existential), skip this step and escalate immediately.

### Step 2: Recognize the Escalation Trigger
- Identify which trigger applies:
  - **Authority gap:** "I do not have the authority to make this call."
  - **Deadlock:** "We have tried to agree and cannot."
  - **Risk threshold:** "This risk exceeds my mitigation authority."
  - **Information asymmetry:** "Leadership needs to know this to make other decisions."
  - **Timeline breach:** "We will miss the deadline without intervention."
  - **Ethical concern:** "I believe this action violates our values or the law."
- Name the trigger explicitly in the escalation. This prevents the recipient from sending it back down without understanding why.

### Step 3: Package the Escalation
- The escalation package contains:
  - **One-sentence summary:** What the issue is.
  - **Context:** What led to this point (3-5 sentences maximum).
  - **What was tried:** Resolution attempts and why they failed.
  - **Options:** The 2-3 possible paths forward with pros and cons.
  - **Recommendation:** Your best judgment on what should happen, even if you lack authority.
  - **Time sensitivity:** When a decision is needed and what happens if it is delayed.
  - **Impact:** Who and what is affected.
- Packaging quality matters. A well-packaged escalation gets resolved faster. A vague "we have a problem" creates more meetings.

### Step 4: Route to the Right Person
- Escalate to the **lowest level of authority** that can resolve the issue. Do not skip levels unless the intermediate level is the problem.
- Routing guide:
  - **Operational decisions:** Direct manager or functional lead.
  - **Cross-functional conflicts:** The lowest shared manager of the conflicting parties.
  - **Financial decisions:** The budget owner at the required threshold level.
  - **Strategic decisions:** CEO or board depending on magnitude.
  - **Ethical concerns:** CEO, legal counsel, or board depending on severity.
- Channel: Use the most direct channel available. Do not hide escalations in email threads. A dedicated message or brief meeting is appropriate.
- Copy: Include the other involved parties. Escalations should never be a surprise to the other side.

### Step 5: Resolve the Escalation
- The escalation recipient:
  - Acknowledges receipt within the stated timeframe (or within 4 hours if no timeframe stated).
  - May request additional information but should resolve within one additional cycle.
  - Makes a decision and communicates it to all involved parties.
  - If the recipient cannot resolve it, they escalate further using the same pattern (do not let it stall).
- The resolution includes: the decision, the rationale, and any follow-up actions with owners and deadlines.

### Step 6: Close the Loop
- Communicate the resolution to everyone affected, not just the escalating parties.
- Update relevant registries (decision registry, risk registry, action items).
- Capture lessons: Was this escalation necessary? Could it have been prevented? Does a policy or authority change prevent recurrence?
- If the same type of escalation recurs three or more times, treat it as a systemic issue and fix the root cause (unclear authority, missing policy, organizational design flaw).

## Anti-Patterns

| Anti-Pattern | Description | Consequence |
|-------------|-------------|-------------|
| Premature escalation | Escalating before attempting local resolution | Creates bottlenecks at senior levels; erodes team autonomy |
| Escalation avoidance | Refusing to escalate when triggers are clearly met | Issues fester; small problems become crises |
| Punishment for escalation | Culture where escalating is seen as weakness or disloyalty | Issues go underground; leadership operates blind |
| Surprise escalation | Escalating without informing the other party | Destroys trust; turns problem-solving into politics |
| Vague escalation | "We have a problem" without context, options, or recommendation | Wastes the recipient's time; delays resolution |
| Level-skipping | Escalating past the person who can resolve it to someone more senior | Undermines managers; creates organizational chaos |
| Escalation ping-pong | Recipient sends it back without resolving; original escalator sends it back up | Issue is never resolved; all parties frustrated |

## Examples

### Example 1: Cross-Functional Resource Conflict

**Trigger:** Deadlock. VP Engineering and VP Marketing both need the same senior developer for the next 3 weeks. Neither will yield. Direct conversation attempted; no resolution.

**Package:**
> **Summary:** Dev resource conflict between engineering (SOC2 compliance deadline) and marketing (launch campaign tooling).
> **Attempted:** VP Eng and VP Marketing met Tuesday; both deadlines are firm.
> **Options:** (A) Developer goes to engineering, marketing delays launch 2 weeks. (B) Developer goes to marketing, SOC2 misses deadline, enterprise deal at risk. (C) Hire contractor for marketing work at $25K.
> **Recommendation:** Option C. The enterprise deal ($180K ACV) justifies the contractor cost.
> **Time sensitivity:** Decision needed by Thursday or both deadlines are at risk.

**Route:** CEO (lowest shared authority).

**Resolution:** CEO approves Option C within 2 hours. Contractor engaged Friday.

### Example 2: Ethical Concern Escalation

**Trigger:** Ethical concern. An engineer discovers that a customer-facing metric is being calculated incorrectly in the customer's favor to avoid churn.

**Package:**
> **Summary:** Customer health score calculation contains a known error that inflates scores, reducing churn triggers.
> **Context:** Error was introduced 3 months ago. Product lead was informed and said "leave it for now, churn numbers look better."
> **Recommendation:** Fix the calculation immediately and notify affected customers.
> **Time sensitivity:** Every day the error persists increases our liability and ethical exposure.

**Route:** CEO and legal counsel simultaneously. This is not a peer conflict; it is a values issue.

**Resolution:** CEO orders immediate fix, customer notification within 48 hours, and a review of the product lead's judgment.
