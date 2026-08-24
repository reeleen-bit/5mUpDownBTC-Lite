# 5mUpDownBTC — Live Price to Beat tracker for Polymarket

A free, browser-based tool for Polymarket's **5-minute Up/Down** crypto markets (BTC, ETH, SOL, XRP, DOGE, BNB, HYPE).

It tracks the exact price each market settles on — captured from the same live Chainlink feed
Polymarket itself uses to resolve these markets — and displays it alongside a live candlestick chart,
so you always know the level price needs to clear before the window closes.

**Live demo:** https://pro.5mupdownbtc.com/cryptor-free.html
**Full product page:** https://www.5mupdownbtc.com/

## What it does

- **Live Price to Beat**, updated automatically at every new 5-minute window, for all seven markets
- **Live candlestick chart** with moving averages (MA7/25/99)
- **Session history**, captured server-side around the clock — even if you weren't watching
- Runs entirely in the browser — no install, no account, no sign-up

## What's in this repo

This repo contains the **free (Lite)** build only: `cryptor-free.html`, a single self-contained file
(no build step, no external dependencies beyond public APIs). Open it directly in a browser, or host
it anywhere that serves static HTML.

A paid **PRO** version exists with additional tools (more timeframes, chart drawing tools,
support/resistance, statistical projection, full session history, and more) — see the product page
for details.

## How it works, briefly

- Live prices and the Price to Beat come from Polymarket's public RTDS WebSocket feed
  (`wss://ws-live-data.polymarket.com`), the same relay Polymarket's own site uses.
- Chart history comes from Binance's public REST API.
- No API key or backend is required to run the free build as-is.

## Disclaimer

This is a data and analysis tool. It does not provide investment advice, recommendations, or
performance guarantees. Prediction markets carry a risk of total loss of the amount staked. Always
do your own research.

## License

Provided as-is, for personal use. Not licensed for resale or redistribution of the PRO version.
