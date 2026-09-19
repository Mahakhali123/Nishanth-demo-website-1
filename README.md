# Vesper.ai — Landing Page

Single-viewport landing page for **Vesper.ai** — Operational AI Infrastructure.

## Stack

- Pure HTML + inline CSS + vanilla JS (one file, zero dependencies)
- Fonts: Inter (variable) + Instrument Serif (italic) via Google Fonts CDN  
  *(drop `inter.woff2` & `instrument-serif-italic.woff2` next to `index.html` for self-hosted)*
- Hero: full-bleed MP4 video background (`autoplay muted loop playsinline`)

## Local development

Just open `index.html` in a browser — no build step required.

```bash
# Or serve with any static server, e.g.:
npx serve .
```

## Deploy to Vercel

### Option A — Vercel CLI

```bash
npm i -g vercel
vercel
```

### Option B — Vercel dashboard (Git)

1. Push this repo to GitHub / GitLab / Bitbucket  
2. Go to [vercel.com/new](https://vercel.com/new) → Import repository  
3. Framework preset: **Other** (static)  
4. Root directory: `.`  
5. Click **Deploy** ✓

No build command or output directory needed — Vercel serves `index.html` directly.

## Files

```
index.html          ← entire site (HTML + CSS + JS)
vercel.json         ← Vercel routing + security headers
.gitignore
README.md
```
