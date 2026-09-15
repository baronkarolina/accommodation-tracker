# Accommodation Tracker

Dashboard for tracking rental/housing applications — built to make flat-hunting less chaotic.

## What it does

- Track listings through a status pipeline: **New → Interested → Shortlisted → Applied → Rejected**
- Log key details per listing: rent, neighbourhood, postcode, commute time, transport cost, whether bills are included, and free-text notes
- See at-a-glance summary stats: average rent, average commute, and how many listings are within budget
- Export your data to **CSV** (for Excel/Sheets) or **JSON** (for backup/restore)
- Everything is saved locally in the browser via `localStorage` — no backend, no account, no data leaves your machine

## Why I built it

I used this to track my own student housing search — comparing dozens of listings on price, commute, and status quickly got messy in a spreadsheet, so I built a small dashboard tailored to exactly the fields I cared about.

## Tech stack

Plain **HTML, CSS, and vanilla JavaScript** — no frameworks, no build step, no dependencies. Just open the file in a browser.

## Running it

Clone the repo and open `index.html` (or `accommodation_tracker.html`) directly in any browser — that's it.

```bash
git clone https://github.com/baronkarolina/accommodation-tracker.git
cd accommodation-tracker
open index.html   # or just double-click the file
```

Or, if GitHub Pages is enabled on this repo, view it live at:
`https://baronkarolina.github.io/accommodation-tracker/`

## Data & privacy

All listings you add are stored only in your own browser's `localStorage` — nothing is sent anywhere. Use the **Export JSON** button to back up your data, and **Import JSON** to restore it (e.g. on a different device or browser).

## Possible improvements

- Sync across devices (currently local-only by design)
- Map view of listings by commute time / price
- Reminders for application deadlines

## License

Personal project, shared for portfolio purposes.
