# GitHub Pages starter — bilingual

Plain HTML/CSS site — no Jekyll, no build step. A `.nojekyll` file is
included so GitHub Pages serves these files exactly as-is.

## Structure
- `index.html`, `about.html`, `projects.html`, `documents.html` — Spanish
  version, at the site root (default language)
- `en/` — English mirror of the same four pages
- `pdfs/` — shared PDF files, referenced by both language versions
- `style.css` — shared styling for both languages
- Each page has an "EN" / "ES" button in the header to switch versions

## Deploy
1. Push this to a GitHub repo (see chat instructions for the full walkthrough)
2. Settings → Pages → Source → Deploy from a branch → main → / (root)
3. Visit the URL GitHub gives you — it opens on the Spanish version by default
