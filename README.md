# Yattemiyo Tools Site

Official portfolio / product site for **Yattemiyo Tools**.

> ちょっと面倒を、ちょっと便利に。

## For Muse / AI collaborators

**Read [MUSE_HANDOFF.md](./MUSE_HANDOFF.md) first.**

It contains the current design direction, approved public copy, real product scope, Konshu rules, asset map, and the things that must not be invented.

Concise approved copy is also separated in:

- [docs/SITE_COPY.md](./docs/SITE_COPY.md)

## Current status

- Phase: one-page portfolio redesign
- Working branch: `feat/initial-portfolio`
- Draft PR: #1
- Current implementation reference: `index.html`
- No npm dependency required
- No build step required
- GitHub Pages publication: deferred until user approval
- GitHub Actions: do not use as a preview/debug loop

## Local preview on Windows

```powershell
git clone https://github.com/goroyattemiyo/yattemiyo-tools-site.git
cd yattemiyo-tools-site
git switch feat/initial-portfolio
start .\index.html
```

## Asset map

### Canonical brand assets

`assets/brand/`

- `konshu-guide-master.png` — approved 2D Konshu master
- `konshu.webp` — web-friendly Konshu
- `brand-icon.webp`
- `hero-moon.webp`
- `crescent.webp`
- `cosmic-bg.webp`

**Do not regenerate or redraw Konshu.** Reuse the canonical asset.

### Product showcase visuals

`assets/showcase/`

- `01-threads-posting.webp`
- `02-sticker-tools.webp`
- `03-wms-android.webp`
- `04-ai-music-score-lab.webp`
- `05-irodori-tts-studio.webp`

These are presentation illustrations, not literal screenshots or proof of every UI detail.

## Current public information rule

The homepage should primarily use:

> **見出し → 1〜2行の説明 → 大きい画像**

Avoid filling the page with small status badges, technical tags, framework names, PASS labels, or dense architecture diagrams.

## Current showcase

1. Threads Posting Tool
2. LINEスタンプ作成ツール
3. WMS Android
4. AI Music Score Lab
5. Irodori TTS Studio

## Brand direction

- black / midnight navy / indigo
- restrained moonlight gold
- moon motif
- premium but personal
- useful tool first, AI second
- concise copy
- no cyberpunk / neon-heavy AI aesthetic

## Konshu

Approved public introduction:

> エジプトの月の神をルーツに持つ、Yattemiyo Toolsのマスコット。  
> 月夜と、新しい道具が生まれる場所に現れます。

Do not publicly define Konshu as an “案内役” or “見守り役”.

## Safety / release

- Do not invent product features, metrics, releases, or completed integrations.
- Do not expose secrets or private implementation data.
- Do not deploy, publish, or merge without explicit user approval.
- Keep Draft PR #1 until the design is accepted.
