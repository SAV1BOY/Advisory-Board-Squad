# Minutes Extractor

## Purpose

Extracts structured meeting minutes from raw meeting content (transcripts, notes, recordings, chat logs). Transforms unstructured meeting output into the standard meeting block format from `lib/components/meeting-blocks.md`, ensuring decisions, action items, and key discussions are captured with precision.

## Input

- **Meeting transcript or notes:** Raw text from the meeting — can be auto-transcribed, hand-written, or a combination.
- **Meeting agenda:** The planned agenda with time allocations and desired outcomes.
- **Attendee list:** Who was present and their roles.
- **Meeting type:** Classification per `lib/taxonomies/meeting-types.md`.

## Process Steps

1. **Parse meeting header:** Extract or confirm: meeting type, date/time, chair, scribe, attendees present, quorum status.

2. **Match to agenda:** Align the raw content with the planned agenda items. Identify which items were covered, which were skipped, and which emerged unexpectedly.

3. **Extract decisions:** Scan for decision language ("we decided," "approved," "agreed to," "will proceed with"). For each decision found:
   - Formulate a clear decision statement
   - Identify the method used (vote, consensus, conviction)
   - Capture any dissent (look for "disagreed," "concerned about," "alternative view")
   - Assign a confidence level if discussed
   - Generate a decision ID for the decision registry

4. **Extract action items:** Scan for commitment language ("will do," "by next week," "owner is," "action item"). For each action found:
   - Extract the task description (verb + noun)
   - Identify the owner (single person)
   - Extract the due date (convert relative dates to absolute)
   - Note any dependencies
   - Assign an action ID

5. **Extract key discussion points:** For each agenda item, summarize:
   - The core question or topic
   - Key positions expressed and by whom
   - Important data or facts referenced
   - Open questions that were not resolved

6. **Generate meeting health check:** Using `lib/utilities/meeting-effectiveness-rubric.md`, assess:
   - Were pre-reads consumed? (inferred from discussion quality)
   - Did the meeting stay on time? (compare agenda to actual coverage)
   - Were decisions made on [DECIDE] items?
   - Did multiple voices contribute?

7. **Format output:** Compile all extracted elements into the standard meeting blocks format.

## Output

- Structured meeting minutes in markdown following meeting-blocks.md format.
- List of decisions for insertion into decision-registry.yaml.
- List of action items for insertion into action-item-tracker.md.
- Meeting health check score.
- List of unresolved items requiring follow-up.

## Automation Notes

- Best used within 24 hours of the meeting while context is fresh.
- If auto-transcription is used, human review of decision statements is critical — transcription errors in decisions are high-cost.
- Integrates with decision-log-updater.md and action-item-tracker.md for automatic registry updates.
- Output feeds into stakeholder-update-builder.md for post-meeting communications.
- For recurring meetings, compare minutes format across sessions for consistency.
