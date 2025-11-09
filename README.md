# Personal Website — David Felix

This repository contains a responsive personal portfolio built with plain HTML and CSS.

What I updated
- Reworked the hero and about sections with concise, professional copy.
- Added a newsletter CTA and social-proof badges in the hero area.
- Replaced lyrical placeholder text with clear, client-facing messaging.
- Added a responsive, animated mobile navigation (hamburger toggle).
- Created a stylized profile card with subtle shadow for the portrait.
- Added a lightweight CSS reset and responsive CSS variables.
- Improved typography using the Inter font and CSS clamp() sizing.
- Added a GitHub Actions workflow to publish the site to GitHub Pages (pushes to `gh-pages` branch).

How to preview locally

1. From the project folder run a simple static server. With Python 3:

```bash
python -m http.server 5173
```

Then open http://localhost:5173 in your browser.

Deployment (GitHub Pages)

The repo includes a GitHub Actions workflow that publishes the repository root to the `gh-pages` branch on every push to `main`. After the workflow finishes, enable GitHub Pages in the repository settings (Pages -> Branch: gh-pages / Root) if it isn't enabled automatically.

If you want me to additionally:
- enable Pages for you (I can't change the repo settings from here),
- or adjust the deployment to publish only the `dist/` folder if you add a build step,
tell me which you'd prefer.
# Personal Website — Responsive Update

This branch contains a responsive, refreshed version of the Personal Website. Key changes I applied:

- Replaced placeholder lyrical copy with concise professional copy (hero, about, services, contact, footer).
- Added Google Inter font for improved typography.
- Introduced a lightweight CSS variable system and polished color palette.
- Added a hero CTA with a small newsletter/email capture form (mailto fallback).
- Converted the profile image to a stylized profile card with subtle shadow.
- Implemented a mobile off-canvas navigation with smooth open/close animation and keyboard accessibility.
- Added responsive breakpoints (<=900px, <=768px, <=480px) and removed rigid fixed margins.
- Improved buttons, spacing, and accessibility focus states.

How to preview locally

1. From the project folder, run a simple static server (Python 3 required):

```bash
cd "c:/Users/USER/Desktop/Web Development Projects/Personal Website"
python -m http.server 5173
```

2. Open http://localhost:5173 in your browser.

Notes

- The email forms use `mailto:` as a fallback. For production, wire them to a proper backend or a service (Formspree, Netlify Forms, etc.).
- If you want a different accent color or font, tell me the hex or font name and I can update the theme variables.

If you'd like, I can:
- Add a small animations toggle or refine spacing further,
- Replace the newsletter `mailto:` with a serverless form integration,
- Or generate a production-ready build and help you deploy to GitHub Pages.
