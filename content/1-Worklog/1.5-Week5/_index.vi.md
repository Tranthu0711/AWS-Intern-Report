---
title: "Worklog Tuần 5"
date: 2026-04-27
weight: 1
chapter: false
pre: " <b> 1.5. </b> "
---


### Mục tiêu tuần 5:

* Tuần này tập trung tích hợp Amazon RDS vào ứng dụng PHP và thực hiện các điều chỉnh cơ bản để đảm bảo kết nối database ổn định.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | **-	Công việc:**  <br>&emsp; + Tạo một instance RDS MySQL. <br>&emsp; + Cấu hình thông tin đăng nhập database. <br> **- Kết quả:**  <br>&emsp; + RDS được tạo thành công. <br> **- Bài học:**  <br>&emsp; + Dịch vụ database được quản lý giúp đơn giản hóa hạ tầng.       | 06/04/2026   | 06/04/2026      | Create RDS Instance – <https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_CreateDBInstance.html> |
| 3   | **-	Công việc:**  <br>&emsp; + Cấu hình Security Group để EC2 truy cập RDS. <br>&emsp; + Mở port 3306. <br> **- Kết quả:**  <br>&emsp; + EC2 kết nối được với RDS. <br> **- Bài học:**  <br>&emsp; + Cấu hình mạng rất quan trọng để đảm bảo kết nối.            | 07/04/2026   | 07/04/2026      | RDS Security Group Setup – <https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Overview.RDSSecurityGroups.html> |
| 4   | **-	Công việc:**  <br>&emsp; + Import database từ file SQL lên RDS. <br> **- Kết quả:**  <br>&emsp; + Dữ liệu được chuyển thành công. <br> **- Bài học:**  <br>&emsp; + Cần cẩn thận khi chuyển dữ liệu để tránh lỗi.     | 08/04/2026   | 08/04/2026      | MySQL Import Guide – <https://dev.mysql.com/doc/refman/8.0/en/mysqlimport.html> |
| 5   | **-	Công việc:**  <br>&emsp; + Cập nhật cấu hình database trong code PHP. <br>&emsp; + Thay localhost bằng endpoint RDS. <br> **- Kết quả:**  <br>&emsp; + Ứng dụng kết nối thành công với RDS. <br> **- Bài học:**  <br>&emsp; + Database trên cloud giúp mở rộng tốt hơn.             | 09/04/2026   | 09/04/2026      | PHP MySQL Connection |
| 6   | **-	Công việc:**  <br>&emsp; + Kiểm tra các chức năng CRUD. <br>&emsp; + Sửa một số lỗi kết nối nhỏ. <br> **- Kết quả:**  <br>&emsp; + Các chức năng database hoạt động bình thường. <br> **- Bài học:**  <br>&emsp; + Những chỉnh sửa nhỏ giúp hệ thống ổn định hơn.           | 10/04/2026   | 10/04/2026      | CRUD Operations Guide |


### Kết quả đạt được tuần 5:

* Tích hợp RDS thành công và đảm bảo hệ thống hoạt động ổn định.