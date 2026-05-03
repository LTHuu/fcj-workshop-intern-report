---
title: "Worklog Tuần 4"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.4. </b> "
---


### Mục tiêu tuần 4:

* Thống nhất đề tài nhóm.
* Tìm hiểu về ECS và EDR

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu về ECS và EDR   <br> **Thực hành:** : <br>&emsp; + Tạo database và push database container từ máy cá nhân và docker lên AWS.                                                                                         | 30/03/2026   | 30/03/2026      |
| 4   |    - Cùng nhóm chọn đề tài <br> - Tìm hiểu về các dịch vụ liên quan đến đề tài | 01/04/2026   | 01/04/2026      | |


### Kết quả đạt được tuần 4:

* Chọn đề tài là **Một hệ thống đăng kí và nhận log tập trung:**

* Các dịch vụ liên quan đến đề tài : 
  * **CloudWatch:**: Dịch vụ giám sát và quản lý tài nguyên; dùng để theo dõi log, thu thập số liệu (metrics) và thiết lập cảnh báo tự động cho hệ thống.

  * **SQS (Simple Queue Service):** Dịch vụ hàng đợi thông điệp, đảm bảo truyền tải dữ liệu ổn định và tin cậy.

  * **SNS (Simple Notification Service):** Dịch vụ thông báo đẩy; cho phép gửi tin nhắn, email hoặc kích hoạt các hàm Lambda khi có sự kiện xảy ra trong hệ thống.

  * **Lambda:** Dịch vụ tính toán phi máy chủ (Serverless); cho phép chạy mã nguồn trực tiếp mà không cần quản lý server, tự động kích hoạt theo sự kiện.

  * **S3 (Simple Storage Service):** Dịch vụ lưu trữ đối tượng; cung cấp khả năng lưu trữ tệp tin, hình ảnh và dữ liệu tĩnh với độ bền và khả năng mở rộng cực cao.

  * **DynamoDB:** Cơ sở dữ liệu NoSQL; cung cấp hiệu năng cao với độ trễ thấp ở mọi quy mô, phù hợp cho các ứng dụng cần truy xuất dữ liệu cực nhanh.

  * **Athena:** Dịch vụ truy vấn dữ liệu trực tiếp trên S3 bằng ngôn ngữ SQL; giúp phân tích các tệp log hoặc dữ liệu thô mà không cần nạp vào cơ sở dữ liệu phức tạp.

  * **ECS (Elastic Container Service):** Dịch vụ quản lý container; dùng để chạy, dừng và quản lý các Docker container trên một cụm server được tối ưu hóa.

  * **API Gateway:** Cổng quản lý API; giúp tạo, xuất bản, duy trì và bảo mật các HTTP/REST API để kết nối ứng dụng với các dịch vụ backend.
  * **IAM:** Dịch vụ quản lý định danh và quyền truy cập;

  * **Kinesis Data Streams:** Dịch vụ thu thập và xử lý dòng dữ liệu theo thời gian thực với độ trễ cực thấp; 

  * **Kinesis Data Firehose:** Dịch vụ truyền tải dữ liệu dòng trực tiếp vào các đích lưu trữ (như S3, Redshift, Elasticsearch); giúp tự động nén, chuyển đổi định dạng dữ liệu mà không cần viết mã xử lý phức tạp.

  > **Ghi chú:** Tuy nhiên, các dịch vụ của Kinesis trên không khả dụng cho các tài khoản free tier nên sẽ không sử dụng vào đề tài

* Biết cách tạo và triển khai database container từ máy hoặc Docker lên AWS thông qua **ECS** và **ECR**. 



