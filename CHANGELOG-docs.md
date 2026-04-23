# Documentation changelog

## 2026-04-23 — Gitbook Copy (Notion) sync

- Aligned user-guide copy with internal **Gitbook Copy** page in Notion (via Notion MCP): **culture markets** positioning, sign-in providers, deposits, token creation steps, anti-snipe numbers, fee distribution table, UGC feeds/eligibility/payouts, treasury proposal types, **Gnosis Safe** execution, referral fee-share lines, holder/profile/tier wording, trading surfaces, and FAQ answers (no TBD placeholders).

## 2026-04-22 — Trend-first rebuild

- Renamed user-facing vocabulary from **IP** to **trend** across user guides (legal pages still reference ITL/IPA).
- Reorganized Mintlify navigation into **Start → Account → Discover → Token page → Trading → Launch → Verification → Owners → Rewards → Safety → Reference**.
- Added `redirects` in `docs.json` for every legacy slug (`/user-guides/create/*`, `/user-guides/explore/*`, etc.).
- Replaced old screenshot call-outs with branded `/images/*.svg` documentation figures (swap for real PNGs anytime).
- Updated palette to match `ip.world/app/globals.css` tokens (`#0D0D0D`, `#AD74FE`, `#C093FF`, `#321F4D`) and set default appearance to **dark**.
- Replaced developer stub pages with sourced authentication and `/api` route tables.
- Added internal `STYLEGUIDE.md`, `VOICE_AUDIT.md`, and `SLUG_MATRIX.csv` for contributors.
