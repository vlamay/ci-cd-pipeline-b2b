# 🚀 B2B SaaS CI/CD Pipeline with FastAPI & Fly.io

A real-world inspired DevOps pipeline for staging/production deployments of a FastAPI app via GitHub Actions and Fly.io.

## 🔧 Features

- 🐳 Docker-based microservice
- 🚀 Auto-deployment to Fly.io via GitHub Actions
- 🧪 Pytest-based testing
- 📂 Secrets via GitHub Actions and Fly.io
- 🛠️ Local dev with `venv` or `pipx`

## 🧪 Quick Start

```bash
# Run locally
pipx install fastapi[standard]
uvicorn app.main:app --reload
