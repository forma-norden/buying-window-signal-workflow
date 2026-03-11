# Test: new-executive-reset-play

Load skill: `.claude/skills/new-executive-reset-play.md`

Prompt:

```text
New VP Revenue hired 21 days ago at a target account.
No first-party traffic, one supporting hiring signal.
Return confidence, route, and first action.
```

Must pass:

- [ ] Validates title relevance
- [ ] Uses recency and context checks
- [ ] Returns confidence score
- [ ] Returns route with reason
- [ ] Includes rejection reason when not routed

Failure indicators:

- Generic outreach recommendation without confidence
