# Playbook: build assurance

## Objective

Ensure every change has a clear requirement, technical decision, and validation path before it is considered ready for release.

## Procedure

1. Link each change to a requirement or approved defect.
2. Keep secrets and environment-specific configuration outside source control.
3. Review accessibility, responsive behavior, error handling, and data-volume implications in proportion to the change risk.
4. Record the test scenario and expected result before user validation.
5. Add the resulting evidence to the traceability matrix.

## Exit evidence

- The change has an owner, rationale, and test evidence.
- Known limitations are documented rather than hidden.
- No critical security, accessibility, or data-quality issue is left unresolved.
