---
title: "Worklog Tuần 6"
date: 2026-04-27
weight: 1
chapter: false
pre: " <b> 1.6. </b> "
---


### Mục tiêu tuần 6:

* Tuần này tập trung tích hợp Amazon S3 vào ứng dụng để quản lý và lưu trữ các file tĩnh như hình ảnh.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | **-	Công việc:**  <br>&emsp; + Tạo một S3 bucket mới để lưu trữ file của ứng dụng. <br>&emsp; + Cấu hình các thiết lập cơ bản cho bucket. <br> **- Kết quả:**  <br>&emsp; + Bucket được tạo thành công và sẵn sàng sử dụng. <br> **- Bài học:**  <br>&emsp; + S3 cung cấp giải pháp lưu trữ có khả năng mở rộng và độ tin cậy cao.        | 13/04/2026   | 13/04/2026      | Amazon S3 Getting Started – <https://docs.aws.amazon.com/AmazonS3/latest/userguide/GetStartedWithS3.html> |
| 3   | **-	Công việc:**  <br>&emsp; + Cấu hình policy để cho phép truy cập public đối với file hình ảnh. <br>&emsp; + Điều chỉnh quyền truy cập để đảm bảo an toàn. <br> **- Kết quả:**  <br>&emsp; + File trong S3 có thể truy cập thông qua URL công khai. <br> **- Bài học:**  <br>&emsp; + Cần cấu hình bảo mật cẩn thận để tránh lộ dữ liệu quan trọng.              | 14/04/20265   | 14/04/2026      | S3 Bucket Policy Guide – <https://docs.aws.amazon.com/AmazonS3/latest/userguide/bucket-policies.html> |
| 4   | **-	Công việc:**  <br>&emsp; + Cài đặt AWS SDK cho PHP trên EC2. <br>&emsp; + Cấu hình thông tin xác thực để truy cập S3. <br> **- Kết quả:**  <br>&emsp; + Ứng dụng kết nối thành công với dịch vụ S3. <br> **- Bài học:**  <br>&emsp; + Việc sử dụng SDK giúp việc tương tác với AWS trở nên dễ dàng hơn.     | 15/04/2026   | 15/04/2026      | AWS SDK for PHP – <https://docs.aws.amazon.com/sdk-for-php/> |
| 5   | **-	Công việc:**  <br>&emsp; + Xây dựng chức năng upload ảnh từ ứng dụng lên S3. <br>&emsp; + Kiểm tra quá trình upload file. <br> **- Kết quả:**  <br>&emsp; + File được upload thành công lên S3. <br> **- Bài học:**  <br>&emsp; + Lưu file trên S3 giúp giảm tải bộ nhớ cho EC2.            | 16/04/2026   | 16/04/2026      | Upload Files to S3 using PHP – <https://docs.aws.amazon.com/sdk-for-php/v3/developer-guide/s3-examples.html> |
| 6   | **-	Công việc:**  <br>&emsp; + Hiển thị hình ảnh từ S3 trên website. <br>&emsp; + Kiểm tra việc load file. <br> **- Kết quả:**  <br>&emsp; + Hình ảnh hiển thị chính xác trên website. <br> **- Bài học:**  <br>&emsp; + Tích hợp S3 giúp cải thiện hiệu năng và khả năng mở rộng của hệ thống.             | 17/04/2026   | 17/04/2026      | AWS Console |


### Kết quả đạt được tuần 6:
* Tích hợp thành công Amazon S3 vào ứng dụng để lưu trữ và hiển thị file tĩnh.