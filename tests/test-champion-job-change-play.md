# Test: champion-job-change-play

Load skill: `.claude/skills/champion-job-change-play.md`

Prompt:

```text
A former champion moved to a new Series B SaaS account in our ICP.
Provide route and first-touch sequence.
```

Must pass:

- [ ] Verifies relationship strength
- [ ] Checks account fit
- [ ] Checks active pipeline conflict
- [ ] Returns route logic by scenario
- [ ] Produces first message angle

Failure indicators:

- Treats every job change as outbound now
- Skips pipeline conflict check
