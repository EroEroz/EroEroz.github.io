---
title: "Week 12 Worklog"
date: 2025-09-10
weight: 2
chapter: false
pre: " <b> 1.12. </b> "
---

### Week 12 Objectives:

- Deploy and verify project stability on **AWS Cloud**.
- Implement CI/CD automation using **AWS CodePipeline**.
- Optimize static asset delivery using **S3** and **CloudFront**.
- Implement distributed caching using **Amazon ElastiCache (Redis)**.
- Begin **AWS Cloud Architecture** training.

### Tasks to be carried out this week:

| Day | Task                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | Start Date | Completion Date | Reference Material |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- | ------------------ |
| 2   | - Reviewed and merged latest **group code** changes to ensure consistency <br>&emsp; + Refactored local configuration files (appsettings) to prepare for **AWS** migration | 11/24/2025 | 11/24/2025 | |
| 3 | - Test deploy project code on **AWS Cloud** to verify stability <br>&emsp; + Verify functions: **add items to cart** and **payment** <br>&emsp; + **Configure services** to ensure compatibility with **group code** <br> - Enrolled in **AWS Cloud Solutions Architect** specialization on Coursera <br>&emsp; + Started Course 1: **AWS Cloud Technical Essentials** <br>&emsp;&emsp; - Completed **Week 1: AWS Overview and Security** introductory materials <br>&emsp;&emsp; - Covered **What is AWS?** and **AWS Global Infrastructure** (Video & Reading 1.3) | 11/25/2025 | 11/25/2025 | |
| 4 | - Configure **AWS CodePipeline** for automated deployment <br>&emsp; + Set up **CodeBuild** and **CodeDeploy** services <br>&emsp;&emsp; - Configure **GitHub** integration: code push triggers automatic deployment to **AWS Cloud** | 11/26/2025 | 11/26/2025 | |
| 5 | - Initialize **S3 Bucket** and migrate static assets (images) <br>&emsp; + Configure **CloudFront** (CDN) to serve content from S3 <br>&emsp; + Implement security controls (**OAC** and Bucket Policies) | 11/27/2025 | 11/27/2025 | |
| 6 | - Deploy **Amazon ElastiCache (Redis)** cluster <br>&emsp; + Configure .NET Core application to use Redis for **Session Storage** integration | 11/28/2025 | 11/28/2025 | |

### Week 12 Achievements:

- Validated project deployment on **AWS Cloud**.
- Established CI/CD pipeline using **CodePipeline**, **CodeBuild**, and **CodeDeploy**.
- Successfully integrated **S3** and **CloudFront** for static asset storage and delivery.
- Implemented **Amazon ElastiCache** to handle distributed sessions.
- Initiated AWS training: Completed introductory modules on **AWS Global Infrastructure**.
