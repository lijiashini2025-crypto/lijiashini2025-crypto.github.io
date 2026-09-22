# SPEC GAP AUDIT

## Current Status

`CORE INTERACTION MISSING` — the persistent spec is now present, but no iPad case page, project assets, standalone route, or Brain Building hotspot exists in the current repository.

## KEEP

- Keep `CASE_SPEC.md` unchanged as the persistent source of truth.
- Keep the existing `/mind` responsive building image, percentage hotspot geometry, GSAP camera transition, and session-based scroll restoration.
- Keep the working IN STEP, EMBI, and HK7s routes untouched.
- Keep the existing standalone-document pattern used by EMBI and HK7s when the iPad route is added later.

## BLOCKERS

### Gap 01 — Case page and route do not exist

**Current:** `public/projects/ipad-2010/` contains only `CASE_SPEC.md`. Requesting `/projects/ipad-2010/` loads the React fallback and redirects to `/mind`. The Vite standalone-route middleware does not include `ipad-2010`.

**Expected:** A standalone case at `/projects/ipad-2010/` with `← BACK TO MY MIND`, plus a THINK-floor hotspot that enters the route through the existing camera transition.

**Gap:** There is no page, route mapping, or hotspot entry to audit beyond the spec.

**Action:** In the implementation round, create `index.html`, add the route to the existing standalone middleware, and register an iPad room using percentage coordinates without changing the current building architecture.

**Dependency:** `code only` for routing and hotspot; page implementation depends on the assets listed below.

### Gap 02 — Core narrative and six-node journey are absent

**Current:** None of the required Hero, Challenge, Big Idea, Journey Overview, Ignite, Enter, Reveal, Experience, Amplify, Light the Map, My Role, Why It Works, or Final sections exist.

**Expected:** A single progression: `IGNITE → ENTER → REVEAL → EXPERIENCE → AMPLIFY → LIGHT THE MAP`, supported by the emotional journey `Mystery → Curiosity → Delight → Resonance → Motivation`.

**Gap:** The strategy cannot currently be understood, and `Light the Spark Within` is not represented anywhere in the portfolio.

**Action:** Build the semantic section order from the spec before adding decorative animation. Keep the project framed as a concept strategy proposal, with no invented Apple execution claims or KPIs.

**Dependency:** `code only` for structure and verified project copy; `existing project material` for factual detail.

### Gap 03 — Journey interactions and video evidence are absent

**Current:** There is no sticky journey map, active-node state, Spark interaction, Spark Corridor, Reveal video, feature-light network, Light the Map interaction, or map video.

**Expected:** The Journey Map must work as both information architecture and navigation; the page must progressively brighten while video evidence appears inside REVEAL and LIGHT THE MAP.

**Gap:** The required participatory journey has no functional expression. A static case page would not satisfy the spec.

**Action:** Implement the sticky/stepper journey state first, then Ignite and Corridor, then integrate verified videos, feature paths, and map illumination in their narrative nodes.

**Dependency:** `code only` for state and light-network behavior; `video` for Reveal and Light the Map; `new asset` for the corridor and maps.

## P0

### Gap 04 — Confirmed art direction has no production system

**Current:** No iPad asset directory or visual layer exists.

**Expected:** Charcoal gray, violet liquid glass, selective refraction, sparks, cinematic light, and a controlled transition from one spark to a brighter world.

**Gap:** There is no basis for judging fidelity to the confirmed four-panel art direction.

**Action:** Establish the charcoal/violet tokens and independent Spark, device, ribbon, corridor, map, and video-window layers. Do not flatten the reference board into a single background or fall back to a generic Apple product page.

**Dependency:** `new asset` plus `code only` composition.

### Gap 05 — My Role and strategic proof are absent

**Current:** No contribution statement or strategic rationale exists.

**Expected:** Accurate coverage of Experience Framework, Spark Corridor, Light Up the U.S. Map, Experience Narrative, and Pitch Integration, followed by Why It Works.

