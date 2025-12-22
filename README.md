# AbdulmonemElsherif.github.io

This repository hosts a simple "Coming Soon" landing page for the site.

## Files added

- `index.html` — The landing page (headline, countdown, and a basic notification form).
- `assets/styles.css` — Styling for the page.
- `CNAME` — Your custom domain is already configured (keeps GitHub Pages mapping).

## How to customize

- Change the countdown date: edit the `LAUNCH_DATE` constant in `index.html` near the bottom of the file.
- Update the notification target: the form currently uses `mailto:` as a placeholder — replace with your backend endpoint or a form service like Formspree.
- Edit copy and branding: change the title/subtitle and the footer inside `index.html`.

## Deploying

This repo is ready for GitHub Pages — push to the `main` branch (or your pages branch) and enable Pages in the repository settings. The included `CNAME` file will cause GitHub Pages to serve the site at your custom domain.

---

### Automated deployment ✅

A GitHub Actions workflow has been added at `.github/workflows/deploy.yml` to automatically deploy the site to **GitHub Pages** when you push to the `main` branch (it also supports manual dispatch). The workflow uses the official Pages actions (`configure-pages`, `upload-pages-artifact`, `deploy-pages`).

If you want to change the branch that triggers deployment or add a build step (e.g., a static site generator), edit the workflow file accordingly or let me know and I can adjust it for you.