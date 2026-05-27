# wellhub-spdd-site

Public web mirror of the Wellhub SPDD / AI-native analysis.
Live at: https://fabiosampaio-91.github.io/wellhub-spdd-site/

> **This repo is public and Google-indexable.** It holds published web assets only — never meeting notes, pricing, or internal cost numbers. See [`CLAUDE.md`](CLAUDE.md).

The source of truth (analysis content, drafts, PDFs, the original proposal, meeting notes, business-case numbers) lives in the **private** companion repo `wellhub-spdd-analysis` (folder `presentation/`).

## Pages

- [`index.html`](index.html) — analysis slide deck
- [`analysis.html`](analysis.html) — document view (long-form read)
- `business-case.html` — business-case deck (narrative only) — _not yet published; lands via the publish step before the June 16 board meeting_

## Updating

1. Make the change in the private repo's `presentation/`.
2. Copy the changed `*.html` / `assets/*` here.
3. Check the diff for any private/pricing content.
4. Commit & push — GitHub Pages redeploys automatically.
