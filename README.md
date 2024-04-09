# How do we manage k8s applications deployed in multiple k8s clusters using argoCD & Helm?

GitOps is a way of implementing Continuous Deployment for cloud-native applications. It focuses on a developer-centric experience when operating infrastructure using tools developers are already familiar with, including Git and Continuous Deployment tools.

The core idea of GitOps is to have a Git repository that always contains declarative descriptions of the infrastructure currently desired in the production environment and an automated process to make the production environment match the described state in the repository. If you want to deploy a new or existing application, you only need to update the repository - the automated process handles everything else. It's like having cruise control for managing your applications in production.

![1](https://github.com/Dhruvin4530/argoCD-Helm/blob/main/1.png)

For a detailed overview click [here](https://medium.com/@dksoni4530/how-do-we-manage-k8s-applications-deployed-in-multiple-k8s-clusters-using-argocd-helm-d1de7b1d36e6). 
