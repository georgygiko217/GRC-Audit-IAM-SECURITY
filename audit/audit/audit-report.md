# Preliminary Audit Report — Identity & Access Management

**Bayline Financial Services (fictional)**  
**Assessment date:** November 20, 2026  
**Framework:** NIST SP 800-53 Rev. 5, selected controls AC-2, AC-6, IA-2  
**Preliminary overall auditor judgment:** High

## Executive summary
The provided sample shows deficiencies in terminated-user access management and MFA configuration, plus material questions regarding privileged-access approval and review cadence. These weaknesses may increase exposure to unauthorized access. No breach, misuse, or enterprise-wide failure has been demonstrated.

## Findings

| Finding | Condition | Policy criteria | Preliminary priority |
|---|---|---|---|
| F-01 | Maria Lopez's terminated-user account still enabled | Disable within 24 hours | High |
| F-02 | David Chen's MFA disabled while account is enabled | MFA mandatory | High |
| F-03 | David Chen's administrator approval not produced | IT Security Manager approval and job-aligned access | High provisional |
| F-04 | Last documented review 189 days before audit | Review every 90 days | Medium contextual |

Refer to [risk methodology](risk-methodology.md) for a distinction between numerical ratings and qualitative priorities.

## Compliant or unresolved observations
- Michael Brown's account was disabled 17 hours after termination, meeting the 24-hour rule for that account.
- Sarah Johnson has management-approved administrator rights, but the required approver's role is not verified.
- John Smith and Emily Davis have no visible sample exceptions; this is not blanket compliance assurance.

## Major evidence gaps
Full account population and system inventory; authoritative HR termination roster; provider sign-in/audit logs; privileged access tickets; documented review history; compensating controls; management responses.

## Recommendations
1. Disable and investigate any active terminated-user accounts; reconcile HR and IAM inventories.
2. Require and validate MFA, prioritizing privileged users.
3. Verify all administrator approvals and job requirements; remove unnecessary rights.
4. Complete overdue access certification and maintain documented 90-day reviews.
5. Establish repeatable evidence retention, ownership, and exception escalation.

## Audit conclusion
**Preliminary High concern** within the supplied sample. Formal conclusions are pending population completeness testing, corroborating evidence, management discussion, and confirmation of effective controls. Company-specific 24-hour and 90-day targets are not universal NIST requirements.
