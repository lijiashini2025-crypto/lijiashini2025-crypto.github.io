# SPEC GAP AUDIT

## Current Status

`CORE INTERACTION MISSING` — the persistent spec is now present, but no Scott Cafe case page, assets, standalone route, or Brain Building hotspot exists in the current repository.

## KEEP

- Keep `CASE_SPEC.md` unchanged as the persistent source of truth.
- Keep the existing Brain Building responsive image, percentage hotspot system, GSAP transition, and scroll restoration.
- Keep IN STEP, EMBI, and HK7s routes and interactions untouched.
- Preserve the supplied Scott Cafe cup/chair logo exactly when the production file is added.

## BLOCKERS

### Gap 01 — Case page and route do not exist

**Current:** `public/projects/scott-cafe/` contains only `CASE_SPEC.md`. `/projects/scott-cafe/` is handled by the React wildcard and returns to `/mind`; no standalone middleware entry or room configuration exists.

**Expected:** A standalone case at `/projects/scott-cafe/` with Back to My Mind and a THINK-floor Scott Cafe hotspot.

**Gap:** There is no implemented page to preserve, test, or compare with the spec.

**Action:** In the implementation round, add the page, route mapping, and percentage-based room while keeping the portfolio shell unchanged.

**Dependency:** `code only` for route/hotspot; full page depends on the P0 visual assets.

### Gap 02 — Primary DESK → WINDOW experience is absent

**Current:** There is no grayscale desk world, warm window world, draggable divider, color transition, or state change.

**Expected:** The Hero must begin with compressed office tension and let the visitor drag into a sunlit Hong Kong window seat, revealing `A WINDOW SEAT IN CENTRAL. WAITING FOR YOU.`

**Gap:** The project's defining interaction and emotional proof do not exist.

**Action:** Build a pointer-, touch-, and keyboard-operable before/after divider as the first implementation milestone. It must preserve image proportions and progressively restore color, sunlight, air, and layout space.

**Dependency:** `new asset` for matched desk/window scenes and `code only` for the divider.

### Gap 03 — Strategic reframe and narrative are absent

**Current:** The portfolio does not show `20% EMPTY SEATS → A SEAT WAITING FOR YOU`, the 45-minute emotional escape, Consumer Insight, Business → Human Value, or the Big Idea.

**Expected:** The case must show that lunch is more than efficiency and translate a business weakness into a human promise before presenting campaign mechanics.

**Gap:** Without this context, later booking and UGC modules would read as generic restaurant marketing.

**Action:** Implement the specified sequence from desk tension through insight, reframe, Big Idea, execution, My Role, Why It Works, and Final without adding unsupported campaign logic.

**Dependency:** `code only` plus verified project copy and original materials.

## P0

### Gap 04 — Window-seat protagonist and logo reveal are absent

**Current:** No empty chair, Window Seat scene, chair hover, coffee-cup silhouette, or cup-to-chair reveal exists.

**Expected:** The empty chair must communicate Reserved for You, reveal `THIS ONE IS YOURS.`, and the logo must retain its cup/chair double meaning.

**Gap:** The campaign's emotional symbol and brand device have no visual presence.

**Action:** Compose the Window Seat from independent assets and implement a lightweight logo reveal after the primary divider is approved.

**Dependency:** `new asset` for the faithful logo, window environment, and transparent chair; `code only` for hover/reveal.

### Gap 05 — Conversion and participation proof are absent

**Current:** No One Tap Seat prototype, reservation state, Real Moments, UGC Polaroid, conversion loop, or campaign-content proof exists.

**Expected:** `PICK → CLICK → SIT`, followed by `YOUR CHAIR IS WAITING.`, scrapbook memories, simulated UGC, and `RESERVE → ARRIVE → ENJOY/COLLECT → SHARE → RETURN`.

**Gap:** The emotional idea has no demonstrated path to business action or repeat participation.

**Action:** Add the lightweight booking interaction after the Big Idea, then build the Polaroid and hand-drawn conversion path without turning the app UI into the visual protagonist.

**Dependency:** `code only` plus `new asset` for moments and campaign evidence.

### Gap 06 — Locked hand-drawn art direction has no production system

**Current:** No Scott Cafe asset directory, cream-paper texture, black-ink sketches, Hong Kong sunlight, scrapbook objects, or Polaroid language exists.

**Expected:** A hand-drawn, doodle, sketch, scrapbook world that moves from dense monochrome to warm open color across the page.

**Gap:** Visual fidelity cannot be assessed; a normal cafe landing page or beige brand site would fail the spec.

