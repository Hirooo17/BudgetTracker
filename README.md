# Ipon Budget

An offline-first, mobile-friendly budget and savings tracker for GitHub Pages.

## Features

- Monthly and cut-off budget views with category progress bars
- Savings goals and emergency-fund progress
- Searchable transaction history
- Recurring monthly expenses
- Budget health insights and overspending warnings
- JSON export/import backups
- Installable PWA with service-worker offline caching

## Run locally

Because the service worker requires HTTP, use any static server:

```bash
npx serve .
```

Then open the printed local URL. Data is stored locally in the browser; no account or server is required.

## Deploy

The repository includes a GitHub Actions workflow that publishes the site to GitHub Pages after pushes to `main`.
