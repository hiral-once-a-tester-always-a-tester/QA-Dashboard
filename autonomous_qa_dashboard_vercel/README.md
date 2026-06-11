# Autonomous QA Dashboard (Vercel-ready)

This package contains a self-contained interactive dashboard for an Autonomous QA function.

## Files
- `autonomous_qa_dashboard.html` — single-file dashboard (HTML/CSS/JS)
- `index.html` — same dashboard, renamed for static hosting
- `vercel.json` — minimal Vercel config for static deployment

## Deploy on Vercel
1. Create a new GitHub repo and upload the files.
2. In Vercel, import the repo.
3. Deploy — Vercel will serve the static files automatically.
4. Optional: drag-and-drop the folder into Vercel Drop for a quick prototype deployment.

## Customise
- Edit the `dashboard` object inside `index.html` / `autonomous_qa_dashboard.html`.
- Replace sample releases, risks, coverage values, implemented items, and future roadmap assumptions with your own.

## Features
- KPI cards: issues, risks, regressions, release readiness
- Interactive tabs for day-to-day QA, autonomy split, feasibility roadmap, and implemented practices
- Coverage bars and QA health trend chart
- Prioritised issues and release cockpit view
- Designed for leadership storytelling and practical team operations
