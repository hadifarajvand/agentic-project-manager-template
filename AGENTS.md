# Agent Rules (Universal)

This file defines non-negotiable rules for agentic project management. It applies to all projects using this template.

## Phases
- For phase details and gates, see `PHASES.md`.

## Non-Negotiable Rules
- No new dependencies without a new ADR under `docs/adr/`.
- No public interface changes (API, events, CLI) without updating the relevant contract in `docs/contracts/` and adding or adjusting tests.
- No refactor until the project can run locally or failures are reproducible and documented in `docs/ops/findings.md`.
- All commands you run and any error output must be recorded in `docs/ops/findings.md`.

## Output Rules
- For code changes, prefer diff-only outputs.
- Include tests for any behavior changes.

## How to apply without polluting projects
UNIVERSAL (never project-specific):
- `AGENTS.md`
- `PHASES.md`
- `docs/playbooks/*`
- `docs/ops/checklist.md`
- Empty placeholder headings in the rest of the template

PROJECT-SPECIFIC (filled during Phase 1-2):
- `docs/ops/runbook.md`
- `docs/ops/findings.md`
- `docs/system/*`
- `docs/contracts/*`
- `docs/adr/*`

## Human responsibilities
- Define scope and priorities
- Approve ADRs and interface changes
- Review and merge changes
- Provide access and resolve blockers
