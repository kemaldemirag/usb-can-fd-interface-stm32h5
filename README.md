# USB Dual CAN FD Interface (STM32H5)

> Portfolio reference work derived from public job postings (CONTEXT-BOUND / PLANNED). Source jobs are requirements inspiration only; no client execution, fabrication, bench test or production claim is made.

**Status:** INITIAL / EVIDENCE REQUIRED · **Workspace phase:** Phase 1 · **Source:** JOB-02 (+ JOB-06 interface concepts)
**Handoff ID:** `CAN-ENERGY-PORTFOLIO-2026-09-15`

## Goal
Create a compact STM32-based dual-channel CAN/CAN FD engineering interface inspired by JOB-02 and interface concepts from JOB-06.

## Current scope
Job context, canonical `CAN-*` requirements, architecture assumptions, interface/evidence expectations.

## Required future artifacts
Requirements, architecture, ICD, CAN message model, schematic/KiCad source, PCB notes, firmware architecture, bring-up plan, test vectors, decision register, validation matrix and validation report.

Empty implementation-stage directories are intentionally not created until useful artifacts exist.

## Repository layout
```
usb-can-fd-interface-stm32h5/
├─ README.md
├─ 01_job_context/README.md
├─ 02_requirements/requirements.md
├─ 03_architecture/architecture-initial.md
└─ docs/00_shared/   # governance mirrored from workspace
```

## Governance
- Source jobs are requirements inspiration only; they are not evidence of client execution.
- VERIFIED / VALIDATED / TESTED / PASS / COMPLETE / PRODUCTION READY / MANUFACTURING READY require evidence paths — see [evidence_policy](docs/00_shared/evidence_policy.md).
- Hardware status is limited to DESIGNED, SIMULATED, FABRICATED, ASSEMBLED, BENCH_TESTED, FIELD_TESTED — see [terminology](docs/00_shared/terminology.md).
- Major architecture choices are recorded in decision registers; unknowns remain OPEN or BLOCKED — see [engineering_rules](docs/00_shared/engineering_rules.md).

## Workspace execution order

| Phase | Scope |
|---|---|
| 0 | Governance + job-source map + requirement templates |
| 1 | Project 01 and Project 02 baselines |
| 2 | Project 03 |
| 3 | Project 04 |
| 4 | Cross-project consistency |
| 5 | Releases only when evidence is traceable |

Related repositories: see [portfolio_map](docs/00_shared/portfolio_map.md).
