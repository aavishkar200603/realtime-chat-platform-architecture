# Architecture Documentation

---

# Overview

This project is a production-grade real-time chat platform built using React.js, Node.js, MongoDB, and Socket.IO.

The application supports real-time messaging, JWT-based authentication, online presence tracking, typing indicators, emoji reactions, and persistent chat history.

The platform is deployed across Amazon EKS and lightweight k3s Kubernetes environments using Terraform Infrastructure as Code, GitHub Actions CI/CD pipelines, NGINX Ingress networking, and Prometheus/Grafana observability.

---

# Application Architecture

```text
┌─────────────┐
│    User     │
└──────┬──────┘
       │
       ▼
┌─────────────┐
│ React Front │
└──────┬──────┘
       │
       ▼
┌─────────────────────┐
│ REST APIs + SocketIO│
└──────┬──────────────┘
       │
       ▼
┌─────────────────────┐
│ Node.js / Express   │
└──────┬──────────────┘
       │
       ▼
┌─────────────┐
│   MongoDB   │
└─────────────┘
```
---

# Hybrid Kubernetes Architecture

![Hybrid Kubernetes Architecture](../assets/architecture/hybrid-kubernetes-architecture.svg)

---

# Core Components

- React Frontend
- Node.js Backend API
- Socket.IO Real-Time Communication
- MongoDB
- Kubernetes Deployments
- NGINX Ingress Controller
- Prometheus
- Grafana

---

# Amazon EKS Architecture

## Components

- Amazon EKS
- Managed Node Groups
- AWS ECR
- Terraform
- Route53
- ACM TLS Certificates
- Elastic Load Balancer

---

# EKS Cluster Validation

![EKS Cluster Validation](../assets/infrastructure/eks-cluster-validation.png)

---

# EKS Worker Nodes

![EKS Worker Nodes](../assets/infrastructure/eks-worker-nodes.png)

---

# AWS Load Balancer

![AWS Load Balancer](../assets/infrastructure/aws-load-balancer.png)

---

# AWS ECR Repositories

![AWS ECR](../assets/infrastructure/aws-ecr.png)

---

# k3s Architecture

## Components

- Lightweight k3s Cluster
- DockerHub
- GitHub Actions
- NGINX Reverse Proxy

---

# Request Flow

```text
User
   ↓
NGINX Ingress
   ↓
Frontend Service
   ↓
Backend API
   ↓
MongoDB
```
