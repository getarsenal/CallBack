# Callback — Interview Tracker

A single-file, offline-friendly web app to track every job-interview process in one place:
companies, rounds, interviewers, notes, comp, and one-tap **AI briefs** to spin up a new
chat that helps you prep, write your intro, and research interviewers.

No build step, no dependencies, no accounts. All data lives in your browser (with JSON
export/import for backup).

## Use it
Open `index.html` — that's it. Hosted via GitHub Pages, then **Add to Home Screen** on
mobile for an app-like, full-screen experience.

## Features
- **Dashboard** — active processes, advance rate, "coming up", and a follow-up radar that
  flags anything gone quiet 7+ days
- **Pipeline** — drag-and-drop Kanban board by interview stage
- **All Roles** — sortable, searchable table of everything
- **Upcoming** — calendar of interviews, tasks, and offer deadlines
- **Insights** — which sources actually convert, and comp in play
- **AI Brief** — copy a ready-to-paste brief / "prep me" / "write my intro" prompt for any
  role, plus per-interviewer research prompts

## Cloud sync
Settings (⚙) → **Cloud sync** connects the app to a free Supabase project so your phone and
computer stay in sync via a private sync code. Optional — local-only by default.

## Backup
Settings (⚙) → **Export backup** saves a JSON snapshot. Import it on any device to restore.

## iOS App Store
See [APP_STORE.md](APP_STORE.md) for the Capacitor packaging + submission runbook.
[privacy.html](privacy.html) is the hostable privacy policy required by App Store Connect.
