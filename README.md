# SpendSense — Smart Personal Budget Planner

A polished, interactive personal finance dashboard built with **HTML, CSS, and vanilla JavaScript**. No backend, database, package installation, build step, or API key is required.

## Run it locally

1. Download and extract `SpendSense.zip`.
2. Open the extracted `SpendSense` folder.
3. Double-click `index.html` to open it in your browser.
4. That's it. The app works directly from the file system. For a more app-like local preview, open the folder in VS Code and use the Live Server extension.

## Features

- Dashboard with income, expenses, net cash flow, and savings rate.
- Month selector and six/three/twelve-month cash-flow charts.
- Category spending breakdown and budget progress indicators.
- Add, edit, delete, search, and filter income/expense transactions.
- Customizable monthly category budgets.
- Insights and context-aware money nudges based on recorded data.
- Currency preferences (INR, USD, GBP, EUR) and display name.
- Export monthly reports as text, transaction lists as CSV, and full data backups as JSON.
- Restore JSON backups and reset the sample data.
- Responsive layout for desktop, tablet, and mobile.
- Demo transactions are included so the dashboard is populated on first launch.
- Data is stored in browser `localStorage`; there is no server or account login.

## Files

- `index.html` — app structure and modals
- `style.css` — responsive styling
- `script.js` — app logic, demo data, charts, filters, storage, import/export
- `README.md` — this guide

## Important data note

SpendSense stores information only in the current browser on the current device. It does not sync between devices and clearing browser site data may remove your records. Use **Settings & data → Export backup** regularly. The included transactions are fictional demo data; replace or delete them for personal use.

## Deploy as a static website on AWS

This app has no build step. You can deploy the three app files (`index.html`, `style.css`, and `script.js`) as a static site using AWS Amplify Hosting or an S3 static website setup. Review AWS pricing and public-access settings before deploying. Because data is stored in each visitor's browser, visitors do not share or centrally save transactions.
