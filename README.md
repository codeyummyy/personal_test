# Eve AcademicPages (Ready-to-Publish)

A prefilled AcademicPages-style site for admissions. Edit text, replace PDFs in `/files`, and publish with GitHub Pages.

## Quick Deploy (GitHub Pages)
1. Create a **public repo** named `<your-username>.github.io` on GitHub.
2. Download this ZIP, unzip, and upload all files to that repo.
3. In `_config.yml`, set:
   - `repository: "<your-username>/<your-username>.github.io"`
   - `url: "https://<your-username>.github.io"`
   - `author.email`, `author.github`, etc.
4. Commit → GitHub will build the site (using `remote_theme: academicpages/academicpages`).
5. Visit `https://<your-username>.github.io`.

## Structure
- `index.md` — Landing with 3–4 action buttons (Research / Projects / Talks / Downloads)
- `_pages/*.md` — Section pages
- `_data/navigation.yml` — Top nav
- `files/` — Put your PDFs here (posters, briefs, scripts, CV)
- `assets/img/hero.jpg` — Header image (replace with your own)

## Content Policy (Admissions)
- Keep homepage ≈ 250–400 words.
- Every claim should have a **clickable artifact** (PDF/video/code/media).
- Update monthly. Current timestamp: **2025-10**.

——
