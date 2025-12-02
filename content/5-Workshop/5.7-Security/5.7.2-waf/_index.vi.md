---
title: "Thiết lập Tường lửa (WAF)"
date: 2025-09-10
weight: 2
chapter: false
pre: " <b> 5.7.2 </b> "
---

1.  Truy cập **WAF & Shield** > **Create web ACL**.
2.  **Resource type:** CloudFront distributions (Global).
3.  **Add rules** > **Add managed rule groups**:
    *   Thêm `Core rule set` (Chặn bot, IP xấu).
    *   Thêm `SQL database` (Chặn SQL Injection).
4.  **Associate:** Gắn WAF này vào CloudFront Distribution đã tạo.

**Kiểm thử:** Truy cập URL: `https://[domain]/?id=1 OR 1=1`. Nếu nhận lỗi **403 Forbidden**, WAF đã hoạt động.