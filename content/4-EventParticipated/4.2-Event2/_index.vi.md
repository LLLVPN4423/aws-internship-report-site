---
title: "Event 2"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 4.2. </b> "
---

{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}

# Bài thu hoạch “FCAJ Community Day”

### Mục Đích Của Sự Kiện

- Chia sẻ các ứng dụng thực tiễn của AI trong phát triển phần mềm và hệ thống doanh nghiệp.
- Giới thiệu cách xây dựng các ứng dụng AI hiệu quả bằng cách tận dụng ngữ cảnh (context).
- Cập nhật các dịch vụ AI và công nghệ Cloud hiện đại của AWS.
- Chia sẻ kinh nghiệm thực tế trong quá trình xây dựng các sản phẩm và hệ thống ứng dụng AI.

### Danh Sách Diễn Giả

- **Bảo Huỳnh** – Docker - A containerization technology
- **Lê Hoàng Gia Đại** – Combining AWS WAF with Machine Learning for Cyber Attack Detection on AWS
- **Nguyễn Quốc Bảo** – Topic: Multiplayer in the Cloud: Connecting Godot Clients with AWS WebSockets
- **Trương Huy Phước** – Topic: Cách làm việc nhóm hiệu quả
- **Việt Phát** – Topic: AWS Neptune for Building a Graph Knowledge Base for GraphRAG
- **Vinh Trần** – Topic: Từ IT Helpdesk lên Senior Sysadmin: Hành trình tự học và Lộ trình dịch chuyển sang Cloud/DevOps

### Những điểm nhấn chính

#### Docker - A containerization technology
- Nhấn mạnh giá trị cốt lõi của Docker: đóng gói ứng dụng cùng mọi thư viện phụ thuộc để đảm bảo chạy đồng nhất trên nhiều môi trường ("build once, run anywhere").
- Làm rõ sự khác biệt giữa Máy ảo (nặng nề, khởi động chậm, chạy hệ điều hành riêng) và Container (nhẹ, khởi động siêu tốc, dùng chung nhân hệ điều hành máy chủ).
- Nêu bật các lợi ích to lớn của container hóa, bao gồm tính di động cao, sự nhất quán trong vận hành, tối ưu hóa tài nguyên và tiết kiệm chi phí hạ tầng.

#### Combining AWS WAF with Machine Learning for Cyber Attack Detection on AWS
- Chỉ ra những hạn chế của WAF dựa trên luật (rule-based) truyền thống trong việc phát hiện các cuộc tấn công mới/zero-day và các hành vi bất thường.
- Đề xuất Hệ thống phát hiện xâm nhập mạng (NIDS) dựa trên Machine Learning như một lớp phòng thủ chủ động hoạt động song song với AWS WAF.
- Chi tiết hóa quá trình xây dựng mô hình ML bằng tập dữ liệu CSE-CIC-IDS2018, từ làm sạch dữ liệu, cân bằng lớp (class balancing), đến việc đánh giá các mô hình như LightGBM.
- Trình diễn kiến trúc triển khai NIDS trên AWS, tích hợp với Dashboard thời gian thực để trực quan hóa các cuộc tấn công và tự động chặn IP.

#### Topic: Multiplayer in the Cloud: Connecting Godot Clients with AWS WebSockets
- So sánh các kiến trúc mạng multiplayer (UDP, HTTP Polling) và khẳng định AWS WebSockets là lựa chọn tối ưu cho giao tiếp hai chiều theo thời gian thực.
- Trình bày kiến trúc AWS có khả năng mở rộng sử dụng API Gateway cho kết nối WebSocket, Lambda để xử lý logic game, và DynamoDB để lưu trạng thái người chơi.
- Hướng dẫn cách tích hợp vào game engine Godot, từ việc quản lý kết nối, quét gói tin (poll packets), đến đồng bộ trạng thái game giữa các người chơi.

#### Topic: Cách làm việc nhóm hiệu quả
- Chỉ ra "4 Nguyên tắc Vàng" để nhóm thành công: Mục tiêu chung rõ ràng, Đúng người - Đúng việc, Giao tiếp cởi mở & Lắng nghe tích cực, và Trách nhiệm cá nhân.
- Nhấn mạnh quá trình chuyển đổi từ "Hiệu suất cá nhân" sang "Hiệu suất làm việc nhóm" để đạt được các mục tiêu dự án lớn.
- Giới thiệu các công cụ số thiết yếu cho việc cộng tác hiện đại, bao gồm Trello và ClickUp để theo dõi tiến độ, cùng Slack, Discord, và Google Workspace để giao tiếp trơn tru.

