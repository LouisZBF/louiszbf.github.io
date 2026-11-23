# louiszbf.github.io

Personal academic homepage for Bofan Zhao, hosted with GitHub Pages. The site is the landing page for
RIDE (Risk Index for Decline in eGFR), a calculator that estimates the 3-year risk of sustained eGFR decline
of 30% or greater from routinely available primary care data, without albuminuria measurements, to help
prioritise repeat eGFR and urine ACR testing.

- Public site: https://louiszbf.github.io/
- RIDE calculator: https://spark-kidney-decline.streamlit.app
- RIDE source code: https://github.com/LouisZBF/SPARK

## Contents

This repository contains only static website files: plain HTML and CSS with no build system, no external
dependencies and no server-side code. It contains no research data, model code, model parameters or
analysis outputs.

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

GitHub Pages publishes this site from the `main` branch, repository root (`/`). Pushing to `main` updates
https://louiszbf.github.io/ ; no build step runs.

## Notice

RIDE supports prioritisation of kidney assessment in primary care. It does not diagnose CKD and does not
replace urine ACR testing or the Kidney Failure Risk Equation (KFRE) when these are indicated.
