# AWS Highly Available Web Application Architecture

## 📌 Project Overview

This project demonstrates the design of a highly available, scalable, and secure web application architecture on Amazon Web Services (AWS).

The architecture follows AWS best practices for:

- High availability
- Scalability
- Security
- Fault tolerance
- Performance
- Monitoring
- Cost optimization

## 🏗️ Architecture

The proposed architecture uses the following AWS services:

- Amazon Route 53
- Amazon CloudFront
- Application Load Balancer (ALB)
- Amazon VPC
- Amazon EC2
- Amazon RDS
- AWS IAM
- Amazon CloudWatch

### High-Level Request Flow

```text
User
  │
  ▼
Route 53
  │
  ▼
CloudFront
  │
  ▼
Application Load Balancer
  │
  ├───────────────┐
  ▼               ▼
EC2 - AZ1       EC2 - AZ2
  │               │
  └───────┬───────┘
          ▼
       Amazon RDS
