
# DevOps Task 3 - Infrastructure as Code (IaC) with Terraform

This task demonstrates how to provision a Docker container using **Terraform** as an Infrastructure as Code (IaC) tool.

## 🔧 Tools Used
- Terraform
- Docker
- Docker Provider for Terraform

## 📁 Files
- `main.tf` — Main Terraform configuration
- `README.md` — Task instructions and setup

## 🚀 What This Setup Does
1. Downloads the latest `nginx` image.
2. Creates a container named `terraform-nginx`.
3. Maps port `8082` on your host to port `80` inside the container.

## ✅ How to Run

```bash
terraform init
terraform plan
terraform apply
```

Then visit:
> http://localhost:8082

To stop and delete everything:

```bash
terraform destroy
```

## 🙋‍♀️ Author
**Polanki Sravya**