#### Topic: AWS Neptune for Building a Graph Knowledge Base for GraphRAG
- Giải thích cách RAG cung cấp kiến thức nền cho LLM, đồng thời giới thiệu GraphRAG để khắc phục nhược điểm của RAG truyền thống trong việc suy luận đa bước (multi-hop reasoning).
- Trình diễn hai phương pháp triển khai: sử dụng giải pháp được quản lý hoàn toàn (Amazon Bedrock Knowledge Bases + Neptune Analytics) và giải pháp tùy chỉnh mã nguồn mở (LlamaIndex).
- Nêu bật lợi thế của cơ sở dữ liệu đồ thị (Neptune) trong việc lưu trữ và truy xuất rõ ràng các mối quan hệ phức tạp, giúp tăng độ chính xác ngữ cảnh cho AI.

#### Topic: Từ IT Helpdesk lên Senior Sysadmin: Hành trình tự học và Lộ trình dịch chuyển sang Cloud/DevOps
- Chia sẻ lộ trình thăng tiến thực tế từ IT Helpdesk (kỹ năng giao tiếp, xử lý sự cố) lên Quản trị hệ thống (Linux, Mạng, Hạ tầng).
- Nhấn mạnh "Tư duy Vận hành": tự động hóa các tác vụ lặp đi lặp lại, viết tài liệu cấu hình, và nguyên tắc vàng "không bao giờ test trực tiếp trên môi trường production".
- Vạch ra lộ trình DevOps hiện đại, chuyển dịch từ quản lý máy chủ vật lý sang Điện toán đám mây, Quản lý hạ tầng bằng mã lệnh (Terraform), và thiết lập CI/CD.

### Những bài học rút ra

- **Container hóa là tiêu chuẩn:** Tính linh hoạt và nhẹ bén của Docker khiến nó trở thành công cụ bắt buộc trong phát triển phần mềm, vượt trội hoàn toàn so với máy ảo truyền thống.
- **Bảo mật AI là điều kiện tiên quyết:** Các bộ luật WAF tĩnh cần được bổ sung bằng Machine Learning (NIDS) để chủ động phát hiện và ngăn chặn các rủi ro an ninh mạng khó lường.
- **Serverless giải quyết bài toán mở rộng game:** Sự kết hợp giữa AWS WebSockets, Lambda và DynamoDB mang lại một backend mạnh mẽ, dễ mở rộng cho game multiplayer mà không cần quản lý máy chủ vật lý.
- **GraphRAG mang lại ngữ cảnh sâu sắc:** Sử dụng AWS Neptune để xây dựng bản đồ quan hệ thực thể giúp LLM có khả năng suy luận logic phức tạp mà các hệ thống RAG dựa trên vector thông thường không làm được.
- **Làm việc nhóm cần sự rõ ràng và công cụ hỗ trợ:** Sự cộng tác hiệu quả đòi hỏi các thành viên phải chia sẻ chung mục tiêu, có trách nhiệm cá nhân, và được hỗ trợ bởi các công cụ quản lý như ClickUp hay Discord.
- **Tự học quyết định sự nghiệp:** Hành trình từ Helpdesk lên Cloud/DevOps đòi hỏi việc liên tục thực hành dự án thực tế, nắm vững công nghệ lõi (Linux, Network) và một tư duy vận hành hệ thống nhạy bén.

#### Một số hình ảnh tại sự kiện
*Add your event photos here*  

> Tóm lại, "FCAJ Community Day" là một sự kiện xuất sắc, mang lại những góc nhìn kỹ thuật chuyên sâu qua nhiều lĩnh vực của điện toán đám mây và phát triển phần mềm. Từ sự chuyển dịch nền tảng sang Docker và DevOps, đến những ứng dụng thực tiễn của Machine Learning trong bảo mật AWS WAF và kiến trúc GraphRAG, nội dung các phiên trình bày đều có tính ứng dụng rất cao. Việc học cách tối ưu hệ thống backend cho game bằng WebSocket hay lắng nghe những câu chuyện thăng tiến sự nghiệp truyền cảm hứng đã củng cố thêm niềm tin rằng: thành công trong ngành IT đòi hỏi sự kết hợp chặt chẽ giữa tinh thần tự học, kỹ năng làm việc nhóm hiệu quả, và việc không ngừng cập nhật các công nghệ cloud tiên tiến nhất.