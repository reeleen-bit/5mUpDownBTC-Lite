# 5mUpDownBTC — Live Crypto Price Tracker for Polymarket

A live price tracker for Polymarket's 5-minute crypto markets.

---

## What it does

Polymarket's 5-minute Up/Down markets settle against a specific price, fixed the moment each window
opens — the **Price to Beat**. 5mUpDownBTC shows you that price live, on the exact same feed
Polymarket itself uses to resolve the market, alongside a live chart, so you can see where the price
stands before you place a bet. Covers seven markets: **BTC, ETH, SOL, XRP, DOGE, BNB and HYPE**.

**Try it free, right now:** https://pro.5mupdownbtc.com/cryptor-free.html
**Get PRO:** https://www.5mupdownbtc.com/

No sign-up required to try Lite. No spam, ever.

---

## Lite vs PRO

| Feature | Lite | PRO |
|---|:---:|:---:|
| **Included in both** | | |
| Exact Price to Beat, all 7 markets | ✔ | ✔ |
| Live market sync (always the current 5-min window) | ✔ | ✔ |
| Drawing tools (trend lines, notes) | ✔ | ✔ |
| Vertical price-axis zoom | ✔ | ✔ |
| Lifetime updates, delivered automatically | ✔ | ✔ |
| **Chart control — PRO** | | |
| Chart resolution | 2s only | 1s → 1D (13 timeframes) |
| Horizontal pan / time zoom | — | ✔ |
| Moving averages (MA7 / MA25 / MA99) | — | ✔ |
| Session markers | — | ✔ |
| **Decision tools — PRO** | | |
| 10 previous Price to Beat levels, plottable | — | ✔ |
| Statistical projection with uncertainty band | — | ✔ |
| Live Polymarket odds & edge | — | ✔ |
| Volume & anomaly alerts | — | ✔ |
| Pattern & correlation analysis | — | ✔ |
| Historical market insights | — | ✔ |

One-time payment, lifetime access. No subscription.

**Get PRO:** https://www.5mupdownbtc.com/

---

## What's in this repo

`cryptor-free.html` — the Lite build above, as a single self-contained file. No build step, no
external dependencies beyond public APIs (Polymarket's live feed, Binance for chart history). Open
it directly in a browser, or host it anywhere that serves static HTML.

**PRO user manual (PDF):** https://18fef2f3-3349-469f-96e6-3f6f0186f1aa.usrfiles.com/ugd/18fef2_f9993e7353634cc0a242d0c643e13d23.pdf

### How it works, briefly

- Live prices and the Price to Beat come from Polymarket's public RTDS WebSocket feed
  (`wss://ws-live-data.polymarket.com`) — the same relay Polymarket's own site uses to display and
  resolve these markets.
- Chart history comes from Binance's public REST API.
- No API key or backend required to run this build as-is.

---

## Disclaimer

5mUpDownBTC is a data and analysis tool. Everything it displays — projections, scores, signals and
alerts — is indicative only and is never financial advice. Prediction markets carry a risk of total
loss of the amount staked. Always do your own research before placing any trade.

Provided as-is, for personal use. Not licensed for resale or redistribution of the PRO version.
