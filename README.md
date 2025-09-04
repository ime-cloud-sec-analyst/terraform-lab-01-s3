# terraform-lab-01-s3
Terraform Lab 1 — Create S3 bucket with versioning (AWS)

Terraform Lab 01 — Create an AWS S3 Bucket with Versioning
📌 Lab Overview
This lab demonstrates how to provision an Amazon S3 bucket with versioning enabled using Terraform. The goal is to show how Infrastructure as Code (IaC) can automate cloud resource creation, configuration, and management.
🎯 Objectives
• Configure AWS CLI and Terraform on a local machine.
• Create a Terraform project with a main.tf configuration.
• Provision an S3 bucket with globally unique naming.
• Enable bucket versioning to maintain multiple versions of stored objects.
• Verify the deployment on the AWS Management Console.
• Push all project files and documentation to GitHub with screenshots.
🛠️ Tools & Technologies
• AWS CLI (configured with IAM user credentials)
• Terraform v1.13.1
• AWS S3 (storage service)
• Visual Studio Code (VS Code)
• GitHub (for version control & portfolio)
🔑 Prerequisites
• An AWS account with IAM user access (terraform-user) and programmatic access enabled.
• AWS CLI installed and configured (aws configure).
• Terraform installed and available in your system path.
• Git installed for version control.
📝 Lab Procedure
Step 1 — Configure AWS CLI
Run aws configure, aws sts get-caller-identity, and terraform -version.
Step 2 — Initialize Project Directory
Clone the repository from GitHub and open it in VS Code.
Step 3 — Write Terraform Code
Create a file main.tf with configuration for S3 bucket and versioning.
Step 4 — Initialize Terraform
Run terraform init to install providers.
Step 5 — Validate Configuration
Run terraform validate.
Step 6 — Apply the Configuration
Run terraform apply and confirm with yes.
Step 7 — Verify in AWS Console
Check S3 bucket and versioning in AWS Console.
Step 8 — Push Lab to GitHub
Commit and push files and screenshots to GitHub.
✅ Lab Results
• Successfully provisioned an S3 bucket in eu-west-1.
• Versioning enabled for object storage.
• Terraform state (terraform.tfstate) created to track resources.
• Project files and screenshots documented on GitHub.
📚 Lessons Learned
• Terraform init/plan/apply workflow is the standard approach for IaC.
• Always use globally unique names for S3 buckets.
• GitHub documentation with screenshots strengthens portfolio credibility.
• PAT (Personal Access Token) authentication is required instead of username/password for Git pushes.
🚀 Next Steps
• Extend the lab to enable server-side encryption for the bucket.
• Add lifecycle rules (e.g., transition old objects to Glacier).
• Configure logging and bucket policies for security.
📂 Repository Structure
terraform-lab-01-s3/
│── main.tf              # Terraform configuration
│── terraform.tfstate    # Terraform state file
│── README.md            # Lab documentation
│── images/              # Screenshots
🏆 Summary
This lab proved that Infrastructure as Code with Terraform provides a repeatable, automated, and scalable way to deploy AWS resources. By combining Terraform + GitHub documentation, this project is production-ready and serves as an excellent addition to a Cloud Security/DevOps Engineer portfolio.
👤 Author Details
**Name:** Ime Ben
**Role:** Cloud Security Engineer | DevOps Practitioner
**GitHub:** https://github.com/ime-cloud-sec-analyst
**Email:** imegcu55@gmail.com
**LinkedIn:** https://www.linkedin.com/in/imeben
