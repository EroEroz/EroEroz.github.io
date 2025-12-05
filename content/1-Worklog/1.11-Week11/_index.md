---
title: "Week 11 Worklog"
date: 2025-09-10
weight: 2
chapter: false
pre: " <b> 1.11. </b> "
---

### Week 11 Objectives:
- Audit and synchronize the latest backend codebase for deployment.
- Prepare application configuration (Environment Variables) for production.
- Draft build scripts and configuration files for AWS services.
- Finalize project structure for the upcoming cloud migration.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | -  Attended **"DevOps on AWS"** full-day workshop <br>&emsp; + **Morning Session (CI/CD & IaC):** <br>&emsp;&emsp; - Learned **DevOps Mindset** and metrics (DORA, MTTR) <br>&emsp;&emsp; - Deep dived into **AWS Code** Suite (CodeCommit, CodeBuild, CodeDeploy, CodePipeline) <br>&emsp;&emsp; - Explored **Infrastructure as Code (IaC)** using CloudFormation and CDK <br>&emsp; + **Afternoon Session (Containers & Observability):** <br>&emsp;&emsp; - Covered **Docker Fundamentals** and **Amazon ECR/ECS/EKS** orchestration <br>&emsp;&emsp; - Learned **Monitoring & Observability** best practices using **CloudWatch** and **AWS X-Ray**  | 11/17/2025 | 11/17/2025 | |
| 3 | - **Codebase & Config Prep** (Post-workshop implementation) <br>&emsp; + Synced with backend team to obtain the stable release branch <br>&emsp; + Sanitized `appsettings.json` and mapped **Environment Variables** for the cloud  | 11/18/2025 | 11/18/2025 | |
| 4 | - Drafted `buildspec.yml` commands for the upcoming CI/CD pipeline| 11/19/2025 | 11/19/2025 | |
| 5 | - Removed unused files and debug logs from the project directory | 11/20/2025 | 11/20/2025 | |
| 6 | - Reviewed the deployment checklist for next week <br>&emsp; + Confirmed with the team that no further code changes will be made before Monday | 11/21/2025 | 11/21/2025 | |

### Week 11 Achievements:
- Successfully prepared the application configuration for a production environment.
- Cleaned up the project structure to ensure a smooth deployment.
- Confirmed project readiness for the Week 12 cloud migration.