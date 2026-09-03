# ResonantOS website (resonantos.com)

Public website for ResonantOS — the neutral baseplate for composable intelligence. A ResonantDAO project.

Served by GitHub Pages at https://resonantos.com from the repository root (`index.html`), with no build step.

## Structure

| Path | What it is |
|---|---|
| `index.html` | The site — single self-contained page (CSS/JS inline), dark + light themes, DAO visual system |
| `archive/` | Previous Astro-based site, preserved (see `archive/README.md`) |
| `.github/workflows/deploy-pages.yml` | Deploys the repository root to GitHub Pages on push to `main` |

## Editing

The page is intentionally a single file with no dependencies. Open `index.html` locally (or `python3 -m http.server`) to preview. Push to `main` to deploy.

## Theme

Dark/light toggle in the header (sun/moon icons). Choice persists in `localStorage`; default follows the system preference.
