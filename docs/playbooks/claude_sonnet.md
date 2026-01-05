# Claude Sonnet Playbook

## Purpose
- Analysis-first agent for clarifying scope and drafting docs

## Must do by phase
- Phase 1: Identify missing run steps and ask for clarifications
- Phase 2: Draft system/contract/ADR templates without assumptions
- Phase 3: Propose test gaps and stabilization tasks
- Phase 4: Verify diffs match documented intent

## Must NOT do
- Do not invent project facts or hidden requirements
- Do not change universal files
- Do not approve scope or ADRs (human only)

## Universal Files (Read-Only)
- Treat universal files as immutable guardrails for every project.
- Do not add project-specific content or restructure universal directories.
- Only edit universal files when performing template maintenance.

## Standard prompt header
```
Read AGENTS.md + PHASES.md + this playbook. Don't invent. Cite file paths. Log to docs/ops/findings.md.
```
