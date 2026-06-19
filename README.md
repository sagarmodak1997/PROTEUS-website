# PROTEUS Website

Source for the PROTEUS project website — `sagarmodak1997.github.io/PROTEUS-website/`.

## Local preview

```bash
cd PROTEUS-website
python3 -m http.server 8000
# open http://localhost:8000
```

## Structure

```
.
├── index.html          ← homepage
├── docs/index.html     ← documentation
├── updates/index.html  ← release notes / news
├── community/index.html← forum (Giscus embed)
├── assets/
│   ├── css/main.css
│   └── images/         ← logo, hero illustration
└── .nojekyll           ← disables Jekyll on GitHub Pages
```

## Deployment

This repo is configured to deploy automatically to GitHub Pages from the `main` branch.
After pushing, enable Pages in: **Settings → Pages → Source: Deploy from a branch → main / (root)**.
