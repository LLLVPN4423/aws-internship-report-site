---
title: "Worklog Tuần 8"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu tuần 8:

* Giảm thiểu sự cố gián đoạn môi trường cloud nghiêm trọng bằng cách chuyển đổi (migrate) hạ tầng AWS và xử lý các vấn đề về IAM.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | ------------ | --------------- | --------------- |
| Thứ 2 | Phân tích sự cố API ngừng phản hồi, xác định nguyên nhân cốt lõi do tài khoản AWS chính đã hết Free Credit. | 08/06/2026 | 09/06/2026 | GitHub / AWS |
| Thứ 3 | Thiết lập tài khoản AWS mới, khởi tạo lại môi trường Cloud và cấu hình các quyền IAM cơ bản. | 09/06/2026 | 10/06/2026 | GitHub / AWS / Jira |
| Thứ 4 | Chuyển đổi (migrate) tài nguyên hạ tầng, cập nhật biến môi trường và Credentials bảo mật sang tài khoản AWS mới. | 10/06/2026 | 11/06/2026 | GitHub / AWS |
| Thứ 5 | Debug và khắc phục các lỗi phân quyền truy cập (Access Denied) giữa các dịch vụ (services) trên môi trường AWS mới. | 11/06/2026 | 12/06/2026 | GitHub / AWS |
| Thứ 6 | Cấu hình lại kết nối mạng và khắc phục các sự cố liên quan đến kết nối DynamoDB trên tài khoản mới. | 12/06/2026 | 13/06/2026 | GitHub / AWS |
| Thứ 7 | Chạy kiểm thử toàn diện (End-to-End Test) trên hạ tầng mới để đảm bảo tính ổn định và bảo mật của API. | 13/06/2026 | 14/06/2026 | GitHub / AWS |
| Chủ Nhật | Bàn giao hệ thống đã ổn định cho team Frontend và cập nhật tài liệu liên quan đến các thay đổi về endpoint. | 14/06/2026 | 15/06/2026 | GitHub / AWS / docs |

### Kết quả đạt được tuần 8:

* Khôi phục nhanh chóng khỏi sự cố giới hạn credit bằng cách migrate thành công toàn bộ hạ tầng backend sang thiết lập AWS mới.
* Cấu hình chuẩn xác các quyền IAM và giao thức mạng, loại bỏ hoàn toàn các lỗi Access Denied trong quá trình runtime.
* Ổn định và bàn giao lại các API an toàn, đã được kiểm thử toàn diện cho team Frontend mà không gây ra thời gian gián đoạn (downtime) kéo dài.