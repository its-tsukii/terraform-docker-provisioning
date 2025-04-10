# Terraform Docker Provisioning 🚀

This project provisions a local Docker container using **Terraform**, as part of **Task 3** for the Elevate Labs DevOps Internship.

## 🔧 Tools Used

- **Terraform** (Infrastructure as Code)
- **Docker** (Container platform)

## 📄 What It Does

- Pulls the latest `nginx` image
- Creates a Docker container named `nginx-server`
- Maps it to your local machine at [http://localhost:8082](http://localhost:8082)

## 📁 Project Files

- `main.tf` – Terraform configuration file
- `.gitignore` – To keep the repo clean

## 🚀 How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/terraform-docker-provisioning.git
   cd terraform-docker-provisioning
