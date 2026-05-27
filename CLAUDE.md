# CLAUDE.md — wellhub-spdd-site

Onboarding for any AI agent working in this repo.

## What this repo is

The **public** GitHub Pages mirror of the Wellhub SPDD / AI-native analysis.
Live at: https://fabiosampaio-91.github.io/wellhub-spdd-site/

It exists only because GitHub Pages can't serve a private repo on the free plan. It contains **only** published web assets (HTML/CSS/JS). The source of truth — analysis content, drafts, PDFs, the original proposal, meeting notes, business-case numbers — lives in the **private** companion repo `wellhub-spdd-analysis` (folder `presentation/`).

## ⚠️ This repo is PUBLIC and Google-indexable

**Never add private or sensitive content here.** Specifically, do not commit:

- Meeting transcripts or summaries.
- **Pricing, rates, internal cost numbers, effort estimates** — the business-case page here carries only the value/ROI narrative + qualitative framing. Hard numbers stay in the private repo.
- Any customer-internal detail not already approved for publication.

Anything pushed here may be cached or indexed even after deletion. If unsure, ask André or Fábio before publishing.

## Files

```
index.html          Analysis slide deck
analysis.html       Document view (the long-form read)
business-case.html  Business-case deck (narrative only — no sensitive numbers)
assets/styles.css, assets/nav.js
```

## How to update

This is a deployment target, not a place to author. To update:

1. Make the change in the private repo's `presentation/` (source of truth).
2. Copy the changed `*.html` / `assets/*` into this repo.
3. Sanity-check the diff for any private/pricing content (see warning above).
4. Commit & push. GitHub Pages redeploys automatically.

Commit or push **only when asked**.
