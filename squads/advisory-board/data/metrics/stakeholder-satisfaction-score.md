# Stakeholder Satisfaction Score

## Definition

A composite metric measuring the satisfaction of all key stakeholder groups with the company's performance, governance, communication, and trajectory. Stakeholder groups include: investors, employees, customers, partners, and the advisory board itself. This metric provides the board with a holistic view of organizational health beyond financial performance — a company can have strong revenue growth but deteriorating stakeholder relationships that will eventually constrain growth, fundraising, or talent acquisition.

## Formula

```
Stakeholder Satisfaction Score = Weighted average across stakeholder groups:

  - Customer Satisfaction (30%): NPS score normalized to 0-100 scale
    (NPS -100 = 0, NPS 0 = 50, NPS +100 = 100)
  - Employee Satisfaction (25%): Employee engagement score (0-100)
    from employee-engagement-score.md
  - Investor Satisfaction (20%): Investor confidence survey (0-100)
    Dimensions: communication quality, strategic progress, governance quality, trust in leadership
  - Partner Satisfaction (15%): Partner NPS or satisfaction survey (0-100)
    Dimensions: collaboration quality, mutual value creation, communication, reliability
  - Board Satisfaction (10%): Advisory board self-assessment (0-100)
    from board-effectiveness-score.md (self-reported dimension)

Composite = (Customer x 0.30) + (Employee x 0.25) + (Investor x 0.20) + (Partner x 0.15) + (Board x 0.10)
```

## Target Range

| Rating | Score | Status |
|--------|-------|--------|
| Exceptional | 80-100 | All stakeholder groups are highly satisfied; strong foundation for growth |
| Strong | 65-79 | Most groups satisfied; address any below-60 sub-scores |
| Moderate | 50-64 | Mixed satisfaction; multiple groups need attention |
| Weak | 35-49 | Significant dissatisfaction in 2+ groups; board intervention required |
| Critical | <35 | Broad stakeholder dissatisfaction; existential risk to company |

**Target: Composite score above 65. No individual stakeholder group below 50. Quarter-over-quarter improvement on the lowest-scoring group.**

## Data Sources

- Customer NPS surveys (quarterly or transactional)
- Employee engagement platform (semi-annual full survey, monthly pulse)
- Investor feedback (annual structured survey + quarterly informal pulse)
- Partner satisfaction surveys (annual or semi-annual)
- Board self-assessment (from board-effectiveness-score.md process)
- Glassdoor, G2, or TrustPilot reviews (external sentiment validation)

## Frequency

- **Customer satisfaction:** Quarterly (NPS survey)
- **Employee satisfaction:** Semi-annually (full survey) with monthly pulse
- **Investor satisfaction:** Annually (structured) with quarterly informal check-in
- **Partner satisfaction:** Annually
- **Composite score calculation:** Semi-annually
- **Board reporting:** Semi-annually — present composite and per-group scores with trends
- **Trend monitoring:** Quarterly — flag any group showing >10-point decline

## Owner

- **Primary:** CEO (accountable for all stakeholder relationships)
- **Board sponsor:** Board chair
- **Data collection by group:**
  - Customer: VP Customer Success
  - Employee: VP People
  - Investor: CEO / CFO
  - Partner: VP Business Development
  - Board: Board Secretary
- **Data steward:** Chief of Staff or Strategy team (aggregation and reporting)

## Related Metrics

- `data/metrics/customer-health-score.md` — detailed customer-level health data
- `data/metrics/employee-engagement-score.md` — detailed employee engagement data
- `data/metrics/board-effectiveness-score.md` — board-level effectiveness assessment
- `data/metrics/advisor-contribution-score.md` — individual advisor value measurement
- `data/research/culture-and-performance-correlation.md` — research linking stakeholder satisfaction to performance
