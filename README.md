# [Vận dụng cơ bản 1] Sửa đổi prompt thiếu cấu trúc ràng buộc định dạng
### Bước 1: Phân tích lỗi
1	Lời chào xã giao: "Xin chào, mình rất vui được hỗ trợ bạn!" -	Không cần thiết.
2	Lời dẫn dài: "Trước tiên, chúng ta hãy cùng tìm hiểu..." -	Làm câu trả lời dài dòng.
3	Lời kết: "Hy vọng những thông tin trên sẽ giúp ích cho bạn!" -	Không bổ sung kiến thức.

Bước 2: Viết prompt tối ưu

```Prompt đã sửa:
Hãy giải thích ngắn gọn hai nội dung sau:
1. Feynman Prompt gia sư.
2. Rubric chấm bài tự động.
Yêu cầu đầu ra:
- Trình bày bằng gạch đầu dòng.
- Mỗi nội dung tối đa 3 dòng.
- Sử dụng ngôn ngữ đơn giản, dễ hiểu.
- Không viết lời chào, lời dẫn hoặc lời kết.
- Chỉ cung cấp nội dung chính, không giải thích lan man.
```

Bước 3: Kết quả phản hồi của AI
1. Feynman Prompt gia sư
- Là phương pháp yêu cầu AI giải thích kiến thức bằng ngôn ngữ đơn giản như đang dạy cho người mới bắt đầu.
- Giúp người học hiểu sâu và phát hiện những phần kiến thức chưa nắm vững.
2. Rubric chấm bài tự động
- Là bảng tiêu chí đánh giá bài làm theo các mức điểm cụ thể.
- Giúp AI chấm bài nhất quán, khách quan và đưa ra nhận xét theo từng tiêu chí.
