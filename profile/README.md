# What makes it tick

Interactive, scroll-driven explanations of how machines work. Each explainer is a
3D model you can scrub, rotate and switch between variants of, with the text
driving the view as you read. Available in eight languages.

Live at https://whatmakesittick.github.io/

## Explainers

| Topic | Category | Live |
| --- | --- | --- |
| Internal combustion engine | Engines | https://whatmakesittick.github.io/engine/ |
| Helicopter | Aircraft | https://whatmakesittick.github.io/helicopter/ |
| Glider | Aircraft | https://whatmakesittick.github.io/glider/ |
| Sewing machine | Home | https://whatmakesittick.github.io/sewing-machine/ |

## How the organisation is laid out

- `whatmakesittick.github.io` holds the whole site in one repository: the page
  shell and 3D toolkit in `src/core`, the catalogue in `src/site`, and one folder
  per explainer under `explainers/<slug>/`. Every push to `main` deploys it to
  GitHub Pages.
- A new explainer is a folder, not a repository: a manifest, the chapters, the
  translations, and the model, scene and controls code. `ARCHITECTURE.md` in the
  site repository describes the contract between the shell and an explainer.
- `.github` holds this organisation profile.
