# Edwin Jonathan

I work on infrastructure problems where a successful automation run does not necessarily mean a safe or correct outcome.

**Cloud / platform engineering · Open-source tooling · Systems investigations**

[Work](#selected-work) · [Investigations](#investigations) · [Writing](https://edwinjdevops.github.io/engineering-platform/articles/) · [Website](https://edwinjdevops.github.io/engineering-platform/)

---

## Selected work

**[DriftGuard](https://github.com/EdwinJdevops/driftguard)** · Terraform / AWS

A drift-analysis implementation with an important failure boundary: if AWS inventory enumeration fails, the result must not quietly imply the infrastructure is gone.

[Regression fix](https://github.com/EdwinJdevops/driftguard/pull/3) · [Tests](https://github.com/EdwinJdevops/driftguard/blob/main/backend/tests/test_drift_engine.py) · [Source](https://github.com/EdwinJdevops/driftguard)

**[Warden](https://github.com/EdwinJdevops/warden)** · Kubernetes / GitOps

A remediation experiment around a strict distinction: proposing a change is not permission to merge it.

[Approval-boundary tests](https://github.com/EdwinJdevops/warden/blob/master/controller/internal/remediation/tier_test.go) · [Source](https://github.com/EdwinJdevops/warden)

**[SER](https://github.com/EdwinJdevops/ser)** · AWS / access containment

A decision core and bounded AWS experiments testing what can—and cannot—be concluded after an access-remediation workflow completes.

[Experimental evidence](https://github.com/EdwinJdevops/ser/blob/main/LIVE_VALIDATION.md) · [Source](https://github.com/EdwinJdevops/ser)

These are different kinds of engineering work, not a single product suite. Each repository documents its own operational limits.

## Investigations

- **[When AWS inventory fails](https://edwinjdevops.github.io/engineering-platform/articles/aws-inventory-failure-terraform-drift/)** — handling collection failure without reporting misleading drift.
- **[Policy before automation](https://github.com/EdwinJdevops/warden/blob/master/controller/internal/remediation/tier_test.go)** — tests for a manual-approval boundary.
- **[Containment is an evidence question](https://github.com/EdwinJdevops/ser)** — offline evaluation, live experiments, and known gaps.

## Work with the code

Start with the README, run the documented tests, and examine the unresolved limits. Bug reports backed by reproduction steps, design critiques, and scoped contributions are useful.

Check the license of each project before reuse; public visibility alone does not grant redistribution rights.

---

[Engineering notes](https://edwinjdevops.github.io/engineering-platform/articles/) · [LinkedIn](https://www.linkedin.com/in/edwin-jonathan-1094093b0) · [Contact](https://edwinjdevops.github.io/engineering-platform/)
