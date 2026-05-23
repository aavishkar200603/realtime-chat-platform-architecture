# Production-Grade Real-Time Chat Platform with Hybrid Kubernetes Deployment

## Live Demo

### Active Deployment
- https://chat.aavishkar.online

### Amazon EKS Deployment

Amazon EKS infrastructure is provisioned on-demand for deployment demonstrations, Kubernetes validation, and infrastructure testing.

EKS deployment screenshots and validation outputs are available throughout the documentation.

---

# Live Application

## k3s Deployment

Realtime chat application deployed on lightweight k3s Kubernetes cluster.

![k3s Live Application](assets/deployment/k3s-live-chat-application.png)

---

## Amazon EKS Deployment

Realtime chat application deployed on Amazon EKS with NGINX Ingress and TLS.

![EKS Live Application](assets/deployment/eks-live-chat-application.png)

---

# Overview

Production-style cloud-native real-time chat platform demonstrating hybrid Kubernetes deployments, Infrastructure as Code, CI/CD automation, observability, and cloud-native networking.

The project showcases deployment workflows across both Amazon EKS and lightweight k3s environments using unified GitHub Actions pipelines and Terraform-based infrastructure provisioning.

---

# Key Highlights

- Hybrid Kubernetes deployments (Amazon EKS + k3s)
- Terraform-based Infrastructure as Code
- Multi-repository GitHub Actions CI/CD pipelines
- Dockerized frontend and backend services
- NGINX Ingress with HTTPS/TLS termination
- Prometheus + Grafana observability stack
- AWS ECR + DockerHub deployment workflows
- Kubernetes rolling deployments and health probes
- Environment-aware deployment automation
- Production-style ingress networking
- TLS-secured Kubernetes workloads

---

# Tech Stack

## Backend & Frontend

- React.js
- Node.js
- Express.js
- MongoDB
- Socket.IO

## DevOps & Cloud

- Docker
- Kubernetes
- Terraform
- GitHub Actions
- Prometheus
- Grafana
- NGINX Ingress
- cert-manager

## AWS

- EKS
- EC2
- VPC
- IAM
- ECR
- Route53
- ACM
- Elastic Load Balancer

---

# System Architecture

## Hybrid Kubernetes Architecture

![Hybrid Kubernetes Architecture](assets/architecture/hybrid-kubernetes-architecture.svg)

---

# CI/CD Workflow

![CI/CD Workflow](assets/architecture/github-actions-flow.svg)

---

# Monitoring Architecture

![Monitoring Architecture](assets/architecture/monitoring-architecture.svg)

---

# Infrastructure Provisioning Architecture

![Infrastructure Provisioning](assets/architecture/infrastructure-provisioning-architecture.svg)

---

# Repository Ecosystem

| Repository | Purpose | Access |
|------------|----------|---------|
| [Frontend Repository](https://github.com/aavishkar200603/realtime-chat-platform-frontend) | React frontend and Socket.IO client integration | Available on request |
| [Backend Repository](https://github.com/aavishkar200603/realtime-chat-platform-backend) | Node.js APIs, authentication, and real-time communication | Available on request |
| [Infrastructure Repository](https://github.com/aavishkar200603/realtime-chat-platform-Infra) | Terraform infrastructure, Kubernetes manifests, and deployment workflows | Available on request |
| [Architecture Repository](https://github.com/aavishkar200603/realtime-chat-platform-devops-architecture) | Architecture diagrams, observability setup, networking workflows, and documentation | Public |

---

# Repository Access

Some repositories remain private because they contain infrastructure automation and deployment configurations.

Access can be provided upon request for technical review or interview discussions.

---

# Documentation

- [Architecture Documentation](docs/ARCHITECTURE.md)
- [Deployment Documentation](docs/DEPLOYMENT.md)
- [Monitoring Documentation](docs/MONITORING.md)
- [Networking Documentation](docs/NETWORKING.md)

---

# Author

Aavishkar Pawar

- LinkedIn: https://www.linkedin.com/in/aavishkarpawar
- GitHub: https://github.com/aavishkar200603