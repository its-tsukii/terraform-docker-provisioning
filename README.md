# Terraform Docker Provisioning 🚀

This project demonstrates how to use **Terraform** to provision a local **Docker container** running NGINX.  
It is completed as **Task 3** of the **Elevate Labs DevOps Internship**.

---

## 🔧 Tools Used

- 🏗️ **Terraform** – Infrastructure as Code (IaC)
- 🐳 **Docker** – Containerization platform

---

## 📌 What This Project Does

- Uses Terraform to define infrastructure (an NGINX container)
- Pulls the latest NGINX image from Docker Hub
- Provisions a container named `nginx-server`
- Maps local port **8082** to container port **80**
- Exposes the container on: [http://localhost:8082](http://localhost:8082)

---

## 📁 Folder Structure

```bash
.
├── main.tf               # Terraform configuration
├── .gitignore            # Ignores .terraform, state files, logs
├── execution-log.txt     # Optional: Terminal logs of Terraform commands
├── screenshots/          # Visual outputs for each Terraform step
└── README.md             # You're reading it!
🚀 How to Run This Project
Clone the repo:

bash
Copy
Edit
git clone https://github.com/YOUR_USERNAME/terraform-docker-provisioning.git
cd terraform-docker-provisioning
Initialize Terraform:

bash
Copy
Edit
terraform init
Preview the infrastructure:

bash
Copy
Edit
terraform plan
Apply to provision:

bash
Copy
Edit
terraform apply
Access the app:

Visit → http://localhost:8082

Destroy the infrastructure when done:

bash
Copy
Edit
terraform destroy
📸 Screenshots
🔧 Terraform Init

🔍 Terraform Plan

🚀 Terraform Apply

🐳 Docker Container Running

🌐 NGINX Webpage (localhost:8082)

💣 Terraform Destroy

📚 Concepts Covered
✅ Infrastructure as Code with Terraform

✅ Docker provider usage in Terraform

✅ Managing state with terraform.tfstate

✅ Terraform commands: init, plan, apply, destroy

✅ Clean and repeatable local development environments

🧠 Interview Prep – Core Terraform Questions
What is Infrastructure as Code (IaC)?

How does Terraform work?

What is the Terraform state file?

Difference between terraform plan and apply

What are Terraform providers?

What is resource dependency in Terraform?

How to handle secrets in Terraform?

Benefits of Terraform in DevOps pipelines

👨‍💻 Author
Aayush Kukade
DevOps Intern @ Elevate Labs

yaml
Copy
Edit

---

## ✅ Final Push Command

After replacing your current `README.md` with this version, commit and push everything:

```bash
git add README.md screenshots/
git commit -m "Updated README with embedded screenshots for Task 3"
git push
