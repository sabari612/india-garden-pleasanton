# India Garden Pleasanton

A modern, single-page website for **India Garden** — an authentic North Indian restaurant in Pleasanton, CA.

## Live site

- **Website:** [indiagardenpleasanton.com](https://indiagardenpleasanton.com/)
- **Order online:** [Boons ordering](https://order.boons.io/site/indian-garden/300/y)
- **Catering:** [Catering orders](https://order.boons.io/site/catering/indian-garden/300/y)

## Features

- Responsive layout with mobile navigation and sticky order bar
- Hero section with featured dishes
- Filterable menu (All, Non-Veg, Vegetarian, Breads & Sides, Desserts)
- Photo gallery and customer reviews
- Table reservation, catering, and contact forms
- SEO meta tags and Open Graph support

## Tech stack

- HTML5
- CSS3 (custom properties, flexbox, grid)
- Vanilla JavaScript (no frameworks or build step)

## Project structure

```
.
├── index.html    # Main website (all HTML, CSS, and JS in one file)
└── README.md
```

## Run locally

Open `index.html` in your browser, or serve it with any static file server:

```bash
# Python
python -m http.server 8000

# Node.js (npx)
npx serve .
```

Then visit `http://localhost:8000`.

## Deploy on Vercel

This site is ready for Vercel — no build step required.

### Option 1: Import from GitHub (recommended)

1. Open [Import india-garden-pleasanton on Vercel](https://vercel.com/new/import?s=https%3A%2F%2Fgithub.com%2Fsabari612%2Findia-garden-pleasanton).
2. Sign in with GitHub and authorize Vercel.
3. Confirm these settings:
   - **Framework Preset:** Other
   - **Root Directory:** `./`
   - **Build Command:** leave empty
   - **Output Directory:** leave empty
4. Click **Deploy**.

Vercel will give you a live URL like `https://india-garden-pleasanton.vercel.app`. Future pushes to GitHub redeploy automatically.

### Option 2: Vercel CLI

```bash
npm i -g vercel
vercel login
vercel --prod
```

## Other hosts

This is a static site — you can also deploy to GitHub Pages, Netlify, or Cloudflare Pages with no build step.

## Restaurant info

| | |
|---|---|
| **Address** | 210 Rose Ave, Pleasanton, CA 94566 |
| **Phone** | [(925) 485-4800](tel:9254854800) |
| **Email** | [info@indiagardenpleasanton.com](mailto:info@indiagardenpleasanton.com) |

## License

© 2025 India Garden Pleasanton. All rights reserved.
