# Muse Handoff — Yattemiyo Tools Portfolio

Updated: 2026-10-28 (JST)  
Repository: `goroyattemiyo/yattemiyo-tools-site`  
Working branch: `feat/initial-portfolio`  
PR: Draft PR #1

## 1. Purpose

This repository is the working source for the **Yattemiyo Tools** portfolio / product site.

The next design pass may be done by Muse.  
Muse should be able to understand the intended site from this repository alone without inventing product features or recreating the brand character.

The site goal is simple:

> **見た人が、見出し・短い説明・画像だけで「こういうものか」と直感的に分かること。**

The homepage is not a technical specification page.

---

## 2. Source-of-truth order

When documents conflict, use this priority:

1. This `MUSE_HANDOFF.md`
2. Latest explicit decisions recorded in `LATEST_HANDOFF.md`
3. Current `index.html`
4. Existing assets under `assets/`
5. Older copy / old mockups

Do not treat an old label, mockup, image text, or historical README statement as current product truth when a newer decision exists.

For actual product capabilities, do not invent details. The public copy below is intentionally conservative and was prepared from repository-verified scope.

---

## 3. Brand

### Name

**Yattemiyo Tools**

### Main message

> **ちょっと面倒を、ちょっと便利に。**

Supporting phrase:

> **まずは、やってみよう。**

Current hero direction:

> **「それだけやってくれればいい」をAI時代に。**

### Brand feeling

- premium but approachable
- quiet moonlit night
- black / deep midnight navy / Japanese indigo
- restrained moonlight gold / champagne accents
- minimal
- handcrafted / personal-tool feeling
- useful tool first, AI second

### Avoid

- cyberpunk
- neon-heavy UI
- generic purple/blue “AI gradient”
- dense dashboards used only as decoration
- excessive glassmorphism
- meaningless 3D objects
- large amounts of tiny metadata
- corporate SaaS copy that loses the personal-tool feeling

Current site palette reference:

- background: `#07090D` / `#0B1020`
- navy: `#10182D`
- indigo: `#18264A` / `#213A63`
- champagne: `#D7C48A`
- silver: `#C9CED8`
- off-white: `#E9EDF3`

---

## 4. Public information-design rule

The latest rule for the visible site is:

### **見出し → 1〜2行の説明 → 大きい画像**

Use large visual areas and generous spacing.

Do **not** automatically add:

- product numbers
- tiny English category labels
- status chips
- PASS / VERIFIED badges
- framework names
- implementation tags
- architecture matrices
- small technical feature lists

Technical facts may exist in the repository, but they do not all belong on the homepage.

A visitor should understand the product category before reading implementation details.

---

## 5. Konshu — canonical mascot

### Public name

**コンシュ / Konshu**

### Approved public introduction

> **エジプトの月の神をルーツに持つ、Yattemiyo Toolsのマスコット。**  
> **月夜と、新しい道具が生まれる場所に現れます。**

This copy was approved after the current `index.html` version and should be incorporated in the next design.

### Critical visual rule

**Do not regenerate, redraw, reinterpret, or “improve” Konshu.**

Previous generative versions changed the character too much. Use the supplied canonical asset directly.

Approved / reusable assets:

- `assets/brand/konshu-guide-master.png` — approved 2D full-body master
- `assets/brand/konshu.webp` — web-friendly Konshu asset
- `assets/brand/brand-icon.webp` — brand icon

Important identity features:

- rounded white hood / robe
- black face
- large white eyes
- **no black pupils**
- recognizable black beak
- two front buttons
- small black feet
- preserve the original silhouette and proportions

Do not publicly describe Konshu as an “案内役” or “見守り役”. Keep the character introduction above.

---

## 6. Existing visual assets

### Brand / world assets

- `assets/brand/brand-icon.webp`
- `assets/brand/konshu-guide-master.png`
- `assets/brand/konshu.webp`
- `assets/brand/hero-moon.webp`
- `assets/brand/crescent.webp`
- `assets/brand/cosmic-bg.webp`

### Product showcase visuals

- `assets/showcase/01-threads-posting.webp`
- `assets/showcase/02-sticker-tools.webp`
- `assets/showcase/03-wms-android.webp`
- `assets/showcase/04-ai-music-score-lab.webp`
- `assets/showcase/05-irodori-tts-studio.webp`

The showcase images are **presentation illustrations**, not literal screenshots or proof of every UI detail.

Use them to communicate the product intuitively.  
Do not infer unsupported features from text that happens to appear inside an illustration.

---

## 7. Product showcase — approved public direction

The site currently focuses on these five real projects.

### Threads Posting Tool

**Heading**

> Threads Posting Tool

**Short explanation**

> ChatGPTとの会話から、Threadsの予定確認・下書き・修正・キャンセル・承認まで。

**What is actually important**

The product surface is conversational. Do not replace it with a fictional analytics dashboard.

Verified tool-flow concepts include scheduled-post viewing, draft creation, update, cancel, and explicit approval. Human approval is intentionally part of the design.

Visual:

`assets/showcase/01-threads-posting.webp`

---

### LINEスタンプ作成ツール

This is the public-facing heading.  
The repository/project name may still appear as **Yattemiyo Sticker Tools**, but the homepage should make the use case obvious first.

