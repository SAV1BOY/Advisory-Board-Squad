# Irreversible (Type 1) Decision Memos

## Overview

Jeff Bezos popularized the distinction between Type 1 (irreversible, one-way door) and Type 2 (reversible, two-way door) decisions. Type 1 decisions demand rigorous analysis, broad input, and deliberate pacing. These memo examples model how to structure thinking around decisions you cannot undo.

## Framework: When Is a Decision Truly Irreversible?

A decision qualifies as Type 1 when:
- Reversal cost exceeds 10x the original investment
- Reversal damages relationships or reputation that took years to build
- Reversal is structurally impossible (legal, regulatory, or physical constraints)
- The decision creates path dependencies that foreclose future options

## Example 1: Selling a Business Unit

### Memo: Proposed Divestiture of [Division Y]

**Decision type:** Type 1 — Irreversible. Once sold, reacquisition would cost 3-5x current valuation and may not be possible.

**Recommendation:** Proceed with divestiture at or above $85M valuation.

**Analysis structure:**
- **Strategic rationale:** Division Y operates in a declining market segment. Its talent and capital are trapped in a business with negative growth trajectory.
- **Financial case:** Proceeds fund 24 months of R&D in our growth segment. Division Y's standalone cash flow turns negative by Year 3 under current trends.
- **What we lose permanently:** Customer relationships in adjacent segment, proprietary manufacturing knowledge, optionality to pivot Division Y into new applications.
- **What we cannot get back:** The team. Key engineers and operators will integrate into the acquirer's organization within 12 months.
- **Dissenting view:** Our CTO believes Division Y's technology platform could be repurposed for emerging applications within 3-5 years. This view has merit but requires $20M additional investment with uncertain outcome.

**Pre-mortem:** If this decision looks wrong in 3 years, the most likely reason is that the emerging applications our CTO identified became viable faster than expected. We assess this probability at 15-20%.

**Decision process:** Board vote required. Minimum 7-day deliberation period after memo distribution. External advisor review completed.

---

## Example 2: Exclusive Platform Commitment

### Memo: Proposal to Build Exclusively on [Platform Z] Infrastructure

**Decision type:** Type 1 — Migration cost estimated at $8M+ and 18 months if we later need to switch.

**Recommendation:** Proceed with exclusive commitment, contingent on negotiated exit provisions.

**Why this is irreversible:**
- Architecture will be deeply coupled to Platform Z APIs and services
- Team expertise will specialize in Platform Z tooling
- Customer integrations will depend on Platform Z capabilities
- Switching costs compound with every month of development

**Benefits of commitment:**
- 40% reduction in infrastructure costs via committed-use discounts
- Access to beta features and dedicated engineering support
- Simplified architecture reduces operational complexity
- Faster development velocity from standardized tooling

**Risks we are accepting:**
- Platform Z pricing changes (mitigated by 3-year rate lock)
- Platform Z strategic shifts that deprioritize our use case
- Competitive disadvantage if a superior platform emerges
- Vendor dependency in negotiation leverage

**Safeguards required before proceeding:**
1. Negotiate contractual exit provisions with 12-month transition support
2. Maintain abstraction layer for core business logic (not infrastructure)
3. Annual review of platform dependency risk at board level
4. Document all Platform Z-specific architectural decisions

---

## Example 3: Market Entry Commitment

### Memo: Committing to Regulated Market Entry

**Decision type:** Type 1 — Regulatory commitments, licensing costs, and legal entity creation cannot be easily unwound.

**Recommendation:** Proceed with market entry, phased over 18 months.

**Irreversible elements:**
- Legal entity formation with ongoing compliance obligations
- Regulatory licensing process (9-12 months, $500K+ in fees)
- Hiring commitments to local employees with labor law protections
- Customer commitments that create contractual obligations
- Brand presence that, once established, cannot be quietly withdrawn without reputational cost

**Decision quality checklist:**
- [x] Have we consulted people who will disagree? (Three dissenting views documented)
- [x] Have we identified what would make us regret this? (Pre-mortem completed)
- [x] Have we separated the decision from the decision-maker's ego?
- [x] Have we allowed adequate time for deliberation? (45-day review period)
- [x] Have we identified the minimum viable commitment to test our thesis?

## Type 1 Decision Principles

1. **Slow down deliberately** — Speed is a virtue for Type 2 decisions. For Type 1, patience is the virtue.
2. **Seek dissent actively** — Assign someone to argue the opposing case with full effort.
3. **Write the pre-mortem** — Describe the future in which this decision was wrong. How likely is that future?
4. **Separate the decision from sunk costs** — What would you do if you were starting fresh today?
5. **Identify the minimum commitment** — Can you structure a smaller, reversible test before the full commitment?
6. **Document your reasoning** — Future leaders need to understand why this choice was made and what assumptions it rested on.
