# Latest Handoff

## Project

- Project: Yattemiyo Tools portfolio site
- Repository: goroyattemiyo/yattemiyo-tools-site
- Target branch: feat/initial-portfolio
- Base branch: main
- Updated: 2026-09-30 JST

## Current Goal

Create a polished one-page Yattemiyo Tools portfolio using the current night / moon / Konshu brand direction.

Acceptance criteria:

- [x] Premium black / navy / indigo visual direction
- [x] Generated moon imagery integrated into the actual HTML
- [x] Generated cosmic / crescent decoration integrated into the actual HTML
- [x] Header and footer use the same Konshu brand icon
- [x] `コンシュ / Konshu` name is visible without explanatory character copy
- [x] No.001 Threads Posting Tool remains the featured product
- [x] Copy is intentionally concise
- [x] AI Plugin Lab added for ChatGPT / MCP / future Claude / Gemini expansion
- [x] Desktop and mobile layouts render without horizontal overflow
- [ ] User final visual acceptance
- [ ] GitHub Pages publication

## Current Status

- `checked`

The visual redesign is implemented and browser-rendered locally. Publication remains deferred.

GitHub Actions cannot be used until the user's account limit resets in October 2026. Do not use CI or GitHub Actions for this phase.

## Completed

- Silent visual slider: removed VISUAL count/pause/slide labels; images now lead with only arrows and progress dots
- Information design pass: English micro-labels reduced across Tools / Philosophy / Build / About
- Consistent Konshu brand icon for header/footer/favicon
- Hero visual slider: moon / Konshu workshop / Konshu night
- Generated moon image integrated
- Generated moonlit landscape integrated into Philosophy
- Generated cosmic texture integrated into tool/build surfaces
- Generated gold crescent ornament integrated into headings/About
- About split into creator + `コンシュ / Konshu`
- AI Plugin Lab simplified into a clearer evidence-first layout: one verified case, one architecture view, three design principles, and next-port targets
- Small explanatory filler copy reduced further; non-essential English micro-labels removed
- Current Phase 1 is a self-contained `index.html` with embedded visual assets
- Plugin Lab separates verified facts from next targets: ChatGPT / OAuth / live publish are shown as verified; Claude / Gemini remain planned compatibility work
- Responsive static site retained with no framework or build step

## Remaining

- Implement and verify the same MCP tool flow on Claude when scheduled
- Implement and verify Gemini custom-app compatibility when eligible / available
- User final visual review
- Adjust wording / spacing only if review finds a concrete issue
- Confirm final Threads / note links before public release
- Add Privacy / Terms / Support before Plugin publication
- Enable public hosting only after acceptance

## Decisions / Spec Changes

- Plugin Lab direction: portfolio should accumulate evidence of cross-AI Plugin / MCP integration expertise, not just claim expertise.
- Old visual direction: light / ivory Modern Freeware.
- New visual direction: premium nocturnal black / navy / indigo with restrained moonlight gold.
- Old mascot treatment: placeholder / explanatory "guide / watcher" copy.
- New mascot treatment: Konshu is shown as a brand character with the name only; no unnecessary role explanation.
- Header/footer icon mismatch is eliminated: both use the same embedded asset.
- `styles.css` is no longer required; CSS, JS and current image assets are embedded in `index.html` for the one-page phase.

## Important Files

- `index.html`
- `README.md`
- `LATEST_HANDOFF.md`

## Verification

- [x] static review
- [x] desktop browser render: 1440 x 1000
- [x] mobile browser render: 390 x 844
- [x] no horizontal overflow in either viewport
- [x] JavaScript slider initialized without page errors
- [x] Simplified Plugin Lab structure / responsive rules reviewed
- [x] Lab content grounded in verified 2026-09-30 Threads Posting results
- [ ] user manual review
- [ ] GitHub Pages
- [ ] CI (intentionally not run)

## CI

- Status: `Not run`
- Reason: GitHub Actions unavailable until October 2026 and intentionally excluded from this phase.

## Next Action

1. User reviews the current HTML visually.
2. Apply only concrete visual/copy corrections.
3. Keep Draft PR until local acceptance.
4. Add public/legal pages before Plugin publication.

## Do Not

- Do not run or add GitHub Actions for this phase.
- Do not enable deployment before user acceptance.
- Do not introduce npm / Astro / React yet.
- Do not re-add verbose explanatory mascot copy.
- Do not invent product metrics, versions, release dates, or usage counts.

## 2026-10-01 Project Showcase Integration

- Replaced placeholder tool cards with five grounded project showcase cards:
  1. Threads Posting Tool
  2. Yattemiyo Sticker Tools
  3. WMS Android
  4. AI Music Score Lab
  5. Irodori TTS Studio
- Added generated section visuals under `assets/showcase/`.
- Portfolio copy is based on repository-verified current scope/status; no Smart Rename / Log Packager placeholders remain.
- AI Music Score Lab is explicitly labeled `編集ドラフト検証中`; the visual is a concept illustration and does not assert musical approval.
- Generated showcase images are presentation visuals, not literal screenshots/specification evidence.
- Browser render validation remains user/manual because automated browser navigation is blocked in the current environment.
- GitHub Actions were not run.

## 2026-10-01 Title + explanation + image

- Public presentation rule changed to: heading + 1–2 line explanation + large image.
- Removed visible project numbers, technical tags, status labels, verification chips, architecture micro-panels, and numbered build-step cards from the main content presentation.
- Repository/source verification remains mandatory internally; verified details should not automatically become homepage microcopy.
- Goal: a first-time visitor should understand the kind of tool from the title, short explanation, and visual without reading metadata.
