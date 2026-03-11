# signal-scoring-router

## Purpose

Evaluate a buying-window signal, score it, and return a route decision.

## Inputs Required

- signal type
- account fit data
- supporting context
- recency data

## Scoring Model

Use four checks:

1. ICP fit
2. recency
3. signal strength
4. supporting context

Assign route:

- high score -> outbound now
- medium score -> LinkedIn warm or ABM assist
- low score -> monitor

## Output Format

- `signal_score`
- `route`
- `owner`
- `first_move`
- `message_angle`
- `monitor_recheck_date`

## Fail Conditions

Stop and ask for more data when:

- ICP fit is unknown
- signal recency is unknown
- supporting context is missing for medium-confidence events
