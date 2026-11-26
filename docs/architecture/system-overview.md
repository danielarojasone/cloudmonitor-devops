
# CloudMonitor - System Architecture

## 1. Project Overview

CloudMonitor is a cloud-native monitoring platform
designed to monitor HTTP endpoints, collect availability
metrics, detect incidents and generate alerts.

## 2. Architecture Style

- Microservices
- Event-driven communication
- Containerized workloads
- Kubernetes orchestration
- Infrastructure as Code
- Automated CI/CD

## 3. Application Components

- Frontend: React and TypeScript
- API Gateway: NGINX
- Monitoring API: Python and FastAPI
- Probe Worker: Python
- Alert Service: Python and FastAPI
- Database: PostgreSQL
- Message Broker: Redis Streams

## 4. Infrastructure Components

- Docker
- Docker Compose
- Kubernetes (k3d locally)
- Terraform
- Ansible
- GitHub Actions
- GitHub Container Registry
- Helm

## 5. Observability

- Prometheus
- Grafana
- Loki
- OpenTelemetry

## 6. Deployment Environments

### Local
Linux Mint, Docker and k3d.

### Cloud
AWS VPC, EKS, ECR, RDS and ElastiCache.

## 7. Security Principles

- Least privilege
- No secrets in source code
- Container image scanning
- Infrastructure security scanning
- Kubernetes RBAC
- Network segmentation
- Automated security checks
