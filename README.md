# AWS Terraform Ansible Git GitHub - Self EC2 Deployment Project

## Project Overview
This project demonstrates how to provision an AWS EC2 instance using Terraform and manage the project with Git and GitHub.

## Technologies Used
- AWS EC2
- Terraform
- Git
- GitHub
- Ubuntu Linux

## Project Structure
```
terraform/
├── provider.tf
├── main.tf
├── variables.tf
├── output.tf
├── terraform.tfvars
└── .gitignore
```

## Workflow
1. Configure AWS CLI
2. Create Terraform files
3. Run `terraform init`
4. Run `terraform validate`
5. Run `terraform plan`
6. Run `terraform apply`
7. View outputs using `terraform output`
8. Push the project to GitHub

## Outputs
- EC2 Instance ID
- Public IP Address

## Commands Used
```bash
aws configure
terraform init
terraform validate
terraform plan
terraform apply
terraform output

git init
git add .
git commit -m "Self AWS Terraform Ansible Project"
git push -u origin master
```

## Learning Outcome
- AWS CLI Configuration
- Infrastructure as Code (Terraform)
- EC2 Provisioning
- Git & GitHub Version Control
- Basic DevOps Workflow
