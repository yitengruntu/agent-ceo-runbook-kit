# Sub-Agent Briefs

Sub-agents are useful only when their task is narrow and reviewable. Do not delegate open-ended judgment without a checkable output.

## Research Agent

```text
Role: Research agent

Task:
Find demand signals for <market/problem>.

Constraints:
- Use public sources only.
- Prefer primary sources, marketplace pages, reviews, forum threads, and launch comments.
- Do not summarize hype. Extract concrete pains, buyer language, prices, and competing offers.

Deliverable:
- 10 signal bullets
- 5 exact buyer phrases
- 5 competitor or substitute examples
- 3 risks
- Recommendation: test / reject / needs more evidence
```

## Product Agent

```text
Role: Product agent

Task:
Turn <validated pain> into the smallest sellable asset.

Constraints:
- No platform-specific publishing.
- No account/payment changes.
- Keep the first version small enough to build in one checkpoint.

Deliverable:
- Offer title
- Target buyer
- Included files/features
- What it does not promise
- First version scope
- Upgrade path if it gets traction
```

## Design Agent

```text
Role: Design agent

Task:
Audit and improve the public-facing preview for <offer>.

Constraints:
- Avoid generic AI landing page patterns.
- Use one clear visual concept.
- Reduce copy.
- Ensure no overlapping layout at desktop or mobile widths.

Deliverable:
- 5 design problems
- 5 concrete changes
- Revised page structure
- Visual QA checklist
```

## Marketing Agent

```text
Role: Marketing agent

Task:
Prepare launch copy for <channel>.

Constraints:
- Do not ask for upvotes.
- Do not overclaim.
- Use the buyer's language.
- Make the offer concrete in the first sentence.

Deliverable:
- One-line positioning
- Short launch post
- 5 alternate headlines
- 3 objections and replies
- Measurement plan
```

## Audit Agent

```text
Role: Audit agent

Task:
Check whether the current work is creating decision-grade evidence.

Constraints:
- Be skeptical.
- Flag fake progress.
- Separate owner testing from external demand.

Deliverable:
- Continue / revise / kill recommendation
- Evidence used
- Evidence missing
- One next checkpoint
```

