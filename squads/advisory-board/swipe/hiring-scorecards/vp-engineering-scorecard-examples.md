# VP Engineering Scorecard Examples

## VP Engineering Evaluation Dimensions

### Engineering Execution (Weight: 25%)
- Delivers product roadmap on time with acceptable quality and minimal unplanned work
- Establishes release cadence and deployment practices that balance speed with reliability
- Manages technical debt strategically: quantifies it, allocates capacity, prevents accumulation
- Translates business priorities into engineering plans with clear milestones and dependencies
- **Rating scale:** 1 (consistently misses deadlines, quality issues in production) to 5 (predictable delivery cadence with high quality and continuous improvement)

### Team Building and Engineering Culture (Weight: 25%)
- Recruits and retains top engineering talent at all levels (IC and management)
- Builds an engineering culture of ownership, craftsmanship, and collaboration
- Develops engineering managers who can run teams independently
- Maintains a healthy engineering org: low regrettable attrition, high engagement scores, strong internal mobility
- **Rating scale:** 1 (high attrition, toxic culture, can't hire) to 5 (engineering team is a competitive advantage and recruiting magnet)

### Technical Architecture and Strategy (Weight: 20%)
- Ensures the technical architecture supports current scale and anticipated growth (10x headroom)
- Makes sound build-vs-buy decisions with clear reasoning and ROI analysis
- Drives platform reliability: uptime, incident response, disaster recovery
- Manages security posture and compliance requirements without slowing development velocity
- **Rating scale:** 1 (architecture is a bottleneck, frequent outages) to 5 (scalable, secure, and resilient architecture with clear technical vision)

### Product Partnership (Weight: 15%)
- Partners effectively with product management to shape roadmap priorities
- Provides accurate effort estimates and communicates tradeoffs clearly
- Proposes technical solutions that unlock product capabilities beyond what product imagined
- Pushes back constructively when product requests are technically unsound or poorly prioritized
- **Rating scale:** 1 (adversarial with product, says "no" without alternatives) to 5 (trusted partner who shapes product strategy through technical insight)

### Organizational Design and Process (Weight: 10%)
- Designs team topology that minimizes coordination overhead (aligned to architecture)
- Implements engineering processes that scale: code review, testing, on-call, incident management
- Establishes metrics and reporting that provide visibility without micromanagement
- Manages engineering budget (headcount, infrastructure, tools) within targets
- **Rating scale:** 1 (no process, chaotic coordination) to 5 (well-designed teams and processes that scale smoothly)

### CTO/VP Eng Boundary Management (Weight: 5%)
- Clear division of responsibilities with CTO (if both roles exist): VP Eng owns delivery and people, CTO owns technical vision and architecture
- Maintains productive working relationship with CTO without territorial conflict
- If CTO role does not exist, takes ownership of technical strategy alongside delivery
- **Rating scale:** 1 (role confusion, duplicated effort) to 5 (complementary partnership with clear boundaries)

## Stage-Specific VP Eng Criteria

### Early-Stage (10-30 engineers)
- Hands-on coding ability: the VP Eng should still be able to contribute code when needed
- Hiring the first engineering managers and establishing engineering culture
- Building CI/CD pipeline, testing infrastructure, and on-call processes from scratch
- Managing the transition from "everyone does everything" to functional specialization

### Growth-Stage (30-100 engineers)
- Scaling the engineering org through management layers without losing velocity
- Establishing architecture review and technical governance processes
- Managing multiple product teams with competing priorities and shared infrastructure
- Building platform and infrastructure teams to support product squads

### Late-Stage (100+ engineers)
- Multi-site engineering operations and distributed team coordination
- Engineering metrics and productivity measurement at organizational scale
- Technical due diligence readiness for IPO or M&A scenarios
- Compliance and audit-ready engineering practices (SOX, SOC 2)

## Interview Evaluation Framework

### Technical Depth
- Can they discuss architecture decisions at a level that earns engineering team respect?
- Do they understand the technology stack and its constraints?

### Management Philosophy
- How do they handle underperforming engineers? Ask for specific examples.
- How do they structure 1:1s, performance reviews, and career development?

### Prioritization Under Pressure
- Present a scenario with competing demands (product deadline, technical debt, outage, key engineer leaving). How do they triage?

### Communication
- Can they explain technical decisions to non-technical board members clearly?
- How do they communicate bad news (delays, outages, departures)?

## Board Application
- Require quarterly engineering health metrics: deployment frequency, lead time, change failure rate, mean time to recovery
- Evaluate whether the VP Eng and CTO roles are clearly defined — role ambiguity is the top cause of executive departure in engineering
- Ask: "What is the ratio of new feature development to maintenance to technical debt reduction?" A healthy ratio is roughly 70/20/10
- Monitor engineering attrition as a leading indicator — engineers leave before problems become visible to the board
- Challenge any engineering plan that does not include explicit capacity for technical debt and platform investment
