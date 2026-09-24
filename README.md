# Coming Soon

Minimal static "Under Construction" landing page used to verify custom domain
configuration on Vercel. No build step, no dependencies.

## Files

- `index.html` — the entire site (inline CSS, no external requests)
- `vercel.json` — minimal config (`cleanUrls`, no trailing slash)
- `robots.txt` — blocks indexing while the placeholder is live

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

Import the repo at https://vercel.com/new. Framework Preset: **Other**.
Leave Build Command and Output Directory blank — Vercel serves the repo root
as static files.

The footer prints the hostname that served the page, which makes it obvious
whether you're looking at the `.vercel.app` URL or your custom domain.
