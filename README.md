# Infrastructure as Code with Terraform on AWS

## Overview
Provisioned complete AWS infrastructure using Terraform, managing EC2 instances, S3 buckets, and security groups as code.

## Architecture
Terraform Config → AWS Provider → EC2 + S3 + Security Groups

## Tools Used
- Terraform
- AWS (EC2, S3, IAM)
- Ubuntu (Linux)
- Git & GitHub

## Resources Provisioned
| Resource | Description |
|----------|-------------|
| EC2 Instance | Virtual server for application hosting |
| S3 Bucket | Remote storage for Terraform state |
| Security Groups | Firewall rules for secure access |
| Key Pairs | SSH access to EC2 instance |

## Key Highlights
- Modular Terraform configuration with variables and outputs
- Remote state stored in S3 for consistency
- Used terraform plan before every apply for safe changes
- Reusable configuration for multiple environments

## What I Learned
- Writing Terraform configuration files
- Provisioning AWS resources as code
- Managing Terraform state remotely in S3
- Using variables and outputs for reusable infrastructure
