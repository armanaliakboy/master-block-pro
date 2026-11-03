# Master Block PRO — Forex SMC starter

A static browser app for GitHub Pages. It displays candlesticks, a simple confirmed swing-break signal, ATR-based Entry/SL/TP1/TP2/TP3, and optional browser notifications.

## Publish with GitHub Pages
1. Create a GitHub repository (for example `master-block-pro`).
2. Upload `index.html` and this `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for the Pages URL shown there, then open it on your phone.

## Live data
- Get an API key from Twelve Data: https://twelvedata.com/
- Open the app, select a pair, paste the key, and press **Load live data**.
- The key is kept only in the current page session; do not hard-code it into a public repository.
- Free-plan limits and available symbols/intervals are controlled by the data provider. Browser requests may be blocked by provider CORS policy or plan restrictions.

## Important limitations
- Demo mode uses random simulated candles and must never be used for trading decisions.
- The SMC logic is deliberately a starter approximation: swing break/BOS and ATR-based risk levels. It is not a full institutional order-block/CHOCH engine and does not guarantee profitable signals.
- It does not connect to Tradeox or place trades. Use a demo account and verify data/signal timing before any live use.
- This is educational software, not financial advice.
