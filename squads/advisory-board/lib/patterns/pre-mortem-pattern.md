# Pre-Mortem Pattern

## Pattern Name

Pre-Mortem — a prospective exercise that imagines a decision has already failed and works backward to identify the most likely causes, conducted before the decision is finalized.

## When to Use

- Before making any irreversible or high-stakes decision.
- When the team has reached a preliminary recommendation and needs to stress-test it.
- When groupthink risk is high (strong leader championing a direction, high team cohesion, time pressure).
- Before major launches, fundraises, hires, partnerships, or strategic bets.
- When the "what could go wrong" conversation has been too brief or too optimistic.

Do NOT use when:
- The decision is already made and executed (use postmortem-pattern.md instead).
- The decision is trivially reversible and the cost of failure is negligible.
- It is being used as a stalling tactic by people who oppose the decision for political reasons.

## Structure

```
1. SET UP     → Establish the scenario and ground rules
2. IMAGINE    → "The decision was made. It failed. Why?"
3. GENERATE   → Each person independently writes failure causes
4. SHARE      → All causes are surfaced without judgment
5. PRIORITIZE → Rank by likelihood and severity
6. MITIGATE   → Build defenses against the top failure modes
```

## Steps

### Step 1: Set Up the Exercise
- Timing: Conduct after the recommendation is formed but before the final decision is ratified.
- Duration: 45-60 minutes for a typical decision; 90 minutes for existential decisions.
- Participants: Everyone involved in the decision plus at least one outsider or skeptic.
- Frame: "We have a recommendation on the table. Before we finalize it, we are going to assume it was implemented and failed badly. Our job is to figure out why."
- Ground rules:
  - Pessimism is the objective. Do not defend the decision during this exercise.
  - No idea is too unlikely. We are mining for blind spots.
  - Write independently before sharing — this prevents anchoring on the first speaker's ideas.
  - The goal is to improve the decision, not to kill it.

### Step 2: Set the Failure Scenario
- The facilitator reads the scenario:
  - "It is [6 months / 12 months / appropriate timeframe] from now. We went ahead with [the recommendation]. It has failed spectacularly. The outcome is [worst realistic scenario — lost money, damaged reputation, missed the market, etc.]. We are conducting the postmortem. Your job: what went wrong?"
- Be specific about the failure. "It failed" is too vague. "We launched in LATAM and lost $2M in 9 months with zero traction" is vivid enough to trigger useful thinking.
- Allow 30 seconds of silence for the scenario to sink in.

### Step 3: Independent Failure Cause Generation
- Each participant writes independently for 8-10 minutes.
- Prompt: "List every reason you can think of for why this failed. Include causes that are unlikely but devastating, not just obvious risks."
- Categories to consider:
  - **Assumptions:** Which assumptions underlying the decision proved wrong?
  - **Execution:** Where did implementation break down?
  - **External:** What market, competitive, or regulatory changes caught us off guard?
  - **People:** Who left, burned out, or turned out to be wrong for the role?
  - **Timing:** What happened because we moved too fast or too slow?
  - **Incentives:** Whose incentives were misaligned with the decision's success?
  - **Unknown unknowns:** What did we not even think to worry about?
- Target: 5-10 causes per person. Push past the first 3-4 obvious ones — the valuable insights usually come after the easy answers.

### Step 4: Share Without Judgment
- Go around the room. Each person shares one cause at a time, round-robin, until all unique causes are captured.
- No debating or defending during this phase. Only clarifying questions.
- Facilitator captures all causes on a shared board.
- Group similar causes but do not eliminate anything yet.
- After all causes are shared, ask: "What did we miss? What are we still not willing to say out loud?"

### Step 5: Prioritize Failure Modes
- Score each failure cause on two dimensions:
  - **Likelihood:** How probable is this failure mode? (1 = very unlikely, 5 = very likely)
  - **Severity:** If this happens, how bad is the damage? (1 = minor setback, 5 = existential)
- Multiply for a composite score (1-25).
- Focus on the top 5-7 failure modes by composite score.
- Pay special attention to high-severity items even if likelihood is moderate — these are the ones that kill companies.

### Step 6: Build Mitigations
- For each top failure mode, define:
  - **Prevention:** What can we do before launch to reduce the probability of this failure?
  - **Detection:** What early warning signal would tell us this failure mode is materializing?
  - **Response:** If we detect the signal, what is our pre-planned response?
  - **Kill trigger:** At what point does this failure mode invalidate the entire decision?
- Integrate mitigations into the decision memo (use `lib/components/decision-memo-blocks.md` Block 4).
- If the pre-mortem reveals a failure mode that is both highly likely and highly severe with no credible mitigation, the recommendation should be reconsidered or modified.

## Anti-Patterns

| Anti-Pattern | Description | Consequence |
|-------------|-------------|-------------|
| Performative pre-mortem | Going through the motions without genuine pessimism | Blind spots remain; false confidence |
| Leader anchoring | Senior leader speaks first and everyone agrees with their failure causes | Groupthink persists despite the exercise |
| Defense mode | Participants defend the recommendation instead of attacking it | Defeats the entire purpose |
| Too many mitigations | Every failure cause gets an elaborate mitigation plan | Diluted focus; execution paralysis |
| Skipping independent writing | Going straight to group discussion without individual reflection | Anchoring bias; introverts silenced |
| Pre-mortem as veto | Using the exercise to kill a decision that has been properly vetted | Tool becomes political weapon |

## Examples

### Example: Pre-Mortem on Series A Fundraise

**Scenario:** "It is October 2026. We launched our Series A process in April. We failed to close a round. The company has 4 months of runway and is scrambling for a bridge. What happened?"

**Top failure causes generated:**
1. Market downturn hit in Q3; VCs pulled back on new investments (Likelihood: 3, Severity: 5, Score: 15)
2. Our metrics were not Series A-ready; VCs wanted $2M ARR and we showed $1.4M (Likelihood: 4, Severity: 4, Score: 16)
3. CEO spent 3 months fundraising and product velocity collapsed (Likelihood: 3, Severity: 4, Score: 12)
4. Key reference from previous investor was lukewarm (Likelihood: 2, Severity: 4, Score: 8)
5. Lead investor term sheet fell through at final diligence (Likelihood: 2, Severity: 5, Score: 10)
6. Competitive funding round by rival created comparison pressure (Likelihood: 3, Severity: 3, Score: 9)

**Mitigations for top causes:**
| Failure Mode | Prevention | Detection | Kill Trigger |
|-------------|-----------|-----------|-------------|
| Metrics not ready (16) | Delay process until $1.8M ARR; build pipeline now | Monthly ARR check against target | If ARR is below $1.6M by March, defer to Q4 |
| Market downturn (15) | Build bridge option with existing investors as insurance | Monitor VC deal volume monthly | If VC deal volume drops 30% from baseline, activate bridge |
| CEO bandwidth drain (12) | Hire interim COO or empower VP to run ops during fundraise | Weekly product velocity check during process | If velocity drops >25% for 2 consecutive weeks, pause fundraise |

**Decision modification:** Based on pre-mortem, the board decided to delay fundraise by one quarter, target $1.8M ARR as the trigger, and secure a $500K bridge commitment from existing investors as insurance.
