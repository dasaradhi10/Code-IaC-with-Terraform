# Task: Infrastructure as Code (IaC) with Terraform

## 🎯 Objective
Provision a local Docker container using Terraform.

## 🛠️ Tools Used
- Terraform
- Docker

## 📁 Files
- `main.tf` – Terraform configuration to create an Nginx container

## ⚙️ Steps Performed
1. Installed Terraform and Docker
2. Created `main.tf` with Docker provider and resources
3. Ran `terraform init` to initialize the project
4. Used `terraform plan` to preview changes
5. Applied the configuration using `terraform apply`
6. Verified the container by visiting `http://localhost:8080`
7. Checked resources with `terraform state list`
8. Destroyed the container using `terraform destroy`

## ✅ Outcome
Successfully provisioned and managed Docker containers using Terraform IaC.
