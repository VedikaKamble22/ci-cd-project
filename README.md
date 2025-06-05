# 🚀 CI/CD Pipeline with GitHub Actions & Docker

This project demonstrates a basic Continuous Integration and Continuous Deployment (CI/CD) pipeline using *GitHub Actions* and *Docker*. On every push to the main branch, a Docker image is built and (optionally) pushed to Docker Hub automatically.

---

## 📦 Project Overview

A simple Node.js app is containerized using Docker. GitHub Actions is used to automate the CI/CD process.

---

## 🧱 Features

- 🐳 Dockerized Node.js app
- 🤖 GitHub Actions for CI/CD automation
- 🔐 Secrets-based login to DockerHub
- 📤 Auto-push Docker image to DockerHub on each commit

---

## 🛠️ Tools Used

- *Node.js*
- *Docker*
- *Git & GitHub*
- *GitHub Actions*
- *DockerHub*

---

## ⚙️ How the Pipeline Works

1. Code is pushed to the main branch
2. GitHub Actions runs:
   - Checks out the repo
   - Logs into DockerHub using secrets
   - Builds Docker image using Dockerfile
   - Pushes image to DockerHub with latest tag

---

## 📷 Screenshots

> (Include these screenshots in your project or report)

- ✅ GitHub Actions successful run
- ✅ DockerHub repo showing image tag

---

## 📤 DockerHub Image

If enabled, the built Docker image is pushed to:

👉 [https://hub.docker.com/repository/docker/vedikakamble22/ci-cd-project](https://hub.docker.com/repository/docker/vedikakamble22/ci-cd-project)

---

## 📚 Learnings

- Learned how to automate Docker builds using GitHub Actions
- Understood the use of GitHub Secrets for secure credentials
- Gained confidence in setting up basic DevOps pipelines

---

## 🙋‍♀️ Author

*Vedika Kamble*  
📧 kamblevedika22@gmail.com
