# CHƯƠNG 6: LẬP TRÌNH

## PHẦN 1: Câu hỏi tự luận ngắn

1. **Khái niệm lập trình phần mềm là gì?**
   *Gợi ý:* Là quá trình chuyển đổi các bản thiết kế phần mềm thành các dòng mã lệnh (code) có thể thực thi được bởi máy tính.
2. **Một sản phẩm phần mềm tốt phụ thuộc vào những yếu tố nào?**
   *Gợi ý:* Phân tích tốt, Thiết kế tốt, Lập trình tốt (ổn định, hiệu quả) và Kiểm thử chặt chẽ.
3. **Thế nào là lập trình hiệu quả?**
   *Gợi ý:* Lập trình hiệu quả mang lại tốc độ phát triển cao (dễ tái sử dụng), dễ bảo trì (dễ hiểu, dễ sửa lỗi) và chất lượng cao (an toàn, ổn định).
4. **Phương pháp lập trình không cấu trúc (Unstructured Programming) có đặc điểm gì?**
   *Gợi ý:* Mã nguồn được viết thành một chuỗi liên tục, sử dụng lệnh `goto` để điều khiển luồng, dễ dẫn đến mã "spaghetti", khó hiểu và khó bảo trì.
5. **Đặc điểm nổi bật của lập trình có cấu trúc (Structured Programming) là gì?**
   *Gợi ý:* Chương trình được tổ chức thành các khối lệnh (block) và sử dụng các cấu trúc điều khiển cơ bản như tuần tự (Sequence), chọn lựa (Selection/If), và lặp (Iteration/Loop) thay vì dùng `goto`.
6. **Phương pháp lập trình thủ tục (Procedural Programming) cải tiến thế nào so với lập trình có cấu trúc?**
   *Gợi ý:* Kế thừa cấu trúc, nhưng chia chương trình thành các hàm/thủ tục (functions/procedures) nhỏ hơn để tái sử dụng mã và quản lý dễ dàng hơn.
7. **Khái niệm cốt lõi của lập trình hướng đối tượng (OOP) là gì?**
   *Gợi ý:* Dựa trên khái niệm "Đối tượng" (Object), bao gồm cả dữ liệu (thuộc tính) và hành vi (phương thức).
8. **Bốn tính chất cơ bản của lập trình hướng đối tượng (OOP) là gì?**
   *Gợi ý:* Đóng gói (Encapsulation), Kế thừa (Inheritance), Đa hình (Polymorphism) và Trừu tượng (Abstraction).
9. **Kể tên một số ngôn ngữ lập trình phổ biến hiện nay?**
   *Gợi ý:* Python, Java, C++, C#, JavaScript, PHP.
10. **Trình biên dịch (Compiler) khác với Trình thông dịch (Interpreter) ở điểm nào?**
    *Gợi ý:* Compiler dịch toàn bộ mã nguồn sang mã máy một lần rồi mới chạy, trong khi Interpreter dịch và chạy từng dòng mã một.
11. **Phong cách lập trình (Programming Style) là gì?**
    *Gợi ý:* Là các quy tắc, chuẩn mực và thói quen mà lập trình viên áp dụng khi viết mã (ví dụ: cách đặt tên biến, cách thụt lề, comment) để mã dễ đọc và bảo trì.
12. **Tại sao việc tuân thủ quy ước đặt tên (Naming convention) lại quan trọng?**
    *Gợi ý:* Giúp mã nguồn rõ ràng, tự giải thích (self-documenting), những người khác trong đội ngũ (hoặc chính tác giả sau này) dễ dàng hiểu được biến hay hàm đó dùng để làm gì.
13. **Quy tắc CamelCase là gì?**
    *Gợi ý:* Từ đầu tiên viết thường, chữ cái đầu của các từ tiếp theo viết hoa (VD: `myVariableName`).
