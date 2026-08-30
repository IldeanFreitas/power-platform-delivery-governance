# Playbook: release governance

## Objective

Make a deliberate Go/No-Go decision for each release.

## Procedure

1. Review open risks, test evidence, rollback approach, and release owner.
2. Confirm that environment configuration and access are handled by approved operators, outside this public kit.
3. Verify user-facing accessibility and failure paths for the release scope.
4. Record the Go/No-Go decision, approver, timestamp, and follow-up actions.
5. After release, capture operational feedback and route it to the backlog.

## No-Go conditions

- A critical defect, security concern, or data-integrity issue remains open.
- Rollback or recovery ownership is unknown.
- Required test evidence or approval is missing.
