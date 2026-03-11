# Vertical Integration Strategy Memos — Swipe File

## Overview
Vertical integration — owning more of the value chain by moving upstream (toward suppliers) or downstream (toward customers) — is a high-stakes strategic bet. When it works, it creates margin expansion, quality control, and competitive moats. When it fails, it creates complexity, capital drain, and distraction from core competencies. These memos provide frameworks for rigorous integration analysis.

## Vertical Integration Memo Template

### Section 1: Integration Thesis
- **Direction:** Upstream (supply side) or downstream (demand side)?
- **What are we integrating?** Specific capability, process, or function
- **Why integrate vs. partner or buy?** What market failure, quality issue, or strategic imperative justifies owning this function?
- **Strategic endgame:** How does this integration strengthen our competitive position over 5+ years?

### Section 2: Current Value Chain Analysis
- **Map the full value chain:** From raw inputs to end customer, where do we currently participate?
- **Identify margin pools:** Where does profit concentrate in the value chain? Who captures it today?
- **Dependency assessment:** How reliant are we on the function we are considering integrating? What is the risk of supplier/partner failure?
- **Competitive landscape:** Are competitors integrating? If so, what are they learning?

### Section 3: Integration Economics
- **Cost to build or acquire:** Capital investment, hiring, technology, and timeline
- **Margin impact:** What margins exist in the target function? What margins do we capture by integrating?
- **Volume requirements:** Do we have sufficient scale to justify the fixed costs of integration?
- **Transition costs:** What is the cost and risk of migrating from external providers during the transition?

### Section 4: Operational Complexity
- **New competencies required:** What skills do we need that we do not have today?
- **Management attention:** How much executive bandwidth does this consume?
- **Organizational impact:** New teams, reporting structures, cultural integration
- **Technology requirements:** Systems, infrastructure, and data integration needed

### Section 5: Risk Analysis
- **Execution risk:** Can we actually operate this function at the required quality level?
- **Capital allocation risk:** Does this investment outperform alternative uses of the same capital?
- **Partner/supplier reaction:** Will existing partners view us as a competitor and withdraw support?
- **Reversibility:** If integration fails, can we return to the external model? At what cost?

## Example: E-commerce Company Building In-House Logistics

**Thesis:** Our third-party logistics provider controls delivery speed, packaging quality, and customer experience for the most critical touchpoint — the unboxing. As we scale, their errors become our brand damage. Integration gives us control over the customer experience end-to-end.

**Economics:** Current 3PL cost: $8.50 per order. Estimated in-house cost at scale: $6.80 per order (20% savings). Requires $4M warehouse buildout and 60 new hires. Breakeven on capital investment: 18 months at current volume.

**Risks:** Logistics is operationally intensive and error-prone during ramp. If we fail, fulfillment speed degrades during the transition — directly impacting customer satisfaction. 3PL contract has 6-month termination notice; we need parallel operations during transition.

**Decision framework:** Pilot with one region (30% of volume) for 6 months. Measure: cost per order, delivery speed, error rate, customer satisfaction. If pilot meets targets, expand. If not, extend 3PL contract and apply learnings.

## Example: SaaS Company Building Data Infrastructure Layer

**Thesis:** Our analytics product depends on customer data pipelines built by third-party ETL tools. When those tools fail, our product fails. Customers blame us, not the ETL provider. By building a lightweight data ingestion layer, we control reliability and reduce integration friction.

**Economics:** Current state: 40% of support tickets relate to data pipeline issues. Estimated engineering investment: 3 engineers for 9 months. Expected support ticket reduction: 60%. Customer satisfaction impact: NPS increase of 8-12 points.

**Risks:** We become responsible for data infrastructure reliability. If our ingestion layer has bugs, we can no longer point to the third-party tool. We may also alienate ETL partners who refer customers to us.

**Decision:** Build a thin ingestion layer for the top 5 data sources (covering 80% of customers). Maintain third-party integrations as fallback. Do not attempt to replace the full ETL ecosystem.

## Vertical Integration Decision Matrix

| Factor | Integrate | Partner | Buy (Acquire) |
|--------|-----------|---------|---------------|
| Strategic criticality | Core to differentiation | Important but not core | Core, but time-to-market matters |
| Internal capability | Strong related competency | Weak, would need to build | Can be acquired with the team |
| Capital availability | Sufficient for multi-year build | Limited, need capital efficiency | Sufficient for acquisition |
| Time pressure | Can wait 12-18 months | Need it now | Need it in 3-6 months |
| Reversibility | Willing to commit long-term | Want flexibility | Moderate commitment |
| Scale requirements | Sufficient volume to justify | Insufficient volume alone | Volume comes with acquisition |

## Integration Anti-Patterns

| Anti-Pattern | Why It Fails |
|-------------|-------------|
| Integrating because a competitor did | Mimicry is not strategy; your value chain position may differ |
| Integrating commoditized functions | Owning commodity inputs does not create differentiation |
| Underestimating operational complexity | Every integration adds management layers and failure modes |
| Burning partner bridges prematurely | Announce integration plans only after you can execute independently |
| No pilot phase | Full-scale integration without validation is an irreversible bet |

## Board Application
- Vertical integration decisions are Type 1 (irreversible) decisions — require full board deliberation
- Challenge the "make" assumption: is the real problem supplier quality, and can it be solved with better contracts or alternative suppliers?
- Require a pilot plan before approving full integration — demand evidence before commitment
- Monitor management attention: integration projects consume disproportionate executive bandwidth
- Ask: "What are we not doing because we are doing this?" The opportunity cost of integration is often underestimated

## Cross-References
- See `checklists/innovation/build-vs-buy-vs-partner.md` for the build/buy/partner decision framework
- See `swipe/partnership-deals/strategic-partnership-examples.md` for partnership alternatives
- See `checklists/capital-allocation-quality.md` for capital allocation evaluation
