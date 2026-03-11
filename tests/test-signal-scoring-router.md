# Test: signal-scoring-router

Load skill: `.claude/skills/signal-scoring-router.md`

Prompt:

```text
Signal type: New Executive Hire
ICP fit: strong
Recency: 14 days
Support context: two related open roles
Return score, route, owner, and first move.
```

Must pass:

- [ ] Uses the four scoring checks
- [ ] Returns explicit route
- [ ] Returns owner and first move
- [ ] Includes monitor date when route is monitor
- [ ] Handles missing-data fail condition

Failure indicators:

- Route given without score logic
- Missing owner output
