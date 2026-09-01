<div align="center">

# Edwin Jonathan

### Cloud Platform Engineer
**Infrastructure Reliability · Cloud Security · Kubernetes · Infrastructure Automation**

<a href="https://www.linkedin.com/in/edwin-jonathan-1094093b0">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white">
</a>
<a href="https://hashnode.com/@jonathandevops">
  <img src="https://img.shields.io/badge/Hashnode-2962FF?style=flat-square&logo=hashnode&logoColor=white">
</a>
<a href="https://x.com/TheCloudDeveng">
  <img src="https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white">
</a>
<a href="https://learn.microsoft.com/credentials/certifications/azure-fundamentals/">
  <img src="https://img.shields.io/badge/AZ--900-Certified-0078D4?style=flat-square&logo=microsoftazure&logoColor=white">
</a>

</div>

---

## Engineering

I build and investigate **cloud infrastructure and platform systems where reliability, security, automation, and operational control intersect.**

My work spans AWS, Azure, Kubernetes, Terraform, GitOps, observability, cloud security, and AI-assisted infrastructure operations.

A recurring problem across my work is the gap between:

**what infrastructure is declared to be → what is actually running → what should happen when those states diverge.**

That problem drives much of my work around infrastructure drift, security posture, Kubernetes operations, and controlled remediation.

---

## Selected Systems

### `DriftGuard`
**Terraform drift detection → security analysis → cost impact → reviewable remediation**

DriftGuard compares Terraform state against live AWS infrastructure and turns detected divergence into actionable engineering evidence.

- Detects infrastructure drift across supported AWS resources
- Maps findings against CIS AWS Benchmarks and MITRE ATT&CK
- Calculates estimated monthly cost deltas
- Generates Terraform HCL remediation
- Opens GitHub pull requests instead of modifying infrastructure directly
- Uses STS AssumeRole with workspace-specific external IDs
- Uses GitHub App installation tokens rather than shared PATs
- Includes CLI, API, dashboard and VS Code integration

`AWS` `Terraform` `Python` `FastAPI` `PostgreSQL` `Redis` `GitHub Apps`

**[Repository](https://github.com/EdwinJdevops/driftguard) · [Demo](https://github.com/EdwinJdevops/driftguard/tree/main/demo)**

---

### `InfraGuard Agent`
**AI-assisted infrastructure security analysis and controlled remediation**

InfraGuard explores a harder problem than simply adding an LLM to DevOps:

> **How much authority should an AI system have when its output can change infrastructure?**

The system:

- Processes infrastructure security findings
- Uses Azure AI Foundry and Phi-4 reasoning
- Performs structured root-cause and blast-radius analysis
- Applies a 70% confidence gate
- Generates Terraform remediation
- Creates GitHub pull requests
- Maintains an audit trail
- Uses OIDC / workload identity rather than static runtime credentials
- Never directly applies infrastructure changes

The final path is:

**Finding → Analysis → Confidence Gate → Terraform → GitHub PR → Human Approval → Infrastructure**

`Azure AI Foundry` `Phi-4` `FastAPI` `Terraform` `OIDC` `Kubernetes` `GitHub Actions`

**[Repository](https://github.com/EdwinJdevops/infraguard-agent) · [Live Dashboard](https://infraguard-agent.onrender.com/dashboard) · [API](https://infraguard-agent.onrender.com/docs)**

---

### `SENTINEL`
**Kubernetes security posture + runtime detection + observability**

A Kubernetes security pipeline combining:

- Trivy vulnerability scanning
- Kubescape MITRE ATT&CK assessment
- Falco runtime detection
- Prometheus metrics
- Grafana visualization
- ArgoCD GitOps delivery
- Terraform infrastructure provisioning

Example assessment recorded in the project:

**80/100 Kubescape score · 101 Kubernetes resources assessed · 10 failed controls**

`Kubernetes` `Trivy` `Kubescape` `Falco` `Prometheus` `Grafana` `ArgoCD` `Terraform`

**[Repository](https://github.com/EdwinJdevops/SENTINEL)**

---

### `ARCHNET`
**Zero-trust Internal Developer Platform on Kubernetes**

A GitOps-driven platform architecture built around:

- K3s
- ArgoCD
- Terraform
- Sealed Secrets
- Prometheus
- Loki
- GitHub Actions

The project focuses on the platform boundary between developers, workloads, infrastructure, secrets, deployment automation, and observability.

`K3s` `Kubernetes` `ArgoCD` `Terraform` `Sealed Secrets` `Loki` `Prometheus`

**[Repository](https://github.com/EdwinJdevops/ARCHNET)**

---

## Core Engineering Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,azure,kubernetes,terraform,docker,githubactions,prometheus,grafana&perline=8" />
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,postgres,redis,linux,git&perline=8" />
</p>

### Cloud
`AWS` · `Azure`

### Platform
`Kubernetes` · `K3s` · `ArgoCD` · `GitOps`

### Infrastructure
`Terraform` · `Helm` · `Kustomize` · `Ansible`

### Security
`IAM` · `OIDC` · `RBAC` · `NetworkPolicy` · `Trivy` · `Kubescape` · `Falco`

### Observability
`Prometheus` · `Grafana` · `Loki` · `CloudWatch`

### AI Infrastructure
`Azure AI Foundry` · `Phi-4` · `LangGraph`

### Backend / Automation
`Python` · `FastAPI` · `Celery` · `Redis` · `PostgreSQL` · `Bash`

---

## Engineering Interests

**Infrastructure Control**

**Platform Engineering**

**Kubernetes Reliability**

**Cloud Security**

**Infrastructure as Code**

**GitOps**

**Observability**

**AI-assisted Infrastructure Operations**

---

## Writing

I write about infrastructure problems rather than technology checklists:

- Cloud architecture and failure modes
- Kubernetes security and operations
- Terraform and infrastructure drift
- GitOps and platform engineering
- Reliability and observability
- Controlled automation of infrastructure operations

**[Read the engineering notes →](https://hashnode.com/@jonathandevops)**

---

## Connect

**LinkedIn:** [Edwin Jonathan](https://www.linkedin.com/in/edwin-jonathan-1094093b0)

**Hashnode:** [@jonathandevops](https://hashnode.com/@jonathandevops)

**GitHub:** [EdwinJdevops](https://github.com/EdwinJdevops)
