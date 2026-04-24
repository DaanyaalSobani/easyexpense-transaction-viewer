# EasyExpense Transaction Viewer

A React web app for visualising expense and income transactions exported from [EasyExpense](https://easyexpense.io/). Upload a CSV file and browse your transactions with a clean UI.

## Stack

- [React](https://react.dev/) (Create React App)
- [Tailwind CSS](https://tailwindcss.com/)

## Getting Started

```bash
npm install
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## CSV Format

The app expects the CSV format produced by EasyExpense. Sample files are included in `public/` (`Expenses.csv`, `Incomes.csv`) to test with.

## Build

```bash
npm run build
```

Produces an optimised production build in `build/`.
