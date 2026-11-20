# Risk Scoring Methodology

This **illustrative training model** is not an official NIST formula.

**Risk score = Likelihood (1–5) × Impact (1–5)**

- Likelihood: 1 Rare; 2 Unlikely; 3 Possible; 4 Likely; 5 Almost certain.
- Impact: 1 Insignificant; 2 Minor; 3 Moderate; 4 Major; 5 Severe.
- Classification: 1–9 Low; 10–19 Medium; 20–25 High.

| Finding | Likelihood | Impact | Score | Rating |
|---|---:|---:|---:|---|
| F-01 Terminated account | 4 | 5 | 20 | High |
| F-02 MFA disabled | 4 | 5 | 20 | High |
| F-03 Privileged access approval evidence missing | 3 | 5 | 15 | Medium (score); auditor priority: provisional High |
| F-04 Overdue access reviews | 3 | 3 | 9 | Low (score); auditor priority: Medium |

## Important distinction
The initial audit narrative assigned **provisional High** to F-03 and **Medium** to F-04, while the selected example scores yield Medium and Low respectively. These are *not identical classifications*. The table preserves both transparently: numerical scores are calculated from the stated model; auditor priorities reflect contextual judgment. A final report must reconcile differences through an approved organizational risk methodology, verified exposure, and management review. If using only numerical ratings, F-03 is Medium and F-04 is Low.

Ratings are preliminary because asset criticality, exposure, mitigating controls, and actual system access have not been confirmed.
