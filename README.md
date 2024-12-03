# DevOps Case Study: CI/CD Pipeline for Kubernetes Application

Project Overview

This project demonstrates a CI/CD pipeline for deploying a Node.js application with database integration on Kubernetes. The solution leverages modern DevOps tools and practices to enable seamless deployment, scalability, and configuration management across multiple environments.


Steps Followed

Step 1: Local Setup
Installed Docker and MySQL locally.
Containerized the Node.js application and deployed it locally using Docker.

Step 2: Kubernetes Setup
Installed Minikube to create a local Kubernetes cluster.
Deployed the application and database containers to Kubernetes using Helm charts.

Step 3: ArgoCD Installation
Set up ArgoCD for GitOps-based continuous deployment.
Configured ArgoCD to manage application deployment in the Kubernetes cluster.

Step 4: GitLab Integration and Pipeline
Created a GitLab account and implemented a CI/CD pipeline.

The pipeline automates the following:
Building the application and creating a Docker image.
Pushing the image to a container registry.
Deploying the application to the Kubernetes cluster via ArgoCD.


Additional Implementations
Integrated GitHub and GitLab for seamless collaboration.
Configured automated deployment triggers on Git push events.



Features

-GitOps approach with ArgoCD ensuring Kubernetes state is always aligned with the Git repository.
-Environment-specific configuration using Helm values and External-Secret for managing sensitive information.
-Automated CI/CD process with GitLab pipelines to build, test, and deploy the application.




## Project setup
```
npm install
```

### Run
```
node server.js
```
