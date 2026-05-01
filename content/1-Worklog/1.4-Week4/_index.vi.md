---
title: "Worklog Tuần 4"
date: 2026-04-27
weight: 1
chapter: false
pre: " <b> 1.4. </b> "
---


### Mục tiêu tuần 4:

* Tuần này tập trung triển khai ứng dụng web PHP có sẵn lên EC2 và đưa hệ thống hoạt động online.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | **-	Công việc:**  <br>&emsp; + Upload mã nguồn PHP lên EC2 bằng SCP.  <br> **- Kết quả:**  <br>&emsp; + Mã nguồn được chuyển lên server thành công. <br> **- Bài học:**  <br>&emsp; + SCP là phương pháp đơn giản và an toàn để truyền file.      | 30/03/2026   | 30/03/2026      | SCP Command Guide – <https://linux.die.net/man/1/scp> |
| 3   | **-	Công việc:**  <br>&emsp; + Di chuyển mã nguồn vào thư mục /var/www/html.  <br> **- Kết quả:**  <br>&emsp; + File nằm đúng thư mục web root. <br> **- Bài học:**  <br>&emsp; + Cấu trúc thư mục đúng là yếu tố quan trọng để web server hoạt động.           | 31/03/2026   | 31/03/2026      | Linux File System Structure – <https://www.linux.com/training-tutorials/linux-filesystem-explained/> |
| 4   | **-	Công việc:**  <br>&emsp; + Thiết lập quyền truy cập file cho Apache. <br> **- Kết quả:**  <br>&emsp; + Không còn lỗi liên quan đến quyền. <br> **- Bài học:**  <br>&emsp; + Cấu hình quyền hợp lý giúp hệ thống an toàn và ổn định.    | 01/04/2026   | 01/04/2026      | Linux Permissions (chmod, chown) – <https://www.gnu.org/software/coreutils/manual/html_node/chmod-invocation.html> |
| 5   | **-	Công việc:**  <br>&emsp; + Khởi động lại Apache và kiểm tra website. <br> **- Kết quả:**  <br>&emsp; + Website hiển thị thành công trên trình duyệt. <br> **- Bài học:**  <br>&emsp; + Deploy thành công là một cột mốc quan trọng.          | 02/04/2026   | 02/04/2026      | Apache Configuration Guide – <https://httpd.apache.org/docs/current/configuring.html> |
| 6   | **-	Công việc:**  <br>&emsp; + Phát hiện và sửa các lỗi nhỏ trong ứng dụng. <br> **- Kết quả:**  <br>&emsp; + Ứng dụng hoạt động ổn định. <br> **- Bài học:**  <br>&emsp; + Debug là kỹ năng quan trọng trong quá trình triển khai.           | 03/04/2026   | 03/04/2026      | Web Debugging Basics – <https://developer.mozilla.org/en-US/docs/Learn/Common_questions> |


### Kết quả đạt được tuần 4:

* Triển khai thành công ứng dụng PHP lên EC2.