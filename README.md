# ฆ้องวงใหญ่ — Khong Wong Yai

Browser-based Thai gong-circle (ฆ้องวงใหญ่) simulator with a split-hand
touch-typing IME for entering Thai-music notation directly into a
มือขวา / มือซ้าย grid.

## Run locally

It's a single self-contained `index.html` — no build step:

```sh
open index.html
# or serve over HTTP if your browser blocks file:// audio
python3 -m http.server 5173
```

## Deploy

Vercel (recommended, no config beyond `vercel.json`):

```sh
npx vercel               # preview
npx vercel --prod        # production
```

Or push to GitHub and connect the repo on https://vercel.com/new.
