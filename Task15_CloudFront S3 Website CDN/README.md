# CloudFront S3 Website CDN

## Project Overview
This project demonstrates creating a CloudFront distribution to serve an Amazon S3 static website, enabling faster content delivery via a global Content Delivery Network (CDN).

## Objective
- Link CloudFront to an S3 static website.
- Distribute content globally with low latency.
- Understand caching and CDN principles in AWS.

## Steps
1. Upload your static website to an **S3 bucket**.
2. Create a **CloudFront distribution**:
   - Origin: Your S3 bucket.
   - Configure default cache behavior and viewer settings.
3. Wait for distribution deployment (may take several minutes).
4. Access your website using the CloudFront URL.
5. Verify content is delivered via the CDN.

## Proof
- Screenshot 1: CloudFront distribution linked to S3.
- Screenshot 2: Website displayed through CloudFront URL.

## Outcome
Faster, globally distributed static website using CloudFront CDN, demonstrating AWS content delivery optimization.