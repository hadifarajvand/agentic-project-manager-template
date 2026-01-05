# Findings Log (Project-Specific)

## Environment
- Date: TBD
- Host: TBD
- OS: TBD
- Repo path: /Users/hadi/Documents/GitHub/agentic-project-manager-template
- Shell: zsh
- Notes: TBD

## Command Log

### Entry
- Command: `ls`
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
AGENTS.md
```

### Entry
- Command: `sed -n '1,200p' AGENTS.md`
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
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

The following files and directories are **project‑specific** and must be filled out during Phase 1 and Phase 2:

- `docs/ops/runbook.md` (verified commands to run the project)
- `docs/ops/findings.md` (raw logs from running commands)
- `docs/system/` (facts about this specific system: overview, context, components, interactions, invariants, requirements, diagrams)
- `docs/contracts/` (interfaces for this system)
- `docs/adr/` (decisions for this system, both pending and accepted)
```

### Entry
- Command: `mkdir -p docs/playbooks docs/ops docs/system/diagrams docs/contracts docs/adr/pending docs/adr/accepted`
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
```

### Entry
- Command: `cat <<'EOF' > docs/ops/findings.md`
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Wrote findings log template and initial entries.
```

### Entry
- Command: `cat <<'EOF' >> docs/ops/findings.md`
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Appended entry for findings creation command.
```

### Entry
- Command: `cat <<'EOF' >> docs/ops/findings.md` (this entry)
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Appended entries for prior log append and this append command.
```

### Entry
- Command: `cat <<'EOF' > README.md`
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Wrote README.md template.
```

### Entry
- Command: `cat <<'EOF' >> docs/ops/findings.md` (this entry)
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Logged README.md creation.
```

### Entry
- Command: `cat <<'EOF' > AGENTS.md`
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Wrote AGENTS.md template.
```

### Entry
- Command: `cat <<'EOF' >> docs/ops/findings.md` (this entry)
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Logged AGENTS.md creation.
```

### Entry
- Command: `cat <<'EOF' > PHASES.md`
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Wrote PHASES.md template.
```

### Entry
- Command: `cat <<'EOF' >> docs/ops/findings.md` (this entry)
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Logged PHASES.md creation.
```

### Entry
- Command: `cat <<'EOF' > docs/playbooks/codex.md`
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Wrote docs/playbooks/codex.md.
```

### Entry
- Command: `cat <<'EOF' >> docs/ops/findings.md` (this entry)
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Logged codex playbook creation.
```

### Entry
- Command: `cat <<'EOF' > docs/playbooks/claude_sonnet.md`
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Wrote docs/playbooks/claude_sonnet.md.
```

### Entry
- Command: `cat <<'EOF' >> docs/ops/findings.md` (this entry)
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Logged Claude Sonnet playbook creation.
```

### Entry
- Command: `cat <<'EOF' > docs/playbooks/claude_opus.md`
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Wrote docs/playbooks/claude_opus.md.
```

### Entry
- Command: `cat <<'EOF' >> docs/ops/findings.md` (this entry)
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Logged Claude Opus playbook creation.
```

### Entry
- Command: `cat <<'EOF' > docs/ops/checklist.md`
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Wrote docs/ops/checklist.md.
```

### Entry
- Command: `cat <<'EOF' >> docs/ops/findings.md` (this entry)
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Logged checklist creation.
```

### Entry
- Command: `cat <<'EOF' > docs/ops/runbook.md`
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Wrote docs/ops/runbook.md template.
```

### Entry
- Command: `cat <<'EOF' >> docs/ops/findings.md` (this entry)
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Logged runbook creation.
```

### Entry
- Command: `cat <<'EOF' > docs/system/overview.md`
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Wrote docs/system/overview.md template.
```

### Entry
- Command: `cat <<'EOF' >> docs/ops/findings.md` (this entry)
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Logged overview creation.
```

### Entry
- Command: `cat <<'EOF' > docs/system/context.md`
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Wrote docs/system/context.md template.
```

### Entry
- Command: `cat <<'EOF' >> docs/ops/findings.md` (this entry)
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Logged context creation.
```

### Entry
- Command: `cat <<'EOF' > docs/system/components.md`
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Wrote docs/system/components.md template.
```

### Entry
- Command: `cat <<'EOF' >> docs/ops/findings.md` (this entry)
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Logged components creation.
```

### Entry
- Command: `cat <<'EOF' > docs/system/interactions.md`
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Wrote docs/system/interactions.md template.
```

### Entry
- Command: `cat <<'EOF' >> docs/ops/findings.md` (this entry)
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Logged interactions creation.
```

