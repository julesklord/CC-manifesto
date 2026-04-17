# Failures

This file records failures, broken assumptions, and corrections worth preserving as institutional memory.

## 2026-04-17 | Treating the landing as if it still lived in `scratch/`

- Failure:
  Parts of the repository documentation and external reasoning still treated the landing page as if it lived under `scratch/`.
- Impact:
  This created confusion about what was public, what was exploratory, and what should be considered canonical.
- Correction:
  The repository was revalidated from the actual working tree, and the docs were updated to reflect that the landing now lives in `index.html` at the root.
- Lesson:
  Before making structural recommendations, verify the repository shape from the current filesystem, not from stale assumptions or previous states.

## 2026-04-17 | Doctrine referenced maintenance artifacts that did not exist yet

- Failure:
  The framework encouraged `DECISIONS.md`, `TECHNICAL_DEBT.md`, and `FAILURES.md`, but the doctrine repository itself did not include them.
- Impact:
  The repository risked demanding discipline it was not yet applying to itself.
- Correction:
  Those artifacts were added and seeded with repository-level decisions, debt, and failure memory.
- Lesson:
  A standard repository must model its own claims if it expects other repositories to adopt them seriously.
