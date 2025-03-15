# 2048 Game Deployment on AWS

EKS Cluster with Fargate for Scalable Deployment

Tools: AWS (EKS, EC2, Fargate, IAM, ALB), Kubernetes, Helm, AWS CLI, Kubectl, Eksctl.

1.  Set up an EC2 instance and configured AWS CLI, Kubectl, and Eksctl for EKS cluster management.
2.  Created an EKS cluster with Fargate to enable serverless Kubernetes-based deployment.
3.  Configured kubeconfig to interact with the EKS cluster for application deployment.
4.  Configured Ingress to manage external traffic and deployed an AWS Application Load Balancer (ALB) for public access.
5.  Installed Helm for package management and streamlined application deployment.
6.   Made the game accessible via the Load Balancer DNS, ensuring scalability and availability.
