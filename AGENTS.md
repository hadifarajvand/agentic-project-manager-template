# Agent Rules (Universal)

This file defines non‑negotiable rules for agentic project management. It applies to all projects using this template.

## Phases

For detailed descriptions of each phase and their gates, see `PHASES.md`.

## Non‑Negot‑iable Rules

- No new dependencies without creating a new ADR under `docs/adr/`.
- No public interface changes (API, events, CLI) without updating the relevant contract in `docs/contracts/` and adding or adjusting tests.
- No refactor until the project can run locally **or** failures are reproducible and documented in `docs/ops/findings.md`.
- All commands you run and any error output must be recorded in `docs/ops/findings.md`.
- For code changes, prefer diff‑only outputs and include tests for any behaviour changes.

## Universal vs Project‑specific Files

The following files and directories are **universal** and should not be modified on a per‑project basis:

- `AGENTS.md` (this file)
- `PHASES.md`
- Everything under `docs/playbooks/`
- `docs/ops/checklist.md`
- The empty placeholder headings in the rest of the template

The following files and directories are **project‑specific** and must be filled out during Phase&nbsp;1 and Phase&nbsp;2:

- `docs/ops/runbook.md` (verified commands to run the project)
- `docs/ops/findings.md` (raw logs from running commands)
- `docs/system/` (facts about this specific system: overview, context, components, interactions, invariants, requirements, diagrams)
- `docs/contracts/` (interfaces for this system)
- `docs/adr/` (decisions for this system, both pending and accepted)
