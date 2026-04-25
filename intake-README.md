# Intake

A minimal mobile-friendly calorie and macro tracker. Single HTML file, no dependencies, no backend.

## Features

- Log meals with calories, protein, carbs, and fat
- Daily totals with progress bar against calorie goal
- Editable calorie goal
- Data persists in localStorage (per device, per browser)
- Resets daily — clear manually or entries persist until removed

## Setup

No build step. Drop `index.html` into any static host.

To publish on GitHub Pages:
1. Create a repo (e.g. `intake`)
2. Upload `index.html`
3. Go to Settings → Pages → deploy from main branch
4. Access at `https://jeffreyparravano.github.io/intake`

## Usage

- Enter a food name, calorie count, and macros → tap **+ Add**
- Tap **×** on any entry to remove it
- Tap **Edit** next to the goal to set your daily calorie target
- **Clear all** wipes the day's log

## Notes

- Data lives in the browser's localStorage — not synced across devices
- Rename the file to `index.html` before uploading to GitHub Pages
