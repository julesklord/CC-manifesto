# Conscious Code Checklist

Use the checklist for the level your repository actually belongs to.

Do not apply Certified requirements to an Explore project.
Do not use Explore status as a permanent excuse for a mature repository.

## Level 0 — Explore

- The question being explored is explicit.
- The expected learning outcome is explicit.
- The conclusion is recorded: continue, freeze, or discard.
- Unknowns and untrusted assumptions are named.

## Level 1 — Personal Tool

- `README.md` explains the real workflow problem.
- Non-supported cases are explicit.
- Dependencies are justified.
- Secrets strategy is defined.
- Verification exists, automated or manual.
- Known limitations are visible.
- The tool is actually used by its author.

## Level 2 — Maintained Project

- `README.md` matches actual runtime behavior.
- `ARCHITECTURE.md` describes the main flow and trade-offs.
- Tests verify real documented use cases.
- At least one real edge case is covered.
- `TECHNICAL_DEBT.md` exists and is visible.
- `DECISIONS.md` records major choices.
- Failures or broken assumptions are documented when relevant.
- CI reflects the current real surface area of the system.
- Docs, tests, and runtime no longer contradict each other.

## Level 3 — Certified Conscious Code

- All Maintained Project checks pass.
- AI trust boundaries are documented.
- Failure memory is treated as first-class knowledge.
- Critical-path ownership remains human.
- At least one person outside the project can navigate it with the docs alone.
- Release/version references are aligned across docs and metadata.
- Conscious overrides are documented with reason and exit condition.
- Post-release observations exist when the project has been deployed.

## Working Rule

No project should claim a level it has not earned.

A false certification is worse than no certification.
