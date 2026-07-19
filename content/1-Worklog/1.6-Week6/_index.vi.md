---
title: "Worklog Tuần 6"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu tuần 6:

* Phát triển logic cốt lõi cho việc tính toán Điểm kinh nghiệm (XP) và tích hợp các bảng DynamoDB nâng cao.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | ------------ | --------------- | --------------- |
| Thứ 2 | Thiết kế hệ thống, Khởi tạo API & Xác định công thức tính XP. | 25/05/2026 | 26/05/2026 | AWS / Git / Jira |
| Thứ 3 | Validate dữ liệu & Xử lý lỗi (Error Handling). | 26/05/2026 | 27/05/2026 | AWS / Git / Jira |
| Thứ 4 | Viết Core Logic - Tính toán XP & Cập nhật trạng thái. | 27/05/2026 | 28/05/2026 | GitHub / AWS |
| Thứ 5 | Tích hợp DynamoDB (Phần 1 - ChildProfiles). | 28/05/2026 | 29/05/2026 | GitHub / AWS |
| Thứ 6 | Tích hợp DynamoDB (Phần 2 - ActivityHistory & DailyActivities). | 29/05/2026 | 30/05/2026 | GitHub / AWS |
| Thứ 7 | Ghép nối API (API Assembly) & Kiểm thử với Postman (Postman Test Flow). | 30/05/2026 | 31/05/2026 | GitHub / Postman |
| Chủ Nhật | Rà soát Tiêu chí nghiệm thu (Acceptance Criteria) & Refactor. | 31/05/2026 | 01/06/2026 |  |

### Kết quả đạt được tuần 6:

* Xây dựng và triển khai chuẩn xác logic backend cho việc tự động tính toán XP và cập nhật trạng thái.
* Mở rộng hạ tầng cơ sở dữ liệu để xử lý các tương tác phức tạp, có tính liên kết chặt chẽ giữa các bảng ChildProfiles, ActivityHistory và DailyActivities.
* Refactor mã nguồn nhằm đảm bảo tính ổn định sau quá trình kiểm thử nghiêm ngặt bằng Postman và rà soát chặt chẽ theo các tiêu chí nghiệm thu.