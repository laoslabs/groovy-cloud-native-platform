# GROOVY ☁️

### AWS EKS-Based Cloud-Native Platform

Cloud-native infrastructure designed and implemented for a microservice-based study platform using AWS, Kubernetes, Terraform, Argo CD, and a full observability stack.

---

## 🚀 Key Results

- 📉 Reduced AWS infrastructure cost by approximately **35%**
- ⚡ Validated scalability with **1,000 VUs / approximately 300 RPS**
- 🔄 Implemented GitOps-based deployment using **GitHub Actions + Argo CD**
- 📈 Implemented Kubernetes HPA-based autoscaling
- 🔭 Built an observability stack with **Prometheus, Grafana, Loki, Tempo, and Alloy**
- 🏗 Provisioned AWS infrastructure using **Terraform**

---

## 👤 My Role

**Cloud Infrastructure / DevOps Engineer**

I was primarily responsible for:

- AWS infrastructure architecture and deployment
- Amazon EKS deployment and operation
- Terraform-based Infrastructure as Code
- Kubernetes resource configuration
- GitHub Actions and Argo CD CI/CD
- Horizontal Pod Autoscaling
- Monitoring and observability
- Load testing and scalability validation
- AWS infrastructure cost optimization

---

## 📌 Project Overview

GROOVY is a cloud-native study platform composed of multiple microservices.

### Microservices

- Identity
- Study
- Content
- Calendar
- Notification

The infrastructure evolved from a Docker Compose-based deployment environment to Kubernetes running on Amazon EKS.

```text
Docker Compose
      ↓
Kubernetes
      ↓
Amazon EKS
      ↓
GitOps + Autoscaling + Observability
