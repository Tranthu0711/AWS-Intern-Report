---
title: "Nhật ký công việc"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1. </b> "
---


Trong trang này, tôi trình bày worklog (nhật ký công việc) của dự án Classic Groove theo từng tuần và từng ngày.

Worklog giúp theo dõi tiến độ thực hiện, các nhiệm vụ đã hoàn thành, cũng như những vấn đề gặp phải trong quá trình triển khai hệ thống.

Dự án được thực hiện trong vòng 8 tuần (2 tháng), với mục tiêu xây dựng và triển khai một ứng dụng web hoàn chỉnh trên nền tảng cloud (AWS).

**Tuần 1:** [Tìm hiểu AWS và các khái niệm Cloud. Làm quen với các dịch vụ EC2, RDS. Tạo tài khoản AWS và cấu hình IAM theo nguyên tắc least privilege.](1.1-week1/)

**Tuần 2:** [Phân tích yêu cầu project, thiết lập môi trường local (LAMP), xây dựng và kiểm thử database MySQL.](1.2-week2/)

**Tuần 3:** [Khởi tạo EC2 (Amazon Linux 2), cấu hình Security Group (SSH, HTTP, HTTPS), tạo SSH key, cài đặt Apache và PHP.](1.3-week3/)

**Tuần 4:** [Upload source code bằng SCP, deploy vào thư mục /var/www/html, cấu hình quyền file và kiểm tra truy cập. ](1.4-week4/)

**Tuần 5:** [Tạo RDS MySQL, cấu hình Security Group (port 3306), kết nối EC2 với RDS và import database từ local. ](1.5-week5/)

**Tuần 6:** [Xử lý lỗi kết nối MySQL 8 và charset, cài đặt php-mysqlnd, nâng cấp PHP, tạo script test kết nối database.](1.6-week6/)

**Tuần 7:** [Cấu hình kết nối database trong source code (dataProvider.php) sử dụng mysqli_real_connect (SSL), restart Apache và kiểm tra hệ thống. ](1.7-week7/)

**Tuần 8:** [ Kiểm thử hệ thống, debug lỗi, kiểm tra toàn bộ chức năng, viết tài liệu và hoàn thiện báo cáo. ](1.8-week8/)
