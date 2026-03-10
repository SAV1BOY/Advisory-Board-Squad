# Reversible Decision Pattern

## Pattern Name

Reversible Decision — lightweight process for two-way door decisions that prioritizes speed over certainty.

## When to Use

- The decision can be undone or significantly altered without catastrophic cost.
- The cost of gathering more information exceeds the cost of being wrong and correcting.
- Speed of learning matters more than precision of planning.
- The decision affects a bounded scope (one team, one feature, one quarter).
- Analysis paralysis is the greater risk than making the wrong call.

Do NOT use when:
- The decision involves people (firing, major re-orgs) — these are never truly reversible.
- Legal or regulatory commitments make reversal impossible or extremely expensive.
- The decision creates path dependency that constrains future options (e.g., choosing a core technology stack).
- Stakeholder trust would be damaged by a reversal (e.g., announcing a product then killing it).

## Structure

```
1. CLASSIFY  → Confirm the decision is genuinely reversible
2. BOUND     → Define the experiment scope, cost, and duration
3. DECIDE    → Make the call with available information (70% threshold)
4. EXECUTE   → Move fast with built-in measurement
5. EVALUATE  → Check results against pre-set criteria
6. ADJUST    → Continue, modify, or reverse
```

## Steps

### Step 1: Classify Reversibility
- Answer three questions:
  1. **Can we undo this?** What does reversal look like operationally?
  2. **What does reversal cost?** Time, money, reputation, opportunity.
  3. **What is the blast radius of reversal?** Who is affected if we change course?
- If reversal cost is less than 10% of the total investment and blast radius is contained to one team or one customer segment, classify as reversible.
- Document the classification briefly — one paragraph, not a memo.

### Step 2: Bound the Experiment
- **Time box:** Set a maximum duration before evaluation (typically 2-6 weeks).
- **Cost cap:** Set a maximum investment before the decision is reviewed.
- **Success criteria:** Define 2-3 observable metrics that would validate the decision.
- **Kill criteria:** Define 1-2 signals that should trigger immediate reversal, even before the time box expires.
- **Minimum viable scope:** Identify the smallest version of the decision that still produces useful signal.

### Step 3: Decide with Available Information
- Apply the 70% rule: if you have 70% of the information you wish you had, decide now.
- The decision-maker should be the person closest to the work, not the most senior person.
- Decision does not require a meeting. An async message with context, decision, and rationale is sufficient.
- Document: who decided, what they decided, and the two-sentence rationale.

### Step 4: Execute with Measurement
- Begin execution within 24-48 hours of the decision.
- Instrument measurement from day one — do not plan to "add metrics later."
- Communicate the experiment to affected stakeholders: "We are trying X for Y weeks. Here is what we are measuring."
- Designate one person to monitor the kill criteria continuously.

### Step 5: Evaluate at the Time Box
- Compare results against success criteria defined in Step 2.
- Three possible outcomes: Clear success, clear failure, or ambiguous signal.
- For ambiguous signal: extend the time box once (not more) with tightened criteria.
- Evaluation should take less than one hour. If it takes longer, you under-defined your criteria.

### Step 6: Adjust Course
- **Continue:** Results met success criteria. Formalize the decision and scale.
- **Modify:** Partial signal. Adjust the approach and run another bounded cycle.
- **Reverse:** Results met kill criteria or failed success criteria. Undo cleanly.
- If reversing, communicate the reversal with the same transparency as the original decision. No shame in fast learning.
- Update the decision registry with the outcome and lessons.

## Anti-Patterns

| Anti-Pattern | Description | Consequence |
|-------------|-------------|-------------|
| Treating irreversible decisions as reversible | Mis-classifying to avoid rigorous analysis | Costly reversals, broken trust |
| Reversible decision, irreversible process | Using heavy process for a lightweight decision | Slow execution, missed learning window |
| Unbounded experiments | No time box or cost cap on the "experiment" | The experiment becomes the strategy by default |
| No kill criteria | Running the experiment without defined failure signals | Zombie initiatives that never die |
| Stigmatizing reversal | Treating course correction as failure rather than learning | People avoid reversible decisions, defaulting to inaction |
| Endless extensions | Repeatedly extending ambiguous experiments instead of deciding | Decision avoidance disguised as rigor |

## Examples

### Example 1: Pricing Tier Experiment

**Classify:** Adding a new pricing tier is reversible. Reversal cost: update the pricing page and grandfather early adopters. Blast radius: small — affects new signups only.

**Bound:** 4-week experiment. Cost cap: $2K in engineering time. Success: 15% of new signups choose the new tier. Kill: conversion rate on existing tiers drops more than 5%.

**Decide:** Product lead decides to launch the tier. Rationale: "Customer interviews suggest willingness to pay; 4 weeks of data beats 4 more weeks of interviews."

**Result:** After 4 weeks, 11% chose the new tier (below 15% target) but overall revenue per signup increased 8%. Modified: adjusted pricing and extended 2 weeks. Hit 16% adoption. Formalized.

### Example 2: Async Standup Trial

**Classify:** Switching from daily video standups to async written updates is reversible. Reversal cost: zero. Blast radius: one team.

**Bound:** 3-week experiment. Success: team velocity maintained or improved; satisfaction survey scores stable or improved. Kill: any critical blocker goes undetected for more than 24 hours.

**Decide:** Team lead decides the same afternoon as the proposal. No meeting required.

**Result:** Velocity improved 12%, satisfaction up, no blockers missed. Team voted unanimously to continue. Two other teams adopted the practice.
