# Architecture

This repository is intentionally simple.

It is a doctrine repository, not an application repository.

## Purpose

Its job is to define and maintain a transferable internal standard for software development in the AI era.

That means the repository should privilege:
- clarity
- portability of principles
- operational usefulness
- easy adoption across other repositories

## Repository Shape

- `README.md`
  Entry point and positioning.

- `MANIFESTO.md`
  Core philosophy and governing principles.

- `LEVELS.md`
  Maturity model for classifying repositories.

- `CHECKLIST.md`
  Working checklist per maturity level.

- `ADOPTION.md`
  Practical migration path for applying the standard.

- `index.html`
  Public-facing landing page for GitHub Pages or lightweight static hosting.

- `scratch/`
  Exploratory artifacts and non-canonical drafts.

## Source Of Truth

The markdown documents in the repository root are the current source of truth.
`index.html` presents that standard publicly, but should not become the only place where doctrine changes live.

## Adoption Pattern

This repository is intended to influence other repositories through:
- direct reference
- selective copying of documents or sections
- transformation into local standards such as `STANDARD.md`
- use as a review lens when evaluating portfolio quality
