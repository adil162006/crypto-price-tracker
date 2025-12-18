
# Crypto Price Tracker

Simple crypto price tracker built with React and Vite. Fetches data from the CoinGecko API and shows price, market data and details for individual coins.

**Live demo**: https://cypto-price-tracker-99.netlify.app/

**Source (GitHub)**: https://github.com/adil162006/crypto-price-tracker

**Quick features:**
- **Price list:** View top cryptocurrencies with current price and 24h change.
- **Details page:** Click a coin to see market data and price history on `/coin/:id`.
- **Responsive UI:** Works on desktop and mobile screens.

**Tech stack:** React, Vite, plain CSS, CoinGecko API

**Getting started**

Prerequisites: Node.js (16+ recommended) and npm or Yarn.

Install dependencies:

```
npm install
```

Run development server:

```
npm run dev
```

Build for production:

```
npm run build
```

Preview production build locally:

```
npm run preview
```

**Usage**
- Open the app at `http://localhost:5173` (or the port shown by Vite).
- Click any coin card on the home page to open the details view (for example: `/coin/bitcoin`).

**Project structure (important files)**

- `src/App.jsx` — App root and routes
- `src/main.jsx` — App bootstrap
- `src/pages/Home.jsx` — Home / listing page
- `src/pages/CoinDetails.jsx` — Coin details page
- `src/components/CryptoCard.jsx` — Card component for each coin
- `src/api/coinGecko.js` — API helpers for CoinGecko
- `src/utils/formatter.js` — helpers for number & currency formatting

**API**
This project uses the public CoinGecko API (no API key required). See `src/api/coinGecko.js` for request logic.

**Notes & next steps**
- Improve error handling and loading states.
- Add caching or SWR for fewer network calls.
- Add charts for price history (e.g., Chart.js or Recharts).

**Author**: adil162006

**License**: MIT
