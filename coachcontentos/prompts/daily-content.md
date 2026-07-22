# Prompt: Daily Content

**Purpose:** Turn today's topic into a ready-to-post slate of content across whichever
formats are needed today. This is the core "one topic → many formats" engine.

## Required Reading Before Writing

1. `inputs/current-topic.md` — what today's content is about, who it's for, the goal
2. `knowledge/voice.md` — tone rules and banned phrases
3. `knowledge/audience.md` — the specific persona this is written for
4. `knowledge/approved-examples.md` — closest matching format for calibration
5. Whichever of `inputs/property-details.md`, `inputs/market-data.md`,
   `inputs/raw-notes.md` are relevant to today's topic
6. `knowledge/compliance.md` — before finalizing anything

## Steps

1. Confirm the topic, persona, and goal from `inputs/current-topic.md`. If any of these
   are missing, ask for them rather than assuming.
2. Identify which formats are needed today (checked off in `inputs/current-topic.md`, or
   as directed).
3. Write the strongest version of the idea first, in whichever format is the "lead"
   format for today (often the Reel script or the caption) — nail the core message once.
4. Adapt that core message into each additional requested format, respecting each
   format's natural structure (below) rather than just re-pasting the same text.
5. Flag every missing fact with `[INFORMATION NEEDED]`.
6. Run the compliance checklist in `knowledge/compliance.md` against every piece.
7. Save each piece to `outputs/daily/` using the naming convention in that folder's
   README.

## Format Structures

- **Instagram Reel script:** hook (first 2 seconds), 3–5 beats, on-screen text cues,
  spoken voiceover, CTA. See `prompts/reel-script.md` for the full structure.
- **Instagram caption:** hook line, 2–4 short paragraphs or a tight list, CTA, minimal
  relevant hashtags (no hashtag stuffing).
- **Instagram carousel:** slide-by-slide breakdown (title slide + 4–7 content slides +
  CTA slide), each slide's on-screen text kept to one idea.
- **Instagram Stories:** 3–6 sequential story frames, each with one short line of text
  and a clear next-frame hook or poll/question sticker prompt.
- **Facebook post:** slightly longer and more conversational than Instagram, can include
  more context since Facebook audiences skew a bit older/more local-community focused.
- **LinkedIn post:** insight-led opener, 3–5 short paragraphs, positions Glen's
  market expertise; less "salesy" than Instagram, more thought-leadership.
- **YouTube concept:** title, one-sentence premise, target persona, estimated length,
  3-bullet outline — a planning artifact, not a full script.
- **YouTube script:** full script with intro hook, chaptered body sections, and outro
  CTA — longer and more explanatory than a Reel script.
- **Email newsletter:** see `prompts/email-campaign.md`.
- **Blog post:** headline, subheadings, 500–900 words, written to actually teach
  something (SEO-aware but never keyword-stuffed).
- **Text message:** 1–3 sentences, reads like Glen actually typed it, one clear ask.
- **Lead-nurture sequence:** see `prompts/lead-nurture.md`.

## Output

Save each generated piece as a separate file in `outputs/daily/`, named
`YYYY-MM-DD-[format]-[topic-slug].md`. Include the persona and goal as a one-line header
comment at the top of each file for future reference.

## Quality Checklist

- [ ] Every format serves the same core idea without feeling copy-pasted
- [ ] No banned clichés or AI-sounding phrases (`knowledge/voice.md`)
- [ ] No invented facts — every claim traces to `knowledge/` or `inputs/`
- [ ] Compliance checklist passed
- [ ] CTA is clear and matches the stated goal
