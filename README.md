# Agentic Project Manager Template

## What this is for
- A reusable structure for agentic project management across repos
- A minimal, enforceable set of rules, phases, and documentation placeholders

## How to apply this template
- New repo: copy the entire directory into your repository root
- Existing repo: add missing files only; do not overwrite project-specific content
- Keep universal files unchanged; fill project-specific files during Phase 1-2

## Universal vs project-specific
- Universal (never edit per project): `AGENTS.md`, `PHASES.md`, `docs/playbooks/*`, `docs/ops/checklist.md`, empty headings in the rest
- Project-specific (fill during Phase 1-2): `docs/ops/runbook.md`, `docs/ops/findings.md`, `docs/system/*`, `docs/contracts/*`, `docs/adr/*`

## Recommended workflow (Phase 1-4)
- Phase 1: Reality Scan
- Phase 2: Source of Truth
- Phase 3: Stabilize Baseline
- Phase 4: Controlled Change Loop

## Codex/Claude roles (high-level)
- Use playbooks to align agent behavior per phase
- Require agents to read `AGENTS.md` and `PHASES.md` first
- Log every command and error in `docs/ops/findings.md`
