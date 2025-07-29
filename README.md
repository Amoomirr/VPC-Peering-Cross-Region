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

🗺️ Mumbai VPC Configuration
<img width="1877" alt="Mumbaivpc" src="https://github.com/user-attachments/assets/aeec44e1-58c1-4d3a-9332-e64b41c604f9" />
🗺️ Seoul VPC Configuration
<img width="1865" alt="SeoulVPC" src="https://github.com/user-attachments/assets/0af0e52a-3156-4b7e-a9e4-f8dc1d3d862d" />
🔁 VPC Peering Overview Architecture
<img width="1621" alt="VPCPeering" src="https://github.com/user-attachments/assets/47464821-944f-4e83-bf66-044d410dd85d" />
🔁 VPC Peering Request Initiated (Mumbai)
<img width="1613" alt="VPCpeeringMumbai" src="https://github.com/user-attachments/assets/7200cc47-1b40-41cd-8a45-6b11c1b4ed80" />
🔐 Security Group Rules – Seoul
<img width="1555" alt="SeoulSG" src="https://github.com/user-attachments/assets/d06e455c-e6cd-4155-bf55-21846761ef09" />
🔐 Security Group Rules – Mumbai
<img width="1587" alt="MumbaiSG" src="https://github.com/user-attachments/assets/c86fd626-5b46-40eb-9371-250cb24505cc" />
🧭 Route Table – Mumbai Region
<img width="1627" alt="MumbaiRouteTable" src="https://github.com/user-attachments/assets/87a83bcd-1bd1-479c-9856-44920c16949e" />
🧭 Route Table – Seoul Region
<img width="1565" alt="SeoulRoute" src="https://github.com/user-attachments/assets/8a3a07eb-3cbb-4ecf-8268-0e4c3bb4a718" />
💻 EC2 Dashboard – Mumbai
<img width="1526" alt="MumbaiEC2Dashboard" src="https://github.com/user-attachments/assets/aa07a1cb-7492-4d06-9a1d-9487100894c1" />
💻 EC2 Dashboard – Seoul
<img width="1413" alt="SeoulEC2Dashboard" src="https://github.com/user-attachments/assets/0991814d-4957-45ad-b27f-a257db6a9fc8" />
🔐 SSH Access from Mumbai EC2
<img width="1902" alt="MumbaiEC2SSH" src="https://github.com/user-attachments/assets/5c8ddc07-855e-42ad-a089-19bb65c09685" />
🔐 Bastion Host Access – Mumbai
<img width="805" alt="BastionHostMumbai" src="https://github.com/user-attachments/assets/91428773-4da4-44c9-b9d5-2566f9c66915" />
🔄 SSH from Mumbai Public EC2 to Mumbai Private EC2
<img width="1516" alt="MumbaiPriavteEC2-SSH-From-MumbaiPublicEC2" src="https://github.com/user-attachments/assets/fb92ca45-4f71-441a-86c4-44ad31c496e0" />
🌐 Cross-Region SSH: Seoul Private EC2 from Mumbai Private EC2
<img width="853" alt="SeoulPrivateEC2-SSH-From-MumbaiPrivateEC2" src="https://github.com/user-attachments/assets/266e030e-577c-4d8c-9fdf-aa1e5aa2723e" />






