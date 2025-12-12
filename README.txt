# thoms.email

A minimal, fast personal site that doubles as a résumé and brand hub.

## Pages
- `index.html` — Home / overview
- `career.html` — Career & Experience (detail view)
- `career-story.html` — Long-form career story
- `interview-qa.html` — Common interview Q&A
- `keel.html` — Keel Systems consulting page
- `hobbies.html` — Hobbies & side quests
- `lifestyle.html` — Lifestyle & training story
- `404.html` — Not found page

## Assets
- `assets/Portrait.png` and `assets/Portrait@2x.png` — Headshot (1x/2x)
- `assets/Jonathan_Thoms_Resume.pdf` — Resume PDF
- `assets/favicon.svg` — JT monogram favicon

## Site files
- `site.webmanifest`
- `robots.txt`
- `sitemap.xml` — Remember to add new pages here when you create them
- `CNAME` — Only include if you use a custom domain with GitHub Pages

## Local tweaks
- Theme: adjust colors under `:root` and `[data-theme='dark']` in any page
- Navigation: keep the header/nav consistent across pages
- When you add a new page: update `sitemap.xml` and add it to the “Pages” list above

## Deploy to GitHub Pages
1. Create a repo (any name is fine).
2. Commit all files in this folder to the repo root (keep `CNAME` if using a custom domain).
3. Enable Pages: Settings → Pages → Source: Deploy from a branch → `main` branch `/ (root)`.
4. DNS: point `thoms.email` to GitHub Pages and ensure the `CNAME` file contains `thoms.email`.

## Optional improvements
- Add per-page OpenGraph images if you want richer previews when sharing links
- Add screenshots/diagrams to case studies
- Add privacy-friendly analytics (Plausible, Simple Analytics, etc.)
