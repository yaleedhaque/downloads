# yaleedhaque / downloads

A public download hub for finished products: apps, software and websites. **This repo contains only built outputs — never source code.**

Source code, configuration, extensions and internals stay in private repositories. This page is the public face of that boundary.

## Rules of this repo

- Only *distributable* files go here: APKs, executables, standalone HTML files, config samples.
- No source code, no secrets, no internal docs, no private configuration.
- Everything listed must be genuinely usable and free.
- Files are served via **GitHub Pages** from the `files/` directory (keep each file under 100 MB).

## Adding a download

1. Copy the built file into `files/`.
2. Add (or update) its card in `index.html`.
3. Commit + push to `main` — Pages redeploys automatically.

For larger files: upload as a **GitHub Release** on this repo and link the release asset from `index.html`.

## Layout

```
files/          → downloadable files (served publicly via Pages)
index.html      → the download portal (also served via Pages)
README.md       → this file
```

## Deploying Pages

`Settings → Pages → Source = Deploy from a branch → branch: main, folder: / (root)`. Both `index.html` and `files/` are then public at:

```
https://yaleedhaque.github.io/downloads/
```

## Related

- Portfolio: <https://yaleedhaque.github.io>
- Family Tapestry: <https://family-tapestry-nine.vercel.app>
- bKash E-Commerce: <https://bkash-ecommerce.vercel.app>