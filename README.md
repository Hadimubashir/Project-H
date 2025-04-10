# 🎮 2048 Game Deployment on AWS (EKS with Fargate)

Deployed the classic **2048 Game** on a serverless Kubernetes environment using **Amazon EKS with Fargate**, ensuring high availability, scalability, and ease of management.

## 🛠️ Tools & Technologies
- AWS EKS (Elastic Kubernetes Service)
- AWS Fargate (Serverless compute for containers)
- EC2 (for initial CLI setup)
- IAM, ALB (Application Load Balancer)
- Kubernetes, Helm
- AWS CLI, Kubectl, Eksctl

## ⚙️ Architecture Overview

- **Infrastructure Setup**:
  - Launched an **EC2 instance** for CLI and Kubernetes tool setup.
  - Installed and configured **AWS CLI**, **kubectl**, and **eksctl** to manage EKS resources.

- **EKS Cluster Configuration**:
  - Created an **Amazon EKS cluster** with **Fargate profiles** for serverless deployment.
  - Updated and verified `kubeconfig` to interact with the EKS cluster.

- **Application Deployment**:
  - Installed **Helm** to manage Kubernetes packages.
  - Deployed the 2048 game using a Helm chart or Kubernetes manifests.

- **Ingress and Load Balancer**:
  - Configured **Kubernetes Ingress** to handle external traffic.
  - Integrated **AWS Application Load Balancer (ALB)** via AWS Load Balancer Controller.
  - Exposed the game publicly using the **ALB DNS name**.

## 🌐 Live Access
- Access the game via the **Load Balancer DNS** provided by AWS.

## 🚀 Outcome
- Fully functional and scalable **2048 Game** hosted on **AWS EKS with Fargate**
- Zero server maintenance using **serverless containers**
- Clean and efficient **CI/CD-ready Kubernetes setup**

---

> This project showcases your understanding of Kubernetes, AWS container services, Helm, and production-grade application deployment.
