# Prompt: Performance Review

**Purpose:** Periodically turn `knowledge/performance-learnings.md` into concrete
improvements to the rest of the system, so content quality compounds instead of staying
flat.

## Required Reading Before Writing

1. `knowledge/performance-learnings.md` — the full log since the last review
2. `knowledge/voice.md`, `knowledge/audience.md` — the files most likely to need updates
3. `knowledge/business.md` — current goals, to judge whether content is actually serving
   them

## Steps

1. Read every entry logged in `knowledge/performance-learnings.md` since the last
   review. Do not skim — patterns often show up across several small entries rather than
   one big one.
2. Group findings into categories:
   - **Format performance** — which formats are consistently earning engagement/leads
     vs. underperforming
   - **Topic/persona performance** — which persona and topic combinations are working
   - **Hook/opener performance** — which openers get engagement vs. get scrolled past
   - **CTA performance** — which CTAs actually generate replies/bookings
3. For each real pattern (backed by more than one data point — a single result isn't a
   pattern), write a specific, actionable recommendation. Vague conclusions ("do more
   engaging content") are not useful — the output should be specific enough to change
   what gets written next week (e.g., "Reels with a direct-to-camera hook outperformed
   text-overlay-only hooks in the last 4 entries — default to direct-to-camera going
   forward").
4. Propose specific edits to:
   - `knowledge/voice.md` (tone/style adjustments)
   - `knowledge/audience.md` (persona refinements — e.g., an objection that keeps coming
     up that isn't documented yet)
   - Specific `prompts/` files (structural changes — e.g., "shorten the hook window in
     `prompts/reel-script.md`")
5. Update the "Standing Patterns" section of `knowledge/performance-learnings.md`
   directly with the confirmed findings.
6. Flag anything inconclusive as still needing more data rather than forcing a
   premature conclusion.

## Output Format

```
## Performance Review — [Date range covered]

### Confirmed Patterns
- [Pattern] — [supporting evidence from the log] — [recommended action]

### Recommended File Updates
- knowledge/voice.md: [specific proposed edit]
- knowledge/audience.md: [specific proposed edit]
- prompts/[file].md: [specific proposed edit]

### Inconclusive / Needs More Data
- [Observation that needs more entries before acting on it]

### Not Working — Stop Doing
- [Anything the data clearly shows isn't working]
```

## Output Location

Save the review itself to `outputs/weekly/YYYY-MM-DD-performance-review.md`, and apply
the confirmed, specific file updates directly to the relevant `knowledge/` files.

## Quality Checklist

- [ ] Every recommendation is backed by actual logged data, not assumption
- [ ] Recommendations are specific enough to change what's written next, not generic
      advice
- [ ] `knowledge/performance-learnings.md` "Standing Patterns" section is updated
- [ ] Inconclusive findings are labeled as such rather than forced into a conclusion
