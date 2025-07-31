# FortStack DevOps Task

## 🚀 Overview
This project is a **Todo List Node.js web app** that is containerized, deployed with Docker and Kubernetes, and uses CI/CD via **GitHub Actions** and **ArgoCD**.

---

## 📄 Initial Setup and Assumptions

### MongoDB Atlas Setup:
- Created an account on **MongoDB Atlas**.
- Created a **free cluster**.
- Added my **IP address** to the access list.
- Created a **database user** with proper permissions.
- Obtained a **connection URI** and used it in the `.env` file.

### DockerHub Setup:
- Created a **DockerHub account**.
- Created a repository named **fortstack**.
- Generated **DockerHub credentials** and added them to **GitHub Secrets**.

### GitHub Setup:
- Created a **GitHub repository** for the project.
- Pushed all **application code**, `Dockerfile`, **GitHub Actions workflow**, and **Kubernetes manifests**.

### Kind Kubernetes Cluster:
- Used **Kind** to create a local Kubernetes cluster.
- Verified cluster with `kubectl get nodes` and `kubectl cluster-info`.

### ArgoCD Installation:
- Installed **ArgoCD** in the Kind cluster.
- Accessed ArgoCD dashboard via **port-forwarding**.

### VM Configuration using Ansible:
- Created a **Linux VM** (locally or on cloud).
- Used **Ansible** to install Docker on the VM.

---

## ✅ Part 1: Clone and Setup Project

### Clone Repo:
```bash
git clone https://github.com/Ankit6098/Todo-List-nodejs.git