### Entry
- Command: `cat <<'EOF' > docs/system/invariants.md`
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Wrote docs/system/invariants.md template.
```

### Entry
- Command: `cat <<'EOF' >> docs/ops/findings.md` (this entry)
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Logged invariants creation.
```

### Entry
- Command: `cat <<'EOF' > docs/system/requirements.md`
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Wrote docs/system/requirements.md template.
```

### Entry
- Command: `cat <<'EOF' >> docs/ops/findings.md` (this entry)
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Logged requirements creation.
```

### Entry
- Command: `cat <<'EOF' > docs/contracts/core.md`
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Wrote docs/contracts/core.md template.
```

### Entry
- Command: `cat <<'EOF' >> docs/ops/findings.md` (this entry)
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Logged core contract creation.
```

### Entry
- Command: `cat <<'EOF' > docs/contracts/engine.md`
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Wrote docs/contracts/engine.md template.
```

### Entry
- Command: `cat <<'EOF' >> docs/ops/findings.md` (this entry)
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Logged engine contract creation.
```

### Entry
- Command: `cat <<'EOF' > docs/contracts/storage.md`
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Wrote docs/contracts/storage.md template.
```

### Entry
- Command: `cat <<'EOF' >> docs/ops/findings.md` (this entry)
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Logged storage contract creation.
```

### Entry
- Command: `cat <<'EOF' > docs/adr/pending/0000-template.md`
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Wrote docs/adr/pending/0000-template.md.
```

### Entry
- Command: `cat <<'EOF' >> docs/ops/findings.md` (this entry)
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Logged ADR template creation.
```

### Entry
- Command: `find . -maxdepth 4 -print`
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
.
./.DS_Store
./PHASES.md
./docs
./docs/adr
./docs/adr/.DS_Store
./docs/adr/accepted
./docs/adr/pending
./docs/adr/pending/0000-template.md
./docs/.DS_Store
./docs/contracts
./docs/contracts/storage.md
./docs/contracts/engine.md
./docs/contracts/core.md
./docs/playbooks
./docs/playbooks/claude_opus.md
./docs/playbooks/codex.md
./docs/playbooks/claude_sonnet.md
./docs/system
./docs/system/requirements.md
./docs/system/overview.md
./docs/system/.DS_Store
./docs/system/context.md
./docs/system/diagrams
./docs/system/invariants.md
./docs/system/components.md
./docs/system/interactions.md
./docs/ops
./docs/ops/runbook.md
./docs/ops/checklist.md
./docs/ops/findings.md
./README.md
./AGENTS.md
./.git
./.git/config
./.git/objects
./.git/objects/pack
./.git/objects/pack/pack-edfc7418629f0f8805bd89f20e033d213cfa6ee1.idx
./.git/objects/pack/pack-edfc7418629f0f8805bd89f20e033d213cfa6ee1.rev
./.git/objects/pack/pack-edfc7418629f0f8805bd89f20e033d213cfa6ee1.pack
./.git/objects/42
./.git/objects/42/b781d16421d2ab8162c6b601e64031eabc28fd
./.git/objects/info
./.git/HEAD
./.git/info
./.git/info/exclude
./.git/logs
./.git/logs/HEAD
./.git/logs/refs
./.git/logs/refs/heads
./.git/logs/refs/remotes
./.git/description
./.git/hooks
./.git/hooks/commit-msg.sample
./.git/hooks/pre-rebase.sample
./.git/hooks/sendemail-validate.sample
./.git/hooks/pre-commit.sample
./.git/hooks/applypatch-msg.sample
./.git/hooks/fsmonitor-watchman.sample
./.git/hooks/pre-receive.sample
./.git/hooks/prepare-commit-msg.sample
./.git/hooks/post-update.sample
./.git/hooks/pre-merge-commit.sample
./.git/hooks/pre-applypatch.sample
./.git/hooks/pre-push.sample
./.git/hooks/update.sample
./.git/hooks/push-to-checkout.sample
./.git/refs
./.git/refs/heads
./.git/refs/heads/main
./.git/refs/tags
./.git/refs/remotes
./.git/refs/remotes/origin
./.git/index
./.git/branches
./.git/packed-refs
./.git/FETCH_HEAD
```

### Entry
- Command: `cat <<'EOF' >> docs/ops/findings.md` (this entry)
- Workdir: `/Users/hadi/Documents/GitHub/agentic-project-manager-template`
- Exit code: 0
- Output:
```text
Logged repo tree output.
```
