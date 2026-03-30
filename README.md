# AI BankApp DevOps (Kubernetes Kind + Ollama Integration)
# Project Overview

This project demonstrates a **DevOps deployment of a Banking Application with AI integration** using Docker and Kubernetes (Kind). The application is containerized and deployed on a local Kubernetes cluster and integrates **Ollama LLM** to provide AI capabilities.

This project shows practical implementation of:

- **Containerization** – Docker was used to package the Spring Boot banking application for consistent deployments.
- **Kubernetes Orchestration** – Kubernetes manages deployment, networking, scaling, and service communication.
- **AI Model Deployment** – Ollama LLM deployed as a container inside Kubernetes.
- **Multi-container Architecture** – Application designed with multiple services:
  - Bank Application (Spring Boot)
  - MySQL Database
  - Ollama AI Service
- **DevOps Deployment Practices**
  - Kubernetes manifests organization
  - Resource requests and limits
  - Horizontal Pod Autoscaler (HPA)
  - Service exposure using NodePort
  - Kubernetes troubleshooting

---

## DevOps Tools

- Docker
- Kubernetes
- Kind (Kubernetes in Docker)
- Kubectl
- Helm (Learning – not implemented in this project)
---

## AI Integration

- Ollama (Local LLM runtime)
- LLM container deployment in Kubernetes
