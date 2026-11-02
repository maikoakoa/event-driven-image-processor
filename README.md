# Event-Driven Image Processing Platform

A cloud-native, event-driven image processing system built on AWS EKS.

## Architecture
(Client) --> (API) --> (SQS) --> (Worker) --> (S3)

## Tech Stack
- **Infrastructure:** Terraform, AWS (VPC, EKS, SQS, ECR, S3)
- **Container Orchestration:** Kubernetes (EKS), KEDA (Autoscaling)
- **Backend:** Node.js (API & Worker)
- **Observability:** Prometheus, Grafana, Loki
- **Testing:** K6

## Project Structure
- `apps/`: Source code for API and Worker.
- `infra/`: Terraform code for AWS infrastructure.
- `k8s/`: Kubernetes manifests (Deployment, Service, KEDA ScaledObject).

## Getting Started
(To be updated)