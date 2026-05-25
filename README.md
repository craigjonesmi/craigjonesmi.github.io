# craigjonesmi.github.io

Personal site for Craig Jones, served at <https://craigjonesmi.github.io>.

## Stack

Plain HTML + CSS. No build step. GitHub Pages serves it directly from `main`.

## Local preview

Just open `index.html` in a browser, or run a tiny static server:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Editing content

All copy lives in `index.html`. Search for `[` to find every placeholder
that still needs to be filled in. Most of the design lives in `styles.css`.

## Adding the resume PDF

Drop your PDF at the repo root as `resume.pdf` — the "Download resume" button
already points at that path. Don't commit a real PDF you don't want public.

## Color / typography

- Accent: `#0d4a4a` (deep teal). Change in `styles.css` `:root`.
- Headings: Newsreader (serif). Body: Inter (sans). Both via Google Fonts.
- Auto dark mode via `prefers-color-scheme`.

## Deploy

Push to `main`. GitHub Pages picks up automatically. First-time setup:
**Settings → Pages → Source: Deploy from a branch → `main` / `(root)`**.
