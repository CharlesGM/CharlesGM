# Charles Mbugua Gachango

**Senior DevOps / Site Reliability Engineer** based in Nairobi, Kenya. I keep production systems up, cut cloud bills, and build the tooling that makes both repeatable.

8+ years running Kubernetes and multi-cloud infrastructure (AWS, GCP, Azure) across fintech, banking, blockchain, and SaaS. I focus on incident response and root-cause analysis, observability on the Grafana stack, and FinOps. Recent highlights: **$746K in verified annualized AWS savings**, a **45-customer observability platform** shipped in 7 days, and a self-hosted CI fleet scaled to **~200 runners (~1,800 jobs/hour)**.

---

## What I do

**Reliability & incident response.** Own triage and root-cause for P1 / showstopper incidents across US, EU, and Asia production environments. Recent catches: a silent alert-drop discarding real incidents across four clusters, and a release whose deferred DB migration shipped an untracked regression to 12 customer orgs.

**Observability engineering.** Built a multi-tenant Grafana / Mimir / Loki / Tempo platform for a 45-instance SaaS fleet, dashboards and alerts shipped as Terraform. Onboarded two AWS estates (ECS Fargate + EKS) streaming ~26,000 metric series while holding ingest cost to $182/mo against a $3,100 unfiltered baseline.

**Cloud cost optimization (FinOps).** Delivered $746K realized annualized AWS savings across 52 items, ranking 2nd of 20 engineers at 96% of estimate realized, every change validated against live billing before execution.

**Platform & CI.** Contributed production Go to a self-hosted GitHub Actions runner platform: fixed a dispatch race, added vCPU-aware autoscaling, moved to one ephemeral instance per job. Scaled it to ~200 EC2 runners and migrated 9 repos off hosted runners.

**AI-assisted operations.** Building read-only diagnostic agents and MCP servers in Python that cross-check firing alerts against live AWS and label each finding confirmed, contradicted, or unverifiable, cutting incident time-to-context.

---

## Tech stack

**Cloud:** AWS (EKS, ECS Fargate, CloudWatch, Secrets Manager) · GCP (GKE, Workload Identity, Networking) · Azure (AKS, Key Vault, DevOps)

**Kubernetes:** EKS / GKE / AKS · Helm · ArgoCD · GitOps · Docker

**Observability:** Prometheus · Grafana · Mimir · Loki · Tempo · Grafana Alloy · Thanos · PromQL / LogQL

**IaC & CI/CD:** Terraform · Crossplane · Ansible · GitHub Actions · Azure DevOps

**Security:** Zero-trust · HashiCorp Vault · IAM · GCP Workload Identity Federation · DevSecOps

**Languages:** Python · Bash · Go · AI agent tooling (MCP, Claude API)

---

## Featured projects

Most of my production work lives in private and employer repositories. A few public pieces that show how I build:

- **[oidc-gcp-integration-project](https://github.com/CharlesGM/oidc-gcp-integration-project)**: keyless CI/CD using GCP Workload Identity Federation with GitHub Actions and Terraform. The pattern I use to kill long-lived cloud credentials.
- **[nethermind-network-manager](https://github.com/CharlesGM/nethermind-network-manager)**: Helm-based deployment for running Nethermind Ethereum nodes on Kubernetes (miners, bootnodes, configurable networks).
- **[erc-20-geth-gcp](https://github.com/CharlesGM/erc-20-geth-gcp)**: ERC-20 deployment on Ethereum Sepolia using Geth on GCP, provisioned with Terraform.

---

## Experience

- **Trilogy**: DevOps Engineer, remote (Sep 2025 – present)
- **Diamond Trust Bank Africa**: Senior DevSecOps & Cloud Engineer (Jan 2025 – Aug 2025)
- **Fujitsu Uvance**: Senior DevOps Engineer, remote (Sep 2022 – Aug 2024)
- **Orteo Payment Systems**: Lead Cloud Engineer (Mar 2020 – Feb 2022)

Earlier: security analyst roles in penetration testing and SDLC audits across banking. BSc Electronics & Computer Engineering (JKUAT). GCP Professional Security Engineer, HashiCorp Terraform Associate, CCNA/CCNP.

---

## Connect

📧 gachangocmbugua@gmail.com · 💼 [LinkedIn](https://www.linkedin.com/in/charles-mbugua-b7525ba5/)
