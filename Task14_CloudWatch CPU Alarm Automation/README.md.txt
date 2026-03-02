# CloudWatch CPU Alarm Automation

## Project Overview
This project demonstrates creating an Amazon CloudWatch alarm that monitors EC2 CPU usage and automatically stops the instance when it exceeds a threshold, with email notifications via SNS.

## Objective
- Monitor EC2 CPU utilization using CloudWatch.
- Trigger automated actions (stop instance) when threshold is reached.
- Send notifications via SNS for proactive alerting.

## Steps
1. Create an **SNS Topic** and subscribe an email address.
2. Navigate to **CloudWatch > Alarms** and create a new alarm:
   - Metric: CPU Utilization
   - Threshold: 70%
   - Period: e.g., 5 minutes
3. Configure **Actions** for the alarm:
   - Stop EC2 instance when threshold exceeded.
   - Send notification to SNS topic.
4. Test alarm by simulating high CPU load (e.g., stress command on EC2).
5. Verify that EC2 stops and email notification is received.

## Proof
- Screenshot 1: CloudWatch alarm and configured action.
- Screenshot 2: Email notification received from SNS.

## Outcome
Automated monitoring and response system using CloudWatch and SNS, demonstrating EC2 CPU-based auto-stop with alerting.