**Action:** Establish the DESK/WINDOW visual contrast and independent collage layers before building secondary sections.

**Dependency:** `new asset` plus `code only` composition.

## P1

### Gap 07 — My Role and campaign-system explanation are absent

**Current:** Big Idea, Consumer Insight, Campaign Framework, Content Formats, Conversion Journey, and Pitch Integration contributions are not shown.

**Expected:** Accurate collaborative language and a clear explanation of how the Window Seat idea moves across video, carousel, app, UGC, and retention.

**Gap:** Reviewers cannot see the candidate's strategic contribution or how the idea scales.

**Action:** Add My Role and concise campaign proof after the core experience and conversion loop work.

**Dependency:** `existing project material` and verified role copy.

### Gap 08 — Responsive and accessible interaction behavior cannot be assessed

**Current:** No divider, selectable booking controls, chair hover alternative, or mobile layout exists.

**Expected:** Touch/keyboard divider control, visible focus, a non-hover chair reveal, readable mobile stacking, and reduced-motion behavior.

**Gap:** All interaction-health checks are untestable.

**Action:** Define alternative input states while implementing each core interaction.

**Dependency:** `code only`.

## P2

### Gap 09 — Secondary scrapbook polish is absent

**Current:** No tape, paper edges, coffee/lunch cutouts, note fragments, or tiny doodles exist.

**Expected:** Restrained imperfection that supports the hand-drawn system.

**Gap:** Polish is missing but should follow approval of the main divider and Window Seat composition.

**Action:** Defer until Blockers and P0 pass.

**Dependency:** optional production assets and `code only` micro-motion.

## Asset Gaps

All items are `ASSET NEEDED`; `public/assets/scott-cafe/` does not currently exist.

- **P0:** `scott-logo-hires.png` — transparent PNG — faithful cup/chair logo.
- **P0:** `desk-world.webp` — WebP — compressed grayscale office world.
- **P0:** `window-world.webp` — WebP — warm sunlit Hong Kong window world.
- **P0:** `window-seat.webp` — WebP — core emotional environment.
- **P0:** `chair-empty.png` — transparent PNG — independent hoverable protagonist.
- **P1:** `office-worker-desk.webp` and `office-worker-window.webp` — WebP — matched emotional states.
- **P1:** `central-skyline.webp` — WebP — matching illustrated Hong Kong view.
- **P1:** `paper-texture.webp` — WebP — scrapbook base.
- **P1:** `polaroid-01.webp`, `polaroid-02.webp`, `polaroid-03.webp` — WebP — Window Seat Moments.
- **P1:** `scribble-arrow.svg` — SVG — reusable hand-drawn directional language.
- **P1:** `carousel-01.webp` through `carousel-04.webp` — WebP — campaign-content proof if retained.
- **P2:** `coffee.png`, `lunch.png`, handwritten notes, tape, paper edges, and doodles — PNG/WebP/SVG — supporting collage elements.

## Interaction Gaps

- DESK → WINDOW draggable divider: missing.
- Empty-chair hover/focus/tap reveal: missing.
- Cup → chair logo reveal: missing.
- Clickable One Tap Seat flow: missing.
- Reservation confirmation state: missing.
- UGC Polaroid generation: missing.
- Scroll-driven transition from dense grayscale to warm spacious color: missing.

## Visual Match

Not assessable because no page or assets exist. Future work must match `hand drawn + doodle + sketch + scrapbook + black ink + cream paper + Hong Kong sunlight + Polaroid`; polished luxury cafe, minimalist beige branding, corporate presentation, and generic restaurant landing-page treatments should be rejected.

## Route / Technical Health

- `/projects/scott-cafe/`: **BROKEN AS A CASE ROUTE** — currently redirects to `/mind`.
- `public/projects/scott-cafe/index.html`: missing.
- `public/assets/scott-cafe/`: missing.
- Brain Building Scott Cafe hotspot: missing.
- Console errors: none observed during the fallback redirect, but no Scott Cafe runtime exists to test.

## Recommended Implementation Order

1. Secure the matched DESK/WINDOW pair, faithful logo, Window Seat, and empty-chair assets.
2. Create the standalone route, page shell, accurate strategy sequence, and Back to My Mind behavior.
3. Implement and approve the DESK → WINDOW divider.
4. Build the Big Idea Window Seat composition, chair interaction, and logo reveal.
5. Implement One Tap Seat and `YOUR CHAIR IS WAITING.`
6. Add Real Moments, UGC, conversion loop, campaign proof, My Role, Why It Works, and Final.
7. Complete responsive, accessibility, performance, and P2 scrapbook polish.
