# Prompt: Lead-Nurture Sequence

**Purpose:** Build multi-touch email/text sequences that move a lead from first contact
toward a booked call — without ever feeling like an automated drip.

## Required Reading Before Writing

1. `knowledge/audience.md` — which persona and which entry point (e.g., downloaded a
   relocation guide, inquired about a specific listing, attended an open house)
2. `knowledge/voice.md`
3. `knowledge/business.md` — sign-off and current goals
4. `knowledge/services.md` — what Glen can actually offer/promise at each stage

## Sequence Types

1. **New lead / relocation inquiry** — someone who raised their hand about moving from
   NY to FL.
2. **Listing inquiry** — someone who engaged with a specific property.
3. **Past client / sphere re-engagement** — warming up a dormant relationship.
4. **Open house follow-up** — someone who showed up in person.

## Steps

1. Identify the sequence type and the persona (`knowledge/audience.md`) it's built for.
2. Map the sequence length and cadence to the situation — a hot listing inquiry needs a
   fast, short sequence (same day, next day, 3 days later); a relocation inquiry earlier
   in their timeline can run longer and more educational (weekly over 4–6 weeks).
3. Each touch should do exactly one job — don't try to sell, educate, and ask for a
   referral in the same message. Map the job of each touch before writing it:
   - Touch 1: acknowledge + immediate value (answer their actual question)
   - Touch 2: build trust (a genuinely useful piece of education specific to their
     situation)
   - Touch 3: social proof / process transparency (how Glen actually works — only using
     confirmed facts from `knowledge/services.md` and real approved testimonials from
     `knowledge/approved-examples.md`, never fabricated ones)
   - Touch 4+: direct, low-pressure ask to talk
4. Mix channels where appropriate — email for longer touches, text for short, timely
   ones (see `knowledge/voice.md` for text message tone).
5. Every touch needs a genuinely different angle — never send the same message reworded;
   a lead who doesn't respond to touch 2 shouldn't get a weaker version of touch 2 as
   touch 3.
6. No fake urgency, ever, in a nurture sequence — it's usually the fastest way to lose
   trust with exactly the sophisticated, skeptical buyer this system is built for.

## Output Format

```
## Sequence: [type] — [persona]

### Touch 1 — [channel] — [timing, e.g., "immediately"]
**Job of this touch:** [one line]
[Copy]

### Touch 2 — [channel] — [timing]
**Job of this touch:** [one line]
[Copy]

(continue for full sequence)

**Exit condition:** [what happens when the lead responds — sequence should stop/branch,
not keep firing]
```

## Output Location

Save to `outputs/emails/nurture-[sequence-type]-[persona-slug].md`.

## Quality Checklist

- [ ] Each touch has one distinct job — no redundant messaging
- [ ] No fabricated testimonials, stats, or urgency
- [ ] Cadence matches the lead's actual buying timeline/temperature
- [ ] Clear exit/branch condition once the lead responds
- [ ] Every claim about Glen's process traces to `knowledge/services.md`
