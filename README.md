# devops-cicd-kubernetes-pipeline
Production-ready CI/CD pipeline using GitHub Actions to build Docker images and deploy containerized applications to Kubernetes with automated rolling updates.
# 🚀 DevOps CI/CD Kubernetes Pipeline

Production-ready CI/CD pipeline using GitHub Actions, Docker, and Kubernetes.

---

## 📌 Project Overview

This project demonstrates a modern DevOps workflow where:

- Application code is pushed to GitHub
- GitHub Actions automatically builds a Docker image
- Docker image is pushed to DockerHub
- Kubernetes cluster is updated automatically
- Rolling updates ensure zero downtime

---

## 🏗️ Architecture

Developer → GitHub → GitHub Actions → DockerHub → Kubernetes Cluster

---

## 🛠️ Tech Stack

- Git & GitHub
- GitHub Actions (CI/CD)
- Docker (Containerization)
- Kubernetes (Container Orchestration)
- Node.js (Sample Application)

---

## 📂 Project Structure
├── app.js
├── package.json
├── Dockerfile
├── k8s/
│ ├── deployment.yaml
│ └── service.yaml
└── .github/
└── workflows/
└── deploy.yml


---

## ⚙️ CI/CD Workflow

1. Push code to `main` branch
2. GitHub Actions triggers automatically
3. Docker image is built
4. Image pushed to DockerHub
5. Kubernetes deployment updated

---

## 🔐 Secrets Used

- DOCKER_USERNAME
- DOCKER_PASSWORD
- KUBE_CONFIG

Configured inside GitHub Actions secrets.

---

## 🚀 How to Run Locally

### Build Docker Image

### Run Container

### Deploy to Kubernetes

---

## 📈 Key DevOps Concepts Demonstrated

- CI/CD Automation
- Containerization
- Rolling Updates
- Infrastructure Automation
- Secret Management
- Kubernetes Services & Deployments

---

## 🧠 What I Learned

- Designing automated deployment pipelines
- Secure secret management in CI/CD
- Kubernetes workload management
- Docker image lifecycle
- Production-style DevOps workflow

---

## 👨‍💻 Author

Aniket Khamkar  
Aspiring DevOps Engineer
aniketdk
