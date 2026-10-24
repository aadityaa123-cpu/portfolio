# Adi — Graphic Design Portfolio

A responsive, dark-themed portfolio website built with plain HTML, CSS and JavaScript. No build step or dependencies required.

## Run locally
Open `index.html` in a browser, or use a local static server.

## Before publishing
1. Replace `hello@adidesigns.example` in `index.html` with your real email address.
2. Add your actual Instagram / LinkedIn links if you want them shown.
3. The six pieces are original CSS-built concept artworks and are explicitly labelled as concept projects — they are not client work.

## Deploy to Vercel
### Fastest method
1. Sign in to Vercel.
2. Choose **Add New → Project** and import a GitHub repository containing these files.
3. Framework preset: **Other**. Build command: leave blank. Output directory: `.` (project root).
4. Click **Deploy**.

### Without GitHub
Use Vercel CLI:
```bash
npm i -g vercel
cd adi-graphic-portfolio
vercel
```
Follow the prompts, then use `vercel --prod` for production deployment.

## Files
- `index.html` — page content
- `styles.css` — responsive dark visual system and concept artwork
- `script.js` — mobile menu, project filters and active navigation
