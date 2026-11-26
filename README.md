# CloudMonitor

Production-oriented cloud-native monitoring platform.

CloudMonitor is a monitoring platform designed to register HTTP endpoints, execute periodic health checks, measure response times, detect outages and generate alerts.

## Architecture

- Frontend: React and TypeScript
- API Gateway: NGINX
- Monitoring API: Python and FastAPI
- Probe Worker: Python
- Alert Service: Python and FastAPI
- Database: PostgreSQL
- Message Broker: Redis Streams

## Infrastructure and DevOps

- Docker and Docker Compose
- Kubernetes and k3d
- Helm
- Terraform
- Ansible
- GitHub Actions
- GitHub Container Registry

## Observability

- Prometheus
- Grafana
- Loki
- OpenTelemetry

## Deployment strategy

Local first, using Docker, Docker Compose and k3d.

Future AWS deployment using VPC, EKS, ECR, RDS and ElastiCache.

## Project roadmap

- [x] Initial architecture and technology decisions
- [ ] Backend microservices
- [ ] Docker and Docker Compose integration
- [ ] Kubernetes deployment
- [ ] Helm charts
- [ ] Terraform infrastructure
- [ ] CI/CD with GitHub Actions
- [ ] Observability
- [ ] Security automation
- [ ] AWS deployment

## Project status

Currently in the initial architecture and environment preparation phase.
