---
title: "Dọn dẹp tài nguyên"
date: 2025-09-10
weight: 9
chapter: false
pre: " <b> 5.9. </b> "
---

#### Tổng quan

Chúc mừng bạn đã hoàn thành Workshop triển khai MiniMarket trên AWS!

Tuy nhiên, công việc của một Cloud Engineer chưa kết thúc ở đó. Bước cuối cùng và cũng là bước quan trọng nhất để bảo vệ "ví tiền" của bạn là **Dọn dẹp tài nguyên**

Các dịch vụ chúng ta đã triển khai như **NAT Gateway, Elastic Load Balancer, RDS, ElastiCache** đều tính phí theo giờ, dù bạn có sử dụng hay không. Nếu quên xóa, hóa đơn cuối tháng có thể rất cao.

Chúng ta sẽ đi qua quy trình **Decommissioning** hệ thống theo đúng trình tự để đảm bảo không còn tài nguyên nào bị sót lại gây phát sinh chi phí ngầm.

**Các dịch vụ có thể ăn rất nhiều chi phí của bạn nếu quên chúng:**
1.  **NAT Gateway & Elastic IP:** Tốn khoảng $1.5 - $3/tháng mỗi cái.
2.  **Elastic Load Balancer (ALB):** Tốn khoảng $16/tháng.
3.  **RDS & ElastiCache:** Tốn phí theo giờ chạy của Instance.

#### Nội dung

1. [Quy trình xóa tài nguyên an toàn](5.9.1-cleanup/)
