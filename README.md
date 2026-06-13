# Sonara Yoga

Personalised pregnancy wellness — yoga, music and expert-led support.

This repository contains a static landing page prototype for Sonara Yoga. The site is intentionally lightweight (plain HTML/CSS/JS) for rapid design iteration. Use this repo as a marketing site or prototype for the larger Next.js product described in the project PRD.

Contents
- `index.html` — landing page
- `styles.css` — site styling
- `sonara-yoga-site-builder.json` — frontend-ready content model
- `website-structure.json` — product and information architecture
- `# SONARA YOGA™.md` — original product requirements document (PRD)

Local preview

To preview the site locally (simple static server):

```bash
# from the project root
python3 -m http.server 8000
# then open http://localhost:8000 in your browser
```

GitHub ready checklist
- Add a short README (this file) — done
- Add `.gitignore` — recommended (see below)
- Replace placeholder logos and images in `index.html`/`styles.css` with production assets
- Review accessibility (contrast, alt text, aria labels) before publishing
- Add license and contributing guidelines if desired

Notes and next steps
- This repo is a prototype. For production, move assets and code into a Next.js or similar app and add a build pipeline.
- Consider adding an image assets folder `public/images` and replacing text initials with headshots.
- Add real partner logos to the footer `partner-strip` when available.

Contact
- Founder vision and PRD are in `# SONARA YOGA™.md`.

---

Generated and curated for GitHub readiness.