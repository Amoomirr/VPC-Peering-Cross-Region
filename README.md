# VPC-Peering-Cross-Region
# 🌐 VPC Peering for Cross Region — AWS Project

This project demonstrates how to configure **cross-region VPC peering** between two Virtual Private Clouds (VPCs) hosted in **Mumbai** and **Seoul** AWS regions. It includes network setup, routing, security group configuration, and EC2 access using Bastion Hosts — all documented in a well-structured LaTeX PDF report.

## 📄 Project Description

The goal of this project was to:
- Establish secure communication between EC2 instances in two different AWS regions.
- Enable SSH and ICMP (ping) traffic across both public and private subnets.
- Follow AWS best practices for networking and security.

Key services used:
- Amazon VPC
- EC2 Instances
- Internet Gateway
- Route Tables
- Security Groups
- Bastion Host
- VPC Peering (Cross-region)

## 🏗️ Architecture Overview

- **Mumbai VPC (ap-south-1)**: `10.0.0.0/16`
- **Seoul VPC (ap-northeast-2)**: `10.1.0.0/16`
- Subnets, Route Tables, and Security Groups were configured individually.
- Bastion Host was used for accessing private EC2s.

## 📁 Files

