---
title: "Workshop"
date: 2026-04-27
weight: 5
chapter: false
pre: " <b> 4. </b> "
---

# Triển khai ứng dụng "Classic Groove" trên nền tảng AWS

#### Tổng quan về workshop
Workshop này trình bày cách triển khai ứng dụng web Classic Groove trên AWS theo mô hình 3-tier. Hệ thống sử dụng EC2 để chạy ứng dụng, RDS (MySQL) để quản lý database và S3 để lưu trữ tài nguyên tĩnh, đảm bảo khả năng mở rộng và độ ổn định.

#### Điều kiện tiên quyết
- Tài khoản AWS 
- Kiến thức Linux, Apache cơ bản 
- SSH (Terminal / PuTTY) 
- MySQL 
- Source code PHP

#### Mô tả kiến trúc
Thành phần hệ thống:
- EC2: Chạy ứng dụng 
- RDS: Database 
- S3: File tĩnh 
Luồng: Client → EC2 → RDS → S3
Bảo mật:
- Security Group giới hạn port 
- IAM Role cho EC2 truy cập S3

#### Các bước thực hiện 
Step 1: EC2 Steup
- Tạo EC2 
- Mở port 22, 80, 443 
- Cài Apache, PHP

Step 2: Deploy Web Application
- Upload code bằng SCP 
- Đưa vào /var/www/html 
- Restart Apache

Step 3: RDS Setup 
- Tạo RDS MySQL 
- Mở public access 
- Mở port 3306 
- Import database

Step 4: Connect EC2 to RDS
- Sửa config DB trong code 
- Test kết nối

Step 5: S3 Integration
- Tạo S3 bucket 
- Upload file tĩnh 
- Sửa code load từ S3

Step 6: IAM Policy (Optional but recommended)
Policy cho phép EC2 đọc file từ S3: 
```
{
    "Version": "2012-10-17",
  "Statement": [
    {
      "Effect": "Allow",
      "Action": ["s3:GetObject"],
      "Resource": "arn:aws:s3:::your-bucket-name/*"
    }
  ]
}
```

Step 7: Testing & Validation
- Truy cập web 
- Test CRUD database 
- Kiểm tra load ảnh từ S3
  
Step 8: Clean-up
- Xóa EC2 
- Xóa RDS 
- Xóa S3 
- Dọn tài nguyên

#### Nội dung

1. [Hình thức và công cụ làm project](5.1-Workshop-overview/)
2. [Kiến trúc & thiết kế kỹ thuật](5.2-Architecture/)
3. [Triển khai & Lab Step-by-step](5.3-Implementation/)
4. [Kiểm thử & đo lường ](5.4-S3-Testing/)
5. [Tối ưu & Clean-up](5.5-Optimization/)
