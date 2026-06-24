# GitOps Platform

A DevOps project demonstrating containerization and Kubernetes deployment.

## Tech Stack

- Python Flask
- Docker
- Kubernetes
- Minikube

## Architecture

Developer
  ↓
Git
  ↓
Docker
  ↓
Kubernetes
  ↓
Flask Application

## Deployment

```bash
kubectl apply -f k8s/
