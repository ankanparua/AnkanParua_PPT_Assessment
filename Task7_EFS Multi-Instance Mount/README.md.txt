# EFS Multi-Instance Mount

## Project Overview
This project demonstrates creating an Amazon Elastic File System (EFS) and connecting it to multiple Ubuntu EC2 instances, providing shared storage for scalable applications.

## Objective
- Create an EFS file system.
- Mount the EFS on multiple Ubuntu EC2 instances.
- Enable shared access for data across instances.

## Steps
1. Create an **EFS** in the desired VPC and configure security groups for NFS access.
2. On each EC2 Ubuntu instance, install NFS client:
   ```bash
   sudo apt update
   sudo apt install nfs-common -y
3. Create a mount point and mount the EFS:

	sudo mkdir /mnt/efs
	sudo mount -t nfs4 <EFS-DNS>:/ /mnt/efs