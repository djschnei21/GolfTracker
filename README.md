# 2026 British Open Fantasy Golf Pool

Lightweight, mobile-first single-page app for a fantasy golf pool leaderboard.

## What it does

- Pulls live PGA leaderboard data from ESPN's public endpoint.
- Calculates each manager's score using the **best 5 of 6** golfers.
- Automatically applies the **weekend last-place penalty score** for missed-cut golfers.
- Uses tie-breakers when team totals are tied.
- Supports manager row expansion to view full roster details.

## League rosters included

All required managers, picks, and tiebreakers are preloaded directly in `index.html`.

## Deploy to GitHub Pages (zero build step)

1. Push this repository to GitHub.
2. In GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, choose:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (or your preferred branch), `/ (root)` folder
4. Save. GitHub will publish the site and provide a URL.

Because this app is a plain `index.html` file with Tailwind loaded by CDN, no build process is required.

## Local usage

Open `index.html` directly in a browser, or serve the folder with any static server.
