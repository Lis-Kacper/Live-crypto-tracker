# Live-crypto-tracker

A small, single-page static web app created quickly using AI that shows live cryptocurrency prices and market data. The project is delivered as a single `index.html` file (no build step), so you can run it locally by opening the file in a browser or serving it from a simple HTTP server.

## Features
- Live price updates for selected cryptocurrencies
- Basic market data (24h change, market cap, volume)
- Simple, responsive UI implemented in one HTML file
- No backend required — uses public crypto APIs from the browser

## How to use
- The app displays real-time prices and basic market information. Use the on-page controls to change tracked coins, sort, or adjust refresh intervals (if such controls are present in the UI).
- If data appears stale, refresh the page or increase the refresh frequency in the UI (if available).

## Development
- This is a plain HTML/CSS/JavaScript project. Edit `index.html` to change the UI or update the data-fetching logic.
- No Node.js or build tools are required.
- If you need to test changes while avoiding browser caching, open DevTools and disable cache while DevTools is open.

## Data sources / API notes
- The app uses public crypto data from Binance Websocket 

## License
MIT License — see LICENSE (or add a LICENSE file if not present).

## Author
Lis-Kacper
