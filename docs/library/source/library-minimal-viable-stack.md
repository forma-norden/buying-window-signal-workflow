# Minimal Viable Stack

> **What it targets:** Teams that want to operationalize buying-window signals without turning the system into a 12-tool sprawl.

## The logic

The goal is not to collect every signal.

The goal is to make a small number of signals operational fast.

That requires just enough tooling to:

- detect the signal
- enrich the account
- route the motion
- send or warm the account
- measure the result

## Baseline stack

| Layer | Tool |
| --- | --- |
| Signal capture | Sales Navigator [prospecting], UserGems [signal], Bombora [intent], visitor ID tool |
| Enrichment | Clay [enrichment / automation] |
| CRM + routing | HubSpot [CRM] |
| Sequencing | Instantly.ai [sequencing] or Smartlead [sequencing] |
| Social support | LinkedIn |
| Measurement | HubSpot [CRM] first, HockeyStack [attribution] later |

## Why this stack is enough

It solves the core operating problem:

1. detect the event
2. qualify the account
3. identify the right contact
4. route the motion
5. measure whether the signal created pipeline

That is enough to prove the model before you add more complexity.

## The infrastructure warning

Signal quality does not rescue bad sending infrastructure.

Baseline inbox placement still varies materially by provider, with Microsoft Office365 around **67.95%** and Google Workspace around **56.97%** in the cited clean-sending benchmark set (GlockApps, Q4 2025). If the inbox layer is weak, the trigger will look worse than it really is.

Also remember that a 3+ provider waterfall can push contact coverage toward **70% to 80%** (GTM Evidence Pack, 2025). If you skip that layer, the best signals still die on missing contacts.

## Cost logic

The system only matters if it beats static SDR economics.

Traditional SDR cost still lands around **$98,000 to $173,000** fully loaded, with typical output around **10 to 15 qualified meetings per month** (SurfoX, February 2026). The signal stack is valuable when it helps your team concentrate effort more precisely than that headcount model can.

## Common mistake

Buying too many tools before the route logic is clear.

If your team cannot answer:

- which six signals matter
- who owns them
- what score activates them
- which route each one triggers

then more software will not fix the system.
