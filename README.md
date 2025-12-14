# Live-crypto-tracker

A small, single-page static web app that shows live cryptocurrency prices and market data. The project is delivered as a single `index.html` file (no build step), so you can run it locally by opening the file in a browser or serving it from a simple HTTP server.

## Features
- Live price updates for selected cryptocurrencies
- Basic market data (24h change, market cap, volume)
- Simple, responsive UI implemented in one HTML file
- No backend required — uses public crypto APIs from the browser

## Quick start
1. Clone the repository:
   git clone https://github.com/Lis-Kacper/Live-crypto-tracker.git
2. Open the app:
   - Double-click `index.html` or open it from your browser's File → Open menu
   - Recommended: run a simple local server to avoid CORS/mixed-content issues:
     python3 -m http.server 8000
     # then open http://localhost:8000 in your browser

## How to use
- The app displays real-time prices and basic market information. Use the on-page controls to change tracked coins, sort, or adjust refresh intervals (if such controls are present in the UI).
- If data appears stale, refresh the page or increase the refresh frequency in the UI (if available).

## Development
- This is a plain HTML/CSS/JavaScript project. Edit `index.html` to change the UI or update the data-fetching logic.
- No Node.js or build tools are required.
- If you need to test changes while avoiding browser caching, open DevTools and disable cache while DevTools is open.

## Data sources / API notes
- The app uses public crypto data APIs (for example CoinGecko or similar). If you decide to switch providers or use a provider that requires an API key, you may:
  - Add the key to the front-end (not recommended for secret keys), or
  - Proxy requests through a small server to keep keys secret.
- If opening `index.html` directly causes CORS or mixed-content issues, serve the repo over HTTP as described above.

## Contributing
- Contributions are welcome. Please open an issue to discuss changes or submit a pull request with a clear description of the change.
- Keep changes lightweight and avoid introducing a build step unless necessary.

## License
MIT License — see LICENSE (or add a LICENSE file if not present).

## Author
Lis-Kacper
