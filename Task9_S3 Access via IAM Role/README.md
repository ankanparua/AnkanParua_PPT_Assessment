    # S3 Access via IAM Role

## Project Overview
This project demonstrates securely accessing an Amazon S3 bucket from an Ubuntu EC2 instance using IAM roles, eliminating the need for access keys.

## Objective
- Attach an IAM role with proper S3 permissions to an EC2 instance.
- Access and manage S3 objects securely from Ubuntu.
- Understand role-based access management in AWS.

## Steps
1. Create an **IAM Role** with S3 access permissions.
2. Attach the IAM role to the target EC2 instance.
3. SSH into the EC2 instance and test access:
   ```bash
   aws s3 ls s3://<bucket-name>/
   aws s3 cp testfile.txt s3://<bucket-name>/


Command History:    
    1  sudo apt update
    2  sudo apt install awscli -y
    3  sudo apt install awscli
    4  sudo apt update
    5  sudo apt install awscli
    6  sudoapt install unzip
    7  sudo apt install unzip
    8  sudo apt install awscli -y
    9  curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
   10  unzip awscliv2.zip
   11  sudo ./aws/install
   12  aws --version
   13  aws s3 ls
   14  aws s3 ls s3://task9-bucket-hit
   15  aws s3 cb s3://task9-bucket-hit
   16  aws s3 ls s3://task9-bucket-hit