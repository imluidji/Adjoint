# Adjoint — TopStrike Companion Tool

A free companion tool for [TopStrike](https://play.topstrike.io), the real-time fantasy football trading game on [MegaETH](https://megaeth.com).

Adjoint helps you make smarter trades by combining matchday data, player stats, and lineup information in one place — so you don't have to juggle between Flashscore, TopStrike, and ten browser tabs.

## 🔗 Live

👉 **[Use Adjoint](https://YOUR_USERNAME.github.io/adjoint)** *(update after deploy)*

## What it does

**For new players:**
- Matchday overview with fixtures, player availability, and difficulty ratings based on bookmaker odds
- Adjoint Picks — automated player recommendations (Best Pick, Value Pick, High Risk)
- Budget Builder — enter your ETH budget, get a suggested XI
- Interactive football pitch to plan your matchday selections

**For experienced players:**
- All-in-one dashboard replacing the Flashscore + TopStrike tab-switching workflow
- 191 real on-chain TopStrike players with positions and clubs
- Bench shortlist (10 slots) for tracking extra players
- Matchday navigation across PL, Bundesliga, Serie A, and Champions League

## Roadmap

- [ ] API-Football integration (auto fixtures, predicted → confirmed lineups with notifications)
- [ ] On-chain price data from TopStrike smart contract (live bonding curve prices)
- [ ] Player performance scores from real matchday data
- [ ] IPO alerts and tracking
- [ ] Portfolio manager with eligibility countdown and price alerts
- [ ] Live matchday dashboard with real-time TopStrike scoring
- [ ] Matchday calendar (monthly view)
- [ ] Matchday recap (post-match analysis vs optimal picks)

## Tech

Currently a single-file HTML/CSS/JS prototype. Planned migration to a full stack with:
- Frontend: React or vanilla JS
- Data: API-Football (fixtures, lineups, stats) + MegaETH RPC (on-chain prices, supply)
- Notifications: TBD (Telegram bot, push notifications, or in-app)

## TopStrike Smart Contract

```
Address: 0xf3393dC9E747225FcA0d61BfE588ba2838AFb077
Network: MegaETH Mainnet
Audited by: Pashov Audit Group (Dec 2025)
```

## Play TopStrike

New to TopStrike? [Join here](https://play.topstrike.io?ref=SYNDICATE) — trade real football player cards and win ETH prizes every matchday.

## License

MIT