**Heading**

> LINEスタンプ作成ツール

**Short explanation**

> 静止画も、動くスタンプも。画像を整えて、規格チェックから提出ZIPまで。

**Scope**

It supports ordinary static stickers **and** animated stickers. APNG is an implementation capability, not the entire product identity.

Current grounded flow includes image preparation, grid splitting, animated APNG generation, rule validation, main/tab image generation, and ZIP packaging.

Do not imply automatic submission to LINE Creators Market.

Visual:

`assets/showcase/02-sticker-tools.webp`

---

### WMS Android

**Heading**

> WMS Android

**Short explanation**

> 手元の音楽や動画を保存して、ライブラリから気持ちよく再生するAndroidプレーヤー。

Core product ideas include local media, Library, Playlist, mini/full Player, playback controls, and visualizer surfaces.

Do not present it as a generic image/video editor.

Visual:

`assets/showcase/03-wms-android.webp`

---

### AI Music Score Lab

**Heading**

> AI Music Score Lab

**Short explanation**

> 音源を解析してMIDIやMusicXML、譜面へ。人が確認しながら演奏できる形へ近づけていく。

Important honesty rule:

This project has produced editable drafts and conversion outputs, but the current documented song transcription is **not a fully musically approved finished score**.

Do not market it as perfect automatic transcription.

Visual:

`assets/showcase/04-ai-music-score-lab.webp`

---

### Irodori TTS Studio

**Heading**

> Irodori TTS Studio

**Short explanation**

> 声をデザインし、台本から音声を作って、WAVや動画素材までまとめて出力する。

The project helps run the IrodoriTTS workflow through a browser / Colab-oriented interface. VoiceDesign, script/chunk handling, speech generation, WAV use, and optional video conversion are the main visual ideas.

Do not imply that this repository contains or owns the underlying Irodori-TTS model itself.

Visual:

`assets/showcase/05-irodori-tts-studio.webp`

---

## 8. AI Plugin Lab

Keep **AI Plugin Lab** as a site section / expertise area, but keep it visually simple.

Core message:

> **作る。つなぐ。移植する。**

Current explanation direction:

> ChatGPTで作ったToolを、MCPを核にClaudeやGeminiへ。  
> ひとつの道具を、いろいろなAIで使える形へ育てていく実験です。

Important distinction:

- ChatGPT / MCP / OAuth / live Threads publish have been verified in the Threads Posting work.
- Claude and Gemini portability are future / next work unless newer repository evidence says otherwise.

Do not display planned compatibility as completed.

A simple representative visual is preferable to a dense architecture panel on the homepage.

---

## 9. Philosophy / creator

### Philosophy

> **「機能がある」と「また使いたくなる」は違う。**

The site should feel like small useful freeware evolved for the AI era.

### Creator

**ごろー / goro_yattemiyo**

Current tone:

> AIで「ちょっと便利」を作る人。  
> 昔からフリーソフト好き。  
> まずは、やってみよう。

The existing site also mentions long-time use of IrfanView. It may remain if it fits the design, but avoid turning About into a long biography.

---

## 10. Current repository implementation

Current phase:

- one-page static portfolio
- `index.html` is the current working implementation / visual reference
- no npm dependency is required
- no build step is required
- showcase visuals are external files under `assets/showcase/`
- canonical reusable brand assets are under `assets/brand/`
- older decorative images may still be embedded as data URLs inside `index.html`

Muse may clean up the implementation if it helps maintainability, but should not introduce a framework merely for style.

Keep changes understandable and easy to preview locally.

---

## 11. What Muse is being asked to do

Use the existing work as source material and create / refine a polished Yattemiyo Tools portfolio.

Priorities:

1. Make the site immediately understandable visually.
2. Keep the moonlit premium Yattemiyo identity.
3. Let the five product visuals carry the explanation.
4. Keep copy short.
5. Preserve canonical Konshu exactly.
6. Make desktop and mobile both feel intentional.
7. Keep technical claims conservative and grounded.
8. Reuse the provided assets before creating new imagery.

A redesign is allowed. Inventing new product capabilities is not.

---

## 12. Do not do

- Do not regenerate Konshu.
- Do not invent products such as Smart Rename / Log Packager unless real repository evidence is added later.
- Do not invent user counts, revenue, release dates, performance metrics, or “production ready” claims.
- Do not turn concept illustrations into factual UI claims.
- Do not expose secrets, tokens, IDs, or private implementation data.
- Do not add GitHub Actions as a design-preview mechanism.
- Do not deploy / publish / merge without explicit user approval.
- Do not convert the site into a framework project without a concrete maintenance reason.
- Do not fill the homepage with small labels and technical metadata.

---

## 13. Review checklist

Before presenting the next version:

- [ ] Five product areas are recognizable from title + short copy + image
- [ ] Static and animated LINE stickers are both represented
- [ ] AI Music Score Lab is not overclaimed
- [ ] Konshu uses the canonical asset without redraw
- [ ] Konshu origin copy is included
- [ ] No fake product or unsupported feature appears
- [ ] Desktop layout checked
- [ ] Mobile layout checked
- [ ] No horizontal overflow
- [ ] No deployment performed
- [ ] No GitHub Actions run just to preview the site

