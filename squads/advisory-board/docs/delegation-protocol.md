# Delegation Protocol

## Purpose

Defines when and how the Advisory Board Squad delegates tasks to other squads. The board advises, governs, and decides — it does not execute. Tasks requiring hands-on execution must be delegated through a formal protocol.

## When to Delegate

### Out-of-Scope Indicators

A task should be delegated when any of these apply:

1. **Execution-heavy:** Task requires hands-on work (coding, design, content creation, campaign management) rather than advisory input
2. **Operational/tactical:** Task has no strategic, governance, or capital dimension
3. **Domain mismatch:** Task requires expertise not held by any advisory-board agent (e.g., technical implementation, creative production)
4. **Sub-task of handoff:** Task is a downstream deliverable from a cross-squad handoff already assigned to the receiving squad

### NOT Delegation Candidates

- Tasks that require board-level judgment, even if they have execution components
- Strategic reviews with embedded analytical work (the analysis stays in-squad)
- Crisis response coordination (board owns coordination even if squads execute)

## Delegation Process

### Step 1: Flag
**Owner:** Lead agent
- Identify the task as a delegation candidate
- Write a one-paragraph rationale explaining why it's out of scope
- Propose the receiving squad based on `config.yaml → delegation_rules → receiving_squads`

### Step 2: Validate
**Owner:** board-chair
- Confirm the delegation is appropriate
- Ensure the advisory board retains oversight where needed
- Approve or reject with documented reasoning

### Step 3: Prepare Handoff Package
**Owner:** governance-clerk (Simon Sinek)
- Follow `workflows/15-cross-squad-strategic-handoff.md`
- Package must include:
  - Decision context and intent
  - Scope definition (what's delegated, what's retained)
  - Constraints and boundaries
  - Success criteria
  - Authority level granted to receiving squad
  - Review checkpoints (when does the board review progress?)

### Step 4: Quality Gate
**Owner:** board-chair + governance-clerk
- Apply `checklists/cross-squad-handoff-quality.md`
- Handoff package must pass before transfer
- If fail → rework per `docs/rework-loop-protocol.md`

### Step 5: Transfer and Log
**Owner:** governance-clerk (Simon Sinek)
- Deliver handoff package to receiving squad
- Log the delegation in `data/registries/cross-squad-log.yaml`
- Set review checkpoint dates
- Notify board-chair of completion

## Receiving Squads

| Squad | Delegation Domain | Example Tasks |
|---|---|---|
| brand_squad | Brand positioning, identity | Brand campaign execution, employer branding |
| copy_squad | Written communications | Investor updates, press releases, editorial |
| data_squad | Analytics, dashboards | Dashboard building, data pipeline, reporting |
| cybersecurity_squad | Security, compliance | Security audits, compliance implementation |
| design_squad | UX/UI, design systems | Board deck design, UX research execution |
| traffic_squad | Growth channels | Paid media, SEO, channel optimization |
| storytelling_squad | Narrative, content | Thought leadership, content production |
| movement_squad | Community, advocacy | Community programs, event management |

## Post-Delegation Oversight

The board retains oversight of delegated tasks:
- **Review checkpoints:** Set at delegation time, typically weekly or bi-weekly
- **Quality verification:** Board reviews output against original success criteria
- **Course correction:** Board can redirect, adjust scope, or recall the task
- **Closure:** Board formally accepts the deliverable or requests rework

## Integration Points

- **Cross-squad integration:** `config.yaml → cross_squad` (handoff contracts)
- **Handoff workflow:** `workflows/15-cross-squad-strategic-handoff.md`
- **Handoff quality gate:** `checklists/cross-squad-handoff-quality.md`
- **Cross-squad log:** `data/registries/cross-squad-log.yaml`
- **Architecture:** `ARCHITECTURE.md → Section 14` (delegation protocol summary)
- **Integration guide:** `docs/cross-squad-integration-guide.md`
