# Recruiting Profile Builder

A web app for managing the college baseball recruiting process: player profiles, game logging, coach email generation, college target lists, and contact tracking.

## What it does

- **Profile builder** — one-page recruiting profile with measurables, academics, contact info, and narrative
- **Game logger** — pitching, hitting, and fielding stats per game with season total auto-calculation
- **Email generator** — tailored cold-email templates for JUCO, NAIA, D3, plus follow-ups
- **College database** — 35 pre-loaded schools across CA/AZ/CO/UT/OR, filterable by division and state
- **Contact tracker** — email status, follow-up reminders (7/10-day flags), per-school notes
- **To-do list** — 35-item recruiting checklist across video, measurables, documents, outreach, and development

## Data

All data stays in your browser (localStorage). Use the "Export data" button to download a JSON backup. Use "Import data" to restore on another device.

## Deploy

This is a single `index.html` file. Drop it in any static host:
- **Vercel**: import the GitHub repo, deploy. Done.
- **Netlify**: drag the folder into the dashboard.
- **GitHub Pages**: enable Pages on the repo, point at `main` branch root.

## Local use

Open `index.html` in any modern browser. No build step, no dependencies.
