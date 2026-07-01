# 🥾 The Python Trailhead

**A 6-month, day-by-day roadmap from your first line of Python to a finished, portfolio-ready project.**

![weeks](https://img.shields.io/badge/weeks-24-2C6E5A) ![days](https://img.shields.io/badge/days-168-D9A544) ![no build](https://img.shields.io/badge/build%20step-none-5C7A8A) ![deps](https://img.shields.io/badge/dependencies-zero-B8C9B2)

A single self-contained HTML file — no framework, no build step, no install. Open it in a browser and start Day 1.

---

## What it is

Six "base camps" (months) → twenty-four weeks → **168 daily sessions**. Every day gives you:

- **A topic** — the specific thing you're learning that day
- **Hours** — how long to spend (1.5 hrs weekdays, 2.5 hrs Saturday project time, 1 hr Sunday review)
- **"You'll be able to"** — the concrete outcome, so progress is measurable, not vague
- **"Try it"** — a hands-on practice task, because reading about Python isn't the same as writing it

Progress is tracked with checkboxes that save automatically as you go — a trail-map bar at the top fills in as you move through each camp, and small badges light up at 25/50/75/100%.

## The route

| Camp | Weeks | Focus |
|---|---|---|
| 1 — Python Foundations | 1–4 | Variables, control flow, loops, strings, first lists |
| 2 — Data Structures & Functions | 5–8 | Lists/tuples/sets/dicts, functions, lambda/map/filter, recursion |
| 3 — OOP, Errors & Modules | 9–12 | Classes & inheritance, exceptions, file I/O, modules, venv |
| 4 — Data, APIs & the Real World | 13–16 | JSON, requests, regex, web scraping, pandas/numpy, SQLite |
| 5 — Building Real Applications | 17–20 | Git & GitHub, Tkinter GUIs, Flask, testing & debugging |
| 6 — Capstone & Launch | 21–24 | Plan, build, document, and ship one original project |

## Using it

**Locally**
```bash
git clone https://github.com/<your-username>/<repo>.git
cd <repo>
open python_trailhead_roadmap.html   # macOS — or just double-click the file
```

**On GitHub Pages**
1. Push this repo to GitHub.
2. Go to **Settings → Pages** and set the source to your default branch, root folder.
3. Either rename `python_trailhead_roadmap.html` to `index.html`, or, once Pages is live, share the direct link to the file (e.g. `https://<username>.github.io/<repo>/python_trailhead_roadmap.html`).

No server, database, or backend is required — it's a static page.

## How progress saving works

Checkbox state is stored in the browser via `localStorage`, keyed per browser/device (there's no account or sync — clearing your browser data clears your progress). A **Reset all progress** button is included if you want to start clean.

> Note: this file also runs correctly inside Claude.ai as an Artifact, where it automatically uses Claude's built-in storage instead of `localStorage`.

## Customizing

Everything — pace, topics, project ideas — is meant to be adjusted. A few common tweaks:

- **Slower pace:** stretch each week across 10–12 days instead of 7; the "outcome before speed" philosophy already assumes some weeks will run long.
- **Different focus:** swap Month 4's data/API track for something like automation, game dev, or your own subject area — the structure (topic → outcome → practice) works for any curriculum.
- **Design:** all styling is in one `<style>` block at the top of the file — colors are CSS custom properties (`--pine`, `--amber`, `--moss`, etc.) if you want to re-theme it.

## Who this is for

Complete beginners who want a structured, self-paced path to becoming someone who can build their own Python projects from scratch — not just follow tutorials.

## License

No license file is included yet. Add one (MIT is a common, permissive choice) if you'd like others to freely reuse or adapt this roadmap.

---

*Six base camps. Twenty-four weeks. One hundred and sixty-eight days of walking, not running.*
