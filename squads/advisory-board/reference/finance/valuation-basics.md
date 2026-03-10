# Valuation Basics

## Valuation Methods

### Discounted Cash Flow (DCF)
- **What:** Project future free cash flows and discount them to present value using a discount rate
- **When to use:** Companies with predictable cash flows, mature businesses, capital allocation decisions
- **Strengths:** Theoretically sound, focuses on intrinsic value, forces explicit assumptions
- **Weaknesses:** Highly sensitive to terminal value assumptions and discount rate; garbage in, garbage out
- **Key variables:** Revenue growth rate, operating margins, capital requirements, discount rate (WACC), terminal growth rate

### Comparable Company Analysis (Comps)
- **What:** Value a company based on how similar public companies are valued (EV/Revenue, EV/EBITDA, P/E)
- **When to use:** When comparable public companies exist, quick sanity checks
- **Strengths:** Market-based, reflects current investor sentiment, widely understood
- **Weaknesses:** "Comparable" is subjective, reflects market mood (may be irrationally high or low)
- **SaaS multiples:** Typically EV/ARR. Range: 5-15x for growth SaaS (varies dramatically with growth rate and NRR)

### Comparable Transaction Analysis (Precedent Transactions)
- **What:** Value based on what acquirers paid for similar companies in recent M&A deals
- **When to use:** Evaluating M&A offers, setting acquisition price expectations
- **Strengths:** Reflects actual prices paid, includes control premium
- **Weaknesses:** Deal terms vary, strategic premiums distort comparability, data may be stale

### Venture Capital Method
- **What:** Estimate exit value, apply target return multiple, work backward to current valuation
- **When to use:** Early-stage companies with limited financial history
- **Formula:** Post-money valuation = Expected exit value / Target return multiple
- **Example:** Expected exit at $200M in 5 years, investor targets 10x return → Post-money valuation today = $20M

## Key Valuation Concepts

### Enterprise Value vs. Equity Value
- **Enterprise Value (EV)** = Equity value + Debt - Cash. Represents the total value of the business.
- **Equity Value** = EV - Debt + Cash. Represents what shareholders own.
- **Why it matters:** When comparing companies, use EV-based multiples (EV/Revenue, EV/EBITDA) to normalize for capital structure differences.

### Revenue Multiples by Growth Rate
| ARR Growth | Typical EV/ARR Multiple |
|-----------|----------------------|
| > 100% | 15-30x |
| 50-100% | 8-15x |
| 30-50% | 5-10x |
| 10-30% | 3-7x |
| < 10% | 1-4x |
*Note: multiples vary dramatically by market conditions, NRR, and profitability*

### The Rule of 40
- **Formula:** Revenue growth rate (%) + Profit margin (%) should exceed 40%
- A company growing 60% with -20% margins = 40 (good)
- A company growing 20% with 20% margins = 40 (good)
- A company growing 30% with -5% margins = 25 (below benchmark)

## Board Application
- Never rely on a single valuation method; triangulate with at least two
- Challenge the assumptions in any DCF presented (especially terminal value and discount rate)
- Use the Rule of 40 as a quick health check for growth-stage companies
- In fundraising, understand that valuation is a negotiation, not a calculation
- In M&A, ensure the board independently validates management's valuation of targets
