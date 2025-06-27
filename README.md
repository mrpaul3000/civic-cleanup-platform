# civic-cleanup-platform
A cloud-native AI-enhanced platform to report and coordinate sanitation projects in Nigerian schools.


## Problem Statement

In many Nigerian schools, unsanitary toilet conditions threaten student health and dignity. Traditional cleanup efforts lack organization, transparency, and data. This platform bridges that gap through technology.

---

## Key Features

- Upload sanitation issues with images
- Crowd-support to escalate cases
- AI-based assessment and auto-generated cleanup project plans
- Volunteer/donor engagement system
- Fully built on AWS, designed for scale and automation

---

## AWS Architecture Overview

This platform uses a serverless, event-driven design pattern to ensure scalability, reliability, and cost-efficiency.

Key services include:
- **Amazon S3** – Store uploaded images
- **DynamoDB** – Store report and user data
- **Lambda** – Run backend logic
- **Step Functions** – Orchestrate AI workflows
- **Rekognition** – Analyze sanitation images
- **Amazon Bedrock (or SageMaker)** – Generate project plans
- **API Gateway** – Serve API endpoints to frontend
- **Cognito** – User registration and login
- **CloudWatch** – Logging and monitoring

Architecture diagram and service details are in `/architecture/README.md`.

---

## User Roles

- **Reporter** – Submits cleanup issue with images
- **Community** – Upvotes and supports issues
- **System** – AI executes cleanup assessment once threshold is met
- **Volunteers/Donors** – Sign up to support the project

---

## Development Status

Architecture design: **In progress**  
Backend Lambda logic: **To be implemented**  
AI pipeline: **Under research & prototyping**

---

## Future Features

- Automate Maintainance Scheduling 
- Trigger new project from scheduled maintenance
- SMS/email alerts to stakeholders
- Leaderboard for active volunteers
- Admin dashboard for project tracking
- Mobile-first Progressive Wed Application version

---

## Created By

[Paul Oteh] – AWS Cloud practioner & Innovation Enthusiast  
[www.linkedin.com/in/pauloteh]  
