# Innovation Portfolio Pattern

## Pattern Name

Innovation Portfolio — a structured approach to managing a portfolio of innovation bets across multiple time horizons, ensuring the company balances near-term improvements with long-term growth investments while maintaining the discipline to kill failing initiatives and double down on winners.

## When to Use

- The company has more innovation ideas than resources to pursue them and needs a principled allocation framework.
- The board wants visibility into whether the company is investing in future growth or only optimizing the current business.
- Leadership is struggling with the tension between "focus" (do fewer things) and "optionality" (explore many things).
- The company is approaching a growth plateau and needs to identify the next S-curve.
- Post-pivot or post-acquisition, when the innovation portfolio needs rebalancing.

Do NOT use when:
- The company has not yet achieved product-market fit — focus all resources on finding PMF before diversifying.
- The company is in cash crisis — innovation portfolio management is a growth-stage activity, not a survival-stage activity.

## Structure

```
1. INVENTORY  → Catalog all innovation initiatives across the company
2. CLASSIFY   → Assign each initiative to a horizon (H1, H2, H3)
3. ALLOCATE   → Set target resource allocation by horizon
4. GATE       → Define stage gates and advancement criteria
5. REVIEW     → Quarterly portfolio review with kill/continue/accelerate decisions
6. REBALANCE  → Adjust allocation based on results and strategic shifts
```

## Steps

### Step 1: Inventory All Innovation Activity

- Catalog every initiative that is not maintenance, bug fixing, or operational work. Include:
  - Formal projects with dedicated resources
  - Skunkworks or side projects consuming engineer time
  - Customer-requested features that represent new capability development
  - R&D explorations without clear product targets
- For each initiative: name, owner, resources consumed (people x weeks), current stage, and evidence of value.
- This step often reveals that the company is already spreading innovation resources across 3-5x more initiatives than leadership realizes.

### Step 2: Classify by Horizon

- **H1 — Core (0-12 months):** Improvements to existing products for existing customers. Lower risk, predictable returns. Examples: performance optimization, feature completions, UX improvements.
- **H2 — Adjacent (12-24 months):** Extensions into adjacent markets, customer segments, or capabilities using existing strengths. Moderate risk, less predictable returns. Examples: new product lines for existing customers, existing products for new segments.
- **H3 — Transformational (24-36 months):** Bets on fundamentally new capabilities, business models, or markets. High risk, potentially transformational returns. Examples: new technology platforms, new business models, entering new industries.
- Classify honestly. Most companies want to label H1 work as H2 to feel innovative. The test: if it fails, does the core business continue unaffected? If yes, it might be H2 or H3. If failure would damage core revenue, it is H1.

### Step 3: Set Target Resource Allocation

Recommended starting allocation (adjust by company stage and strategy):

| Company Stage | H1 (Core) | H2 (Adjacent) | H3 (Transformational) |
|--------------|-----------|----------------|----------------------|
| Post-PMF, pre-scale | 70% | 20% | 10% |
| Growth stage | 55% | 30% | 15% |
| Mature/at scale | 50% | 30% | 20% |
| Facing disruption | 40% | 30% | 30% |

- Resources = engineering time + product management time + budget. Measure all three.
- The most common failure: H3 allocation drops to 0% under short-term pressure. Protect H3 allocation like a strategic reserve.

### Step 4: Define Stage Gates

Each initiative progresses through gates. Advancement requires evidence, not enthusiasm:

| Gate | From → To | Advancement Criteria |
|------|-----------|---------------------|
| Gate 0 | Idea → Hypothesis | Thesis documented with kill criteria (Block 1 from innovation-blocks.md) |
| Gate 1 | Hypothesis → Experiment | Experiment designed with clear success metric (Block 2) |
| Gate 2 | Experiment → Build | Experiment produced positive signal meeting pre-defined threshold |
| Gate 3 | Build → Scale | MVP shipped, early adopter metrics meet targets |
| Gate 4 | Scale → Core | Revenue contribution meets investment case projections |

- Gate reviews happen monthly for H1, quarterly for H2 and H3.
- At each gate: advance, pivot, or kill. "Continue as-is" is not a valid gate decision — it is a decision to avoid deciding.

### Step 5: Quarterly Portfolio Review

The board should review the innovation portfolio quarterly using Block 3 from innovation-blocks.md:
- Pipeline fullness by stage and horizon
- Initiatives advanced, killed, or stalled since last review
- Resource allocation actuals vs. targets
- Top 3 bets with evidence summaries
- Graveyard with lessons learned

Key questions for the board to ask:
- "What did we kill this quarter, and what did we learn from it?"
- "Is our H3 allocation being protected or raided for short-term priorities?"
- "What is the strongest signal from our experiments, and are we resourcing it adequately?"

### Step 6: Rebalance

- After each quarterly review, adjust resource allocation if:
  - An H2 or H3 initiative has strong enough evidence to warrant acceleration (shift resources toward it)
  - A horizon is depleted (all initiatives killed or advanced) and needs refilling
  - Strategic context has changed (new competitive threat, market shift, regulatory change)
- Rebalancing is not failure — it is disciplined response to new information.

## Anti-Patterns

| Anti-Pattern | Description | Consequence |
|-------------|-------------|-------------|
| Peanut butter spreading | Distributing resources thinly across too many initiatives | Nothing gets enough investment to reach validation |
| H3 raiding | Pulling H3 resources to meet H1 deadlines | No future growth engine; eventual revenue plateau |
| Zombie projects | Initiatives that neither advance nor get killed | Resource drain and opportunity cost |
| Innovation theater | Visible innovation activities that produce no validated learning | False confidence in future growth pipeline |
| Gate avoidance | Skipping stage gates because "we already know this will work" | Overinvestment in unvalidated hypotheses |

## Examples

### Example: Growth-Stage SaaS Company Portfolio

**Context:** $15M ARR SaaS company, 120 employees, Series B, 18-month runway.

**Current state (before rebalancing):**
- 22 active initiatives: 18 H1, 4 H2, 0 H3
- 92% of engineering on H1, 8% on H2, 0% on H3
- Diagnosis: Innovation pipeline is critically unbalanced; no investment in future growth

**Rebalanced portfolio:**
- Target: 12 initiatives: 7 H1, 3 H2, 2 H3
- Allocation: 60% H1, 25% H2, 15% H3
- Actions: Kill 10 low-impact H1 initiatives; fund 2 H3 explorations (AI integration, new vertical)
- Gate review cadence: Monthly for H1, quarterly for H2/H3

## Related Patterns

- `lib/components/innovation-blocks.md` — structural blocks for innovation documents
- `lib/patterns/kill-decision-pattern.md` — process for terminating initiatives at gates
- `lib/patterns/pivot-pattern.md` — when portfolio evidence suggests strategic redirection
- `data/metrics/innovation-pipeline-score.md` — metric tracking portfolio health
- `data/research/ai-disruption-landscape.md` — external context for H3 investment decisions
