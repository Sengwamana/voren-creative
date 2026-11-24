# Vorén

Vorén — independent creative production house site.

Portfolio site for Vorén (Hagenimana Shema Samuel), a video editor and motion designer based in Kigali, Rwanda. The site showcases commercial videos, short-form social content, wide-screen work, motion graphics and poster design, along with services, process and contact details.

## Features

- Responsive, single-page portfolio with sections for about, work, services, process, graphics and contact
- Vertical reels and wide-screen video cards, with poster images and previews
- Light/dark theme toggle and animated scroll reveals
- Mobile navigation drawer and video lightbox
- Contact hub with project-type chips, tailored WhatsApp/email links and a copy-to-clipboard email button
- SEO metadata, Open Graph/Twitter tags, JSON-LD structured data, sitemap and robots.txt

## Tech stack

- [Vite](https://vite.dev/) 6 (vanilla JavaScript, no framework)
- Plain HTML, CSS and JavaScript
- Self-hosted fonts plus Google Fonts (Syne, Plus Jakarta Sans, JetBrains Mono)
- Static hosting (Vercel configuration included; deployable to any static host)

## Getting started

Requirements: Node.js and npm.

```bash
npm install       # install dependencies
npm run dev       # start the dev server at http://localhost:3000
```

Other scripts:

```bash
npm run build     # produce the production site in dist/
npm run preview   # preview the production build locally
npm run serve     # serve the project with Python on http://localhost:8080
```

The Vite config copies `css/`, `js/`, `media/`, `fonts/`, `robots.txt`, `sitemap.xml`, `site.webmanifest` and `favicon.ico` into `dist/` after the build, so the output is fully self-contained.

## Project structure

```
index.html          Page markup, metadata and structured data
css/style.css       Styles
js/main.js          Interactions (theme, navigation, reveals, lightbox, contact hub)
fonts/              Self-hosted web fonts
media/
  graphic/          Poster and graphic images
  posters/          Video poster frames
  preview/          Short preview videos
  wide/             Wide-screen videos
  work/             Full project videos
vite.config.js      Vite config and static asset copy step
vercel.json         Vercel build/output settings
```

## Deployment

`vercel.json` builds with `vite build` and serves `dist/`. You can also upload the generated `dist/` directory to any static host (e.g. Cloudflare Pages, Netlify or GitHub Pages).

## Contact

- Email: Sam.kamo500@gmail.com
- WhatsApp / phone: +250 789 906 133
- Instagram: [@voren.007](https://www.instagram.com/voren.007)
