# louiszbf.github.io

Personal academic homepage for Bofan Zhao, hosted with GitHub Pages. The site is a
landing page for SPARK (Stratified Primary-care Assessment of Risk for Kidney
Decline), a research-use calculator.

- Public site: https://louiszbf.github.io/
- SPARK application: https://spark-kidney-decline.streamlit.app
- SPARK source code: https://github.com/LouisZBF/SPARK

## Contents

This repository contains only static website files: plain HTML and CSS with no build
system, no external dependencies, and no server-side code. It contains no research
data, model code, model parameters, or analysis outputs.

```
index.html    landing page
styles.css    stylesheet
404.html      not-found page
.nojekyll     disables Jekyll processing on GitHub Pages
README.md     this file
```

## Local preview

From the repository root:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000/ in a browser.

## Deployment

GitHub Pages publishes this site from the `main` branch, repository root (`/`).
Pushing to `main` updates https://louiszbf.github.io/ ; no build step runs.

## Notice

SPARK is for research use only. It is not a diagnostic, treatment, referral, or
deployment-ready clinical decision-support tool.
