# Pennywise Expense Tracker

A responsive personal-finance dashboard built with **HTML, CSS and vanilla JavaScript**. Track income and expenses, monitor a monthly budget, and keep your financial data on your own device.

## Features

- Dashboard with total balance, monthly income, expenses and savings rate
- Add, edit and delete transactions
- Expense categories, dates, notes, search and filters
- Six-month income-versus-expense chart
- Monthly budget and category spending overview
- Reports and quick financial insights
- Export transactions to CSV
- **Download and restore a full JSON backup**
- **Light and dark themes** with saved preference
- Responsive layout for desktop, tablet and mobile
- Input validation and keyboard-friendly dialog controls

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. No package installation, backend, or internet connection is required.

## Data and privacy

Transactions, budget settings and theme preference are stored in browser `localStorage`. Nothing is sent to a server. Data is specific to the browser and device. Use **Backup** regularly to download a JSON copy. **Restore** replaces the currently stored transactions and budget with the selected backup.

## Project structure

- `index.html` — app structure
- `styles.css` — responsive styling and themes
- `app.js` — application logic and local storage
- `LICENSE` — MIT License

## Tech stack

HTML5, CSS3 and vanilla JavaScript (ES6+), including Canvas and localStorage.

## Notes

The app starts with sample transactions on a fresh browser so the dashboard is populated for demonstration. You can edit or delete them and enter your own records.