14. **PascalCase thường được dùng để đặt tên cho loại thành phần nào trong OOP (ví dụ trong C# hoặc Java)?**
    *Gợi ý:* Thường dùng để đặt tên Lớp (Class), Interface hoặc Phương thức (Method) (VD: `CustomerRecord`).
15. **Mục đích của việc viết chú thích (Comment) trong mã nguồn là gì?**
    *Gợi ý:* Để giải thích tại sao một đoạn code được viết theo cách đó, hoặc để mô tả những logic phức tạp, giúp người bảo trì sau này hiểu rõ ngữ cảnh.
16. **"Code Smell" là thuật ngữ dùng để chỉ điều gì?**
    *Gợi ý:* Là các dấu hiệu bề mặt trong mã nguồn cho thấy có thể có những vấn đề sâu hơn về thiết kế, vi phạm nguyên tắc lập trình tốt (VD: một hàm quá dài, mã lặp lại nhiều lần).
17. **Refactoring (Tái cấu trúc mã) là quá trình gì?**
    *Gợi ý:* Quá trình cấu trúc lại mã nguồn hiện tại nhằm cải thiện tính dễ đọc và giảm bớt độ phức tạp mà không làm thay đổi hành vi bên ngoài của phần mềm.
18. **Nguyên tắc DRY (Don't Repeat Yourself) khuyến cáo điều gì?**
    *Gợi ý:* Mọi phần kiến thức, logic phải có một định nghĩa duy nhất và rõ ràng trong hệ thống. Khuyên lập trình viên nên sử dụng hàm/lớp thay vì copy-paste code nhiều lần.
19. **KISS (Keep It Simple, Stupid) là nguyên tắc nhấn mạnh yếu tố nào khi lập trình?**
    *Gợi ý:* Nhấn mạnh sự đơn giản. Các hệ thống hoạt động tốt nhất khi chúng đơn giản thay vì phức tạp một cách không cần thiết.
20. **Lỗi cú pháp (Syntax error) là gì?**
    *Gợi ý:* Lỗi xảy ra khi người lập trình viết sai quy tắc ngữ pháp của ngôn ngữ lập trình, khiến trình biên dịch/thông dịch không thể hiểu và báo lỗi ngay lập tức.
21. **Lỗi logic (Logical error) nguy hiểm hơn lỗi cú pháp ở chỗ nào?**
    *Gợi ý:* Chương trình vẫn biên dịch và chạy bình thường, nhưng kết quả xử lý sai. Nó khó phát hiện hơn và thường chỉ bộc lộ khi người dùng thực tế thao tác hoặc trong quá trình kiểm thử.
22. **Debug (Gỡ lỗi) là hoạt động gì?**
    *Gợi ý:* Quá trình định vị, phân tích và sửa chữa các lỗi (bugs) trong phần mềm.
23. **Framework (Khung làm việc) khác với Library (Thư viện) như thế nào về "Inversion of Control"?**
    *Gợi ý:* Thư viện là tập hợp mã do bạn chủ động gọi để thực hiện một tác vụ. Framework cung cấp cấu trúc hệ thống và nó là bên "gọi" mã của bạn tại những thời điểm thích hợp (Inversion of Control).
24. **Một IDE (Integrated Development Environment) cung cấp các công cụ chính nào?**
    *Gợi ý:* Trình soạn thảo văn bản (Code Editor), Trình biên dịch/Thông dịch (Compiler/Interpreter), Trình gỡ lỗi (Debugger), và các công cụ hỗ trợ như tự động hoàn thành mã (Auto-completion).
25. **Kiểm soát phiên bản (Version Control - VD: Git) đóng vai trò gì trong quá trình lập trình nhóm?**
    *Gợi ý:* Giúp theo dõi lịch sử thay đổi của mã nguồn, cho phép nhiều người cùng làm việc trên một dự án mà không bị ghi đè dữ liệu, và hỗ trợ hoàn tác khi xảy ra lỗi.


## PHẦN 2: Câu hỏi trắc nghiệm

**Câu 1:** Đặc trưng chính của phương pháp lập trình không cấu trúc (Unstructured Programming) là gì?
A. Chia chương trình thành nhiều lớp và đối tượng.
B. Sử dụng lệnh GOTO để nhảy tới các nhãn, khiến luồng điều khiển rối rắm.
C. Tập trung vào giao diện đồ họa.
D. Không cần viết mã nguồn, chỉ cần kéo thả.
*Đáp án: B*

**Câu 2:** Lập trình có cấu trúc (Structured Programming) dựa trên những cấu trúc điều khiển cơ bản nào?
A. Tuần tự (Sequence), Lựa chọn (Selection), Lặp (Iteration).
B. Đối tượng (Object), Lớp (Class), Kế thừa (Inheritance).
C. GOTO, JUMP, RETURN.
D. Biến toàn cục, Con trỏ, Tham chiếu.
*Đáp án: A*

**Câu 3:** Ưu điểm của phương pháp lập trình thủ tục (Procedural) so với lập trình khối là gì?
A. Khó bảo trì hơn.
B. Có thể chia nhỏ chương trình thành các hàm (functions) để tái sử dụng.
C. Mã nguồn chỉ chạy được trên một hệ điều hành duy nhất.
D. Chương trình chỉ có một luồng thực thi duy nhất từ trên xuống dưới không thể tái sử dụng.
*Đáp án: B*

**Câu 4:** Tính Đóng gói (Encapsulation) trong OOP có ý nghĩa gì?
A. Viết tất cả các lớp trong cùng một file vật lý.
B. Nén mã nguồn lại thành file ZIP trước khi biên dịch.
C. Che giấu thông tin nội bộ của đối tượng và chỉ giao tiếp qua các phương thức được cho phép.
D. Tái sử dụng lại toàn bộ mã của một lớp khác.
*Đáp án: C*

**Câu 5:** Khái niệm Kế thừa (Inheritance) trong lập trình hướng đối tượng cho phép điều gì?
A. Một lớp có thể nhận lại các thuộc tính và phương thức từ một lớp khác, giúp tái sử dụng mã.
B. Xóa bỏ các phương thức của lớp cha.
C. Đóng gói dữ liệu an toàn hơn.
D. Thay đổi kiểu dữ liệu của biến linh hoạt.
*Đáp án: A*

**Câu 6:** Tính Đa hình (Polymorphism) thể hiện đặc điểm nào?
A. Một đối tượng có thể bị xóa bằng nhiều cách.
B. Cùng một phương thức nhưng có thể thực hiện những hành động khác nhau tùy thuộc vào đối tượng gọi nó.
C. Chương trình có thể chạy trên nhiều hệ điều hành.
D. Một lớp có nhiều tên gọi khác nhau.
*Đáp án: B*

**Câu 7:** Tại sao việc duy trì một Phong cách lập trình (Programming Style) nhất quán là quan trọng?
A. Làm cho chương trình chạy nhanh hơn gấp đôi.
B. Giúp mã nguồn dễ đọc, dễ hiểu và dễ bảo trì, đặc biệt khi làm việc nhóm.
C. Trình biên dịch bắt buộc phải có phong cách mới dịch được.
D. Giảm dung lượng file mã nguồn.
*Đáp án: B*

**Câu 8:** Quy tắc đặt tên CamelCase là như thế nào?
A. Viet_Hoa_Tung_Chu_Cai.
B. chu_cai_thuong_co_gach_duoi.
C. tuDauTienVietThuongCacTuTiepTheoVietHoaChuCaiDau.
D. VIET_HOA_TOAN_BO.
*Đáp án: C*

**Câu 9:** Theo nguyên tắc viết mã tốt, khi nào nên sử dụng Chú thích (Comment)?
A. Giải thích MỌI dòng code, kể cả những dòng gán giá trị đơn giản.
B. Khi muốn tắt một đoạn code không muốn chạy.
C. Để giải thích TẠI SAO một đoạn mã được viết như vậy, nhất là đối với logic phức tạp.
D. Chỉ để ghi tên tác giả.
*Đáp án: C*

**Câu 10:** Nguyên tắc DRY (Don't Repeat Yourself) nghĩa là gì?
A. Không sử dụng vòng lặp trong chương trình.
B. Không sao chép và dán (copy-paste) cùng một đoạn mã nhiều lần, mà nên dùng hàm hoặc lớp để tái sử dụng.
C. Không bao giờ viết lại code của người khác.
D. Không chạy chương trình hai lần.
*Đáp án: B*

**Câu 11:** Loại lỗi nào khiến chương trình không thể biên dịch thành công?
A. Lỗi Logic.
B. Lỗi Cú pháp (Syntax error).
C. Lỗi Runtime.
D. Lỗi Giao diện.
*Đáp án: B*

**Câu 12:** Đặc điểm của lỗi Logic (Logical error) là gì?
A. Trình biên dịch báo lỗi ngay khi vừa viết xong code.
B. Xảy ra do thiếu dấu chấm phẩy hoặc viết sai từ khóa.
C. Chương trình vẫn chạy nhưng kết quả tính toán hoặc hoạt động không đúng như mong đợi.
D. Làm máy tính bị treo ngay lập tức.
*Đáp án: C*

**Câu 13:** Quá trình Debug là gì?
A. Xóa toàn bộ mã nguồn để viết lại từ đầu.
B. Tối ưu hóa thuật toán để chạy nhanh hơn.
C. Quá trình tìm kiếm, xác định nguyên nhân và sửa chữa các lỗi trong chương trình.
D. Thiết kế giao diện đồ họa.
*Đáp án: C*

**Câu 14:** Đặc trưng chính của phương pháp lập trình không cấu trúc (Unstructured Programming) là gì?
A. Chia chương trình thành nhiều lớp và đối tượng.
B. Sử dụng lệnh GOTO để nhảy tới các nhãn, khiến luồng điều khiển rối rắm.
C. Tập trung vào giao diện đồ họa.
D. Không cần viết mã nguồn, chỉ cần kéo thả.
*Đáp án: B*

**Câu 15:** Lập trình có cấu trúc (Structured Programming) dựa trên những cấu trúc điều khiển cơ bản nào?
A. Tuần tự (Sequence), Lựa chọn (Selection), Lặp (Iteration).
B. Đối tượng (Object), Lớp (Class), Kế thừa (Inheritance).
C. GOTO, JUMP, RETURN.
D. Biến toàn cục, Con trỏ, Tham chiếu.
*Đáp án: A*

**Câu 16:** Ưu điểm của phương pháp lập trình thủ tục (Procedural) so với lập trình khối là gì?
A. Khó bảo trì hơn.
B. Có thể chia nhỏ chương trình thành các hàm (functions) để tái sử dụng.
C. Mã nguồn chỉ chạy được trên một hệ điều hành duy nhất.
D. Chương trình chỉ có một luồng thực thi duy nhất từ trên xuống dưới không thể tái sử dụng.
*Đáp án: B*

**Câu 17:** Tính Đóng gói (Encapsulation) trong OOP có ý nghĩa gì?
A. Viết tất cả các lớp trong cùng một file vật lý.
B. Nén mã nguồn lại thành file ZIP trước khi biên dịch.
C. Che giấu thông tin nội bộ của đối tượng và chỉ giao tiếp qua các phương thức được cho phép.
D. Tái sử dụng lại toàn bộ mã của một lớp khác.
*Đáp án: C*

**Câu 18:** Khái niệm Kế thừa (Inheritance) trong lập trình hướng đối tượng cho phép điều gì?
A. Một lớp có thể nhận lại các thuộc tính và phương thức từ một lớp khác, giúp tái sử dụng mã.
B. Xóa bỏ các phương thức của lớp cha.
C. Đóng gói dữ liệu an toàn hơn.
D. Thay đổi kiểu dữ liệu của biến linh hoạt.
*Đáp án: A*

**Câu 19:** Tính Đa hình (Polymorphism) thể hiện đặc điểm nào?
A. Một đối tượng có thể bị xóa bằng nhiều cách.
B. Cùng một phương thức nhưng có thể thực hiện những hành động khác nhau tùy thuộc vào đối tượng gọi nó.
C. Chương trình có thể chạy trên nhiều hệ điều hành.
D. Một lớp có nhiều tên gọi khác nhau.
*Đáp án: B*

**Câu 20:** Tại sao việc duy trì một Phong cách lập trình (Programming Style) nhất quán là quan trọng?
A. Làm cho chương trình chạy nhanh hơn gấp đôi.
B. Giúp mã nguồn dễ đọc, dễ hiểu và dễ bảo trì, đặc biệt khi làm việc nhóm.
C. Trình biên dịch bắt buộc phải có phong cách mới dịch được.
D. Giảm dung lượng file mã nguồn.
*Đáp án: B*

**Câu 21:** Quy tắc đặt tên CamelCase là như thế nào?
A. Viet_Hoa_Tung_Chu_Cai.
B. chu_cai_thuong_co_gach_duoi.
C. tuDauTienVietThuongCacTuTiepTheoVietHoaChuCaiDau.
D. VIET_HOA_TOAN_BO.
*Đáp án: C*

**Câu 22:** Theo nguyên tắc viết mã tốt, khi nào nên sử dụng Chú thích (Comment)?
A. Giải thích MỌI dòng code, kể cả những dòng gán giá trị đơn giản.
B. Khi muốn tắt một đoạn code không muốn chạy.
C. Để giải thích TẠI SAO một đoạn mã được viết như vậy, nhất là đối với logic phức tạp.
D. Chỉ để ghi tên tác giả.
*Đáp án: C*

**Câu 23:** Nguyên tắc DRY (Don't Repeat Yourself) nghĩa là gì?
A. Không sử dụng vòng lặp trong chương trình.
B. Không sao chép và dán (copy-paste) cùng một đoạn mã nhiều lần, mà nên dùng hàm hoặc lớp để tái sử dụng.
C. Không bao giờ viết lại code của người khác.
D. Không chạy chương trình hai lần.
*Đáp án: B*

**Câu 24:** Loại lỗi nào khiến chương trình không thể biên dịch thành công?
A. Lỗi Logic.
B. Lỗi Cú pháp (Syntax error).
C. Lỗi Runtime.
D. Lỗi Giao diện.
*Đáp án: B*

**Câu 25:** Đặc điểm của lỗi Logic (Logical error) là gì?
A. Trình biên dịch báo lỗi ngay khi vừa viết xong code.
B. Xảy ra do thiếu dấu chấm phẩy hoặc viết sai từ khóa.
C. Chương trình vẫn chạy nhưng kết quả tính toán hoặc hoạt động không đúng như mong đợi.
D. Làm máy tính bị treo ngay lập tức.
*Đáp án: C*

**Câu 26:** Quá trình Debug là gì?
A. Xóa toàn bộ mã nguồn để viết lại từ đầu.
B. Tối ưu hóa thuật toán để chạy nhanh hơn.
C. Quá trình tìm kiếm, xác định nguyên nhân và sửa chữa các lỗi trong chương trình.
D. Thiết kế giao diện đồ họa.
*Đáp án: C*

**Câu 27:** Đặc trưng chính của phương pháp lập trình không cấu trúc (Unstructured Programming) là gì?
A. Chia chương trình thành nhiều lớp và đối tượng.
B. Sử dụng lệnh GOTO để nhảy tới các nhãn, khiến luồng điều khiển rối rắm.
C. Tập trung vào giao diện đồ họa.
D. Không cần viết mã nguồn, chỉ cần kéo thả.
*Đáp án: B*

**Câu 28:** Lập trình có cấu trúc (Structured Programming) dựa trên những cấu trúc điều khiển cơ bản nào?
A. Tuần tự (Sequence), Lựa chọn (Selection), Lặp (Iteration).
B. Đối tượng (Object), Lớp (Class), Kế thừa (Inheritance).
C. GOTO, JUMP, RETURN.
D. Biến toàn cục, Con trỏ, Tham chiếu.
*Đáp án: A*

**Câu 29:** Ưu điểm của phương pháp lập trình thủ tục (Procedural) so với lập trình khối là gì?
A. Khó bảo trì hơn.
B. Có thể chia nhỏ chương trình thành các hàm (functions) để tái sử dụng.
C. Mã nguồn chỉ chạy được trên một hệ điều hành duy nhất.
D. Chương trình chỉ có một luồng thực thi duy nhất từ trên xuống dưới không thể tái sử dụng.
*Đáp án: B*

**Câu 30:** Tính Đóng gói (Encapsulation) trong OOP có ý nghĩa gì?
A. Viết tất cả các lớp trong cùng một file vật lý.
B. Nén mã nguồn lại thành file ZIP trước khi biên dịch.
C. Che giấu thông tin nội bộ của đối tượng và chỉ giao tiếp qua các phương thức được cho phép.
D. Tái sử dụng lại toàn bộ mã của một lớp khác.
*Đáp án: C*

**Câu 31:** Khái niệm Kế thừa (Inheritance) trong lập trình hướng đối tượng cho phép điều gì?
A. Một lớp có thể nhận lại các thuộc tính và phương thức từ một lớp khác, giúp tái sử dụng mã.
B. Xóa bỏ các phương thức của lớp cha.
C. Đóng gói dữ liệu an toàn hơn.
D. Thay đổi kiểu dữ liệu của biến linh hoạt.
*Đáp án: A*

**Câu 32:** Tính Đa hình (Polymorphism) thể hiện đặc điểm nào?
A. Một đối tượng có thể bị xóa bằng nhiều cách.
B. Cùng một phương thức nhưng có thể thực hiện những hành động khác nhau tùy thuộc vào đối tượng gọi nó.
C. Chương trình có thể chạy trên nhiều hệ điều hành.
D. Một lớp có nhiều tên gọi khác nhau.
*Đáp án: B*

**Câu 33:** Tại sao việc duy trì một Phong cách lập trình (Programming Style) nhất quán là quan trọng?
A. Làm cho chương trình chạy nhanh hơn gấp đôi.
B. Giúp mã nguồn dễ đọc, dễ hiểu và dễ bảo trì, đặc biệt khi làm việc nhóm.
C. Trình biên dịch bắt buộc phải có phong cách mới dịch được.
D. Giảm dung lượng file mã nguồn.
*Đáp án: B*

**Câu 34:** Quy tắc đặt tên CamelCase là như thế nào?
A. Viet_Hoa_Tung_Chu_Cai.
B. chu_cai_thuong_co_gach_duoi.
C. tuDauTienVietThuongCacTuTiepTheoVietHoaChuCaiDau.
D. VIET_HOA_TOAN_BO.
*Đáp án: C*

**Câu 35:** Theo nguyên tắc viết mã tốt, khi nào nên sử dụng Chú thích (Comment)?
A. Giải thích MỌI dòng code, kể cả những dòng gán giá trị đơn giản.
B. Khi muốn tắt một đoạn code không muốn chạy.
C. Để giải thích TẠI SAO một đoạn mã được viết như vậy, nhất là đối với logic phức tạp.
D. Chỉ để ghi tên tác giả.
*Đáp án: C*

**Câu 36:** Nguyên tắc DRY (Don't Repeat Yourself) nghĩa là gì?
A. Không sử dụng vòng lặp trong chương trình.
B. Không sao chép và dán (copy-paste) cùng một đoạn mã nhiều lần, mà nên dùng hàm hoặc lớp để tái sử dụng.
C. Không bao giờ viết lại code của người khác.
D. Không chạy chương trình hai lần.
*Đáp án: B*

**Câu 37:** Loại lỗi nào khiến chương trình không thể biên dịch thành công?
A. Lỗi Logic.
B. Lỗi Cú pháp (Syntax error).
C. Lỗi Runtime.
D. Lỗi Giao diện.
*Đáp án: B*

**Câu 38:** Đặc điểm của lỗi Logic (Logical error) là gì?
A. Trình biên dịch báo lỗi ngay khi vừa viết xong code.
B. Xảy ra do thiếu dấu chấm phẩy hoặc viết sai từ khóa.
C. Chương trình vẫn chạy nhưng kết quả tính toán hoặc hoạt động không đúng như mong đợi.
D. Làm máy tính bị treo ngay lập tức.
*Đáp án: C*

**Câu 39:** Quá trình Debug là gì?
A. Xóa toàn bộ mã nguồn để viết lại từ đầu.
B. Tối ưu hóa thuật toán để chạy nhanh hơn.
C. Quá trình tìm kiếm, xác định nguyên nhân và sửa chữa các lỗi trong chương trình.
D. Thiết kế giao diện đồ họa.
*Đáp án: C*

**Câu 40:** Đặc trưng chính của phương pháp lập trình không cấu trúc (Unstructured Programming) là gì?
A. Chia chương trình thành nhiều lớp và đối tượng.
B. Sử dụng lệnh GOTO để nhảy tới các nhãn, khiến luồng điều khiển rối rắm.
C. Tập trung vào giao diện đồ họa.
D. Không cần viết mã nguồn, chỉ cần kéo thả.
*Đáp án: B*

**Câu 41:** Lập trình có cấu trúc (Structured Programming) dựa trên những cấu trúc điều khiển cơ bản nào?
A. Tuần tự (Sequence), Lựa chọn (Selection), Lặp (Iteration).
B. Đối tượng (Object), Lớp (Class), Kế thừa (Inheritance).
C. GOTO, JUMP, RETURN.
D. Biến toàn cục, Con trỏ, Tham chiếu.
*Đáp án: A*

**Câu 42:** Ưu điểm của phương pháp lập trình thủ tục (Procedural) so với lập trình khối là gì?
A. Khó bảo trì hơn.
B. Có thể chia nhỏ chương trình thành các hàm (functions) để tái sử dụng.
C. Mã nguồn chỉ chạy được trên một hệ điều hành duy nhất.
D. Chương trình chỉ có một luồng thực thi duy nhất từ trên xuống dưới không thể tái sử dụng.
*Đáp án: B*

**Câu 43:** Tính Đóng gói (Encapsulation) trong OOP có ý nghĩa gì?
A. Viết tất cả các lớp trong cùng một file vật lý.
B. Nén mã nguồn lại thành file ZIP trước khi biên dịch.
C. Che giấu thông tin nội bộ của đối tượng và chỉ giao tiếp qua các phương thức được cho phép.
D. Tái sử dụng lại toàn bộ mã của một lớp khác.
*Đáp án: C*

**Câu 44:** Khái niệm Kế thừa (Inheritance) trong lập trình hướng đối tượng cho phép điều gì?
A. Một lớp có thể nhận lại các thuộc tính và phương thức từ một lớp khác, giúp tái sử dụng mã.
B. Xóa bỏ các phương thức của lớp cha.
C. Đóng gói dữ liệu an toàn hơn.
D. Thay đổi kiểu dữ liệu của biến linh hoạt.
*Đáp án: A*

**Câu 45:** Tính Đa hình (Polymorphism) thể hiện đặc điểm nào?
A. Một đối tượng có thể bị xóa bằng nhiều cách.
B. Cùng một phương thức nhưng có thể thực hiện những hành động khác nhau tùy thuộc vào đối tượng gọi nó.
C. Chương trình có thể chạy trên nhiều hệ điều hành.
D. Một lớp có nhiều tên gọi khác nhau.
*Đáp án: B*

**Câu 46:** Tại sao việc duy trì một Phong cách lập trình (Programming Style) nhất quán là quan trọng?
A. Làm cho chương trình chạy nhanh hơn gấp đôi.
B. Giúp mã nguồn dễ đọc, dễ hiểu và dễ bảo trì, đặc biệt khi làm việc nhóm.
C. Trình biên dịch bắt buộc phải có phong cách mới dịch được.
D. Giảm dung lượng file mã nguồn.
*Đáp án: B*

**Câu 47:** Quy tắc đặt tên CamelCase là như thế nào?
A. Viet_Hoa_Tung_Chu_Cai.
B. chu_cai_thuong_co_gach_duoi.
C. tuDauTienVietThuongCacTuTiepTheoVietHoaChuCaiDau.
D. VIET_HOA_TOAN_BO.
*Đáp án: C*

**Câu 48:** Theo nguyên tắc viết mã tốt, khi nào nên sử dụng Chú thích (Comment)?
A. Giải thích MỌI dòng code, kể cả những dòng gán giá trị đơn giản.
B. Khi muốn tắt một đoạn code không muốn chạy.
C. Để giải thích TẠI SAO một đoạn mã được viết như vậy, nhất là đối với logic phức tạp.
D. Chỉ để ghi tên tác giả.
*Đáp án: C*

**Câu 49:** Nguyên tắc DRY (Don't Repeat Yourself) nghĩa là gì?
A. Không sử dụng vòng lặp trong chương trình.
B. Không sao chép và dán (copy-paste) cùng một đoạn mã nhiều lần, mà nên dùng hàm hoặc lớp để tái sử dụng.
C. Không bao giờ viết lại code của người khác.
D. Không chạy chương trình hai lần.
*Đáp án: B*

**Câu 50:** Loại lỗi nào khiến chương trình không thể biên dịch thành công?
A. Lỗi Logic.
B. Lỗi Cú pháp (Syntax error).
C. Lỗi Runtime.
D. Lỗi Giao diện.
*Đáp án: B*

**Câu 51:** Đặc điểm của lỗi Logic (Logical error) là gì?
A. Trình biên dịch báo lỗi ngay khi vừa viết xong code.
B. Xảy ra do thiếu dấu chấm phẩy hoặc viết sai từ khóa.
C. Chương trình vẫn chạy nhưng kết quả tính toán hoặc hoạt động không đúng như mong đợi.
D. Làm máy tính bị treo ngay lập tức.
*Đáp án: C*

**Câu 52:** Quá trình Debug là gì?
A. Xóa toàn bộ mã nguồn để viết lại từ đầu.
B. Tối ưu hóa thuật toán để chạy nhanh hơn.
C. Quá trình tìm kiếm, xác định nguyên nhân và sửa chữa các lỗi trong chương trình.
D. Thiết kế giao diện đồ họa.
*Đáp án: C*

**Câu 53:** Đặc trưng chính của phương pháp lập trình không cấu trúc (Unstructured Programming) là gì?
A. Chia chương trình thành nhiều lớp và đối tượng.
B. Sử dụng lệnh GOTO để nhảy tới các nhãn, khiến luồng điều khiển rối rắm.
C. Tập trung vào giao diện đồ họa.
D. Không cần viết mã nguồn, chỉ cần kéo thả.
*Đáp án: B*

**Câu 54:** Lập trình có cấu trúc (Structured Programming) dựa trên những cấu trúc điều khiển cơ bản nào?
A. Tuần tự (Sequence), Lựa chọn (Selection), Lặp (Iteration).
B. Đối tượng (Object), Lớp (Class), Kế thừa (Inheritance).
C. GOTO, JUMP, RETURN.
D. Biến toàn cục, Con trỏ, Tham chiếu.
*Đáp án: A*

**Câu 55:** Ưu điểm của phương pháp lập trình thủ tục (Procedural) so với lập trình khối là gì?
A. Khó bảo trì hơn.
B. Có thể chia nhỏ chương trình thành các hàm (functions) để tái sử dụng.
C. Mã nguồn chỉ chạy được trên một hệ điều hành duy nhất.
D. Chương trình chỉ có một luồng thực thi duy nhất từ trên xuống dưới không thể tái sử dụng.
*Đáp án: B*

**Câu 56:** Tính Đóng gói (Encapsulation) trong OOP có ý nghĩa gì?
A. Viết tất cả các lớp trong cùng một file vật lý.
B. Nén mã nguồn lại thành file ZIP trước khi biên dịch.
C. Che giấu thông tin nội bộ của đối tượng và chỉ giao tiếp qua các phương thức được cho phép.
D. Tái sử dụng lại toàn bộ mã của một lớp khác.
*Đáp án: C*

**Câu 57:** Khái niệm Kế thừa (Inheritance) trong lập trình hướng đối tượng cho phép điều gì?
A. Một lớp có thể nhận lại các thuộc tính và phương thức từ một lớp khác, giúp tái sử dụng mã.
B. Xóa bỏ các phương thức của lớp cha.
C. Đóng gói dữ liệu an toàn hơn.
D. Thay đổi kiểu dữ liệu của biến linh hoạt.
*Đáp án: A*

**Câu 58:** Tính Đa hình (Polymorphism) thể hiện đặc điểm nào?
A. Một đối tượng có thể bị xóa bằng nhiều cách.
B. Cùng một phương thức nhưng có thể thực hiện những hành động khác nhau tùy thuộc vào đối tượng gọi nó.
C. Chương trình có thể chạy trên nhiều hệ điều hành.
D. Một lớp có nhiều tên gọi khác nhau.
*Đáp án: B*

**Câu 59:** Tại sao việc duy trì một Phong cách lập trình (Programming Style) nhất quán là quan trọng?
A. Làm cho chương trình chạy nhanh hơn gấp đôi.
B. Giúp mã nguồn dễ đọc, dễ hiểu và dễ bảo trì, đặc biệt khi làm việc nhóm.
C. Trình biên dịch bắt buộc phải có phong cách mới dịch được.
D. Giảm dung lượng file mã nguồn.
*Đáp án: B*

**Câu 60:** Quy tắc đặt tên CamelCase là như thế nào?
A. Viet_Hoa_Tung_Chu_Cai.
B. chu_cai_thuong_co_gach_duoi.
C. tuDauTienVietThuongCacTuTiepTheoVietHoaChuCaiDau.
D. VIET_HOA_TOAN_BO.
*Đáp án: C*

**Câu 61:** Theo nguyên tắc viết mã tốt, khi nào nên sử dụng Chú thích (Comment)?
A. Giải thích MỌI dòng code, kể cả những dòng gán giá trị đơn giản.
B. Khi muốn tắt một đoạn code không muốn chạy.
C. Để giải thích TẠI SAO một đoạn mã được viết như vậy, nhất là đối với logic phức tạp.
D. Chỉ để ghi tên tác giả.
*Đáp án: C*

**Câu 62:** Nguyên tắc DRY (Don't Repeat Yourself) nghĩa là gì?
A. Không sử dụng vòng lặp trong chương trình.
B. Không sao chép và dán (copy-paste) cùng một đoạn mã nhiều lần, mà nên dùng hàm hoặc lớp để tái sử dụng.
C. Không bao giờ viết lại code của người khác.
D. Không chạy chương trình hai lần.
*Đáp án: B*

**Câu 63:** Loại lỗi nào khiến chương trình không thể biên dịch thành công?
A. Lỗi Logic.
B. Lỗi Cú pháp (Syntax error).
C. Lỗi Runtime.
D. Lỗi Giao diện.
*Đáp án: B*

**Câu 64:** Đặc điểm của lỗi Logic (Logical error) là gì?
A. Trình biên dịch báo lỗi ngay khi vừa viết xong code.
B. Xảy ra do thiếu dấu chấm phẩy hoặc viết sai từ khóa.
C. Chương trình vẫn chạy nhưng kết quả tính toán hoặc hoạt động không đúng như mong đợi.
D. Làm máy tính bị treo ngay lập tức.
*Đáp án: C*

**Câu 65:** Quá trình Debug là gì?
A. Xóa toàn bộ mã nguồn để viết lại từ đầu.
B. Tối ưu hóa thuật toán để chạy nhanh hơn.
C. Quá trình tìm kiếm, xác định nguyên nhân và sửa chữa các lỗi trong chương trình.
D. Thiết kế giao diện đồ họa.
*Đáp án: C*

**Câu 66:** Đặc trưng chính của phương pháp lập trình không cấu trúc (Unstructured Programming) là gì?
A. Chia chương trình thành nhiều lớp và đối tượng.
B. Sử dụng lệnh GOTO để nhảy tới các nhãn, khiến luồng điều khiển rối rắm.
C. Tập trung vào giao diện đồ họa.
D. Không cần viết mã nguồn, chỉ cần kéo thả.
*Đáp án: B*

**Câu 67:** Lập trình có cấu trúc (Structured Programming) dựa trên những cấu trúc điều khiển cơ bản nào?
A. Tuần tự (Sequence), Lựa chọn (Selection), Lặp (Iteration).
B. Đối tượng (Object), Lớp (Class), Kế thừa (Inheritance).
C. GOTO, JUMP, RETURN.
D. Biến toàn cục, Con trỏ, Tham chiếu.
*Đáp án: A*

**Câu 68:** Ưu điểm của phương pháp lập trình thủ tục (Procedural) so với lập trình khối là gì?
A. Khó bảo trì hơn.
B. Có thể chia nhỏ chương trình thành các hàm (functions) để tái sử dụng.
C. Mã nguồn chỉ chạy được trên một hệ điều hành duy nhất.
D. Chương trình chỉ có một luồng thực thi duy nhất từ trên xuống dưới không thể tái sử dụng.
*Đáp án: B*

**Câu 69:** Tính Đóng gói (Encapsulation) trong OOP có ý nghĩa gì?
A. Viết tất cả các lớp trong cùng một file vật lý.
B. Nén mã nguồn lại thành file ZIP trước khi biên dịch.
C. Che giấu thông tin nội bộ của đối tượng và chỉ giao tiếp qua các phương thức được cho phép.
D. Tái sử dụng lại toàn bộ mã của một lớp khác.
*Đáp án: C*

**Câu 70:** Khái niệm Kế thừa (Inheritance) trong lập trình hướng đối tượng cho phép điều gì?
A. Một lớp có thể nhận lại các thuộc tính và phương thức từ một lớp khác, giúp tái sử dụng mã.
B. Xóa bỏ các phương thức của lớp cha.
C. Đóng gói dữ liệu an toàn hơn.
D. Thay đổi kiểu dữ liệu của biến linh hoạt.
*Đáp án: A*

**Câu 71:** Tính Đa hình (Polymorphism) thể hiện đặc điểm nào?
A. Một đối tượng có thể bị xóa bằng nhiều cách.
B. Cùng một phương thức nhưng có thể thực hiện những hành động khác nhau tùy thuộc vào đối tượng gọi nó.
C. Chương trình có thể chạy trên nhiều hệ điều hành.
D. Một lớp có nhiều tên gọi khác nhau.
*Đáp án: B*

**Câu 72:** Tại sao việc duy trì một Phong cách lập trình (Programming Style) nhất quán là quan trọng?
A. Làm cho chương trình chạy nhanh hơn gấp đôi.
B. Giúp mã nguồn dễ đọc, dễ hiểu và dễ bảo trì, đặc biệt khi làm việc nhóm.
C. Trình biên dịch bắt buộc phải có phong cách mới dịch được.
D. Giảm dung lượng file mã nguồn.
*Đáp án: B*

**Câu 73:** Quy tắc đặt tên CamelCase là như thế nào?
A. Viet_Hoa_Tung_Chu_Cai.
B. chu_cai_thuong_co_gach_duoi.
C. tuDauTienVietThuongCacTuTiepTheoVietHoaChuCaiDau.
D. VIET_HOA_TOAN_BO.
*Đáp án: C*

**Câu 74:** Theo nguyên tắc viết mã tốt, khi nào nên sử dụng Chú thích (Comment)?
A. Giải thích MỌI dòng code, kể cả những dòng gán giá trị đơn giản.
B. Khi muốn tắt một đoạn code không muốn chạy.
C. Để giải thích TẠI SAO một đoạn mã được viết như vậy, nhất là đối với logic phức tạp.
D. Chỉ để ghi tên tác giả.
*Đáp án: C*

**Câu 75:** Nguyên tắc DRY (Don't Repeat Yourself) nghĩa là gì?
A. Không sử dụng vòng lặp trong chương trình.
B. Không sao chép và dán (copy-paste) cùng một đoạn mã nhiều lần, mà nên dùng hàm hoặc lớp để tái sử dụng.
C. Không bao giờ viết lại code của người khác.
D. Không chạy chương trình hai lần.
*Đáp án: B*

**Câu 76:** Loại lỗi nào khiến chương trình không thể biên dịch thành công?
A. Lỗi Logic.
B. Lỗi Cú pháp (Syntax error).
C. Lỗi Runtime.
D. Lỗi Giao diện.
*Đáp án: B*

**Câu 77:** Đặc điểm của lỗi Logic (Logical error) là gì?
A. Trình biên dịch báo lỗi ngay khi vừa viết xong code.
B. Xảy ra do thiếu dấu chấm phẩy hoặc viết sai từ khóa.
C. Chương trình vẫn chạy nhưng kết quả tính toán hoặc hoạt động không đúng như mong đợi.
D. Làm máy tính bị treo ngay lập tức.
*Đáp án: C*

**Câu 78:** Quá trình Debug là gì?
A. Xóa toàn bộ mã nguồn để viết lại từ đầu.
B. Tối ưu hóa thuật toán để chạy nhanh hơn.
C. Quá trình tìm kiếm, xác định nguyên nhân và sửa chữa các lỗi trong chương trình.
D. Thiết kế giao diện đồ họa.
*Đáp án: C*

**Câu 79:** Đặc trưng chính của phương pháp lập trình không cấu trúc (Unstructured Programming) là gì?
A. Chia chương trình thành nhiều lớp và đối tượng.
B. Sử dụng lệnh GOTO để nhảy tới các nhãn, khiến luồng điều khiển rối rắm.
C. Tập trung vào giao diện đồ họa.
D. Không cần viết mã nguồn, chỉ cần kéo thả.
*Đáp án: B*

**Câu 80:** Lập trình có cấu trúc (Structured Programming) dựa trên những cấu trúc điều khiển cơ bản nào?
A. Tuần tự (Sequence), Lựa chọn (Selection), Lặp (Iteration).
B. Đối tượng (Object), Lớp (Class), Kế thừa (Inheritance).
C. GOTO, JUMP, RETURN.
D. Biến toàn cục, Con trỏ, Tham chiếu.
*Đáp án: A*

**Câu 81:** Ưu điểm của phương pháp lập trình thủ tục (Procedural) so với lập trình khối là gì?
A. Khó bảo trì hơn.
B. Có thể chia nhỏ chương trình thành các hàm (functions) để tái sử dụng.
C. Mã nguồn chỉ chạy được trên một hệ điều hành duy nhất.
D. Chương trình chỉ có một luồng thực thi duy nhất từ trên xuống dưới không thể tái sử dụng.
*Đáp án: B*

**Câu 82:** Tính Đóng gói (Encapsulation) trong OOP có ý nghĩa gì?
A. Viết tất cả các lớp trong cùng một file vật lý.
B. Nén mã nguồn lại thành file ZIP trước khi biên dịch.
C. Che giấu thông tin nội bộ của đối tượng và chỉ giao tiếp qua các phương thức được cho phép.
D. Tái sử dụng lại toàn bộ mã của một lớp khác.
*Đáp án: C*

**Câu 83:** Khái niệm Kế thừa (Inheritance) trong lập trình hướng đối tượng cho phép điều gì?
A. Một lớp có thể nhận lại các thuộc tính và phương thức từ một lớp khác, giúp tái sử dụng mã.
B. Xóa bỏ các phương thức của lớp cha.
C. Đóng gói dữ liệu an toàn hơn.
D. Thay đổi kiểu dữ liệu của biến linh hoạt.
*Đáp án: A*

**Câu 84:** Tính Đa hình (Polymorphism) thể hiện đặc điểm nào?
A. Một đối tượng có thể bị xóa bằng nhiều cách.
B. Cùng một phương thức nhưng có thể thực hiện những hành động khác nhau tùy thuộc vào đối tượng gọi nó.
C. Chương trình có thể chạy trên nhiều hệ điều hành.
D. Một lớp có nhiều tên gọi khác nhau.
*Đáp án: B*

**Câu 85:** Tại sao việc duy trì một Phong cách lập trình (Programming Style) nhất quán là quan trọng?
A. Làm cho chương trình chạy nhanh hơn gấp đôi.
B. Giúp mã nguồn dễ đọc, dễ hiểu và dễ bảo trì, đặc biệt khi làm việc nhóm.
C. Trình biên dịch bắt buộc phải có phong cách mới dịch được.
D. Giảm dung lượng file mã nguồn.
*Đáp án: B*

**Câu 86:** Quy tắc đặt tên CamelCase là như thế nào?
A. Viet_Hoa_Tung_Chu_Cai.
B. chu_cai_thuong_co_gach_duoi.
C. tuDauTienVietThuongCacTuTiepTheoVietHoaChuCaiDau.
D. VIET_HOA_TOAN_BO.
*Đáp án: C*

**Câu 87:** Theo nguyên tắc viết mã tốt, khi nào nên sử dụng Chú thích (Comment)?
A. Giải thích MỌI dòng code, kể cả những dòng gán giá trị đơn giản.
B. Khi muốn tắt một đoạn code không muốn chạy.
C. Để giải thích TẠI SAO một đoạn mã được viết như vậy, nhất là đối với logic phức tạp.
D. Chỉ để ghi tên tác giả.
*Đáp án: C*

**Câu 88:** Nguyên tắc DRY (Don't Repeat Yourself) nghĩa là gì?
A. Không sử dụng vòng lặp trong chương trình.
B. Không sao chép và dán (copy-paste) cùng một đoạn mã nhiều lần, mà nên dùng hàm hoặc lớp để tái sử dụng.
C. Không bao giờ viết lại code của người khác.
D. Không chạy chương trình hai lần.
*Đáp án: B*

**Câu 89:** Loại lỗi nào khiến chương trình không thể biên dịch thành công?
A. Lỗi Logic.
B. Lỗi Cú pháp (Syntax error).
C. Lỗi Runtime.
D. Lỗi Giao diện.
*Đáp án: B*

**Câu 90:** Đặc điểm của lỗi Logic (Logical error) là gì?
A. Trình biên dịch báo lỗi ngay khi vừa viết xong code.
B. Xảy ra do thiếu dấu chấm phẩy hoặc viết sai từ khóa.
C. Chương trình vẫn chạy nhưng kết quả tính toán hoặc hoạt động không đúng như mong đợi.
D. Làm máy tính bị treo ngay lập tức.
*Đáp án: C*

**Câu 91:** Quá trình Debug là gì?
A. Xóa toàn bộ mã nguồn để viết lại từ đầu.
B. Tối ưu hóa thuật toán để chạy nhanh hơn.
C. Quá trình tìm kiếm, xác định nguyên nhân và sửa chữa các lỗi trong chương trình.
D. Thiết kế giao diện đồ họa.
*Đáp án: C*

**Câu 92:** Đặc trưng chính của phương pháp lập trình không cấu trúc (Unstructured Programming) là gì?
A. Chia chương trình thành nhiều lớp và đối tượng.
B. Sử dụng lệnh GOTO để nhảy tới các nhãn, khiến luồng điều khiển rối rắm.
C. Tập trung vào giao diện đồ họa.
D. Không cần viết mã nguồn, chỉ cần kéo thả.
*Đáp án: B*

**Câu 93:** Lập trình có cấu trúc (Structured Programming) dựa trên những cấu trúc điều khiển cơ bản nào?
A. Tuần tự (Sequence), Lựa chọn (Selection), Lặp (Iteration).
B. Đối tượng (Object), Lớp (Class), Kế thừa (Inheritance).
C. GOTO, JUMP, RETURN.
D. Biến toàn cục, Con trỏ, Tham chiếu.
*Đáp án: A*

**Câu 94:** Ưu điểm của phương pháp lập trình thủ tục (Procedural) so với lập trình khối là gì?
A. Khó bảo trì hơn.
B. Có thể chia nhỏ chương trình thành các hàm (functions) để tái sử dụng.
C. Mã nguồn chỉ chạy được trên một hệ điều hành duy nhất.
D. Chương trình chỉ có một luồng thực thi duy nhất từ trên xuống dưới không thể tái sử dụng.
*Đáp án: B*

**Câu 95:** Tính Đóng gói (Encapsulation) trong OOP có ý nghĩa gì?
A. Viết tất cả các lớp trong cùng một file vật lý.
B. Nén mã nguồn lại thành file ZIP trước khi biên dịch.
C. Che giấu thông tin nội bộ của đối tượng và chỉ giao tiếp qua các phương thức được cho phép.
D. Tái sử dụng lại toàn bộ mã của một lớp khác.
*Đáp án: C*

**Câu 96:** Khái niệm Kế thừa (Inheritance) trong lập trình hướng đối tượng cho phép điều gì?
A. Một lớp có thể nhận lại các thuộc tính và phương thức từ một lớp khác, giúp tái sử dụng mã.
B. Xóa bỏ các phương thức của lớp cha.
C. Đóng gói dữ liệu an toàn hơn.
D. Thay đổi kiểu dữ liệu của biến linh hoạt.
*Đáp án: A*

**Câu 97:** Tính Đa hình (Polymorphism) thể hiện đặc điểm nào?
A. Một đối tượng có thể bị xóa bằng nhiều cách.
B. Cùng một phương thức nhưng có thể thực hiện những hành động khác nhau tùy thuộc vào đối tượng gọi nó.
C. Chương trình có thể chạy trên nhiều hệ điều hành.
D. Một lớp có nhiều tên gọi khác nhau.
*Đáp án: B*

**Câu 98:** Tại sao việc duy trì một Phong cách lập trình (Programming Style) nhất quán là quan trọng?
A. Làm cho chương trình chạy nhanh hơn gấp đôi.
B. Giúp mã nguồn dễ đọc, dễ hiểu và dễ bảo trì, đặc biệt khi làm việc nhóm.
C. Trình biên dịch bắt buộc phải có phong cách mới dịch được.
D. Giảm dung lượng file mã nguồn.
*Đáp án: B*

**Câu 99:** Quy tắc đặt tên CamelCase là như thế nào?
A. Viet_Hoa_Tung_Chu_Cai.
B. chu_cai_thuong_co_gach_duoi.
C. tuDauTienVietThuongCacTuTiepTheoVietHoaChuCaiDau.
D. VIET_HOA_TOAN_BO.
*Đáp án: C*

**Câu 100:** Theo nguyên tắc viết mã tốt, khi nào nên sử dụng Chú thích (Comment)?
A. Giải thích MỌI dòng code, kể cả những dòng gán giá trị đơn giản.
B. Khi muốn tắt một đoạn code không muốn chạy.
C. Để giải thích TẠI SAO một đoạn mã được viết như vậy, nhất là đối với logic phức tạp.
D. Chỉ để ghi tên tác giả.
*Đáp án: C*

**Câu 101:** Nguyên tắc DRY (Don't Repeat Yourself) nghĩa là gì?
A. Không sử dụng vòng lặp trong chương trình.
B. Không sao chép và dán (copy-paste) cùng một đoạn mã nhiều lần, mà nên dùng hàm hoặc lớp để tái sử dụng.
C. Không bao giờ viết lại code của người khác.
D. Không chạy chương trình hai lần.
*Đáp án: B*

**Câu 102:** Loại lỗi nào khiến chương trình không thể biên dịch thành công?
A. Lỗi Logic.
B. Lỗi Cú pháp (Syntax error).
C. Lỗi Runtime.
D. Lỗi Giao diện.
*Đáp án: B*

**Câu 103:** Đặc điểm của lỗi Logic (Logical error) là gì?
A. Trình biên dịch báo lỗi ngay khi vừa viết xong code.
B. Xảy ra do thiếu dấu chấm phẩy hoặc viết sai từ khóa.
C. Chương trình vẫn chạy nhưng kết quả tính toán hoặc hoạt động không đúng như mong đợi.
D. Làm máy tính bị treo ngay lập tức.
*Đáp án: C*

**Câu 104:** Quá trình Debug là gì?
A. Xóa toàn bộ mã nguồn để viết lại từ đầu.
B. Tối ưu hóa thuật toán để chạy nhanh hơn.
C. Quá trình tìm kiếm, xác định nguyên nhân và sửa chữa các lỗi trong chương trình.
D. Thiết kế giao diện đồ họa.
*Đáp án: C*

**Câu 105:** Đặc trưng chính của phương pháp lập trình không cấu trúc (Unstructured Programming) là gì?
A. Chia chương trình thành nhiều lớp và đối tượng.
B. Sử dụng lệnh GOTO để nhảy tới các nhãn, khiến luồng điều khiển rối rắm.
C. Tập trung vào giao diện đồ họa.
D. Không cần viết mã nguồn, chỉ cần kéo thả.
*Đáp án: B*

**Câu 106:** Lập trình có cấu trúc (Structured Programming) dựa trên những cấu trúc điều khiển cơ bản nào?
A. Tuần tự (Sequence), Lựa chọn (Selection), Lặp (Iteration).
B. Đối tượng (Object), Lớp (Class), Kế thừa (Inheritance).
C. GOTO, JUMP, RETURN.
D. Biến toàn cục, Con trỏ, Tham chiếu.
*Đáp án: A*

**Câu 107:** Ưu điểm của phương pháp lập trình thủ tục (Procedural) so với lập trình khối là gì?
A. Khó bảo trì hơn.
B. Có thể chia nhỏ chương trình thành các hàm (functions) để tái sử dụng.
C. Mã nguồn chỉ chạy được trên một hệ điều hành duy nhất.
D. Chương trình chỉ có một luồng thực thi duy nhất từ trên xuống dưới không thể tái sử dụng.
*Đáp án: B*

**Câu 108:** Tính Đóng gói (Encapsulation) trong OOP có ý nghĩa gì?
A. Viết tất cả các lớp trong cùng một file vật lý.
B. Nén mã nguồn lại thành file ZIP trước khi biên dịch.
C. Che giấu thông tin nội bộ của đối tượng và chỉ giao tiếp qua các phương thức được cho phép.
D. Tái sử dụng lại toàn bộ mã của một lớp khác.
*Đáp án: C*

**Câu 109:** Khái niệm Kế thừa (Inheritance) trong lập trình hướng đối tượng cho phép điều gì?
A. Một lớp có thể nhận lại các thuộc tính và phương thức từ một lớp khác, giúp tái sử dụng mã.
B. Xóa bỏ các phương thức của lớp cha.
C. Đóng gói dữ liệu an toàn hơn.
D. Thay đổi kiểu dữ liệu của biến linh hoạt.
*Đáp án: A*

**Câu 110:** Tính Đa hình (Polymorphism) thể hiện đặc điểm nào?
A. Một đối tượng có thể bị xóa bằng nhiều cách.
B. Cùng một phương thức nhưng có thể thực hiện những hành động khác nhau tùy thuộc vào đối tượng gọi nó.
C. Chương trình có thể chạy trên nhiều hệ điều hành.
D. Một lớp có nhiều tên gọi khác nhau.
*Đáp án: B*

**Câu 111:** Tại sao việc duy trì một Phong cách lập trình (Programming Style) nhất quán là quan trọng?
A. Làm cho chương trình chạy nhanh hơn gấp đôi.
B. Giúp mã nguồn dễ đọc, dễ hiểu và dễ bảo trì, đặc biệt khi làm việc nhóm.
C. Trình biên dịch bắt buộc phải có phong cách mới dịch được.
D. Giảm dung lượng file mã nguồn.
*Đáp án: B*

**Câu 112:** Quy tắc đặt tên CamelCase là như thế nào?
A. Viet_Hoa_Tung_Chu_Cai.
B. chu_cai_thuong_co_gach_duoi.
C. tuDauTienVietThuongCacTuTiepTheoVietHoaChuCaiDau.
D. VIET_HOA_TOAN_BO.
*Đáp án: C*

**Câu 113:** Theo nguyên tắc viết mã tốt, khi nào nên sử dụng Chú thích (Comment)?
A. Giải thích MỌI dòng code, kể cả những dòng gán giá trị đơn giản.
B. Khi muốn tắt một đoạn code không muốn chạy.
C. Để giải thích TẠI SAO một đoạn mã được viết như vậy, nhất là đối với logic phức tạp.
D. Chỉ để ghi tên tác giả.
*Đáp án: C*

**Câu 114:** Nguyên tắc DRY (Don't Repeat Yourself) nghĩa là gì?
A. Không sử dụng vòng lặp trong chương trình.
B. Không sao chép và dán (copy-paste) cùng một đoạn mã nhiều lần, mà nên dùng hàm hoặc lớp để tái sử dụng.
C. Không bao giờ viết lại code của người khác.
D. Không chạy chương trình hai lần.
*Đáp án: B*

**Câu 115:** Loại lỗi nào khiến chương trình không thể biên dịch thành công?
A. Lỗi Logic.
B. Lỗi Cú pháp (Syntax error).
C. Lỗi Runtime.
D. Lỗi Giao diện.
*Đáp án: B*

**Câu 116:** Đặc điểm của lỗi Logic (Logical error) là gì?
A. Trình biên dịch báo lỗi ngay khi vừa viết xong code.
B. Xảy ra do thiếu dấu chấm phẩy hoặc viết sai từ khóa.
C. Chương trình vẫn chạy nhưng kết quả tính toán hoặc hoạt động không đúng như mong đợi.
D. Làm máy tính bị treo ngay lập tức.
*Đáp án: C*

**Câu 117:** Quá trình Debug là gì?
A. Xóa toàn bộ mã nguồn để viết lại từ đầu.
B. Tối ưu hóa thuật toán để chạy nhanh hơn.
C. Quá trình tìm kiếm, xác định nguyên nhân và sửa chữa các lỗi trong chương trình.
D. Thiết kế giao diện đồ họa.
*Đáp án: C*

**Câu 118:** Đặc trưng chính của phương pháp lập trình không cấu trúc (Unstructured Programming) là gì?
A. Chia chương trình thành nhiều lớp và đối tượng.
B. Sử dụng lệnh GOTO để nhảy tới các nhãn, khiến luồng điều khiển rối rắm.
C. Tập trung vào giao diện đồ họa.
D. Không cần viết mã nguồn, chỉ cần kéo thả.
*Đáp án: B*

**Câu 119:** Lập trình có cấu trúc (Structured Programming) dựa trên những cấu trúc điều khiển cơ bản nào?
A. Tuần tự (Sequence), Lựa chọn (Selection), Lặp (Iteration).
B. Đối tượng (Object), Lớp (Class), Kế thừa (Inheritance).
C. GOTO, JUMP, RETURN.
D. Biến toàn cục, Con trỏ, Tham chiếu.
*Đáp án: A*

**Câu 120:** Ưu điểm của phương pháp lập trình thủ tục (Procedural) so với lập trình khối là gì?
A. Khó bảo trì hơn.
B. Có thể chia nhỏ chương trình thành các hàm (functions) để tái sử dụng.
C. Mã nguồn chỉ chạy được trên một hệ điều hành duy nhất.
D. Chương trình chỉ có một luồng thực thi duy nhất từ trên xuống dưới không thể tái sử dụng.
*Đáp án: B*

**Câu 121:** Tính Đóng gói (Encapsulation) trong OOP có ý nghĩa gì?
A. Viết tất cả các lớp trong cùng một file vật lý.
B. Nén mã nguồn lại thành file ZIP trước khi biên dịch.
C. Che giấu thông tin nội bộ của đối tượng và chỉ giao tiếp qua các phương thức được cho phép.
D. Tái sử dụng lại toàn bộ mã của một lớp khác.
*Đáp án: C*

**Câu 122:** Khái niệm Kế thừa (Inheritance) trong lập trình hướng đối tượng cho phép điều gì?
A. Một lớp có thể nhận lại các thuộc tính và phương thức từ một lớp khác, giúp tái sử dụng mã.
B. Xóa bỏ các phương thức của lớp cha.
C. Đóng gói dữ liệu an toàn hơn.
D. Thay đổi kiểu dữ liệu của biến linh hoạt.
*Đáp án: A*

**Câu 123:** Tính Đa hình (Polymorphism) thể hiện đặc điểm nào?
A. Một đối tượng có thể bị xóa bằng nhiều cách.
B. Cùng một phương thức nhưng có thể thực hiện những hành động khác nhau tùy thuộc vào đối tượng gọi nó.
C. Chương trình có thể chạy trên nhiều hệ điều hành.
D. Một lớp có nhiều tên gọi khác nhau.
*Đáp án: B*

**Câu 124:** Tại sao việc duy trì một Phong cách lập trình (Programming Style) nhất quán là quan trọng?
A. Làm cho chương trình chạy nhanh hơn gấp đôi.
B. Giúp mã nguồn dễ đọc, dễ hiểu và dễ bảo trì, đặc biệt khi làm việc nhóm.
C. Trình biên dịch bắt buộc phải có phong cách mới dịch được.
D. Giảm dung lượng file mã nguồn.
*Đáp án: B*

**Câu 125:** Quy tắc đặt tên CamelCase là như thế nào?
A. Viet_Hoa_Tung_Chu_Cai.
B. chu_cai_thuong_co_gach_duoi.
C. tuDauTienVietThuongCacTuTiepTheoVietHoaChuCaiDau.
D. VIET_HOA_TOAN_BO.
*Đáp án: C*

**Câu 126:** Theo nguyên tắc viết mã tốt, khi nào nên sử dụng Chú thích (Comment)?
A. Giải thích MỌI dòng code, kể cả những dòng gán giá trị đơn giản.
B. Khi muốn tắt một đoạn code không muốn chạy.
C. Để giải thích TẠI SAO một đoạn mã được viết như vậy, nhất là đối với logic phức tạp.
D. Chỉ để ghi tên tác giả.
*Đáp án: C*

**Câu 127:** Nguyên tắc DRY (Don't Repeat Yourself) nghĩa là gì?
A. Không sử dụng vòng lặp trong chương trình.
B. Không sao chép và dán (copy-paste) cùng một đoạn mã nhiều lần, mà nên dùng hàm hoặc lớp để tái sử dụng.
C. Không bao giờ viết lại code của người khác.
D. Không chạy chương trình hai lần.
*Đáp án: B*

**Câu 128:** Loại lỗi nào khiến chương trình không thể biên dịch thành công?
A. Lỗi Logic.
B. Lỗi Cú pháp (Syntax error).
C. Lỗi Runtime.
D. Lỗi Giao diện.
*Đáp án: B*

**Câu 129:** Đặc điểm của lỗi Logic (Logical error) là gì?
A. Trình biên dịch báo lỗi ngay khi vừa viết xong code.
B. Xảy ra do thiếu dấu chấm phẩy hoặc viết sai từ khóa.
C. Chương trình vẫn chạy nhưng kết quả tính toán hoặc hoạt động không đúng như mong đợi.
D. Làm máy tính bị treo ngay lập tức.
*Đáp án: C*

**Câu 130:** Quá trình Debug là gì?
A. Xóa toàn bộ mã nguồn để viết lại từ đầu.
B. Tối ưu hóa thuật toán để chạy nhanh hơn.
C. Quá trình tìm kiếm, xác định nguyên nhân và sửa chữa các lỗi trong chương trình.
D. Thiết kế giao diện đồ họa.
*Đáp án: C*

**Câu 131:** Đặc trưng chính của phương pháp lập trình không cấu trúc (Unstructured Programming) là gì?
A. Chia chương trình thành nhiều lớp và đối tượng.
B. Sử dụng lệnh GOTO để nhảy tới các nhãn, khiến luồng điều khiển rối rắm.
C. Tập trung vào giao diện đồ họa.
D. Không cần viết mã nguồn, chỉ cần kéo thả.
*Đáp án: B*

**Câu 132:** Lập trình có cấu trúc (Structured Programming) dựa trên những cấu trúc điều khiển cơ bản nào?
A. Tuần tự (Sequence), Lựa chọn (Selection), Lặp (Iteration).
B. Đối tượng (Object), Lớp (Class), Kế thừa (Inheritance).
C. GOTO, JUMP, RETURN.
D. Biến toàn cục, Con trỏ, Tham chiếu.
*Đáp án: A*

**Câu 133:** Ưu điểm của phương pháp lập trình thủ tục (Procedural) so với lập trình khối là gì?
A. Khó bảo trì hơn.
B. Có thể chia nhỏ chương trình thành các hàm (functions) để tái sử dụng.
C. Mã nguồn chỉ chạy được trên một hệ điều hành duy nhất.
D. Chương trình chỉ có một luồng thực thi duy nhất từ trên xuống dưới không thể tái sử dụng.
*Đáp án: B*

**Câu 134:** Tính Đóng gói (Encapsulation) trong OOP có ý nghĩa gì?
A. Viết tất cả các lớp trong cùng một file vật lý.
B. Nén mã nguồn lại thành file ZIP trước khi biên dịch.
C. Che giấu thông tin nội bộ của đối tượng và chỉ giao tiếp qua các phương thức được cho phép.
D. Tái sử dụng lại toàn bộ mã của một lớp khác.
*Đáp án: C*

**Câu 135:** Khái niệm Kế thừa (Inheritance) trong lập trình hướng đối tượng cho phép điều gì?
A. Một lớp có thể nhận lại các thuộc tính và phương thức từ một lớp khác, giúp tái sử dụng mã.
B. Xóa bỏ các phương thức của lớp cha.
C. Đóng gói dữ liệu an toàn hơn.
D. Thay đổi kiểu dữ liệu của biến linh hoạt.
*Đáp án: A*

**Câu 136:** Tính Đa hình (Polymorphism) thể hiện đặc điểm nào?
A. Một đối tượng có thể bị xóa bằng nhiều cách.
B. Cùng một phương thức nhưng có thể thực hiện những hành động khác nhau tùy thuộc vào đối tượng gọi nó.
C. Chương trình có thể chạy trên nhiều hệ điều hành.
D. Một lớp có nhiều tên gọi khác nhau.
*Đáp án: B*

**Câu 137:** Tại sao việc duy trì một Phong cách lập trình (Programming Style) nhất quán là quan trọng?
A. Làm cho chương trình chạy nhanh hơn gấp đôi.
B. Giúp mã nguồn dễ đọc, dễ hiểu và dễ bảo trì, đặc biệt khi làm việc nhóm.
C. Trình biên dịch bắt buộc phải có phong cách mới dịch được.
D. Giảm dung lượng file mã nguồn.
*Đáp án: B*

**Câu 138:** Quy tắc đặt tên CamelCase là như thế nào?
A. Viet_Hoa_Tung_Chu_Cai.
B. chu_cai_thuong_co_gach_duoi.
C. tuDauTienVietThuongCacTuTiepTheoVietHoaChuCaiDau.
D. VIET_HOA_TOAN_BO.
*Đáp án: C*

**Câu 139:** Theo nguyên tắc viết mã tốt, khi nào nên sử dụng Chú thích (Comment)?
A. Giải thích MỌI dòng code, kể cả những dòng gán giá trị đơn giản.
B. Khi muốn tắt một đoạn code không muốn chạy.
C. Để giải thích TẠI SAO một đoạn mã được viết như vậy, nhất là đối với logic phức tạp.
D. Chỉ để ghi tên tác giả.
*Đáp án: C*

**Câu 140:** Nguyên tắc DRY (Don't Repeat Yourself) nghĩa là gì?
A. Không sử dụng vòng lặp trong chương trình.
B. Không sao chép và dán (copy-paste) cùng một đoạn mã nhiều lần, mà nên dùng hàm hoặc lớp để tái sử dụng.
C. Không bao giờ viết lại code của người khác.
D. Không chạy chương trình hai lần.
*Đáp án: B*

**Câu 141:** Loại lỗi nào khiến chương trình không thể biên dịch thành công?
A. Lỗi Logic.
B. Lỗi Cú pháp (Syntax error).
C. Lỗi Runtime.
D. Lỗi Giao diện.
*Đáp án: B*

**Câu 142:** Đặc điểm của lỗi Logic (Logical error) là gì?
A. Trình biên dịch báo lỗi ngay khi vừa viết xong code.
B. Xảy ra do thiếu dấu chấm phẩy hoặc viết sai từ khóa.
C. Chương trình vẫn chạy nhưng kết quả tính toán hoặc hoạt động không đúng như mong đợi.
D. Làm máy tính bị treo ngay lập tức.
*Đáp án: C*

**Câu 143:** Quá trình Debug là gì?
A. Xóa toàn bộ mã nguồn để viết lại từ đầu.
B. Tối ưu hóa thuật toán để chạy nhanh hơn.
C. Quá trình tìm kiếm, xác định nguyên nhân và sửa chữa các lỗi trong chương trình.
D. Thiết kế giao diện đồ họa.
*Đáp án: C*

**Câu 144:** Đặc trưng chính của phương pháp lập trình không cấu trúc (Unstructured Programming) là gì?
A. Chia chương trình thành nhiều lớp và đối tượng.
B. Sử dụng lệnh GOTO để nhảy tới các nhãn, khiến luồng điều khiển rối rắm.
C. Tập trung vào giao diện đồ họa.
D. Không cần viết mã nguồn, chỉ cần kéo thả.
*Đáp án: B*

**Câu 145:** Lập trình có cấu trúc (Structured Programming) dựa trên những cấu trúc điều khiển cơ bản nào?
A. Tuần tự (Sequence), Lựa chọn (Selection), Lặp (Iteration).
B. Đối tượng (Object), Lớp (Class), Kế thừa (Inheritance).
C. GOTO, JUMP, RETURN.
D. Biến toàn cục, Con trỏ, Tham chiếu.
*Đáp án: A*

**Câu 146:** Ưu điểm của phương pháp lập trình thủ tục (Procedural) so với lập trình khối là gì?
A. Khó bảo trì hơn.
B. Có thể chia nhỏ chương trình thành các hàm (functions) để tái sử dụng.
C. Mã nguồn chỉ chạy được trên một hệ điều hành duy nhất.
D. Chương trình chỉ có một luồng thực thi duy nhất từ trên xuống dưới không thể tái sử dụng.
*Đáp án: B*

**Câu 147:** Tính Đóng gói (Encapsulation) trong OOP có ý nghĩa gì?
A. Viết tất cả các lớp trong cùng một file vật lý.
B. Nén mã nguồn lại thành file ZIP trước khi biên dịch.
C. Che giấu thông tin nội bộ của đối tượng và chỉ giao tiếp qua các phương thức được cho phép.
D. Tái sử dụng lại toàn bộ mã của một lớp khác.
*Đáp án: C*

**Câu 148:** Khái niệm Kế thừa (Inheritance) trong lập trình hướng đối tượng cho phép điều gì?
A. Một lớp có thể nhận lại các thuộc tính và phương thức từ một lớp khác, giúp tái sử dụng mã.
B. Xóa bỏ các phương thức của lớp cha.
C. Đóng gói dữ liệu an toàn hơn.
D. Thay đổi kiểu dữ liệu của biến linh hoạt.
*Đáp án: A*

**Câu 149:** Tính Đa hình (Polymorphism) thể hiện đặc điểm nào?
A. Một đối tượng có thể bị xóa bằng nhiều cách.
B. Cùng một phương thức nhưng có thể thực hiện những hành động khác nhau tùy thuộc vào đối tượng gọi nó.
C. Chương trình có thể chạy trên nhiều hệ điều hành.
D. Một lớp có nhiều tên gọi khác nhau.
*Đáp án: B*

**Câu 150:** Tại sao việc duy trì một Phong cách lập trình (Programming Style) nhất quán là quan trọng?
A. Làm cho chương trình chạy nhanh hơn gấp đôi.
B. Giúp mã nguồn dễ đọc, dễ hiểu và dễ bảo trì, đặc biệt khi làm việc nhóm.
C. Trình biên dịch bắt buộc phải có phong cách mới dịch được.
D. Giảm dung lượng file mã nguồn.
*Đáp án: B*

**Câu 151:** Quy tắc đặt tên CamelCase là như thế nào?
A. Viet_Hoa_Tung_Chu_Cai.
B. chu_cai_thuong_co_gach_duoi.
C. tuDauTienVietThuongCacTuTiepTheoVietHoaChuCaiDau.
D. VIET_HOA_TOAN_BO.
*Đáp án: C*

**Câu 152:** Theo nguyên tắc viết mã tốt, khi nào nên sử dụng Chú thích (Comment)?
A. Giải thích MỌI dòng code, kể cả những dòng gán giá trị đơn giản.
B. Khi muốn tắt một đoạn code không muốn chạy.
C. Để giải thích TẠI SAO một đoạn mã được viết như vậy, nhất là đối với logic phức tạp.
D. Chỉ để ghi tên tác giả.
*Đáp án: C*

**Câu 153:** Nguyên tắc DRY (Don't Repeat Yourself) nghĩa là gì?
A. Không sử dụng vòng lặp trong chương trình.
B. Không sao chép và dán (copy-paste) cùng một đoạn mã nhiều lần, mà nên dùng hàm hoặc lớp để tái sử dụng.
C. Không bao giờ viết lại code của người khác.
D. Không chạy chương trình hai lần.
*Đáp án: B*

**Câu 154:** Loại lỗi nào khiến chương trình không thể biên dịch thành công?
A. Lỗi Logic.
B. Lỗi Cú pháp (Syntax error).
C. Lỗi Runtime.
D. Lỗi Giao diện.
*Đáp án: B*

**Câu 155:** Đặc điểm của lỗi Logic (Logical error) là gì?
A. Trình biên dịch báo lỗi ngay khi vừa viết xong code.
B. Xảy ra do thiếu dấu chấm phẩy hoặc viết sai từ khóa.
C. Chương trình vẫn chạy nhưng kết quả tính toán hoặc hoạt động không đúng như mong đợi.
D. Làm máy tính bị treo ngay lập tức.
*Đáp án: C*

**Câu 156:** Quá trình Debug là gì?
A. Xóa toàn bộ mã nguồn để viết lại từ đầu.
B. Tối ưu hóa thuật toán để chạy nhanh hơn.
C. Quá trình tìm kiếm, xác định nguyên nhân và sửa chữa các lỗi trong chương trình.
D. Thiết kế giao diện đồ họa.
*Đáp án: C*

**Câu 157:** Đặc trưng chính của phương pháp lập trình không cấu trúc (Unstructured Programming) là gì?
A. Chia chương trình thành nhiều lớp và đối tượng.
B. Sử dụng lệnh GOTO để nhảy tới các nhãn, khiến luồng điều khiển rối rắm.
C. Tập trung vào giao diện đồ họa.
D. Không cần viết mã nguồn, chỉ cần kéo thả.
*Đáp án: B*

**Câu 158:** Lập trình có cấu trúc (Structured Programming) dựa trên những cấu trúc điều khiển cơ bản nào?
A. Tuần tự (Sequence), Lựa chọn (Selection), Lặp (Iteration).
B. Đối tượng (Object), Lớp (Class), Kế thừa (Inheritance).
C. GOTO, JUMP, RETURN.
D. Biến toàn cục, Con trỏ, Tham chiếu.
*Đáp án: A*

**Câu 159:** Ưu điểm của phương pháp lập trình thủ tục (Procedural) so với lập trình khối là gì?
A. Khó bảo trì hơn.
B. Có thể chia nhỏ chương trình thành các hàm (functions) để tái sử dụng.
C. Mã nguồn chỉ chạy được trên một hệ điều hành duy nhất.
D. Chương trình chỉ có một luồng thực thi duy nhất từ trên xuống dưới không thể tái sử dụng.
*Đáp án: B*

**Câu 160:** Tính Đóng gói (Encapsulation) trong OOP có ý nghĩa gì?
A. Viết tất cả các lớp trong cùng một file vật lý.
B. Nén mã nguồn lại thành file ZIP trước khi biên dịch.
C. Che giấu thông tin nội bộ của đối tượng và chỉ giao tiếp qua các phương thức được cho phép.
D. Tái sử dụng lại toàn bộ mã của một lớp khác.
*Đáp án: C*

**Câu 161:** Khái niệm Kế thừa (Inheritance) trong lập trình hướng đối tượng cho phép điều gì?
A. Một lớp có thể nhận lại các thuộc tính và phương thức từ một lớp khác, giúp tái sử dụng mã.
B. Xóa bỏ các phương thức của lớp cha.
C. Đóng gói dữ liệu an toàn hơn.
D. Thay đổi kiểu dữ liệu của biến linh hoạt.
*Đáp án: A*

**Câu 162:** Tính Đa hình (Polymorphism) thể hiện đặc điểm nào?
A. Một đối tượng có thể bị xóa bằng nhiều cách.
B. Cùng một phương thức nhưng có thể thực hiện những hành động khác nhau tùy thuộc vào đối tượng gọi nó.
C. Chương trình có thể chạy trên nhiều hệ điều hành.
D. Một lớp có nhiều tên gọi khác nhau.
*Đáp án: B*

**Câu 163:** Tại sao việc duy trì một Phong cách lập trình (Programming Style) nhất quán là quan trọng?
A. Làm cho chương trình chạy nhanh hơn gấp đôi.
B. Giúp mã nguồn dễ đọc, dễ hiểu và dễ bảo trì, đặc biệt khi làm việc nhóm.
C. Trình biên dịch bắt buộc phải có phong cách mới dịch được.
D. Giảm dung lượng file mã nguồn.
*Đáp án: B*

**Câu 164:** Quy tắc đặt tên CamelCase là như thế nào?
A. Viet_Hoa_Tung_Chu_Cai.
B. chu_cai_thuong_co_gach_duoi.
C. tuDauTienVietThuongCacTuTiepTheoVietHoaChuCaiDau.
D. VIET_HOA_TOAN_BO.
*Đáp án: C*

**Câu 165:** Theo nguyên tắc viết mã tốt, khi nào nên sử dụng Chú thích (Comment)?
A. Giải thích MỌI dòng code, kể cả những dòng gán giá trị đơn giản.
B. Khi muốn tắt một đoạn code không muốn chạy.
C. Để giải thích TẠI SAO một đoạn mã được viết như vậy, nhất là đối với logic phức tạp.
D. Chỉ để ghi tên tác giả.
*Đáp án: C*

**Câu 166:** Nguyên tắc DRY (Don't Repeat Yourself) nghĩa là gì?
A. Không sử dụng vòng lặp trong chương trình.
B. Không sao chép và dán (copy-paste) cùng một đoạn mã nhiều lần, mà nên dùng hàm hoặc lớp để tái sử dụng.
C. Không bao giờ viết lại code của người khác.
D. Không chạy chương trình hai lần.
*Đáp án: B*

**Câu 167:** Loại lỗi nào khiến chương trình không thể biên dịch thành công?
A. Lỗi Logic.
B. Lỗi Cú pháp (Syntax error).
C. Lỗi Runtime.
D. Lỗi Giao diện.
*Đáp án: B*

**Câu 168:** Đặc điểm của lỗi Logic (Logical error) là gì?
A. Trình biên dịch báo lỗi ngay khi vừa viết xong code.
B. Xảy ra do thiếu dấu chấm phẩy hoặc viết sai từ khóa.
C. Chương trình vẫn chạy nhưng kết quả tính toán hoặc hoạt động không đúng như mong đợi.
D. Làm máy tính bị treo ngay lập tức.
*Đáp án: C*

**Câu 169:** Quá trình Debug là gì?
A. Xóa toàn bộ mã nguồn để viết lại từ đầu.
B. Tối ưu hóa thuật toán để chạy nhanh hơn.
C. Quá trình tìm kiếm, xác định nguyên nhân và sửa chữa các lỗi trong chương trình.
D. Thiết kế giao diện đồ họa.
*Đáp án: C*

**Câu 170:** Đặc trưng chính của phương pháp lập trình không cấu trúc (Unstructured Programming) là gì?
A. Chia chương trình thành nhiều lớp và đối tượng.
B. Sử dụng lệnh GOTO để nhảy tới các nhãn, khiến luồng điều khiển rối rắm.
C. Tập trung vào giao diện đồ họa.
D. Không cần viết mã nguồn, chỉ cần kéo thả.
*Đáp án: B*

**Câu 171:** Lập trình có cấu trúc (Structured Programming) dựa trên những cấu trúc điều khiển cơ bản nào?
A. Tuần tự (Sequence), Lựa chọn (Selection), Lặp (Iteration).
B. Đối tượng (Object), Lớp (Class), Kế thừa (Inheritance).
C. GOTO, JUMP, RETURN.
D. Biến toàn cục, Con trỏ, Tham chiếu.
*Đáp án: A*

**Câu 172:** Ưu điểm của phương pháp lập trình thủ tục (Procedural) so với lập trình khối là gì?
A. Khó bảo trì hơn.
B. Có thể chia nhỏ chương trình thành các hàm (functions) để tái sử dụng.
C. Mã nguồn chỉ chạy được trên một hệ điều hành duy nhất.
D. Chương trình chỉ có một luồng thực thi duy nhất từ trên xuống dưới không thể tái sử dụng.
*Đáp án: B*

**Câu 173:** Tính Đóng gói (Encapsulation) trong OOP có ý nghĩa gì?
A. Viết tất cả các lớp trong cùng một file vật lý.
B. Nén mã nguồn lại thành file ZIP trước khi biên dịch.
C. Che giấu thông tin nội bộ của đối tượng và chỉ giao tiếp qua các phương thức được cho phép.
D. Tái sử dụng lại toàn bộ mã của một lớp khác.
*Đáp án: C*

**Câu 174:** Khái niệm Kế thừa (Inheritance) trong lập trình hướng đối tượng cho phép điều gì?
A. Một lớp có thể nhận lại các thuộc tính và phương thức từ một lớp khác, giúp tái sử dụng mã.
B. Xóa bỏ các phương thức của lớp cha.
C. Đóng gói dữ liệu an toàn hơn.
D. Thay đổi kiểu dữ liệu của biến linh hoạt.
*Đáp án: A*

**Câu 175:** Tính Đa hình (Polymorphism) thể hiện đặc điểm nào?
A. Một đối tượng có thể bị xóa bằng nhiều cách.
B. Cùng một phương thức nhưng có thể thực hiện những hành động khác nhau tùy thuộc vào đối tượng gọi nó.
C. Chương trình có thể chạy trên nhiều hệ điều hành.
D. Một lớp có nhiều tên gọi khác nhau.
*Đáp án: B*

**Câu 176:** Tại sao việc duy trì một Phong cách lập trình (Programming Style) nhất quán là quan trọng?
A. Làm cho chương trình chạy nhanh hơn gấp đôi.
B. Giúp mã nguồn dễ đọc, dễ hiểu và dễ bảo trì, đặc biệt khi làm việc nhóm.
C. Trình biên dịch bắt buộc phải có phong cách mới dịch được.
D. Giảm dung lượng file mã nguồn.
*Đáp án: B*

**Câu 177:** Quy tắc đặt tên CamelCase là như thế nào?
A. Viet_Hoa_Tung_Chu_Cai.
B. chu_cai_thuong_co_gach_duoi.
C. tuDauTienVietThuongCacTuTiepTheoVietHoaChuCaiDau.
D. VIET_HOA_TOAN_BO.
*Đáp án: C*

**Câu 178:** Theo nguyên tắc viết mã tốt, khi nào nên sử dụng Chú thích (Comment)?
A. Giải thích MỌI dòng code, kể cả những dòng gán giá trị đơn giản.
B. Khi muốn tắt một đoạn code không muốn chạy.
C. Để giải thích TẠI SAO một đoạn mã được viết như vậy, nhất là đối với logic phức tạp.
D. Chỉ để ghi tên tác giả.
*Đáp án: C*

**Câu 179:** Nguyên tắc DRY (Don't Repeat Yourself) nghĩa là gì?
A. Không sử dụng vòng lặp trong chương trình.
B. Không sao chép và dán (copy-paste) cùng một đoạn mã nhiều lần, mà nên dùng hàm hoặc lớp để tái sử dụng.
C. Không bao giờ viết lại code của người khác.
D. Không chạy chương trình hai lần.
*Đáp án: B*

**Câu 180:** Loại lỗi nào khiến chương trình không thể biên dịch thành công?
A. Lỗi Logic.
B. Lỗi Cú pháp (Syntax error).
C. Lỗi Runtime.
D. Lỗi Giao diện.
*Đáp án: B*

**Câu 181:** Đặc điểm của lỗi Logic (Logical error) là gì?
A. Trình biên dịch báo lỗi ngay khi vừa viết xong code.
B. Xảy ra do thiếu dấu chấm phẩy hoặc viết sai từ khóa.
C. Chương trình vẫn chạy nhưng kết quả tính toán hoặc hoạt động không đúng như mong đợi.
D. Làm máy tính bị treo ngay lập tức.
*Đáp án: C*

**Câu 182:** Quá trình Debug là gì?
A. Xóa toàn bộ mã nguồn để viết lại từ đầu.
B. Tối ưu hóa thuật toán để chạy nhanh hơn.
C. Quá trình tìm kiếm, xác định nguyên nhân và sửa chữa các lỗi trong chương trình.
D. Thiết kế giao diện đồ họa.
*Đáp án: C*

**Câu 183:** Đặc trưng chính của phương pháp lập trình không cấu trúc (Unstructured Programming) là gì?
A. Chia chương trình thành nhiều lớp và đối tượng.
B. Sử dụng lệnh GOTO để nhảy tới các nhãn, khiến luồng điều khiển rối rắm.
C. Tập trung vào giao diện đồ họa.
D. Không cần viết mã nguồn, chỉ cần kéo thả.
*Đáp án: B*

**Câu 184:** Lập trình có cấu trúc (Structured Programming) dựa trên những cấu trúc điều khiển cơ bản nào?
A. Tuần tự (Sequence), Lựa chọn (Selection), Lặp (Iteration).
B. Đối tượng (Object), Lớp (Class), Kế thừa (Inheritance).
C. GOTO, JUMP, RETURN.
D. Biến toàn cục, Con trỏ, Tham chiếu.
*Đáp án: A*

**Câu 185:** Ưu điểm của phương pháp lập trình thủ tục (Procedural) so với lập trình khối là gì?
A. Khó bảo trì hơn.
B. Có thể chia nhỏ chương trình thành các hàm (functions) để tái sử dụng.
C. Mã nguồn chỉ chạy được trên một hệ điều hành duy nhất.
D. Chương trình chỉ có một luồng thực thi duy nhất từ trên xuống dưới không thể tái sử dụng.
*Đáp án: B*

**Câu 186:** Tính Đóng gói (Encapsulation) trong OOP có ý nghĩa gì?
A. Viết tất cả các lớp trong cùng một file vật lý.
B. Nén mã nguồn lại thành file ZIP trước khi biên dịch.
C. Che giấu thông tin nội bộ của đối tượng và chỉ giao tiếp qua các phương thức được cho phép.
D. Tái sử dụng lại toàn bộ mã của một lớp khác.
*Đáp án: C*

**Câu 187:** Khái niệm Kế thừa (Inheritance) trong lập trình hướng đối tượng cho phép điều gì?
A. Một lớp có thể nhận lại các thuộc tính và phương thức từ một lớp khác, giúp tái sử dụng mã.
B. Xóa bỏ các phương thức của lớp cha.
C. Đóng gói dữ liệu an toàn hơn.
D. Thay đổi kiểu dữ liệu của biến linh hoạt.
*Đáp án: A*

**Câu 188:** Tính Đa hình (Polymorphism) thể hiện đặc điểm nào?
A. Một đối tượng có thể bị xóa bằng nhiều cách.
B. Cùng một phương thức nhưng có thể thực hiện những hành động khác nhau tùy thuộc vào đối tượng gọi nó.
C. Chương trình có thể chạy trên nhiều hệ điều hành.
D. Một lớp có nhiều tên gọi khác nhau.
*Đáp án: B*

**Câu 189:** Tại sao việc duy trì một Phong cách lập trình (Programming Style) nhất quán là quan trọng?
A. Làm cho chương trình chạy nhanh hơn gấp đôi.
B. Giúp mã nguồn dễ đọc, dễ hiểu và dễ bảo trì, đặc biệt khi làm việc nhóm.
C. Trình biên dịch bắt buộc phải có phong cách mới dịch được.
D. Giảm dung lượng file mã nguồn.
*Đáp án: B*

**Câu 190:** Quy tắc đặt tên CamelCase là như thế nào?
A. Viet_Hoa_Tung_Chu_Cai.
B. chu_cai_thuong_co_gach_duoi.
C. tuDauTienVietThuongCacTuTiepTheoVietHoaChuCaiDau.
D. VIET_HOA_TOAN_BO.
*Đáp án: C*

**Câu 191:** Theo nguyên tắc viết mã tốt, khi nào nên sử dụng Chú thích (Comment)?
A. Giải thích MỌI dòng code, kể cả những dòng gán giá trị đơn giản.
B. Khi muốn tắt một đoạn code không muốn chạy.
C. Để giải thích TẠI SAO một đoạn mã được viết như vậy, nhất là đối với logic phức tạp.
D. Chỉ để ghi tên tác giả.
*Đáp án: C*

**Câu 192:** Nguyên tắc DRY (Don't Repeat Yourself) nghĩa là gì?
A. Không sử dụng vòng lặp trong chương trình.
B. Không sao chép và dán (copy-paste) cùng một đoạn mã nhiều lần, mà nên dùng hàm hoặc lớp để tái sử dụng.
C. Không bao giờ viết lại code của người khác.
D. Không chạy chương trình hai lần.
*Đáp án: B*

**Câu 193:** Loại lỗi nào khiến chương trình không thể biên dịch thành công?
A. Lỗi Logic.
B. Lỗi Cú pháp (Syntax error).
C. Lỗi Runtime.
D. Lỗi Giao diện.
*Đáp án: B*

**Câu 194:** Đặc điểm của lỗi Logic (Logical error) là gì?
A. Trình biên dịch báo lỗi ngay khi vừa viết xong code.
B. Xảy ra do thiếu dấu chấm phẩy hoặc viết sai từ khóa.
C. Chương trình vẫn chạy nhưng kết quả tính toán hoặc hoạt động không đúng như mong đợi.
D. Làm máy tính bị treo ngay lập tức.
*Đáp án: C*

**Câu 195:** Quá trình Debug là gì?
A. Xóa toàn bộ mã nguồn để viết lại từ đầu.
B. Tối ưu hóa thuật toán để chạy nhanh hơn.
C. Quá trình tìm kiếm, xác định nguyên nhân và sửa chữa các lỗi trong chương trình.
D. Thiết kế giao diện đồ họa.
*Đáp án: C*

**Câu 196:** Đặc trưng chính của phương pháp lập trình không cấu trúc (Unstructured Programming) là gì?
A. Chia chương trình thành nhiều lớp và đối tượng.
B. Sử dụng lệnh GOTO để nhảy tới các nhãn, khiến luồng điều khiển rối rắm.
C. Tập trung vào giao diện đồ họa.
D. Không cần viết mã nguồn, chỉ cần kéo thả.
*Đáp án: B*

**Câu 197:** Lập trình có cấu trúc (Structured Programming) dựa trên những cấu trúc điều khiển cơ bản nào?
A. Tuần tự (Sequence), Lựa chọn (Selection), Lặp (Iteration).
B. Đối tượng (Object), Lớp (Class), Kế thừa (Inheritance).
C. GOTO, JUMP, RETURN.
D. Biến toàn cục, Con trỏ, Tham chiếu.
*Đáp án: A*

**Câu 198:** Ưu điểm của phương pháp lập trình thủ tục (Procedural) so với lập trình khối là gì?
A. Khó bảo trì hơn.
B. Có thể chia nhỏ chương trình thành các hàm (functions) để tái sử dụng.
C. Mã nguồn chỉ chạy được trên một hệ điều hành duy nhất.
D. Chương trình chỉ có một luồng thực thi duy nhất từ trên xuống dưới không thể tái sử dụng.
*Đáp án: B*

**Câu 199:** Tính Đóng gói (Encapsulation) trong OOP có ý nghĩa gì?
A. Viết tất cả các lớp trong cùng một file vật lý.
B. Nén mã nguồn lại thành file ZIP trước khi biên dịch.
C. Che giấu thông tin nội bộ của đối tượng và chỉ giao tiếp qua các phương thức được cho phép.
D. Tái sử dụng lại toàn bộ mã của một lớp khác.
*Đáp án: C*

**Câu 200:** Khái niệm Kế thừa (Inheritance) trong lập trình hướng đối tượng cho phép điều gì?
A. Một lớp có thể nhận lại các thuộc tính và phương thức từ một lớp khác, giúp tái sử dụng mã.
B. Xóa bỏ các phương thức của lớp cha.
C. Đóng gói dữ liệu an toàn hơn.
D. Thay đổi kiểu dữ liệu của biến linh hoạt.
*Đáp án: A*

**Câu 201:** Tính Đa hình (Polymorphism) thể hiện đặc điểm nào?
A. Một đối tượng có thể bị xóa bằng nhiều cách.
B. Cùng một phương thức nhưng có thể thực hiện những hành động khác nhau tùy thuộc vào đối tượng gọi nó.
C. Chương trình có thể chạy trên nhiều hệ điều hành.
D. Một lớp có nhiều tên gọi khác nhau.
*Đáp án: B*

**Câu 202:** Tại sao việc duy trì một Phong cách lập trình (Programming Style) nhất quán là quan trọng?
A. Làm cho chương trình chạy nhanh hơn gấp đôi.
B. Giúp mã nguồn dễ đọc, dễ hiểu và dễ bảo trì, đặc biệt khi làm việc nhóm.
C. Trình biên dịch bắt buộc phải có phong cách mới dịch được.
D. Giảm dung lượng file mã nguồn.
*Đáp án: B*

**Câu 203:** Quy tắc đặt tên CamelCase là như thế nào?
A. Viet_Hoa_Tung_Chu_Cai.
B. chu_cai_thuong_co_gach_duoi.
C. tuDauTienVietThuongCacTuTiepTheoVietHoaChuCaiDau.
D. VIET_HOA_TOAN_BO.
*Đáp án: C*

**Câu 204:** Theo nguyên tắc viết mã tốt, khi nào nên sử dụng Chú thích (Comment)?
A. Giải thích MỌI dòng code, kể cả những dòng gán giá trị đơn giản.
B. Khi muốn tắt một đoạn code không muốn chạy.
C. Để giải thích TẠI SAO một đoạn mã được viết như vậy, nhất là đối với logic phức tạp.
D. Chỉ để ghi tên tác giả.
*Đáp án: C*

**Câu 205:** Nguyên tắc DRY (Don't Repeat Yourself) nghĩa là gì?
A. Không sử dụng vòng lặp trong chương trình.
B. Không sao chép và dán (copy-paste) cùng một đoạn mã nhiều lần, mà nên dùng hàm hoặc lớp để tái sử dụng.
C. Không bao giờ viết lại code của người khác.
D. Không chạy chương trình hai lần.
*Đáp án: B*

**Câu 206:** Loại lỗi nào khiến chương trình không thể biên dịch thành công?
A. Lỗi Logic.
B. Lỗi Cú pháp (Syntax error).
C. Lỗi Runtime.
D. Lỗi Giao diện.
*Đáp án: B*

**Câu 207:** Đặc điểm của lỗi Logic (Logical error) là gì?
A. Trình biên dịch báo lỗi ngay khi vừa viết xong code.
B. Xảy ra do thiếu dấu chấm phẩy hoặc viết sai từ khóa.
C. Chương trình vẫn chạy nhưng kết quả tính toán hoặc hoạt động không đúng như mong đợi.
D. Làm máy tính bị treo ngay lập tức.
*Đáp án: C*

**Câu 208:** Quá trình Debug là gì?
A. Xóa toàn bộ mã nguồn để viết lại từ đầu.
B. Tối ưu hóa thuật toán để chạy nhanh hơn.
C. Quá trình tìm kiếm, xác định nguyên nhân và sửa chữa các lỗi trong chương trình.
D. Thiết kế giao diện đồ họa.
*Đáp án: C*

**Câu 209:** Đặc trưng chính của phương pháp lập trình không cấu trúc (Unstructured Programming) là gì?
A. Chia chương trình thành nhiều lớp và đối tượng.
B. Sử dụng lệnh GOTO để nhảy tới các nhãn, khiến luồng điều khiển rối rắm.
C. Tập trung vào giao diện đồ họa.
D. Không cần viết mã nguồn, chỉ cần kéo thả.
*Đáp án: B*

**Câu 210:** Lập trình có cấu trúc (Structured Programming) dựa trên những cấu trúc điều khiển cơ bản nào?
A. Tuần tự (Sequence), Lựa chọn (Selection), Lặp (Iteration).
B. Đối tượng (Object), Lớp (Class), Kế thừa (Inheritance).
C. GOTO, JUMP, RETURN.
D. Biến toàn cục, Con trỏ, Tham chiếu.
*Đáp án: A*

**Câu 211:** Ưu điểm của phương pháp lập trình thủ tục (Procedural) so với lập trình khối là gì?
A. Khó bảo trì hơn.
B. Có thể chia nhỏ chương trình thành các hàm (functions) để tái sử dụng.
C. Mã nguồn chỉ chạy được trên một hệ điều hành duy nhất.
D. Chương trình chỉ có một luồng thực thi duy nhất từ trên xuống dưới không thể tái sử dụng.
*Đáp án: B*

**Câu 212:** Tính Đóng gói (Encapsulation) trong OOP có ý nghĩa gì?
A. Viết tất cả các lớp trong cùng một file vật lý.
B. Nén mã nguồn lại thành file ZIP trước khi biên dịch.
C. Che giấu thông tin nội bộ của đối tượng và chỉ giao tiếp qua các phương thức được cho phép.
D. Tái sử dụng lại toàn bộ mã của một lớp khác.
*Đáp án: C*

**Câu 213:** Khái niệm Kế thừa (Inheritance) trong lập trình hướng đối tượng cho phép điều gì?
A. Một lớp có thể nhận lại các thuộc tính và phương thức từ một lớp khác, giúp tái sử dụng mã.
B. Xóa bỏ các phương thức của lớp cha.
C. Đóng gói dữ liệu an toàn hơn.
D. Thay đổi kiểu dữ liệu của biến linh hoạt.
*Đáp án: A*

**Câu 214:** Tính Đa hình (Polymorphism) thể hiện đặc điểm nào?
A. Một đối tượng có thể bị xóa bằng nhiều cách.
B. Cùng một phương thức nhưng có thể thực hiện những hành động khác nhau tùy thuộc vào đối tượng gọi nó.
C. Chương trình có thể chạy trên nhiều hệ điều hành.
D. Một lớp có nhiều tên gọi khác nhau.
*Đáp án: B*

**Câu 215:** Tại sao việc duy trì một Phong cách lập trình (Programming Style) nhất quán là quan trọng?
A. Làm cho chương trình chạy nhanh hơn gấp đôi.
B. Giúp mã nguồn dễ đọc, dễ hiểu và dễ bảo trì, đặc biệt khi làm việc nhóm.
C. Trình biên dịch bắt buộc phải có phong cách mới dịch được.
D. Giảm dung lượng file mã nguồn.
*Đáp án: B*

**Câu 216:** Quy tắc đặt tên CamelCase là như thế nào?
A. Viet_Hoa_Tung_Chu_Cai.
B. chu_cai_thuong_co_gach_duoi.
C. tuDauTienVietThuongCacTuTiepTheoVietHoaChuCaiDau.
D. VIET_HOA_TOAN_BO.
*Đáp án: C*

**Câu 217:** Theo nguyên tắc viết mã tốt, khi nào nên sử dụng Chú thích (Comment)?
A. Giải thích MỌI dòng code, kể cả những dòng gán giá trị đơn giản.
B. Khi muốn tắt một đoạn code không muốn chạy.
C. Để giải thích TẠI SAO một đoạn mã được viết như vậy, nhất là đối với logic phức tạp.
D. Chỉ để ghi tên tác giả.
*Đáp án: C*

**Câu 218:** Nguyên tắc DRY (Don't Repeat Yourself) nghĩa là gì?
A. Không sử dụng vòng lặp trong chương trình.
B. Không sao chép và dán (copy-paste) cùng một đoạn mã nhiều lần, mà nên dùng hàm hoặc lớp để tái sử dụng.
C. Không bao giờ viết lại code của người khác.
D. Không chạy chương trình hai lần.
*Đáp án: B*

**Câu 219:** Loại lỗi nào khiến chương trình không thể biên dịch thành công?
A. Lỗi Logic.
B. Lỗi Cú pháp (Syntax error).
C. Lỗi Runtime.
D. Lỗi Giao diện.
*Đáp án: B*

**Câu 220:** Đặc điểm của lỗi Logic (Logical error) là gì?
A. Trình biên dịch báo lỗi ngay khi vừa viết xong code.
B. Xảy ra do thiếu dấu chấm phẩy hoặc viết sai từ khóa.
C. Chương trình vẫn chạy nhưng kết quả tính toán hoặc hoạt động không đúng như mong đợi.
D. Làm máy tính bị treo ngay lập tức.
*Đáp án: C*

**Câu 221:** Quá trình Debug là gì?
A. Xóa toàn bộ mã nguồn để viết lại từ đầu.
B. Tối ưu hóa thuật toán để chạy nhanh hơn.
C. Quá trình tìm kiếm, xác định nguyên nhân và sửa chữa các lỗi trong chương trình.
D. Thiết kế giao diện đồ họa.
*Đáp án: C*

**Câu 222:** Đặc trưng chính của phương pháp lập trình không cấu trúc (Unstructured Programming) là gì?
A. Chia chương trình thành nhiều lớp và đối tượng.
B. Sử dụng lệnh GOTO để nhảy tới các nhãn, khiến luồng điều khiển rối rắm.
C. Tập trung vào giao diện đồ họa.
D. Không cần viết mã nguồn, chỉ cần kéo thả.
*Đáp án: B*

**Câu 223:** Lập trình có cấu trúc (Structured Programming) dựa trên những cấu trúc điều khiển cơ bản nào?
A. Tuần tự (Sequence), Lựa chọn (Selection), Lặp (Iteration).
B. Đối tượng (Object), Lớp (Class), Kế thừa (Inheritance).
C. GOTO, JUMP, RETURN.
D. Biến toàn cục, Con trỏ, Tham chiếu.
*Đáp án: A*

**Câu 224:** Ưu điểm của phương pháp lập trình thủ tục (Procedural) so với lập trình khối là gì?
A. Khó bảo trì hơn.
B. Có thể chia nhỏ chương trình thành các hàm (functions) để tái sử dụng.
C. Mã nguồn chỉ chạy được trên một hệ điều hành duy nhất.
D. Chương trình chỉ có một luồng thực thi duy nhất từ trên xuống dưới không thể tái sử dụng.
*Đáp án: B*

**Câu 225:** Tính Đóng gói (Encapsulation) trong OOP có ý nghĩa gì?
A. Viết tất cả các lớp trong cùng một file vật lý.
B. Nén mã nguồn lại thành file ZIP trước khi biên dịch.
C. Che giấu thông tin nội bộ của đối tượng và chỉ giao tiếp qua các phương thức được cho phép.
D. Tái sử dụng lại toàn bộ mã của một lớp khác.
*Đáp án: C*

**Câu 226:** Khái niệm Kế thừa (Inheritance) trong lập trình hướng đối tượng cho phép điều gì?
A. Một lớp có thể nhận lại các thuộc tính và phương thức từ một lớp khác, giúp tái sử dụng mã.
B. Xóa bỏ các phương thức của lớp cha.
C. Đóng gói dữ liệu an toàn hơn.
D. Thay đổi kiểu dữ liệu của biến linh hoạt.
*Đáp án: A*

**Câu 227:** Tính Đa hình (Polymorphism) thể hiện đặc điểm nào?
A. Một đối tượng có thể bị xóa bằng nhiều cách.
B. Cùng một phương thức nhưng có thể thực hiện những hành động khác nhau tùy thuộc vào đối tượng gọi nó.
C. Chương trình có thể chạy trên nhiều hệ điều hành.
D. Một lớp có nhiều tên gọi khác nhau.
*Đáp án: B*

**Câu 228:** Tại sao việc duy trì một Phong cách lập trình (Programming Style) nhất quán là quan trọng?
A. Làm cho chương trình chạy nhanh hơn gấp đôi.
B. Giúp mã nguồn dễ đọc, dễ hiểu và dễ bảo trì, đặc biệt khi làm việc nhóm.
C. Trình biên dịch bắt buộc phải có phong cách mới dịch được.
D. Giảm dung lượng file mã nguồn.
*Đáp án: B*

**Câu 229:** Quy tắc đặt tên CamelCase là như thế nào?
A. Viet_Hoa_Tung_Chu_Cai.
B. chu_cai_thuong_co_gach_duoi.
C. tuDauTienVietThuongCacTuTiepTheoVietHoaChuCaiDau.
D. VIET_HOA_TOAN_BO.
*Đáp án: C*

**Câu 230:** Theo nguyên tắc viết mã tốt, khi nào nên sử dụng Chú thích (Comment)?
A. Giải thích MỌI dòng code, kể cả những dòng gán giá trị đơn giản.
B. Khi muốn tắt một đoạn code không muốn chạy.
C. Để giải thích TẠI SAO một đoạn mã được viết như vậy, nhất là đối với logic phức tạp.
D. Chỉ để ghi tên tác giả.
*Đáp án: C*

**Câu 231:** Nguyên tắc DRY (Don't Repeat Yourself) nghĩa là gì?
A. Không sử dụng vòng lặp trong chương trình.
B. Không sao chép và dán (copy-paste) cùng một đoạn mã nhiều lần, mà nên dùng hàm hoặc lớp để tái sử dụng.
C. Không bao giờ viết lại code của người khác.
D. Không chạy chương trình hai lần.
*Đáp án: B*

**Câu 232:** Loại lỗi nào khiến chương trình không thể biên dịch thành công?
A. Lỗi Logic.
B. Lỗi Cú pháp (Syntax error).
C. Lỗi Runtime.
D. Lỗi Giao diện.
*Đáp án: B*

**Câu 233:** Đặc điểm của lỗi Logic (Logical error) là gì?
A. Trình biên dịch báo lỗi ngay khi vừa viết xong code.
B. Xảy ra do thiếu dấu chấm phẩy hoặc viết sai từ khóa.
C. Chương trình vẫn chạy nhưng kết quả tính toán hoặc hoạt động không đúng như mong đợi.
D. Làm máy tính bị treo ngay lập tức.
*Đáp án: C*

**Câu 234:** Quá trình Debug là gì?
A. Xóa toàn bộ mã nguồn để viết lại từ đầu.
B. Tối ưu hóa thuật toán để chạy nhanh hơn.
C. Quá trình tìm kiếm, xác định nguyên nhân và sửa chữa các lỗi trong chương trình.
D. Thiết kế giao diện đồ họa.
*Đáp án: C*

**Câu 235:** Đặc trưng chính của phương pháp lập trình không cấu trúc (Unstructured Programming) là gì?
A. Chia chương trình thành nhiều lớp và đối tượng.
B. Sử dụng lệnh GOTO để nhảy tới các nhãn, khiến luồng điều khiển rối rắm.
C. Tập trung vào giao diện đồ họa.
D. Không cần viết mã nguồn, chỉ cần kéo thả.
*Đáp án: B*

**Câu 236:** Lập trình có cấu trúc (Structured Programming) dựa trên những cấu trúc điều khiển cơ bản nào?
A. Tuần tự (Sequence), Lựa chọn (Selection), Lặp (Iteration).
B. Đối tượng (Object), Lớp (Class), Kế thừa (Inheritance).
C. GOTO, JUMP, RETURN.
D. Biến toàn cục, Con trỏ, Tham chiếu.
*Đáp án: A*

**Câu 237:** Ưu điểm của phương pháp lập trình thủ tục (Procedural) so với lập trình khối là gì?
A. Khó bảo trì hơn.
B. Có thể chia nhỏ chương trình thành các hàm (functions) để tái sử dụng.
C. Mã nguồn chỉ chạy được trên một hệ điều hành duy nhất.
D. Chương trình chỉ có một luồng thực thi duy nhất từ trên xuống dưới không thể tái sử dụng.
*Đáp án: B*

**Câu 238:** Tính Đóng gói (Encapsulation) trong OOP có ý nghĩa gì?
A. Viết tất cả các lớp trong cùng một file vật lý.
B. Nén mã nguồn lại thành file ZIP trước khi biên dịch.
C. Che giấu thông tin nội bộ của đối tượng và chỉ giao tiếp qua các phương thức được cho phép.
D. Tái sử dụng lại toàn bộ mã của một lớp khác.
*Đáp án: C*

**Câu 239:** Khái niệm Kế thừa (Inheritance) trong lập trình hướng đối tượng cho phép điều gì?
A. Một lớp có thể nhận lại các thuộc tính và phương thức từ một lớp khác, giúp tái sử dụng mã.
B. Xóa bỏ các phương thức của lớp cha.
C. Đóng gói dữ liệu an toàn hơn.
D. Thay đổi kiểu dữ liệu của biến linh hoạt.
*Đáp án: A*

**Câu 240:** Tính Đa hình (Polymorphism) thể hiện đặc điểm nào?
A. Một đối tượng có thể bị xóa bằng nhiều cách.
B. Cùng một phương thức nhưng có thể thực hiện những hành động khác nhau tùy thuộc vào đối tượng gọi nó.
C. Chương trình có thể chạy trên nhiều hệ điều hành.
D. Một lớp có nhiều tên gọi khác nhau.
*Đáp án: B*

**Câu 241:** Tại sao việc duy trì một Phong cách lập trình (Programming Style) nhất quán là quan trọng?
A. Làm cho chương trình chạy nhanh hơn gấp đôi.
B. Giúp mã nguồn dễ đọc, dễ hiểu và dễ bảo trì, đặc biệt khi làm việc nhóm.
C. Trình biên dịch bắt buộc phải có phong cách mới dịch được.
D. Giảm dung lượng file mã nguồn.
*Đáp án: B*

**Câu 242:** Quy tắc đặt tên CamelCase là như thế nào?
A. Viet_Hoa_Tung_Chu_Cai.
B. chu_cai_thuong_co_gach_duoi.
C. tuDauTienVietThuongCacTuTiepTheoVietHoaChuCaiDau.
D. VIET_HOA_TOAN_BO.
*Đáp án: C*

**Câu 243:** Theo nguyên tắc viết mã tốt, khi nào nên sử dụng Chú thích (Comment)?
A. Giải thích MỌI dòng code, kể cả những dòng gán giá trị đơn giản.
B. Khi muốn tắt một đoạn code không muốn chạy.
C. Để giải thích TẠI SAO một đoạn mã được viết như vậy, nhất là đối với logic phức tạp.
D. Chỉ để ghi tên tác giả.
*Đáp án: C*

**Câu 244:** Nguyên tắc DRY (Don't Repeat Yourself) nghĩa là gì?
A. Không sử dụng vòng lặp trong chương trình.
B. Không sao chép và dán (copy-paste) cùng một đoạn mã nhiều lần, mà nên dùng hàm hoặc lớp để tái sử dụng.
C. Không bao giờ viết lại code của người khác.
D. Không chạy chương trình hai lần.
*Đáp án: B*

**Câu 245:** Loại lỗi nào khiến chương trình không thể biên dịch thành công?
A. Lỗi Logic.
B. Lỗi Cú pháp (Syntax error).
C. Lỗi Runtime.
D. Lỗi Giao diện.
*Đáp án: B*

**Câu 246:** Đặc điểm của lỗi Logic (Logical error) là gì?
A. Trình biên dịch báo lỗi ngay khi vừa viết xong code.
B. Xảy ra do thiếu dấu chấm phẩy hoặc viết sai từ khóa.
C. Chương trình vẫn chạy nhưng kết quả tính toán hoặc hoạt động không đúng như mong đợi.
D. Làm máy tính bị treo ngay lập tức.
*Đáp án: C*

**Câu 247:** Quá trình Debug là gì?
A. Xóa toàn bộ mã nguồn để viết lại từ đầu.
B. Tối ưu hóa thuật toán để chạy nhanh hơn.
C. Quá trình tìm kiếm, xác định nguyên nhân và sửa chữa các lỗi trong chương trình.
D. Thiết kế giao diện đồ họa.
*Đáp án: C*

**Câu 248:** Đặc trưng chính của phương pháp lập trình không cấu trúc (Unstructured Programming) là gì?
A. Chia chương trình thành nhiều lớp và đối tượng.
B. Sử dụng lệnh GOTO để nhảy tới các nhãn, khiến luồng điều khiển rối rắm.
C. Tập trung vào giao diện đồ họa.
D. Không cần viết mã nguồn, chỉ cần kéo thả.
*Đáp án: B*

**Câu 249:** Lập trình có cấu trúc (Structured Programming) dựa trên những cấu trúc điều khiển cơ bản nào?
A. Tuần tự (Sequence), Lựa chọn (Selection), Lặp (Iteration).
B. Đối tượng (Object), Lớp (Class), Kế thừa (Inheritance).
C. GOTO, JUMP, RETURN.
D. Biến toàn cục, Con trỏ, Tham chiếu.
*Đáp án: A*

**Câu 250:** Ưu điểm của phương pháp lập trình thủ tục (Procedural) so với lập trình khối là gì?
A. Khó bảo trì hơn.
B. Có thể chia nhỏ chương trình thành các hàm (functions) để tái sử dụng.
C. Mã nguồn chỉ chạy được trên một hệ điều hành duy nhất.
D. Chương trình chỉ có một luồng thực thi duy nhất từ trên xuống dưới không thể tái sử dụng.
*Đáp án: B*
