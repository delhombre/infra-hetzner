# 🚀 Hetzner Infrastructure

Infrastructure as Code for centralized management of K3s clusters on Hetzner Cloud. Automated provisioning via Ansible and GitOps-based Kubernetes application deployment.

## 🎯 Goals

- Reproducible provisioning of Hetzner VPS
- Automated deployment of highly available K3s clusters
- Centralized configuration and secrets management
- GitOps pipeline for application deployments

## 🛠️ Tech Stack

- **Cloud Provider**: Hetzner Cloud
- **IaC**: Ansible
- **Orchestration**: K3s (Lightweight Kubernetes)
- **GitOps**: ArgoCD / FluxCD
- **Secrets**: Sealed Secrets / External Secrets Operator

## 📁 Structure

```
├── ansible/          # Ansible playbooks and roles
├── kubernetes/       # K8s manifests and GitOps configs
├── docs/            # Detailed documentation
└── scripts/         # Utility scripts
```

## 🚦 Prerequisites

- Ansible >= 2.14
- kubectl >= 1.28
- Hetzner Cloud account with API token

## 🏃 Quick Start

See [GETTING_STARTED.md](docs/GETTING_STARTED.md)

---

**Note**: This repository contains infrastructure only. Applications are deployed from their respective repos via GitOps.
