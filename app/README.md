# 🚀 Multi-Cloud CI/CD Pipeline Project

This project builds a real-world CI/CD pipeline deploying applications into Kubernetes clusters across AWS (EKS) and Azure (AKS).

## 📦 Components Used:
- AWS EKS
- Azure AKS
- Terraform (Infrastructure as Code)
- Kubernetes
- Helm Charts
- GitHub Actions (CI/CD)
- Docker (Containerization)
- Monitoring (Prometheus & Grafana - optional for future)

## 🛠 How It Works:
1. Application code is pushed to GitHub ➔ triggers GitHub Actions.
2. Docker image is built and pushed to DockerHub.
3. Terraform provisions EKS & AKS clusters.
4. Helm deploys the app automatically into Kubernetes clusters.

## 🚀 Deploy Your Own:
- Clone repo
- Configure GitHub Secrets
- Push to main branch
- Your app will deploy automatically to AWS and Azure!

---
