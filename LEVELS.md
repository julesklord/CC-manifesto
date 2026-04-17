# Conscious Code Levels

Conscious Code uses four maturity levels.

This prevents two common failures:
- demanding production rigor from exploratory work
- letting mature projects hide behind “it was just an experiment”

## Level 0 — Explore

Use for:
- prototypes
- learning spikes
- API tests
- throwaway experiments
- investigations expected to live less than 48 hours

Required:
- a clear question
- a clear learning objective
- a recorded conclusion: continue, freeze, or discard

Expected artifacts:
- short `README.md` or working note
- what was tested
- what was learned
- what is still untrusted

Does not require:
- certification
- peer review
- full architecture docs
- release discipline
- production-grade testing

Rule:
If the project survives exploration, it must be reclassified.

## Level 1 — Personal Tool

Use for:
- tools primarily built for yourself
- workflow automation
- private utilities
- systems with direct personal operational value

Required:
- clear use case
- clear non-goals
- dependency justification
- known limitations
- secret handling strategy
- minimal verification, automated or manual

Expected artifacts:
- `README.md`
- optional `TECHNICAL_DEBT.md`
- optional `FAILURES.md` if mistakes already matter in practice

Does not require:
- public deployment
- multi-user validation
- external peer review
- full certification

Rule:
A personal tool is valid if it saves time, reduces friction, prevents mistakes, or unifies workflow.

## Level 2 — Maintained Project

Use for:
- active repositories
- tools with ongoing iteration
- internal systems meant to remain understandable
- codebases intended to survive their first version

Required:
- current `README.md`
- architecture description
- tests for real behavior
- visible technical debt
- documented critical decisions
- failures recorded when relevant
- CI that reflects actual runtime behavior
- docs aligned with reality

Expected artifacts:
- `README.md`
- `ARCHITECTURE.md`
- `TECHNICAL_DEBT.md`
- `DECISIONS.md`
- `FAILURES.md` strongly recommended

Rule:
A maintained project must be explainable without relying on chat history.

## Level 3 — Certified Conscious Code

Use for:
- flagship repositories
- reference projects
- repositories intended to model best practice for others

Required:
- all Maintained Project requirements
- AI trust boundaries documented
- explicit failure memory
- post-release evidence
- conscious overrides documented
- navigability validated by someone outside the project
- author retains critical-path sovereignty

Expected artifacts:
- `README.md`
- `ARCHITECTURE.md`
- `DECISIONS.md`
- `TECHNICAL_DEBT.md`
- `FAILURES.md`
- AI trust map or equivalent section
- release/version alignment
- override log if exceptions were taken

Rule:
Certification is intentionally rare.
It is not a reward for effort.
It is a signal of maintainable mastery.
