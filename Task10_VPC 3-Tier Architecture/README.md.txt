# VPC 3-Tier Architecture

## Project Overview
This project demonstrates designing a secure 3-tier network architecture in AWS, including public, private, and database subnets, along with NAT Gateway and Internet Gateway configuration.

## Objective
- Create a VPC with public and private subnets.
- Set up routing, NAT Gateway, and Internet Gateway.
- Enable secure access via SSH tunneling.
- Understand network isolation, NACLs, and subnet-level security.

## Steps
1. Create a **VPC** with CIDR block (e.g., 10.0.0.0/16).
2. Create **public and private subnets** in different AZs.
3. Set up **Internet Gateway** for public subnet and **NAT Gateway** for private subnet outbound traffic.
4. Configure **Route Tables** and associate them with subnets.
5. Configure **Network ACLs (NACLs)** for additional security.
6. Launch EC2 instances in public and private subnets.
7. Use **SSH tunneling** or bastion host to access private instances.

## Proof
- Screenshot 1: VPC and subnet layout.
- Screenshot 2: Route tables, NAT, and IGW setup.
- Screenshot 3: EC2 instances connected through SSH tunneling showing private subnet access.

## Outcome
A fully functional 3-tier VPC architecture in AWS demonstrating secure networking, subnet isolation, and proper routing.