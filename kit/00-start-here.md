# Agent CEO Runbook Kit

## What This Is

This is a working kit for running a semi-autonomous AI agent as a project CEO, not just a coding worker.

The agent is expected to:

1. Read the project state.
2. Pick the highest-value checkpoint.
3. Delegate bounded work to specialist sub-agents when useful.
4. Make a small amount of progress.
5. Validate the work.
6. Commit or record the result.
7. Stop when real-world data or owner action is required.

## What This Is Not

- It is not a promise of fully unattended company operation.
- It is not a replacement for legal, tax, payment, or identity decisions.
- It is not an infinite loop that ignores blockers.
- It is not a prompt that should spend money or publish externally without approval.

## Recommended Folder Structure

```text
project/
  README.md
  ops/
    OPERATING_RULES.md
    RUNBOOK.md
    DELEGATION_POLICY.md
    MILESTONES.md
  data/
    backlog.json
    experiments.json
    metrics/
  decisions/
    DECISIONS.md
  reports/
```

## First Setup Checklist

- Define the objective.
- Define forbidden actions.
- Define when the agent must stop.
- Define the data needed for decisions.
- Define the commit rule.
- Define the owner-action board.
- Give the agent a small first checkpoint.

## Good First Checkpoint

Create or update the project runbook so the next run can understand:

- Current objective
- Current status
- Live experiments
- Blocked work
- Next checkpoint
- Owner-required actions

