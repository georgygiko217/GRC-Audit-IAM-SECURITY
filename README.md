# GRC Portfolio Project: Identity & Access Management Audit

**Organization:** Bayline Financial Services (fictional)  
**Audit date:** November 20, 2026  
**Framework:** NIST SP 800-53 Rev. 5 (AC-2, AC-6, IA-2)  
**Assessment:** Preliminary overall risk: **High**

> **Simulation disclaimer:** This is an independent educational exercise using fabricated names, policies, and records. It is not an audit of a real organization, a professional engagement, or evidence of actual compliance failures. Risk scores, deadlines, and remediation targets are exercise assumptions.

## Objective
Assess whether selected identity and access management (IAM) practices conform to the fictional company's access control policy. Practice evaluating evidence, identifying exceptions, rating risks, and writing actionable audit findings.

## Scope and limitations
- In scope: the six accounts shown in the supplied November 20, 2026 sample and supporting narrative evidence.
- Evaluated topics: terminated-user access, MFA, privileged-access approval, and periodic access reviews.
- Not independently validated: completeness of the identity population, application coverage, system logs, management responses, and remediation status.
- This is a **sample-based preliminary assessment**, not an enterprise-wide assurance opinion.

## Key findings

| ID | Observation | NIST mapping | Preliminary risk | Confidence |
|---|---|---|---|---|
| F-01 | Terminated user Maria Lopez's account remains enabled | AC-2 | High | Confirmed within supplied export; scope unverified |
| F-02 | David Chen's MFA is disabled | IA-2 | High | Confirmed within supplied export; enforcement unverified |
| F-03 | No approval record provided for David Chen's admin rights | AC-2, AC-6 | High (provisional) | Requires verification of missing documentation and business need |
| F-04 | Last documented access review is older than the required 90 days | AC-2 | Medium | Confirm whether later reviews exist |

**Important:** The 24-hour disablement and 90-day review frequencies are requirements of the *fictional company policy*, not universal mandates prescribed by NIST.

## Repository contents

```text
bayline-grc-iam-audit/
├── README.md
├── audit/
│   ├── audit-plan.md
│   ├── audit-report.md
│   └── risk-methodology.md
├── evidence/
│   ├── access-control-policy.md
│   ├── user-access-sample.csv
│   └── evidence-register.csv
├── findings/
│   ├── F-01-terminated-account.md
│   ├── F-02-mfa-not-enforced.md
│   ├── F-03-privileged-access-approval.md
│   └── F-04-overdue-access-review.md
└── tracking/
    └── remediation-tracker.csv
```

## Method
1. Read company policy and identify explicit audit criteria.
2. Examine the sample account export and narrative evidence.
3. Compare each observation with the policy.
4. Distinguish corroborated exceptions from unresolved questions.
5. Score preliminary risks on an illustrative likelihood × impact matrix.
6. Document recommendations, owners, and follow-up evidence.

## Evidence-based audit judgments
- **Maria Lopez:** Terminated October 15; account still enabled November 20. Apparent breach of the 24-hour termination rule.
- **David Chen:** MFA disabled for an active admin user. Apparent MFA policy breach. No approval ticket found, but absence of a ticket does **not** prove that no approval occurred.
- **Review cadence:** Last provided completed review May 15, 2026; 189 calendar days to November 20, 2026. Verify if later reviews occurred.
- **Michael Brown:** Terminated November 18 at 16:00; disabled November 19 at 09:00 (17 hours): within 24 hours for the sampled account.
- **Sarah Johnson:** Management approval documented, but approval by the specifically required IT Security Manager must still be verified.

## NIST references
- [NIST SP 800-53 Rev. 5: Security and Privacy Controls](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final)
- [NIST Risk Management Framework](https://csrc.nist.gov/projects/risk-management/about-rmf)

## Skills demonstrated
Audit scoping, control mapping, policy testing, evidence evaluation, least-privilege assessment, risk prioritization, professional finding documentation, and corrective-action tracking.

## Suggested GitHub topics
`grc` `it-audit` `identity-access-management` `nist-800-53` `cybersecurity-portfolio` `risk-assessment`
