---
title: "Worklog Tuần 9"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.9. </b> "
---


### Mục tiêu tuần 9:

* Hoàn thiện các tính năng của dự án, kiểm thử và tích hợp.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | ------------ | --------------- | --------------- |
| Thứ 2 | Hỗ trợ Frontend thiết kế luồng tích hợp cho API POST `/ai-camera/analyze`. Lên ý tưởng giao diện (UI) Loading State với mascot hoạt hình. | 15/06/2026 | 16/06/2026 | GitHub / Figma |
| Thứ 3 | Tư vấn logic xử lý dữ liệu hình ảnh (Capture/Upload) và cách đóng gói `multipart/form-data` an toàn. Hướng dẫn FE trích xuất `childId`. | 16/06/2026 | 17/06/2026 | GitHub |
| Thứ 4 | Hỗ trợ FE xử lý logic Error Handling. Ánh xạ các kịch bản lỗi tiêu chuẩn (thiếu ảnh, server error) thành các thông báo chính xác trên UI. | 17/06/2026 | 18/06/2026 | GitHub / Figma |
| Thứ 5 | Hỗ trợ ánh xạ dữ liệu (Data Mapping) từ Backend Response (label, confidence, binColor) sang màn hình kết quả (Result Screen). Xác thực tính hợp lệ của các S3 URLs trả về. | 18/06/2026 | 19/06/2026 | GitHub |
| Thứ 6 | Hỗ trợ FE render động các thẻ nội dung giáo dục (Recycling Guide, Reuse Suggestion, Environmental Impact) dựa trên JSON response. | 19/06/2026 | 20/06/2026 | GitHub / Figma |
| Thứ 7 | Nghiên cứu và đề xuất tích hợp Web Speech API cho tính năng Mascot Voice. Xây dựng logic tự động ghép chuỗi văn bản để đọc kết quả. | 20/06/2026 | 21/06/2026 | GitHub / Jira |
| Chủ Nhật | Phối hợp với team Frontend chạy kiểm thử toàn diện (End-to-End testing) mọi tính năng AI Camera. Khắc phục các lỗi CORS và sự sai lệch định dạng payload. | 21/06/2026 | 22/06/2026 | GitHub / Figma |

### Kết quả đạt được tuần 9:

* Tích hợp mượt mà các API AI Camera phức tạp, tạo điều kiện thuận lợi cho quy trình upload ảnh ổn định và tích hợp S3 thành công.
* Thiết kế logic tự động chuyển đổi văn bản thành giọng nói (text-to-speech) sử dụng Web Speech API nhằm mang lại trải nghiệm giáo dục mang tính tương tác.
* Đảm bảo tính chính xác của dữ liệu và hệ thống mapping lỗi chặt chẽ cho toàn bộ các component giáo dục động trên frontend.