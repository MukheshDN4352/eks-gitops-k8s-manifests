# Kubernetes Manifests (EKS GitOps)

This repository contains Kubernetes YAML manifests used to deploy and manage a containerized application on **AWS EKS** using **GitOps principles**.

The manifests are designed to be consumed by **ArgoCD** for automated, secure, and reliable Kubernetes deployments.

---

## 📌 Overview

- Defines Kubernetes resources required for application deployment
- Supports GitOps-based continuous delivery
- Used as a separate infrastructure repository, decoupled from application code
- Designed for production-ready EKS environments

---

## 🧱 Kubernetes Resources Included

- **Deployments** – Application pod definitions
- **Services** – Internal and external service exposure
- **Ingress** – HTTP routing and path-based access
- **ConfigMaps** – Application configuration
- **Secrets** – Sensitive configuration (base64 encoded)
- **Namespaces** – Logical environment isolation

---

## 🔄 GitOps Workflow

1. Application or configuration changes are pushed to this repository
2. **ArgoCD** continuously monitors the repo
3. Changes are automatically synchronized to the **EKS cluster**
4. Ensures declarative, version-controlled deployments

---

## ☁️ Platform & Tools

- **Kubernetes**
- **AWS EKS**
- **ArgoCD**
- **Docker**
- **GitHub**

---

## 📂 Repository Structure (Example)

