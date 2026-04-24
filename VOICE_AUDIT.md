# Voice audit - phrases to retire (execution checklist)

Scan complete when `rg` on `docs/` returns **zero** matches for the patterns below.

## Global replacements

| Retire | Replace with |
|--------|----------------|
| "Internet IP" as hero noun (user-facing) | **trend** or "idea / meme / brand" |
| "IP page" in user guides | **trend page** |
| "Create an IP" | **Create a trend** |
| "IPs & tokens" | **Trends and tokens** |
| "scaffold" / "Coming soon" / "content coming soon" | Real content or explicit "not public" one sentence |
| `<Note>` blocks that only say add a screenshot | Real `![](/images/...)` + descriptive alt text |
| "typically" / "commonly" / "often" / "may" / "might" / "roughly" | Commit to the number. If the number can change, commit AND add a one-line `<Note>` that the protocol sets it. |
| "confirm in the UI" / "follow the live app" / "subject to limits shown" | State the fact. The live UI is always the ultimate truth; documentation should not dodge the statement. |
| "some builds" / "your build" / "legacy builds" | There is one build. State what the product does now. |

## 2026-04-23 rewrite pass

Full rewrite pass completed. Every page in `user-guides/` and `dev/` was rewritten for confident, concrete prose. Concrete numbers committed as authoritative:

- Launch fee: **30 IP** (protocol-set; `<Note>` flags it as mutable).
- Opening buy: freeform amount; UI presets at **0.25%, 0.5%, 1%, 2%, 3%**.
- Anti-snipe: **2% per wallet, 5 min**.
- Networks: **Story + Solana only** (IP, USDC, SOL).
- Tiers: Normie ≤500 → Casual ≤2000 → Degen ≤6000 → Trencher ≤15000 → Legend ≤30000 → **GOAT** 30001+.
- Onboarding quests: **10 points** each (6 quests total).
- Referral bonus: **100 points** on signup, **10%** of referee trading-volume points ongoing.
- UGC payout cadence: **Fridays 12:00 PM PDT**, flat.
- Verification: 5-step form (Eligibility → Supporting Info → Verifier Details → IP Rights → T&Cs); review in **7 business days**.
- Trend-owner allocation: **3% of supply, 3-month linear vest**.
- Holder rewards: **30% of token-side fees, 50% of IP-side fees**.
- Community verification: **$1M MC, 1,000 holders, 5–7 days age**.
- Governance pass: `YES > NO` and `YES ≥ 10% + NO`.
- Search shortcut: **⌘K / Ctrl+K**.
- Governance: Snapshot + Gnosis Safe. **No shielded voting.**
