# terraform_lab
Terraform Lab

# Client Installs

NIX:
curl -fsSL https://apt.releases.hashicorp.com/gpg | sudo apt-key add -
sudo apt-add-repository "deb [arch=$(dpkg --print-architecture)] https://apt.releases.hashicorp.com $(lsb_release -cs) main"
sudo apt install terraform

# Web
https://www.terraform.io/

Note: 
Using AWS in these examples, but Terraform works with all cloud providers.

# Creating User/Service Accounts

Notes:
Should create a unique account for Terraform 

# Go to the IAM Service in AWS
  \_https://console.aws.amazon.com/iam/home?region=us-east-2#

Username: $username
Access type: Programmatic access

# Attach an existing policy
  \_ AdministratorAccess
