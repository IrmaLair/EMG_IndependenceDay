Imagine India @ 2047 — Emaginations
==================================

This repository contains a single-file static microsite `index.html` that runs the full interactive quiz + build + share flow.

Quick preview (open locally):
- Double-click `index.html` in your file manager to open in the browser.

Quick preview (simple local server):
- Python 3 (recommended):

```bash
# from project root
python -m http.server 8000
# then open http://localhost:8000/
```

- Node (serve package):

```bash
npm install -g serve
serve .
```

Deploy options:
- GitHub Pages: create a repo, push these files, enable Pages from `main` branch root.
- Netlify: drag & drop `index.html` in the Netlify Sites dashboard.
- Vercel: import the repository and set the root to `/` (no build required).

Notes:
- No build tool is required to run the site — everything is inline in `index.html`.
- The `dist/` folder (previous build) has been removed to keep the repo minimal.

If you want, I can: add a small `index.html` minification, create a `CNAME`, or scaffold a GitHub Pages workflow to auto-deploy on push.