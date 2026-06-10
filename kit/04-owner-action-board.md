# Owner Action Board

Use this file shape when an autonomous agent needs the owner to do something later.

```json
{
  "version": 1,
  "items": [
    {
      "id": "owner-action-001",
      "project": "example-project",
      "status": "open",
      "needed_by": "2026-06-17",
      "where": "Google Search Console",
      "what_to_get": "Performance export for the last 14 days",
      "why_it_matters": "Needed to decide whether to continue the experiment",
      "blocking": true
    }
  ]
}
```

## Status Values

- `open`: needed from owner.
- `done`: owner supplied it.
- `cancelled`: no longer needed.
- `superseded`: replaced by another request.

## Owner Request Rules

- Ask for the minimum data needed.
- Say exactly where to get it.
- Say the date window.
- Say why it matters.
- Do not ask daily when the data window is not due.

