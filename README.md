# CNG Network Intelligence

**Advanced Station-Level Demand Forecasting · Sales · RTO · Network Expansion Optimizer**

A polished, responsive decision-support web application inspired by the CNG Network Scout reference, rebuilt with a closer visual match (dark sidebar + clean light main area) and significantly more advanced interactive features.

## What’s new / more advanced

- Visual language matches the reference (dark navy sidebar, light main canvas, yellow synthetic banner, KPI cards, risk list, quick links)
- Animated KPI counters
- Station Explorer with utilization risk filters + capacity/peak columns
- Multi-model demand forecast (Actual / Baseline / Capacity ceiling) with station selector
- Utilization distribution doughnut
- Interactive map with risk-only toggle (color-coded by utilization)
- Transparent multi-criteria site ranking model
- Live What-if Simulator (A/B/C scenarios + festival demand shock slider that updates the chart in real time)
- Working CSV download from Reports
- Full auth flow: Login → Sign Up → Demo OTP (`123456`) → Dashboard
- Fully responsive (mobile sidebar + overlay)

## How to run

1. Extract the zip
2. Open `index.html` **or** serve the folder:
   ```bash
   npx serve .
   ```
3. Login with any email + password (≥ 6 chars) → enter OTP **123456**

## Demo credentials

- Email: any valid format
- Password: any ≥ 6 characters
- OTP: **123456**

## Data

- Station master context from the 344-record Gujarat directory
- All demand / capacity / RTO numbers are **synthetic** and clearly labelled

## Tech

- Pure HTML / CSS / JS (no build step)
- Chart.js + Leaflet
- Works on any static host (Netlify, Vercel, GitHub Pages, S3…)

© 2026 · Decision-support prototype · Not an official Gujarat Gas product
