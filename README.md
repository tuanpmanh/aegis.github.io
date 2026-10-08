# Aegis — Company Landing Page

Static landing page for Aegis, a software engineering company focused on
finance, banking, and AI. Plain HTML/CSS/JS, no build step.

## Structure

- `index.html` — page markup
- `assets/css/style.css` — styles
- `assets/js/main.js` — nav toggle, scroll reveal, contact form handling
- `assets/img/favicon.svg` — site icon

## Local preview

Open `index.html` directly in a browser, or serve the folder:

```
npx serve .
```

## Deployment

Deployed via GitHub Actions (`.github/workflows/deploy.yml`) to GitHub Pages
on every push to `master`. In the repo settings, under **Pages**, set the
source to **GitHub Actions** (one-time setup).

## Contact form

The contact form has no backend — submitting it opens the visitor's email
client with a pre-filled message addressed to `contact@tuanpm.vip`.
