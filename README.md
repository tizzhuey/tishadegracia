# Portfolio Site

Static site (no build step) implementing the sitemap: Hero → About → Construction & Project Coordination (Category 1) → CAD & 3D Modeling (Category 2) → Skills → Resume → Contact.

## Files
- `index.html` — the one-page site
- `project-template.html` — duplicate this file per project (rename e.g. `project-riverside-villa.html`) and link to it from a project card in `index.html`
- `assets/` — put `resume.pdf` and project images/drawings here

## Deploy to GitHub Pages
1. Push this folder to a GitHub repo.
2. Repo → **Settings → Pages** → Source: `main` branch, `/root`.
3. Your site publishes at `https://<username>.github.io/<repo>/`.

## Before adding real content
- [ ] Replace `[Project Name]`, `[City, Province]`, etc. placeholders
- [ ] Add `assets/resume.pdf`
- [ ] Replace `you@example.com` and the LinkedIn placeholder
- [ ] Add real project photos/drawings to `assets/` and swap into the `.gallery` divs
- [ ] Duplicate `project-template.html` once per project, keep the "Project Scope (Team)" vs "My Contribution" split honest for each
- [ ] Contact form currently has no backend — wire it to Formspree, Netlify Forms, or similar, or leave it as `mailto:` only

## Notes
- Nav and structure follow the "simple navigation, few pages" recommendation — one main page, one repeatable project-detail page.
- Category 2 (CAD/3D) cards use a dashed border to visually separate technical-drafting work from full project-coordination work.
