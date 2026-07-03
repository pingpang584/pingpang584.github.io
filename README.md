# E-In Son — Academic Website

AcademicPages-style personal researcher homepage. Pure static HTML/CSS — no build step,
works directly on GitHub Pages.

## Deploy to GitHub Pages (username.github.io)

1. Create a repository named **`<your-github-username>.github.io`**.
2. Copy the contents of this `site/` folder to the repository root
   (so `index.html`, `files/`, and `images/` sit at the top level).
3. Commit and push:
   ```bash
   git init
   git add .
   git commit -m "Add academic homepage"
   git branch -M main
   git remote add origin https://github.com/<username>/<username>.github.io.git
   git push -u origin main
   ```
4. In the repo: **Settings → Pages → Source: Deploy from a branch → `main` / root**.
5. Visit `https://<username>.github.io` (allow ~1 minute for the first build).

## Editing

- All content lives in `index.html` — edit text directly.
- Papers/CV: `files/`   ·   Thumbnails & photo: `images/`

## TODO (fill in before publishing)

- [ ] Add profile photo as `images/profile.jpg` (square works best).
- [ ] Add your **Google Scholar** URL (sidebar link, currently `#`).
- [ ] Add your **GitHub** URL (sidebar link, currently `#`).
- [ ] Add per-paper links (arXiv / code / project page / DOI) in the `.pub-links` blocks.
- [ ] Confirm the ORION ECCV 2026 news date (currently "Jul 2026").
- [ ] Optionally add project pages, a photo, or a "Selected Publications" split.
