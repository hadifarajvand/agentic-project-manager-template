# Phase Gates Checklist (Universal)

## Phase 1 Gate: Reality Scan
- `docs/ops/runbook.md` has verified or failed commands
- `docs/ops/findings.md` includes raw logs for every command
- Known blockers are documented

## Phase 2 Gate: Source of Truth
- `docs/system/*` populated with project facts
- `docs/contracts/*` updated for public interfaces
- `docs/adr/*` contains pending or accepted decisions

## Phase 3 Gate: Stabilize Baseline
- Tests reflect current behavior or failures are reproducible
- Config and runtime dependencies documented
- CI/Docker status recorded (if present)

## Phase 4 Gate: Controlled Change Loop
- Changes are doc-first with contracts/requirements updated
- Diffs are minimal and reviewed
- Verification steps recorded in findings/runbook

## Stop Conditions (Pause and Ask Human)
- Missing access, secrets, or permissions
- Ambiguous scope or conflicting requirements
- Proposed dependency or interface change without ADR/contract
- Non-reproducible failures after documented attempts
