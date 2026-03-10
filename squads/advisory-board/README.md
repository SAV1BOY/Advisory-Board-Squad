# Advisory Board Squad

## Purpose

The Advisory Board Squad is an AI-native advisory board that provides board-level strategy, capital allocation, leadership, culture, and governance guidance. It operates as a system of 11 specialized agents coordinated through a central routing configuration, producing written artifacts — decision memos, strategic diagnoses, hiring scorecards, culture audits, and crisis responses — at the quality standard expected of a world-class board of directors.

This is not a chatbot. It is a governance system with documented principles, enforceable quality gates, institutional memory, and a learning loop that improves judgment over time.

## Vision

Build the most rigorous, transparent, and effective advisory board system by codifying the best practices of exceptional boards, the mental models of the world's sharpest strategic thinkers, and the discipline of writing everything down.

---

## Agents

The squad operates through 11 agents, each with a defined domain and persona. The board-chair orchestrates all routing and resolves deadlocks.

| # | Agent | Domain | Role |
|---|-------|--------|------|
| 1 | **board-chair** | Governance | Chief orchestrator. Routes tasks, runs meetings, resolves deadlocks, owns quality. Speaks last. |
| 2 | **strategic-advisor** | Strategy | Competitive strategy, moat analysis, market positioning, product-strategy review. |
| 3 | **capital-allocator** | Capital | Financial modeling, fundraising, investment decisions, resource allocation. |
| 4 | **talent-advisor** | People | Executive hiring, org design, succession planning, team effectiveness. |
| 5 | **culture-steward** | Culture | Culture audits, trust repair, values alignment, organizational health. |
| 6 | **risk-sentinel** | Risk | Risk mapping, crisis response, scenario planning, compliance. |
| 7 | **partnership-broker** | Partnerships | Partnership evaluation, deal structuring, negotiation, alliance management. |
| 8 | **growth-navigator** | Growth | Growth strategy, execution planning, 30-60-90 programs, scaling. |
| 9 | **governance-clerk** | Governance | Documentation, compliance, decision logs, meeting minutes, registries. |
| 10 | **ethics-compass** | Ethics | Ethical review, stakeholder impact, sustainability, long-term reputation. |
| 11 | **simplicity-czar** | Operations | Complexity reduction, focus enforcement, scope control, noise filtering. |

---

## Directory Structure

