# 🌅 Circadian Almanac

An evidence-based, single-file web application that calculates personalized biological circadian windows using local solar positioning (`SunCalc`) and individual chronotype anchors. Designed to sit alongside tools like `salat-almanac.html`.

## 📌 Features

- **Hybrid Science Engine**: Combines real GPS solar coordinates (Sunrise, Solar Zenith) with $T_{\text{min}}$ (Core Temperature Minimum) phase calculations.
- **Dynamic Chronotype Calibration**: User-adjustable habitual wake and sleep inputs recalculate biological windows live.
- **Honest Confidence Tiers**: Distinguishes between hard solar anchors (🟢 High), validated biological windows (🔵 Medium), and population estimates (🟡 Estimate).
- **DLMO Evening Light Cutoff**: Highlights the crucial Dim-Light Melatonin Onset window to safeguard sleep architecture.
- **Native iCal (.ics) Export**: One-click export to Google Calendar, Apple Calendar, or Outlook.
- **Zero-Dependency Infrastructure**: Pure HTML, CSS, and Vanilla JS with CDN-based `SunCalc.js`. Fully compatible with GitHub Pages hosting.

## 🚀 Quick Start / Deployment

1. Drop `circadian-almanac.html` directly into your repository (e.g., alongside `salat-almanac.html`).
2. Commit and push to GitHub:
   ```bash
   git add circadian-almanac.html README.md
   git commit -m "feat: Add Circadian Almanac single-file web engine"
   git push origin main
