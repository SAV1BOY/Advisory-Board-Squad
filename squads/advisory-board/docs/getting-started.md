# Getting Started with the Advisory Board Squad

## What This Is

The Advisory Board Squad is an AI-native advisory board — a system of agents, workflows, and frameworks that provides strategic counsel to the organization. It operates like a world-class board of advisors: it reviews strategy, challenges decisions, manages risk, and holds leadership accountable.

## Quick Start (5 Minutes)

### 1. Understand the structure

```
squads/advisory-board/
├── agents/         → The AI agents that staff the board
├── workflows/      → End-to-end playbooks for every board activity
├── frameworks/     → Mental models and decision frameworks
├── voice/          → Tone profiles, language guides, calibration
├── phrases/        → Curated phrase libraries for specific contexts
├── templates/      → Reusable document templates
├── docs/           → Documentation (you are here)
├── reference/      → External reference materials
├── data/           → Data inputs and outputs
├── archive/        → Historical records
├── tasks/          → Active task queue
└── scripts/        → Automation scripts
```

### 2. Read these three files first

1. **`docs/board-overview.md`** — What the board does, who the agents are, and how they interact.
2. **`docs/board-charter.md`** — The board's authority, scope, and operating rules.
3. **`docs/workflow-guide.md`** — How to select and run the right workflow for your situation.

### 3. Run your first workflow

The most common starting points:

- **New to the board?** Start with `workflows/00-board-setup-flow.md` to understand the formation process.
- **Preparing for a meeting?** Use `workflows/01-end-to-end-board-meeting.md`.
- **Making a strategic decision?** Use `workflows/02-strategy-refresh-cycle.md` or `workflows/03-capital-allocation-cycle.md`.
- **Facing a crisis?** Go directly to `workflows/07-crisis-response-72h.md`.

## Key Concepts

### Agents
The board is staffed by specialized agents, each with a defined role:
- **Board-Chair** — Runs the board, facilitates decisions, holds people accountable.
- **Strategy-Analyst** — Produces analysis, builds models, prepares pre-reads.
- **Devil's-Advocate** — Challenges every recommendation. Their job is to find flaws.
- **Risk-Analyst** — Assesses risks, models downsides, maintains the risk register.
- **Culture-Guardian** — Monitors values alignment and organizational health.
- **Governance-Ops** — Handles logistics, templates, tracking, and archiving.
- **Execution-Tracker** — Monitors action items and follow-through.
- **Decision-Tracker** — Logs decisions with rationale, dissent, and review dates.

See `docs/agent-roles-guide.md` for complete role descriptions.

### Workflows
Workflows are numbered playbooks that cover every board activity from setup to post-mortem. Each workflow specifies: trigger, agents involved, phases, quality gates, outputs, timeline, metrics, and common failure modes.

See `docs/workflow-guide.md` for the complete workflow index.

### Voice
The board communicates with a specific tone — direct, evidence-based, and caring. Voice is calibrated through tone profiles, language guides, and channel-specific templates.

See `voice/tone-profiles/` for the six tone profiles and `voice/language-guides/` for writing and communication standards.

### Frameworks
Mental models and decision frameworks used by the board — from first-principles thinking to expected-value analysis to pre-mortems.

See `frameworks/` for the full library and `docs/framework-selection-guide.md` for when to use which framework.

## How to Use This System

### For a board meeting
1. Open `workflows/01-end-to-end-board-meeting.md`.
2. Follow the phases: agenda prep, pre-reads, meeting execution, minutes, follow-through.
3. Use `voice/language-guides/meeting-facilitation.md` for facilitation language.
4. Use `phrases/meeting-control-phrases.md` for managing discussion flow.

### For a strategic decision
1. Identify the decision type (strategy, capital, hiring, partnership).
2. Select the corresponding workflow.
3. Follow the phases, engaging the relevant agents at each step.
4. Use `docs/decision-policy.md` for decision-rights and process standards.

### For communication
1. Identify the audience and channel.
2. Select the appropriate channel guide from `voice/channels/`.
3. Apply the relevant tone profile from `voice/tone-profiles/`.
4. Use `phrases/words-to-avoid-board.md` as a final check.

## Naming Conventions

All files follow the conventions in `docs/naming-conventions.md`. The short version:
- Workflows: `NN-descriptive-name.md` (numbered, kebab-case).
- Templates: `descriptive-name-template.md`.
- Archive: `YYYY-MM-DD-descriptive-name.md`.

## Contributing

See `docs/contribution-guide.md` for how to propose changes, add new workflows, or update existing materials.

## Getting Help

- **Workflow selection:** See `docs/workflow-guide.md`.
- **Framework selection:** See `docs/framework-selection-guide.md`.
- **Escalation:** See `docs/escalation-policy.md`.
- **Glossary:** See `docs/glossary.md` for terminology.
