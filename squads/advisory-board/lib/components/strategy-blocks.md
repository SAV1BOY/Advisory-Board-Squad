# Strategy Blocks

## Purpose

Reusable structural blocks for composing strategy documents at board level. These blocks enforce rigorous strategic thinking by separating diagnosis from choices, choices from execution, and execution from measurement. They prevent the common failure mode of jumping from aspiration to action without confronting tradeoffs.

## Structure

### Block 1 — Strategic Context

Grounds the strategy in observable reality rather than aspiration.

**Fields:**
- **Current position:** Where the company stands today — market share, capabilities, financial position, competitive standing.
- **Key trends:** 3-5 external forces shaping the environment (technology shifts, regulatory changes, customer behavior evolution, competitor moves).
- **Strategic question:** The single most important question the strategy must answer, framed as a choice (e.g., "Should we pursue enterprise or SMB as our primary segment?").
- **Time frame:** The planning horizon (typically 12-36 months for startups, 3-5 years for mature companies).
- **Constraints:** Non-negotiable boundaries — capital limits, regulatory requirements, mission commitments.

### Block 2 — Diagnosis

Identifies the critical challenge or opportunity. A strategy without diagnosis is just a wish list.

**Fields:**
- **Core challenge:** One paragraph describing the fundamental problem or opportunity.
- **Root causes:** Numbered list of underlying factors driving the challenge.
- **Evidence base:** Data points, customer signals, market research that support the diagnosis.
- **What we got wrong before:** Previous strategic assumptions that proved incorrect.
- **Competing diagnoses:** Alternative interpretations of the same evidence and why they were rejected.

### Block 3 — Strategic Choices

Defines the set of choices and explicitly names what is being traded away.

**Fields:**
- **Guiding policy:** One sentence that describes the overall approach (e.g., "Win through product-led growth in mid-market").
- **Where to play:** Markets, segments, geographies, or verticals where the company will compete.
- **How to win:** The specific advantage or approach that will produce victory in the chosen arena.
- **What we will NOT do:** Explicit list of attractive options being rejected. This is the hardest and most valuable part.
- **Sequencing:** In what order will strategic moves be executed and why.

### Block 4 — Resource Allocation

Translates choices into resource commitments — strategy is revealed by budgets, not slide decks.

**Fields:**
- **People allocation:** Headcount and talent deployment by strategic priority.
- **Capital allocation:** Budget distribution across initiatives, with kill thresholds.
- **Time allocation:** Leadership attention distribution across strategic bets.
- **Reallocation from:** What current activities lose resources to fund the strategy.
- **Investment thesis per bet:** For each major allocation, the expected return and timeline.

### Block 5 — Coherent Action Set

Bridges strategy to execution with a set of reinforcing actions.

**Fields:**
- **Initiatives:** 3-7 major initiatives that implement the strategy (fewer is better).
- **Initiative interdependencies:** How initiatives reinforce or depend on each other.
- **Milestone map:** Key milestones per initiative with dates and owners.
- **First 90-day sprint:** The immediate actions that create momentum and test assumptions.
- **Decision points:** Pre-scheduled moments where the strategy will be evaluated and potentially adjusted.

### Block 6 — Strategic Risk & Assumptions

Makes the bets explicit so they can be monitored.

**Fields:**
- **Critical assumptions:** What must be true for this strategy to work (list each explicitly).
- **Assumption testing plan:** How and when each assumption will be validated.
- **Key risks:** Top 5 strategic risks using `lib/components/risk-blocks.md`.
- **Hedging moves:** Actions that reduce exposure without abandoning the strategy.
- **Pivot triggers:** Specific signals that should cause a strategic reassessment.

## Usage

1. **Block 1 + Block 2** always come first and must be completed before strategy formulation begins.
2. **Block 3** is the core deliverable — a strategy document without explicit choices and tradeoffs is not a strategy.
3. **Block 4** is the integrity check — if resource allocation does not match stated choices, the strategy is aspirational fiction.
4. **Block 5** creates accountability — every initiative needs a single owner and measurable milestones.
5. **Block 6** creates adaptability — strategies that cannot be falsified cannot be improved.

## Example

```markdown
# Product Strategy 2026-2027

## Strategic Context
- **Position:** $12M ARR, 340 customers, 18-month runway, #3 in market
- **Key trends:** AI automation reshaping workflow tools; enterprise buyers consolidating vendors; SMB churn rising industry-wide
- **Strategic question:** Do we move upmarket to enterprise or deepen SMB penetration?
- **Time frame:** 18 months
- **Constraints:** Cannot raise before $20M ARR; must maintain >70% gross margin

## Diagnosis
- **Core challenge:** SMB growth is decelerating because our product has outgrown the SMB price ceiling but lacks the security, compliance, and integration features enterprise demands.
- **Root causes:** (1) Product complexity grew faster than SMB willingness to pay (2) No SOC2 or SSO, blocking enterprise deals (3) Sales team is SMB-trained
- **Evidence:** SMB close rates dropped 15% YoY; 47 enterprise prospects stalled on security requirements

## Strategic Choices
- **Guiding policy:** Move upmarket to mid-market enterprise (100-2000 employees) through product-led growth with sales assist
- **Where to play:** North American mid-market, financial services and healthcare verticals first
- **How to win:** Fastest time-to-value through self-serve onboarding with enterprise-grade security
- **What we will NOT do:** Custom enterprise deals > $500K ACV; geographic expansion; SMB feature requests that do not serve mid-market; building our own AI model
- **Sequencing:** Security/compliance first (Q1-Q2), then integrations (Q3), then vertical features (Q4)
```
