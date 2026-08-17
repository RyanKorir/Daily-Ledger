# Daily Ledger

A personal, self-hosted study and task tracker styled like a weekly calendar. Built to juggle multiple learning tracks (ALX, networking, game dev, language test prep, etc.) without losing momentum on any single one.

## Features
- **Weekly calendar view** — click any time slot to add a task, drag tasks to move them
- **Custom categories** — rename and recolor each goal/track to whatever you're actually working on
- **Auto-suggested recurring tasks** — optional daily rotation across your tracks so no single goal gets neglected (toggle on/off)
- **Shuffle** — reshuffle upcoming recurring tasks that aren't done or manually pinned yet, to keep things from feeling repetitive
- **Today's checklist** — a plain crossed-off list view alongside the calendar
- **Evening report + log** — jot what you learned each day; past entries resurface after 1/3/7 days as a lightweight recall prompt
- **In-app reminders** — optional toast + sound alert when a scheduled task's time arrives (while the tab is open)
- **Streak tracking**
- **Reset all data** — wipe everything and start fresh whenever you want

## Usage
This is a single self-contained HTML file — no build step, no dependencies to install.

1. Open `index.html` directly in a browser, **or**
2. Serve it as a static site (GitHub Pages works — see below)

All data is stored locally in your browser via the Storage API used by the page, so it persists between visits on the same device/browser.

## Hosting on GitHub Pages
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Under **Source**, choose the `main` branch and `/ (root)` folder
4. Save — your ledger will be live at `https://<your-username>.github.io/Daily-Ledger/`
