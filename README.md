# Portfolio — Zain ul Abideen

Personal portfolio site. Plain HTML, CSS, and JavaScript — no build step.

## Structure

```
index.html          Single-page site (hero, work, skills, about, contact)
css/style.css        All styles (light + dark theme)
js/main.js           Theme toggle, mobile nav, footer year
assets/              Images and resume.pdf  (see assets/README.md)
_old/                The previous version of the site, kept for reference
```

## Run locally

```bash
python -m http.server 8000
```

Then open http://localhost:8000

## Deploy

Hosted on GitHub Pages from `main` of https://github.com/Zain7652/portfolio
→ https://zain7652.github.io/portfolio/

```bash
git add .
git commit -m "Update portfolio"
git push
```

The previous site is preserved on the `old-portfolio` branch.

## To do

- [ ] Add a real screenshot at `assets/shop-app-1.png` and update the `<img src>` in `index.html`
