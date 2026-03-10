# Moat Strength Rubric

## Purpose

A scoring rubric for evaluating the durability and strength of a company's competitive advantages (moats). Moats determine long-term value creation — a business without a moat is a commodity. This rubric assesses whether competitive advantages are real, growing, or eroding, and feeds strategic planning on moat investment and defense.

## How to Use

Assess each potential moat the company possesses using the dimensions below. Conduct a full moat assessment annually during strategic planning and a light-touch review quarterly. Cross-reference moat types with `lib/taxonomies/moat-types.md`. Feed results into `data/registries/moat-registry.yaml`.

## Scale/Criteria

### Dimension 1: Strength (Weight: 30%)
How difficult is it for a competitor to replicate or neutralize this advantage?

| Score | Description |
|-------|-------------|
| 5 | Extremely difficult to replicate. Would require years and hundreds of millions of dollars. Protected by network effects, regulation, or proprietary data that compounds over time. |
| 4 | Very difficult. Requires significant time and capital. Meaningful structural barriers exist. |
| 3 | Moderately difficult. A well-funded competitor could replicate in 12-18 months with focused effort. |
| 2 | Somewhat difficult. Multiple competitors are actively eroding this advantage. Replicable within 6-12 months. |
| 1 | Not a real moat. Any competent competitor can match this advantage quickly. Provides no durable differentiation. |

### Dimension 2: Width (Weight: 20%)
How much of the business does this moat protect?

| Score | Description |
|-------|-------------|
| 5 | Protects the entire business and all revenue streams. The moat is the business. |
| 4 | Protects the core business and most revenue. Some peripheral areas are exposed. |
| 3 | Protects the primary product or segment but not adjacent offerings. |
| 2 | Protects a narrow niche or specific customer segment. Most of the business is unprotected. |
| 1 | Minimal coverage. The moat applies to an edge case, not the core business. |

### Dimension 3: Trend (Weight: 25%)
Is the moat getting stronger or weaker over time?

| Score | Description |
|-------|-------------|
| 5 | Actively compounding. Each new customer, data point, or interaction makes the moat stronger. Positive feedback loop is operating. |
| 4 | Growing steadily. Investments are widening the advantage. Competitors are falling further behind. |
| 3 | Stable. The moat is maintained but not growing. Requires ongoing investment to sustain. |
| 2 | Eroding. Competitors are closing the gap. Technology shifts or market changes are weakening the advantage. |
| 1 | Collapsing. The moat is being disrupted. The advantage will be neutralized within 12-24 months without dramatic intervention. |

### Dimension 4: Measurability (Weight: 10%)
Can the moat's strength be quantified and tracked?

| Score | Description |
|-------|-------------|
| 5 | Clear, quantifiable metrics exist and are tracked regularly (switching costs in dollars, network density, data volume, cost advantage percentage). |
| 4 | Most aspects of the moat are measurable. Key metrics are defined and tracked. |
| 3 | Some metrics exist but the moat is partially assessed through qualitative judgment. |
| 2 | The moat is mostly assessed through intuition and anecdote. Few hard metrics. |
| 1 | No measurement exists. The moat is asserted but not verified. |

### Dimension 5: Investability (Weight: 15%)
Can the company deliberately invest to strengthen this moat?

| Score | Description |
|-------|-------------|
| 5 | Clear investment thesis: specific actions with measurable moat-strengthening outcomes. Capital deployed here compounds the advantage. |
| 4 | Good investment options available. Returns on moat investment are predictable. |
| 3 | Some investment options but the relationship between investment and moat strength is indirect. |
| 2 | Limited ability to invest in moat strengthening. The moat is more accidental than designed. |
| 1 | No investable path to strengthen this moat. It is a circumstantial advantage only. |

## Scoring Guide

### Calculating the Overall Moat Score
**Overall = (Strength x 0.30) + (Width x 0.20) + (Trend x 0.25) + (Measurability x 0.10) + (Investability x 0.15)**

### Interpretation
| Score Range | Rating | Strategic Implication |
|-------------|--------|----------------------|
| 4.5 - 5.0 | Fortress | This moat is a core strategic asset. Invest aggressively to compound it. Build strategy around it. |
| 3.5 - 4.4 | Strong | Genuine competitive advantage. Invest to maintain and grow. Monitor for erosion. |
| 2.5 - 3.4 | Moderate | Provides some protection but vulnerable. Needs deliberate investment or supplementation with additional moats. |
| 1.5 - 2.4 | Weak | Provides minimal durable advantage. Consider whether investment to strengthen is worthwhile or if resources should go elsewhere. |
| 1.0 - 1.4 | Absent | Not a real moat. Do not make strategic decisions based on this advantage — it will not hold. |

### Portfolio View
Most durable businesses have 2-3 reinforcing moats. Assess all moats and look for:
- **Reinforcing moats:** Moats that strengthen each other (e.g., brand + network effects + data).
- **Single-moat risk:** Dependence on one advantage creates fragility.
- **Moat gaps:** Areas where the business has no protection and competitors can attack.

### Assessment Template
```
Company: [Name] | Assessment Date: [Date]

| Moat | Type | Strength | Width | Trend | Measurability | Investability | Overall |
|------|------|----------|-------|-------|---------------|---------------|---------|
| [Moat 1] | [Type] | [1-5] | [1-5] | [1-5] | [1-5] | [1-5] | [X.X] |
| [Moat 2] | [Type] | [1-5] | [1-5] | [1-5] | [1-5] | [1-5] | [X.X] |

Portfolio assessment: [Reinforcing / Fragile / Gap-heavy]
Top investment priority: [Which moat to invest in and why]
Top risk: [Which moat is eroding and what to do]
```
