<div align="center">

# Edwin Jonathan

**I build infrastructure tools and investigate what happens when automation gets the answer wrong.**

Cloud infrastructure · Platform engineering · Open source · Systems reliability

[Explore tools](#tools-and-implementations) · [Read investigations](#engineering-investigations) · [Engineering website](https://edwinjdevops.github.io/engineering-platform/) · [Writing](https://edwinjdevops.github.io/engineering-platform/articles/)

</div>

---

## Start here

| If you're looking for… | Open this | What to inspect |
| --- | --- | --- |
| Terraform drift analysis for AWS | **[DriftGuard](https://github.com/EdwinJdevops/driftguard)** | Drift engine, regression tests, reviewable remediation proposals |
| Policy-controlled Kubernetes remediation | **[Warden](https://github.com/EdwinJdevops/warden)** | Manual-approval enforcement tests and dry-run PR boundary |
| Evidence-based access containment experiments | **[SER](https://github.com/EdwinJdevops/ser)** | Offline decision core, recorded AWS experiments, validation limits |
| Kubernetes security scanning examples | **[SENTINEL](https://github.com/EdwinJdevops/SENTINEL)** | Trivy/Kubescape workflow and report aggregation |

These projects have different levels of readiness. **A working test, a cloud experiment, and a production-qualified system are not interchangeable.** Check each repository's scope and limitations before using its code in an operational environment.

## Tools and implementations

### [DriftGuard — investigate AWS/Terraform drift](https://github.com/EdwinJdevops/driftguard)

Compare recorded Terraform state with collected AWS observations, analyze supported differences, and prepare proposed changes for human review.

**The engineering question:** Can an inventory failure accidentally look like an absence of infrastructure?

[Inspect the regression fix](https://github.com/EdwinJdevops/driftguard/pull/3) · [Read drift-engine tests](https://github.com/EdwinJdevops/driftguard/blob/main/backend/tests/test_drift_engine.py) · [Open the case study](https://edwinjdevops.github.io/engineering-platform/projects/driftguard/)

### [Warden — enforce remediation boundaries](https://github.com/EdwinJdevops/warden)

Explore a GitOps remediation design that separates proposed changes from authorization to merge them.

**The engineering question:** What prevents automated remediation from bypassing a human-approval policy?

[Inspect approval-boundary tests](https://github.com/EdwinJdevops/warden/blob/master/controller/internal/remediation/tier_test.go) · [Open the case study](https://edwinjdevops.github.io/engineering-platform/projects/warden/)

### [SER — evaluate containment evidence](https://github.com/EdwinJdevops/ser)

A bounded decision core and AWS experiments for assessing declared access checks after remediation.

**The engineering question:** A workflow completed. What evidence establishes whether access remains usable?

[Inspect the implementation and validation record](https://github.com/EdwinJdevops/ser) · [Read live validation](https://github.com/EdwinJdevops/ser/blob/main/LIVE_VALIDATION.md)

## Engineering investigations

I publish failure cases, tests, and the limits of what an experiment can prove.

- [AWS inventory failure and Terraform drift](https://edwinjdevops.github.io/engineering-platform/articles/aws-inventory-failure-terraform-drift/) — investigation into misleading results when collection fails
- [Engineering case studies](https://edwinjdevops.github.io/engineering-platform/projects/) — implementation, tests, and explicit validation boundaries
- [SER's experimental record](https://github.com/EdwinJdevops/ser) — live observations alongside unqualified integration paths

## Learn, fork, challenge, contribute

If you're learning infrastructure engineering, start with the tests and failure cases—not the screenshots. If you're reviewing a design, challenge its assumptions and verify the stated boundary.

Each repository has its own setup, license, and contribution conditions. A public repository is not automatically licensed for unrestricted reuse: **check its LICENSE before copying or redistributing code.**

I welcome reproducible bug reports, narrowly scoped pull requests, architecture review, and evidence that contradicts my assumptions.

## Beyond the repositories

I work across cloud infrastructure, security, automation, and software delivery. I also write about the engineering and organizational decisions behind these systems; the repositories are the inspectable part of that work.

[Engineering site](https://edwinjdevops.github.io/engineering-platform/) · [Technical writing](https://edwinjdevops.github.io/engineering-platform/articles/) · [LinkedIn](https://www.linkedin.com/in/edwin-jonathan-1094093b0) · [Services](https://edwinjdevops.github.io/engineering-platform/services/)

Microsoft credential: [Azure Fundamentals](https://learn.microsoft.com/en-us/users/jonathanedwin-0146/credentials/certification/azure-fundamentals)

---

*Source code is evidence of implementation. Production readiness requires separate qualification.*
