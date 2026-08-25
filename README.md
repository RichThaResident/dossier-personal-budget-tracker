# Dossier Budget Tracker

A simple, offline-first personal budget tracker for Rich Tha Resident X Dossier.

Built as a single self-contained HTML file — no backend, no build step, no dependencies. Works entirely in the browser, including offline.

## Live tool

Once GitHub Pages is enabled for this repo, the tool will be available at:

https://richtharesident.github.io/dossier-budget-tracker/

## Features

- Set a monthly budget and track spending against it, month by month
- Log expenses under six simple categories: **Savings, Food, Gas, Credit, Bills, Other**
- Visual donut/pie chart of spending by category, colored using the Dossier logo palette (gold, green, black)
- Month-by-month navigation to review past spending
- Remaining budget shown in green when under, red when over
- All data stored locally in your browser (no account, no server)

## Usage

1. Open the tool (via the Pages link above, or the HTML file directly)
2. Enter your monthly budget and tap **Set**
3. Log expenses as they happen — pick a category, enter the amount, tap **Add to This Month**
4. Use the arrows at the top to review previous or upcoming months
5. Tap the **×** next to any expense to remove it

### iOS tip

Add the page to your Home Screen from Safari for a native app-like experience.

## Categories

Kept intentionally simple — six fixed categories, no custom category creation, so tracking spending stays quick and doesn't turn into a chore:

- **Savings** — money set aside
- **Food** — groceries, eating out
- **Gas** — fuel and transportation
- **Credit** — credit card / debt payments
- **Bills** — rent, utilities, subscriptions
- **Other** — everything else

## Data & privacy

All budget data is stored locally in your browser's storage on your device. Nothing is sent to a server. This means:

- Your data stays private to whichever device/browser you use
- Data does **not** sync across devices — the same file opened locally vs. via GitHub Pages are treated as separate storage locations
- Clearing your browser's site data will erase saved budget history

## License

See [LICENSE.md](./LICENSE.md).
