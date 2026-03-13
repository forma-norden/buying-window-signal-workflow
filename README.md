# Buying Window Signal Workflow

This repository packages a signal-routing workflow for B2B SaaS teams that want better timing across outbound, ABM, LinkedIn warming, and monitor states. It turns buying-window signals into operational decisions with clear scoring, routing, and first-action rules.

## What's Inside

| File | What it does |
|------|-------------|
| `.agents/skills/signal-scoring-router.md` | Scores signals using a fixed decision model and assigns route by confidence and fit. |
| `.agents/skills/champion-job-change-play.md` | Runs the champion move workflow and outputs the first action path by account state. |
| `.agents/skills/new-executive-reset-play.md` | Qualifies executive-hire signals and routes execution based on support context. |
| `.agents/skills/intent-signal-play.md` | Handles first-party and third-party intent events with route logic and message angles. |
| `.agents/skills/minimal-stack-operator.md` | Defines the minimum stack to run the workflow before adding extra tooling. |
| `docs/library/buying-window-signal-library.md` | Hub page for the signal model and recommended usage order. |
| `docs/library/when-to-reach-out-six-signals.md` | Field guide version of the six highest-value signals to route first. |
| `docs/library/source/` | Full markdown source set from both signal-library page trees. |
| `tests/` | Prompt-based tests and checklists for each workflow skill. |

## Prerequisites

- [ ] Claude Code installed and running
- [ ] CRM access (HubSpot or Salesforce)
- [ ] Enrichment layer access (Clay or equivalent)
- [ ] At least one signal source (Sales Navigator, visitor ID, or intent provider)
- [ ] Sequencer access for outbound routing

## Installation

### Cursor, Windsurf, or Generic AI IDE
1. Clone the repo: `git clone https://github.com/forma-norden/buying-window-signal-workflow`
2. Copy the `.agents/skills/` directory into your project's `.agents/skills/` folder.

### Claude Code
1. Clone the repo: `git clone https://github.com/forma-norden/buying-window-signal-workflow`
2. Copy the `.agents/skills/` directory into your project's `.claude/skills/` folder.

## Usage

Load the scoring and routing skill before evaluating any signal:

```text
Read .agents/skills/signal-scoring-router.md

Signal type: New Executive Hire
Account context: [firmographic data]
Supporting context: [hiring, traffic, stack change, or none]
Return route: outbound, ABM, LinkedIn warm, or monitor.
```

Expected output:

- signal score with reason
- route decision with owner
- first move and message angle

## Who This Is For

GTM engineers, RevOps leads, VP Sales, and founders at B2B companies with 50 to
500 employees who are building or consolidating their outbound infrastructure and
want to reduce tool sprawl through better-engineered GTM systems.

---

## From the Forma Nôrden GTM Library

This is a free resource from the Forma Nôrden open-source GTM library, built by
[Yananai A. Chiwuta](https://yananaichiwuta.com/), GTM engineer and founder of
[Forma Nôrden](https://formanorden.com/).

- [Open-source GTM systems](https://github.com/forma-norden) - all repos in the library  
- [GTM engineering blog](https://formanorden.com/blog/) - strategy, systems, and outbound deep-dives  
- [All resources](https://formanorden.com/resources/) - guides, frameworks, and templates  

If this saves you time, star the repo and follow
[Forma Nôrden on LinkedIn](https://www.linkedin.com/company/formanorden/).

Built by [Forma Nôrden](https://formanorden.com/) - GTM engineering for B2B companies.

