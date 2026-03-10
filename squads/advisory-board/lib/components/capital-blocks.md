# Capital Blocks

## Purpose

Reusable structural blocks for capital allocation decisions, fundraising narratives, and financial analysis at board level. These blocks create a shared language for discussing how money is raised, deployed, and measured so capital decisions receive the same rigor as product or strategy decisions.

## Structure

### Block 1 — Capital Position Snapshot

Establishes the current financial reality.

**Fields:**
- **Cash on hand:** Current balance with date.
- **Monthly burn rate:** Trailing 3-month average and trend direction.
- **Runway:** Months of operation remaining at current burn.
- **Revenue run rate:** Current ARR/MRR and growth rate.
- **Gross margin:** Trailing quarter percentage.
- **Key financial covenants:** Any debt or investor covenants and current compliance status.
- **Upcoming capital needs:** Known large expenditures in the next 6 months.

### Block 2 — Capital Allocation Framework

Defines how capital is distributed across strategic priorities.

**Fields:**
- **Allocation categories:** Core business, growth bets, strategic optionality, reserves.
- **Percentage allocation:** Target distribution across categories.
- **Core business definition:** Activities that sustain current revenue and operations.
- **Growth bet criteria:** What qualifies an initiative for growth-bet funding.
- **Kill threshold per bet:** Maximum investment before a bet must show traction or be killed.
- **Reserve floor:** Minimum cash reserve that is never allocated (typically 3-6 months runway).
- **Rebalancing cadence:** How often allocation is reviewed (monthly recommended for startups).

### Block 3 — Investment Decision Card

Evaluates a specific capital deployment decision.

**Fields:**
- **Investment title:** Name of the initiative requiring capital.
- **Amount requested:** Total investment and disbursement schedule.
- **Expected return:** Revenue, cost savings, or strategic value with timeline.
- **Return calculation method:** NPV, IRR, payback period, or strategic option value (link to `utilities/ev-calculator.md`).
- **Confidence level:** High / Medium / Low with basis for the assessment.
- **Opportunity cost:** What else this capital could fund and why this investment ranks higher.
- **Downside scenario:** Worst-case loss if the investment fails completely.
- **Reversibility:** Can the investment be unwound, and at what cost.
- **Decision criteria:** Specific metrics that determine success or failure within a stated timeframe.

### Block 4 — Fundraising Parameters

Defines the terms and strategy for raising external capital.

**Fields:**
- **Amount to raise:** Target and acceptable range.
- **Instrument type:** Equity, SAFE, convertible note, debt, revenue-based financing.
- **Target valuation / cap:** Desired terms with walkaway floor.
- **Dilution impact:** Pro forma cap table showing post-raise ownership.
- **Use of proceeds:** Specific allocation plan for raised capital (category + percentage).
- **Milestone before next raise:** What the company must achieve before needing more capital.
- **Investor criteria:** What the company values beyond capital (expertise, network, brand, patience).
- **Timeline:** Target close date and key milestones (deck, first meetings, term sheet, close).
- **Walkaway conditions:** Terms or investor behaviors that should kill the deal.

### Block 5 — Unit Economics Dashboard

Tracks the fundamental health of the business model.

**Fields:**
- **CAC (Customer Acquisition Cost):** Current and trailing 6-month trend.
- **LTV (Lifetime Value):** Current and method of calculation.
- **LTV:CAC ratio:** Current with target (typically > 3:1).
- **Payback period:** Months to recover CAC.
- **Gross margin per customer:** Revenue minus direct cost of serving.
- **Expansion revenue rate:** Net dollar retention percentage.
- **Cohort analysis summary:** How recent cohorts compare to earlier ones on retention and spend.

### Block 6 — Capital Review Record

Documents the outcome of a capital allocation review.

**Fields:**
- **Review date:** When the review occurred.
- **Participants:** Who attended.
- **Current allocation vs. plan:** Actual spend by category versus planned allocation.
- **Variance analysis:** Where reality diverged from plan and why.
- **Reallocation decisions:** Any shifts in allocation with rationale.
- **Bets to kill:** Investments that hit their kill threshold.
- **New bets approved:** Investments approved with terms from Block 3.
- **Runway update:** Revised runway projection.
- **Next review date:** When the next capital review is scheduled.

## Usage

1. **Block 1** opens every board meeting financial section and every fundraising conversation.
2. **Block 2** is established annually and reviewed monthly — it is the capital equivalent of a strategic plan.
3. **Block 3** is completed for any capital deployment exceeding 5% of cash reserves.
4. **Block 4** is built when fundraising is being considered, well before the first investor meeting.
5. **Block 5** is updated monthly and reviewed at every board meeting. Deteriorating unit economics are the leading indicator of capital problems.
6. **Block 6** captures the output of monthly or quarterly capital reviews.

## Example

```markdown
# Capital Allocation Review — March 2026

## Position Snapshot
- **Cash:** $4.2M (as of March 1)
- **Monthly burn:** $320K (trending down from $350K)
- **Runway:** 13.1 months
- **ARR:** $3.8M growing 12% QoQ
- **Gross margin:** 74%

## Current Allocation
| Category | Planned % | Actual % | Variance |
|----------|-----------|----------|----------|
| Core business | 55% | 58% | +3% (higher support costs) |
| Growth bets | 25% | 22% | -3% (ML hire delayed) |
| Strategic optionality | 10% | 10% | On track |
| Reserves | 10% | 10% | On track |

## Decisions
1. **Kill:** Content marketing experiment — 4 months, no measurable pipeline impact. Redeploy $15K/mo to product-led growth.
2. **Approve:** $50K for SOC2 certification — payback in 2 enterprise deals (pipeline > $200K ACV).
3. **Fundraise trigger:** If ARR hits $5M by June, begin Series A process targeting $12-15M raise.
```
