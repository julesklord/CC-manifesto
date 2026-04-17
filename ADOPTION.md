# Adoption Guide

Use this process to apply Conscious Code to an existing repository.

## 1. Classify The Repository

Before changing anything, decide what the project actually is:
- `Explore`
- `Personal Tool`
- `Maintained Project`
- `Certified Conscious Code`

Do not classify aspirationally.
Classify honestly.

## 2. Align Reality

Close contradictions first:
- runtime vs docs
- tests vs current behavior
- version metadata vs public version claims
- repository shape vs intended maturity

This step usually produces the biggest clarity gain.

## 3. Clean The Surface

Minimum hygiene:
- remove throwaway files from root
- move experiments to `scratch/`
- keep `tests/` for real automated tests only
- make `.gitignore` reflect local reality

## 4. Make Decisions Visible

If the repository matters, document:
- critical decisions
- known debt
- broken assumptions
- AI-generated risks that were discovered

Use these files when needed:
- `DECISIONS.md`
- `TECHNICAL_DEBT.md`
- `FAILURES.md`

## 5. Establish Boundaries

Critical boundaries should be explicit:
- composition vs runtime
- orchestration vs rendering
- domain logic vs infrastructure
- maintainable code vs black-box zones

If something remains a black box, mark it honestly.

## 6. Stabilize Verification

Do not chase total coverage.
Stabilize the tests that matter most:
- entrypoints
- critical orchestration
- real workflow behavior
- security or failure-sensitive paths

## 7. Raise The Level Only With Evidence

Do not claim:
- `Maintained` without aligned docs/tests/runtime
- `Certified` without documented discipline and explainability

The purpose of the framework is not status.
It is reduction of self-deception.
