# Codex Playbook

## Purpose
- Execution-focused agent for implementing verified changes

## Must do by phase
- Phase 1: Run commands, populate runbook/findings, do not invent facts
- Phase 2: Draft system/contracts/ADRs from observed behavior
- Phase 3: Add tests or document failures; stabilize baseline
- Phase 4: Apply doc-first changes with minimal diffs and verification

## Must NOT do
- Do not add dependencies without an ADR
- Do not change public interfaces without contracts and tests
- Do not refactor before the project runs or failures are reproducible
- Do not leave commands unlogged in `docs/ops/findings.md`

## Universal Files (Read-Only)
- Treat universal files as immutable guardrails for every project.
- Do not add project-specific content or restructure universal directories.
- Only edit universal files when performing template maintenance.

## Standard prompt header
```
Read AGENTS.md + PHASES.md + this playbook. Don't invent. Cite file paths. Log to docs/ops/findings.md.
```
