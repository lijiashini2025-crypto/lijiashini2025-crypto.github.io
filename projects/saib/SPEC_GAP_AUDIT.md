# SPEC GAP AUDIT

## Current Status

`CORE INTERACTION MISSING` — the persistent spec is now present, but the SAIB page, project assets, standalone route, and Brain Building hotspot do not exist in the current repository.

## KEEP

- Keep `CASE_SPEC.md` unchanged as the persistent source of truth.
- Keep the existing Brain Building responsive image, percentage hotspot system, GSAP transition, and scroll restoration.
- Keep IN STEP, EMBI, and HK7s behavior intact.
- Preserve authentic SAIB packaging when supplied; do not redesign it during implementation.

## BLOCKERS

### Gap 01 — Case page and route do not exist

**Current:** `public/projects/saib/` contains only `CASE_SPEC.md`. `/projects/saib/` falls through to the React wildcard and returns to `/mind`; the Vite standalone middleware and room configuration do not include SAIB.

**Expected:** A standalone case at `/projects/saib/`, with Back to My Mind and a THINK-floor SAIB hotspot.

**Gap:** There is no implemented case to preserve or visually compare with the spec.

**Action:** In the implementation round, add the standalone page, route mapping, and percentage-based hotspot through the existing portfolio mechanisms.

**Dependency:** `code only` for route and hotspot; page production depends on the assets below.

### Gap 02 — The central perspective concept is absent

**Current:** There is no Social Persona narrative or editorial system.

**Expected:** `SOCIAL PERSONA = HOW SHE SEES`: a fictional independent female filmmaker/city observer whose perspective, distance, tone, and content lens define the brand voice.

**Gap:** The project currently cannot communicate the distinction between a point of view and a demographic persona card.

**Action:** Structure the case around observation and editorial choices. Do not introduce profile-card demographics, a real director likeness, or generic empowerment copy.

**Dependency:** `code only` for narrative; `new asset` for the fictional city observer and editorial scenes.

### Gap 03 — Defining transformations and explorations are absent

**Current:** There is no Old Film opening, Film Cut, `BIAS → SAIB` flip, Viewfinder, Three Rights exploration, Social Persona feed, or One Moment, Three Voices interaction.

**Expected:** These interactions must demonstrate the move from old rules to a new perspective and prove how SAIB sounds across content.

**Gap:** The strategy has no experiential proof; a static brand deck would not meet the spec.

**Action:** Prioritize Film Cut and BIAS flip first, then Viewfinder and Three Rights, followed by the editorial feed and tone comparison.

**Dependency:** `code only` for interaction logic; `new asset` for film, persona, rights, and feed visuals.

## P0

### Gap 04 — Required narrative sequence is absent

**Current:** Old Film, Where Are Women?, The Old Game, From Product to Perspective, Tone of Voice, Content Lens, Product & Beyond, My Role, and Final are not implemented.

**Expected:** The page should unfold like a film: old image → rupture → reversal → observer → content system → product truth → perspective.

**Gap:** The visitor has no context for why the persona exists or how it changes the brand.

**Action:** Build the spec sequence and keep `SHE DOESN'T SHOUT. SHE NOTICES.` and the three content lenses as structural anchors.

**Dependency:** `code only` plus verified project copy.

### Gap 05 — Confirmed editorial art direction has no production system

**Current:** No SAIB asset folder, color system, film strip, contact sheet, paper, tape, handwriting, photography, or packaging is present.

**Expected:** Pink, near-black, cream, film-strip editorial collage, independent-film city observation, handwritten notes, and gentle realism.

**Gap:** Visual fidelity cannot be assessed, and there is a high risk of drifting into beauty e-commerce or generic feminist campaign styling.

**Action:** Establish the locked palette and independent editorial layers before populating all sections. Keep product and persona imagery separate and composable.

**Dependency:** `new asset` plus `code only` composition.

### Gap 06 — My Role and strategic conclusion are absent

