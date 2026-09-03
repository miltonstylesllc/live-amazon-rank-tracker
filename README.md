# Live Amazon Rank Tracker — GitHub Pages

Public landing + privacy for **Live Amazon Rank Tracker**.

Live URLs (after deploy):

- https://miltonstylesllc.github.io/live-amazon-rank-tracker/
- https://miltonstylesllc.github.io/live-amazon-rank-tracker/privacy

This folder is its own git repo. It is gitignored from the Empire / extension project.

**Companion workbook (Free tier):** build with `build_excel_companion.ps1` in the extension project, then copy `store/excel-companion/live-amazon-rank-tracker-companion.xlsx` to `companion/live-amazon-rank-tracker-companion.xlsx` here. Landing links `#companion` and the direct download path above.

Same deploy path as History Exporter: `.github/workflows/deploy-static-pages.yml` plus `.nojekyll` and `privacy/index.html` for the `/privacy` URL. A clean `git push` is not enough — the Actions job **Deploy static site to GitHub Pages** must succeed.