**Gap:** Reviewers cannot distinguish the candidate's work from the team proposal.

**Action:** Add the spec-approved collaborative wording after the journey is established; avoid sole-ownership claims.

**Dependency:** `existing project material` and verified role copy.

## P1

### Gap 06 — Responsive, media, and accessibility behavior cannot be evaluated

**Current:** There is no page DOM, CSS, media control, focus behavior, or reduced-motion path.

**Expected:** Desktop-first 1200–1440px composition, tablet scaling, mobile vertical stepper, keyboard-operable nodes, usable play/pause/replay, and a graceful reduced-motion state.

**Gap:** All responsive and accessibility acceptance checks are currently untestable.

**Action:** Include these requirements during implementation and verify them after core interactions exist.

**Dependency:** `code only`.

## P2

### Gap 07 — Secondary atmosphere and micro-motion are not available

**Current:** No grain, particle drift, refraction, residual glow, or subtle cosmic texture exists.

**Expected:** Restrained polish that supports the Spark progression without turning the interface into glass cards.

**Gap:** Polish is absent, but it should not be produced before the core journey works.

**Action:** Defer until all Blockers and P0 gaps pass.

**Dependency:** `code only` plus optional texture assets.

## Asset Gaps

All items are `ASSET NEEDED`; `public/assets/ipad-2010/` does not currently exist.

- **P0:** `hero-spark.webp` — WebP — tactile Hero spark focal point.
- **P0:** `ipad-2010.png` — transparent PNG — clean first-generation iPad cutout.
- **P0:** `spark-corridor.webp` or layered corridor files — WebP/PNG — ENTER environment.
- **P0:** `liquid-glass-texture.webp` — WebP — selective refraction material.
- **P0:** `journey-map-reference.png` — PNG — composition reference only.
- **P1:** `reveal-video.mp4` — MP4 — REVEAL node evidence.
- **P1:** `light-map-video.mp4` — MP4 — LIGHT THE MAP evidence.
- **P1:** `us-map.svg` and `world-map.svg` — SVG — interactive illumination maps.
- **P1:** `spark-particle.png` and `light-ribbon.svg` — PNG/SVG — reusable light interaction layers.
- **P1:** `jobs-stage.png` — PNG — verified AMPLIFY-stage visual if required by the source material.
- **P2:** `feature-draw.png`, `feature-read.png`, `feature-video.png`, `feature-work.png` — PNG — feature evidence after the network mechanism is working.

## Interaction Gaps

- Sticky Journey Map and active/passed/upcoming states: missing.
- Pointer-driven Spark and drag trail: missing.
- Scroll/pointer Spark Corridor: missing.
- Reveal count-up, cinematic playback, and replay: missing.
- Clickable feature-light network: missing.
- Individual-to-collective Light the Map behavior: missing.
- Page-brightness progression: missing.

## Visual Match

Not assessable because no page or assets exist. The implementation must be measured against `charcoal gray + violet liquid glass + spark/light + dreamy cinematic technology`; generic Apple minimalism and repetitive glass cards should be treated as visual failures.

## Route / Technical Health

- `/projects/ipad-2010/`: **BROKEN AS A CASE ROUTE** — currently redirects to `/mind` through the React wildcard.
- `public/projects/ipad-2010/index.html`: missing.
- `public/assets/ipad-2010/`: missing.
- Brain Building iPad hotspot: missing.
- Console errors: none observed during the fallback redirect, but there is no case runtime to test.

## Recommended Implementation Order

1. Secure the P0 visual reference assets and both project videos.
2. Create the route, page shell, accurate narrative structure, and Back to My Mind behavior.
3. Build the Journey Map state model and brightness progression.
4. Implement IGNITE and ENTER / Spark Corridor.
5. Integrate REVEAL and LIGHT THE MAP videos in context.
6. Build the feature-light network, AMPLIFY, My Role, Why It Works, and Final.
7. Add responsive, accessibility, performance, and P2 atmosphere polish.
