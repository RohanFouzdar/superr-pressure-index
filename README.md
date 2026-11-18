# Pressure Index dashboard: SupeRR Selector S2, Round 1

`index.html` is the whole dashboard. Its data is embedded and it makes no network calls, so any static host can serve it.

## Publish on GitHub Pages
1. Create a **public** repo on GitHub, e.g. `superr-pressure-index`.
2. Choose **Add file → Upload files** and upload `index.html` (and this README if you want it). Commit.
3. Open **Settings → Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, Branch to **main**, and folder to **/ (root)**. Click Save.
4. After about a minute, the site is live at `https://<your-username>.github.io/superr-pressure-index/`. Paste that link into Unstop's dashboard field.

## Rebuild from the model outputs
`python3 code/build_dashboard.py <out_dir> dashboard/index.html`
