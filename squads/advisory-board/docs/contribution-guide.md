# Contribution Guide

## Purpose

This guide explains how to propose changes, add new content, or update existing materials in the Advisory Board squad. A consistent contribution process ensures quality, traceability, and alignment.

## What Can Be Contributed

### New Content
- New workflows for scenarios not currently covered.
- New phrase libraries for emerging board needs.
- New voice profiles or channel guides.
- New frameworks or reference materials.
- New templates for recurring activities.

### Updates to Existing Content
- Corrections (factual errors, broken references).
- Enhancements (additional examples, clarified guidance).
- Revisions (structural changes based on experience or feedback).
- Deprecations (marking content as outdated with a replacement).

## Contribution Process

### Step 1: Identify the Need
Before creating new content, check:
- Does a similar file already exist? (Search `docs/`, `workflows/`, `phrases/`, `voice/`.)
- Can the need be met by updating an existing file?
- Is this need recurring enough to warrant a permanent addition?

If an existing file covers the need, update it. Only create new files for genuinely new topics.

### Step 2: Draft the Content
- Follow the naming conventions in `docs/naming-conventions.md`.
- Follow the relevant format:
  - Workflows: Overview, Trigger, Agents, Phases, Quality Gates, Outputs, Timeline, Metrics, Common Failures.
  - Voice files: Format depends on the voice subdirectory (tone profiles, language guides, calibration, channels).
  - Phrases: 15-30 phrases with context for when to use each.
  - Docs: Clear structure with purpose, content, and cross-references.
- Write in the board's voice: direct, evidence-based, actionable.
- No placeholders. Every file must be complete and usable on submission.

### Step 3: Review
All contributions require review before being added:

| Content Type | Reviewer |
|---|---|
| Workflows | Board-Chair + Strategy-Analyst |
| Voice (tone, language, calibration) | Board-Chair + Culture-Guardian |
| Phrases | Board-Chair |
| Docs (policies) | Board-Chair + Governance-Ops |
| Docs (guides) | Board-Chair |
| Templates | Governance-Ops |
| Frameworks | Strategy-Analyst |

### Step 4: Approval
- Reviewer approves, requests changes, or rejects.
- If changes requested: revise and resubmit.
- If rejected: documented reason provided. Content may be salvaged as a reference note in `reference/`.

### Step 5: Integration
Once approved:
1. Add the file to the appropriate directory.
2. Update any indexes or guides that reference the content type (e.g., `docs/workflow-guide.md` for new workflows).
3. Add an entry to `docs/changelog.md`.
4. If the new content affects existing workflows or policies, update those cross-references.

## Quality Standards

All contributions must meet these standards:

### Completeness
- No placeholder text ("TBD", "TODO", "add later").
- All sections of the required format are filled.
- Cross-references point to real, existing files.

### Accuracy
- Facts are verifiable.
- Frameworks are correctly described.
- Process steps are in the right order and logically complete.

### Consistency
- Follows naming conventions.
- Uses the same terminology as the rest of the squad (see `docs/glossary.md`).
- Formatting matches peer files in the same directory.

### Voice
- Written in active voice.
- Direct and specific.
- No corporate jargon (see `phrases/words-to-avoid-board.md`).

## Updating Existing Content

### Minor Updates (corrections, typos, small additions)
- Make the change directly.
- Add a changelog entry if the change is substantive.
- No formal review required for typos and formatting fixes.

### Major Updates (structural changes, new sections, policy changes)
- Draft the update.
- Submit for review (same reviewer as the content type).
- Add a changelog entry with the date, description, and reason.

### Deprecation
When content is no longer relevant:
1. Do not delete the file.
2. Add a deprecation notice at the top: "DEPRECATED: This file has been superseded by [new file]. Retained for historical reference."
3. Move to `archive/` if it clutters the active directory.
4. Update all cross-references.
5. Add a changelog entry.

## Changelog Protocol

Every substantive change is recorded in `docs/changelog.md`:

```
## [YYYY-MM-DD] — [Brief description]
- **Type:** [Added / Updated / Deprecated / Fixed]
- **File:** [path/to/file.md]
- **Description:** [What changed and why]
- **Author:** [Who made the change]
- **Reviewer:** [Who approved it]
```
