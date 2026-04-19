# Dodgy Dave's Stock Predictions

An AI-powered stock analysis app. Enter up to 3 stock tickers,
fetch real price data, and get a GPT-4o-mini generated
buy/hold/sell report. Always correct 15% of the time.

**[Live Demo](#)** ← add Netlify URL once deployed

---

![Dodgy Dave Screenshot](screenshot.png)

---

## Features

- Add up to 3 stock tickers (e.g. MSFT, TSLA, AAPL)
- Fetches real stock price data from Polygon.io API
- Sends data to GPT-4o-mini with a custom trading analyst prompt
- Generates a 150-word buy/hold/sell report in seconds
- Loading states and error handling throughout

---

## Built with

- Vanilla JavaScript (ES6 modules)
- Vite (build tool + environment variables)
- Polygon.io API (stock price data)
- OpenAI API — GPT-4o-mini (report generation)

---

## Getting started

```bash
# Clone the repo
git clone https://github.com/greshchuk-dev/dodgy-daves-stock-predictions

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Add your API keys to .env

# Run locally
npm run dev
```

---

## Environment variables

Create a `.env` file in the root with:
