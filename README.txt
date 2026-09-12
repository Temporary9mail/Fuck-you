Trading Strategy Vault — Gemini-only AI version

AI analysis:
- Google Gemini vision only
- Upload a chart screenshot, choose market/pair and candle timeframe
- Gemini returns UP or DOWN + confidence + reason + risk
- STOP is not used as a signal; if evidence is weak Gemini is instructed to choose the more likely direction with lower confidence
- Future Signals also uses Gemini only
- Twelve Data is optional market-data context and may not match Quotex OTC pricing

Setup:
1. Open ai-config.js
2. Put your Gemini API key in GEMINI_API_KEY
3. Optional: put Twelve Data key in TWELVE_DATA_API_KEY
4. Keep GEMINI_MODEL as gemini-3.8-flash unless your account uses another supported model
5. Upload all files to GitHub Pages root

Security:
Browser-side API keys are visible to visitors. Use a restricted/auth key and usage limits. For real secret protection, use a backend/proxy.

This is an educational chart-analysis tool. No signal is guaranteed to be accurate or profitable.
