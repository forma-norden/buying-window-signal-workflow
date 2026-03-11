# Test: intent-signal-play

Load skill: `.claude/skills/intent-signal-play.md`

Prompt:

```text
Signal: repeat pricing-page visits from a named account in ICP.
Return route and message angle.
```

Must pass:

- [ ] Classifies signal source type
- [ ] Scores confidence
- [ ] Returns route with owner
- [ ] Returns message angle tied to signal
- [ ] Handles low-confidence branch

Failure indicators:

- Same route for all signal strengths
