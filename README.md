# Resume GitHub Pages Site (Template)

This repository contains a minimal single-page resume ready to be published with GitHub Pages.

## What’s inside
- `index.html` — the resume page (edit to add your details).
- `styles.css` — styles for the page.
- `.nojekyll` — ensures GitHub Pages serves files from the root.
- `resume.pdf` — optional (not included) — add your PDF if you want a download link.

## Quick steps to publish on GitHub Pages

1. Create a new repository on GitHub (e.g. `yourname.github.io`) or any repo name.
2. Clone it locally:
   ```bash
   git clone https://github.com/YOUR-USERNAME/YOUR-REPO.git
   cd YOUR-REPO
   ```
3. Copy these files into the repo (or upload through GitHub web UI).
4. Commit and push:
   ```bash
   git add .
   git commit -m "Add resume site"
   git push origin main
   ```
5. Enable GitHub Pages:
   - If the repo name is `yourname.github.io`, Pages will publish from the `main` branch automatically at `https://yourname.github.io/`.
   - Otherwise go to **Settings → Pages** and choose the branch (main) and folder (`/ (root)` or `docs/`) and save. It will provide the URL that looks like `https://your-username.github.io/your-repo/`.
6. (Optional) Add a PDF `resume.pdf` to the repo root to make the download link work.

## Custom domain
If you want to use a custom domain, add a `CNAME` file with your domain and configure DNS.

---

Edit `index.html` to replace placeholders (`Your Name`, contact links, experience, skills). If you'd like, I can fill the template with your real resume details — paste them here and I’ll update the HTML for you.
