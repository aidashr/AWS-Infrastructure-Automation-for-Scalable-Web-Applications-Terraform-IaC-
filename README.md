# AWS Infrastructure Automation for Scalable Web Applications

This project demonstrates how to design, provision, and manage a scalable and secure AWS web application infrastructure using **Terraform** and **Infrastructure as Code (IaC)** principles. The entire cloud environment is deployed automatically, ensuring repeatability, consistency, and version control.

---

## 🚀 Project Overview

The goal of this project is to eliminate manual cloud setup by defining a production-ready AWS architecture entirely in Terraform. The infrastructure supports a typical web application deployment with proper networking, security, and scalability considerations.

---

## 🏗️ Architecture Components

The Terraform configuration provisions the following AWS resources:

- **VPC** with public and private subnets  
- **Internet Gateway** and routing configuration  
- **Security Groups** with controlled inbound/outbound rules  
- **EC2 Instances** for application hosting  
- **Load Balancer** to distribute traffic  
- **IAM Roles and Policies** for secure resource access  

All resources are modularized to promote reuse and maintainability.

---

## 🛠️ Technologies Used

- **Terraform** (Infrastructure as Code)
- **Amazon Web Services (AWS)**
  - EC2
  - VPC
  - Security Groups
  - IAM
  - Load Balancing
- **Git** for version control

---

## 📈 Key Features

- Fully automated infrastructure provisioning (zero manual setup)
- Modular and reusable Terraform code
- Secure networking with isolated private subnets
- Scalable architecture suitable for production workloads
- Consistent deployments through version-controlled IaC

---

## ▶️ How to Deploy

### Prerequisites
- AWS account
- Terraform installed
- AWS credentials configured (`aws configure`)

### Deployment Steps
```bash
terraform init
terraform plan
terraform apply
