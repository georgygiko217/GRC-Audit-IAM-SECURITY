# F-02 — MFA Disabled for Active Privileged User

**Control:** NIST IA-2 · **Preliminary risk:** High · **Status:** Supported by supplied sample; verify enforcement.

## Criteria
Policy BFS-SEC-001 requires MFA for all employees accessing company systems.

## Condition
David Chen is active, has administrator access, and the supplied export marks MFA Disabled.

## Evidence
E-01 policy; E-02 account export. Request E-07 authentication and conditional-access reports.

## Risk / effect
If passwords are compromised, systems might be accessed without a second factor. Administrator rights can amplify impact. No compromise has been established.

## Root cause
Unknown. Investigate enrollment, exception governance, and policy enforcement.

## Recommendation
Verify the account and effective MFA policy; require MFA or restrict access; review exceptions; monitor login and privileged activity; enforce centralized MFA policies.

## Suggested owner / target
IAM Team / immediate containment.

## Closure evidence
Authentication policy configuration, successful MFA test, access logs, exception documentation if applicable.
