# F-01 — Terminated Employee Account Remained Enabled

**Control:** NIST AC-2 · **Preliminary risk:** High · **Status:** Supported by supplied sample; verify system scope.

## Criteria
Policy BFS-SEC-001 requires account disablement within 24 hours after termination.

## Condition
Maria Lopez was terminated October 15, 2026. The November 20 account export still marks her account Enabled—well beyond the policy deadline.

## Evidence
E-01 company policy; E-02 account export. Request E-06 HR roster and E-07 identity/sign-in logs.

## Risk / effect
Unused former-employee accounts may enable unauthorized access and exposure of client data. No misuse has been proven.

## Root cause
Unknown. Investigate HR–IT offboarding communication, automation, and monitoring.

## Recommendation
Disable account and revoke sessions immediately; investigate post-termination sign-ins; reconcile all terminated employees to accounts; automate HR-to-IT workflows and exception alerts.

## Suggested owner / target
IT Operations Manager / immediate containment, process improvement in 30 days.

## Closure evidence
Disablement record, sign-in review, reconciliation report, tested offboarding workflow.
