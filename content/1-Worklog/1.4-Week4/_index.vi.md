---
title: "Worklog Tuần 4"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu tuần 4:

* Thiết lập môi trường Cloud trên Local và khởi tạo kiến trúc dự án sử dụng Docker và FastAPI.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | ------------ | --------------- | --------------- |
| Thứ 2 | Nghiên cứu kiến trúc FastAPI/AWS và lập giải pháp giả lập môi trường Cloud trên Local. | 11/05/2026 | 12/05/2026 | Google |
| Thứ 3 | Khởi tạo cấu trúc dự án và xây dựng Dockerfile tối ưu (bật Hot-reload, tối ưu log). | 12/05/2026 | 13/05/2026 | Docker |
| Thứ 4 | Thiết lập docker-compose.yml, tích hợp container DynamoDB Local và cấu hình Port Mapping. | 13/05/2026 | 14/05/2026 | AWS / Docker |
| Thứ 5 | Cấu hình Docker Networking (kết nối nội bộ) và Docker Volumes (lưu trữ dữ liệu DB bền vững). | 14/05/2026 | 15/05/2026 | GitHub / Jira |
| Thứ 6 | Thiết lập quản lý biến môi trường (.env.local) và cấu hình cơ chế ánh xạ AWS Credentials an toàn. | 15/05/2026 | 16/05/2026 | GitHub / AWS |
| Thứ 7 | Viết mã nguồn kết nối (bằng boto3), kiểm thử tính năng Hot-reload và fix bug kết nối giữa các container. | 16/05/2026 | 17/05/2026 | AWS / GitHub |
| Chủ Nhật | Tối ưu hóa dung lượng Image, cấu hình .gitignore bảo mật và đóng gói tài liệu kỹ thuật. | 17/05/2026 | 18/05/2026 | GitHub / AWS |

### Kết quả đạt được tuần 4:

* Xây dựng thành công môi trường container hóa (containerized) trên Local, giả lập hiệu quả các dịch vụ AWS thông qua FastAPI.
* Cấu hình các thiết lập Docker nâng cao bao gồm custom networking, volumes và tích hợp mượt mà với DynamoDB Local.
* Triển khai cấu hình môi trường bảo mật và thiết lập kết nối thành công giữa các container sử dụng thư viện boto3.