# EC2 Auto Scaling with ELB

## Project Overview
This project demonstrates setting up an Auto Scaling Group (ASG) in EC2 and attaching it to an Elastic Load Balancer (ELB) to achieve high availability and automatic scaling.

## Objective
- Create a Launch Template for EC2 instances.
- Configure an Auto Scaling Group.
- Attach the ASG to an Elastic Load Balancer for traffic distribution.

## Steps
1. Create a Launch Template with the desired EC2 configuration (AMI, instance type, security groups).
2. Create an Auto Scaling Group using the Launch Template:
   - Specify minimum, maximum, and desired instance counts.
3. Create an ELB (Application or Classic) and attach the ASG to it.
4. Verify traffic distribution across multiple instances:
   - Access the ELB DNS in a browser or via curl.
5. Monitor scaling events in the AWS Console.

## Proof
- Screenshot 1: Launch Template and ASG configuration.
- Screenshot 2: ELB setup and attached instances.
- Screenshot 3: Website/instance access showing load balancing and scaling.

## Outcome
Automatic scaling and load balancing achieved using ASG and ELB, demonstrating high availability for web applications.