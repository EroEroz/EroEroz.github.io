---
title: "Dọn dẹp tài nguyên"
date: 2025-09-10
weight: 1
chapter: false
pre: " <b> 5.9.1 </b> "
---

Để tránh phát sinh chi phí không mong muốn sau khi hoàn thành Workshop, hãy xóa tài nguyên theo đúng thứ tự sau:

1.  **NAT Gateway:** Delete NAT Gateway > Đợi Deleted > **Release Elastic IP**. (Quan trọng nhất vì tốn tiền nhất).
2.  **Elastic Beanstalk:** Terminate Environment.
3.  **ElastiCache:** Delete Redis Cluster (Bỏ chọn Final Backup).
4.  **RDS:** Stop (hoặc Delete nếu không dùng nữa - nhớ bỏ chọn Final Snapshot).
5.  **WAF:** Delete Web ACL.
6.  **S3:** Empty và Delete Bucket (Tùy chọn).