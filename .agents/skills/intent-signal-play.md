# intent-signal-play

## Purpose

Handle pricing-page, review-site, and adjacent intent signals with consistent routing.

## Inputs Required

- intent signal type
- account identity
- fit data
- source reliability

## Workflow

1. Classify signal as first-party or third-party.
2. Confirm account and segment fit.
3. Score confidence by source and recency.
4. Route:
   - strong first-party + fit -> outbound now
   - medium third-party + fit -> warm plus monitor
   - low confidence -> monitor only

## Output

- route
- first action by owner
- message angle by signal type
