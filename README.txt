# thoms.email

A minimal, fast personal site that doubles as a résumé and brand hub.

## Files
- `index.html` — Single-page site with sticky navigation, dark-mode toggle, and structured data.
- `assets/Portrait.png` and `assets/Portrait@2x.png` — Headshot at 1x and 2x.
- `favicon.svg` — Simple JT monogram.
- `site.webmanifest`, `robots.txt`, `sitemap.xml`, `404.html`
- `CNAME` — Only include if you use a custom domain with GitHub Pages.

## Local tweaks
- In HTML, change avatar sizing by editing: `style="--avatar:180px; --y:42%"`.
- Adjust colors under `:root` and `[data-theme='dark']`.
- Add or edit Featured Projects and Keel Systems bullets to match your current focus.

## Deploy to GitHub Pages
1. Create a repo named `thoms-email` or any name you prefer.
2. Commit all files in this folder to the repo root (keep `CNAME` if you use a custom domain).
3. Enable Pages: Settings → Pages → Source: Deploy from a branch → `main` branch `/root`.
4. DNS: Point your domain `thoms.email` to GitHub Pages and ensure the `CNAME` file contains `thoms.email`.

## Ongoing improvements
- Add project case studies as separate anchors or a `/projects.html` page.
- Replace text-only projects with screenshots or small diagrams.
- Add a simple contact form using a static form service.
- Add OpenGraph images for specific pages if you add more routes.
- Track visits with a privacy-friendly analytics tool (e.g., Plausible).

