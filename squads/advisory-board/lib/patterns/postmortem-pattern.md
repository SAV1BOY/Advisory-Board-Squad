# Postmortem Pattern

## Pattern Name

Postmortem — structured learning from significant outcomes (failures, near-misses, and unexpected successes) that converts experience into organizational knowledge.

## When to Use

- A project, decision, or initiative produced a significantly different outcome than expected (positive or negative).
- A crisis, outage, or incident has been resolved and the team needs to learn from it.
- A major bet was killed and the organization should understand why.
- A customer was lost or a deal failed in a way that suggests systemic issues.
- A quarterly or annual cycle is complete and retrospective learning is needed.
- Any event where "we should make sure this never happens again" is spoken.

Do NOT use when:
- The event is trivial and local learning suffices (not every bug needs a postmortem).
- The purpose is to assign blame rather than learn. If blame is the goal, fix the culture first.
- It has been more than 30 days since the event — memory has degraded too far. Conduct a brief retrospective instead.

## Structure

```
1. CONVENE    → Assemble the right people quickly
2. RECONSTRUCT → Build the factual timeline
3. ANALYZE    → Identify root causes and contributing factors
4. EXTRACT    → Derive actionable lessons
5. COMMIT     → Assign actions to prevent recurrence
6. PUBLISH    → Share learnings broadly
```

## Steps

### Step 1: Convene
- Schedule the postmortem within 5-10 business days of the event's resolution.
- Invite everyone directly involved plus one external facilitator who was not involved.
- The facilitator's role: keep discussion blame-free, ensure all voices are heard, maintain focus on systemic causes.
- Set ground rules: (a) no blame, only understanding, (b) assume good intent, (c) focus on systems not individuals, (d) disagreements about facts are resolved with data.
- Duration: 60-90 minutes. Longer means the scope is too broad — split into multiple postmortems.

### Step 2: Reconstruct the Timeline
- Build a shared chronological timeline of events starting from the earliest relevant point.
- Each entry includes: timestamp, what happened, who was involved, what information was available at the time.
- Distinguish between facts and interpretations. Annotate assumptions.
- Identify decision points: moments where a different choice could have changed the outcome.
- Capture what was NOT known at each decision point — hindsight bias is the enemy of honest postmortems.

### Step 3: Analyze Root Causes
- For each key failure point or surprising outcome, ask "Why?" five times (5 Whys technique).
- Categorize contributing factors:
  - **Process:** Was a process missing, broken, or not followed?
  - **Information:** Was critical information unavailable, ignored, or misinterpreted?
  - **Capability:** Did the team lack the skills, tools, or resources needed?
  - **Judgment:** Was a reasonable judgment made that turned out to be wrong, or was the judgment itself flawed?
  - **Incentives:** Did incentive structures encourage the behavior that led to the outcome?
  - **Communication:** Did information fail to reach the right people at the right time?
- Distinguish between root causes (the fundamental issue) and contributing factors (conditions that amplified the impact).
- Test each root cause: "If we fixed only this, would the event still have occurred?"

### Step 4: Extract Lessons
- Convert root causes into lessons stated as principles or guidelines.
- Each lesson must be:
  - **Specific:** Not "communicate better" but "share deployment risk assessments with on-call engineer before every release."
  - **Actionable:** Something the organization can implement.
  - **Proportionate:** The fix should be proportionate to the risk — do not build a fortress around a fender-bender.
- Categorize lessons: process change, tooling improvement, training need, organizational design, policy update.
- Identify which lessons apply beyond the immediate context (cross-team, cross-functional, company-wide).

### Step 5: Commit to Actions
- Each lesson generates one or more action items with:
  - **Owner:** Single accountable person (not "the team").
  - **Due date:** Specific date, not "soon."
  - **Success criteria:** How you will know the action is complete and effective.
  - **Verification plan:** How the action will be tested (e.g., "simulate the failure scenario to confirm the fix works").
- Prioritize ruthlessly: 3-5 actions are better than 15 actions that never get done.
- Track actions in `data/registries/lessons-learned-registry.yaml` and `scripts/tracking/action-item-tracker.md`.

### Step 6: Publish and Share
- Write a postmortem document that includes: summary, timeline, root causes, lessons, and actions.
- Share broadly — the value of a postmortem is organizational, not local.
- Present key findings at the next all-hands or relevant leadership meeting.
- Archive in `archive/` for future reference.
- Review actions at 30 and 90 days to verify completion and effectiveness.

## Anti-Patterns

| Anti-Pattern | Description | Consequence |
|-------------|-------------|-------------|
| Blame storm | Postmortem becomes a finger-pointing exercise | People hide failures; learning stops |
| Hero narrative | "Everything was fine because [hero] saved us" — ignores systemic fragility | False confidence; no structural improvement |
| Action-free postmortem | Great analysis, no committed actions | Same failure recurs; postmortems lose credibility |
| Delayed postmortem | Conducted months later when memories have faded | Inaccurate reconstruction; weak lessons |
| Shallow root cause | Stopping at the first "why" instead of going deeper | Surface-level fixes; root cause persists |
| Postmortem fatigue | Every small issue triggers a full postmortem | Team burnout; important postmortems get less attention |
| Locked-away learning | Postmortem exists but is not shared broadly | Same failure occurs in another team |

## Examples

### Example: Failed Product Launch Postmortem

**Summary:** Feature X launched on Feb 1 targeting 500 activations in week one. Actual: 23 activations. Feature was rolled back on Feb 14.

**Timeline (abbreviated):**
- Dec 15: Feature approved based on 12 customer interviews
- Jan 5: Scope expanded to include mobile (no timeline adjustment)
- Jan 20: QA flagged performance issues; team chose to "fix after launch"
- Feb 1: Launch. Onboarding flow had 67% drop-off at step 3
- Feb 3: Customer support received 40 tickets about confusing UX
- Feb 14: Feature rolled back

**Root Causes:**
1. Scope creep without timeline adjustment (Process — no change control on scope)
2. Performance issues deprioritized under time pressure (Judgment — known risk accepted without mitigation)
3. Onboarding UX was never user-tested with real customers (Process — no user testing gate in launch checklist)
4. Original 12 interviews selected for enthusiasm, not representativeness (Information — sampling bias)

**Lessons:**
1. Scope changes after approval require explicit timeline re-negotiation with stakeholders.
2. Performance regressions are launch blockers, not post-launch tasks.
3. Any customer-facing feature requires user testing with minimum 5 representative users before launch.

**Actions:**
| Action | Owner | Due | Verification |
|--------|-------|-----|-------------|
| Add scope change gate to project checklist | VP Product | Mar 1 | Audit next 3 projects |
| Add performance regression to launch-blocker list | VP Eng | Feb 28 | Review CI/CD pipeline |
| Establish user testing requirement | UX Lead | Mar 15 | Test with next feature release |
