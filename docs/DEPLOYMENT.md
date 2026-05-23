# Deployment Documentation

---

# CI/CD Overview

This project uses GitHub Actions-based multi-repository CI/CD pipelines integrated with Docker, Kubernetes, Terraform, and cloud-native deployment workflows.

---

# CI/CD Workflow

![CI/CD Workflow](../assets/architecture/github-actions-flow.svg)

---

# Backend CI/CD Pipeline

The backend pipeline automates:

- Docker image builds
- AWS ECR image push
- DockerHub image push
- Kubernetes deployment updates
- Environment-aware deployments

![Backend Pipeline](../assets/github-actions/backend-pipeline.png)

---

# Frontend CI/CD Pipeline

The frontend pipeline automates:

- Frontend Docker image builds
- Registry pushes
- Kubernetes rollout updates

![Frontend Pipeline](../assets/github-actions/frontend-pipeline.png)

---

# Infrastructure Deployment Pipeline

The infrastructure deployment pipelines automate:

- Kubernetes manifest deployment
- Frontend deployment orchestration
- Backend deployment orchestration
- TLS setup
- Ingress deployment
- Rolling deployment updates
- Repository dispatch-based deployment automation

---

## Backend Infrastructure Deployment

![Backend Infra Pipeline](../assets/github-actions/infra-backend-pipeline.png)

---

## Frontend Infrastructure Deployment

![Frontend Infra Pipeline](../assets/github-actions/infra-frontend-pipeline.png)

---

# Kubernetes Deployment Validation

![Kubernetes Validation](../assets/deployment/kubectl-validation.png)

---

# Kubernetes Worker Nodes

![Worker Nodes](../assets/deployment/kubectl-nodes.png)

---

# Deployment Workflow

```text
Developer Push
      ↓
GitHub Actions
      ↓
Docker Build
      ↓
Push to Registry
      ↓
Trigger Infra Repository
      ↓
kubectl Deployment Update
      ↓
Kubernetes Cluster
```