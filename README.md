# Yattemiyo Tools Site

Official portfolio / product site for **Yattemiyo Tools**.

> ちょっと面倒を、ちょっと便利に。

## Current status

- Phase 1: one-page static portfolio
- **Single self-contained `index.html`**
- CSS / JavaScript / visual assets are embedded in the HTML
- No build step
- No npm dependencies
- GitHub Actions: **do not use until the account limit resets in October 2026**
- GitHub Pages deployment: deferred
- Current verification gate: local browser review

## Local preview on Windows

```powershell
git clone https://github.com/goroyattemiyo/yattemiyo-tools-site.git
cd yattemiyo-tools-site
git switch feat/initial-portfolio
start .\index.html
```

No server or install is required.

## Visual direction

- black / midnight navy / indigo
- restrained moonlight gold accents
- moon motif
- Konshu mascot
- concise copy; tools remain the main subject

The same Konshu brand icon is used in the header and footer. `コンシュ / Konshu` is presented separately in the About area without explanatory character lore.

## Structure

- Hero + 3-image visual slider
- Featured Tool: Threads Posting Tool
- Next Tools
- Philosophy
- Build in Public
- About / Konshu
- Footer

## Planned growth

When content grows, split into pages such as:

- `/tools/threads`
- `/about`
- `/support`
- `/privacy`
- `/terms`

At that point, move embedded assets out of `index.html` and consider a framework only if plain HTML becomes a real maintenance problem.