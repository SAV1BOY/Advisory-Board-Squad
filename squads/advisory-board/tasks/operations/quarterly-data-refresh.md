# Task: Quarterly Data Refresh

## Objective
Systematically review and update all data, research, and benchmark files in the advisory board knowledge base to ensure that every data point, market reference, and benchmark used in board deliberations is current, accurate, and sourced. Stale data leads to stale advice.

## Trigger
- First week of each quarter (Q1: January, Q2: April, Q3: July, Q4: October)
- After a significant market event that invalidates current data (e.g., market crash, regulatory change, major competitor exit)
- Before annual strategic planning session
- When a board member flags outdated data in a briefing

## Agents Involved
- **Lead:** Board Secretary or Board Ops Lead
- **Support:** Research analysts, functional leaders (for domain-specific data), CFO (financial benchmarks)
- **Advisory:** Board Chair for prioritization of research areas


## Agent Assignment
> Routing: see `config.yaml → routing → quarterly-board-review`

- **Lead:** governance-clerk (Simon Sinek)
- **Support:** board-chair (Board Chair), strategic-advisor (Peter Thiel), capital-allocator (Charlie Munger)

## Pre-Requisites
- [ ] Complete inventory of all data and research files with last-updated dates
- [ ] Access to primary data sources (industry reports, public filings, databases)
- [ ] List of subscriptions and research services available
- [ ] Prior quarter's refresh log for continuity
- [ ] Feedback from board members on data gaps or quality issues

## Steps

1. **Audit current data files (Days 1-2).** Generate a complete inventory of all files in the data/research directory. For each file, record: filename, topic, last updated date, primary sources, and staleness status (current, approaching stale, stale). Flag any file not updated in the prior two quarters.

2. **Prioritize refresh targets (Day 2).** Rank files by refresh urgency using three criteria: (a) staleness — how far past the refresh cycle, (b) usage — how frequently referenced in recent board materials, (c) volatility — how fast the underlying data changes. High-volatility, high-usage, stale files are top priority.

3. **Gather updated data (Days 3-8).** For each priority file, pull current data from primary sources:
   - Industry benchmarks: update from latest published reports, public company filings, and analyst research
   - Market trends: refresh with current quarter data points and forward-looking indicators
   - Competitive intelligence: update competitor actions, funding events, product launches, and market share estimates
   - Talent market data: refresh compensation benchmarks, hiring velocity, and labor market indicators
   - Financial benchmarks: update valuation multiples, fundraising terms, and exit data

4. **Update research files (Days 8-12).** Rewrite or augment each file with current data. For every data point, include the source and date. Remove or archive data points that are no longer relevant. Add new sections for emerging trends identified during the research phase. Maintain consistent formatting across all files.

5. **Cross-reference and validate (Days 12-14).** Check updated files against each other for consistency. Ensure that benchmarks referenced in multiple files use the same source and values. Validate that conclusions drawn from data still hold with updated numbers. Flag any data points where sources conflict.

6. **Update the change log (Day 14).** Document every file updated, the nature of the changes, new sources added, and data points retired. Include a summary of the most significant findings or shifts from the prior quarter.

7. **Distribute and communicate (Day 15).** Notify board members of the refresh completion. Highlight the 3-5 most significant data shifts that may affect board deliberations. Attach the change log and flag any files where updated data challenges prior assumptions or decisions.

## Frameworks to Apply
- **Single Source of Truth** — Every data point has one canonical source and version
- **Base Rates and Reference Class** — Refresh base rate data used in decision frameworks
- **Information Architecture** — Maintain consistent structure and findability across all files

## Checklists

### Quality Gate
- [ ] Every data/research file reviewed and staleness assessed
- [ ] All high-priority files updated with current data
- [ ] Every data point includes source and date
- [ ] Cross-file consistency verified (no conflicting numbers)
- [ ] Change log complete with summary of significant shifts
- [ ] Board notified of refresh completion and key findings
- [ ] Next quarter's refresh date scheduled

### Data Quality Standards
- [ ] No data point older than 6 months unless explicitly labeled as historical baseline
- [ ] At least two independent sources for critical benchmarks
- [ ] Confidence level noted for estimates and projections
- [ ] Methodology documented for any calculated or derived metrics

## Output
- Updated data and research files across all categories
- Quarterly change log with summary of significant shifts
- Board notification memo highlighting key data changes
- Staleness report for any files not refreshed this cycle with justification
- Updated refresh schedule for next quarter

## Handoffs
- Updated benchmarks feed into quarterly-board-review and annual-board-review
- Market data feeds into competitive-response-plan and strategic-diagnosis
- Financial benchmarks feed into fundraising-plan and unit-economics-review
- Talent data feeds into exec-hiring and compensation-review
- Research updates inform scenario-planning-session and annual-strategy-refresh

## Metrics
| Metric | Target | Measurement |
|---|---|---|
| Refresh completion rate | 100% of high-priority files updated | Inventory audit |
| Timeliness | Refresh completed within 15 business days of quarter start | Calendar tracking |
| Data currency | Zero files >6 months stale without justification | Staleness report |
| Source quality | All critical benchmarks have 2+ independent sources | Source audit |
| Board satisfaction | >4/5 on data quality and currency | Board survey |
| Change log delivery | Distributed within 1 business day of refresh completion | Distribution log |
