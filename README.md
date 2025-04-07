# 🚀 Node.js CI/CD Web App with GitHub Actions & Docker

This project demonstrates how to build a **CI/CD pipeline** using **GitHub Actions** to automate testing, building, and deployment of a **Node.js web app** via **Docker** to **DockerHub**.

---

## 🧰 Tech Stack

- Node.js
- Docker
- GitHub Actions
- DockerHub

---

## 📁 Project Structure

my-node-app/
├── Dockerfile
├── index.js
├── package.json
└── .github/
    └── workflows/
        └── main.yml


🔐 Secrets Configuration
Add the following secrets to your GitHub repository:

# Secret Name	Description
DOCKER_USERNAME	Your DockerHub username
DOCKER_PASSWORD	Your DockerHub password/token
