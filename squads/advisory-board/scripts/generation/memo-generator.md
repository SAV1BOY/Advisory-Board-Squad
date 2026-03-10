# Memo Generator

## Purpose

Generates structured decision memos from raw inputs (meeting notes, Slack threads, email chains, verbal briefs). Ensures every decision memo follows the standard block structure from `lib/components/decision-memo-blocks.md` and captures all required fields regardless of how messy the source material is.

## Input

- **Decision trigger:** A brief description of the decision need (can be a sentence, a Slack message, or a meeting note).
- **Context documents:** Any supporting materials — financial data, market research, customer feedback, competitive analysis.
- **Stakeholder input:** Positions from relevant stakeholders (can be interview notes, emails, or meeting recordings).
- **Decision type classification:** The submitter's initial assessment of reversibility and scope (will be validated).
- **Deadline:** When the decision must be made.

## Process Steps

1. **Validate decision type:** Classify the decision using `lib/taxonomies/decision-types.md`. Confirm reversibility (one-way/two-way door), scope (strategic/operational/tactical), and urgency.

2. **Extract context frame:** From input materials, construct Block 1 (Context Frame):
   - Derive decision title (verb + noun format)
   - Identify the trigger event
   - Determine time horizon and stakeholders affected
   - If information is missing, flag gaps rather than fabricate

3. **Generate option set:** Construct Block 2 (Option Set):
   - Extract proposed options from input materials
   - Always include the null option ("do nothing" or "defer")
   - For each option, estimate: expected value range, key assumptions, reversibility
   - If fewer than 2 genuine options exist, flag this — a decision with only one option is not a decision

4. **Build analysis engine:** Construct Block 3 (Analysis Engine):
   - Select appropriate sub-blocks based on decision type and available data
   - For financial decisions: link to or generate EV calculation per `lib/utilities/ev-calculator.md`
   - For strategic decisions: generate scenario table per `lib/utilities/scenario-table.md`
   - For all decisions: extract top risks from context and link to risk types
   - Run incentive alignment check per `lib/utilities/incentive-map.md`

5. **Draft recommendation:** Construct Block 4 (Recommendation):
   - Synthesize analysis into a recommended option with rationale
   - Assign confidence level based on information quality and analysis strength
   - Identify the pre-mortem flag (most likely failure mode)
   - Define kill criteria (observable reversal triggers)

6. **Prepare dissent capture:** Construct Block 5 (Dissent & Commit Record):
   - Extract any dissenting views from stakeholder input
   - If no dissent exists in the inputs, flag this — unanimous agreement on high-stakes decisions should be investigated
   - Pre-format the dissent capture template for completion during the decision meeting

7. **Draft action cascade:** Construct Block 6 (Action Cascade):
   - From the recommendation, derive immediate, short-term, and medium-term actions
   - Pre-assign owners based on stakeholder roles
   - Draft communication plan
   - Pre-generate decision registry entry for `data/registries/decision-registry.yaml`

8. **Quality check:** Validate the draft memo against `lib/utilities/decision-quality-rubric.md`:
   - Verify all six dimensions are addressed
   - Flag any dimension scoring below 3
   - Recommend specific improvements

## Output

- A complete decision memo in markdown format following the six-block structure.
- A decision registry entry pre-formatted for YAML insertion.
- A quality check summary with improvement recommendations.
- A list of information gaps that should be resolved before the decision meeting.

## Automation Notes

- Can be triggered by dropping materials into a designated folder or channel.
- Integrates with meeting notes (from minutes-extractor.md) to pull decision context.
- Output feeds into pre-read-pack-builder.md for distribution to decision-meeting attendees.
- After the decision meeting, the decision-log-updater.md script finalizes the registry entry.
- Estimated generation time: 15-30 minutes depending on input complexity.
- Human review is mandatory before distribution — this script generates a draft, not a final document.
