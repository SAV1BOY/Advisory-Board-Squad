# Governance Blocks

## Purpose

Reusable structural blocks for composing governance documents — board charters, committee mandates, conflict of interest policies, delegation of authority frameworks, and compliance protocols. These blocks enforce governance rigor by separating authority from accountability, disclosure from enforcement, and policy from practice. They prevent the common failure mode of governance documents that exist on paper but have no operational mechanism.

## Structure

### Block 1 — Authority and Mandate

Defines the scope of authority for a governance body or role.

**Fields:**
- **Body/Role:** The governance entity being defined (board, committee, officer, or advisor).
- **Mandate:** One paragraph describing the purpose and scope of authority.
- **Delegated powers:** Specific decisions this body can make without further approval.
- **Reserved matters:** Decisions that require escalation to a higher authority (e.g., board approval for expenditures above a threshold).
- **Reporting line:** Who this body reports to and how frequently.
- **Term and renewal:** Duration of mandate and renewal mechanism.

### Block 2 — Composition and Qualification

Defines who serves and what qualifications are required.

**Fields:**
- **Membership criteria:** Required skills, experience, or independence standards.
- **Composition target:** Number of members, diversity targets, independence requirements.
- **Appointment process:** How members are nominated, evaluated, and approved.
- **Removal process:** Conditions and process for removing a member.
- **Skills matrix:** Required competencies mapped against current membership. Reference `lib/utilities/board-effectiveness-rubric.md`.
- **Onboarding requirements:** What new members must complete before assuming full responsibilities.

### Block 3 — Meeting Protocol

Defines how governance meetings are conducted.

**Fields:**
- **Cadence:** Frequency of regular meetings and process for calling special meetings.
- **Quorum:** Minimum attendance for valid deliberation and decision-making.
- **Agenda setting:** Who sets the agenda, when it is distributed, and how members add items.
- **Pre-read requirements:** Materials required, distribution timeline (minimum 5 business days), and format standards.
- **Decision-making method:** Consensus, majority vote, supermajority — specify for different decision types.
- **Minutes and records:** Who records, review process, retention policy, and access controls.
- **Executive session:** Standing provision for session without management present.

### Block 4 — Conflict of Interest

Defines disclosure and management of conflicts.

**Fields:**
- **Disclosure requirement:** When and how conflicts must be disclosed (proactive, before each meeting, and upon discovery).
- **Conflict categories:** Financial interests, competing board seats, related-party relationships, personal relationships with management.
- **Management protocols:** Recusal from discussion, recusal from vote, divestiture, or resignation depending on severity.
- **Disclosure register:** Where disclosures are recorded and who maintains the register.
- **Annual attestation:** Annual reconfirmation of all ongoing potential conflicts.
- **Breach consequences:** What happens when a conflict is not disclosed — ranging from formal warning to removal.

### Block 5 — Accountability and Evaluation

Defines how governance effectiveness is measured.

**Fields:**
- **Self-assessment:** Frequency and method of self-evaluation (reference `lib/utilities/board-effectiveness-rubric.md`).
- **External evaluation:** Frequency of independent governance review (recommended every 2-3 years).
- **Performance indicators:** Key metrics tracked (meeting attendance, pre-read completion, action item follow-through, decision quality).
- **Feedback mechanism:** How the CEO and management provide feedback to the governance body.
- **Improvement planning:** Process for translating evaluation results into governance improvement actions.
- **Public reporting:** What governance information is shared with stakeholders (investors, employees, regulators).

### Block 6 — Compliance and Risk Oversight

Defines the governance body's role in compliance and risk management.

**Fields:**
- **Regulatory obligations:** List of applicable regulations and the governance body's oversight responsibility for each.
- **Risk reporting:** What risk information the body receives, in what format, and how frequently.
- **Whistleblower protocol:** How concerns are escalated to the governance body, confidentiality protections, and investigation process.
- **Audit rights:** The body's authority to commission independent audits or investigations.
- **Insurance and indemnification:** D&O insurance coverage, indemnification provisions, and review cadence.
- **Crisis escalation:** Triggers and process for emergency governance sessions.

## Usage

1. **Block 1 + Block 2** form the foundation of any governance charter or mandate document.
2. **Block 3** should be established at the first meeting and reviewed annually.
3. **Block 4** should be completed by every member upon appointment and re-attested annually.
4. **Block 5** creates the governance improvement cycle — without evaluation, governance calcifies.
5. **Block 6** ensures the governance body fulfills its oversight obligations and is protected while doing so.

## Components

- References `lib/utilities/board-effectiveness-rubric.md` for evaluation criteria
- References `lib/taxonomies/decision-types.md` for reserved matter categorization
- References `lib/taxonomies/risk-types.md` for risk oversight framework
- References `lib/patterns/escalation-pattern.md` for crisis escalation protocols

## Related Patterns

- `lib/patterns/dissent-and-commit-pattern.md` — for managing disagreement within governance bodies
- `lib/patterns/delegation-pattern.md` — for structuring authority delegation
- `lib/components/meeting-blocks.md` — for meeting structure within governance sessions
- `data/research/governance-best-practices-2024.md` — current governance best practices for benchmarking
