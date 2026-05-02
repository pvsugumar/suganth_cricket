# 🏏 Suganth – Cricket Dashboard

A personal cricket statistics dashboard built with vanilla HTML, CSS, and JavaScript. It automatically loads match data from a Google Sheet and visualises batting and bowling performance across multiple dimensions.

---

## Features

- **Overview** — Career progression, runs per innings, rolling averages, year-on-year trends, dismissal analysis, win/loss performance, and seasonal trends
- **Position Analysis** — Stats broken down by batting position with composite ideal-position scoring
- **League Analysis** — Performance across different tournaments with win/loss splits
- **Phase Analysis** — Batting breakdown by powerplay, middle overs, and death overs
- **Consistency** — Score distribution, form trends, and milestone tracking
- **Bowling** — Over-by-over economy, wickets, and phase-wise bowling analysis
- **Achievements** — Auto-generated badges and milestones based on career data
- **Raw Data** — Full match-by-match table with sortable columns
- **PDF Export** — Print-ready export of the entire dashboard

---

## Tech Stack

| Library | Purpose |
|---|---|
| [Chart.js 4.4](https://www.chartjs.org/) | All charts and visualisations |
| [PapaParse 5.4](https://www.papaparse.com/) | CSV parsing from Google Sheets |
| Vanilla JS / HTML / CSS | No frameworks, no build step |

---

## Data Source

Match data is pulled automatically from a **Google Sheets CSV** (published to web). No manual data import needed — just open the file and the latest stats load instantly.

---

## How to Use

1. Clone or download this repo
2. Open `suganth-cricket-dashboard.html` in any modern browser
3. Data loads automatically from the linked Google Sheet

No server, no build tools, no dependencies to install.

---

## Project Structure

```
suganth_cricket/
├── suganth-cricket-dashboard.html   # Single-file dashboard (all JS/CSS inline)
└── README.md
```

---

## Author

**Suganth** · [@pvsugumar](https://github.com/pvsugumar)
