---
title: "Giám sát với CloudWatch"
date: 2025-09-10
weight: 1
chapter: false
pre: " <b> 5.8.1 </b> "
---
1.  **Tạo SNS Topic:**
    *   Vào SNS > Create Topic > `DevOps-Alerts`.
    *   Create Subscription > Protocol: Email > Nhập email của bạn (Nhớ Confirm mail).

2.  **Tạo Alarm CPU:**
    *   Vào CloudWatch > Alarms > Create alarm.
    *   Select metric > EC2 > Per-Instance Metrics > Chọn InstanceID của Beanstalk > **CPUUtilization**.
    *   Condition: Greater than **70%**.
    *   Notification: Chọn Topic `DevOps-Alerts`.
    *   Create Alarm.