##🚀 Kubernetes CI/CD Deployment with GitHub Actions

## Overview
This project demonstrates automated deployment of a containerized application to Kubernetes using CI/CD pipelines.

## Tech Stack
- Kubernetes
- Docker
- GitHub Actions
- Python (Flask)

## Features
- Containerized application
- Kubernetes deployment and service
- Automated CI/CD pipeline
- Scalable deployment (replicas)

## How to Run

1. Build Docker image
2. Push to DockerHub
3. Apply Kubernetes manifests:
   kubectl apply -f deployment.yaml
   kubectl apply -f service.yaml

## Architecture
GitHub → CI/CD → Docker → Kubernetes Cluster
