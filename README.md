# PlatusForge landing page

Static landing page for **PlatusForge**, an open-source platform for developers, and **Baseware**, its MIT-licensed SaaS starter.

- Live site: https://platusforge.github.io/lp/
- Baseware repository: https://github.com/platusforge/baseware

## Local preview

Open `index.html` directly, or serve the folder:

```sh
python -m http.server 8000
# http://localhost:8000
```

## Deploy

Every push to `main` deploys the repository root to GitHub Pages through `.github/workflows/pages.yml`. Pages is configured with **GitHub Actions** as the source.

The site is served from the project path `/lp/`; canonical, Open Graph, sitemap and `llms.txt` URLs point to `https://platusforge.github.io/lp/`.

## Structure

- `index.html` — bilingual (EN / PT-BR) landing page
- `license.html` — MIT license summary
- `privacy.html` — privacy policy
- `llms.txt` — product summary for LLMs
- `sitemap.xml`, `robots.txt` — SEO
- `platusforge-og-2026-v2.jpg`, `platusforge-icon.png`, `platusforge-logo-mark.png` — brand assets
