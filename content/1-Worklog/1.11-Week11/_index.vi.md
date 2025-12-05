---
title: "Worklog tuần 11"
date: 2025-09-10
weight: 2
chapter: false
pre: " <b> 1.11. </b> "
---

### Mục tiêu tuần 11:
- Kiểm tra và đồng bộ hóa codebase backend mới nhất để triển khai.
- Chuẩn bị cấu hình ứng dụng (Biến môi trường) cho production.
- Soạn thảo các script build và file cấu hình cho các dịch vụ AWS.
- Hoàn thiện cấu trúc dự án cho việc di chuyển lên cloud sắp tới.

### Các nhiệm vụ thực hiện trong tuần này:

| Thứ | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 2 | - Tham dự workshop **"DevOps on AWS"** <br>&emsp; + **Buổi sáng (CI/CD & IaC):** <br>&emsp;&emsp; - Học về **Tư duy DevOps** và các chỉ số (DORA, MTTR) <br>&emsp;&emsp; - Tìm hiểu sâu về **AWS Code** Suite (CodeCommit, CodeBuild, CodeDeploy, CodePipeline) <br>&emsp;&emsp; - Khám phá **Infrastructure as Code (IaC)** sử dụng CloudFormation và CDK <br>&emsp; + **Buổi chiều (Containers & Observability):** <br>&emsp;&emsp; - Bao gồm các kiến thức cơ bản về **Docker** và điều phối **Amazon ECR/ECS/EKS** <br>&emsp;&emsp; - Học các best practice về **Monitoring & Observability** sử dụng **CloudWatch** và **AWS X-Ray**  | 17/11/2025 | 17/11/2025 | |
| 3 | - **Chuẩn bị Codebase & Cấu hình** (Thực hiện sau workshop) <br>&emsp; + Đồng bộ với team backend để lấy nhánh release ổn định <br>&emsp; + Làm sạch `appsettings.json` và mapped **Biến môi trường** cho cloud  | 18/11/2025 | 18/11/2025 | |
| 4 | - Soạn thảo các lệnh `buildspec.yml` cho pipeline CI/CD sắp tới| 19/11/2025 | 19/11/2025 | |
| 5 | - Xóa các file không sử dụng và log debug khỏi thư mục dự án | 20/11/2025 | 20/11/2025 | |
| 6 | - Xem lại danh sách kiểm tra triển khai cho tuần tới <br>&emsp; + Xác nhận với nhóm rằng sẽ không có thay đổi code nào được thực hiện trước thứ Hai | 21/11/2025 | 21/11/2025 | |

### Kết quả đạt được tuần 11:
- Chuẩn bị thành công cấu hình ứng dụng cho môi trường production.
- Dọn dẹp cấu trúc dự án để đảm bảo triển khai suôn sẻ.
- Xác nhận dự án đã sẵn sàng cho việc di chuyển lên cloud vào tuần 12.