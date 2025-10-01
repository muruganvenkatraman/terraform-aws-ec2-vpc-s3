# Murugan's Terraform AWS Project

This repository contains a Terraform project for automating AWS infrastructure deployment (EC2, VPC, S3). You can run it locally using your own AWS account.

---

## Prerequisites

- [Terraform](https://www.terraform.io/downloads)  
- [AWS CLI](https://aws.amazon.com/cli/)

---

## Quick Setup & Usage

1. **Create an IAM user** in AWS with programmatic access and required permissions (EC2, S3, VPC, IAM).  

2. **Configure AWS CLI**:

```bash
aws configure
# Enter your AWS Access Key ID
# Enter your AWS Secret Access Key
# Enter your AWS region
# Enter default output format (e.g., json)


Verify credentials
aws sts get-caller-identity

Navigate to Terraform project:
cd terraform

Initialize Terraform:
terraform init

Preview the infrastructure changes:
terraform plan

Apply Terraform configuration:
terraform apply

Destroy resources when done:
terraform destroy

