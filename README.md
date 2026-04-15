# Juju Couture Website

A GitHub-ready, production-style frontend starter for Juju Couture.

## Stack
- Vite
- Vanilla JavaScript with ES modules
- Structured CSS

## Project Structure

```bash
juju-couture/
├── index.html
├── package.json
├── README.md
├── public/
└── src/
    ├── components/
    │   └── layout.js
    ├── data/
    │   └── site.js
    ├── styles/
    │   └── main.css
    └── main.js
```

## Why this is better than a single HTML file
- Separation of concerns: markup, styles, and data live in different files
- Easier Git diffs and code reviews
- Easier onboarding for collaborators
- Ready for deployment and future scaling
- Product/content updates can be done in one place (`src/data/site.js`)

## Local Development

```bash
npm install
npm run dev
```

## Production Build

```bash
npm run build
```

## Deploy Options
- GitHub + Vercel
- GitHub + Netlify
- GitHub Pages (with minor Vite config if needed)

## Push to GitHub

```bash
git init
git add .
git commit -m "Initial Juju Couture website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/juju-couture.git
git push -u origin main
```

## Next upgrades I recommend
1. Replace gradient placeholders with real product photography
2. Connect the form to Formspree, Netlify Forms, or WhatsApp
3. Add SEO metadata and social preview tags
4. Add a CMS or admin-driven product source
5. Add analytics and conversion tracking
