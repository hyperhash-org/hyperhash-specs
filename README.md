[![CI](https://github.com/hyperhash-org/hyperhash-specs/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/hyperhash-org/hyperhash-specs/actions/workflows/ci.yml)

# Hyper Hash — Specs

Central repository for Hyper Hash specifications.  
Defines the standards, APIs, and technical architecture for the pool.

## Contents
- Stratum V1 / V2 lane definitions
- Header generation methods
- Edge node behavior
- Overlay / analytics design
- UI data contracts

## Contents & Structure

- **Phase specs (1–15)** — design + acceptance criteria
- **ADRs** — Architecture Decision Records for key choices
- **Protocol notes** — SV1/SV2 extensions, payouts, governance

~~~
docs/
  adr/
    0001-record-architecture-decisions.md
specs/
  phase-1-template-engine.md
  phase-2-sv1-lane.md
  phase-3-sv2-lane.md
  ...
~~~

## Contributing

- Use ADRs for any significant change (one ADR per decision).
- Link PRs to the relevant project **phase** issue.
- Keep each spec focused and testable (“Done when…” clearly stated).


This is the reference for all development repos.
