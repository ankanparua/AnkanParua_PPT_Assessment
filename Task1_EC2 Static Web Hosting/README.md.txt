# EC2 Static Web Hosting

## Project Overview
This project demonstrates deploying a basic static website on an AWS EC2 Ubuntu instance using Nginx. It covers EC2 setup, SSH access, and web server deployment.

## Objective
- Launch an Ubuntu EC2 instance.
- Install and configure Nginx.
- Host a static HTML website accessible via the public IP.

## Steps
1. Launch an Ubuntu EC2 instance on AWS.
2. Connect via SSH:
   ```bash
   ssh -i <key-pair.pem> ubuntu@<EC2-public-IP>