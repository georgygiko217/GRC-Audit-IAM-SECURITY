# Audit Plan — Identity and Access Management

## Background
Bayline Financial Services is a fictional financial consulting organization with 150 employees. The exercise examines whether selected IAM practices comply with fictional policy BFS-SEC-001.

## Objective
Evaluate design and apparent operation of controls for account termination, MFA, privileged access, and access reviews.

## Criteria
| Policy clause | Requirement | Control mapping |
|---|---|---|
| 1 | Disable terminated users within 24 hours | NIST AC-2 |
| 2 | Require MFA for employees accessing company systems | NIST IA-2 |
| 3 | IT Security Manager approval for administrative access | NIST AC-2 / AC-6 |
| 4 | Review user access every 90 days | NIST AC-2 |
| 5 | Access appropriate to job duties | NIST AC-6 |

NIST provides control concepts; the specific deadlines are organization-defined exercise policy.

## Procedures
1. Obtain authoritative termination roster and reconcile to identity provider users.
2. Compare employment termination and account-disable timestamps; calculate delays.
3. Verify MFA configurations and enforced authentication policies for in-scope applications.
4. Match each administrator assignment to an approval ticket and role justification.
5. Obtain access-review completion evidence and determine review intervals.
6. Expand sample to other applications and privileged/service identities before final conclusions.
7. Discuss exceptions with responsible owners and record management responses.

## Limitations
Only six sample accounts, one policy extract, and brief narrative evidence were supplied. No independent source-system extraction, log verification, management interviews, or full population reconciliation occurred.

## Deliverables
Audit report, issue workpapers, evidence register, risk scoring method, and proposed remediation tracker.
