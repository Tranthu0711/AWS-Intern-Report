---
title : "Điều kiện tiên quyết"
date : 2026-04-27
weight : 1
chapter : false
pre : " <b> 4.3.1 </b> "
---

Trước khi bắt đầu triển khai và thực hiện lab, cần chuẩn bị các điều kiện sau:
- Tài khoản AWS: Cần có tài khoản AWS hợp lệ để sử dụng và quản lý các dịch vụ như EC2, RDS và S3. 
- Region: Hệ thống được triển khai tại ap-southeast-2 (Sydney) nhằm đảm bảo tính ổn định và tương thích dịch vụ. 
- Công cụ sử dụng: 
<br>&emsp; - AWS Management Console (giao diện chính để cấu hình tài nguyên) 
<br>&emsp; - SSH (Git Bash / Terminal) để kết nối vào EC2 
<br>&emsp; - SCP để truyền source code từ máy local lên server 
<br>&emsp; - Composer để cài đặt AWS SDK cho PHP (dùng cho S3) 
- Quyền IAM cần thiết: 
<br>&emsp; - Toàn quyền EC2 
<br>&emsp; - Toàn quyền RDS 
<br>&emsp; - Toàn quyền S3 
<br>&emsp; - Quyền tạo Access Key trong IAM 

