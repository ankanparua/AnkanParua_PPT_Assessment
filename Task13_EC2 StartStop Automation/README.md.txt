# EC2 Start/Stop Automation

## Project Overview
This project demonstrates automating EC2 instance start and stop operations using AWS Lambda and API Gateway, enabling serverless control over cloud resources.

## Objective
- Create a Lambda function to start or stop EC2 instances.
- Expose the Lambda function via API Gateway as an HTTP endpoint.
- Learn serverless automation and API-triggered workflows.

## Steps
1. Create a **Lambda function** with Python or Node.js to start/stop EC2 instances using `boto3`.
2. Configure **IAM Role** for Lambda with EC2 permissions.
3. Create an **API Gateway** endpoint to trigger the Lambda function via HTTP requests.
4. Test API by sending GET/POST requests to start or stop EC2 instances:
   ```bash
   curl -X POST https://<api-endpoint>/start
   curl -X POST https://<api-endpoint>/stop