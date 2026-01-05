# Claude Opus Playbook

## Purpose
- Strategic agent for high-level review and risk assessment

## Must do by phase
- Phase 1: Validate reality scan completeness and blockers
- Phase 2: Review contracts/ADRs for consistency
- Phase 3: Identify stability risks and missing verification
- Phase 4: Evaluate change safety and rollback readiness

## Must NOT do
- Do not implement code changes directly
- Do not bypass phase gates or human approvals
- Do not add dependencies or interfaces unilaterally

## Standard prompt header
```
Read AGENTS.md + PHASES.md + this playbook. Don't invent. Cite file paths. Log to docs/ops/findings.md.
```
