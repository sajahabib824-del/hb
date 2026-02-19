# Hand Particle Saturn — Final v2

This version addresses UI positioning, removes the previous 'Text via' hint, and improves low-light detection heuristics.

## Changes in v2
- removed "Text via ?text=HELLO"
- moved & reduced the hint so it doesn't overlap camera preview
- improved low-light handling using percentile-based sampling to pick brightness/contrast multipliers
- watermark "by Abb" present
- Edit button for changing text live; short text => large font, long text => smaller font
- Adaptive performance tuning retained

## Run
Serve over HTTPS or localhost. Example:
- `python -m http.server 8000`
- `ngrok http 8000` for mobile testing