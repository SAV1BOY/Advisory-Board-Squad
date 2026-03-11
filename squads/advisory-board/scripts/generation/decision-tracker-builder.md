# Decision Tracker Builder

## Purpose

Generates and maintains a decision tracking dashboard from the decision registry (`data/registries/decision-registry.yaml`). The tracker provides a consolidated view of all board and executive decisions: their status, outcomes, follow-up actions, and lessons learned. It transforms raw registry data into an actionable monitoring tool that surfaces decisions requiring attention.

## Input

- **Decision registry:** The primary data source (`data/registries/decision-registry.yaml`), containing all logged decisions with metadata.
- **Action item tracker:** Cross-referenced with `scripts/tracking/action-item-tracker.md` output to link decisions to their downstream actions.
- **Meeting minutes:** Cross-referenced with recent meeting outputs to identify new decisions not yet in the registry.
- **Time range:** Configurable window for the dashboard view (default: last 90 days, with option for all-time).

## Process Steps

1. **Parse decision registry:** Read all entries from `data/registries/decision-registry.yaml`. For each decision, extract:
   - Decision ID, title, date, type (strategic/operational/tactical)
   - Classification: reversible (two-way door) vs. irreversible (one-way door)
   - Status: pending, active, completed, reversed, deferred
   - Owner and stakeholders
   - Expected outcome and actual outcome (if completed)
   - Follow-up actions and their completion status

2. **Identify gaps:** Scan recent meeting minutes (from `scripts/generation/minutes-extractor.md` output) for decisions mentioned but not yet in the registry. Flag these as "unregistered decisions" requiring entry.

3. **Assess decision health:** For each active decision, evaluate:
   - Are follow-up actions on track? Cross-reference with action item tracker.
   - Has the decision passed its review date without a review?
   - Are kill criteria approaching or breached?
   - Has the decision's context changed materially since it was made?

4. **Generate dashboard sections:**

   **Section A: Decision Summary**
   - Total decisions in period, by type and status
   - Trend: are decisions being made faster or slower than the prior period?
   - Ratio of reversible to irreversible decisions

   **Section B: Decisions Requiring Attention**
   - Overdue reviews: decisions past their scheduled review date
   - Stalled actions: decisions with follow-up actions that are behind schedule
   - Kill criteria alerts: decisions approaching or exceeding defined failure thresholds
   - Unregistered decisions: identified in meetings but not formally logged

   **Section C: Decision Outcomes**
   - Completed decisions with outcome assessment: achieved, partially achieved, failed
   - Lessons learned from completed decisions (extracted from registry notes)
   - Decision quality score trend (from `scripts/analysis/decision-quality-analyzer.md`)

   **Section D: Decision Patterns**
   - Average time from decision to first action
   - Percentage of decisions with defined kill criteria
   - Most common decision types and categories
   - Decisions by owner (to identify concentration or bottlenecks)

5. **Generate alerts:** Create a prioritized list of items requiring immediate board or executive attention:
   - Critical: Kill criteria breached, irreversible decision at risk
   - Warning: Review overdue by more than 30 days, multiple stalled actions
   - Info: Upcoming review dates, newly registered decisions

6. **Format output:** Produce the dashboard in markdown format suitable for inclusion in board pre-read packs. Include summary metrics at the top, detailed sections below, and an appendix with raw data references.

## Output

- A markdown dashboard document with four sections (Summary, Attention Required, Outcomes, Patterns).
- An alerts list sorted by priority (critical, warning, info).
- A list of unregistered decisions requiring formal logging.
- Updated decision registry entries with status changes flagged during the health assessment.

## Automation Notes

- Recommended cadence: generate weekly for executive team, monthly for board reporting.
- Can be triggered automatically before board meetings by the `scripts/generation/pre-read-pack-builder.md` pipeline.
- Integrates with `scripts/tracking/decision-log-updater.md` for registry maintenance.
- Integrates with `scripts/analysis/decision-quality-analyzer.md` for quality scoring.
- Dashboard output feeds into `scripts/generation/stakeholder-update-builder.md` for investor and stakeholder reporting.
- Human review is mandatory before distribution — the script identifies patterns and flags issues, but interpretation requires judgment.
- Estimated generation time: 5-10 minutes depending on registry size.