**Current:** No independent-strategy scope, Brand Reframe, Social Persona, Tone & Manner, Content Strategy, Product Narrative, or Visual Storytelling contribution is shown.

**Expected:** The page must clarify the independent strategy contribution and close with why a consistent way of seeing strengthens the brand.

**Gap:** The case has no authorship boundary or evaluative conclusion.

**Action:** Add the spec-approved role scope and final rationale after the content system is visible.

**Dependency:** `existing project material` and verified role copy.

## P1

### Gap 07 — Responsive, keyboard, and reduced-motion states cannot be assessed

**Current:** No page DOM or interaction code exists.

**Expected:** Film strips, horizontal exploration, viewfinder, feed panels, and voice switching must remain usable by keyboard and on smaller screens without losing the film/editorial rhythm.

**Gap:** Technical usability is untestable.

**Action:** Define mobile alternatives and focus states alongside each core interaction rather than after visual completion.

**Dependency:** `code only`.

## P2

### Gap 08 — Editorial texture and micro-motion are absent

**Current:** No grain, halftone, torn edge, contact-sheet detail, tape, or restrained cut transition exists.

**Expected:** These elements should support the independent-film voice without becoming Y2K decoration.

**Gap:** Polish is missing but should follow the core perspective and interaction work.

**Action:** Defer until Blockers and P0 are validated.

**Dependency:** `code only` and optional production assets.

## Asset Gaps

All items are `ASSET NEEDED`; `public/assets/saib/` does not currently exist.

- **P0:** `saib-product-tin.png`, `saib-product-box.png`, `saib-product-pack.png` — transparent PNG — authentic product packaging.
- **P0:** `persona-city-01.webp` — WebP — principal fictional city-observer Hero.
- **P0:** `persona-film.webp` — WebP — editorial/film persona scene.
- **P1:** `film-strip.svg` or `film-strip.png` — SVG/PNG — cinematic framing and horizontal exploration.
- **P1:** `film-grain.webp` and `paper-texture.webp` — WebP — film and cream-paper bases.
- **P1:** `right-know.webp`, `right-define.webp`, `right-lead.webp` — WebP — Three Rights exploration.
- **P1:** `social-observation.webp`, `social-her-story.webp`, `social-product-truth.webp` — WebP — editorial feed examples.
- **P2:** `pink-tape.png`, contact-sheet fragments, handwritten notes, halftone, and torn-paper edges — PNG/WebP/SVG — finishing layers.

## Interaction Gaps

- OLD FILM → new editorial world Film Cut: missing.
- `BIAS → SAIB` typographic reversal: missing.
- Viewfinder reveal of overlooked details: missing.
- Three Rights horizontal exploration: missing.
- Social Persona feed expansion: missing.
- One Moment, Three Voices switching: missing.

## Visual Match

Not assessable because no page or assets exist. Future work must match `pink + black + cream + film strip + editorial collage + independent film + city observer + gentle realism` and must reject beauty-commerce, loud girlboss, Y2K-overload, and generic feminist-campaign treatments.

## Route / Technical Health

- `/projects/saib/`: **BROKEN AS A CASE ROUTE** — currently redirects to `/mind`.
- `public/projects/saib/index.html`: missing.
- `public/assets/saib/`: missing.
- Brain Building SAIB hotspot: missing.
- Console errors: none observed during the fallback redirect, but no SAIB runtime exists to test.

## Recommended Implementation Order

1. Secure authentic packaging and the P0 fictional city-observer visuals.
2. Create the standalone route, page shell, narrative sequence, and Back to My Mind behavior.
3. Implement OLD FILM, Film Cut, and BIAS → SAIB.
4. Establish Social Persona as a way of seeing through Viewfinder and Tone of Voice.
5. Build Three Rights, the editorial feed, and One Moment, Three Voices.
6. Add Product & Beyond, My Role, conclusion, responsive behavior, and P2 texture polish.
