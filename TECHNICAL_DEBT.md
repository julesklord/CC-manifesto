# Technical Debt

This file tracks deferred work that is known, intentional, and visible.

## High

- The landing page and root documentation still require manual synchronization.
  Why:
  `index.html` is public-facing, while the markdown documents are canonical. Content drift is possible if both evolve separately.
  Exit condition:
  Define a lightweight maintenance checklist for doctrine changes or automate parts of the landing generation from markdown.

## Medium

- The repository has no explicit deploy note for GitHub Pages yet.
  Why:
  The landing lives in `index.html` at the root, but the deployment path and intended Pages strategy are not documented.
  Exit condition:
  Add a short deployment section to `README.md` or create a dedicated deployment note once the publication flow is fixed.

- The `scratch/` folder has no explicit retention policy.
  Why:
  The folder exists for exploration, but the repository does not yet state what belongs there, how long it stays, or when artifacts should be promoted or deleted.
  Exit condition:
  Document `scratch/` retention rules in `ARCHITECTURE.md` or `ADOPTION.md`.

## Low

- The repository does not yet include a compact external-facing summary artifact.
  Why:
  The repo is internally coherent, but a shorter public summary for first-time readers may still be useful later.
  Exit condition:
  Add a concise overview page or a dedicated public summary once the doctrine stabilizes.
