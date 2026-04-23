# Voice audit — phrases to retire (execution checklist)

Scan complete when `rg` on `docs/` returns **zero** matches for the patterns below.

## Global replacements

| Retire | Replace with |
|--------|----------------|
| “Internet IP” as hero noun (user-facing) | **trend** or “idea / meme / brand” |
| “IP page” in user guides | **trend page** |
| “Create an IP” | **Create a trend** |
| “IPs & tokens” | **Trends and tokens** |
| “scaffold” / “Coming soon” / “content coming soon” | Real content or explicit “not public” one sentence |
| `<Note>` blocks that only say add a screenshot | Real `![](/images/...)` + descriptive alt text |

## Files that contained screenshot placeholders (pre-rebuild)

All cleared during rebuild; grep should stay clean:

- `user-guides/getting-started.mdx`, `app-tour.mdx`, `what-is-ipworld.mdx`
- `user-guides/account/*`, `user-guides/create/*`, `user-guides/explore/*`
- `user-guides/manage/*`, `user-guides/verification/*`, `user-guides/rewards/*`, `user-guides/growth/referrals.mdx`
- `user-guides/reference/reporting-and-moderation.mdx`
- `index.mdx`, `dev/index.mdx`, `dev/api.mdx`, `dev/authentication.mdx`, `dev/webhooks.mdx`

## Rewards wording

- Remove “we intentionally do not document…” — document **what the UI shows**; link `base/docs` only as “engineering detail”.
