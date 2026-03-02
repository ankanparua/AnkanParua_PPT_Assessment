# S3 Upload Email Notification

## Project Overview
This project demonstrates triggering email notifications when a file is uploaded to an S3 bucket using AWS Lambda and SNS, showcasing event-driven architecture in AWS.

## Objective
- Configure an S3 bucket to trigger a Lambda function on file upload.
- Use SNS to send email notifications automatically.
- Learn serverless event handling and notifications.

## Steps
1. Create an **S3 bucket** for file uploads.
2. Create an **SNS Topic** and subscribe an email address.
3. Create a **Lambda function** in Python to send SNS notifications on S3 events.
4. Add S3 **Event Notification** to trigger Lambda on `PUT` operations.
5. Upload a test file to the S3 bucket and check email notifications.

## Proof
- Screenshot 1: S3 bucket and uploaded file.
- Screenshot 2: Lambda function configuration.
- Screenshot 3: Email received via SNS confirming upload.

## Outcome
Automatic email notification triggered on S3 file upload, demonstrating AWS event-driven architecture using Lambda and SNS.