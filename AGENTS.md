# Repository Guidelines

## Project Structure & Module Organization
This repository is a static personal website hosted from the root directory. Key files and folders:
- `index.html`, `about/index.html`, `sitemap/index.html`, `404.html`: primary pages.
- `style.css`, `mycss.css`: global styling assets.
- `/about`, `/sitemap`, `/archive`: content sections (note: `archive/` is currently empty).
- Images and media (`*.png`, `*.jpg`, `*.jpeg`) and PDFs are stored at the repo root alongside pages.
- `CNAME`, `robots.txt`, `sitemap.xml`, `feed.xml`, `redirects.json`: hosting and SEO configuration.

## Build, Test, and Development Commands
There is no build system or test runner in this repo. To preview locally:
- Open `index.html` directly in a browser.
- For a quick static server, use: `python -m http.server` (then visit `http://localhost:8000`).

## Coding Style & Naming Conventions
- Indentation: 2 spaces in HTML and CSS.
- Keep file names lowercase with hyphens when adding new pages (e.g., `project-overview.html`).
- Prefer editing shared styles in `style.css` and use `mycss.css` for page-specific overrides.
- Keep HTML semantic and minimal; avoid inline styles unless necessary.

## Testing Guidelines
No automated tests are configured. Validate changes manually:
- Load updated pages in a browser.
- Check responsive layout at mobile and desktop widths.

## Commit & Pull Request Guidelines
Git history shows short, descriptive messages without a strict convention (e.g., “updated position”).
- Use concise, present-tense summaries: “update publications list”.
- For PRs, include a brief summary of changes and screenshots for visual updates.
- Link related issues if applicable.

## Configuration Tips
- Update `CNAME` only when changing the custom domain.
- If adding new pages, update `sitemap.xml` and `feed.xml` when relevant.
