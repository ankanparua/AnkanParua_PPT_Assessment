# Cross-AZ EBS Volume Attachment

## Project Overview
This project demonstrates creating an Amazon EBS snapshot and attaching the restored volume to an EC2 instance in a different Availability Zone (AZ). It helps understand EBS snapshot functionality and cross-AZ storage handling.

## Objective
- Create an EBS snapshot of an existing volume.
- Restore the snapshot in another AZ.
- Attach the restored volume to a target EC2 instance.

## Steps
1. Create a snapshot of the source EBS volume via AWS Console or CLI.
2. Restore a new volume from the snapshot in the target Availability Zone.
3. Attach the new volume to the EC2 instance in the target AZ.
4. Mount the volume on the instance (Linux example):
   ```bash
   sudo mkdir /mnt/newvolume
   sudo mount /dev/xvdf /mnt/newvolume