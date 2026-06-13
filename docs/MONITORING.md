# Monitoring Documentation

---

# Overview

This project integrates Prometheus and Grafana for Kubernetes observability and real-time application monitoring.

---

# Monitoring Features

- Prometheus-based metrics collection
- Kubernetes pod monitoring
- Application metrics scraping
- Real-time observability dashboards
- Resource utilization tracking
- Health monitoring and target validation
- Grafana visualization dashboards

---

# Monitoring Architecture

![Monitoring Architecture](../assets/architecture/monitoring-architecture.svg)

---

# Prometheus

Prometheus scrapes Kubernetes pods using annotations.

Example:

```yaml
annotations:
  prometheus.io/scrape: "true"
  prometheus.io/port: "5000"
  prometheus.io/path: "/metrics"
```

---

# Prometheus Target Health

![Prometheus Targets](../assets/monitoring/prometheus-targets.png)

---

# Grafana

Grafana dashboards visualize:

- Kubernetes cluster metrics
- Pod resource utilization
- Application health
- Real-time monitoring insights

---

# Metrics Collected

The monitoring stack collects metrics from Kubernetes workloads and application services including:

- Pod health and availability
- Kubernetes deployment status
- Frontend and backend pod metrics
- Node.js application metrics
- Active requests
- Active handles
- Active resources
- Prometheus scrape target health
- Infrastructure and application observability metrics

---

# Grafana Dashboard

![Grafana Dashboard](../assets/monitoring/grafana-dashboard.png)
