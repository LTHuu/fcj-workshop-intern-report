---
title: "Week 4 Worklog"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.4. </b> "
---
## Week 4 Objectives:

* Finalize the group project topic.
* Research AWS ECS and ECR.

### Tasks to be implemented this week:

| Day | Tasks | Start Date | Completion Date | Reference |
| :--- | :--- | :--- | :--- | :--- |
| Mon | - Research **ECS** and **ECR** <br> - **Practice:** Create a database and push the database container from local/Docker to AWS. | 30/03/2026 | 30/03/2026 | |
| Wed | - Team meeting to select the project topic <br> - Research AWS services related to the chosen topic | 01/04/2026 | 01/04/2026 | |

### Week 4 Key Results:

* Finalized the topic: **"Centralized Log Registration and Management System."**

* **Relevant Services for the Project:**
    * **CloudWatch:** Monitoring and management service; used for tracking logs, collecting metrics, and setting up automated system alarms.
    * **SQS (Simple Queue Service):** Message queuing service ensuring stable and reliable data transmission.
    * **SNS (Simple Notification Service):** Push notification service; allows sending messages, emails, or triggering Lambda functions based on system events.
    * **Lambda:** Serverless computing service; runs code without managing servers, triggered automatically by events.
    * **S3 (Simple Storage Service):** Object storage service; provides durable and scalable storage for files, images, and static data.
    * **DynamoDB:** NoSQL database; provides high performance with low latency at any scale.
    * **Athena:** Interactive query service that makes it easy to analyze data in S3 using standard SQL.
    * **ECS (Elastic Container Service):** Container management service used to run, stop, and manage Docker containers on a cluster.
    * **API Gateway:** API management tool to create, publish, maintain, and secure HTTP/REST APIs.
    * **IAM (Identity and Access Management):** Manages identities and access permissions for AWS resources.
    * **Kinesis Data Streams:** Collects and processes real-time data streams with ultra-low latency.
    * **Kinesis Data Firehose:** Directly loads streaming data into storage destinations (S3, Redshift, etc.) with automatic scaling and transformation.

    > **Note:** Kinesis services are not available within the AWS Free Tier, so they will not be included in the final project implementation.

*  Mastered creating and deploying database containers from local environments to AWS using **ECS** and **ECR**.