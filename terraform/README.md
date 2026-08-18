# Terraform Infrastructure

This directory contains the Infrastructure as Code (IaC) implementation of the AWS highly available web application architecture.

## Planned AWS Resources

The Terraform configuration will provision:

- Amazon VPC
- Public and private subnets
- Internet Gateway
- NAT Gateway
- Route tables
- Security groups
- Application Load Balancer
- EC2 instances / Auto Scaling
- Amazon RDS

## Architecture Goals

The Terraform configuration is designed to demonstrate:

- Multi-AZ deployment
- Network segmentation
- Security best practices
- Infrastructure as Code
- Reusable Terraform configuration
- High availability
- Scalability

## Terraform Structure

```text
terraform/
├── main.tf
├── variables.tf
├── outputs.tf
└── README.md
