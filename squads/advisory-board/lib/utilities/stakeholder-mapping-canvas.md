# Stakeholder Mapping Canvas

## Purpose

A structured tool for identifying, categorizing, and prioritizing all stakeholders relevant to a decision, initiative, or communication. The canvas maps stakeholders along two dimensions — influence (ability to affect outcomes) and interest (degree to which they are affected) — and produces a tailored engagement strategy for each quadrant. This prevents the common failure of over-communicating to low-influence stakeholders while under-engaging those with the power to derail or accelerate an initiative.

## How to Use

### Step 1: Identify All Stakeholders

List every individual or group with a relationship to the decision or initiative. Cast the net wide initially — it is easier to remove stakeholders than to discover omitted ones mid-execution.

**Stakeholder categories to consider:**
- **Internal:** Board members, executive team, employees (by function/level), co-founders
- **Financial:** Investors (lead, follow-on, angels), lenders, potential acquirers
- **Customer:** Key accounts, customer segments, churned customers, prospects
- **Partner:** Technology partners, channel partners, integration partners, suppliers
- **Regulatory:** Government agencies, industry bodies, compliance authorities
- **Community:** Industry analysts, media, open-source community, local community
- **Personal:** Founder advisors, mentors, family members (for founder-level decisions)

### Step 2: Map on the Influence-Interest Grid

Place each stakeholder on a 2x2 matrix:

```
                    HIGH INFLUENCE
                         |
    KEEP SATISFIED       |      MANAGE CLOSELY
    (High influence,     |      (High influence,
     low interest)       |       high interest)
                         |
   ──────────────────────┼──────────────────────
                         |
    MONITOR              |      KEEP INFORMED
    (Low influence,      |      (Low influence,
     low interest)       |       high interest)
                         |
                    LOW INFLUENCE
         LOW INTEREST                HIGH INTEREST
```

**Quadrant definitions:**
- **Manage Closely (top-right):** These stakeholders have both the power to affect outcomes and a strong interest in the result. They require deep engagement, frequent updates, and active relationship management. Examples: lead investor, board chair, CEO, key customer.
- **Keep Satisfied (top-left):** These stakeholders have influence but are not deeply interested in the day-to-day. Engage them sufficiently to maintain support but do not overwhelm with detail. Examples: follow-on investors, regulatory bodies (when not actively regulating).
- **Keep Informed (bottom-right):** These stakeholders are highly affected but lack influence over the outcome. They deserve transparent communication and respect but do not drive the engagement strategy. Examples: individual employees during a reorg, small customers during a pricing change.
- **Monitor (bottom-left):** These stakeholders have low influence and low interest currently. Monitor for changes in either dimension but do not invest significant engagement effort. Examples: industry analysts for a pre-revenue startup, local community for a remote-first company.

### Step 3: Assess Current Relationship State

For each stakeholder in the "Manage Closely" and "Keep Satisfied" quadrants, assess:

| Dimension | Assessment |
|-----------|------------|
| **Awareness:** | Do they know about this initiative/decision? |
| **Understanding:** | Do they understand what it means for them? |
| **Support level:** | Supporter, Neutral, Skeptic, or Opponent |
| **Trust level:** | High, Medium, Low |
| **Unmet needs:** | What do they need from us that they are not getting? |
| **Risk:** | What could cause them to withdraw support or actively oppose? |

### Step 4: Design Engagement Strategy

For each key stakeholder (Manage Closely quadrant), define:

```markdown
## [Stakeholder Name/Group]

**Quadrant:** Manage Closely
**Current support:** [Supporter / Neutral / Skeptic / Opponent]
**Desired support:** [Target state]
**Key concerns:** [What they care about most]
**Engagement approach:**
  - Channel: [How to communicate — meeting, email, call, document]
  - Frequency: [How often — weekly, bi-weekly, monthly, event-driven]
  - Owner: [Who is responsible for this relationship]
  - Key messages: [2-3 messages tailored to their concerns]
  - Success indicator: [How we will know engagement is working]
**Risks:**
  - [What could go wrong with this stakeholder]
  - [Mitigation approach]
```

### Step 5: Monitor and Adjust

Stakeholder positions are not static. Re-map quarterly or upon significant events:
- Stakeholders can move quadrants (a small customer becomes a key account; a passive investor becomes activist)
- Support levels shift based on company performance and communication quality
- New stakeholders emerge (new investors, new partners, new regulators)

## Scale/Criteria

### Influence Assessment Factors

| Factor | High Influence | Low Influence |
|--------|---------------|---------------|
| Decision authority | Can approve, veto, or block | No formal authority |
| Resource control | Controls budget, talent, or access | No resource leverage |
| Information advantage | Holds critical information or expertise | No unique information |
| Network power | Can mobilize other stakeholders | Limited network reach |
| Contractual rights | Has legal or contractual standing | No contractual claims |

### Interest Assessment Factors

| Factor | High Interest | Low Interest |
|--------|--------------|-------------|
| Direct impact | Materially affected by outcome | Minimally affected |
| Emotional investment | Personally invested in the result | Indifferent |
| Frequency of interaction | Regular engagement with the company | Rare interaction |
| Dependency | Relies on the company for value | Independent |
| Strategic alignment | Outcome affects their own strategy | No strategic link |

## Template

```
# Stakeholder Map: [Initiative/Decision Name]
# Date: [Date]
# Owner: [Name]

## Manage Closely (High Influence, High Interest)
1. [Name/Group] — Support: [level] — Primary concern: [concern]
2. [Name/Group] — Support: [level] — Primary concern: [concern]

## Keep Satisfied (High Influence, Low Interest)
1. [Name/Group] — Support: [level] — Engagement: [approach]
2. [Name/Group] — Support: [level] — Engagement: [approach]

## Keep Informed (Low Influence, High Interest)
1. [Name/Group] — Communication: [channel and frequency]
2. [Name/Group] — Communication: [channel and frequency]

## Monitor (Low Influence, Low Interest)
1. [Name/Group] — Review trigger: [what would move them to another quadrant]

## Key Risks
- [Stakeholder risk 1 and mitigation]
- [Stakeholder risk 2 and mitigation]

## Review Schedule
- Next review: [Date]
- Review trigger events: [List of events that should prompt immediate re-mapping]
```

## Related Patterns

- `lib/patterns/stakeholder-communication-pattern.md` — communication approach by stakeholder group
- `lib/taxonomies/stakeholder-types.md` — taxonomy of stakeholder categories
- `lib/patterns/escalation-pattern.md` — for escalating stakeholder concerns
- `data/metrics/stakeholder-satisfaction-score.md` — metric tracking stakeholder satisfaction
- `lib/components/crisis-blocks.md` — stakeholder management during crisis events
