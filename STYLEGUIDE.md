# ip.world documentation style (internal)

This file is for **contributors and AI editors**. It is not published on Mintlify.

## Voice

- **Plain and direct**: Short sentences. No enterprise filler (“leverage,” “solutions,” “delightful”).
- **Second person**: Write **you** for procedures; **we** only for platform facts (“ip.world tracks points…”).
- **Dual audience**: Where it helps, add one line each for **degens** vs **normies** (see existing “10-second version” pattern).
- **Honest about risk**: Crypto can lose money. No price promises, no “moon” copy.

## Vocabulary (User guide)

- **Trend**: User-facing name for the umbrella page that groups related tokens (canonical idea / meme / brand).
- **Token**: The tradable market. If the UI still shows **Remix**, mention once: “token (labeled Remix in the app)” and link [Glossary](/user-guides/reference/glossary).
- **IP / IPA / PIL / ITL**: Use on **verification and licensing** pages only, plus the glossary. Do not lead with “IP” in general guides.

## In-app string fidelity

When documenting flows, **quote UI and toast strings exactly** when it helps support (e.g. “Copied to clipboard”, “Please connect your wallet before submitting a comment”). Verify strings in `ip.world` before shipping.

## Mintlify components

- `<Steps>` / `<Step>` for procedures.
- `<CardGroup>` / `<Card>` on hub pages; titles use **verbs** (“Connect TikTok”, “Open the trade panel”).
- `<Tip>` shortcuts; `<Warning>` irreversible or funds loss; `<Note>` caveats **without** “add screenshot later”.
- `<Accordion>` for dense legal / Story links on licensing pages.

## Visual parity (with the app, not a clone)

Reference colors from the app token file conceptually:

| Role | Hex |
|------|-----|
| Background | `#0D0D0D` |
| Brand | `#AD74FE` |
| Lavender surface | `#DFCDF9` |
| Deep purple text on lavender | `#321F4D` |
| Border | `#313131` |

Docs site styling is controlled via [docs.json](docs.json) and [style.css](style.css).

## Typography

The web app uses **Archivo** and **Geist** in places. Mintlify may not load custom fonts; if previews look off, keep copy tight and rely on Mint defaults-do not block shipping on font parity.

## Frontmatter (every published MDX page)

```yaml
---
title: "Page title"
description: "One line for SEO"
last_verified: "2026-04-22"
---
```

Update `last_verified` when you re-check the live app or backend.

## Banned

- “Coming soon”, “TBD”, “placeholder”, “screenshot to be added”, scaffold language.
- Ambiguous **creator** → use **trend owner**, **UGC creator**, or **token deployer**.
