# S3 Replication & Lifecycle Management

## Project Overview
This project demonstrates configuring Amazon S3 bucket replication and lifecycle policies to manage backups and optimize storage costs.

## Objective
- Enable versioning on S3 buckets.
- Set up cross-region replication for backup.
- Configure lifecycle rules to transition or delete objects automatically.

## Steps
1. Enable **Versioning** on both source and destination S3 buckets.
2. Create a **Replication Rule**:
   - Select source and destination buckets.
   - Choose IAM role for replication.
   - Apply filters if needed (prefixes/tags).
3. Configure **Lifecycle Policies** on the source or destination bucket:
   - Transition objects to cheaper storage (e.g., Glacier).
   - Expire/delete old objects automatically.
4. Upload sample files to verify replication and lifecycle actions.

## Proof
- Screenshot 1: Versioning enabled on source and destination buckets.
- Screenshot 2: Replication rule configuration.
- Screenshot 3: Lifecycle policy applied and working.

## Outcome
Automated replication and storage management in S3, demonstrating cost optimization and backup strategy.