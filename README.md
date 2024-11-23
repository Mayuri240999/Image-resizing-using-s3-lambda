# Seamless Image Resizing and Transfer system using aws services 

## Project Description:
This project aims to develop an automated image processing and management system within the AWS environment. The primary objective is to simplify image handling by resizing images automatically and transferring them to a specified storage destination. Additionally, the system ensures stakeholders are kept informed through real-time notifications. Core AWS services, including Lambda, S3, and SNS, are utilized to seamlessly coordinate the workflow.

## Key Features:
1. Automated Image Processing: Automatically resize and optimize images as soon as they are uploaded.
2. Secure Storage: Safely store processed images in a reliable and secure S3 bucket.
3. Instant Notifications: Receive real-time updates about image processing through SNS alerts.
4. Scalable Design: Built to scale and handle varying image processing workloads efficiently.
5. Cost-Effective Solution: Utilize AWS serverless services to reduce operational expenses and enhance efficiency.

## Workflow:
1. Image Upload to S3 Bucket Users upload images to a designated Amazon S3 bucket. This triggers an event notification.
2. AWS Lambda for Image Resizing An AWS Lambda function is triggered automatically upon image upload. The Lambda function processes the uploaded image, resizes it into predefined dimensions and stores the resized versions in separate folders within the same or another S3 bucket.
3. Notification via SNS After the resizing process is complete, the system uses Amazon SNS to notify stakeholders (e.g., via email, SMS, or HTTP endpoints) about the completion of the task. Notifications can include metadata, such as the file names and locations of the resized images.

## Overview :
