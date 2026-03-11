# Stakeholder Communication Pattern

## Pattern Name

Stakeholder Communication — a structured approach to planning, executing, and maintaining communications with all stakeholder groups (investors, employees, customers, partners, board members) that ensures consistency, appropriate transparency, and trust-building across audiences with different information needs and communication preferences.

## When to Use

- The company is communicating a significant event: fundraise, pivot, leadership change, layoff, product launch, crisis, or strategic shift.
- Regular cadence communications: quarterly investor updates, all-hands meetings, board pre-reads, customer newsletters.
- Stakeholder satisfaction scores indicate communication gaps or misalignment.
- The company is scaling and informal communication channels are breaking down.
- Post-crisis, when trust needs rebuilding through deliberate communication.

Do NOT use when:
- Day-to-day operational communication — this pattern is for strategic and high-stakes communication.
- The message is routine and low-impact — over-engineering routine communication creates overhead without value.

## Structure

```
1. MAP        → Identify all stakeholder groups and their information needs
2. SEQUENCE   → Determine the order in which groups should be informed
3. CRAFT      → Develop messages tailored to each audience
4. DELIVER    → Execute communication through appropriate channels
5. LISTEN     → Collect feedback and gauge reception
6. FOLLOW UP  → Address questions, concerns, and commitments from the communication
```

## Steps

### Step 1: Map Stakeholders and Information Needs

Use `lib/utilities/stakeholder-mapping-canvas.md` to identify:
- **Who:** All groups affected by or interested in this communication
- **What they care about:** Each group's primary concerns and interests
- **What they need to know:** The minimum information required for each group
- **What they should not know:** Information that is confidential, premature, or irrelevant to this group
- **Their current sentiment:** Positive, neutral, or concerned — this shapes tone and framing

| Stakeholder Group | Primary Concern | Communication Need | Sensitivity Level |
|-------------------|----------------|-------------------|-------------------|
| Board / Advisors | Strategic implications, governance impact | Full context, decision rationale | High — receive first or simultaneously with investors |
| Investors | Financial impact, trajectory, risk | Performance data, forward outlook | High — contractual information rights may apply |
| Employees | Job impact, culture, direction | Honest context, what changes for them | High — leaks are fast; communicate before rumors |
| Customers | Service continuity, product direction | Reassurance, concrete commitments | Medium — focus on "what this means for you" |
| Partners | Relationship continuity, strategic alignment | Joint implications, shared roadmap | Medium — tailor to partnership depth |
| Public / Media | Narrative, positioning | Controlled messaging, spokesperson designation | Low — only if event is public-facing |

### Step 2: Sequence Communications

The order matters. General principles:
1. **Board and legal counsel first** (for events requiring governance approval or legal review).
2. **Investors second** (especially if contractual information rights exist).
3. **Employees third** (before any external communication — employees should never learn about their company from the press).
4. **Customers fourth** (especially if the event affects product or service).
5. **Partners fifth** (before public announcement if partnership is affected).
6. **Public / media last** (only if the event warrants external communication).

**Compression rule:** For fast-moving events (crisis, leak), compress the sequence to hours rather than days. In extreme cases, communicate to all groups simultaneously rather than risk information asymmetry.

### Step 3: Craft Messages

For each audience, apply these principles:
- **Lead with the "so what."** What does this mean for the specific audience? Do not bury the implication behind context.
- **Be honest about uncertainty.** If the outcome is unknown, say so. "We do not yet know X, and here is how we plan to find out" builds more trust than false certainty.
- **Separate facts from interpretation.** Present the facts first, then the company's interpretation and plan.
- **Anticipate questions.** Draft a FAQ for each audience. The questions you do not want to answer are the ones you most need to prepare for.
- **Consistent core, tailored framing.** The core facts must be identical across all audiences. The framing, emphasis, and detail level are tailored.

### Step 4: Deliver Through Appropriate Channels

| Audience | High-Impact Events | Regular Cadence |
|----------|-------------------|-----------------|
| Board | Live call + written memo | Pre-read package + quarterly meeting |
| Investors | Live call + follow-up email | Monthly/quarterly written update |
| Employees | All-hands meeting + written follow-up | Weekly standup, monthly all-hands |
| Customers | Direct email from leadership | Product updates, newsletters |
| Partners | Direct call to key contacts | Quarterly business reviews |
| Public | Press release / blog post | As warranted |

### Step 5: Listen and Gauge Reception

- After each communication, actively collect feedback:
  - Board: Immediate discussion and Q&A
  - Investors: Track questions and concerns raised in response
  - Employees: Anonymous pulse survey within 48 hours; open office hours within 1 week
  - Customers: Monitor support tickets and churn signals in the 2 weeks following communication
- Track: Did the message land as intended? What was misunderstood? What questions were unanticipated?

### Step 6: Follow Up

- Address every unanswered question within 1 week.
- If commitments were made during the communication, track them in the action-item tracker and report progress.
- Schedule follow-up communication for ongoing situations: "We said we would update you by [date]. Here is the update."
- Closing the loop is what separates communication from noise.

## Anti-Patterns

| Anti-Pattern | Description | Consequence |
|-------------|-------------|-------------|
| Employees last | Telling investors or press before employees | Destroys trust; employees feel disrespected |
| Happy ears only | Communicating only good news; hiding problems | Stakeholders lose trust when problems eventually surface |
| Firehose | Sharing all information with all audiences | Cognitive overload; critical messages get lost |
| Once and done | Communicating once and assuming the message was received | Messages require repetition; understanding builds over time |
| Tone deafness | Using corporate jargon or upbeat framing during painful events | Perceived as inauthentic; amplifies negative sentiment |

## Related Patterns

- `lib/utilities/stakeholder-mapping-canvas.md` — tool for mapping stakeholder groups and needs
- `lib/components/meeting-blocks.md` — for structuring communication within board meetings
- `lib/components/crisis-blocks.md` — for crisis-specific communication structure
- `lib/patterns/escalation-pattern.md` — for escalating communication when initial approach fails
- `data/metrics/stakeholder-satisfaction-score.md` — metric measuring communication effectiveness over time
