# 🏏 Suganth – Cricket Dashboard

A personal cricket statistics dashboard built with vanilla HTML, CSS, and JavaScript. It automatically loads match data from a Google Sheet and visualises batting and bowling performance across multiple dimensions.

---

## Features

- **Overall Stats** — At-a-glance career summary cards
- **Batting – Overview** — Career progression, runs per innings, rolling averages, year-on-year trends, dismissal analysis, win/loss performance, and seasonal trends
- **Batting – Position** — Stats broken down by batting position with composite ideal-position scoring
- **Batting – League** — Performance across different tournaments with win/loss splits
- **Batting – Phase** — Batting breakdown by powerplay, middle overs, and death overs
- **Batting – Consistency** — Score distribution, form trends, and milestone tracking
- **Batting – Ball by Ball** — Delivery-level analysis of scoring patterns
- **Bowling – Overview** — Over-by-over economy and wickets summary
- **Bowling – By League** — Bowling performance split across tournaments
- **Bowling – Phase** — Phase-wise bowling analysis (powerplay / middle / death)
- **Achievements** — Auto-generated badges and milestones (batting, bowling & special); accessible as a side panel on desktop and a slide-up drawer on mobile
- **Raw Data** — Full match-by-match table with sortable columns
- **PDF Export** — Print-ready export of the entire dashboard
- **CricClubs Integration** — Direct link to the player's CricClubs profile from the header

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
2. Open `index.html` in any modern browser
3. Data loads automatically from the linked Google Sheet

No server, no build tools, no dependencies to install.

---

## Project Structure

```
suganth_cricket/
├── index.html           # Single-file dashboard (all JS/CSS inline)
├── cricclubs-icon.png   # CricClubs logo used in the header link
└── README.md
```

---

## Author

**Sugumar** · [@pvsugumar](https://github.com/pvsugumar)
