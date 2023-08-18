# Project Title

Automated CI/CD Pipeline for Java Application with Jenkins, Maven, SonarQube, Docker, Argo CD and Kubernetes.

## Description

This repository showcases an end-to-end Continuous Integration and Continuous Deployment (CI/CD) pipeline for a Java application. The pipeline automates the entire process, from code checkout to production deployment, leveraging popular DevOps tools such as SonarQube, Argo CD, Helm, and Kubernetes.

## Features

- Code is built, tested, and packaged using Maven.
- Static code analysis is performed using SonarQube.
- Docker image is built, pushed to Docker Hub, and versioned.
- Application is deployed to Kubernetes using Argo CD and Helm charts.
  

## How It Works

1. **Code Checkout**: The pipeline starts with code checkout from the repository.

2. **Build and Test**: The application is built and tested using Maven.

3. **Static Code Analysis**: SonarQube performs detailed static code analysis to ensure code quality.

4. **Docker Image Creation**: Docker image is built with the application and tagged with the version.

5. **Image Push to Docker Hub**: The Docker image is pushed to Docker Hub for centralized image management.

6. **Application Deployment**: Argo CD and Helm charts manage the deployment to Kubernetes.

7. **GitOps Approach**: Changes to the application trigger automated updates on the Kubernetes cluster.

8. **Continuous Monitoring**: Kubernetes ensures high availability and monitoring of deployed applications.


