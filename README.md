# Texas 2026 Tracker

Static site: `index.html` loads its numbers from `data/*.json`.

- `page.html` is the tracker page; `tools/build_site.py` wraps it into `index.html`.
- `data/` is refreshed by scheduled jobs (early vote twice daily; results on election night).
- Turnout totals only. No voter names or IDs are stored here.
