# S3 Static Website Hosting

## Project Overview
This project demonstrates hosting a static website using an Amazon S3 bucket. It showcases serverless website deployment without managing servers.

## Objective
- Create an S3 bucket for website hosting.
- Upload HTML, CSS, and other assets.
- Enable static website hosting to make the site publicly accessible.

## Steps
1. Create an S3 bucket with a unique name.
2. Upload website files (`index.html`, CSS, images, etc.).
3. Enable **Static Website Hosting** in bucket properties.
4. Set proper **bucket policy** for public read access:
   ```json
   {
     "Version":"2012-10-17",
     "Statement":[
       {
         "Effect":"Allow",
         "Principal": "*",
         "Action":"s3:GetObject",
         "Resource":"arn:aws:s3:::<bucket-name>/*"
       }
     ]
   }