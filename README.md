# 🚀 End-to-End GitOps Project Using AWS EKS & ArgoCD 🌐



I'm excited to share a comprehensive guide on implementing GitOps for a Golang web application using Kubernetes & ArgoCD. This project covers containerization, Kubernetes deployment, CI/CD pipelines, and more.

# Key Highlights:

📍 Installation and Setup: Golang, kubernetes, Kubectl, and Helm.

📍 Containerization: Multi-stage Dockerfile for the Golang web application.

📍 Kubernetes Manifests: Deployment, service, and ingress files.

📍 EKS Cluster Creation: Create an EKS cluster using EKS CTL.

📍 Ingress Controller: Setup Nginx Ingress Controller for domain mapping.

📍 Helm Charts: Enable multi-environment support and facilitate GitOps.

📍 Continuous Integration: GitHub Actions for build, test, docker image creation, and pushing to DockerHub.

📍 Continuous Deployment: ArgoCD for automated deployment from DockerHub.

# Go Web Application

This is a simple website written in Golang. It uses the `net/http` package to serve HTTP requests.

## Running the server

To run the server, execute the following command:

```bash
go run main.go
```

The server will start on port 8080. You can access it by navigating to `http://localhost:8080/courses` in your web browser.

## Looks like this

![Website](static/images/golang-website.png)


