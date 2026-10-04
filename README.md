# Wilmer Rodriguez — Front-End Engineer

Personal portfolio and CV site: **https://wilmerrodriguez.github.io/cv_landingPage/**

Front-End Engineer (React · TypeScript · Next.js) with 8 years of software engineering experience. Based in Laval, France, open to remote roles across EU and US time zones. Trilingual: English, Spanish, French.

## What's on the site

- **About & tech stack** — grouped by front end, practices, testing, tooling and back end
- **Experience** — B12, freelance front-end work, Kashiko, EON Reality
- **Featured builds** — Groovy Grub (React + Redux Toolkit e-commerce), an ESL learning site with a bilingual tooltip engine, and AI DJ (in progress)
- **Contact form** — sends through [Web3Forms](https://web3forms.com), no backend needed
- **Resume** — `Wilmer_Rodriguez_Resume.pdf`

## How it's built

A single static `index.html` with hand-written CSS and vanilla JavaScript, no build step:

- English by default with a one-click **FR** toggle (auto-detects French browsers, remembers the choice; `?lang=fr` forces French)
- Responsive layout down to small phones, skip link, visible focus styles and `prefers-reduced-motion` support
- Open Graph tags so the link previews cleanly on LinkedIn and Slack
- Deployed with GitHub Pages from the `main` branch

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Contact

solowildev@gmail.com · [github.com/wilmerRodriguez](https://github.com/wilmerRodriguez)
