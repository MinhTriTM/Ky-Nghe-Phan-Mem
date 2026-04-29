# Câu hỏi:
giúp tôi hoàn thiện prompr cho juler thực hiện nó: Tạo ra file markdown ngân hàng đề cho môn kỹ nghệ phần mềm, mỗi chương bao gồm khoảng 25 câu đến 150 câu hỏi trả hời tự luận ngắn, tương tự "dang de thi knpm.md", ngoài ra mỗi chương có khoảng 200 đến 500 câu hỏi trắc nghiệm A B C D. chương 1 thì tên file là chương 1.md, chương 2 thì chương 2.md nhớ ghi vào @Mục Tiêu.txt

# Suy nghĩ (Thinking):
- Người dùng cần tôi tạo một prompt hoàn chỉnh cho agent khác (Juler) để tự động tạo ngân hàng câu hỏi môn Kỹ nghệ phần mềm.
- Các yêu cầu cần có trong prompt:
  + File xuất ra dưới dạng Markdown.
  + Mỗi chương một file, tên file format: `chương 1.md`, `chương 2.md`,...
  + Phần tự luận ngắn: 25-150 câu, format giống file mẫu `dang de thi knpm.md`.
  + Phần trắc nghiệm: 200-500 câu, có 4 đáp án A, B, C, D và có đáp án đúng.
- Tôi đã kiểm tra file `dang de thi knpm.md` để hiểu cách ra đề tự luận ngắn (hỏi trực diện khái niệm, đặc điểm, quy trình...).
- Tôi cần lưu toàn bộ prompt đã tối ưu vào file `Mục Tiêu.txt` như yêu cầu.
- Tôi sẽ sử dụng tiếng Việt trong mọi báo cáo và thao tác theo đúng vai trò Giám Đốc B.

# Câu trả lời:
Tôi đã hoàn thiện prompt chi tiết, rõ ràng và đã lưu trực tiếp vào file `Mục Tiêu.txt`. Bạn có thể gửi file này hoặc copy nội dung trong đó đưa cho Juler để agent đó hiểu chính xác cấu trúc file cần tạo, số lượng câu hỏi cũng như cách chia nhỏ tác vụ để tránh lỗi do vượt quá giới hạn độ dài của một lần sinh văn bản.