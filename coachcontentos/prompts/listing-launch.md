# Prompt: Listing Launch Campaign

**Purpose:** Turn one property into a complete, coordinated launch campaign across every
format — the flagship "one topic → many formats" use case for a new listing.

## Required Reading Before Writing

1. `inputs/property-details.md` — the property this campaign is for (must be fully
   reviewed; flag any missing field rather than guessing)
2. `knowledge/voice.md`
3. `knowledge/audience.md` — determine which persona(s) this property actually fits
   (waterfront buyer? relocator? condo investor?)
4. `knowledge/markets.md` — neighborhood framing
5. `knowledge/compliance.md` — listing content carries the highest compliance exposure
   of anything in this system
6. `knowledge/approved-examples.md`

## Steps

1. Read `inputs/property-details.md` completely. If key fields are missing (price,
   specs, standout features, the story), stop and flag exactly what's needed before
   producing the full campaign — a launch built on incomplete facts undermines the whole
   push.
2. Identify the primary persona(s) this property fits, from `knowledge/audience.md`.
3. Write the property description first (see `prompts/property-description.md`) — this
   becomes the factual backbone every other piece pulls from, so nothing drifts or
   contradicts itself across formats.
4. Build the full campaign set from that backbone:
   - Instagram Reel script (walkthrough or hook-driven — see `prompts/reel-script.md`)
   - Instagram carousel (property highlights, one feature per slide)
   - Instagram caption (paired with the carousel or Reel)
   - Instagram Stories sequence (behind-the-scenes / countdown-to-launch framing, using
     real dates only)
   - Facebook post
   - LinkedIn post (framed for the seller/referral audience — positions Glen's
     marketing capability, not just the property)
   - Email announcement (see `prompts/email-campaign.md`)
   - Text message version for Glen's buyer database
   - Blog post (deeper neighborhood + property narrative, useful for SEO and serious
     buyers)
5. Sequence matters — draft a suggested launch order/timing (e.g., email + text to
   database first if it's a pocket/exclusive period, public social after public launch)
   based on `inputs/property-details.md` launch details.
6. Run every piece through the compliance checklist.

## Output

Save each piece to `outputs/listings/[address-slug]/[format].md`, and save the overall
campaign plan/sequence as `outputs/listings/[address-slug]/00-campaign-plan.md`.

## Quality Checklist

- [ ] Every factual claim across every format traces back to
      `inputs/property-details.md` — no drift or contradiction between formats
- [ ] No invented urgency (real launch date/open house date only)
- [ ] Persona-appropriate framing for each piece
- [ ] Compliance checklist passed on every piece, especially Fair Housing framing and
      brokerage disclosure
- [ ] Campaign has a clear sequence, not just a pile of disconnected posts
