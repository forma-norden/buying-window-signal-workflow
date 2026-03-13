# Ecosystem: buying-window-signal-workflow

How this repo connects to the rest of the Forma Norden GTM library.

## Works With

| Repo | Relationship | When to use together |
|------|-------------|---------------------|
| `signal-based-list-building-workflow` | Upstream | Signals feeds produce the events this repo scores and routes |
| `cold-email-copy-playbook` | Downstream | Signal type and timing determine email copy angle |
| `clay-claude-code-skill-pack` | Downstream | Scored signals feed into Clay for enrichment |
| `n8n-gtm-workflow-pack` | Parallel | n8n automates signal capture and routing |
| `linkedin-claude-code-workflow` | Downstream | LinkedIn engagement signals route through this system |

## Suggested Skill Chains

1. Signal detection to outreach: `signal-based-list-building-workflow` (capture) > `buying-window-signal-workflow` (score and route) > `clay-claude-code-skill-pack` (enrich) > `cold-email-copy-playbook` (write)
