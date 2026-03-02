# Website Down Alert System

## Project Overview
This project demonstrates monitoring a website’s uptime using AWS Lambda (or Canary) and sending automatic alerts via SNS when the site is down, enabling proactive monitoring.

## Objective
- Set up automated website monitoring using Lambda or Canary.
- Configure SNS to send alerts via email or SMS.
- Learn event-driven monitoring and automated notifications.

## Steps
1. Create an **SNS Topic** and subscribe an email address or phone number.
2. Configure a **Lambda function** or **Canary** to periodically check the website status.
3. Trigger SNS notification when website is unreachable (HTTP error or timeout).
4. Test by stopping the website or pointing to an invalid URL.
5. Verify receipt of alerts in the subscribed channel.

## Proof
- Screenshot 1: Lambda/Canary setup and test configuration.
- Screenshot 2: SNS topic and subscription confirmation.
- Screenshot 3: Alert received when website downtime simulated.

## Outcome
Automated monitoring and alerting for website uptime, demonstrating AWS serverless monitoring with SNS notifications.