# Agent-Role Mapping — Canonical Reference

## Purpose

This document is the single source of truth for mapping between role names (used in `config.yaml` routing) and thinker-based agent files. All workflows, tasks, and documentation should use role names for functional references and thinker names when invoking agent personas.

## Canonical Mapping

| Role Name | Thinker | Agent File | Domain | Primary Responsibility |
|---|---|---|---|---|
| board-chair | Board Chair | `agents/board-chair.md` | governance | Orchestration, agenda, decision registration, quality |
| strategic-advisor | Peter Thiel | `agents/peter-thiel.md` | strategy | Competitive strategy, moat analysis, contrarian truth |
| capital-allocator | Charlie Munger | `agents/charlie-munger.md` | capital | Financial modeling, investment decisions, mental models |
| talent-advisor | Patrick Lencioni | `agents/patrick-lencioni.md` | people | Org health, team alignment, executive hiring |
| culture-steward | Brene Brown | `agents/brene-brown.md` | culture | Trust, psychological safety, courageous conversations |
| risk-sentinel | Ray Dalio | `agents/ray-dalio.md` | risk | Decision process, radical transparency, risk principles |
| partnership-broker | Reid Hoffman | `agents/reid-hoffman.md` | partnerships | Network effects, deal structuring, alliance management |
| growth-navigator | Naval Ravikant | `agents/naval-ravikant.md` | growth | Leverage, compounding, wealth creation, focus |
| governance-clerk | Simon Sinek | `agents/simon-sinek.md` | governance | Purpose clarity, documentation, mission alignment |
| ethics-compass | Yvon Chouinard | `agents/yvon-chouinard.md` | ethics | Ethical review, sustainability, stakeholder impact |
| simplicity-czar | Derek Sivers | `agents/derek-sivers.md` | operations | Complexity reduction, focus enforcement, scope control |

## Usage Convention

- **In config.yaml routing:** Use role names (e.g., `strategic-advisor`)
- **In workflows and tasks:** Use `role-name (Thinker Name)` format (e.g., `strategic-advisor (Peter Thiel)`)
- **When activating personas:** Use thinker names and their full persona description from the agent file
- **In cross-squad handoffs:** Use role names — external squads do not need to know internal persona details

## Why Thinker-Based Agents?

Each agent is modeled after a real-world thinker whose expertise, frameworks, and worldview align with the role's domain. This design provides:

1. **Deep persona consistency** — Each agent has a well-defined intellectual foundation
2. **Framework grounding** — Frameworks are not abstract; they come from specific, proven thinkers
3. **Believability weighting** — Routing questions to the thinker with highest domain credibility
4. **Anti-pattern detection** — Each thinker has documented pitfalls that serve as guardrails

## Cross-References

- **Config routing:** `config.yaml → routing` (task-to-agent assignments)
- **Agent mapping:** `config.yaml → agent_mapping` (machine-readable mapping)
- **Quality gates:** `config.yaml → quality_gates` (per-domain gates owned by agents)
- **Architecture:** `ARCHITECTURE.md → Section 12` (agent-role mapping table)
- **Agent files:** `agents/*.md` (full persona definitions with Role Mapping sections)

## Mapping Tensions

Some role-thinker mappings have natural tension that is intentional:

- **capital-allocator ↔ Charlie Munger:** Munger's primary lens is thinking quality and anti-stupidity, not pure financial modeling. This means capital decisions get an extra layer of cognitive bias checking.
- **risk-sentinel ↔ Ray Dalio:** Dalio's primary lens is decision process design, not pure risk management. This means risk assessment is grounded in systematic principles rather than reactive fear.
- **governance-clerk ↔ Simon Sinek:** Sinek's primary lens is purpose and mission clarity, not administrative documentation. This means governance is anchored to organizational purpose rather than mere compliance.

These tensions are features, not bugs. They ensure each role brings a deeper intellectual perspective than a narrow functional definition would.
