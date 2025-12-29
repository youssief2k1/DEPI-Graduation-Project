# flask-mongo-eks-monitoring
A Flask &amp; MongoDB To-Do app demonstrating end-to-end DevOps practices: Docker containerization, AWS EKS provisioning via Terraform, GitHub Actions CI/CD, and Prometheus/Grafana monitoring

## 📖 Project Description
This project involves the end-to-end development, deployment, and monitoring of a Flask-based To-Do List web application. The application features a simple, responsive user interface backed by **MongoDB** for data persistence.

The core mission of this project is to implement modern **DevOps practices**. The application is containerized using **Docker**, and the infrastructure is provisioned on **AWS** (specifically an **EKS cluster**) using **Terraform** as Infrastructure as Code (IaC). A complete **CI/CD pipeline** is built with **GitHub Actions** to automate testing, building, and deploying. To ensure high availability and performance, a robust monitoring stack using **Prometheus** and **Grafana** has been established.

---

## 🛠 Tools & Technologies
The project utilizes the following stack:

* **Backend:** Flask, MongoDB
* **Containerization:** Docker
* **Orchestration:** Kubernetes (AWS EKS)
* **Infrastructure as Code:** Terraform
* **CI/CD:** GitHub Actions
* **Container Registries:** Docker Hub, GitHub Container Registry (GHCR)
* **Monitoring:** Prometheus, Grafana
* **Cloud Provider:** Amazon Web Services (AWS)

---

## 🎯 Objectives
* **Develop:** A fully functional and responsive Flask To-Do list application with a MongoDB backend.
* **Containerize:** Use Docker for consistent and portable deployments.
* **Automate Infrastructure:** Provision a scalable Kubernetes cluster (AWS EKS) using Terraform.
* **CI/CD Implementation:** Automate the workflow from code commit to production using GitHub Actions.
* **Deploy:** Roll out the application to the Kubernetes cluster with load balancing.
* **Monitor:** Establish a comprehensive system using Prometheus and Grafana.

---

## 👥 Group Members & Roles
* **Youssief Abdelghany Mohamed:** DevOps Engineer
* **Mohamed Khaled Mostafa:** DevOps Engineer
* **Yussuf Samir Yussuf:** DevOps Engineer
* **Mohamed Abdelghany Mohamed:** DevOps Engineer

---

## 📅 Milestones
| Phase | Milestone | Key Tasks |
| :--- | :--- | :--- |
| **Phase 1** | Project Kickoff & App Development | Finalize scope, Git setup, initial app development. |
| **Phase 2** | Containerization & IaC | Dockerfile creation, Terraform scripts for AWS EKS. |
| **Phase 3** | CI/CD Pipeline Implementation | GitHub Actions setup for testing, building, and pushing images. |
| **Phase 4** | Deployment & Monitoring | Kubernetes manifests, EKS deployment, Prometheus & Grafana setup. |
| **Phase 5** | Final Testing & Documentation | End-to-end testing, documentation, final presentation. |

---

## 📊 Key Performance Indicators (KPIs)
* **Infrastructure:** Successful provisioning of AWS EKS via Terraform scripts.
* **Pipeline Efficiency:** CI/CD pipeline completes in under 10 minutes with >95% success rate.
* **Code Quality:** Automated tests triggered on every commit.
* **Deployment:** Zero-downtime deployment to AWS EKS.
* **Reliability:** Achieve 99.9% system uptime and visualize metrics via Grafana dashboards.
