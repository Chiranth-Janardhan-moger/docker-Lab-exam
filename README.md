# 🐳 DevOps Laboratory Dashboard - Exam Project

A containerized React-Vite web portal showcasing pipeline logs, deployment status, and mock laboratory evaluation metrics.

## 🚀 Features
- **Lab Board UI**: Visual dashboard for monitoring automated Jenkins build and docker container status.
- **Vite Setup**: High-performance module bundling.
- **Interactive Routing**: Built-in routing via `react-router-dom` for managing views.

## 📦 Quickstart
```bash
# Build Docker Image
docker build -t devops-lab-board .

# Run Container
docker run -p 80:80 devops-lab-board
```