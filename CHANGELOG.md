# Changelog

All notable changes to Burnish are documented in this file.

Format: [Keep a Changelog](https://keepachangelog.com). Versioning follows [SemVer](https://semver.org). Early history (before v0.5.0) was not tracked; the project began life as the private **hallmark** codebase before being forked and renamed to Burnish.

## [Unreleased]

See [ROADMAP.md](ROADMAP.md): Nanobanana image hook + image-led *Plate* theme, brand-first flow, `burnish variant` verb, theme-aware motion tokens, structural cookbook, analytics `data-viz.md`, multi-page coherence, and a project-path mode for `study`.

## [1.1.0] — 2026-09-10

First public release on GitHub (after the repo restructure that moved the package to the repository root and split the standalone site into its own repository).

Highlights shipped in this release:

- **Four invocations** — default build · `audit` · `redesign` · `study`.
- **Twenty-one named catalogue themes**, rotated by a three-axis diversification rule (paper band · display style · accent hue) scoped to genre clusters.
- **Custom themes with two depths** — *tuned* (one-off OKLCH palette + free-font pairing) and *bespoke* (palette, type, and structure from first principles). Both bound by every slop-test gate.
- **Twenty-one macrostructures** and a **fifty-archetype component cookbook** (9 heroes · 5 section heads · 6 features · 4 CTAs · 4 testimonials · 8 footers · 14 navs), loaded index-then-pick.
- **Four genres** — editorial (default) · modern-minimal · atmospheric · playful.
- **58-gate slop test** and a six-axis pre-emit self-critique, plus the six universal disciplines (honest copy, locked tokens, no re-drawn chrome, mobile as a hard floor, typography purity).
- **Component-scope flow** — eight interaction states (default · hover · focus-visible · active · disabled · loading · error · success) with a demo wrapper, for single-element briefs.
- **`study` verb** — image and URL modes, refusal list, remote-URL safety checks, structured DNA schema, diagnosis → build-with-DNA → `design.md` emission with provenance attestation.
- **Portable `design.md`** and **four export formats** — `tokens.css` · Tailwind v4 `@theme` · DTCG `tokens.json` · shadcn/ui CSS variables.
- **Project memory** — `.burnish/log.json` rotation and `.burnish/preflight.json` caching; diversification inverted to consistency on `design.md`-managed projects.
- **Hero-enrichment hierarchy** (typography → Tier A CSS art → Tier B hand-built SVG → Tier C generated still → Tier D library → Tier E Lottie last resort) with honest placeholder strategy.
- **Generation test suite** in `site/_tests/` (eight briefs, eight distinct fingerprints) and verb demos in `site/_tests/verbs/`.
- **Docs** — nine worked briefs in `docs/recipes.md`, three `study` extractions in `docs/study-examples.md`, and the 2026 "Stop letting your agents ship ugly UIs" talk.

The 58-gate slop test grew from the 38 gates at v0.6.0 through gates 39–57 across the intermediate 0.7–1.0 releases (details not tracked).

## [0.6.0] — second pass · re-generated under the disclosure layers

Regression pass over the generation test suite. The eight `site/_tests/` pages were re-generated in a single rotating session under three new disclosure layers:

- Pre-flight scan (Step 0) — read existing tokens/fonts/framework before asking anything.
- Project-memory rotation (Step 2.5) — `.burnish/log.json` read before picking; diversification enforced across all eight builds.
- Upfront preview block (Step 5) — "Macrostructure · Theme · Enrichment · Sections · Motion · Slop test" before any code.

**Outcome:** every macrostructure unique, every theme unique across the eight briefs. The prior picks are preserved in the folder's git history.

## [0.6.0] — Tracejam fixes + SaaS expansion + visual gallery

- **Tracejam (test 05) defects fixed** — horizontal scroll suppressed via `html/body { overflow-x: clip }`; navbar centering + `line-height: 1`; wordmark to a distinct display face; hero highlight raised to x-height; decorative chrome dots made `aria-hidden`.
- **Three new slop-test gates** (now 38 total) — no horizontal scroll 320–1920 px; decorative text effects visually verified at x-height; interactive bars declare `align-items: center` + `line-height: 1`.
- **Default-on microinteractions** for Bento Grid, Stat-Led, Workbench, Marquee Hero, Conversational FAQ (counter reveal, pricing lift, marquee scroll, stagger). Editorial/Manifesto/Letter/Quote-Led/Long Document stay still.
- **SaaS page sequence** documented for B2B SaaS marketing macrostructures.
- **Wordmark guidance** — the wordmark may (and on Bento/Stat-Led/Workbench/Marquee Hero, should) use a different display face than the body.
- **Page-edge clipping discipline** — clipped-edge enrichment must pair with `overflow-x: clip` (never `hidden`, to preserve sticky).
- **Meridian (test 04) extended** from 7 to 11 sections (refusal anti-list, working rules, practice narrative, annotated bibliography).
- **Two new SaaS-focused tests** — Foundry (Stat-Led, pure-white paper, giant animated stat hero, real pricing + FAQ) and Cohort (Marquee Hero, continuous-scroll marquee, alternating feature rows, stagger-reveal testimonials).
- **Real visual thumbnails** on the example gallery (`_thumbs/*.png`), reskinned by the landing page's theme.
- README updates reflecting gate count and new rules.

## [0.5.0] — Tier 1, 2, and most of Tier 3 of the test-suite punch list

Items 1–11 and 13 from the `site/_tests/` improvement list shipped:

- Per-archetype copy fixtures for all 21 macrostructures.
- Sub-domain refinement of the genre/trio table.
- Documented three-axis theme-diversification rule.
- Free-vs-paid type pairings for every tone.
- Worked examples per hero-enrichment archetype.
- Different-knobs slop-test gate (gate 34).
- Four illustration recipes in `custom-craft.md`.
- Non-LLM voice samples across seven tones in `copy.md`.
- Mobile-collapse discipline in the component cookbook.
- `aria-label` slop-test gate (gate 35).
- Project memory — `.burnish/log.json`.
- Example gallery on the landing page.

Deferred: `study + redesign` combined verb; auto-generated OG cards.

## [0.4.0] and earlier

Not tracked. Burnish's prehistory lives under the private **hallmark** codebase; it was forked and renamed to Burnish, then restructured so the skill package, docs, and site became one repository.