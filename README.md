# 🚀 Murugan's Terraform AWS Project

Easily automate your AWS infrastructure with Terraform!  
This repo helps you spin up EC2 instances, VPCs, and S3 buckets—all with simple commands. Run locally with your own AWS account.

---

## 🛠 Prerequisites

- [Terraform](https://www.terraform.io/downloads) (Install and add to PATH)
- [AWS CLI](https://aws.amazon.com/cli/) (Install and configure with your AWS credentials)

---

## ⚡️ Quick Start Guide

1. **Create an IAM User in AWS**
   - Go to the AWS Console, create a new IAM user with programmatic access.
   - Attach permissions for EC2, S3, VPC, and IAM.

2. **Configure Your AWS CLI**
   - Open your terminal and run:
     ```bash
     aws configure
     ```
   - Enter your AWS Access Key ID, Secret Access Key, AWS region, and output format (e.g., `json`).

   - **Verify your credentials:**
     ```bash
     aws sts get-caller-identity
     ```

3. **Run the Terraform Scripts**

   - Navigate to the Terraform project directory:
     ```bash
     cd terraform
     ```

   - **Initialize Terraform:**
     ```bash
     terraform init
     ```

   - **Preview infrastructure changes:**
     ```bash
     terraform plan
     ```

   - **Deploy resources:**
     ```bash
     terraform apply
     ```

   - **Clean up (destroy resources):**
     ```bash
     terraform destroy
     ```

---

## 💡 Tips

- Review the Terraform files before deployment to understand what resources will be created.
- Remember, AWS charges for resources you create—destroy them when you're done!
- For custom setups, modify the variables in the `terraform` directory.

---

Happy Coding! 🚀  
Feel free to fork, contribute, or raise issues.
