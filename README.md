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


## Learning Plan

Part 1:
Git and GitHub basics

Part 2:
Creating CI/CD pipeline using Azure DevOps

Part 3:
Infrastructure automation using Terraform

Part 4:
Docker and container registry

Part 5:
Adding security checks into pipeline

Part 6:
Deploying application into Kubernetes

Part 7:
Monitoring using Prometheus and Grafana


The goal is not only to learn individual tools, but to understand how these tools connect together in a real project.