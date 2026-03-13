# champion-job-change-play

## Purpose

Run the cleanest warm-signal workflow when a prior champion moves to a new account.

## Inputs Required

- champion identity and previous relationship
- new company and role
- account fit details
- active pipeline check result

## Workflow

1. Validate champion relationship strength.
2. Confirm new account fits minimum ICP.
3. Check if the account is already active in pipeline.
4. Choose route:
   - high fit and warm relationship -> outbound plus LinkedIn
   - high fit and weak relationship -> LinkedIn warm first
   - weak fit -> monitor
5. Produce first message angle tied to transition context.

## Output

- route decision
- first-touch sequence
- owner assignment
