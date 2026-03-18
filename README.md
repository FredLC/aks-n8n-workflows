# Production-Ready n8n Deployment on Azure Kubernetes Service (AKS)

This project demonstrates the deployment of a **production-grade workflow automation platform (n8n)** on Azure Kubernetes Service (AKS), with a strong focus on **security, scalability, and operational best practices**.

## Overview

Designed and deployed a secure, scalable cloud-native application using:

- Azure Kubernetes Service (AKS)
- Terraform (Infrastructure as Code)
- Azure Key Vault (secrets management)
- PostgreSQL (stateful backend)
- GitOps (Flux)

## Key Features

### Infrastructure as Code
Provisioned AKS and supporting resources using Terraform for reproducibility and consistency.

### Secure Application Exposure
Configured Kubernetes Ingress with TLS using cert-manager to securely expose the application to the internet.

### Data Persistence & Backups
Deployed PostgreSQL with backup and restore capabilities to ensure data durability and recovery.

### Secrets Management
Integrated Azure Key Vault for secure handling of application secrets.

### GitOps Deployment
Implemented GitOps workflows using Flux for automated and version-controlled deployments.

### Observability & Operations
Deployed a production-grade monitoring stack using Prometheus and Grafana.


## Outcome

- Delivered a **secure and production-ready Kubernetes deployment**  
- Implemented **GitOps-driven application lifecycle management**  
- Ensured **data reliability through backup and restore testing**  
- Applied **best practices for AKS operations and cluster security**


## Tech Stack

Azure (AKS, Key Vault), Terraform, Kubernetes, Flux, PostgreSQL, Prometheus, Grafana, n8n
