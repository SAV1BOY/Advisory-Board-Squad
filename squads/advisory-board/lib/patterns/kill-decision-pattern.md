# Kill Decision Pattern

## Pattern Name

Kill Decision — structured process for terminating projects, products, partnerships, or initiatives that no longer justify continued investment.

## When to Use

- A project has consumed its allocated budget or time without meeting milestones.
- Market conditions have changed and the original thesis is invalidated.
- A better opportunity has emerged that competes for the same resources.
- The team has lost conviction but no one is willing to say it out loud.
- Sunk cost fallacy is visibly influencing continued investment.
- A periodic review reveals that the initiative is below the kill threshold defined at inception.

Do NOT use when:
- The initiative is on track and meeting milestones (impatience is not a kill trigger).
- Short-term metrics are disappointing but the long-term thesis remains intact and was always the stated timeframe.
- The initiative has not yet reached its first meaningful evaluation point.

## Structure

```
1. TRIGGER   → Identify the signal that puts the initiative on the kill list
2. ASSESS    → Evaluate the initiative against its original thesis and current reality
3. SEPARATE  → Distinguish sunk costs from forward-looking value
4. DECIDE    → Make the kill/continue/pivot call
5. EXECUTE   → Wind down cleanly with dignity and speed
6. LEARN     → Capture the lessons before institutional memory fades
```

## Steps

### Step 1: Identify the Kill Trigger
- What specific signal raised the question? Common triggers:
  - **Milestone miss:** Key milestone not met by deadline (defined at project inception).
  - **Thesis invalidation:** Core assumption proved wrong by data or market change.
  - **Opportunity cost escalation:** A better use of the same resources has emerged.
  - **Team signal:** The people closest to the work have lost belief (this is often the earliest and most reliable signal).
  - **External change:** Regulatory, competitive, or market shift that changes the landscape.
  - **Budget exhaustion:** Allocated investment consumed without proportionate progress.
- Document the trigger and the date it was identified. Delay between trigger and assessment is where sunk cost bias grows.

### Step 2: Assess Against Original Thesis
- Pull out the original brief, decision memo, or investment thesis.
- Answer three questions honestly:
  1. **Is the original thesis still valid?** Has the market, technology, or competitive landscape changed in ways that undermine the premise?
  2. **Are we executing well against a good thesis?** If execution is strong but results are weak, the thesis may be wrong. If execution is weak, is it fixable?
  3. **What would we do if we were starting from scratch today?** If the answer is "we would not start this project," sunk cost is the only reason to continue.
- Gather input from: the project team (closest to the work), a skeptic (someone who questioned the initiative), and a neutral party (someone with no emotional investment).

### Step 3: Separate Sunk Costs from Forward Value
- Calculate the **sunk cost:** Total investment to date (time, money, opportunity cost). This number is irrelevant to the kill decision — it is already spent regardless of what happens next.
- Calculate the **forward investment:** What additional resources are needed to reach the next meaningful milestone.
- Calculate the **forward value:** What is the expected return on the forward investment, given everything known today.
- The only relevant question: "Is the expected value of the forward investment positive, and is it the best use of those resources?"
- Common bias: "We have already invested $500K, we cannot walk away now." This is textbook sunk cost fallacy. The $500K is gone whether you continue or not.

### Step 4: Make the Decision
- Three possible outcomes:
  - **Kill:** Terminate the initiative. Forward value does not justify forward investment.
  - **Pivot:** The thesis has merit but the approach is wrong. Redirect with a new brief (see `pivot-pattern.md`).
  - **Continue with conditions:** The thesis and execution are sound but need more time. Set a new, tighter evaluation point.
- The decision-maker should be one level above the initiative owner to reduce emotional attachment bias.
- Apply the newspaper test: "If a journalist reported that we continued investing in this initiative given what we know, would it look wise or foolish?"
- Record the decision, rationale, and any dissent using `lib/components/decision-memo-blocks.md`.

### Step 5: Execute the Wind-Down
- Speed matters. Slow kills are more painful and more expensive than fast ones.
- Wind-down checklist:
  - [ ] Communicate the decision to the team with honesty and respect. Explain why, not just what.
  - [ ] Reassign team members within 1-2 weeks. Talent from killed projects should be prioritized for redeployment, not penalized.
  - [ ] Notify affected stakeholders (customers, partners) with a transition plan.
  - [ ] Preserve any reusable assets (code, research, relationships, data).
  - [ ] Close financial commitments (contracts, subscriptions, vendor agreements).
  - [ ] Archive all project documentation for future reference.
  - [ ] Update the decision registry and remove the initiative from active tracking.
- Cultural imperative: celebrate the learning, not the failure. Teams that are punished for killed projects will hide failing initiatives instead of surfacing them.

### Step 6: Capture Lessons
- Conduct a brief postmortem (use `postmortem-pattern.md`) within 2 weeks of the kill decision.
- Key questions:
  - What did we learn about our market, customers, or capabilities?
  - At what point could we have identified this earlier?
  - What decision process improvement would help us make better initial bets or faster kills?
  - What assets or knowledge from this initiative can be applied elsewhere?
- Update `data/registries/lessons-learned-registry.yaml` and `data/registries/experiment-registry.yaml`.

## Anti-Patterns

| Anti-Pattern | Description | Consequence |
|-------------|-------------|-------------|
| Zombie projects | Initiatives that are effectively dead but never formally killed | Resources drain slowly; team morale decays |
| Sunk cost continuation | "We have invested too much to stop now" | Throwing good money after bad |
| Kill by neglect | Starving a project of resources instead of making a clear decision | Slow, painful death; team feels abandoned |
| Punishment kill | Team is penalized for the project failing | Future teams hide problems instead of surfacing them |
| No-learn kill | Project is terminated without postmortem | Same bad bet is made again |
| Political kill | Project is killed because the sponsor lost organizational power, not because the thesis failed | Good initiatives die for bad reasons; political behavior is reinforced |
| Premature kill | Terminating before the initiative has had a fair chance to prove itself | Organizational impatience prevents any long-term bet from succeeding |

## Examples

### Example: Killing a Product Line

**Trigger:** Mobile app feature launched 6 months ago with 90-day activation target of 5,000 users. Current: 340 users after 180 days.

**Assessment:**
- Original thesis: "Mobile users will convert at 3x web rate." Reality: mobile converts at 0.4x web rate.
- Execution quality: Strong — the team shipped on time, on budget, with good UX scores.
- Starting from scratch today: "No, we would invest in web conversion optimization instead."

**Sunk vs. Forward:**
- Sunk: $280K (6 months of 2-person team). Irrelevant.
- Forward investment needed: $180K for 4 more months to reach "meaningful scale."
- Forward value: At current trajectory, expected 800 users after 4 more months. LTV per mobile user is $120 = $96K expected value on $180K investment. Negative EV.

**Decision:** Kill. Reallocate team to web conversion optimization (estimated $400K incremental ARR from same investment).

**Wind-down:**
- Team informed same day with context and gratitude.
- Both engineers redeployed to growth team within 1 week.
- 12 paying mobile users migrated to web experience.
- App submitted for sunset with 60-day notice.
- Postmortem scheduled for following Tuesday.
- Lesson captured: "Validate channel-market fit with a 30-day prototype before committing to full build."
