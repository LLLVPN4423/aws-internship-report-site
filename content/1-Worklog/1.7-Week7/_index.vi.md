---
title: "Worklog Tuần 7"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7:

* Thực hiện debug toàn diện, giải quyết các vấn đề đồng bộ trạng thái (state synchronization) và đảm bảo tích hợp Frontend mượt mà.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | ------------ | --------------- | --------------- |
| Thứ 2 | Rà soát system log và tái hiện lại các lỗi logic (bugs) phát sinh từ các API POST `/child-profiles` và POST `/mini-game/complete`. | 01/06/2026 | 02/06/2026 | GitHub / AWS / Postman |
| Thứ 3 | Debug và khắc phục các lỗi cập nhật sai trạng thái (state) về XP, level và chuỗi ngày (streak) trong DynamoDB. | 02/06/2026 | 03/06/2026 | GitHub / AWS |
| Thứ 4 | Phối hợp với team Frontend để tích hợp API, xử lý các lỗi sai lệch định dạng (JSON schema mismatches) giữa Request và Response. | 03/06/2026 | 04/06/2026 | GitHub / AWS |
| Thứ 5 | Gỡ lỗi (troubleshoot) vấn đề không đồng bộ trạng thái nhân vật trên App UI sau khi gọi API hoàn thành mini-game. | 04/06/2026 | 05/06/2026 | GitHub / AWS / Figma |
| Thứ 6 | Chạy Regression Test luồng dữ liệu hai chiều Backend - Frontend, đảm bảo dữ liệu ghi nhận chính xác và phản hồi theo thời gian thực (real-time). | 05/06/2026 | 06/06/2026 | GitHub / AWS / Figma |
| Thứ 7 | Lên văn phòng công ty tham dự sự kiện giao lưu và chia sẻ kiến thức nội bộ. | 06/06/2026 | 07/06/2026 |  |
| Chủ Nhật | Viết technical docs tổng hợp các lỗi tích hợp đã khắc phục và refactor mã nguồn (codebase) sau khi ghép nối thành công. | 07/06/2026 | 08/06/2026 | docs |

### Kết quả đạt được tuần 7:

* Xác định và loại bỏ các lỗi logic (bugs) nghiêm trọng liên quan đến tính toán XP, theo dõi level và chuỗi ngày (streak) của người dùng.
* Đồng bộ hoàn hảo với kiến trúc Frontend, giải quyết sự cố sai lệch JSON payload và khắc phục các điểm không đồng bộ trên UI theo thời gian thực.
* Thực thi Regression Test kỹ lưỡng