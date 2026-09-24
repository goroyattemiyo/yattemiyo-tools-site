# Yattemiyo Tools Site

Official portfolio / product site for **Yattemiyo Tools**.

> ちょっと面倒を、ちょっと便利に。

## Current status

- Phase 1: one-page static portfolio
- HTML + CSS only
- No build step
- No npm dependencies
- GitHub Actions: **do not use until the account limit resets in October 2026**
- GitHub Pages deployment: deferred
- Verification: local browser only for now

## Local preview on Windows

```powershell
git clone https://github.com/goroyattemiyo/yattemiyo-tools-site.git
cd yattemiyo-tools-site
git switch feat/initial-portfolio
start .\index.html
```

No server or install is required for the current version.

## Planned growth

Phase 1 starts as a single page. When content grows, split into pages such as:

- `/tools/threads`
- `/about`
- `/support`
- `/privacy`
- `/terms`

Do not add a framework until the one-page structure becomes a real maintenance problem.
