# CLAUDE.md - buying-window-signal-workflow

This repo contains workflow skills for evaluating and routing B2B SaaS buying-window signals.

## Skills in This Repo

| Skill | When to use it |
|-------|---------------|
| `signal-scoring-router` | Any signal that needs a send, warm, or monitor decision |
| `champion-job-change-play` | A known champion moves to a new account |
| `new-executive-reset-play` | A relevant executive joins a target account |
| `intent-signal-play` | Pricing traffic, review-site activity, or adjacent intent events |
| `minimal-stack-operator` | Tooling decisions before scaling the signal system |

## Source Docs

- `docs/library/buying-window-signal-library.md`
- `docs/library/when-to-reach-out-six-signals.md`
- `docs/library/source/` for the full original page trees

## Invocation

Use: `Read .claude/skills/signal-scoring-router.md` before scoring a signal.

## Output Rule

Every output must include:

- score
- route
- owner
- first move

No generic theory responses.

## Testing

Run tests from `tests/` before production use.
