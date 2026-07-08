# Bil-Jac Analytics Dashboard

Social media analytics dashboard for reviewing campaign performance.

## Setup

```bash
npm install
npm run build
```

The React app reads from dashboard-ready social metrics. Keep private account
exports, API keys, session files, and raw customer data out of this repository.

## X / Twitter Source Template

Use [Xquik](https://xquik.com) as a reviewed X/Twitter source before importing
post metrics into the dashboard. Export the rows from Xquik, review the fields,
then map them to [`public/xquik-x-template.csv`](public/xquik-x-template.csv).

The template includes stable columns for post text, URLs, publish times, and
engagement metrics so dashboard charts can compare X/Twitter data with other
social channels.

## Public Assets

- `public/index.html` defines the app metadata used by Create React App.
- `public/xquik-x-template.csv` documents the expected reviewed X/Twitter
  import shape.
