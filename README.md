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
![Screenshot 2024-11-23 010347](https://github.com/user-attachments/assets/ef4c93d3-d405-410c-88b8-d7c0fd5d186b)
![image-resize1](https://github.com/user-attachments/assets/7ae72012-94b4-456d-a96f-5a9a4bbbce9f)
![image-resize2](https://github.com/user-attachments/assets/642e5ad7-32d2-4b7e-982a-5458f7ef0a02)
![image-resize3](https://github.com/user-attachments/assets/6f6d3efc-793a-4f4c-ada0-53c01e1cf000)
![image-resize4](https://github.com/user-attachments/assets/7f11901c-3c5d-4de8-960b-5de8f514f0d5)

![image-resize5](https://github.com/user-attachments/assets/f1378fee-ca0f-4b19-9781-e5883b50e501)
![image-resize6](https://github.com/user-attachments/assets/3c9f7620-6f88-4468-b28a-704990e89d22)
![image-resize7](https://github.com/user-attachments/assets/e3b5282c-02da-41cd-901d-af8f7c86386f)
![image-resize8](https://github.com/user-attachments/assets/9bec1563-e188-4e43-97e1-09a967cb145e)
![image-resize9](https://github.com/user-attachments/assets/f60a8693-c0c9-40a3-bd97-3260d519c4b5)
![image-resize10](https://github.com/user-attachments/assets/c68bae12-22ea-4e80-a443-667906806841)
![image-resize11](https://github.com/user-attachments/assets/221ea8a4-2cf2-4cc2-af3f-53ed92797315)
![image-resize12](https://github.com/user-attachments/assets/4d22748b-401e-4a55-820f-064259405454)
![image-resize13](https://github.com/user-attachments/assets/f6eb8686-91ed-4880-a9e6-7fed7815043f)
![image-resize14](https://github.com/user-attachments/assets/0c3c6182-32d0-4ca9-9b54-dbc4edf5dbec)
![image-resize15](https://github.com/user-attachments/assets/2434ea97-e992-4dc8-9d79-81a40fcc0aef)
![image-resize16](https://github.com/user-attachments/assets/8e87d29a-c65b-4439-a1fa-c668899dea77)
![image-resize17](https://github.com/user-attachments/assets/2d5a13ac-c433-4b61-bb55-d694c7d68ba9)
![image-resize18](https://github.com/user-attachments/assets/3aada9a3-6a84-4ffd-9010-69537dc5ed76)
![image-resize19](https://github.com/user-attachments/assets/37161aac-994d-427f-afe4-91c8fa9d9060)
![image-resize20](https://github.com/user-attachments/assets/e444850e-c527-43d2-95a9-23d4321ec1da)
![image-resize21](https://github.com/user-attachments/assets/c6daaa32-2bbe-4b20-9710-1202e3427f72)
![image-resize22](https://github.com/user-attachments/assets/41add17c-4f92-4f98-8a63-af576d30396a)
![image-resize23](https://github.com/user-attachments/assets/a6f24901-9777-40e6-b2e0-acbdceb59a7d)
![image-resize24](https://github.com/user-attachments/assets/c724a7e5-90c2-4dd6-80e5-a1a6c023fe42)
![image-resize25](https://github.com/user-attachments/assets/96c5153b-a8ef-4646-a8e5-246cd883089c)
![image-resize26](https://github.com/user-attachments/assets/41cd3327-5043-442b-a782-b9b04cd4aa80)
![image-resize27](https://github.com/user-attachments/assets/78a49089-e7c7-4d89-b7cc-30d51c1f2ed7)
![image-resize28](https://github.com/user-attachments/assets/a0931a16-24d6-465f-94f1-d7e9fcfb4131)
![image-resize29](https://github.com/user-attachments/assets/28d7e17f-c03e-40ad-8a3f-1db5e902766d)
![image-resize30](https://github.com/user-attachments/assets/674ed0ad-688b-484b-b852-f1951211fe7d)

![image-resize31](https://github.com/user-attachments/assets/8316e251-c9e1-492e-bd5e-5ed75248857d)
![image-resize32](https://github.com/user-attachments/assets/827b587b-e483-495e-805b-821155115385)
![image-resize33](https://github.com/user-attachments/assets/50abc363-9731-40ea-8107-0c0d7b190733)
![image-resize34](https://github.com/user-attachments/assets/1c57f68e-7557-41ab-aa0c-2c8cb59da9c1)
![image-resize35](https://github.com/user-attachments/assets/4e8ea11b-41e5-4e1c-83df-a7c093b5979c)
![image-resize36](https://github.com/user-attachments/assets/7b040927-e1f1-4bd7-8b75-8bc8f690fee0)
![image-resize37](https://github.com/user-attachments/assets/3d7934bc-ec3f-42de-a7d7-f7d020387fa9)
