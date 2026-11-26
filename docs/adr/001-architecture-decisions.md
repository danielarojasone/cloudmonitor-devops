
# ADR-001: Initial Technology Decisions

## Status
Accepted

## Context

CloudMonitor requires a scalable, maintainable and
cloud-native architecture.

## Decisions

### Backend
Python with FastAPI.

### Frontend
React with TypeScript.

### Database
PostgreSQL.

### Messaging
Redis Streams.

### Containerization
Docker.

### Orchestration
Kubernetes using k3d locally and EKS in AWS.

### Infrastructure as Code
Terraform.

### Configuration Management
Ansible.

### CI/CD
GitHub Actions.

### Container Registry
GitHub Container Registry.

### Observability
Prometheus, Grafana, Loki and OpenTelemetry.

## Consequences

The architecture introduces independent deployable
services and asynchronous communication.

Operational complexity is higher than a monolithic
application, so service boundaries and operational
procedures must be documented.
