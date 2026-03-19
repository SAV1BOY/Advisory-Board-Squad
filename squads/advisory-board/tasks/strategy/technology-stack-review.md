# Task: Technology Stack Review

## Objective
Conduct a strategic review of the company's technology stack to ensure it supports current operations, future growth, and competitive differentiation. Identify technical debt, scalability risks, security concerns, and investment priorities.

## Trigger
- Annual technology review as part of the strategic planning cycle
- Scalability concerns emerging from growth trajectory
- Major security incident or vulnerability discovery
- Evaluation of build vs. buy for a significant capability
- Technology-driven competitive threat
- Post-acquisition technology integration planning

## Agents Involved
- **Lead:** CTO or VP Engineering
- **Support:** Engineering leads, DevOps, Security, Product, Data teams
- **Advisory:** Board members with technology expertise


## Agent Assignment
> Routing: see `config.yaml → routing → product-strategy-review`

- **Lead:** strategic-advisor (Peter Thiel)
- **Support:** simplicity-czar (Derek Sivers), risk-sentinel (Ray Dalio)
- **Review:** board-chair (Board Chair)

## Pre-Requisites
- [ ] Current architecture documentation up to date
- [ ] Infrastructure cost data available (cloud spend, licensing, tooling)
- [ ] Performance and reliability metrics current (uptime, latency, error rates)
- [ ] Security audit findings current
- [ ] Technical debt inventory maintained
- [ ] Engineering team capacity and allocation data available

## Steps

1. **Architecture Assessment (Days 1-5)**
   - Document the current technology stack — infrastructure, frameworks, databases, third-party services
   - Map system dependencies and identify single points of failure
   - Assess architecture against current and projected scale requirements (2x, 5x, 10x)
   - Evaluate alignment between architecture and product roadmap
   - Review vendor lock-in risks and open-source dependencies

2. **Technical Debt and Quality Assessment (Days 5-10)**
   - Inventory known technical debt — categorize by severity and impact on velocity
   - Measure engineering velocity trends — is tech debt slowing the team?
   - Assess code quality metrics — test coverage, deployment frequency, change failure rate
   - Estimate the cost of deferred maintenance vs. proactive remediation
   - Prioritize tech debt items by business impact

3. **Security and Compliance Review (Days 8-12)**
   - Review security posture — penetration test results, vulnerability scan findings
   - Assess compliance status against applicable standards (SOC 2, GDPR, HIPAA, etc.)
   - Evaluate data protection practices — encryption, access controls, backup/recovery
   - Review third-party risk — vendor security assessments, supply chain vulnerabilities
   - Identify gaps between current posture and industry best practices

4. **Cost and Efficiency Analysis (Days 10-15)**
   - Analyze infrastructure costs — trend, optimization opportunities, cost per unit
   - Evaluate tooling and licensing spend — utilization, redundancy, consolidation opportunities
   - Benchmark infrastructure costs against industry peers (cost as % of revenue)
   - Identify specific cost reduction opportunities with estimated savings

5. **Strategic Technology Decisions (Days 15-20)**
   - Identify technology investments required to support the strategic plan
   - Evaluate build vs. buy decisions for key capabilities
   - Assess emerging technologies relevant to the business (AI/ML, new platforms, etc.)
   - Develop a technology roadmap aligned with business priorities
   - Prepare investment recommendations with cost, timeline, and expected impact

6. **Board Presentation (Days 20-25)**
   - Prepare a technology review summary for the board
   - Highlight strategic technology decisions requiring board input
   - Present investment recommendations and trade-offs
   - Capture board direction on technology priorities

## Frameworks to Apply
- **DORA Metrics:** Deployment frequency, lead time, change failure rate, MTTR
- **Technology Radar:** Assess, trial, adopt, hold categorization for technologies
- **Build vs. Buy Matrix:** Decision framework for capability sourcing
- **Scalability Assessment:** Evaluate each component against growth projections

## Checklists

### Quality Gate
- [ ] Architecture documentation is current and complete
- [ ] Technical debt is quantified by business impact, not just engineering opinion
- [ ] Security posture assessed against a recognized framework
- [ ] Infrastructure costs benchmarked and optimization opportunities identified
- [ ] Technology roadmap aligns with business strategic priorities
- [ ] Investment recommendations include cost, timeline, and success metrics
- [ ] Board has visibility into strategic technology risks and decisions

## Output
- Technology stack assessment report
- Technical debt prioritized backlog with business impact
- Security posture summary
- Infrastructure cost analysis and optimization plan
- Technology roadmap and investment recommendations
- Board technology briefing

## Handoffs
- Investment recommendations feed into capital-allocation-review and budget-review tasks
- Security findings feed into risk-register-update and cyber-and-fraud-gate tasks
- Scalability concerns feed into product-strategy-review
- Hiring needs feed into exec-hiring and team-health-check tasks
- Technology moat assessment feeds into moat-review task

## Metrics
| Metric | Target | Measurement |
|---|---|---|
| System uptime | >[%] (e.g., 99.9%) | Monitoring tools |
| Deployment frequency | [Target cadence] | DORA metrics |
| Infrastructure cost as % of revenue | <[%] | Financial reporting |
| Critical vulnerabilities open | 0 beyond SLA | Security dashboard |
| Technical debt velocity impact | Debt remediation improving velocity quarter-over-quarter | Engineering metrics |
