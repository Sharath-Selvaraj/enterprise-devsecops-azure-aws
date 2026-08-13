# Enterprise DevSecOps Pipeline using Azure DevOps and AWS

This repository is created to learn and implement an end-to-end DevOps/DevSecOps flow using commonly used industry tools.

The main idea is to understand how code moves from a developer machine to production using automation.

We will start from the basics and slowly add each component step by step.

## What we are going to build

A complete CI/CD workflow where:

Developer writes code

-> Code is stored in GitHub

-> Azure DevOps pipeline will build and validate the code

-> Security scanning will identify vulnerabilities

-> Docker image will be created

-> Image will be stored in AWS ECR

-> Infrastructure will be created using Terraform

-> Application will be deployed on AWS EKS

-> Monitoring will be done using Prometheus and Grafana


## Tools used

### Git and GitHub
For source code management, version control, branching and pull requests.

### Azure DevOps
For creating CI/CD pipelines and automating build and deployment activities.

### Terraform
For creating and managing AWS infrastructure using code.

Terraform state will be stored remotely using AWS S3.

### AWS
Cloud platform used for this project.

Main AWS services:

- IAM
- VPC
- ECR
- EKS
- S3

### Docker
For packaging application and running it as containers.

### Kubernetes (Amazon EKS)
For deploying and managing containerized applications.

### Security Tools

OWASP Dependency Check:
To identify vulnerable application dependencies.

Trivy:
To scan container images and identify security issues.

### Monitoring

Prometheus:
For collecting application and infrastructure metrics.

Grafana:
For creating dashboards and visualization.


## Medium Article Series

I am documenting this complete implementation step by step on Medium.

### Part 0: Environment Setup

Topics covered:

- GitHub account creation
- Git installation
- Git Bash setup
- Visual Studio Code installation
- Git basic configuration

Article:
https://medium.com/@sharath_s3/building-enterprise-devsecops-pipeline-using-azure-devops-and-aws-ef0a3d8d75ca


### Part 1: Source Control using Git and GitHub

Topics covered:

- Source control basics
- SSH authentication with GitHub
- Repository creation
- Git initialization
- Commit workflow
- Push code to GitHub

Article:
https://medium.com/@sharath_s3/building-enterprise-devsecops-pipeline-using-azure-devops-and-aws-0849c814c733


### Part 2: Branching and Pull Requests

Topics covered:

- Creating a feature branch
- Making changes in a separate branch
- Committing and pushing the branch
- Creating a Pull Request
- Code review and approval
- Merging changes into the main branch
- Branch protection workflow

Article:
https://medium.com/@sharath_s3/building-enterprise-devsecops-pipeline-using-azure-devops-and-aws-part-2-branching-and-pull-5eb724b1e764

### Part 3: Azure DevOps Setup and First Pipeline

Topics covered:

- Creating an Azure DevOps project
- Connecting Azure DevOps with GitHub
- Authorizing Azure Pipelines
- Selecting the GitHub repository
- Creating a basic YAML pipeline
- Using a feature branch for pipeline changes
- Pull Request review and approval
- Running the first Azure DevOps pipeline
- Verifying successful pipeline execution

Article:
https://medium.com/@sharath_s3/building-an-enterprise-devsecops-pipeline-using-azure-devops-and-aws-part-3-azure-devops-setup-1b07eb4e062f

### Part 4: Building the Azure DevOps CI Pipeline

Upcoming:
- Building the application using Azure DevOps
- Installing application dependencies
- Running the application build
- Validating the build output

### Part 5: Infrastructure as Code using Terraform on AWS

### Part 6: Docker and AWS ECR

### Part 7: DevSecOps Security Integration

### Part 8: Deploying Application to Amazon EKS

### Part 9: Monitoring using Prometheus and Grafana

### Part 10: Complete Enterprise DevSecOps Pipeline

## Current Status

Project is currently in progress.

Each part will be implemented practically and updated in this repository along with Medium documentation.

The goal is not only to learn individual tools, but to understand how these tools connect together in a real project.