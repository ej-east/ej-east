# Hey, I'm EJ

I build cloud platforms and compliance automation in FedRAMP High environments. I work across AWS, AWS GovCloud, Azure, and GCP. If it's hard and repetitive, I make it boring.

[![Website](https://img.shields.io/badge/Website-elijah.fyi-000000?style=flat-square&logo=safari&logoColor=white)](https://elijah.fyi)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/this-is-william-johnson/)

## What I do

- Provision cloud infrastructure with Terraform across AWS, AWS GovCloud, Azure, and GCP
- Deploy and manage Kubernetes workloads with Helm, Argo CD, and GitHub Actions
- Build CI/CD pipelines that replace hour-long manual processes with repeatable automation
- Add security controls with policy as code, vulnerability scanning, signed images, SBOMs, and attestations
- Build and operate a Kubernetes homelab focused on security, secrets, and learning how things fail
- If I do it twice, I automate it.

## Projects

### [Burns](https://github.com/ej-east/burns)

My third Kubernetes homelab iteration. Burns runs a three-node Ubuntu/K3s cluster with Terraform-managed Oracle Cloud infrastructure and Argo CD managing application deployments.

I use separate Traefik instances for public and private traffic. Tailscale handles private network access. Other services include Authentik, cert-manager, External Secrets, 1Password Connect, CloudNativePG, OpenSearch, and Fluent Bit.

### [Redoubt](https://github.com/ej-east/redoubt)

A collection of hardened, reproducible container images and reusable GitHub Actions workflows.

The pipeline builds multi-architecture images, scans them with Trivy and OpenSCAP, signs them with Cosign, and publishes SBOM attestations with Syft. It currently produces SLSA Build Level 2 provenance.

## What I work with

**Cloud and infrastructure:** AWS, AWS GovCloud, Azure, GCP, Terraform, Docker, Kubernetes, Linux

**GitOps and delivery:** Argo CD, Helm, GitHub Actions, ECR

**Security:** FedRAMP, NIST 800-53, OPA Gatekeeper, Wiz, Zscaler, Trivy, Cosign, Syft, OpenSCAP, SBOMs

**Languages:** Python, Bash, Rust

## Certifications

AWS Cloud Practitioner · Google Associate Cloud Engineer · HashiCorp Terraform Associate · CompTIA Security+ · PCAP (Python)
