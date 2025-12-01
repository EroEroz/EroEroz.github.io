---
title: "Cấu hình Internet & NAT Gateway"
date: 2025-09-10
weight: 2
chapter: false
pre: " <b> 5.3.2 </b> "
---

#### Tạo Internet Gateway
1. Trong phần [VPC dashboard](https://ap-southeast-1.console.aws.amazon.com/vpcconsole/home?region=ap-southeast-1#Home:) nhấn vào **Internet gateways**

![IGW1](/images/5-Workshop/5.3-Network/IGW1.png)

2. Sau đó nhấn vào **Create internet gateway**

![IGW2](/images/5-Workshop/5.3-Network/IGW2.png)

3. Trong phần tạo **Internet gateway**, hãy đặt tên tùy thích sau đó nhấn vào **Create internet gateway** rồi đợi nó được tạo

![IGW3](/images/5-Workshop/5.3-Network/IGW3.png)

4. Sau khi **Internet gateway** được tạo xong hãy vào phần **Actions** và bấm vào **Attach to VPC** để gán nó vào VPC đã được tạo ở phần trước

![IGW4](/images/5-Workshop/5.3-Network/IGW4.png)

![IGW5](/images/5-Workshop/5.3-Network/IGW5.png)

#### Tạo NAT Gateway
1. Tạo **NAT Gateway** đặt tại **Public Subnet 1**
2. Gán **Elastic IP** để có địa chỉ tỉnh ra Internet

![NAT1](/images/5-Workshop/5.3-Network/NAT1.png)

![NAT2](/images/5-Workshop/5.3-Network/NAT2.png)



#### Tạo Route Table
Ấn vào phần **Route tables** trong VPC dashboard

![RT1](/images/5-Workshop/5.3-Network/RT1.png)

Tạo 2 Route Table, **Public** với **Private**

![RT2](/images/5-Workshop/5.3-Network/RT2.png)

![RT3](/images/5-Workshop/5.3-Network/RT3.png)

1. **Public Route Table:**
   - Đối với **Public Route Table**, trong phần **Routes** ấn vào **Edit routes**
   - Trỏ 0.0.0.0/0 về **Internet Gateway** 

![RT4](/images/5-Workshop/5.3-Network/RT4.png)

![RT5](/images/5-Workshop/5.3-Network/RT5.png)

   - Và trong phần Subnet associations, gán cho cả hai **Public Subnet**

![RT6](/images/5-Workshop/5.3-Network/RT6.png)

![RT7](/images/5-Workshop/5.3-Network/RT7.png)

