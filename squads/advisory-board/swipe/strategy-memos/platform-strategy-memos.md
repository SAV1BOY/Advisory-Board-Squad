# Platform Strategy Memos — Swipe File

## Overview
The decision to become a platform — opening your product to third-party developers, partners, or complementary services — is one of the most consequential strategic choices a company can make. Done well, it creates network effects, increases switching costs, and expands the value proposition beyond what any single company could build. Done poorly, it fragments the product, confuses the customer, and creates competitors. These memos illustrate rigorous platform thinking.

## Platform Strategy Memo Template

### Section 1: Platform Thesis
- **Why platform, why now?** What has changed in the market, product, or customer base that makes a platform strategy viable?
- **What is the core value we are platforming?** (Data, distribution, workflow, infrastructure, identity)
- **Who are the target developers/partners?** What do they want to build that we cannot or should not build ourselves?
- **What is the end-state vision?** Describe the ecosystem at maturity — who participates, what do they build, how do customers benefit?

### Section 2: Platform Economics
- **Value creation:** How does the platform create value that does not exist without it?
- **Value capture:** How does the company monetize the platform? (Revenue share, API fees, marketplace commission, premium tier, data)
- **Developer economics:** Can third-party developers build sustainable businesses on this platform? If not, they will not invest.
- **Subsidy model:** In the early phase, who do we subsidize (developers or users) to bootstrap the ecosystem?

### Section 3: Platform Architecture
- **API strategy:** What capabilities are exposed? What remains proprietary?
- **Extension model:** Plugins, apps, integrations, or white-label?
- **Data sharing:** What data do partners access? What do they contribute back? Privacy implications?
- **Quality control:** How do we maintain product quality when third parties extend the experience?

### Section 4: Go-to-Platform Strategy
- **Seed the ecosystem:** What are the 5-10 integrations that must exist at launch to demonstrate value?
- **Developer experience:** What tools, documentation, sandboxes, and support do developers need?
- **Distribution:** How do customers discover and install platform extensions?
- **Incentive structure:** Developer grants, co-marketing, revenue share tiers, certification programs

### Section 5: Risks and Governance
- **Platform risk:** What if a popular extension fails or behaves badly? Impact on core brand?
- **Competition risk:** What prevents a successful partner from building a competing platform?
- **Dependency risk:** What if developers build critical functionality and then leave the platform?
- **Governance model:** Who decides what gets built, what gets approved, what gets removed?

## Example: Vertical SaaS Company Launching App Marketplace

**Thesis:** Our restaurant management platform serves 8,000 locations. Customers request integrations with 50+ tools (POS, delivery, accounting, staffing). Building all integrations in-house is not scalable. A marketplace lets partners build integrations while we maintain the core platform.

**Economics:** Partners build and maintain integrations. We take 20% of subscription revenue for distribution. Partners access our install base; we expand our value proposition without engineering cost.

**Architecture:** REST API exposing menu, order, and reporting data. Webhook system for real-time events. Sandboxed execution environment so partner code cannot destabilize the core platform.

**Go-to-market:** Launch with 10 curated partners in the most-requested categories. Provide $50K development grants to the first 10. Co-market the marketplace to our install base. Measure: installations per customer, retention lift for customers with 3+ integrations.

**Kill criteria:** If after 12 months fewer than 20% of customers have installed at least one extension, the platform is not providing sufficient value. Reevaluate strategy.

## Platform Decision Framework

| Factor | Build In-House | Platform / Ecosystem |
|--------|---------------|---------------------|
| Core differentiation | Build it yourself | Never platform your core |
| Long tail of use cases | Cannot justify the investment | Perfect for platform |
| Speed of innovation needed | Slower (internal roadmap) | Faster (many builders) |
| Quality control requirements | Easier to maintain | Requires governance investment |
| Revenue model | Direct | Indirect (take rate, increased retention) |
| Competitive moat | Features | Ecosystem and switching costs |

## Board Application
- Platform decisions are irreversible at scale — once developers invest, retreating destroys trust and value
- Challenge the platform thesis: is there genuine demand from developers, or is this a "build it and they will come" bet?
- Insist on developer economics analysis: if developers cannot make money, the ecosystem will not sustain
- Monitor platform health metrics: number of active developers, extension install rates, customer retention with/without extensions
- Ask: "What is our core, and what is our complement?" Platform strategy requires knowing what you will never let others build

## Cross-References
- See `checklists/product/product-differentiation-durability.md` for moat analysis
- See `swipe/strategy-memos/market-entry-memos.md` for market expansion context
- See `checklists/innovation/build-vs-buy-vs-partner.md` for build/buy/partner decisions
