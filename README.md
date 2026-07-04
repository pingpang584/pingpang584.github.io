# E-In Son — Academic Website

AcademicPages-style personal researcher homepage. Pure static HTML/CSS — no build step,
works directly on GitHub Pages.

## Deploy to GitHub Pages (username.github.io)

1. Create a repository named **`<your-github-username>.github.io`**.
2. Copy the contents of this `site/` folder to the repository root
   (so `index.html` and `images/` sit at the top level).
3. Commit and push:
   ```bash
   git init
   git add .
   git commit -m "Add academic homepage"
   git branch -M main
   git remote add origin https://github.com/pingpang584/pingpang584.github.io.git
   git push -u origin main
   ```
4. In the repo: **Settings → Pages → Source: Deploy from a branch → `main` / root**.
5. Visit `https://<username>.github.io` (allow ~1 minute for the first build).

## Editing

- All content lives in `index.html` — edit text directly.
- Thumbnails & profile photo: `images/`
- Paper links point to external arXiv / IEEE pages (`.pub-links` blocks).

## TODO (optional)

- [ ] Confirm the ORION ECCV 2026 news date (currently "Jul 2026").
- [ ] Optionally add project pages or a "Selected Publications" split.
