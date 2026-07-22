# Prompt: Property Description

**Purpose:** Write the factual, narrative description of a property that anchors an MLS
listing and serves as the source text for every other listing-launch format.

## Required Reading Before Writing

1. `inputs/property-details.md` — the complete factual record for this property
2. `knowledge/voice.md`
3. `knowledge/markets.md` — for neighborhood context
4. `knowledge/compliance.md` — Fair Housing framing is critical here

## Steps

1. Read every field in `inputs/property-details.md`. Any field marked
   `[INFORMATION NEEDED]` stays exactly that in the output — do not fill gaps with
   generic real estate language.
2. Write two versions:
   - **MLS-length version** (typically 150–300 words, whatever the local MLS character
     limit is): fact-dense, compliant, no fluff, front-loads the strongest true
     differentiators (waterfront specs, walkability, standout confirmed features).
   - **Narrative/marketing version** (400–700 words): the fuller story for use on the
     website, blog, and print collateral — more room for texture and lifestyle framing,
     still entirely fact-based.
3. Open with the single strongest, most specific true fact about the property — not a
   generic superlative. ("120 feet of deep water frontage with no fixed bridges to the
   ocean" beats "Stunning waterfront estate.")
4. Use concrete sensory and spatial detail drawn only from confirmed features, not
   invented atmosphere.
5. Weave in neighborhood character from `knowledge/markets.md` only where it's
   genuinely relevant to this specific property (e.g., walkability to Las Olas
   Boulevard, dock access in Las Olas Isles) — don't pad with generic neighborhood
   copy.
6. Close with a clear, non-pushy CTA appropriate to the launch stage in
   `inputs/property-details.md`.
7. Apply the Fair Housing check from `knowledge/compliance.md` — describe the property
   and lifestyle, never "who it's perfect for" in demographic terms.

## Output

Save both versions to `outputs/listings/[address-slug]/property-description.md`, clearly
labeled "MLS Version" and "Narrative Version."

## Quality Checklist

- [ ] Every fact traces to `inputs/property-details.md`; no invented specs, history, or
      condition claims
- [ ] No banned clichés from `knowledge/voice.md` ("must-see," "dream home,"
      "nestled," etc.)
- [ ] Opens with a specific true fact, not a generic superlative
- [ ] Passes the Fair Housing check
- [ ] MLS version fits typical character constraints; narrative version earns its extra
      length with real detail, not padding