```
squads/advisory-board/
├── config.yaml                  # Routing brain — task-to-agent mapping, quality gates, KPIs
├── swipe.config                 # Swipe file sourcing and curation rules
├── README.md                    # This file
├── ARCHITECTURE.md              # Decision-making constitution and system design
│
├── agents/                      # Agent definition files (11 agents)
│
├── frameworks/                  # Thinking tools and analytical models
│   ├── decision-memo-framework.md
│   ├── second-order-thinking.md
│   ├── strategic-diagnosis.md
│   ├── moat-analysis.md
│   ├── pivot-or-persevere.md
│   ├── crisis-response-72h.md
│   ├── ralph-loop.md
│   └── ... (50+ frameworks)
│
├── checklists/                  # Quality gates organized by domain and thinker
│   ├── board-decision-memo-quality.md
│   ├── second-order-effects-quality.md
│   ├── reversible-vs-irreversible-quality.md
│   ├── incentives-alignment-quality.md
│   ├── chair/                   # Board chair operational checklists
│   ├── strategy/                # Strategy domain checklists
│   ├── capital/                 # Capital domain checklists
│   ├── culture/                 # Culture domain checklists
│   ├── hiring/                  # Hiring process checklists
│   ├── leadership/              # Leadership and org design checklists
│   ├── governance/              # Governance and compliance checklists
│   ├── partnerships/            # Partnership evaluation checklists
│   ├── risk/                    # Risk and crisis checklists
│   ├── product/                 # Product strategy checklists
│   ├── growth/                  # Growth execution checklists
│   ├── munger/                  # Charlie Munger mental model checklists
│   ├── thiel/                   # Peter Thiel zero-to-one checklists
│   ├── dalio/                   # Ray Dalio principles checklists
│   ├── sinek/                   # Simon Sinek why-alignment checklists
│   ├── lencioni/                # Patrick Lencioni team health checklists
│   ├── brene-brown/             # Brene Brown trust and vulnerability checklists
│   ├── hoffman/                 # Reid Hoffman alliance checklists
│   ├── naval/                   # Naval Ravikant leverage checklists
│   ├── sivers/                  # Derek Sivers focus checklists
│   └── chouinard/               # Yvon Chouinard sustainability checklists
│
├── templates/                   # Output format templates
│   ├── memos/                   # Decision memos, strategy memos, hiring memos
│   ├── meeting/                 # Agendas, minutes, board packages
│   ├── briefs/                  # Executive briefs, investor briefs
│   ├── dashboards/              # Board dashboards, KPI trackers
│   ├── reports/                 # Review reports, audit reports
│   └── people/                  # Scorecards, interview guides, org charts
│
├── tasks/                       # Task definitions organized by domain
│   ├── board-ops/               # Board setup, meeting, effectiveness
│   ├── strategy/                # Strategic diagnosis, moat, product, pivot
│   ├── capital/                 # Allocation, fundraising, investment
│   ├── people/                  # Hiring, org design, succession
│   ├── culture/                 # Conflict, audit, trust repair
│   ├── partnerships/            # Evaluation, structuring
│   ├── risk/                    # Crisis response, risk mapping
│   ├── operations/              # Simplify, focus, execution
│   └── review/                  # Decision quality, quarterly review
│
├── data/                        # Live data stores and registries
│   ├── decisions/               # Signed decision memos
│   ├── meeting-minutes/         # Board meeting records
│   ├── memos/                   # Working memos and drafts
│   ├── metrics/                 # KPI data files
│   ├── forecasts/               # Financial and strategic forecasts
│   ├── registries/              # Structured registries (YAML)
│   └── research/                # Market, competitor, customer, macro research
│       ├── market-notes/
│       ├── competitor-notes/
│       ├── customer-insights/
│       ├── industry-trends/
│       └── macro-economic-notes/
│
├── swipe/                       # Curated real-world examples
│   ├── shareholder-letters/
│   ├── strategy-memos/
│   ├── board-decks/
│   ├── crisis-playbooks/
│   ├── hiring-scorecards/
│   ├── partnership-deals/
│   ├── decision-memos/
│   ├── culture-docs/
│   └── one-liners-and-narratives/
│
├── swipe-sources/               # Raw source material before curation
│
├── archive/                     # Historical records (never deleted)
│   ├── decisions-archive/
│   ├── pivot-history/
│   ├── crisis-retros/
│   ├── failed-bets/
│   ├── hiring-misses/
│   └── iconic-decisions/
│
├── reference/                   # Reference material by topic
│   ├── books/
│   ├── ethics/
│   ├── finance/
│   ├── governance/
│   ├── industries/
│   ├── letters/
│   ├── memos/
│   ├── negotiation/
│   ├── psychology/
│   └── startups/
│
├── authority/                   # Thought leadership and external assets
│   ├── agent-summaries/
│   ├── case-studies/
│   ├── talks-and-interviews/
│   └── workshop-kits/
│
├── voice/                       # Communication style and tone
│   ├── calibration/
│   ├── channels/
│   ├── language-guides/
│   └── tone-profiles/
│
├── phrases/                     # Signature phrases and language patterns
│
├── lib/                         # Shared components and utilities
│   ├── components/
│   ├── patterns/
│   ├── taxonomies/
│   └── utilities/
│
├── scripts/                     # Automation scripts
│   ├── analysis/
│   ├── generation/
│   └── tracking/
│
├── projects/                    # Active project workspaces
│   ├── annual-strategic-planning/
│   ├── crisis-response/
│   ├── exec-hiring/
│   ├── fundraising/
│   ├── m-and-a/
│   ├── mission-integrity-initiative/
│   ├── org-health-turnaround/
│   ├── partnership-deal/
│   └── strategic-reset/
│
├── workflows/                   # Multi-step workflow definitions
│
└── docs/                        # Internal squad documentation
```

---

## How It Works

### Routing via config.yaml

Every task entering the advisory board is routed through `config.yaml`. The routing table maps each task to:

1. **Agents** — Who works on this (lead agent listed first, supporting agents follow)
2. **Frameworks** — Which thinking tools to apply
3. **Checklists** — Which quality gates the output must pass
4. **Templates** — Which output format to use
5. **Registry** — Which data stores to read from or write to

Example: when the task `pivot-or-persevere-decision` is triggered, config.yaml routes it to `strategic-advisor` (lead), with `board-chair`, `capital-allocator`, `risk-sentinel`, and `culture-steward` consulted. The output must apply the pivot-or-persevere framework, pass the reversibility quality checklist, and produce a decision memo using the standard template.

### Decision Flow

```
Task Arrives
    │
    ▼
config.yaml routing lookup
    │
    ▼
Classify decision type (Type 1 / Type 2)
    │
    ├── Type 2 (reversible): Fast path — lead agent + 1 reviewer
    │
    └── Type 1 (irreversible): Full deliberation — all assigned agents
         │
         ▼
    Apply frameworks
         │
         ▼
    Draft output using template
         │
         ▼
    Run quality gate checklists
         │
         ├── PASS → Sign, file to data/decisions/, notify
         │
         └── FAIL → Revise and resubmit (max 2 cycles, then escalate)
```

---

## Cross-Squad Integration

The advisory board integrates bidirectionally with 8 sibling squads:

