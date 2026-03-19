# Task: Update Board Scorecard

## Objective
Refresh the board scorecard dashboard with current data across all dimensions to ensure the board has an accurate real-time view of company health.

## Trigger
- Monthly for internal management use
- Quarterly for formal board reporting
- Immediately upon material metric changes

## Agents Involved
- **Lead:** Board Ops or CFO
- **Support:** Functional leaders for their metrics, Data or Analytics team
- **Advisory:** Board Chair for scorecard design decisions


## Agent Assignment
> Routing: see `config.yaml → routing → quarterly-board-review`

- **Lead:** governance-clerk (Simon Sinek)
- **Support:** board-chair (Board Chair), capital-allocator (Charlie Munger)

## Pre-Requisites
- [ ] Data sources identified and accessible for each metric
- [ ] Prior scorecard available as baseline
- [ ] Metric definitions and calculation methods documented
- [ ] RAG criteria defined

## Steps

1. **Step 1:** Collect current data for all financial metrics from the finance team ensuring figures are reconciled

2. **Step 2:** Collect current data for growth metrics from sales and marketing teams

3. **Step 3:** Collect product and technology metrics from engineering and product teams

4. **Step 4:** Collect people and culture metrics from the CHRO or People team

5. **Step 5:** Update strategic priority tracker with progress assessments from initiative owners

6. **Step 6:** Refresh the risk summary with current top 5 risks from the risk register

7. **Step 7:** Calculate RAG status for each dimension applying the defined criteria consistently

8. **Step 8:** Prepare commentary for any metric that changed RAG status or moved significantly since last update

## Frameworks to Apply
- **Operational Excellence:** Standardized processes with defined cadence and quality standards
- **Continuous Improvement:** Each cycle identifies and implements at least one process improvement
- **Single Source of Truth:** Every governance artifact has one canonical location and one owner

## Checklists

### Quality Gate
- [ ] All required updates completed within the defined cadence
- [ ] Data accuracy verified before distribution
- [ ] Stakeholders notified of material changes
- [ ] Process followed consistently (not ad hoc)
- [ ] Feedback collected and incorporated into process improvement
- [ ] Documentation current and accessible

## Output
- Updated board scorecard with current metrics
- RAG status updates with commentary
- Trend indicators
- Metric change highlights

## Handoffs
- Scorecard feeds into quarterly board review package
- RAG status changes may trigger board communication
- Metric trends inform strategic-diagnosis
- Scorecard is a key input to meeting-prep

## Metrics
| Metric | Target | Measurement |
|---|---|---|
| Cadence compliance | 100% of updates completed on schedule | Calendar tracking |
| Data accuracy | Zero material corrections required post-distribution | Error tracking |
| Stakeholder satisfaction | >4/5 from board and management | Periodic survey |
| Process efficiency | Continuous improvement in time-per-update | Time tracking |
| Information currency | All governance artifacts updated within defined windows | Staleness audit |
