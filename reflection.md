# Individual reflection — Bùi Cao Chinh (2A202600001)

## 1. Role

Data Engineer. Phụ trách crawl data từ vinmec và tạo mock data

## 2. Đóng góp cụ thể

- Crawl data từ website của vinmec (<https://vinmec.com>)
  - Data danh sách cơ sở bệnh viện của Vinmec
  - Data danh sách các khoa của các bệnh viện
  - Data danh sách bác sĩ trong khoa
  - Tạo data lịch khám
  - Tạo data các triệu chứng red flags (mức độ nghiêm trọng cao, cần cấp cứu ngay)

## 3. Đóng góp khác

- Hỗ trợ các bạn các công việc để nhóm hoàn thành nhanh hơn (VD: github, ...)

## 4. Điều học được

- Các ứng dụng AI nên có UX đơn giản. VD: Khi chat với LLM thì nên làm tính năng để người dùng có thể tương tác chọn khi đang chat thay vì tạo luồng mới.
- Khi tích hợp cần có fallback để phòng khi AI không trả lời được sẽ chuyển sang tổng đài viên hoặc chăm sóc khách hàng.

## 5. Nếu làm lại

- Sẽ sửa đổi khi cảnh báo những biểu hiện nguy hiểm thì có thể gọi ngay cho cứu thương báo vị trí người có biểu hiện vì đây là trường hợp khẩn cấp cần cấp cứu ngay

## 6. AI giúp gì / AI sai gì

- **Giúp:** dùng Antigravity để brainstorm việc crawl data khi đã biết API từ website -> gen code crawl và chạy
- **Sai/mislead:** gợi ý thêm feature "gợi ý thuốc" vào chatbot —
  nhưng over scope cho hackathon.
Bài học: AI brainstorm tốt nhưng không biết giới hạn scope.
