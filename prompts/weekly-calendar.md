# Prompt: Weekly Content Calendar

**Purpose:** Plan a full week of content across all active channels, balancing content
types, personas, and business goals — so daily content isn't produced ad hoc.

## Required Reading Before Writing

1. `knowledge/business.md` — current business goals and cadence target
2. `knowledge/audience.md` — the full set of personas to rotate through
3. `knowledge/markets.md` and `inputs/property-details.md` — active listings and market
   themes available to draw on this week
4. `knowledge/performance-learnings.md` — what's worked recently, to lean into it
5. `inputs/raw-notes.md` — any raw ideas worth scheduling

## Steps

1. Confirm the cadence target from `knowledge/business.md` (e.g., daily Instagram, 3x/
   week LinkedIn, weekly email). If not set, ask or default to: Instagram daily,
   Facebook 3x/week, LinkedIn 2x/week, one email newsletter, one YouTube/blog piece.
2. Identify the week's priorities: any active listing launches
   (`inputs/property-details.md`), any market shifts worth covering
   (`inputs/market-data.md`), and any evergreen educational topics that serve a
   persona that hasn't been addressed recently.
3. Build a 7-day grid. For each day, assign: date, format(s), topic, persona, goal, and
   which `prompts/` file will be used to actually generate it.
4. Balance the week so it isn't all listing promotion — mix listing content, market
   intelligence, relocation education, lifestyle/neighborhood content, and at least one
   direct relationship/CTA-driven piece.
5. Do not write the actual content in this step — this prompt produces the plan. Use
   `prompts/daily-content.md` (or the specific format prompt) on each scheduled day to
   generate the piece itself, populating `inputs/current-topic.md` from this calendar
   entry first.

## Output Format

```
## Week of [Date]

### [Day, Date]
- Format(s): [...]
- Topic: [...]
- Persona: [from knowledge/audience.md]
- Goal: [...]
- Source prompt: [prompts/....md]
- Notes: [...]

(repeat for each day)

### Weekly Theme
[One line tying the week together, if there is one]

### Gaps / Info Needed to Execute This Week
- [INFORMATION NEEDED: anything blocking a planned piece — missing property details,
  missing market data, etc.]
```

## Output Location

Save to `outputs/weekly/YYYY-MM-DD-week-of.md` (using the Monday of that week as the
date).

## Quality Checklist

- [ ] Every persona in `knowledge/audience.md` is addressed at least once a month, not
      just the most active one
- [ ] The week isn't more than ~40% direct listing promotion
- [ ] Every planned piece has a clear, sourced foundation (no plan that requires
      inventing facts to execute)
- [ ] Cadence matches the target in `knowledge/business.md`
