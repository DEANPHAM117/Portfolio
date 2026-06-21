# Dean Pham Blog

Single-page GitHub Pages site for Dean Pham's personal brand: learning journey, personal finance, business finance, project portfolio, philosophy, practical repair skills, and a technology news feed.

## Live URL

```text
https://deanpham117.github.io/Portfolio/
```

## Structure

- `index.html` - complete self-contained page with inline CSS and JavaScript.
- `.nojekyll` - keeps GitHub Pages publishing the static files as-is.
- `.github/workflows/static.yml` - deploys the site to GitHub Pages from `main`.

## Features

- Sticky responsive navigation with mobile menu.
- Hero thesis with CSS geometric visual.
- Journey timeline.
- Personal finance dashboard with tabs and mini chart.
- Business finance framework cards.
- Portfolio filters and accordion case studies.
- Philosophy quote section.
- Repair skill video cards.
- Technology news feed with static fallback and optional endpoint hook via `window.DEAN_NEWS_ENDPOINT`.

The site intentionally avoids a public API key in the browser. If a live Claude/web-search news feed is needed, add a small backend endpoint and assign its URL to `window.DEAN_NEWS_ENDPOINT`.
