# Test: minimal-stack-operator

Load skill: `.claude/skills/minimal-stack-operator.md`

Prompt:

```text
Current stack has CRM and sequencer only.
Recommend minimum stack and deferred additions.
```

Must pass:

- [ ] Returns all required stack layers
- [ ] Includes add-later criteria
- [ ] Avoids unnecessary tool sprawl
- [ ] Ties recommendation to operating requirement
- [ ] Produces audit plus roadmap output

Failure indicators:

- Recommends tools without explaining requirement
