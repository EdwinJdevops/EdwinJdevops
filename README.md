<div align="center">

# Edwin Jonathan

**Cloud & Platform Engineer · Lagos, Nigeria**

Infrastructure reliability · AWS and Terraform · Kubernetes and GitOps · Security and controlled automation

[Engineering website](https://edwinjdevops.github.io/engineering-platform/) · [Case studies](https://edwinjdevops.github.io/engineering-platform/projects/) · [Technical writing](https://edwinjdevops.github.io/engineering-platform/articles/) · [LinkedIn](https://www.linkedin.com/in/edwin-jonathan-1094093b0)

</div>

## Engineering focus

I build and investigate cloud infrastructure and platform tooling where **observability, evidence quality, and safe changes** matter. I work with AWS, Terraform, Python, Kubernetes, GitOps, CI/CD, infrastructure security, and software-delivery systems.

Repositories are evidence of implementation, not proof of production readiness. Each linked case study separates code and executed tests from integrations and behaviors not yet validated.

## Selected engineering work

### [DriftGuard](https://github.com/EdwinJdevops/driftguard) — AWS infrastructure drift analysis

Compares Terraform state and collected AWS observations, produces structured findings, and proposes remediation through reviewable GitHub pull requests rather than applying infrastructure changes automatically.

- [Merged regression fix (PR #3)](https://github.com/EdwinJdevops/driftguard/pull/3): fail on top-level AWS inventory enumeration errors and preserve indexed Terraform resource identities.
- [Drift-engine tests](https://github.com/EdwinJdevops/driftguard/blob/main/backend/tests/test_drift_engine.py) and [CI](https://github.com/EdwinJdevops/driftguard/actions/workflows/ci.yml) are publicly inspectable.
- **Boundary:** real cross-account AssumeRole integration and multi-tenant production operation are not established by the public checks. Some per-resource attribute-read failures still need stronger handling and tests.

[Case study](https://edwinjdevops.github.io/engineering-platform/projects/driftguard/) · [Inventory failure investigation](https://edwinjdevops.github.io/engineering-platform/articles/aws-inventory-failure-terraform-drift/)

### [Warden](https://github.com/EdwinJdevops/warden) — Policy-bounded Kubernetes remediation

Explores a GitOps remediation path that keeps policy enforcement and manual approval separate from the generation of proposed changes.

- [Go regression tests](https://github.com/EdwinJdevops/warden/blob/master/controller/internal/remediation/tier_test.go) exercise the boundary preventing automatic merge under manual-approval policy tiers.
- [Go CI workflow](https://github.com/EdwinJdevops/warden/actions/workflows/go-ci.yml) provides a repeatable source-level validation path.
- **Boundary:** controller PR integration is dry-run by default; end-to-end production integration is not independently established.

[Case study](https://edwinjdevops.github.io/engineering-platform/projects/warden/)

### [SENTINEL](https://github.com/EdwinJdevops/SENTINEL) — Kubernetes security scanning lab

Contains Trivy and Kubescape scanning artifacts, a scheduled GitHub Actions workflow, and a small report aggregation script.

- [Security scanning workflow](https://github.com/EdwinJdevops/SENTINEL/blob/main/.github/workflows/sentinel-scan.yml).
- **Boundary:** these artifacts do not establish a deployable runtime detection, observability or policy-enforcement platform.

[Case study](https://edwinjdevops.github.io/engineering-platform/projects/sentinel/)

## Engineering evidence and delivery

My [engineering website](https://edwinjdevops.github.io/engineering-platform/) publishes project boundaries, implementation details, technical investigations, and delivery records. The [website source](https://github.com/EdwinJdevops/engineering-platform) includes Hugo-based static delivery, source-controlled CI checks, and GitHub Pages deployment verification.

I also provide cloud and DevOps engineering services through **Edwin Cloud DevOps Services**. Confidential client work is not presented as publicly verified project evidence.

## Contact and credentials

- [Engineering website and services](https://edwinjdevops.github.io/engineering-platform/services/)
- [LinkedIn](https://www.linkedin.com/in/edwin-jonathan-1094093b0)
- [Technical articles](https://edwinjdevops.github.io/engineering-platform/articles/)
- [Microsoft Azure Fundamentals credential](https://learn.microsoft.com/en-us/users/jonathanedwin-0146/credentials/certification/azure-fundamentals)

I welcome technical review, platform/cloud engineering roles, open-source collaboration, and clearly scoped infrastructure engagements.
