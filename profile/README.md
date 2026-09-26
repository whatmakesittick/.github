# What makes it tick

Interactive, scroll-driven explanations of how machines work. Each explainer is a
3D model you can scrub, rotate and switch between variants of, with the text
driving the view as you read. Available in eight languages.

## Explainers

| Topic | Live | Repository |
| --- | --- | --- |
| Internal combustion engine | https://whatmakesittick.github.io/engine/ | `engine` |

## How the organisation is laid out

- `whatmakesittick.github.io` is the website: landing page and catalogue.
- `core` is the shared framework every explainer builds on: stage, dock, presets,
  reading-line sections, labels, camera rig, safe area and translation plumbing.
- One repository per explainer, named after the machine. Each deploys itself to
  GitHub Pages and registers in the catalogue with a pull request.
