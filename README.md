# EVLA Project Website

This folder contains a static GitHub Pages website for:

**EVLA: Energy Vision-Language-Action for Residential Energy Management**

The site is built from the provided EVLA paper export and uses selected figures, paper files, validation summaries, and result tables.

## Contents

```text
index.html
static/css/index.css
static/js/index.js
static/images/
static/paper/
static/data/
.github/workflows/static.yml
hosting/
```

## Before Publishing

Replace the placeholder links in `index.html`:

```text
https://github.com/USER/EVLA
https://huggingface.co/datasets/USER/EVLA
https://zenodo.org/records/EVLA_DOI
https://www.csu.edu/
```

Also update:

```text
authors
affiliation line
BibTeX entry
paper status
CSU catalog URL
```

## GitHub Pages Deployment

1. Create a GitHub repository, for example `EVLA`.
2. Upload the contents of this folder to the repository root.
3. Go to repository `Settings > Pages`.
4. Select GitHub Actions as the Pages source.
5. Push to `main`; the included workflow deploys the site.

## Recommended Hosting Split

- GitHub: website, code, sample data, scripts, issues, releases, changelog.
- Hugging Face: full EVLA dataset, dataset card, example loader, optional model checkpoints.
- Zenodo: frozen release snapshot and DOI.
- CSU: institutional catalog entry for visibility and long-term discoverability.

## Local Preview

From this folder:

```bash
python3 -m http.server 8765
```

Then open:

```text
http://localhost:8765
```

## Important Scientific Wording

Keep this distinction visible:

EVLA is a benchmark and reproducibility package for intent-conditioned energy decision learning. It is not a certified deployment-ready home-energy controller.
