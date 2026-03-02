# DynamoDB Basic Table Creation

## Project Overview
This project demonstrates creating a basic Amazon DynamoDB table and inserting sample items, showcasing serverless NoSQL database capabilities.

## Objective
- Create a DynamoDB table.
- Insert and query sample items.
- Understand serverless NoSQL database operations.

## Steps
1. Navigate to **DynamoDB** in AWS Console and create a table:
   - Table name: `SampleTable`
   - Primary key: `ID` (Number or String)
2. Insert sample items manually or via CLI:
   ```bash
   aws dynamodb put-item \
       --table-name SampleTable \
       --item '{"ID": {"N":"1"}, "Name": {"S":"Ankan"}}'
3. Query or scan the table to verify data:

	aws dynamodb scan --table-name SampleTable