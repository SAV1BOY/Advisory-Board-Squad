# Naming Conventions

## Purpose

Consistent naming makes files findable, version-trackable, and self-documenting. Every file in the Advisory Board squad follows these conventions.

## File Naming

### General Rules
- **Lowercase only.** No uppercase letters in file names.
- **Kebab-case.** Words separated by hyphens: `board-charter.md`, not `board_charter.md` or `BoardCharter.md`.
- **No spaces.** Ever.
- **Descriptive names.** The file name should tell you what's inside without opening it.
- **File extension always included.** `.md` for Markdown documents.

### By Directory

#### workflows/
Pattern: `NN-descriptive-name.md`
- Two-digit number prefix for ordering.
- Descriptive name in kebab-case.
- Examples: `00-board-setup-flow.md`, `07-crisis-response-72h.md`, `18-m-and-a-evaluation-flow.md`.

#### voice/tone-profiles/
Pattern: `descriptive-name.md`
- Name reflects the tone's character.
- Examples: `radical-clarity.md`, `calm-precision.md`, `courageous-empathy.md`.

#### voice/language-guides/
Pattern: `descriptive-name.md`
- Name reflects the communication context.
- Examples: `memo-writing-style.md`, `meeting-facilitation.md`, `crisis-communication-language.md`.

#### voice/calibration/
Pattern: `descriptive-name.md`
- Name reflects the calibration concept.
- Examples: `truth-vs-nice.md`, `dissent-and-commit.md`, `believability-weights.md`.

#### voice/channels/
Pattern: `descriptive-name.md`
- Name reflects the communication channel.
- Examples: `board-email.md`, `exec-summary.md`, `crisis-statement.md`.

#### phrases/
Pattern: `descriptive-name.md`
- Name reflects the phrase category.
- Examples: `decision-prompts.md`, `contrarian-questions.md`, `words-to-avoid-board.md`.

#### docs/
Pattern: `descriptive-name.md`
- Name reflects the document topic.
- Examples: `board-charter.md`, `decision-policy.md`, `getting-started.md`.

#### templates/
Pattern: `descriptive-name-template.md`
- Always ends with `-template`.
- Examples: `pre-read-template.md`, `decision-log-entry-template.md`, `meeting-minutes-template.md`.

#### archive/
Pattern: `YYYY-MM-DD-descriptive-name.md` or organized in date-based subdirectories.
- Date prefix for chronological ordering.
- Examples: `archive/meetings/2026-03-25/minutes.md`, `archive/decisions/2026-Q1-review.md`.

#### data/
Pattern: `descriptive-name.ext`
- Extension matches the data format (`.csv`, `.json`, `.md`).
- Date prefix if the data is periodic: `YYYY-MM-metric-name.csv`.

## Document Internal Conventions

### Headers
- `# Title` — One Level 1 header per document (the document title).
- `## Section` — Major sections.
- `### Subsection` — Subsections within a section.
- Do not skip levels (no `###` directly under `#`).

### Version References
When referencing a specific version: `v1.0`, `v1.1`, `v2.0`.
- Major version change: structural or substantive revision.
- Minor version change: corrections, clarifications, additions.

### Cross-References
Use relative paths from the squad root:
- `docs/decision-policy.md`
- `workflows/07-crisis-response-72h.md`
- `voice/tone-profiles/radical-clarity.md`

### Dates
- Always `YYYY-MM-DD` format.
- In text: "March 25, 2026" for readability.
- In file names and metadata: `2026-03-25`.

### Decision IDs
Pattern: `YYYY-MM-DD-NNN`
- Date of the decision plus a sequential number for that day.
- Example: `2026-03-25-001`, `2026-03-25-002`.

### Meeting References
Pattern: `YYYY-MM-DD-meeting-type`
- Example: `2026-03-25-quarterly`, `2026-04-15-monthly-checkin`, `2026-05-03-crisis`.

## Anti-Patterns

| Anti-Pattern | Problem | Convention |
|---|---|---|
| `Board Charter v3 FINAL (2).md` | Unclear versioning, untraceable | `board-charter.md` with version tracked in the document |
| `notes_from_johns_meeting.md` | Personal, not team-accessible | `2026-03-25-quarterly-minutes.md` |
| `New Folder/stuff/ideas.md` | Meaningless directory and file names | Follow the directory structure and naming pattern |
| Mixed case: `BoardCharter.md` | Inconsistent, OS-sensitive | Lowercase always: `board-charter.md` |
| No extension: `board-charter` | File type unclear | Always include `.md` |
