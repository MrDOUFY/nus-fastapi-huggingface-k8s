# nus-fastapi-huggingface-k8s
A production-ready FastAPI application with Hugging Face Question-Answering model, containerized using Docker and deployed on Kubernetes (DigitalOcean). Includes NGINX Ingress, multi-architecture Docker build (AMD64 + ARM64), and CI/CD integration.

---

## 🚀 Features

- **FastAPI Backend** — lightweight REST API with `/chat` endpoint  
- **Hugging Face Model** — `distilbert-base-uncased-distilled-squad` for QA tasks  
- **Docker Multi-Arch Build** — runs on both ARM (Mac M1/M2) and AMD (cloud)  
- **Kubernetes Deployment** — manifests for Deployment, Service, and Ingress  
- **Ingress Routing** — via `sslip.io` hostname and NGINX controller  
- **CI/CD Ready** — GitHub Actions workflow for auto Docker build + push  
