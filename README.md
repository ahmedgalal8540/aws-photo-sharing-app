# AWS Photo Sharing Application

## Overview

This project demonstrates the deployment of a cloud-based photo sharing application using multiple AWS services. The goal is to build a secure, scalable, and highly available infrastructure while applying AWS best practices.

---

## AWS Services Used

* Amazon VPC
* Amazon EC2
* Amazon S3
* Amazon RDS
* AWS IAM
* AWS Lambda
* AWS Secrets Manager
* AWS KMS
* Application Load Balancer (ALB)
* Amazon CloudWatch

---

## Architecture

The application consists of:

* A custom Amazon VPC
* Public and Private Subnets
* Internet Gateway
* Route Tables
* EC2 instances hosting the application
* Amazon RDS for persistent data storage
* Amazon S3 for image uploads
* Application Load Balancer for traffic distribution
* AWS Lambda for serverless processing
* IAM Roles and Policies for secure access
* Secrets Manager for credential management
* KMS for encryption
* CloudWatch for monitoring and alerts

---

## Features

* Secure VPC networking
* Image storage using Amazon S3
* Relational database backend
* High availability with Load Balancer
* Serverless processing using Lambda
* Monitoring and logging
* Encryption using AWS KMS
* Secure secret management

---

## Deployment Steps

1. Create the VPC.
2. Configure Public and Private Subnets.
3. Attach an Internet Gateway.
4. Configure Route Tables.
5. Create IAM Roles.
6. Launch EC2 Instances.
7. Create an Amazon RDS Database.
8. Create an S3 Bucket.
9. Configure Application Load Balancer.
10. Deploy Lambda Functions.
11. Configure Secrets Manager.
12. Enable CloudWatch Monitoring.
13. Test the application.

---

## Project Structure

```text
Screenshots/
Architecture/
README.md
```

---

## Screenshots

Include screenshots of:

* VPC
* Subnets
* Route Tables
* EC2
* S3
* RDS
* ALB
* Lambda
* CloudWatch Dashboard
* Final running application

---

## Skills Demonstrated

* AWS Networking
* Infrastructure Deployment
* IAM Security
* Linux Administration
* Cloud Storage
* Database Deployment
* Serverless Computing
* Monitoring and Logging
* Cloud Architecture
