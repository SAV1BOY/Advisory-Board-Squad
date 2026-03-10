# Partnership Blocks

## Purpose

Reusable structural blocks for evaluating, structuring, and governing strategic partnerships at board level. Partnerships are among the most over-initiated and under-managed activities in business. These blocks enforce discipline from evaluation through governance so partnerships create value rather than consume executive attention without return.

## Structure

### Block 1 — Partnership Opportunity Assessment

Evaluates whether a partnership is worth pursuing before any negotiation begins.

**Fields:**
- **Partner name:** Organization being evaluated.
- **Partnership type:** Distribution, technology integration, co-development, go-to-market, supply chain, strategic investment, joint venture.
- **Strategic rationale:** Why this partnership matters — what capability, market, or asset gap does it fill.
- **Alternative paths:** Could we build this ourselves, acquire it, or find a different partner? Why is partnership the best path.
- **Value creation thesis:** Specific, measurable value expected from the partnership for each side.
- **Value capture risk:** Risk that value flows disproportionately to one partner.
- **Cultural compatibility:** Assessment of working style, decision speed, and values alignment (use `culture-blocks.md` Block 6).
- **Dependency risk:** How dependent will we become on this partner, and what is the exit cost.
- **Opportunity cost:** What we cannot do while investing in this partnership.
- **Preliminary score:** Go / Explore Further / Pass.

### Block 2 — Due Diligence Checklist

Structured investigation before committing.

**Fields:**
- **Financial health:** Partner's financial stability and runway.
- **Reputation check:** Market perception, customer references, Glassdoor, press coverage.
- **Technical capability:** Can they actually deliver what they promise. Evidence beyond demos.
- **Legal and compliance:** Regulatory standing, pending litigation, IP ownership clarity.
- **Key-person risk:** Is the partnership dependent on a specific champion who could leave.
- **Reference checks:** Conversations with their other partners about the working relationship.
- **Competitive conflict:** Does the partner work with our competitors, and how is that managed.
- **Governance track record:** How have their previous partnerships been managed and what happened when things went wrong.

### Block 3 — Terms and Structure

Defines the deal architecture.

**Fields:**
- **Scope definition:** Precisely what each party will do and deliver, with timelines.
- **Economic model:** Revenue share, licensing fees, cost sharing, or other financial arrangement.
- **Exclusivity terms:** Any exclusivity granted and its geographic, temporal, and segment boundaries.
- **IP ownership:** Who owns what is created during the partnership.
- **Data sharing:** What data is shared, how it is used, and who owns it.
- **Performance commitments:** Minimum thresholds each party must meet (SLAs, volume commitments, quality standards).
- **Governance structure:** Joint steering committee composition, meeting cadence, escalation path.
- **Term and renewal:** Duration, renewal mechanism, and notice periods.
- **Exit clauses:** How either party can exit, transition period, and wind-down obligations.
- **Dispute resolution:** Mediation, arbitration, or litigation path with jurisdiction.

### Block 4 — Integration and Launch Plan

Manages the operational reality of making the partnership work.

**Fields:**
- **Integration workstreams:** Technical, commercial, operational, and communication streams with owners.
- **Milestone map:** Key milestones from signing to first value delivery.
- **Resource allocation:** People, budget, and systems dedicated to the partnership.
- **Communication plan:** How the partnership is announced internally, to customers, and to the market.
- **Quick win target:** First tangible result to build momentum and credibility (ideally within 30-60 days).
- **Risk register:** Top 5 integration risks with mitigation plans (use `risk-blocks.md`).

### Block 5 — Ongoing Governance

Structures the management of the partnership after launch.

**Fields:**
- **Governance cadence:** Meeting schedule (operational weekly, strategic monthly, executive quarterly).
- **KPI dashboard:** 5-7 metrics that measure partnership health and value delivery.
- **Escalation protocol:** How issues move from operational to strategic to executive level.
- **Annual review:** Structured assessment of partnership ROI, strategic relevance, and renewal decision.
- **Relationship health check:** Qualitative assessment of trust, communication quality, and alignment.
- **Evolution triggers:** Signals that the partnership should expand, contract, or restructure.
- **Sunset criteria:** Conditions under which the partnership should be terminated.

### Block 6 — Partnership Postmortem

Captures lessons from completed or terminated partnerships.

**Fields:**
- **Partnership duration:** Start date to end date.
- **Original value thesis:** What was expected.
- **Actual value delivered:** What was realized, quantified.
- **Value gap analysis:** Why actual differed from expected.
- **What worked well:** Practices and structures that should be replicated.
- **What failed:** Problems and their root causes.
- **Relationship dynamics:** How the interpersonal and organizational dynamics affected outcomes.
- **Lessons for future partnerships:** Specific, actionable learnings (link to `data/registries/lessons-learned-registry.yaml`).
- **Would we partner with them again:** Yes / No / Conditionally, with reasoning.

## Usage

1. **Block 1** is completed before any meeting with a potential partner. Most partnerships should be killed at this stage.
2. **Block 2** is completed before term sheet discussion. Never negotiate terms before due diligence.
3. **Block 3** requires legal review. Template terms should exist but be adapted per partnership.
4. **Block 4** is built before signing and activated on day one. The number-one partnership failure mode is great signing, poor integration.
5. **Block 5** runs for the life of the partnership. Unmanaged partnerships decay.
6. **Block 6** is completed within 30 days of partnership conclusion.

## Example

```markdown
# Partnership Assessment: CloudScale Integration

## Opportunity Assessment
- **Type:** Technology integration — embed CloudScale's analytics into our platform
- **Strategic rationale:** Customers requesting analytics; 18 months to build vs. 3 months to integrate
- **Alternative paths:** Build (18 mo, $1.2M) / Acquire AnalyticsCo ($8M) / Partner with CloudScale (3 mo, $0)
- **Value thesis:** Access to analytics increases ACV by 20% and reduces churn by 8%
- **Dependency risk:** Medium — CloudScale API is the only integration point; we retain our data
- **Score:** Explore Further

## Terms Summary
- **Economic model:** Revenue share — 15% of analytics add-on revenue to CloudScale
- **Exclusivity:** Non-exclusive both ways
- **IP:** Each party retains pre-existing IP; integration layer jointly owned
- **Term:** 2 years with annual renewal
- **Exit:** 90-day notice, 6-month transition period for customer migration

## Governance KPIs
| Metric | Target | Current |
|--------|--------|---------|
| Integration uptime | 99.9% | 99.7% |
| Customer adoption rate | 40% | 28% |
| Revenue from analytics add-on | $50K MRR | $32K MRR |
| Support ticket volume (integration) | < 20/month | 35/month |
| NPS on analytics feature | > 40 | 38 |
```
