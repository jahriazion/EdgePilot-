# EdgePilot – Crypto Bot Application

![Dark UI Screenshot](screenshot-dark-ui.png)

## Overview
EdgePilot is a full-stack cryptocurrency monitoring and alerting application built for real-time BTC and XMR analysis.  
It runs a technical analysis engine using multiple timeframes and triggers buy/sell alerts based on custom strategies.

## Features
- 🔍 Multi-timeframe TA: 15m / 30m / 1h / 4h / 1D / 1W
- 📈 BTC strength tracking
- 🚨 XMR breakout & dip-band detection
- 📊 RSI, Volume, EMA/MA strategy integration
- 📬 Configurable push / haptic alerts
- 🌗 Light & dark theme UI

## Tech Stack
**Frontend:** React Native + Expo  
**Backend:** Node.js + Express  
**APIs:** Crypto price feeds (CoinGecko, Binance API, etc.)  
**Hosting:** Vercel / Netlify for PWA builds

## Getting Started
```bash
# Clone the repo
git clone https://github.com/YOUR-USERNAME/edgepilot.git
cd edgepilot

# Install dependencies
npm install

# Create env file
cp .env.example .env
# Fill in real API keys in .env

# Start development server
npx expo start
