# 🚀 Shell Scripting Automation with Jenkins, Docker & AWS EC2

## 📌 Project Overview

This project demonstrates a complete DevOps CI/CD pipeline using GitHub, Jenkins, Docker, Docker Hub, and AWS EC2.

Whenever code is pushed to GitHub, Jenkins automatically builds a Docker image and pushes it to Docker Hub. The image is then deployed and executed on an AWS EC2 instance.

---

## 🛠 Technologies Used

- Linux (Ubuntu)
- Shell Scripting (Bash)
- Git
- GitHub
- GitHub Webhooks
- Jenkins
- Docker
- Docker Hub
- AWS EC2

---

## 📂 Project Structure

```
docker-ci-project/
│── Dockerfile
│── Jenkinsfile
│── app.sh
│── test.txt
```

---

## ⚙️ CI/CD Workflow

```
Developer
    │
    ▼
Git Push
    │
    ▼
GitHub Repository
    │
    ▼
GitHub Webhook
    │
    ▼
Jenkins Pipeline
    │
    ▼
Docker Image Build
    │
    ▼
Docker Hub
    │
    ▼
AWS EC2
    │
    ▼
Docker Container
```

---

## 🚀 Features

- Automated CI/CD Pipeline
- GitHub Webhook Integration
- Jenkins Pipeline Automation
- Docker Image Creation
- Docker Hub Image Push
- AWS EC2 Deployment
- Shell Script Execution inside Docker Container

---

## 📦 Docker Commands

### Build Image

```bash
docker build -t yarlagaddapurush/docker-ci-project .
```

### Run Container

```bash
docker run --name docker-ci-project yarlagaddapurush/docker-ci-project
```

### View Logs

```bash
docker logs docker-ci-project
```

---

## ☁️ AWS Deployment

1. Launch Ubuntu EC2 Instance
2. Install Docker
3. Login to Docker Hub
4. Pull Docker Image

```bash
docker pull yarlagaddapurush/docker-ci-project:latest
```

5. Run Container

```bash
docker run --name docker-ci-project yarlagaddapurush/docker-ci-project:latest
```

---

## 📋 Jenkins Pipeline

The Jenkins pipeline performs the following tasks:

- Clone Repository from GitHub
- Build Docker Image
- Push Docker Image to Docker Hub
- Deploy Docker Container

---

## 📊 Project Outcome

Successfully built an end-to-end CI/CD pipeline integrating:

- GitHub
- Jenkins
- Docker
- Docker Hub
- AWS EC2

The application was successfully deployed and executed on an AWS EC2 instance.

---

## 👨‍💻 Author

**Yarlagadda Purush**

B.Tech – Artificial Intelligence & Data Science

GitHub: https://github.com/purush777196
