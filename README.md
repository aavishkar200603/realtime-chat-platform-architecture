# Production-Grade Real-Time Chat Platform Architecture

## Live Demo

### Active Deployment

**https://chat.aavishkar.online**

---

## Overview

Full-stack real-time chat platform built using React.js, Node.js, MongoDB, and Socket.IO, enabling instant messaging, typing indicators, online presence tracking, emoji reactions, and JWT-based authentication.

The platform is deployed using production-grade cloud-native infrastructure across Amazon EKS and lightweight k3s Kubernetes environments with Terraform-based Infrastructure as Code, GitHub Actions CI/CD automation, NGINX Ingress networking, HTTPS/TLS termination, and Prometheus/Grafana observability.

This project demonstrates both full-stack application engineering and modern cloud-native deployment practices.

---

## Application Features

* Real-time messaging using Socket.IO
* JWT-based authentication and authorization
* Online/offline presence tracking
* Typing indicators
* Emoji reactions
* Persistent chat history using MongoDB
* Responsive React.js user interface
* REST API and WebSocket integration
* Secure HTTPS/TLS communication
* Production-ready deployment architecture

---

## Deployment Environments

### k3s Deployment

Realtime chat application deployed on a lightweight k3s Kubernetes cluster for development, testing, and production-style deployment validation.

#### Live Application

**https://chat.aavishkar.online**

---

### Amazon EKS Deployment

Amazon EKS infrastructure is provisioned on-demand for deployment demonstrations, Kubernetes validation, infrastructure testing, and architecture walkthroughs.

Realtime chat application deployed on Amazon EKS using NGINX Ingress, HTTPS/TLS termination, and cloud-native networking components.

EKS deployment screenshots and validation outputs are available throughout the documentation.

---

## Key Highlights

### Application Engineering

* React.js frontend with reusable component architecture
* Node.js and Express.js backend services
* Socket.IO-powered WebSocket communication
* JWT authentication and secure session management
* MongoDB-based message persistence
* Online presence and typing indicator implementation
* Real-time event-driven messaging architecture
* Responsive user experience across devices

### Cloud & DevOps Engineering

* Hybrid Kubernetes deployments (Amazon EKS + k3s)
* Terraform-based Infrastructure as Code
* Multi-repository GitHub Actions CI/CD pipelines
* Dockerized frontend and backend services
* NGINX Ingress with HTTPS/TLS termination
* Prometheus and Grafana observability stack
* AWS ECR and DockerHub deployment workflows
* Kubernetes rolling deployments and health probes
* Environment-aware deployment automation
* Production-style ingress networking

---

## Tech Stack

### Frontend

* React.js
* JavaScript
* Socket.IO Client
* JWT Authentication

### Backend

* Node.js
* Express.js
* MongoDB
* Socket.IO
* REST APIs

### Cloud & DevOps

* Docker
* Kubernetes
* Terraform
* GitHub Actions
* Prometheus
* Grafana
* NGINX Ingress
* cert-manager

### AWS Services

* Amazon EKS
* Amazon EC2
* Amazon ECR
* Amazon VPC
* IAM
* Route53
* ACM
* Elastic Load Balancer

---

## Application Screenshots

### Login Experience

Application login interface with JWT-based authentication workflow.

### Real-Time Messaging Experience

Demonstrates instant message delivery, typing indicators, online presence tracking, emoji reactions, and WebSocket-powered communication.

---

## System Architecture

### Hybrid Kubernetes Architecture

Demonstrates deployment portability across Amazon EKS and lightweight k3s Kubernetes environments using a shared application architecture and deployment workflow.

[Architecture Diagram]

---

### CI/CD Workflow

Automated build, validation, containerization, and deployment pipeline powered by GitHub Actions.

[CI/CD Diagram]

---

### Monitoring Architecture

Production-style observability stack using Prometheus and Grafana for metrics collection, workload monitoring, and operational visibility.

[Monitoring Diagram]

---

### Infrastructure Provisioning Architecture

Terraform-based Infrastructure as Code for provisioning AWS networking, compute, Kubernetes, and supporting cloud resources.

[Infrastructure Diagram]

---

## Repository Ecosystem

| Repository                | Purpose                                                                             | Access               |
| ------------------------- | ----------------------------------------------------------------------------------- | -------------------- |
| Frontend Repository       | React frontend and Socket.IO client integration                                     | Available on request |
| Backend Repository        | Node.js APIs, authentication, and real-time communication                           | Available on request |
| Infrastructure Repository | Terraform infrastructure, Kubernetes manifests, and deployment workflows            | Available on request |
| Architecture Repository   | Architecture diagrams, observability setup, networking workflows, and documentation | Public               |

---

## Repository Access

Some repositories remain private because they contain deployment automation, infrastructure provisioning workflows, environment-specific configurations, and cloud infrastructure assets.

Access can be provided upon request for technical review, interview discussions, or architecture walkthroughs.

---

## Documentation

* Architecture Documentation
* Deployment Documentation
* Monitoring Documentation
* Networking Documentation

---

## Learning Outcomes

This project demonstrates practical experience with:

### Full-Stack Engineering

* React.js
* Node.js
* Express.js
* MongoDB
* Socket.IO
* JWT Authentication
* REST APIs
* Real-Time Communication Systems

### Cloud Engineering

* AWS Infrastructure
* Amazon EKS
* VPC Networking
* IAM
* Route53
* ECR
* Load Balancing

### DevOps Engineering

* Docker
* Kubernetes
* Terraform
* GitHub Actions
* CI/CD Pipelines
* Prometheus
* Grafana
* NGINX Ingress

---

## Author

### Aavishkar Pawar

LinkedIn:
https://www.linkedin.com/in/aavishkarpawar

GitHub:
https://github.com/aavishkar200603
