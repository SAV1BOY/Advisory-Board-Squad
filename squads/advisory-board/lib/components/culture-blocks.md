# Culture Blocks

## Purpose

Reusable structural blocks for assessing, designing, and evolving organizational culture at board level. Culture is the operating system of the organization — it determines how decisions are made when no one is watching. These blocks make culture visible, measurable, and actionable rather than leaving it as an abstract aspiration.

## Structure

### Block 1 — Culture Definition Card

Articulates the intended culture with behavioral specificity.

**Fields:**
- **Core values:** 3-6 values stated as behavioral principles, not single words. Each value includes: (a) what it means in practice, (b) what it does NOT mean, (c) an observable behavior that demonstrates it.
- **Operating principles:** 5-10 rules of engagement that govern daily work (e.g., "Default to transparency — share context, not just conclusions").
- **Decision defaults:** How the culture expects decisions to be made when no policy exists (e.g., "Bias toward action on reversible decisions").
- **Cultural non-negotiables:** Behaviors that result in termination regardless of performance.
- **Cultural debts acknowledged:** Aspects of culture that are aspirational but not yet real.

### Block 2 — Culture Health Assessment

Measures the gap between intended and actual culture.

**Fields:**
- **Assessment method:** Survey, interviews, observation, artifact analysis, or combination.
- **Sample size and representativeness:** Who was assessed and whether the sample reflects the organization.
- **Value-by-value scoring:** Each core value rated on a 1-5 lived-reality scale.
- **Bright spots:** Where culture is strongest — specific teams, practices, or rituals that embody the values.
- **Gap areas:** Where stated values diverge from observed behavior, with specific examples.
- **Trend direction:** Improving, stable, or deteriorating versus the previous assessment.
- **Evasion indicators:** Signs that people are performing culture rather than living it (e.g., values mentioned in all-hands but contradicted in Slack).

### Block 3 — Ritual Design

Defines recurring practices that reinforce desired culture.

**Fields:**
- **Ritual name:** Descriptive name (e.g., "Friday Failure Share").
- **Cultural value reinforced:** Which core value this ritual strengthens.
- **Format:** How the ritual works — cadence, duration, structure, facilitation.
- **Participation:** Who participates and whether attendance is voluntary or expected.
- **Success signal:** How you know the ritual is working (observable behavior change, not attendance count).
- **Decay signal:** How you know the ritual has become performative and needs refreshing.
- **Owner:** Who is responsible for maintaining the ritual's integrity.

### Block 4 — Culture Incident Record

Documents significant cultural events — both positive exemplars and violations.

**Fields:**
- **Incident date:** When it occurred.
- **Type:** Positive exemplar / Minor drift / Serious violation / Systemic pattern.
- **Description:** What happened in specific, observable terms.
- **Value affected:** Which core value was demonstrated or violated.
- **Response:** What action was taken and by whom.
- **Signal strength:** Was this an isolated event or part of a pattern.
- **Systemic implication:** Does this reveal a process, incentive, or leadership gap.
- **Follow-up:** Actions taken to reinforce the positive or address the negative.

### Block 5 — Culture Change Plan

Structured approach to evolving culture intentionally.

**Fields:**
- **Change objective:** Specific cultural shift desired (from X to Y behavior).
- **Why now:** The business trigger making this change urgent.
- **Leadership modeling:** How leaders will visibly demonstrate the new behavior.
- **Structural reinforcement:** Changes to incentives, processes, or organizational design that support the shift.
- **New rituals:** Practices introduced to reinforce the new culture (use Block 3).
- **Retired rituals:** Practices that reinforced the old culture and should be stopped.
- **Narrative shift:** How the change will be communicated and the story told.
- **Measurement plan:** How progress will be tracked (link to `data/metrics/culture-health-score.md`).
- **Timeline:** Realistic timeline acknowledging that culture change takes 6-18 months.
- **Resistance plan:** Expected sources of resistance and how each will be addressed.

### Block 6 — Culture Due Diligence

Assesses culture compatibility in hiring, partnerships, and M&A contexts.

**Fields:**
- **Entity assessed:** The team, company, or partner being evaluated.
- **Assessment method:** Interviews, observation, Glassdoor/public signals, reference checks.
- **Cultural profile:** Summary of the entity's operating culture.
- **Compatibility matrix:** Point-by-point comparison with your culture on key dimensions.
- **Integration risks:** Where cultural collision is most likely and most dangerous.
- **Integration plan:** Specific steps to bridge cultural gaps if the relationship proceeds.
- **Deal-breaker thresholds:** Cultural incompatibilities severe enough to kill the deal.

## Usage

1. **Block 1** is foundational. Every organization needs this documented, and it should be reviewed annually.
2. **Block 2** is conducted quarterly using `utilities/culture-health-rubric.md`. Results feed `data/metrics/culture-health-score.md`.
3. **Block 3** is used when designing new rituals or auditing existing ones. Every ritual should map to a value.
4. **Block 4** is used as events occur. A pattern of unrecorded culture incidents signals that culture is being managed by hope rather than intention.
5. **Block 5** is activated when Block 2 reveals a material gap or when strategic direction demands cultural evolution.
6. **Block 6** is mandatory for executive hires, strategic partnerships, and any M&A activity.

## Example

```markdown
# Culture Health Assessment — Q1 2026

## Assessment Summary
- **Method:** Anonymous survey (87% response rate) + 12 skip-level interviews
- **Overall score:** 3.6 / 5.0 (up from 3.3 in Q4 2025)

## Value-by-Value Scores
| Value | Score | Trend | Notes |
|-------|-------|-------|-------|
| Default to transparency | 4.1 | Up | Open financial sharing well received |
| Disagree and commit | 2.8 | Stable | People agree publicly, undermine privately |
| Customer obsession | 4.0 | Up | Support team sets the standard |
| Move fast, learn faster | 3.4 | Down | Process accumulation slowing shipping |
| Own the outcome | 3.7 | Up | New accountability rituals working |

## Priority Gap: Disagree and Commit (2.8)
- **Observation:** Team leads report that decisions are relitigated in back-channels after meetings
- **Root cause:** No formal dissent capture mechanism; people feel unheard
- **Action plan:** Implement dissent-and-commit pattern from `lib/patterns/dissent-and-commit-pattern.md` in all decision meetings starting April 1
```
