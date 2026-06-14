# Agent CEO Runbook Kit

Run autonomous AI agents without fake progress.

This is a small operating kit for builders who want a local agent to keep working on a project between human check-ins without drifting into endless polishing, random refactors, or blocked loops.

Public page:

https://fix-logic.com/agent-ceo-runbook-kit/

Download ZIP:

https://fix-logic.com/agent-ceo-runbook-kit/Agent-CEO-Runbook-Kit-v0.1.zip

Product Hunt launch pack:

[`launch/product-hunt.md`](launch/product-hunt.md)

## What It Solves

Long-running agents can keep moving even when the next useful step is actually data, account access, payment setup, or a human decision.

This kit gives the agent:

- A bounded CEO-agent operating prompt
- Sub-agent delegation briefs
- Stop rules
- Continue / revise / kill gates
- Owner-action tracking
- A measurement template

## Start Here

Read these in order:

1. [`kit/00-start-here.md`](kit/00-start-here.md)
2. [`kit/01-ceo-agent-prompt.md`](kit/01-ceo-agent-prompt.md)
3. [`kit/03-decision-gates.md`](kit/03-decision-gates.md)

Then copy the owner-action example:

[`examples/owner-action-board.example.json`](examples/owner-action-board.example.json)

Open a feedback issue:

https://github.com/yitengruntu/agent-ceo-runbook-kit/issues/new?template=feedback.md

## Included Files

```text
kit/
  00-start-here.md
  01-ceo-agent-prompt.md
  02-subagent-briefs.md
  03-decision-gates.md
  04-owner-action-board.md
  05-measurement-template.md
examples/
  owner-action-board.example.json
  project-structure.txt
downloads/
  Agent-CEO-Runbook-Kit-v0.1.zip
launch/
  product-hunt.md
```

## What This Is Not

- Not a promise of unattended profit
- Not legal, tax, payment, or identity automation
- Not a replacement for real market data
- Not an infinite loop that ignores blockers

## Recommended Agent Stop Conditions

Stop when:

- Real-world data is needed
- External account action is needed
- Payment, tax, payout, identity, or credential action is needed
- The same blocker repeats
- Continuing would only create fake progress

## Validation

This project is being tested as a short-cycle demand experiment. The first decision window starts only after a deliberate distribution event, not merely because the page exists.
