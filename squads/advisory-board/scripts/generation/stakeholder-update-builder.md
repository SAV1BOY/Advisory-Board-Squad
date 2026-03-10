# Stakeholder Update Builder

## Purpose

Generates tailored stakeholder updates from board meeting outputs, decision records, and initiative progress. Different stakeholders need different messages — investors want financial metrics and strategic progress, employees want clarity and direction, customers want reliability and roadmap. This script routes the right information to the right audience in the right format.

## Input

- **Meeting minutes:** Output from minutes-extractor.md.
- **Decision records:** New entries in decision-registry.yaml.
- **Metrics dashboard:** Current state of all tracked metrics.
- **Stakeholder registry:** Stakeholder list with types and communication preferences from data/registries/stakeholder-registry.yaml.
- **Sensitivity classification:** Which information is public, internal-only, or restricted.

## Process Steps

1. **Identify stakeholder audiences:** From the stakeholder registry, determine which groups need updates based on decisions made and topics discussed.

2. **Classify information sensitivity:** For each piece of information from the meeting:
   - Public: Can be shared externally
   - Internal: Shared with all employees but not externally
   - Restricted: Shared only with named individuals (board, specific executives)
   - Confidential: Legal or HR matters with strict distribution

3. **Generate audience-specific updates:**
   - **Board/Investor update:** Financial metrics, strategic decisions, risk register changes, fundraising progress, key hires. Tone: data-driven, forward-looking.
   - **Leadership team update:** Decisions made, action items assigned, strategic context, discussion summaries. Tone: actionable, context-rich.
   - **All-company update:** Strategic direction, wins, challenges (appropriately framed), upcoming changes that affect everyone. Tone: transparent, motivating.
   - **Customer-facing update:** Product roadmap changes, service improvements, relevant company milestones. Tone: confident, value-focused.
   - **Partner update:** Partnership-relevant decisions, integration changes, joint initiative progress. Tone: collaborative, specific.

4. **Apply communication principles:**
   - Lead with what matters to the audience, not what matters to you
   - Be honest about challenges without creating unnecessary anxiety
   - Every update should answer: what happened, what it means for you, what happens next
   - Decisions should be presented as final, not tentative (per dissent-and-commit pattern)
   - Avoid corporate language — be direct and human

5. **Format for channel:** Adapt the content to the delivery channel:
   - Email: structured with headers and bullet points
   - Slack/chat: concise with links to details
   - All-hands: narrative format with Q&A preparation
   - Formal report: complete with data tables and appendices

6. **Review and approve:** Route each update to the appropriate approver before distribution.

## Output

- Audience-specific update documents (one per stakeholder group that needs an update).
- Distribution schedule (who gets what, when, through what channel).
- Q&A preparation document for anticipated questions.
- Sensitivity-checked distribution matrix.

## Automation Notes

- Triggered after every board meeting and significant decision session.
- Investor updates follow a standardized monthly template that auto-populates with latest metrics.
- All-company updates should go out within 48 hours of board meetings to prevent rumor cycles.
- Integrates with all registry data for automated metric insertion.
- Maintain an archive of past updates for consistency tracking.
