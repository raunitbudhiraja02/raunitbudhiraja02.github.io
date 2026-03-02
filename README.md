# raunitbudhiraja.github.io

Personal ePortfolio website for Raunit Budhiraja — BSc Business Analytics, DCU.

Built with [Quarto](https://quarto.org/) and hosted via GitHub Pages.

## Structure

```
.
├── _quarto.yml           # Site config, navbar, theme
├── styles.scss           # Custom dark/neon theme (Sass + CSS)
├── index.qmd             # Homepage / landing
├── about.qmd             # About me + Kubicle certs
├── reflections.qmd       # Learning reflections
├── contact.qmd           # Contact page
├── images/               # Profile photo, logo, favicon
├── cv/                   # raunit_cv.pdf
├── projects/
│   ├── index.qmd         # Projects listing
│   ├── data-analysis.qmd       # EDA with Pandas & Plotly
│   ├── machine-learning.qmd    # Random Forest churn predictor
│   ├── dashboard.qmd           # KPI dashboard with Plotly
│   └── business-strategy.qmd   # Market entry analysis
└── docs/                 # Rendered output (GitHub Pages serves this)
```

## Local Development

```bash
# Preview site with live reload
quarto preview

# Render to /docs for GitHub Pages
quarto render
```

## Deployment

GitHub Pages is configured to serve from the `/docs` folder on the `main` branch.

After any changes:

```bash
git add .
git commit -m "describe what changed"
git push
```
