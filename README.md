# online-food-ordering-devops
A DevOps project demonstrating deployment of an Online Food Ordering Application using AWS EC2, Jenkins, Docker, AWS ECR, Kubernetes (EKS), Prometheus, and Grafana with CI/CD automation.
# Online Food Ordering Application - DevOps Project

## Project Overview

This project demonstrates the implementation of DevOps practices for deploying an Online Food Ordering Application using AWS cloud services and modern DevOps tools.

The application was containerized using Docker, deployed through Jenkins CI/CD pipelines, stored in AWS Elastic Container Registry (ECR), and integrated with Kubernetes (EKS) for container orchestration. Monitoring was implemented using Prometheus and Grafana.

## Technologies Used

* AWS EC2
* AWS ECR
* AWS EKS
* Jenkins
* Docker
* Kubernetes
* Git & GitHub
* Prometheus
* Grafana
* Linux (Ubuntu)

## Project Workflow

GitHub → Jenkins → Docker → AWS ECR → Amazon EKS → Prometheus → Grafana

## Implementation Steps

### 1. AWS Infrastructure Setup

* Created Ubuntu EC2 instance
* Configured security groups
* Connected using EC2 Instance Connect

### 2. Jenkins Setup

* Installed Java 21
* Deployed Jenkins using Jenkins WAR file
* Configured Jenkins dashboard

### 3. Docker Containerization

* Built Docker image for FoodAppZomato
* Executed application container
* Verified application accessibility

### 4. AWS ECR Integration

* Created ECR repository
* Configured AWS CLI
* Pushed Docker images to ECR

### 5. Kubernetes Deployment

* Created Amazon EKS cluster
* Configured kubectl access
* Created Deployment and Service manifests

### 6. Monitoring

* Installed Prometheus
* Installed Grafana
* Configured dashboards and monitoring

## Key Features

* Continuous Integration & Continuous Deployment
* Docker Containerization
* Cloud Deployment using AWS
* Kubernetes Orchestration
* Real-time Monitoring
* Infrastructure Automation

## Learning Outcomes

* AWS Cloud Services
* Jenkins Administration
* Docker Containerization
* Kubernetes Fundamentals
* CI/CD Pipeline Design
* Monitoring and Observability
* DevOps Best Practices

## Author

Saranya Manne

DevOps | AWS | Docker | Kubernetes | Jenkins | CI/CD
