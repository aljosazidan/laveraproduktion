# Lavera Produktion Status Tracker

A dashboard showing the production status of 36 Lavera products (288 images).
Each product card links directly to the Google Drive folder with the finished images.

## Quick Start

```bash
npm install
npm run dev
```

## Deploy to Vercel

```bash
npx vercel
```

## Project Structure

```
├── index.html          # Entry point
├── package.json        # Dependencies (React + Vite)
├── vite.config.js      # Vite config
└── src/
    ├── main.jsx        # React mount
    └── App.jsx         # Dashboard component (all data + thumbnails embedded)
```

## Status Legend

- 🟣 **Fertig** — Done, images in Google Drive
- 🟢 **Bestätigt** — Approved by Lavera, being finalized (labeling)
- 🟡 **Review** — Waiting for Lavera feedback
- ⬛ **NO/Stop** — Image not being produced

## Data Source

Extracted from `Produktion_Lavera.pdf` (377-page slide deck).
Google Drive folder links mapped from: `Q4_LAVERA_ALL_PRODUCTS > Product Collection > {Teint, Lips, Eyes}`
