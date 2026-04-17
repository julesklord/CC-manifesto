# Decisions

This file records repository-level decisions that materially affect how Conscious Code is structured, communicated, and adopted.

## 2026-04-17 | Repository-first source of truth

- Decision:
  Treat the markdown documents in the repository root as the canonical source of truth.
- Why:
  A landing page is useful for entry, but it is not a stable enough medium to hold the full method, maturity model, and adoption path.
- Alternatives rejected:
  - Keep the landing page as the only real source of truth.
  - Duplicate doctrine across multiple surfaces and accept drift.
- Result:
  `README.md`, `MANIFESTO.md`, `LEVELS.md`, `CHECKLIST.md`, `ADOPTION.md`, and `ARCHITECTURE.md` define the standard. `index.html` presents it.

## 2026-04-17 | Staged maturity model

- Decision:
  Make Conscious Code explicitly staged: `Explore`, `Personal Tool`, `Maintained Project`, `Certified Conscious Code`.
- Why:
  A single rigid standard for every project turns useful discipline into dead bureaucracy.
- Alternatives rejected:
  - One checklist for every kind of work.
  - Treating exploratory spikes and flagship repositories as if they deserved the same burden.
- Result:
  The framework now scales with repository maturity instead of punishing early-stage work.

## 2026-04-17 | Certified checklist is not universal

- Decision:
  Keep the interactive checklist positioned as the highest maturity bar, not as the default entry requirement.
- Why:
  The certification bar should remain rare and meaningful.
- Alternatives rejected:
  - Present the checklist as mandatory for every project.
  - Soften certification until it becomes ornamental.
- Result:
  `index.html` frames the checklist as `Certified Conscious Code`, while `LEVELS.md` and `CHECKLIST.md` define lighter paths for lower maturity levels.
