# Innovation Blocks

## Purpose

Reusable structural blocks for composing innovation review documents — portfolio reviews, experiment proposals, innovation pipeline assessments, and R&D investment cases. These blocks enforce disciplined innovation by separating ideas from experiments, experiments from investments, and investments from outcomes. They prevent the two most common innovation failures: (1) death by committee, where promising ideas are analyzed into oblivion, and (2) undisciplined experimentation, where resources scatter across too many unvalidated initiatives.

## Structure

### Block 1 — Innovation Thesis

Frames the strategic rationale for an innovation initiative.

**Fields:**
- **Strategic question:** What strategic problem or opportunity does this innovation address?
- **Hypothesis:** One sentence stating the core belief being tested (format: "We believe that [action] will result in [outcome] because [reasoning]").
- **Horizon classification:** H1 (core, 0-12 months), H2 (adjacent, 12-24 months), or H3 (transformational, 24-36 months).
- **Evidence basis:** What existing data, customer signals, or market trends support this hypothesis?
- **Assumption inventory:** List the 3-5 critical assumptions that must be true for this thesis to hold. Each assumption should be independently testable.
- **Kill criteria:** Pre-defined conditions under which this initiative should be abandoned. Set these before emotional investment accumulates.

### Block 2 — Experiment Design

Structures the validation approach for an innovation hypothesis.

**Fields:**
- **Experiment type:** Prototype, concierge MVP, landing page test, customer co-development, A/B test, wizard of Oz, or other.
- **Success metric:** The single metric that determines whether the experiment succeeded (be specific: "20% of users complete onboarding in <5 minutes" not "good engagement").
- **Sample size and duration:** Minimum sample for statistical or directional confidence, and maximum time allowed.
- **Resource requirement:** People, budget, and calendar time needed. Experiments that require more than 2 people or 4 weeks are too large — decompose them.
- **Learning objective:** What will we know after this experiment that we do not know now, regardless of outcome?
- **Decision framework:** If result is positive → [next step]. If result is negative → [next step]. If result is ambiguous → [next step].

### Block 3 — Innovation Portfolio View

Structures the board-level view of the full innovation portfolio.

**Fields:**
- **Pipeline summary:** Count of initiatives by stage (idea → experiment → build → scale → mature) and horizon (H1, H2, H3).
- **Stage gate progression:** Initiatives that advanced, stalled, or were killed this quarter, with rationale for each.
- **Resource allocation:** Percentage of engineering, product, and budget allocated to innovation vs. maintenance vs. operations.
- **Portfolio balance assessment:** Current allocation across horizons vs. target allocation. Flag any horizon at 0%.
- **Top 3 bets:** For each of the three highest-conviction initiatives, provide: hypothesis, evidence strength, resource invested, next milestone.
- **Graveyard:** Initiatives killed this quarter with one-line lessons learned. Celebrating kills prevents sunk cost bias.

### Block 4 — Innovation Investment Case

Structures the decision to move from experiment to full investment.

**Fields:**
- **Experiment results:** Summary of validation evidence — what was tested, what was learned, confidence level.
- **Market sizing:** Bottoms-up market size estimate for the validated opportunity.
- **Resource request:** People, budget, and timeline for the build phase.
- **Revenue model:** How this innovation will generate or protect revenue, and the expected timeline to revenue contribution.
- **Cannibalization risk:** Does this innovation compete with existing products or revenue streams? If yes, quantify the tradeoff.
- **Competitive window:** How long before competitors can replicate this innovation? What is our defensibility?
- **Reversibility:** Can this investment be unwound if results disappoint, or is it a one-way door? Reference `lib/patterns/reversible-decision-pattern.md`.

### Block 5 — Innovation Outcome Review

Structures the retrospective on completed innovation initiatives.

**Fields:**
- **Original hypothesis:** What did we set out to prove or build?
- **Outcome:** What actually happened — quantified against the original success metrics.
- **Variance analysis:** Where and why did reality diverge from the hypothesis?
- **Lessons learned:** 3-5 transferable insights for future innovation efforts.
- **Process improvements:** What should change in how we run innovation (speed, rigor, resource allocation)?
- **Follow-on opportunities:** What new hypotheses emerged from this initiative?

## Usage

1. **Block 1** is the entry gate — no initiative enters the pipeline without a documented thesis with kill criteria.
2. **Block 2** is used for every experiment — even small ones. The discipline is in the structure, not the length.
3. **Block 3** is the quarterly board reporting format for innovation. It should occupy 10-15 minutes of board meeting time.
4. **Block 4** is the decision gate between experiment and investment — this is where the board provides strategic input.
5. **Block 5** closes the loop — without retrospectives, the innovation process cannot improve.

## Components

- References `lib/patterns/innovation-portfolio-pattern.md` for portfolio management approach
- References `lib/patterns/kill-decision-pattern.md` for initiative termination process
- References `lib/patterns/reversible-decision-pattern.md` for investment reversibility assessment
- References `lib/components/risk-blocks.md` for risk assessment of innovation bets

## Related Patterns

- `lib/patterns/pre-mortem-pattern.md` — use before committing to major innovation investments
- `lib/patterns/pivot-pattern.md` — when innovation evidence suggests a strategic direction change
- `data/metrics/innovation-pipeline-score.md` — the metric that tracks innovation pipeline health
- `data/research/ai-disruption-landscape.md` — external innovation context for portfolio decisions
