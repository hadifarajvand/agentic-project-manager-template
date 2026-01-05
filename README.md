# Agentic Project Manager Template

## Purpose
- Provide a reusable, enforceable structure for agentic project work.
- Keep universal rules separate from project-specific facts.

## How to use this template
- New repo: copy the entire directory into the repository root before adding project files.
- Existing repo: add only the missing files and folders; never overwrite project-specific content.
- After copying: leave universal files intact and fill project-specific files during Phase 1-2.

## Universal vs project-specific
- Universal (never edit per project): `AGENTS.md`, `PHASES.md`, `docs/playbooks/*`, `docs/ops/checklist.md`, and placeholder headings.
- Project-specific (fill in per project): `docs/ops/runbook.md`, `docs/ops/findings.md`, `docs/system/*`, `docs/contracts/*`, `docs/adr/*`.

## Phase workflow summary
- Phase 1: Reality Scan — identify how to run the project or capture failures; log all commands.
- Phase 2: Source of Truth — document system facts, contracts, and pending ADRs from observed behavior.
- Phase 3: Stabilize Baseline — add or fix tests for current behavior; capture reproducible failures.
- Phase 4: Controlled Change Loop — make doc-first changes with minimal diffs and verified tests.

## Agent roles and when to use each
- Codex: execution-focused; apply verified changes and keep diffs minimal (see `docs/playbooks/codex.md`).
- Claude Sonnet: analysis-first; clarify scope and draft documentation without inventing facts (see `docs/playbooks/claude_sonnet.md`).
- Claude Opus: strategic reviewer; assess risk, consistency, and readiness (see `docs/playbooks/claude_opus.md`).
- All agents: read `AGENTS.md` and `PHASES.md` first and log every command and error in `docs/ops/findings.md`.

## Guardrails
- Do not add dependencies without an ADR.
- Do not change public interfaces without updating contracts and tests.
- Keep instructions short, checklist-driven, and free of project-specific claims.
