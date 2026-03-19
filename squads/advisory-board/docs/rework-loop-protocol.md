# Rework Loop Protocol

## Purpose

Defines what happens when an output fails a quality gate. This protocol prevents both silent failures (outputs that never meet standards) and infinite loops (rework without resolution).

## When This Protocol Applies

- Any task output that fails a mandatory quality gate (see `config.yaml → quality_gates → mandatory`)
- Any task output that fails a domain-specific quality gate with `enforcement: block_on_fail`
- Outputs that fail `warn_on_fail` gates are flagged but do not trigger mandatory rework

## Process

### Step 1: Document the Failure
**Owner:** Quality gate reviewer (the agent assigned to review the output)
- Document specific failure points with evidence
- Reference the exact checklist items that failed
- Provide actionable feedback: what needs to change and why
- File the failure in the task's decision log

### Step 2: Rework by Lead Agent
**Owner:** Lead agent from `config.yaml → routing → [task-name]`
- Review the failure report within 4 hours
- Revise the output addressing each failure point
- Re-submit within:
  - **Type 2 decisions:** 24 hours
  - **Type 1 decisions:** 72 hours

### Step 3: Re-evaluation
**Owner:** Same quality gate reviewer
- Apply the same checklist to the revised output
- If pass → output proceeds to next stage
- If fail → proceed to Step 4

### Step 4: Escalation (Second Failure)
**Owner:** board-chair
- Board-chair reviews both the output and the failure reports
- Options:
  - **Reassign** to a different agent with different perspective
  - **Adjust scope** to match achievable quality within constraints
  - **Convene review session** with multiple agents for collaborative fix
  - **Request external input** if domain expertise is insufficient

### Step 5: Final Attempt or Archive
**Owner:** board-chair + assigned agent
- Third and final rework attempt with board-chair oversight
- If pass → output proceeds with lessons logged
- If fail → task is archived with full documentation of attempts and lessons in `data/registries/lessons-learned-registry.yaml`

## Constraints

| Parameter | Value |
|---|---|
| Max rework cycles | 3 |
| Type 2 rework window | 24 hours per cycle |
| Type 1 rework window | 72 hours per cycle |
| Escalation trigger | Second consecutive failure |
| Archive trigger | Third consecutive failure |

## Anti-Patterns

| Anti-Pattern | Why It's Harmful | Detection |
|---|---|---|
| Rubber-stamping on rework | Degrades quality gate trust | Same reviewer must evaluate; no pass-without-review |
| Infinite rework without escalation | Wastes capacity, delays decisions | Max 3 cycles enforced; escalation mandatory at cycle 2 |
| Rework without specific feedback | Agent cannot improve without direction | Failure report must cite specific checklist items |
| Blaming the agent instead of diagnosing the process | May be a framework gap, not an agent gap | Board-chair investigates root cause at escalation |

## Integration Points

- **Quality gates:** `config.yaml → quality_gates` (defines which gates trigger rework)
- **Escalation rules:** `config.yaml → escalation_rules` (defines escalation levels)
- **Lessons learned:** `data/registries/lessons-learned-registry.yaml` (captures rework outcomes)
- **RalphLoop:** `ARCHITECTURE.md → Section 6` (rework patterns feed into learning system)
- **Architecture:** `ARCHITECTURE.md → Section 13` (rework loop protocol summary)
