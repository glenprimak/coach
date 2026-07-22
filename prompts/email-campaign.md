# Prompt: Email Campaign

**Purpose:** Write emails that read like a personal note from Glen, not a mass blast —
covering newsletters, listing announcements, and standalone market/education emails.

## Required Reading Before Writing

1. `inputs/current-topic.md` and/or `inputs/property-details.md` /
   `inputs/market-data.md` — the content foundation
2. `knowledge/voice.md` — email is the warmest, most personal channel in the system
3. `knowledge/audience.md` — segment the email to a specific persona where possible
   rather than writing one generic version for everyone on the list
4. `knowledge/business.md` — sign-off block

## Email Types This Prompt Covers

1. **Regular newsletter** — market intelligence, neighborhood spotlight, or education,
   sent on a standing cadence.
2. **Listing announcement** — new listing or price update, sent to the buyer database
   and/or relevant segment.
3. **Standalone education/authority email** — a single useful idea (e.g., "what NY
   buyers get wrong about FL insurance"), not tied to a specific listing.

## Steps

1. Identify the email type and the specific segment/persona it's for — don't write to
   "everyone" if a persona-specific version will perform better.
2. Write a subject line that is short, specific, and curiosity- or value-driven —
   never clickbait, never in ALL CAPS, no more than ~50 characters where possible.
   Draft 2–3 subject line options.
3. Open with one sentence that matters to the reader specifically — no "Hope this finds
   you well" or generic pleasantries.
4. Body structure:
   - One clear main idea (don't cram a listing announcement, a market update, and a
     CTA to book a call all into one email — pick the lead story).
   - Short paragraphs (1–3 sentences). Emails get skimmed, not read top to bottom.
   - A specific fact or insight the reader can't get from a generic real estate
     newsletter — this is what makes it worth opening next time.
   - One clear CTA, stated plainly (reply, click, call, book).
5. Close with the sign-off block from `knowledge/business.md`.
6. Include a P.S. line where it adds a genuine second hook (a common high-performing
   email pattern) — never a fake one.

## Output Format

```
**Subject line options:**
1. [...]
2. [...]
3. [...]

**Preview text:** [the inbox preview snippet, 40–90 characters]

**Body:**
[full email copy]

**CTA:** [restate the single action this email drives]
**Segment/persona:** [from knowledge/audience.md]
```

## Output Location

Save to `outputs/emails/YYYY-MM-DD-[type]-[topic-slug].md`.

## Quality Checklist

- [ ] Subject line is specific, not clickbait, no ALL CAPS or excessive punctuation
- [ ] One main idea, not three competing CTAs
- [ ] No invented stats, no fake scarcity/urgency
- [ ] Reads like a note from a person, not a corporate blast
- [ ] Sign-off block matches `knowledge/business.md` exactly
