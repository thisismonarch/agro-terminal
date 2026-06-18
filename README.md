# 🌾 Agro Terminal Pro

A web-based agricultural commodity trading terminal demo. Track prices across eight commodities, place trades, manage a portfolio, and explore trade routes, compliance, and weather — all in a single self-contained HTML file.

**🔓 Demo mode:** enter *any* email and password to sign in.

## Features

- **Multi-commodity dashboard** — maize, wheat, rice, cocoa, coffee, palm oil, soybeans, and cassava with live-style price metrics, country breakdowns, and global market share.
- **Flexible units & currencies** — toggle prices between per-kg and per-tonne (with bulk-volume discount) and switch display currency on the fly.
- **Quick Buy & Advanced Trading** — place orders with risk management (position sizing, stop-loss/take-profit), then track open positions, holdings, P&L, win rate, and an equity curve.
- **Route optimization** — freight, transit, and savings across trade lanes, with AI-style routing insights.
- **Compliance & weather** — tariff/certification status and growing-region conditions per commodity.
- **Price alerts & market volatility popups** — set price targets and get notified on moves.

## Run it

It's a single file with no build step. Either:
- Open `index.html` directly in a browser, **or**
- Deploy to any static host (Netlify Drop, Vercel, GitHub Pages).

## Tech

Plain HTML, CSS, and JavaScript. Charts via [Chart.js](https://www.chartjs.org/) (loaded from CDN, so an internet connection is needed for charts to render).

## Note

This is a **demo / prototype**. All market data is simulated, state is in-memory (it resets on refresh), and the Solana/Pyth wallet and settlement features are cosmetic (devnet). It is not connected to live markets and is not intended for real trading.
