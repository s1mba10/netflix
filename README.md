
# DevSecOps Netflix Clone Project

This repository contains the source code and configuration files for a DevSecOps project that deploys a clone of the Netflix website. The project incorporates various DevSecOps practices and tools to ensure the security and reliability of the deployed application. The primary technologies used in this project are Docker, Kubernetes, ArgoCD, Helm, SonarQube, Trivy, Jenkins, AWS EKS, and AWS EC2. Below, you'll find an overview of the project and instructions for setting up and using it.

[![Click to see more](https://youtu.be/FWR2DMSMY2A)
![ezgif com-video-to-gif](https://github.com/s1mba10/netflix/assets/101098236/c0640755-a073-4121-b3e5-ba473f43e7aa)

## Table of Contents
## Table of Contents
- [Project Overview](#project-overview)
- [Prerequisites](#prerequisites)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)

## Project Overview

The DevSecOps Netflix Clone project aims to create a replica of the Netflix website and demonstrate DevSecOps principles by incorporating security checks, automation, and monitoring into the deployment process. Key components of the project include:

1. **Netflix Clone Website**: The main application, a clone of the Netflix website.

2. **Jenkins Pipeline**: Automation of the deployment process using Jenkins, enabling continuous integration and continuous deployment (CI/CD).

3. **SonarQube**: Integration of SonarQube for static code analysis to identify and address vulnerabilities in the application code.

4. **Prometheus and Grafana**: Monitoring infrastructure components, Jenkins, and the application itself.

5. **Docker and Kubernetes**: Containerization of the application and management of containers in a Kubernetes cluster (AWS EKS).

6. **ArgoCD**: GitOps tool for declarative, automated deployment and management of Kubernetes resources.

7. **Trivy**: Scanning Docker images for vulnerabilities to enhance container security.

8. **AWS EC2**: Used for hosting various components and infrastructure.

## Prerequisites

Before you can get started with this project, you'll need the following prerequisites:

- AWS Account: To deploy resources on AWS, including EKS and EC2 instances.
- Docker: For building and running containers.
- kubectl: The Kubernetes command-line tool for interacting with your EKS cluster.
- Helm: The package manager for Kubernetes.
- ArgoCD: Installed and configured for GitOps.
- Jenkins: Installed and configured with appropriate plugins.
- SonarQube: Configured and integrated with the Jenkins pipeline.
- Prometheus and Grafana: Installed and configured for monitoring.
- Trivy: Installed for vulnerability scanning.

## Installation and Setup

To set up and deploy the Netflix Clone project, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/DevSecOps-Netflix-Clone.git
   cd DevSecOps-Netflix-Clone
   ```

2. Set up your AWS infrastructure, including EKS and EC2 instances.

3. Build and push Docker images for the Netflix Clone and any other necessary components.

4. Configure Jenkins with your project's settings, including your AWS and Docker credentials.

5. Set up SonarQube, Prometheus, and Grafana, and configure them to work with Jenkins.

6. Create a Kubernetes cluster using AWS EKS.

7. Install ArgoCD and configure it to work with your Git repository.

8. Deploy the project using ArgoCD and monitor the deployment in Jenkins and Grafana.

## Usage

Once the project is set up and deployed, you can access the Netflix Clone website and monitor the deployment and infrastructure using Prometheus and Grafana. The Jenkins pipeline will automate the deployment process, and SonarQube will perform static code analysis to enhance the security of the application.