| Squad | What We Send | What We Receive |
|-------|-------------|-----------------|
| **Brand Squad** | Strategic positioning, moat findings, crisis comms | Brand health metrics, competitive perception data |
| **Copy Squad** | Investor narratives, crisis drafts, board comms | Polished communications, editorial standards |
| **Data Squad** | KPI definitions, data requests, dashboard specs | Validated dashboards, forecasting models |
| **Cybersecurity Squad** | Security risk items, compliance needs | Security posture reports, threat briefings |
| **Design Squad** | Product strategy, UX priorities | Board presentation design, UX research |
| **Traffic Squad** | Growth direction, channel capital allocation | Channel performance, CAC/LTV models |
| **Storytelling Squad** | Strategic narrative, company story evolution | Narrative assets, thought leadership |
| **Movement Squad** | Mission alignment, sustainability direction | Community health data, stakeholder sentiment |

All handoffs are documented in `config.yaml` under `cross_squad` with explicit `handoff_to`, `handoff_from`, and `shared_assets` for each squad.

---

## KPIs

The squad tracks 19 KPIs across four categories:

### Board Effectiveness (5 KPIs)
- Decision Memo Quality Score (target: >= 85/100)
- Pre-Read Distribution Timeliness (target: >= 95%)
- Decision Velocity (target: <= 14 days)
- Board Meeting NPS (target: >= 70)
- Action Item Completion Rate (target: >= 90%)

### Business Outcomes (5 KPIs)
- Strategic Plan Adherence (target: >= 75% OKRs on track)
- Capital Efficiency Ratio (target: >= 1.0x plan)
- Moat Durability Score (target: >= 70/100)
- Revenue Growth vs. Board Forecast (target: >= 90% of forecast)
- Runway Months Remaining (target: >= 18 months)

### Organizational Health (5 KPIs)
- Executive Retention Rate (target: >= 85%)
- Culture Alignment Score (target: >= 75/100)
- Psychological Safety Index (target: >= 70/100)
- Succession Coverage (target: >= 80% of critical roles)
- Engagement Score (target: >= 72/100)

### Operational (4 KPIs)
- Decision Log Currency (target: 100% within 24 hours)
- Cross-Squad Sync Cadence (target: >= 90%)
- Quality Gate Pass Rate (target: >= 80% first submission)
- RalphLoop Cycle Completion (target: >= 70%)

All KPIs are defined with targets, measurement frequency, and data sources in `config.yaml`.

---

## Quick Start

### 1. Understand the routing
Read `config.yaml` — specifically the `routing` section. Every task the board handles is listed there with its full resource chain.

### 2. Pick a task
Choose from the 24 defined tasks (e.g., `strategic-diagnosis`, `exec-hiring`, `crisis-response-72h`).

### 3. Follow the routing
For your chosen task, config.yaml tells you:
- Which agents to activate
- Which frameworks to read and apply
- Which checklists the output must pass
- Which template to use for the deliverable
- Which data registries to consult or update

### 4. Apply quality gates
Before any output leaves the squad, run it through the mandatory quality gates listed in `config.yaml` under `quality_gates.mandatory`. Domain-specific gates under `quality_gates.per_domain` apply based on task type.

### 5. File the output
Every decision, memo, and artifact must be filed in the appropriate `data/` subdirectory. Verbal decisions are invalid. If it is not written down, it did not happen.

### 6. Learn from outcomes
After sufficient time has passed, run the RalphLoop: revisit the decision, compare expected vs. actual outcomes, extract lessons, and update frameworks and checklists. This is how the board gets smarter over time.

---

## Principles

These seven principles govern all board behavior. They are not aspirational — they are enforceable constraints checked by quality gates.

1. **Truth over comfort** — Surface uncomfortable facts early. Suppressed truth compounds into crisis.
2. **Incentives first** — Before analyzing behavior, analyze the incentive structure producing it.
3. **Second-order thinking** — Ask "and then what?" at least three levels deep before committing.
4. **Reversible fast, irreversible slow** — Type 2 decisions move fast. Type 1 decisions get full deliberation.
5. **Write it down or it didn't happen** — Verbal agreements and hallway consensus do not exist.
6. **Compounding over hype** — Favor slow, durable advantages over flashy short-term wins.
7. **Integrity over optics** — Do the right thing even when no one is watching.

---

## File Count

The advisory board squad contains approximately **810+ files** across 116 directories, covering agents, frameworks, checklists, templates, tasks, data stores, swipe files, reference materials, authority content, voice profiles, scripts, workflows, and project workspaces.

---

## Architecture

For the full system design — decision policy, conflict resolution protocol, evidence registration, the RalphLoop learning system, quality gates, and cross-squad integration protocol — see [ARCHITECTURE.md](ARCHITECTURE.md).
