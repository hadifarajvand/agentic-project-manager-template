# Phases

## Phase 1: Reality Scan (existing projects)
Checklist:
- Identify how to run the project or capture failures
- Populate `docs/ops/runbook.md` with verified steps or document blockers
- Populate `docs/ops/findings.md` with raw command logs
- Inventory existing interfaces and configs at a high level
Definition of Done:
- Runbook and findings exist with real data or reproducible failures
- Phase 1 gate in `docs/ops/checklist.md` is satisfied

## Phase 2: Source of Truth
Checklist:
- Fill `docs/system/*` with project-specific facts
- Write or update `docs/contracts/*` for public interfaces
- Record decisions in `docs/adr/*`
- List invariants and requirements
Definition of Done:
- System, contracts, and ADRs reflect current behavior
- Phase 2 gate in `docs/ops/checklist.md` is satisfied

## Phase 3: Stabilize Baseline
Checklist:
- Add or fix tests for current behavior
- Document configuration and runtime dependencies
- Add Docker or CI only if already in use
- Ensure the project runs locally or failures are reproducible
Definition of Done:
- Tests pass or failures are documented with reproduction steps
- Phase 3 gate in `docs/ops/checklist.md` is satisfied

## Phase 4: Controlled Change Loop
Checklist:
- Write docs/contracts before code changes
- Make minimal diffs tied to documented requirements
- Verify with tests and update runbook/findings
- Human review for scope and risk
Definition of Done:
- Changes are documented, tested, and reviewed
- Phase 4 gate in `docs/ops/checklist.md` is satisfied

## Universal Files Are Read-Only Across All Phases
- Treat universal files as immutable guardrails unless performing approved template maintenance.
- Do not place project-specific content in universal files or alter their structure.
