# Gambia FLP — Term 3 Tracker (GitHub Pages)

A stable GitHub Pages address for the read-only Term 3 Illustrations & Materials Tracker.
The page frames the live Apps Script web app (deployment `AKfycbwP9PV0…`, access: Anyone),
so the data is always the tracker's own. The **Refresh** button reloads it with a cache-buster.

- Source of the tracker: `Code.gs` / `Dashboard.html` (Google Apps Script). Embedding works
  because `doGet()` sets `XFrameOptionsMode.ALLOWALL` — keep that line when redeploying.
- If the Apps Script deployment URL ever changes, update `APP_URL` in `index.html`.
- `noindex` is set so search engines do not list the page.
