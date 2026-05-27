# wellhub-spdd-site

Public web mirror of the Wellhub SPDD / AI-native analysis.
Live at: https://fabiosampaio-91.github.io/wellhub-spdd-site/

> **This repo is public and Google-indexable.** It holds published web assets only — never meeting notes, pricing, or internal cost numbers. See [`CLAUDE.md`](CLAUDE.md).

The source of truth (analysis content, drafts, PDFs, the original proposal, meeting notes, business-case numbers) lives in the **private** companion repo `wellhub-spdd-analysis` (folder `presentation/`).

## Pages

| Page | What it is | Source | Live |
|---|---|---|---|
| [`index.html`](index.html) | Analysis slide deck | this repo | https://fabiosampaio-91.github.io/wellhub-spdd-site/ |
| [`analysis.html`](analysis.html) | Document view (long-form read) | this repo | https://fabiosampaio-91.github.io/wellhub-spdd-site/analysis.html |
| `business-case.html` | Business-case deck (narrative only) | _pending_ | _not yet published; lands before the June 16 board meeting_ |
| [`assets/styles.css`](assets/styles.css), [`assets/nav.js`](assets/nav.js) | Shared CSS + TOC highlighter | this repo | — |

## Updating

1. Make the change in the private repo's `presentation/`.
2. Copy the changed `*.html` / `assets/*` here.
3. Check the diff for any private/pricing content.
4. Commit & push — GitHub Pages redeploys automatically.
