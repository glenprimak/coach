# Compliance & Advertising Standards

Every piece of content this system produces must pass this checklist before it's
considered finished. This is not optional and not a "nice to have" — real estate
advertising is regulated, and getting it wrong carries real legal and license risk.

This file is guidance, not legal advice. When a specific piece of content raises a real
question, Glen should confirm with his broker or an attorney — flag it rather than
guess.

## Fair Housing (Federal)

The Fair Housing Act prohibits discrimination based on race, color, national origin,
religion, sex, familial status, and disability. In practice, this means content must
never:

- Describe a neighborhood, building, or area in terms of who "belongs" there or who it's
  "perfect for" based on a protected class (e.g., avoid "great for families," "ideal for
  empty nesters," "perfect for a young professional" as blanket statements — describe the
  property/amenities instead of the person).
- Use steering language that implies a property or area is or isn't suitable for someone
  based on a protected characteristic.
- Include photos or language implying exclusivity to a particular race, religion, or
  national origin.
- Describe a property using terms tied to religious facilities as a selling point in a
  way that implies preference ("walking distance to the church" is fine as a factual
  amenity; "perfect for a Christian family" is not).

Safe practice: describe the property, the amenities, and the lifestyle in neutral,
factual terms. Let the buyer decide if it's "perfect for them."

## Florida Real Estate Advertising Rules

Per Florida Real Estate Commission (FREC) advertising rules, real estate advertising by
a licensee generally must:

- Include the licensed brokerage name as registered with the state (not just the
  agent's personal name/brand) in advertisements, per FREC guidelines — confirm the
  exact required format with Glen's broker and store it in
  `knowledge/business.md`.
- Not be false, deceptive, or misleading about the property, the transaction, or Glen's
  credentials.
- Not imply a guarantee of results (sale price, timeline, appreciation) that cannot be
  substantiated.

Because exact brokerage disclosure requirements and preferred formatting vary and change,
the finalized required disclosure line should live in `knowledge/business.md` and be
appended to content exactly as written there — this file should not improvise disclosure
language.

## Truthful Advertising / No Fabrication

This is the system-wide rule stated in `CLAUDE.md`, restated here because it's also a
compliance issue, not just a quality one:

- Never state a statistic, price, date, square footage, or market figure that isn't
  sourced from `inputs/market-data.md` or `inputs/property-details.md`.
- Never claim a ranking, award, "#1," or "top producing" status unless it is currently
  true, current, and documented in `knowledge/business.md`.
- Never fabricate or imply a testimonial, review, or client quote. Real testimonials may
  only be used with the client's documented permission, and should be entered into
  `knowledge/approved-examples.md` verbatim before use — never paraphrased or embellished.
- Never state or imply investment returns, appreciation guarantees, or rental income
  projections without a clearly sourced, current basis — and always paired with language
  that this is not a guarantee.
- Never claim a property has a feature not confirmed in `inputs/property-details.md`
  (e.g., don't say "recently renovated" unless that's a documented fact).

## Condo-Specific Disclosures (Florida)

Florida condo law has evolved significantly around structural inspections, reserve
funding, and financial disclosures (post-Surfside reforms). Content about condo
buildings — especially in Sunny Isles and Miami — should:

- Never state a building's reserve funding status, inspection status, or financial
  health without a current, sourced fact.
- Flag `[INFORMATION NEEDED]` rather than assume a building is "fully funded" or has
  "passed inspection."
- Treat this as a serious buyer-protection and liability issue, not a minor detail.

## Required Elements Checklist

Before publishing, confirm each piece of content:

- [ ] Contains no invented facts, stats, or figures (checked against `inputs/` and
      `knowledge/`)
- [ ] Contains no protected-class-based description of who a property/area suits
- [ ] Contains no guarantee of outcome, price, or timeline
- [ ] Uses the current, approved brokerage disclosure/sign-off from
      `knowledge/business.md` where required (listing content, ads)
- [ ] Contains no unverified testimonial or review
- [ ] Matches the tone standards in `knowledge/voice.md` — deceptive urgency is both a
      compliance and a brand problem

## When Unsure

If a piece of content raises a compliance question this file doesn't clearly answer,
insert a note directly in the draft: `[COMPLIANCE CHECK NEEDED: describe the question]`
and flag it to Glen rather than publishing.
