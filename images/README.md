# Documentation images

All figures live in this folder and are referenced from MDX as `/images/<filename>`.

## Conventions

- **Theme**: Dark, matching ip.world (`#0d0d0d` background).
- **Viewports**: Primary **1280×720** (desktop); optional **390×844** mobile captures use `*-mobile.svg` or PNG when added.
- **PII**: Blur wallet addresses, codes, and DMs in real screenshots. Until real captures ship, **branded SVG figures** (purple `#ad74fe` on `#0d0d0d`) document section intent without camera work.

## Asset manifest

| File | Used in | Alt text theme |
|------|---------|----------------|
| `auth-sign-in-order.svg` | `account/sign-in-methods` | Sign-in order: social, email, wallets |
| `auth-connected.svg` | `account/sign-in-methods` | Connected session overview |
| `explore-default.svg` | `explore/navigating-trends` | Explore grid |
| `explore-filters.svg` | `explore/search-filters-and-sort` | Filters and sort |
| `token-tabs-desktop.svg` | `tokens/token-page-overview` | Token page tab bar |
| `token-feed.svg` | `explore/social-feeds`, `tokens/token-page-overview` | Feed tab |
| `token-holders.svg` | `tokens/holders-and-transactions` | Holders tab |
| `token-transactions.svg` | `tokens/holders-and-transactions` | Transactions tab |
| `token-comments.svg` | `tokens/comments` | Comments tab |
| `token-treasury.svg` | `manage/treasury-and-proposals` | Treasury / proposals |
| `trade-panel.svg` | `trading/overview`, `trading/payment-methods` | Trade panel |
| `create-trend.svg` | `launch/create-a-trend` | Create trend flow |
| `create-token.svg` | `launch/create-a-token` | Launch token flow |
| `manage-owner.svg` | `manage/trend-owner-dashboard` | Owner dashboard |
| `rewards-leaderboard.svg` | `rewards/points-and-leaderboard` | Leaderboard |
| `profile-referrals.svg` | `rewards/referrals`, `account/profile-and-stats` | Referral link UI |
| `diagram-earning-flow.svg` | `rewards/overview` | Earning programs overview |
| `platform-map-nav.svg` | `platform-map` | Navigation map |

## Compression / EXIF

When replacing SVGs with PNG screenshots: strip EXIF, run `pngcrush` or `oxipng`, and re-run the repo grep for wallet-like hex strings.
