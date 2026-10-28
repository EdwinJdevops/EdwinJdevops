# Edwin Jonathan

**Cloud / DevOps / Platform Engineer · Open-source contributor**

I build infrastructure software and investigate the failure cases behind its decisions: incomplete cloud inventories, unauthorized automation, and misleading success signals.

[Projects](https://edwinjdevops.github.io/engineering-platform/projects/) · [Engineering notes](https://edwinjdevops.github.io/engineering-platform/articles/) · [GitHub contributions](https://github.com/EdwinJdevops?tab=overview) · [LinkedIn](https://www.linkedin.com/in/edwin-jonathan-1094093b0)

---

### Built and investigated

| Project | Problem | Inspect the work |
| :--- | :--- | :--- |
| **[DriftGuard](https://github.com/EdwinJdevops/driftguard)** | AWS/Terraform drift analysis must not mistake a failed inventory for deleted resources. | [Regression fix](https://github.com/EdwinJdevops/driftguard/pull/3) · [Tests](https://github.com/EdwinJdevops/driftguard/blob/main/backend/tests/test_drift_engine.py) |
| **[Warden](https://github.com/EdwinJdevops/warden)** | A remediation proposal must not bypass a required human approval. | [Policy-boundary tests](https://github.com/EdwinJdevops/warden/blob/master/controller/internal/remediation/tier_test.go) |
| **[SER](https://github.com/EdwinJdevops/ser)** | A completed access-remediation workflow does not by itself demonstrate containment. | [AWS experiment record](https://github.com/EdwinJdevops/ser/blob/main/LIVE_VALIDATION.md) · [Source](https://github.com/EdwinJdevops/ser) |
| **[SENTINEL](https://github.com/EdwinJdevops/SENTINEL)** | Make Kubernetes security-scan findings inspectable. | [Scan workflow](https://github.com/EdwinJdevops/SENTINEL/blob/main/.github/workflows/sentinel-scan.yml) |

### Engineering decisions, not just demos

- **Failure should not look like success.** [Investigating AWS inventory errors in Terraform drift analysis](https://edwinjdevops.github.io/engineering-platform/articles/aws-inventory-failure-terraform-drift/).
- **Authorization is not an implementation detail.** [Warden's manual-approval regression tests](https://github.com/EdwinJdevops/warden/blob/master/controller/internal/remediation/tier_test.go).
- **Evidence has boundaries.** [SER's measured experiments and unresolved qualifications](https://github.com/EdwinJdevops/ser).

### Open-source work

[Browse repositories](https://github.com/EdwinJdevops?tab=repositories) · [Browse public pull requests](https://github.com/pulls?q=is%3Apr+author%3AEdwinJdevops) · [Explore technical writing](https://edwinjdevops.github.io/engineering-platform/articles/)

If you find a defect, bring a reproduction. If an architectural assumption fails, show the counterexample. Contributions and independent technical review are welcome; check each repository's license and instructions before reuse.

---

[Engineering website](https://edwinjdevops.github.io/engineering-platform/) · [Contact](https://edwinjdevops.github.io/engineering-platform/)
