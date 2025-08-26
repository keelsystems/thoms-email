Jonathan Thoms — Site (v2)

Files:
- index.html — single-page site with sticky nav and non-warping circular avatar.
- assets/Portrait.png — avatar image used at 1x.
- assets/Portrait@2x.png — high-DPI source (same image for now).
- CNAME — included if you had one uploaded (for GitHub Pages custom domain).

Tuning:
- To change avatar size: in index.html, find `.avatar` and edit `--avatar: 180px;`
- To nudge the face framing: edit `--y: 42%;` (lower number moves face up; higher moves it down).
- To adjust ring thickness: `--ringw: 4px;`

Deploy:
- If you use GitHub Pages, commit these files to the root of your repo.
- Keep the CNAME file if you use a custom domain (e.g., thoms.email).

