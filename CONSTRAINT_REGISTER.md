# Constraint Register

Snapshot date: 2026-02-08.

This register is the canonical index of active ecosystem constraints for `t81dev`.

## Ownership and Cadence

- Primary owner: `@t81dev`
- Backup owner: `TBD`
- Review cadence:
  - monthly scheduled review,
  - immediate review on major spec/runtime contract changes.
- Change control:
  - every register update must include rationale and affected repos,
  - constraint relaxations require explicit evidence and linked issue discussion.

## Active Constraint Entries

| ID | Constraint | Canonical Source | Affected Domains | Review Cadence |
| --- | --- | --- | --- | --- |
| C-001 | Identity boundary: `t81dev` is a research ecosystem, not a product/platform claim. | `IDENTITY.md` | All repos | Monthly |
| C-002 | Assumption governance: claims are valid only within documented assumptions. | `ASSUMPTIONS.md` | All repos | Monthly + spec updates |
| C-003 | Failure retention: negative results and invalidated ideas must remain visible. | `FAILURES_AND_LIMITS.md` | Runtime, hardware, crypto, benchmarks | Monthly |
| C-004 | Continuity requirement: implementation repos should carry continuity guidance that defers to this repository. | `CONTINUITY.md` | All implementation repos | Monthly |
| C-005 | Concept map integrity: ecosystem interpretation follows mapped conceptual relationships. | `MAP.md` | Docs/roadmap/research repos | Monthly |

## Update Procedure

1. Open an issue describing proposed register changes and impacted repos.
2. Update this file and any linked canonical source documents.
3. Post evidence links in the issue and downstream roadmap tracker as needed.
4. Merge only after owner review and rationale is documented.
