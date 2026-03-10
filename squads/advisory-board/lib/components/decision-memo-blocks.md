# Decision Memo Blocks

## Purpose

Reusable structural blocks for composing decision memos at board level. These blocks ensure every decision memo covers the essential dimensions: context, options, analysis, recommendation, and dissent capture. Use them as building blocks rather than a rigid template so memos stay proportionate to the decision's weight.

## Structure

### Block 1 — Context Frame

Establishes why this decision exists now. Anchors the reader in the strategic moment.

**Fields:**
- **Decision title:** One-line name (verb + noun, e.g., "Expand into LATAM market").
- **Decision type:** Classify using `taxonomies/decision-types.md` (irreversible/reversible, one-way/two-way door).
- **Trigger:** What event, data point, or deadline forced this decision onto the agenda.
- **Time horizon:** When must a decision be made, and when will its effects be felt.
- **Stakeholders affected:** List roles, teams, or external parties with material exposure.

### Block 2 — Option Set

Enumerates the realistic options. Forces intellectual honesty about alternatives.

**Fields:**
- **Option name:** Short label.
- **Description:** 2-3 sentences on what this option entails.
- **Expected value range:** Best-case, base-case, worst-case outcomes.
- **Key assumptions:** What must be true for this option to work.
- **Reversibility:** How costly and slow is it to unwind.

### Block 3 — Analysis Engine

The analytical core. Choose sub-blocks based on decision type.

**Sub-blocks:**
- **Financial model snapshot:** NPV, IRR, payback period, or EV calculation (link to `utilities/ev-calculator.md`).
- **Scenario table:** 3-5 scenarios with probability weights (link to `utilities/scenario-table.md`).
- **Risk register extract:** Top 3-5 risks from `data/registries/risk-registry.yaml`.
- **Incentive alignment check:** Who wins and loses under each option (link to `utilities/incentive-map.md`).
- **Second-order effects:** Downstream consequences beyond the immediate decision.

### Block 4 — Recommendation

States the proposed path clearly and defends it.

**Fields:**
- **Recommended option:** Name from Option Set.
- **Rationale:** 3-5 bullet points explaining why this option dominates.
- **Confidence level:** High / Medium / Low with brief justification.
- **Pre-mortem flag:** The single most likely reason this recommendation fails.
- **Kill criteria:** Observable signals that should trigger reversal.

### Block 5 — Dissent & Commit Record

Captures disagreement before the decision is finalized so it is honored, not buried.

**Fields:**
- **Dissenting view:** Who disagreed and the substance of their objection.
- **Response to dissent:** How the recommendation accounts for (or overrides) the objection.
- **Commit statement:** Confirmation that dissenters will execute the decision fully once made.
- **Review trigger:** Conditions under which the dissenter's concern should reopen the decision.

### Block 6 — Action Cascade

Translates the decision into accountable next steps.

**Fields:**
- **Immediate actions (0-48 hours):** Who does what.
- **Short-term actions (1-4 weeks):** Milestones and owners.
- **Communication plan:** Who is told, in what order, using what channel.
- **Decision log entry:** Reference to `data/registries/decision-registry.yaml` entry ID.

## Usage

1. **Start with Block 1** for every decision memo regardless of weight.
2. **Include Block 2** with a minimum of two options (the proposed action and the null option "do nothing").
3. **Select Analysis sub-blocks** proportionate to stakes: small reversible decisions need only a quick scenario table; large irreversible ones need the full engine.
4. **Always include Block 5** — skipping dissent capture is an anti-pattern that erodes board trust.
5. **Close with Block 6** — a decision without actions is just an opinion.

## Example

```markdown
# Decision Memo: Acquire DataCo for $45M

## Context Frame
- **Decision type:** Irreversible, one-way door
- **Trigger:** DataCo approached us; LOI deadline is March 28
- **Time horizon:** Decision by March 21; integration effects over 18 months
- **Stakeholders:** Engineering (absorption), Finance (cash deployment), Customers (data product)

## Option Set
| Option | EV Range | Key Assumption | Reversibility |
|--------|----------|----------------|---------------|
| Acquire at $45M | $60-120M value creation | Retention of key engineers | Very low |
| Acquire at $35M (counter) | $70-130M value creation | DataCo accepts lower price | Very low |
| Pass | $0 net; competitor may acquire | Market window stays open | High |

## Analysis Engine
- **Financial snapshot:** NPV of $38M at 12% discount rate (see model v3.2)
- **Scenario table:** 60% base ($80M value), 25% upside ($120M), 15% downside (-$10M)
- **Top risk:** Key-person dependency on DataCo CTO (mitigation: retention package)

## Recommendation
- **Recommended option:** Acquire at $45M
- **Confidence:** Medium — hinges on retention
- **Pre-mortem flag:** CTO leaves within 12 months, IP value decays
- **Kill criteria:** If CTO declines retention terms before close, revert to Pass

## Dissent & Commit
- **Dissent (CFO):** Cash reserves drop below 8-month runway; prefers $35M counter
- **Response:** Runway remains at 11 months post-acquisition; $35M counter risks losing deal
- **Commit:** CFO commits to execute if board approves

## Action Cascade
- [ ] CEO signs LOI by March 22
- [ ] Legal begins diligence by March 25
- [ ] CFO models integration cost by April 1
- [ ] Comms to all-hands after close
```
