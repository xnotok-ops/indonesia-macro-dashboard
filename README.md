# 🇮🇩 Indonesia Macro Impact Dashboard

Interactive HTML infographic visualizing the economic impact of US-Iran geopolitical tensions on Indonesia — covering rupiah weakness, credit rating downgrades (Fitch & Moody's), and crude oil import diversification.

## Why I Built This

When the US-Iran conflict escalated, most Indonesians saw headlines but couldn't connect the dots: why does a conflict in the Middle East weaken the rupiah? Why did Fitch and Moody's downgrade Indonesia's outlook? How does crude oil import dependency fit in?

I built this to connect those dots visually.

## What It Covers

- **Rupiah Depreciation** — Timeline and magnitude of IDR weakness correlated with geopolitical events
- **Credit Rating Downgrades** — Visual comparison of Fitch and Moody's outlook changes for Indonesia
- **Oil Import Dependency** — Indonesia's crude oil import sources and diversification challenges
- **Macro Chain Reaction** — How geopolitical shock → oil prices → current account → currency → credit outlook

## Tech Stack

| Component | Tool |
|-----------|------|
| Frontend | HTML + CSS + JavaScript |
| Visualization | Charts.js / custom SVG |
| Data Sources | Bank Indonesia, BPS, Fitch, Moody's |
| Language | Bahasa Indonesia |
| Format | Static HTML (shareable, no server needed) |

## Project Structure

    indonesia-macro-dashboard/
    ├── index.html              # Main infographic page
    ├── css/
    │   └── styles.css          # Styling and responsive layout
    ├── js/
    │   └── charts.js           # Chart rendering and interactions
    ├── data/
    │   ├── rupiah_timeline.json # IDR/USD historical data
    │   ├── credit_ratings.json  # Fitch & Moody's rating history
    │   └── oil_imports.json     # Crude oil import breakdown
    ├── assets/
    │   └── icons/               # Flag icons, rating agency logos
    └── README.md

## Quick Start
```bash
git clone https://github.com/xnotok-ops/indonesia-macro-dashboard.git
cd indonesia-macro-dashboard
# Just open in browser — no build step needed
open index.html
```

Or deploy to GitHub Pages for sharing.

## Screenshots

> _Add screenshots here_
>
> ![Credit Downgrade Visualization](./screenshots/credit-downgrade.png)
> ![Oil Import Sankey](./screenshots/oil-imports.png)

## Key Visualizations

1. **Geopolitical Timeline** — Interactive timeline linking US-Iran events to IDR/USD movements
2. **Credit Downgrade Comparison** — Side-by-side Fitch vs Moody's rating changes with context
3. **Oil Import Sankey Diagram** — Where Indonesia's crude oil comes from and why diversification matters
4. **Chain Reaction Flow** — Animated flow showing geopolitical shock → economic impact pathway

## Target Audience

- Indonesian general public trying to understand macro economics
- Crypto/finance community on Indonesian Twitter (CT)
- Students and educators looking for accessible economic visualizations

## Data Sources

- Bank Indonesia (BI) — exchange rate data
- Badan Pusat Statistik (BPS) — trade and import data
- Fitch Ratings — sovereign credit outlook
- Moody's — sovereign credit outlook
- EIA / OPEC — crude oil market data

---

**Built by [@xnotok](https://x.com/xnotok)**


