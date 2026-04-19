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
VITE_OPENAI_API_KEY=your_openai_api_key_here
VITE_POLYGON_API_KEY=your_polygon_api_key_here

Get your keys from:
- OpenAI: platform.openai.com
- Polygon.io: polygon.io

---

## What I learned

This project taught me how to chain two APIs together —
first fetching real financial data, then passing it as
context to an AI model with a custom system prompt.
Managing async flows with Promise.all and handling
partial failures was the most challenging part.

---

## Author

Iryna Greshchuk · [GitHub](https://github.com/greshchuk-dev) ·
[LinkedIn](https://linkedin.com/in/iryna-greshchuk-3a9807337)


