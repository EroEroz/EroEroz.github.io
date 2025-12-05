---
title: "Worklog tuần 12"
date: 2025-09-10
weight: 2
chapter: false
pre: " <b> 1.12. </b> "
---

### Mục tiêu tuần 12:

- Triển khai và kiểm tra độ ổn định của dự án trên **AWS Cloud**.
- Triển khai tự động hóa CI/CD sử dụng **AWS CodePipeline**.
- Tối ưu hóa phân phối static assets sử dụng **S3** và **CloudFront**.
- Distributed caching sử dụng **Amazon ElastiCache (Redis)**.
- Bắt đầu đào tạo về **AWS Cloud Architecture**.

### Các nhiệm vụ thực hiện trong tuần này:

| Thứ | Nhiệm vụ                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- | ------------------ |
| 2   | - Xem xét và merge các thay đổi **code nhóm** mới nhất để đảm bảo tính nhất quán <br>&emsp; + Refactor các file cấu hình cục bộ (appsettings) để chuẩn bị cho việc di chuyển lên **AWS** | 24/11/2025 | 24/11/2025 | |
| 3 | - Test deploy code dự án lên **AWS Cloud** để xác minh độ ổn định <br>&emsp; + Xác minh các chức năng: **thêm vào giỏ hàng** và **thanh toán** <br>&emsp; + **Cấu hình dịch vụ** để đảm bảo tương thích với **code nhóm** <br> - Đăng ký khóa học **AWS Cloud Solutions Architect** trên Coursera <br>&emsp; + Bắt đầu Khóa 1: **AWS Cloud Technical Essentials** <br>&emsp;&emsp; - Hoàn thành tài liệu giới thiệu **Tuần 1: AWS Overview and Security** <br>&emsp;&emsp; - Bao gồm **What is AWS?** và **AWS Global Infrastructure** (Video & Bài đọc 1.3) | 25/11/2025 | 25/11/2025 | |
| 4 | - Cấu hình **AWS CodePipeline** cho việc triển khai tự động <br>&emsp; + Thiết lập các dịch vụ **CodeBuild** và **CodeDeploy** <br>&emsp;&emsp; - Cấu hình tích hợp **GitHub**: push code sẽ kích hoạt triển khai tự động lên **AWS Cloud** | 26/11/2025 | 26/11/2025 | |
| 5 | - Khởi tạo **S3 Bucket** và di chuyển static assets (hình ảnh) <br>&emsp; + Cấu hình **CloudFront** (CDN) để phục vụ nội dung từ S3 <br>&emsp; + Triển khai các kiểm soát bảo mật (**OAC** và Bucket Policies) | 27/11/2025 | 27/11/2025 | |
| 6 | - Triển khai cluster **Amazon ElastiCache (Redis)** <br>&emsp; + Cấu hình ứng dụng .NET Core sử dụng Redis để tích hợp **Session Storage** | 28/11/2025 | 28/11/2025 | |

### Kết quả đạt được tuần 12:

- Đã thành công triển khai dự án trên **AWS Cloud**.
- Thiết lập pipeline CI/CD sử dụng **CodePipeline**, **CodeBuild**, và **CodeDeploy**.
- Tích hợp thành công **S3** và **CloudFront** để lưu trữ và phân phối static assets.
- Triển khai **Amazon ElastiCache** để xử lý distributed session.
- Bắt đầu đào tạo AWS: Hoàn thành các module giới thiệu về **AWS Global Infrastructure**.