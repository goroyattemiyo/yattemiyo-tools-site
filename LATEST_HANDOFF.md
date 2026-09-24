# Latest Handoff

## Project

- Project: Yattemiyo Tools portfolio site
- Repository: goroyattemiyo/yattemiyo-tools-site
- Target branch: feat/initial-portfolio
- Base branch: main
- Updated: 2026-09-24 JST

## Current Goal

Create the first local-previewable one-page portfolio for Yattemiyo Tools.

Acceptance criteria:

- [x] Static HTML + CSS only
- [x] Yattemiyo Tools concept visible above the fold
- [x] No.001 Threads Posting Tool shown as the featured product
- [x] File / Dev / Media future tool families visible
- [x] About / Build in Public included
- [x] No build step or external dependency
- [ ] User visual check on Windows
- [ ] GitHub Pages publication

## Current Status

- implemented-unverified

GitHub Actions cannot be used until the user's current limit resets in October 2026.
Do not use CI or GitHub Actions as part of this phase.

## Completed

- Initial one-page structure
- Responsive CSS
- Local-preview instructions
- Project handoff

## Remaining

- User local visual review
- Copy / layout adjustment from real browser feedback
- Decide logo / icon
- Add Privacy / Terms / Support before Plugin publication
- Publish only after local acceptance

## Decisions / Spec Changes

- Old: GitHub Pages could be enabled during initial implementation.
- New: publication is deferred; local browser verification is the only current visual gate.
- No framework for Phase 1. Add Astro or another framework only when multiple pages make plain HTML hard to maintain.

## Important Files

- `index.html`
- `styles.css`
- `README.md`
- `LATEST_HANDOFF.md`

## Verification

- [x] Static source review
- [ ] Manual browser check
- [ ] Responsive visual check on actual browser
- [ ] GitHub Pages

CI:
- Status: Not run
- Reason: Actions unavailable until October 2026; CI is intentionally excluded.

## Next Action

1. Clone / switch to `feat/initial-portfolio`.
2. Open `index.html` locally.
3. Review desktop and narrow-window layout.
4. Report visual / wording changes.
5. Apply minimal fixes on the same Draft PR.

## Do Not

- Do not run or add GitHub Actions for this phase.
- Do not enable deployment before local acceptance.
- Do not introduce npm / Astro / React yet.
- Do not rewrite working sections without a concrete usability reason.
