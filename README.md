# AWS VPC + EC2 with Terraform

Provisions a complete AWS network stack using Terraform.

## Resources created
- VPC (10.20.0.0/16)
- Public subnet with internet access
- Internet Gateway
- Route table
- Security group (SSH)
- EC2 instance (Ubuntu 24.04, t3.micro)

## Usage
```bash
terraform init
terraform plan
terraform apply
terraform destroy
```

## Requirements
- AWS CLI configured
- Terraform installed
- Key pair named `muntasir-key` in us-east-1
