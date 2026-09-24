# ckelly314.github.io

Source for [ckelly314.github.io](https://ckelly314.github.io), built with [Jupyter Book](https://jupyterbook.org) (v1).

## Edit
Pages are Markdown files in the repo root. The sidebar order is set in `_toc.yml`; site settings are in `_config.yml`.

## Preview locally
```bash
conda env create -f environment.yml   # first time only
conda activate website
jupyter-book build .
open _build/html/index.html
```

## Deploy
Every push to `main` builds and deploys via `.github/workflows/deploy.yml`.
One-time setup: **Settings → Pages → Source → GitHub Actions**.
