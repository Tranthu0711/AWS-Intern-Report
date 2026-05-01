---
title: "Worklog Tuần 3"
date: 2026-04-27
weight: 1
chapter: false
pre: " <b> 1.3. </b> "
---


### Mục tiêu tuần 3:

* Trong tuần này, tôi tập trung thực hành các dịch vụ AWS như EC2, RDS và S3. Mục tiêu là tích lũy kinh nghiệm thực tế và hiểu cách các dịch vụ này hoạt động trong môi trường thật trước khi bắt đầu triển khai project.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | **-	Công việc:**  <br>&emsp; + Khởi tạo một EC2 instance sử dụng Amazon Linux. <br>&emsp; + Chọn loại instance và cấu hình key pair.  <br> **- Kết quả:**  <br>&emsp; + EC2 instance đã được tạo và hoạt động thành công. <br> **- Bài học:**  <br>&emsp; + EC2 đóng vai trò như một server ảo và là thành phần quan trọng để triển khai ứng dụng web.       | 23/03/2026   | 23/03/2026      | EC2 Launch Guide – <https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EC2_GetStarted.html> |
| 3   | **-	Công việc:**  <br>&emsp; + Kết nối đến EC2 bằng SSH và key pair. <br>&emsp; + Thực hành các lệnh Linux cơ bản <br> **- Kết quả:**  <br>&emsp; + Truy cập thành công vào terminal của EC2. <br> **- Bài học:**  <br>&emsp; + Kiến thức Linux cơ bản là cần thiết để quản lý server trên cloud.           | 24/03/2026   | 24/03/2026      | Linux Command Line Basics – <https://linuxcommand.org/> |
| 4   | **-	Công việc:**  <br>&emsp; + Cài đặt Apache HTTP Server trên EC2.  <br>&emsp; + Khởi động và cấu hình để Apache chạy tự động. <br> **- Kết quả:**  <br>&emsp; + Web server hoạt động và có thể truy cập qua địa chỉ IP công khai. <br> **- Bài học:**  <br>&emsp; + Việc thiết lập web server trên EC2 khá đơn giản và hiệu quả.   | 25/03/2026   | 25/03/2026      | Apache HTTP Server Documentation – <https://httpd.apache.org/docs/> |
| 5   | **-	Công việc:**  <br>&emsp; + Tạo một instance RDS MySQL để thử nghiệm. <br>&emsp; + Thực hiện kết nối từ EC2 đến RDS. <br> **- Kết quả:**  <br>&emsp; + Xác nhận EC2 có thể kết nối với RDS. <br> **- Bài học:**  <br>&emsp; + Cấu hình mạng đóng vai trò quan trọng trong việc kết nối giữa các dịch vụ.          | 26/03/2026   | 26/03/2026      | Amazon RDS Connection Guide – <https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_ConnectToInstance.html> |
| 6   | **-	Công việc:**  <br>&emsp; + Upload file lên S3 bucket. <br>&emsp; + Kiểm tra truy cập file qua URL công khai. <br> **- Kết quả:**  <br>&emsp; + File được upload và truy cập thành công. <br> **- Bài học:**  <br>&emsp; + S3 rất hiệu quả trong việc lưu trữ và phân phối nội dung tĩnh.           | 27/03/2026   | 27/03/2026      | Amazon S3 Upload Guide – <https://docs.aws.amazon.com/AmazonS3/latest/userguide/upload-objects.html> |


### Kết quả đạt được tuần 3:

* Tuần này giúp tôi có kinh nghiệm thực tế với các dịch vụ AWS, tạo nền tảng vững chắc để triển khai ứng dụng thực tế.