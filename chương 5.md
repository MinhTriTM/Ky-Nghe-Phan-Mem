# CHƯƠNG 5: THIẾT KẾ PHẦN MỀM

## PHẦN 1: Câu hỏi tự luận ngắn

1. **Thiết kế phần mềm là gì?**
   *Gợi ý:* Là việc mô tả các thành phần của phần mềm dựa trên hồ sơ phân tích yêu cầu và công nghệ được chọn.
2. **Vai trò của quá trình thiết kế phần mềm là gì?**
   *Gợi ý:* Tạo ra mô hình cài đặt của phần mềm, đóng vai trò là công cụ giao tiếp giữa những người tham gia phát triển, và là cơ sở đảm bảo chất lượng hệ thống.
3. **Cấu trúc của quá trình thiết kế thường bao gồm những bước nào?**
   *Gợi ý:* Gồm 2 bước chính: Thiết kế tổng thể (kiến trúc) mô tả các thành phần ở mức tổng thể, và Thiết kế chi tiết mô tả chi tiết từng thành phần.
4. **Nội dung của thiết kế phần mềm bao gồm những mảng nào?**
   *Gợi ý:* Bao gồm thiết kế kiến trúc, thiết kế dữ liệu, thiết kế giao diện và thiết kế xử lý (thuật toán).
5. **Chất lượng của thiết kế phần mềm được đánh giá dựa trên những tiêu chí nào?**
   *Gợi ý:* Tính cấu trúc, tính gắn kết (Cohesion), tính kết dính/phụ thuộc (Coupling), tính tiến hóa và tính tái sử dụng.
6. **Mối quan hệ giữa Cohesion và Coupling như thế nào thì được xem là một thiết kế tốt?**
   *Gợi ý:* Thiết kế tốt đòi hỏi độ gắn kết (Cohesion) cao (các phần tử trong cùng một module liên quan chặt chẽ với nhau) và độ phụ thuộc (Coupling) thấp (các module ít phụ thuộc vào nhau).
7. **Thiết kế kiến trúc phần mềm là gì?**
   *Gợi ý:* Là mô tả một cách tổng thể các thành phần của phần mềm, quyết định sự tồn tại và cách thức liên kết/kết nối giữa các thành phần mà không đi vào chi tiết bên trong.
8. **Mô hình kiến trúc đơn nguyên (Monolithic) là gì?**
   *Gợi ý:* Tất cả các xử lý của phần mềm (giao diện, nghiệp vụ, dữ liệu) được thực thi trong một tiến trình duy nhất trên một máy tính.
9. **Kể tên các mô hình kiến trúc phần mềm phổ biến?**
   *Gợi ý:* Kiến trúc đơn nguyên (Monolithic), Kiến trúc Client-Server, Kiến trúc đa tầng (N-tier / 3-tier), và Kiến trúc hướng dịch vụ (SOA / Microservices).
10. **Trong kiến trúc 3 tầng (3-tier), 3 tầng đó là gì?**
    *Gợi ý:* Tầng trình diễn (Presentation Layer - UI), Tầng nghiệp vụ (Business Logic Layer - BLL), và Tầng dữ liệu (Data Access Layer - DAL).
11. **Kiến trúc Client - Server có đặc điểm gì?**
    *Gợi ý:* Chia hệ thống thành 2 loại thành phần: Server (cung cấp dịch vụ) và Client (yêu cầu và tiêu thụ dịch vụ).
12. **Mô hình kiến trúc hướng dịch vụ (SOA) là gì?**
    *Gợi ý:* Kiến trúc tập hợp các dịch vụ độc lập, giao tiếp với nhau qua mạng, có khả năng tái sử dụng cao và linh hoạt trong việc thay đổi công nghệ.
13. **Ưu điểm chính của việc áp dụng kỹ thuật Hướng đối tượng (OOD) trong thiết kế là gì?**
    *Gợi ý:* Dễ bảo trì, dễ hiểu, các đối tượng độc lập (bao gói), liên kết lỏng lẻo và có tính tái sử dụng cao (kế thừa).
14. **Thiết kế dữ liệu hướng đối tượng (OOD) tập trung vào điều gì?**
    *Gợi ý:* Xác định các lớp (Class), thuộc tính (Attributes), phương thức (Methods) và mối quan hệ (Relationships) giữa các lớp.
15. **Tính đóng gói (Encapsulation) trong thiết kế hướng đối tượng có ý nghĩa gì?**
    *Gợi ý:* Che giấu chi tiết cài đặt bên trong của một đối tượng, chỉ cung cấp các giao diện (interface) công khai để tương tác.
16. **Giao diện người dùng (UI) có vai trò gì trong hệ thống phần mềm?**
    *Gợi ý:* Là nơi diễn ra sự tương tác giữa con người và phần mềm, định nghĩa cách thức giao tiếp, tiếp nhận thông tin đầu vào và phản hồi thông tin đầu ra.
17. **Cấu trúc tổ chức của một giao diện thường có những thành phần chính nào?**
    *Gợi ý:* Thành phần nhập liệu (Input), Thành phần xuất dữ liệu (Output), Thành phần điều khiển (Control) và Thành phần hướng dẫn/thông báo.
18. **Hai dạng giao diện phần mềm cơ bản là gì?**
    *Gợi ý:* Giao diện dòng lệnh (CLI - Command Line Interface) và Giao diện đồ họa (GUI - Graphical User Interface).
19. **Một giao diện tốt cần đáp ứng các nguyên tắc nào?**
    *Gợi ý:* Thân thiện, nhất quán, dễ sử dụng, phản hồi nhanh, có cơ chế xử lý lỗi rõ ràng và hỗ trợ người dùng (Help).
20. **Thành phần xử lý của phần mềm bao gồm những nhóm nào?**
    *Gợi ý:* Xử lý giao diện, xử lý nghiệp vụ (Business logic) và xử lý lưu trữ/truy xuất dữ liệu.
21. **Xử lý biến cố (Event handling) trong giao diện là gì?**
    *Gợi ý:* Là quá trình tiếp nhận và thực thi các hành động tương ứng khi có sự kiện phát sinh từ phía người sử dụng (ví dụ: click chuột, gõ phím).
22. **Thiết kế thành phần xử lý (thuật toán) sử dụng những công cụ biểu diễn nào phổ biến?**
    *Gợi ý:* Lưu đồ thuật toán (Flowchart), mã giả (Pseudocode), hoặc biểu đồ hoạt động (Activity Diagram).
23. **Tại sao cần phải tách biệt tầng giao diện (UI) và tầng nghiệp vụ (Business Logic)?**
    *Gợi ý:* Để dễ dàng bảo trì, thay đổi giao diện mà không ảnh hưởng đến logic cốt lõi, và cho phép tái sử dụng logic ở nhiều nền tảng giao diện khác nhau (Web, Mobile, Desktop).
24. **Sự khác biệt giữa thiết kế tổng thể và thiết kế chi tiết là gì?**
    *Gợi ý:* Thiết kế tổng thể định hình kiến trúc và các module chính cùng mối liên kết. Thiết kế chi tiết đi sâu vào từng module để xác định cấu trúc dữ liệu, thuật toán và giao diện cục bộ.
25. **Công nghệ phân tán trong thiết kế kiến trúc phần mềm mang lại lợi ích gì?**
    *Gợi ý:* Tăng khả năng chịu tải, mở rộng hệ thống (Scalability), tăng độ tin cậy (High Availability) và chia sẻ tài nguyên tính toán.


## PHẦN 2: Câu hỏi trắc nghiệm

**Câu 1:** Quá trình thiết kế phần mềm dựa trên nền tảng chính nào?
A. Mã nguồn đã có sẵn.
B. Hồ sơ phân tích yêu cầu và công nghệ được chọn.
C. Ý kiến cá nhân của lập trình viên.
D. Yêu cầu phần cứng của máy chủ.
*Đáp án: B*

**Câu 2:** Đâu là lợi ích chính của việc thiết kế phần mềm trước khi lập trình?
A. Bỏ qua được bước kiểm thử.
B. Viết mã nguồn nhanh hơn mà không cần hiểu nghiệp vụ.
C. Cung cấp một bản thiết kế giúp các thành viên dễ hiểu, dễ sửa đổi và bảo trì.
D. Giảm chi phí mua bản quyền phần mềm.
*Đáp án: C*

**Câu 3:** Bước nào mô tả sự tồn tại và phụ thuộc của các thành phần ở mức tổng thể?
A. Thiết kế chi tiết.
B. Phân tích yêu cầu.
C. Thiết kế kiến trúc (tổng thể).
D. Cài đặt hệ thống.
*Đáp án: C*

**Câu 4:** Nội dung nào KHÔNG thuộc phạm vi chính của quá trình thiết kế phần mềm?
A. Thiết kế kiến trúc.
B. Khảo sát hiện trạng khách hàng.
C. Thiết kế dữ liệu.
D. Thiết kế giao diện.
*Đáp án: B*

**Câu 5:** Tính gắn kết (Cohesion) trong thiết kế mô tả điều gì?
A. Mức độ phụ thuộc lẫn nhau giữa các module khác nhau.
B. Mức độ liên quan và tập trung vào một nhiệm vụ duy nhất của các phần tử bên trong cùng một module.
C. Số lượng hàm trong một module.
D. Số lượng lỗi phát sinh khi chạy chương trình.
*Đáp án: B*

**Câu 6:** Tính kết dính/phụ thuộc (Coupling) đo lường điều gì?
A. Mức độ độc lập giữa các module với nhau.
B. Số dòng code của một class.
C. Tốc độ xử lý của thuật toán.
D. Số lượng bảng trong cơ sở dữ liệu.
*Đáp án: A*

**Câu 7:** Một thiết kế phần mềm được coi là tốt khi nó đạt tiêu chí nào về Cohesion và Coupling?
A. Cohesion thấp và Coupling cao.
B. Cohesion cao và Coupling thấp.
C. Cohesion thấp và Coupling thấp.
D. Cohesion cao và Coupling cao.
*Đáp án: B*

**Câu 8:** Kiến trúc phần mềm quyết định yếu tố gì?
A. Chi tiết từng dòng code sẽ viết như thế nào.
B. Tên của các biến trong chương trình.
C. Sự tồn tại, vai trò và cách liên kết giữa các thành phần lớn của hệ thống.
D. Màu sắc của giao diện người dùng.
*Đáp án: C*

**Câu 9:** Mô hình kiến trúc nào mà toàn bộ giao diện, xử lý nghiệp vụ và truy xuất dữ liệu nằm gọn trong một khối duy nhất?
A. Mô hình Client-Server.
B. Mô hình 3 tầng (3-tier).
C. Mô hình Microservices.
D. Mô hình Đơn nguyên (Monolithic).
*Đáp án: D*

**Câu 10:** Trong kiến trúc Client-Server, đặc điểm của máy Server là gì?
A. Chỉ dùng để hiển thị giao diện cho người dùng cuối.
B. Gửi các yêu cầu xử lý đến máy Client.
C. Cung cấp dịch vụ, lắng nghe và xử lý các yêu cầu từ nhiều máy Client.
D. Không cần kết nối mạng.
*Đáp án: C*

**Câu 11:** Kiến trúc 3 tầng (3-tier) chia ứng dụng thành các tầng nào?
A. Tầng vật lý, Tầng mạng, Tầng ứng dụng.
B. Tầng giao diện, Tầng nghiệp vụ, Tầng dữ liệu.
C. Tầng Client, Tầng trung gian, Tầng Server.
D. Tầng bảo mật, Tầng xử lý, Tầng lưu trữ.
*Đáp án: B*

**Câu 12:** Đặc điểm nổi bật của thiết kế hướng đối tượng (OOD) là gì?
A. Chia chương trình thành các hàm gọi nhau tuần tự.
B. Không quan tâm đến dữ liệu, chỉ quan tâm luồng xử lý.
C. Nhìn nhận hệ thống như một tập các đối tượng tương tác với nhau thông qua thông báo.
D. Tất cả các biến đều là biến toàn cục.
*Đáp án: C*

**Câu 13:** Tính chất nào giúp che giấu thông tin nội bộ của đối tượng trong OOD?
A. Đa hình (Polymorphism).
B. Kế thừa (Inheritance).
C. Đóng gói (Encapsulation).
D. Trừu tượng (Abstraction).
*Đáp án: C*

**Câu 14:** Trong OOD, một đối tượng phần mềm bao gồm hai thành phần cơ bản nào?
A. Dữ liệu (thuộc tính) và Xử lý (phương thức).
B. Giao diện và Cơ sở dữ liệu.
C. Lớp và Đối tượng.
D. Biến toàn cục và Hàm.
*Đáp án: A*

**Câu 15:** Vai trò chính của Giao diện người dùng (UI) là gì?
A. Xử lý các phép toán phức tạp ở backend.
B. Lưu trữ dữ liệu vĩnh viễn vào ổ cứng.
C. Là nơi diễn ra tương tác, tiếp nhận yêu cầu và phản hồi thông tin cho người sử dụng.
D. Bảo vệ hệ thống khỏi hacker.
*Đáp án: C*

**Câu 16:** Thành phần nào KHÔNG thuộc quy trình xử lý giao diện cơ bản?
A. Xử lý biến cố (Event).
B. Xử lý nhập/xuất dữ liệu.
C. Tối ưu hóa truy vấn SQL dưới database.
D. Cập nhật trạng thái hiển thị trên màn hình.
*Đáp án: C*

**Câu 17:** Xử lý nghiệp vụ (Business Logic) đóng vai trò gì?
A. Bắt các sự kiện click chuột của người dùng.
B. Vẽ các nút bấm, biểu mẫu trên màn hình.
C. Lưu trữ dữ liệu dưới dạng file vật lý.
D. Thực hiện các quy tắc tính toán, kiểm tra và ràng buộc cốt lõi của bài toán.
*Đáp án: D*

**Câu 18:** Quá trình thiết kế phần mềm dựa trên nền tảng chính nào?
A. Mã nguồn đã có sẵn.
B. Hồ sơ phân tích yêu cầu và công nghệ được chọn.
C. Ý kiến cá nhân của lập trình viên.
D. Yêu cầu phần cứng của máy chủ.
*Đáp án: B*

**Câu 19:** Đâu là lợi ích chính của việc thiết kế phần mềm trước khi lập trình?
A. Bỏ qua được bước kiểm thử.
B. Viết mã nguồn nhanh hơn mà không cần hiểu nghiệp vụ.
C. Cung cấp một bản thiết kế giúp các thành viên dễ hiểu, dễ sửa đổi và bảo trì.
D. Giảm chi phí mua bản quyền phần mềm.
*Đáp án: C*

**Câu 20:** Bước nào mô tả sự tồn tại và phụ thuộc của các thành phần ở mức tổng thể?
A. Thiết kế chi tiết.
B. Phân tích yêu cầu.
C. Thiết kế kiến trúc (tổng thể).
D. Cài đặt hệ thống.
*Đáp án: C*

**Câu 21:** Nội dung nào KHÔNG thuộc phạm vi chính của quá trình thiết kế phần mềm?
A. Thiết kế kiến trúc.
B. Khảo sát hiện trạng khách hàng.
C. Thiết kế dữ liệu.
D. Thiết kế giao diện.
*Đáp án: B*

**Câu 22:** Tính gắn kết (Cohesion) trong thiết kế mô tả điều gì?
A. Mức độ phụ thuộc lẫn nhau giữa các module khác nhau.
B. Mức độ liên quan và tập trung vào một nhiệm vụ duy nhất của các phần tử bên trong cùng một module.
C. Số lượng hàm trong một module.
D. Số lượng lỗi phát sinh khi chạy chương trình.
*Đáp án: B*

**Câu 23:** Tính kết dính/phụ thuộc (Coupling) đo lường điều gì?
A. Mức độ độc lập giữa các module với nhau.
B. Số dòng code của một class.
C. Tốc độ xử lý của thuật toán.
D. Số lượng bảng trong cơ sở dữ liệu.
*Đáp án: A*

**Câu 24:** Một thiết kế phần mềm được coi là tốt khi nó đạt tiêu chí nào về Cohesion và Coupling?
A. Cohesion thấp và Coupling cao.
B. Cohesion cao và Coupling thấp.
C. Cohesion thấp và Coupling thấp.
D. Cohesion cao và Coupling cao.
*Đáp án: B*

**Câu 25:** Kiến trúc phần mềm quyết định yếu tố gì?
A. Chi tiết từng dòng code sẽ viết như thế nào.
B. Tên của các biến trong chương trình.
C. Sự tồn tại, vai trò và cách liên kết giữa các thành phần lớn của hệ thống.
D. Màu sắc của giao diện người dùng.
*Đáp án: C*

**Câu 26:** Mô hình kiến trúc nào mà toàn bộ giao diện, xử lý nghiệp vụ và truy xuất dữ liệu nằm gọn trong một khối duy nhất?
A. Mô hình Client-Server.
B. Mô hình 3 tầng (3-tier).
C. Mô hình Microservices.
D. Mô hình Đơn nguyên (Monolithic).
*Đáp án: D*

**Câu 27:** Trong kiến trúc Client-Server, đặc điểm của máy Server là gì?
A. Chỉ dùng để hiển thị giao diện cho người dùng cuối.
B. Gửi các yêu cầu xử lý đến máy Client.
C. Cung cấp dịch vụ, lắng nghe và xử lý các yêu cầu từ nhiều máy Client.
D. Không cần kết nối mạng.
*Đáp án: C*

**Câu 28:** Kiến trúc 3 tầng (3-tier) chia ứng dụng thành các tầng nào?
A. Tầng vật lý, Tầng mạng, Tầng ứng dụng.
B. Tầng giao diện, Tầng nghiệp vụ, Tầng dữ liệu.
C. Tầng Client, Tầng trung gian, Tầng Server.
D. Tầng bảo mật, Tầng xử lý, Tầng lưu trữ.
*Đáp án: B*

**Câu 29:** Đặc điểm nổi bật của thiết kế hướng đối tượng (OOD) là gì?
A. Chia chương trình thành các hàm gọi nhau tuần tự.
B. Không quan tâm đến dữ liệu, chỉ quan tâm luồng xử lý.
C. Nhìn nhận hệ thống như một tập các đối tượng tương tác với nhau thông qua thông báo.
D. Tất cả các biến đều là biến toàn cục.
*Đáp án: C*

**Câu 30:** Tính chất nào giúp che giấu thông tin nội bộ của đối tượng trong OOD?
A. Đa hình (Polymorphism).
B. Kế thừa (Inheritance).
C. Đóng gói (Encapsulation).
D. Trừu tượng (Abstraction).
*Đáp án: C*

**Câu 31:** Trong OOD, một đối tượng phần mềm bao gồm hai thành phần cơ bản nào?
A. Dữ liệu (thuộc tính) và Xử lý (phương thức).
B. Giao diện và Cơ sở dữ liệu.
C. Lớp và Đối tượng.
D. Biến toàn cục và Hàm.
*Đáp án: A*

**Câu 32:** Vai trò chính của Giao diện người dùng (UI) là gì?
A. Xử lý các phép toán phức tạp ở backend.
B. Lưu trữ dữ liệu vĩnh viễn vào ổ cứng.
C. Là nơi diễn ra tương tác, tiếp nhận yêu cầu và phản hồi thông tin cho người sử dụng.
D. Bảo vệ hệ thống khỏi hacker.
*Đáp án: C*

**Câu 33:** Thành phần nào KHÔNG thuộc quy trình xử lý giao diện cơ bản?
A. Xử lý biến cố (Event).
B. Xử lý nhập/xuất dữ liệu.
C. Tối ưu hóa truy vấn SQL dưới database.
D. Cập nhật trạng thái hiển thị trên màn hình.
*Đáp án: C*

**Câu 34:** Xử lý nghiệp vụ (Business Logic) đóng vai trò gì?
A. Bắt các sự kiện click chuột của người dùng.
B. Vẽ các nút bấm, biểu mẫu trên màn hình.
C. Lưu trữ dữ liệu dưới dạng file vật lý.
D. Thực hiện các quy tắc tính toán, kiểm tra và ràng buộc cốt lõi của bài toán.
*Đáp án: D*

**Câu 35:** Quá trình thiết kế phần mềm dựa trên nền tảng chính nào?
A. Mã nguồn đã có sẵn.
B. Hồ sơ phân tích yêu cầu và công nghệ được chọn.
C. Ý kiến cá nhân của lập trình viên.
D. Yêu cầu phần cứng của máy chủ.
*Đáp án: B*

**Câu 36:** Đâu là lợi ích chính của việc thiết kế phần mềm trước khi lập trình?
A. Bỏ qua được bước kiểm thử.
B. Viết mã nguồn nhanh hơn mà không cần hiểu nghiệp vụ.
C. Cung cấp một bản thiết kế giúp các thành viên dễ hiểu, dễ sửa đổi và bảo trì.
D. Giảm chi phí mua bản quyền phần mềm.
*Đáp án: C*

**Câu 37:** Bước nào mô tả sự tồn tại và phụ thuộc của các thành phần ở mức tổng thể?
A. Thiết kế chi tiết.
B. Phân tích yêu cầu.
C. Thiết kế kiến trúc (tổng thể).
D. Cài đặt hệ thống.
*Đáp án: C*

**Câu 38:** Nội dung nào KHÔNG thuộc phạm vi chính của quá trình thiết kế phần mềm?
A. Thiết kế kiến trúc.
B. Khảo sát hiện trạng khách hàng.
C. Thiết kế dữ liệu.
D. Thiết kế giao diện.
*Đáp án: B*

**Câu 39:** Tính gắn kết (Cohesion) trong thiết kế mô tả điều gì?
A. Mức độ phụ thuộc lẫn nhau giữa các module khác nhau.
B. Mức độ liên quan và tập trung vào một nhiệm vụ duy nhất của các phần tử bên trong cùng một module.
C. Số lượng hàm trong một module.
D. Số lượng lỗi phát sinh khi chạy chương trình.
*Đáp án: B*

**Câu 40:** Tính kết dính/phụ thuộc (Coupling) đo lường điều gì?
A. Mức độ độc lập giữa các module với nhau.
B. Số dòng code của một class.
C. Tốc độ xử lý của thuật toán.
D. Số lượng bảng trong cơ sở dữ liệu.
*Đáp án: A*

**Câu 41:** Một thiết kế phần mềm được coi là tốt khi nó đạt tiêu chí nào về Cohesion và Coupling?
A. Cohesion thấp và Coupling cao.
B. Cohesion cao và Coupling thấp.
C. Cohesion thấp và Coupling thấp.
D. Cohesion cao và Coupling cao.
*Đáp án: B*

**Câu 42:** Kiến trúc phần mềm quyết định yếu tố gì?
A. Chi tiết từng dòng code sẽ viết như thế nào.
B. Tên của các biến trong chương trình.
C. Sự tồn tại, vai trò và cách liên kết giữa các thành phần lớn của hệ thống.
D. Màu sắc của giao diện người dùng.
*Đáp án: C*

**Câu 43:** Mô hình kiến trúc nào mà toàn bộ giao diện, xử lý nghiệp vụ và truy xuất dữ liệu nằm gọn trong một khối duy nhất?
A. Mô hình Client-Server.
B. Mô hình 3 tầng (3-tier).
C. Mô hình Microservices.
D. Mô hình Đơn nguyên (Monolithic).
*Đáp án: D*

**Câu 44:** Trong kiến trúc Client-Server, đặc điểm của máy Server là gì?
A. Chỉ dùng để hiển thị giao diện cho người dùng cuối.
B. Gửi các yêu cầu xử lý đến máy Client.
C. Cung cấp dịch vụ, lắng nghe và xử lý các yêu cầu từ nhiều máy Client.
D. Không cần kết nối mạng.
*Đáp án: C*

**Câu 45:** Kiến trúc 3 tầng (3-tier) chia ứng dụng thành các tầng nào?
A. Tầng vật lý, Tầng mạng, Tầng ứng dụng.
B. Tầng giao diện, Tầng nghiệp vụ, Tầng dữ liệu.
C. Tầng Client, Tầng trung gian, Tầng Server.
D. Tầng bảo mật, Tầng xử lý, Tầng lưu trữ.
*Đáp án: B*

**Câu 46:** Đặc điểm nổi bật của thiết kế hướng đối tượng (OOD) là gì?
A. Chia chương trình thành các hàm gọi nhau tuần tự.
B. Không quan tâm đến dữ liệu, chỉ quan tâm luồng xử lý.
C. Nhìn nhận hệ thống như một tập các đối tượng tương tác với nhau thông qua thông báo.
D. Tất cả các biến đều là biến toàn cục.
*Đáp án: C*

**Câu 47:** Tính chất nào giúp che giấu thông tin nội bộ của đối tượng trong OOD?
A. Đa hình (Polymorphism).
B. Kế thừa (Inheritance).
C. Đóng gói (Encapsulation).
D. Trừu tượng (Abstraction).
*Đáp án: C*

**Câu 48:** Trong OOD, một đối tượng phần mềm bao gồm hai thành phần cơ bản nào?
A. Dữ liệu (thuộc tính) và Xử lý (phương thức).
B. Giao diện và Cơ sở dữ liệu.
C. Lớp và Đối tượng.
D. Biến toàn cục và Hàm.
*Đáp án: A*

**Câu 49:** Vai trò chính của Giao diện người dùng (UI) là gì?
A. Xử lý các phép toán phức tạp ở backend.
B. Lưu trữ dữ liệu vĩnh viễn vào ổ cứng.
C. Là nơi diễn ra tương tác, tiếp nhận yêu cầu và phản hồi thông tin cho người sử dụng.
D. Bảo vệ hệ thống khỏi hacker.
*Đáp án: C*

**Câu 50:** Thành phần nào KHÔNG thuộc quy trình xử lý giao diện cơ bản?
A. Xử lý biến cố (Event).
B. Xử lý nhập/xuất dữ liệu.
C. Tối ưu hóa truy vấn SQL dưới database.
D. Cập nhật trạng thái hiển thị trên màn hình.
*Đáp án: C*

**Câu 51:** Xử lý nghiệp vụ (Business Logic) đóng vai trò gì?
A. Bắt các sự kiện click chuột của người dùng.
B. Vẽ các nút bấm, biểu mẫu trên màn hình.
C. Lưu trữ dữ liệu dưới dạng file vật lý.
D. Thực hiện các quy tắc tính toán, kiểm tra và ràng buộc cốt lõi của bài toán.
*Đáp án: D*

**Câu 52:** Quá trình thiết kế phần mềm dựa trên nền tảng chính nào?
A. Mã nguồn đã có sẵn.
B. Hồ sơ phân tích yêu cầu và công nghệ được chọn.
C. Ý kiến cá nhân của lập trình viên.
D. Yêu cầu phần cứng của máy chủ.
*Đáp án: B*

**Câu 53:** Đâu là lợi ích chính của việc thiết kế phần mềm trước khi lập trình?
A. Bỏ qua được bước kiểm thử.
B. Viết mã nguồn nhanh hơn mà không cần hiểu nghiệp vụ.
C. Cung cấp một bản thiết kế giúp các thành viên dễ hiểu, dễ sửa đổi và bảo trì.
D. Giảm chi phí mua bản quyền phần mềm.
*Đáp án: C*

**Câu 54:** Bước nào mô tả sự tồn tại và phụ thuộc của các thành phần ở mức tổng thể?
A. Thiết kế chi tiết.
B. Phân tích yêu cầu.
C. Thiết kế kiến trúc (tổng thể).
D. Cài đặt hệ thống.
*Đáp án: C*

**Câu 55:** Nội dung nào KHÔNG thuộc phạm vi chính của quá trình thiết kế phần mềm?
A. Thiết kế kiến trúc.
B. Khảo sát hiện trạng khách hàng.
C. Thiết kế dữ liệu.
D. Thiết kế giao diện.
*Đáp án: B*

**Câu 56:** Tính gắn kết (Cohesion) trong thiết kế mô tả điều gì?
A. Mức độ phụ thuộc lẫn nhau giữa các module khác nhau.
B. Mức độ liên quan và tập trung vào một nhiệm vụ duy nhất của các phần tử bên trong cùng một module.
C. Số lượng hàm trong một module.
D. Số lượng lỗi phát sinh khi chạy chương trình.
*Đáp án: B*

**Câu 57:** Tính kết dính/phụ thuộc (Coupling) đo lường điều gì?
A. Mức độ độc lập giữa các module với nhau.
B. Số dòng code của một class.
C. Tốc độ xử lý của thuật toán.
D. Số lượng bảng trong cơ sở dữ liệu.
*Đáp án: A*

**Câu 58:** Một thiết kế phần mềm được coi là tốt khi nó đạt tiêu chí nào về Cohesion và Coupling?
A. Cohesion thấp và Coupling cao.
B. Cohesion cao và Coupling thấp.
C. Cohesion thấp và Coupling thấp.
D. Cohesion cao và Coupling cao.
*Đáp án: B*

**Câu 59:** Kiến trúc phần mềm quyết định yếu tố gì?
A. Chi tiết từng dòng code sẽ viết như thế nào.
B. Tên của các biến trong chương trình.
C. Sự tồn tại, vai trò và cách liên kết giữa các thành phần lớn của hệ thống.
D. Màu sắc của giao diện người dùng.
*Đáp án: C*

**Câu 60:** Mô hình kiến trúc nào mà toàn bộ giao diện, xử lý nghiệp vụ và truy xuất dữ liệu nằm gọn trong một khối duy nhất?
A. Mô hình Client-Server.
B. Mô hình 3 tầng (3-tier).
C. Mô hình Microservices.
D. Mô hình Đơn nguyên (Monolithic).
*Đáp án: D*

**Câu 61:** Trong kiến trúc Client-Server, đặc điểm của máy Server là gì?
A. Chỉ dùng để hiển thị giao diện cho người dùng cuối.
B. Gửi các yêu cầu xử lý đến máy Client.
C. Cung cấp dịch vụ, lắng nghe và xử lý các yêu cầu từ nhiều máy Client.
D. Không cần kết nối mạng.
*Đáp án: C*

**Câu 62:** Kiến trúc 3 tầng (3-tier) chia ứng dụng thành các tầng nào?
A. Tầng vật lý, Tầng mạng, Tầng ứng dụng.
B. Tầng giao diện, Tầng nghiệp vụ, Tầng dữ liệu.
C. Tầng Client, Tầng trung gian, Tầng Server.
D. Tầng bảo mật, Tầng xử lý, Tầng lưu trữ.
*Đáp án: B*

**Câu 63:** Đặc điểm nổi bật của thiết kế hướng đối tượng (OOD) là gì?
A. Chia chương trình thành các hàm gọi nhau tuần tự.
B. Không quan tâm đến dữ liệu, chỉ quan tâm luồng xử lý.
C. Nhìn nhận hệ thống như một tập các đối tượng tương tác với nhau thông qua thông báo.
D. Tất cả các biến đều là biến toàn cục.
*Đáp án: C*

**Câu 64:** Tính chất nào giúp che giấu thông tin nội bộ của đối tượng trong OOD?
A. Đa hình (Polymorphism).
B. Kế thừa (Inheritance).
C. Đóng gói (Encapsulation).
D. Trừu tượng (Abstraction).
*Đáp án: C*

**Câu 65:** Trong OOD, một đối tượng phần mềm bao gồm hai thành phần cơ bản nào?
A. Dữ liệu (thuộc tính) và Xử lý (phương thức).
B. Giao diện và Cơ sở dữ liệu.
C. Lớp và Đối tượng.
D. Biến toàn cục và Hàm.
*Đáp án: A*

**Câu 66:** Vai trò chính của Giao diện người dùng (UI) là gì?
A. Xử lý các phép toán phức tạp ở backend.
B. Lưu trữ dữ liệu vĩnh viễn vào ổ cứng.
C. Là nơi diễn ra tương tác, tiếp nhận yêu cầu và phản hồi thông tin cho người sử dụng.
D. Bảo vệ hệ thống khỏi hacker.
*Đáp án: C*

**Câu 67:** Thành phần nào KHÔNG thuộc quy trình xử lý giao diện cơ bản?
A. Xử lý biến cố (Event).
B. Xử lý nhập/xuất dữ liệu.
C. Tối ưu hóa truy vấn SQL dưới database.
D. Cập nhật trạng thái hiển thị trên màn hình.
*Đáp án: C*

**Câu 68:** Xử lý nghiệp vụ (Business Logic) đóng vai trò gì?
A. Bắt các sự kiện click chuột của người dùng.
B. Vẽ các nút bấm, biểu mẫu trên màn hình.
C. Lưu trữ dữ liệu dưới dạng file vật lý.
D. Thực hiện các quy tắc tính toán, kiểm tra và ràng buộc cốt lõi của bài toán.
*Đáp án: D*

**Câu 69:** Quá trình thiết kế phần mềm dựa trên nền tảng chính nào?
A. Mã nguồn đã có sẵn.
B. Hồ sơ phân tích yêu cầu và công nghệ được chọn.
C. Ý kiến cá nhân của lập trình viên.
D. Yêu cầu phần cứng của máy chủ.
*Đáp án: B*

**Câu 70:** Đâu là lợi ích chính của việc thiết kế phần mềm trước khi lập trình?
A. Bỏ qua được bước kiểm thử.
B. Viết mã nguồn nhanh hơn mà không cần hiểu nghiệp vụ.
C. Cung cấp một bản thiết kế giúp các thành viên dễ hiểu, dễ sửa đổi và bảo trì.
D. Giảm chi phí mua bản quyền phần mềm.
*Đáp án: C*

**Câu 71:** Bước nào mô tả sự tồn tại và phụ thuộc của các thành phần ở mức tổng thể?
A. Thiết kế chi tiết.
B. Phân tích yêu cầu.
C. Thiết kế kiến trúc (tổng thể).
D. Cài đặt hệ thống.
*Đáp án: C*

**Câu 72:** Nội dung nào KHÔNG thuộc phạm vi chính của quá trình thiết kế phần mềm?
A. Thiết kế kiến trúc.
B. Khảo sát hiện trạng khách hàng.
C. Thiết kế dữ liệu.
D. Thiết kế giao diện.
*Đáp án: B*

**Câu 73:** Tính gắn kết (Cohesion) trong thiết kế mô tả điều gì?
A. Mức độ phụ thuộc lẫn nhau giữa các module khác nhau.
B. Mức độ liên quan và tập trung vào một nhiệm vụ duy nhất của các phần tử bên trong cùng một module.
C. Số lượng hàm trong một module.
D. Số lượng lỗi phát sinh khi chạy chương trình.
*Đáp án: B*

**Câu 74:** Tính kết dính/phụ thuộc (Coupling) đo lường điều gì?
A. Mức độ độc lập giữa các module với nhau.
B. Số dòng code của một class.
C. Tốc độ xử lý của thuật toán.
D. Số lượng bảng trong cơ sở dữ liệu.
*Đáp án: A*

**Câu 75:** Một thiết kế phần mềm được coi là tốt khi nó đạt tiêu chí nào về Cohesion và Coupling?
A. Cohesion thấp và Coupling cao.
B. Cohesion cao và Coupling thấp.
C. Cohesion thấp và Coupling thấp.
D. Cohesion cao và Coupling cao.
*Đáp án: B*

**Câu 76:** Kiến trúc phần mềm quyết định yếu tố gì?
A. Chi tiết từng dòng code sẽ viết như thế nào.
B. Tên của các biến trong chương trình.
C. Sự tồn tại, vai trò và cách liên kết giữa các thành phần lớn của hệ thống.
D. Màu sắc của giao diện người dùng.
*Đáp án: C*

**Câu 77:** Mô hình kiến trúc nào mà toàn bộ giao diện, xử lý nghiệp vụ và truy xuất dữ liệu nằm gọn trong một khối duy nhất?
A. Mô hình Client-Server.
B. Mô hình 3 tầng (3-tier).
C. Mô hình Microservices.
D. Mô hình Đơn nguyên (Monolithic).
*Đáp án: D*

**Câu 78:** Trong kiến trúc Client-Server, đặc điểm của máy Server là gì?
A. Chỉ dùng để hiển thị giao diện cho người dùng cuối.
B. Gửi các yêu cầu xử lý đến máy Client.
C. Cung cấp dịch vụ, lắng nghe và xử lý các yêu cầu từ nhiều máy Client.
D. Không cần kết nối mạng.
*Đáp án: C*

**Câu 79:** Kiến trúc 3 tầng (3-tier) chia ứng dụng thành các tầng nào?
A. Tầng vật lý, Tầng mạng, Tầng ứng dụng.
B. Tầng giao diện, Tầng nghiệp vụ, Tầng dữ liệu.
C. Tầng Client, Tầng trung gian, Tầng Server.
D. Tầng bảo mật, Tầng xử lý, Tầng lưu trữ.
*Đáp án: B*

**Câu 80:** Đặc điểm nổi bật của thiết kế hướng đối tượng (OOD) là gì?
A. Chia chương trình thành các hàm gọi nhau tuần tự.
B. Không quan tâm đến dữ liệu, chỉ quan tâm luồng xử lý.
C. Nhìn nhận hệ thống như một tập các đối tượng tương tác với nhau thông qua thông báo.
D. Tất cả các biến đều là biến toàn cục.
*Đáp án: C*

**Câu 81:** Tính chất nào giúp che giấu thông tin nội bộ của đối tượng trong OOD?
A. Đa hình (Polymorphism).
B. Kế thừa (Inheritance).
C. Đóng gói (Encapsulation).
D. Trừu tượng (Abstraction).
*Đáp án: C*

**Câu 82:** Trong OOD, một đối tượng phần mềm bao gồm hai thành phần cơ bản nào?
A. Dữ liệu (thuộc tính) và Xử lý (phương thức).
B. Giao diện và Cơ sở dữ liệu.
C. Lớp và Đối tượng.
D. Biến toàn cục và Hàm.
*Đáp án: A*

**Câu 83:** Vai trò chính của Giao diện người dùng (UI) là gì?
A. Xử lý các phép toán phức tạp ở backend.
B. Lưu trữ dữ liệu vĩnh viễn vào ổ cứng.
C. Là nơi diễn ra tương tác, tiếp nhận yêu cầu và phản hồi thông tin cho người sử dụng.
D. Bảo vệ hệ thống khỏi hacker.
*Đáp án: C*

**Câu 84:** Thành phần nào KHÔNG thuộc quy trình xử lý giao diện cơ bản?
A. Xử lý biến cố (Event).
B. Xử lý nhập/xuất dữ liệu.
C. Tối ưu hóa truy vấn SQL dưới database.
D. Cập nhật trạng thái hiển thị trên màn hình.
*Đáp án: C*

**Câu 85:** Xử lý nghiệp vụ (Business Logic) đóng vai trò gì?
A. Bắt các sự kiện click chuột của người dùng.
B. Vẽ các nút bấm, biểu mẫu trên màn hình.
C. Lưu trữ dữ liệu dưới dạng file vật lý.
D. Thực hiện các quy tắc tính toán, kiểm tra và ràng buộc cốt lõi của bài toán.
*Đáp án: D*

**Câu 86:** Quá trình thiết kế phần mềm dựa trên nền tảng chính nào?
A. Mã nguồn đã có sẵn.
B. Hồ sơ phân tích yêu cầu và công nghệ được chọn.
C. Ý kiến cá nhân của lập trình viên.
D. Yêu cầu phần cứng của máy chủ.
*Đáp án: B*

**Câu 87:** Đâu là lợi ích chính của việc thiết kế phần mềm trước khi lập trình?
A. Bỏ qua được bước kiểm thử.
B. Viết mã nguồn nhanh hơn mà không cần hiểu nghiệp vụ.
C. Cung cấp một bản thiết kế giúp các thành viên dễ hiểu, dễ sửa đổi và bảo trì.
D. Giảm chi phí mua bản quyền phần mềm.
*Đáp án: C*

**Câu 88:** Bước nào mô tả sự tồn tại và phụ thuộc của các thành phần ở mức tổng thể?
A. Thiết kế chi tiết.
B. Phân tích yêu cầu.
C. Thiết kế kiến trúc (tổng thể).
D. Cài đặt hệ thống.
*Đáp án: C*

**Câu 89:** Nội dung nào KHÔNG thuộc phạm vi chính của quá trình thiết kế phần mềm?
A. Thiết kế kiến trúc.
B. Khảo sát hiện trạng khách hàng.
C. Thiết kế dữ liệu.
D. Thiết kế giao diện.
*Đáp án: B*

**Câu 90:** Tính gắn kết (Cohesion) trong thiết kế mô tả điều gì?
A. Mức độ phụ thuộc lẫn nhau giữa các module khác nhau.
B. Mức độ liên quan và tập trung vào một nhiệm vụ duy nhất của các phần tử bên trong cùng một module.
C. Số lượng hàm trong một module.
D. Số lượng lỗi phát sinh khi chạy chương trình.
*Đáp án: B*

**Câu 91:** Tính kết dính/phụ thuộc (Coupling) đo lường điều gì?
A. Mức độ độc lập giữa các module với nhau.
B. Số dòng code của một class.
C. Tốc độ xử lý của thuật toán.
D. Số lượng bảng trong cơ sở dữ liệu.
*Đáp án: A*

**Câu 92:** Một thiết kế phần mềm được coi là tốt khi nó đạt tiêu chí nào về Cohesion và Coupling?
A. Cohesion thấp và Coupling cao.
B. Cohesion cao và Coupling thấp.
C. Cohesion thấp và Coupling thấp.
D. Cohesion cao và Coupling cao.
*Đáp án: B*

**Câu 93:** Kiến trúc phần mềm quyết định yếu tố gì?
A. Chi tiết từng dòng code sẽ viết như thế nào.
B. Tên của các biến trong chương trình.
C. Sự tồn tại, vai trò và cách liên kết giữa các thành phần lớn của hệ thống.
D. Màu sắc của giao diện người dùng.
*Đáp án: C*

**Câu 94:** Mô hình kiến trúc nào mà toàn bộ giao diện, xử lý nghiệp vụ và truy xuất dữ liệu nằm gọn trong một khối duy nhất?
A. Mô hình Client-Server.
B. Mô hình 3 tầng (3-tier).
C. Mô hình Microservices.
D. Mô hình Đơn nguyên (Monolithic).
*Đáp án: D*

**Câu 95:** Trong kiến trúc Client-Server, đặc điểm của máy Server là gì?
A. Chỉ dùng để hiển thị giao diện cho người dùng cuối.
B. Gửi các yêu cầu xử lý đến máy Client.
C. Cung cấp dịch vụ, lắng nghe và xử lý các yêu cầu từ nhiều máy Client.
D. Không cần kết nối mạng.
*Đáp án: C*

**Câu 96:** Kiến trúc 3 tầng (3-tier) chia ứng dụng thành các tầng nào?
A. Tầng vật lý, Tầng mạng, Tầng ứng dụng.
B. Tầng giao diện, Tầng nghiệp vụ, Tầng dữ liệu.
C. Tầng Client, Tầng trung gian, Tầng Server.
D. Tầng bảo mật, Tầng xử lý, Tầng lưu trữ.
*Đáp án: B*

**Câu 97:** Đặc điểm nổi bật của thiết kế hướng đối tượng (OOD) là gì?
A. Chia chương trình thành các hàm gọi nhau tuần tự.
B. Không quan tâm đến dữ liệu, chỉ quan tâm luồng xử lý.
C. Nhìn nhận hệ thống như một tập các đối tượng tương tác với nhau thông qua thông báo.
D. Tất cả các biến đều là biến toàn cục.
*Đáp án: C*

**Câu 98:** Tính chất nào giúp che giấu thông tin nội bộ của đối tượng trong OOD?
A. Đa hình (Polymorphism).
B. Kế thừa (Inheritance).
C. Đóng gói (Encapsulation).
D. Trừu tượng (Abstraction).
*Đáp án: C*

**Câu 99:** Trong OOD, một đối tượng phần mềm bao gồm hai thành phần cơ bản nào?
A. Dữ liệu (thuộc tính) và Xử lý (phương thức).
B. Giao diện và Cơ sở dữ liệu.
C. Lớp và Đối tượng.
D. Biến toàn cục và Hàm.
*Đáp án: A*

**Câu 100:** Vai trò chính của Giao diện người dùng (UI) là gì?
A. Xử lý các phép toán phức tạp ở backend.
B. Lưu trữ dữ liệu vĩnh viễn vào ổ cứng.
C. Là nơi diễn ra tương tác, tiếp nhận yêu cầu và phản hồi thông tin cho người sử dụng.
D. Bảo vệ hệ thống khỏi hacker.
*Đáp án: C*

**Câu 101:** Thành phần nào KHÔNG thuộc quy trình xử lý giao diện cơ bản?
A. Xử lý biến cố (Event).
B. Xử lý nhập/xuất dữ liệu.
C. Tối ưu hóa truy vấn SQL dưới database.
D. Cập nhật trạng thái hiển thị trên màn hình.
*Đáp án: C*

**Câu 102:** Xử lý nghiệp vụ (Business Logic) đóng vai trò gì?
A. Bắt các sự kiện click chuột của người dùng.
B. Vẽ các nút bấm, biểu mẫu trên màn hình.
C. Lưu trữ dữ liệu dưới dạng file vật lý.
D. Thực hiện các quy tắc tính toán, kiểm tra và ràng buộc cốt lõi của bài toán.
*Đáp án: D*

**Câu 103:** Quá trình thiết kế phần mềm dựa trên nền tảng chính nào?
A. Mã nguồn đã có sẵn.
B. Hồ sơ phân tích yêu cầu và công nghệ được chọn.
C. Ý kiến cá nhân của lập trình viên.
D. Yêu cầu phần cứng của máy chủ.
*Đáp án: B*

**Câu 104:** Đâu là lợi ích chính của việc thiết kế phần mềm trước khi lập trình?
A. Bỏ qua được bước kiểm thử.
B. Viết mã nguồn nhanh hơn mà không cần hiểu nghiệp vụ.
C. Cung cấp một bản thiết kế giúp các thành viên dễ hiểu, dễ sửa đổi và bảo trì.
D. Giảm chi phí mua bản quyền phần mềm.
*Đáp án: C*

**Câu 105:** Bước nào mô tả sự tồn tại và phụ thuộc của các thành phần ở mức tổng thể?
A. Thiết kế chi tiết.
B. Phân tích yêu cầu.
C. Thiết kế kiến trúc (tổng thể).
D. Cài đặt hệ thống.
*Đáp án: C*

**Câu 106:** Nội dung nào KHÔNG thuộc phạm vi chính của quá trình thiết kế phần mềm?
A. Thiết kế kiến trúc.
B. Khảo sát hiện trạng khách hàng.
C. Thiết kế dữ liệu.
D. Thiết kế giao diện.
*Đáp án: B*

**Câu 107:** Tính gắn kết (Cohesion) trong thiết kế mô tả điều gì?
A. Mức độ phụ thuộc lẫn nhau giữa các module khác nhau.
B. Mức độ liên quan và tập trung vào một nhiệm vụ duy nhất của các phần tử bên trong cùng một module.
C. Số lượng hàm trong một module.
D. Số lượng lỗi phát sinh khi chạy chương trình.
*Đáp án: B*

**Câu 108:** Tính kết dính/phụ thuộc (Coupling) đo lường điều gì?
A. Mức độ độc lập giữa các module với nhau.
B. Số dòng code của một class.
C. Tốc độ xử lý của thuật toán.
D. Số lượng bảng trong cơ sở dữ liệu.
*Đáp án: A*

**Câu 109:** Một thiết kế phần mềm được coi là tốt khi nó đạt tiêu chí nào về Cohesion và Coupling?
A. Cohesion thấp và Coupling cao.
B. Cohesion cao và Coupling thấp.
C. Cohesion thấp và Coupling thấp.
D. Cohesion cao và Coupling cao.
*Đáp án: B*

**Câu 110:** Kiến trúc phần mềm quyết định yếu tố gì?
A. Chi tiết từng dòng code sẽ viết như thế nào.
B. Tên của các biến trong chương trình.
C. Sự tồn tại, vai trò và cách liên kết giữa các thành phần lớn của hệ thống.
D. Màu sắc của giao diện người dùng.
*Đáp án: C*

**Câu 111:** Mô hình kiến trúc nào mà toàn bộ giao diện, xử lý nghiệp vụ và truy xuất dữ liệu nằm gọn trong một khối duy nhất?
A. Mô hình Client-Server.
B. Mô hình 3 tầng (3-tier).
C. Mô hình Microservices.
D. Mô hình Đơn nguyên (Monolithic).
*Đáp án: D*

**Câu 112:** Trong kiến trúc Client-Server, đặc điểm của máy Server là gì?
A. Chỉ dùng để hiển thị giao diện cho người dùng cuối.
B. Gửi các yêu cầu xử lý đến máy Client.
C. Cung cấp dịch vụ, lắng nghe và xử lý các yêu cầu từ nhiều máy Client.
D. Không cần kết nối mạng.
*Đáp án: C*

**Câu 113:** Kiến trúc 3 tầng (3-tier) chia ứng dụng thành các tầng nào?
A. Tầng vật lý, Tầng mạng, Tầng ứng dụng.
B. Tầng giao diện, Tầng nghiệp vụ, Tầng dữ liệu.
C. Tầng Client, Tầng trung gian, Tầng Server.
D. Tầng bảo mật, Tầng xử lý, Tầng lưu trữ.
*Đáp án: B*

**Câu 114:** Đặc điểm nổi bật của thiết kế hướng đối tượng (OOD) là gì?
A. Chia chương trình thành các hàm gọi nhau tuần tự.
B. Không quan tâm đến dữ liệu, chỉ quan tâm luồng xử lý.
C. Nhìn nhận hệ thống như một tập các đối tượng tương tác với nhau thông qua thông báo.
D. Tất cả các biến đều là biến toàn cục.
*Đáp án: C*

**Câu 115:** Tính chất nào giúp che giấu thông tin nội bộ của đối tượng trong OOD?
A. Đa hình (Polymorphism).
B. Kế thừa (Inheritance).
C. Đóng gói (Encapsulation).
D. Trừu tượng (Abstraction).
*Đáp án: C*

**Câu 116:** Trong OOD, một đối tượng phần mềm bao gồm hai thành phần cơ bản nào?
A. Dữ liệu (thuộc tính) và Xử lý (phương thức).
B. Giao diện và Cơ sở dữ liệu.
C. Lớp và Đối tượng.
D. Biến toàn cục và Hàm.
*Đáp án: A*

**Câu 117:** Vai trò chính của Giao diện người dùng (UI) là gì?
A. Xử lý các phép toán phức tạp ở backend.
B. Lưu trữ dữ liệu vĩnh viễn vào ổ cứng.
C. Là nơi diễn ra tương tác, tiếp nhận yêu cầu và phản hồi thông tin cho người sử dụng.
D. Bảo vệ hệ thống khỏi hacker.
*Đáp án: C*

**Câu 118:** Thành phần nào KHÔNG thuộc quy trình xử lý giao diện cơ bản?
A. Xử lý biến cố (Event).
B. Xử lý nhập/xuất dữ liệu.
C. Tối ưu hóa truy vấn SQL dưới database.
D. Cập nhật trạng thái hiển thị trên màn hình.
*Đáp án: C*

**Câu 119:** Xử lý nghiệp vụ (Business Logic) đóng vai trò gì?
A. Bắt các sự kiện click chuột của người dùng.
B. Vẽ các nút bấm, biểu mẫu trên màn hình.
C. Lưu trữ dữ liệu dưới dạng file vật lý.
D. Thực hiện các quy tắc tính toán, kiểm tra và ràng buộc cốt lõi của bài toán.
*Đáp án: D*

**Câu 120:** Quá trình thiết kế phần mềm dựa trên nền tảng chính nào?
A. Mã nguồn đã có sẵn.
B. Hồ sơ phân tích yêu cầu và công nghệ được chọn.
C. Ý kiến cá nhân của lập trình viên.
D. Yêu cầu phần cứng của máy chủ.
*Đáp án: B*

**Câu 121:** Đâu là lợi ích chính của việc thiết kế phần mềm trước khi lập trình?
A. Bỏ qua được bước kiểm thử.
B. Viết mã nguồn nhanh hơn mà không cần hiểu nghiệp vụ.
C. Cung cấp một bản thiết kế giúp các thành viên dễ hiểu, dễ sửa đổi và bảo trì.
D. Giảm chi phí mua bản quyền phần mềm.
*Đáp án: C*

**Câu 122:** Bước nào mô tả sự tồn tại và phụ thuộc của các thành phần ở mức tổng thể?
A. Thiết kế chi tiết.
B. Phân tích yêu cầu.
C. Thiết kế kiến trúc (tổng thể).
D. Cài đặt hệ thống.
*Đáp án: C*

**Câu 123:** Nội dung nào KHÔNG thuộc phạm vi chính của quá trình thiết kế phần mềm?
A. Thiết kế kiến trúc.
B. Khảo sát hiện trạng khách hàng.
C. Thiết kế dữ liệu.
D. Thiết kế giao diện.
*Đáp án: B*

**Câu 124:** Tính gắn kết (Cohesion) trong thiết kế mô tả điều gì?
A. Mức độ phụ thuộc lẫn nhau giữa các module khác nhau.
B. Mức độ liên quan và tập trung vào một nhiệm vụ duy nhất của các phần tử bên trong cùng một module.
C. Số lượng hàm trong một module.
D. Số lượng lỗi phát sinh khi chạy chương trình.
*Đáp án: B*

**Câu 125:** Tính kết dính/phụ thuộc (Coupling) đo lường điều gì?
A. Mức độ độc lập giữa các module với nhau.
B. Số dòng code của một class.
C. Tốc độ xử lý của thuật toán.
D. Số lượng bảng trong cơ sở dữ liệu.
*Đáp án: A*

**Câu 126:** Một thiết kế phần mềm được coi là tốt khi nó đạt tiêu chí nào về Cohesion và Coupling?
A. Cohesion thấp và Coupling cao.
B. Cohesion cao và Coupling thấp.
C. Cohesion thấp và Coupling thấp.
D. Cohesion cao và Coupling cao.
*Đáp án: B*

**Câu 127:** Kiến trúc phần mềm quyết định yếu tố gì?
A. Chi tiết từng dòng code sẽ viết như thế nào.
B. Tên của các biến trong chương trình.
C. Sự tồn tại, vai trò và cách liên kết giữa các thành phần lớn của hệ thống.
D. Màu sắc của giao diện người dùng.
*Đáp án: C*

**Câu 128:** Mô hình kiến trúc nào mà toàn bộ giao diện, xử lý nghiệp vụ và truy xuất dữ liệu nằm gọn trong một khối duy nhất?
A. Mô hình Client-Server.
B. Mô hình 3 tầng (3-tier).
C. Mô hình Microservices.
D. Mô hình Đơn nguyên (Monolithic).
*Đáp án: D*

**Câu 129:** Trong kiến trúc Client-Server, đặc điểm của máy Server là gì?
A. Chỉ dùng để hiển thị giao diện cho người dùng cuối.
B. Gửi các yêu cầu xử lý đến máy Client.
C. Cung cấp dịch vụ, lắng nghe và xử lý các yêu cầu từ nhiều máy Client.
D. Không cần kết nối mạng.
*Đáp án: C*

**Câu 130:** Kiến trúc 3 tầng (3-tier) chia ứng dụng thành các tầng nào?
A. Tầng vật lý, Tầng mạng, Tầng ứng dụng.
B. Tầng giao diện, Tầng nghiệp vụ, Tầng dữ liệu.
C. Tầng Client, Tầng trung gian, Tầng Server.
D. Tầng bảo mật, Tầng xử lý, Tầng lưu trữ.
*Đáp án: B*

**Câu 131:** Đặc điểm nổi bật của thiết kế hướng đối tượng (OOD) là gì?
A. Chia chương trình thành các hàm gọi nhau tuần tự.
B. Không quan tâm đến dữ liệu, chỉ quan tâm luồng xử lý.
C. Nhìn nhận hệ thống như một tập các đối tượng tương tác với nhau thông qua thông báo.
D. Tất cả các biến đều là biến toàn cục.
*Đáp án: C*

**Câu 132:** Tính chất nào giúp che giấu thông tin nội bộ của đối tượng trong OOD?
A. Đa hình (Polymorphism).
B. Kế thừa (Inheritance).
C. Đóng gói (Encapsulation).
D. Trừu tượng (Abstraction).
*Đáp án: C*

**Câu 133:** Trong OOD, một đối tượng phần mềm bao gồm hai thành phần cơ bản nào?
A. Dữ liệu (thuộc tính) và Xử lý (phương thức).
B. Giao diện và Cơ sở dữ liệu.
C. Lớp và Đối tượng.
D. Biến toàn cục và Hàm.
*Đáp án: A*

**Câu 134:** Vai trò chính của Giao diện người dùng (UI) là gì?
A. Xử lý các phép toán phức tạp ở backend.
B. Lưu trữ dữ liệu vĩnh viễn vào ổ cứng.
C. Là nơi diễn ra tương tác, tiếp nhận yêu cầu và phản hồi thông tin cho người sử dụng.
D. Bảo vệ hệ thống khỏi hacker.
*Đáp án: C*

**Câu 135:** Thành phần nào KHÔNG thuộc quy trình xử lý giao diện cơ bản?
A. Xử lý biến cố (Event).
B. Xử lý nhập/xuất dữ liệu.
C. Tối ưu hóa truy vấn SQL dưới database.
D. Cập nhật trạng thái hiển thị trên màn hình.
*Đáp án: C*

**Câu 136:** Xử lý nghiệp vụ (Business Logic) đóng vai trò gì?
A. Bắt các sự kiện click chuột của người dùng.
B. Vẽ các nút bấm, biểu mẫu trên màn hình.
C. Lưu trữ dữ liệu dưới dạng file vật lý.
D. Thực hiện các quy tắc tính toán, kiểm tra và ràng buộc cốt lõi của bài toán.
*Đáp án: D*

**Câu 137:** Quá trình thiết kế phần mềm dựa trên nền tảng chính nào?
A. Mã nguồn đã có sẵn.
B. Hồ sơ phân tích yêu cầu và công nghệ được chọn.
C. Ý kiến cá nhân của lập trình viên.
D. Yêu cầu phần cứng của máy chủ.
*Đáp án: B*

**Câu 138:** Đâu là lợi ích chính của việc thiết kế phần mềm trước khi lập trình?
A. Bỏ qua được bước kiểm thử.
B. Viết mã nguồn nhanh hơn mà không cần hiểu nghiệp vụ.
C. Cung cấp một bản thiết kế giúp các thành viên dễ hiểu, dễ sửa đổi và bảo trì.
D. Giảm chi phí mua bản quyền phần mềm.
*Đáp án: C*

**Câu 139:** Bước nào mô tả sự tồn tại và phụ thuộc của các thành phần ở mức tổng thể?
A. Thiết kế chi tiết.
B. Phân tích yêu cầu.
C. Thiết kế kiến trúc (tổng thể).
D. Cài đặt hệ thống.
*Đáp án: C*

**Câu 140:** Nội dung nào KHÔNG thuộc phạm vi chính của quá trình thiết kế phần mềm?
A. Thiết kế kiến trúc.
B. Khảo sát hiện trạng khách hàng.
C. Thiết kế dữ liệu.
D. Thiết kế giao diện.
*Đáp án: B*

**Câu 141:** Tính gắn kết (Cohesion) trong thiết kế mô tả điều gì?
A. Mức độ phụ thuộc lẫn nhau giữa các module khác nhau.
B. Mức độ liên quan và tập trung vào một nhiệm vụ duy nhất của các phần tử bên trong cùng một module.
C. Số lượng hàm trong một module.
D. Số lượng lỗi phát sinh khi chạy chương trình.
*Đáp án: B*

**Câu 142:** Tính kết dính/phụ thuộc (Coupling) đo lường điều gì?
A. Mức độ độc lập giữa các module với nhau.
B. Số dòng code của một class.
C. Tốc độ xử lý của thuật toán.
D. Số lượng bảng trong cơ sở dữ liệu.
*Đáp án: A*

**Câu 143:** Một thiết kế phần mềm được coi là tốt khi nó đạt tiêu chí nào về Cohesion và Coupling?
A. Cohesion thấp và Coupling cao.
B. Cohesion cao và Coupling thấp.
C. Cohesion thấp và Coupling thấp.
D. Cohesion cao và Coupling cao.
*Đáp án: B*

**Câu 144:** Kiến trúc phần mềm quyết định yếu tố gì?
A. Chi tiết từng dòng code sẽ viết như thế nào.
B. Tên của các biến trong chương trình.
C. Sự tồn tại, vai trò và cách liên kết giữa các thành phần lớn của hệ thống.
D. Màu sắc của giao diện người dùng.
*Đáp án: C*

**Câu 145:** Mô hình kiến trúc nào mà toàn bộ giao diện, xử lý nghiệp vụ và truy xuất dữ liệu nằm gọn trong một khối duy nhất?
A. Mô hình Client-Server.
B. Mô hình 3 tầng (3-tier).
C. Mô hình Microservices.
D. Mô hình Đơn nguyên (Monolithic).
*Đáp án: D*

**Câu 146:** Trong kiến trúc Client-Server, đặc điểm của máy Server là gì?
A. Chỉ dùng để hiển thị giao diện cho người dùng cuối.
B. Gửi các yêu cầu xử lý đến máy Client.
C. Cung cấp dịch vụ, lắng nghe và xử lý các yêu cầu từ nhiều máy Client.
D. Không cần kết nối mạng.
*Đáp án: C*

**Câu 147:** Kiến trúc 3 tầng (3-tier) chia ứng dụng thành các tầng nào?
A. Tầng vật lý, Tầng mạng, Tầng ứng dụng.
B. Tầng giao diện, Tầng nghiệp vụ, Tầng dữ liệu.
C. Tầng Client, Tầng trung gian, Tầng Server.
D. Tầng bảo mật, Tầng xử lý, Tầng lưu trữ.
*Đáp án: B*

**Câu 148:** Đặc điểm nổi bật của thiết kế hướng đối tượng (OOD) là gì?
A. Chia chương trình thành các hàm gọi nhau tuần tự.
B. Không quan tâm đến dữ liệu, chỉ quan tâm luồng xử lý.
C. Nhìn nhận hệ thống như một tập các đối tượng tương tác với nhau thông qua thông báo.
D. Tất cả các biến đều là biến toàn cục.
*Đáp án: C*

**Câu 149:** Tính chất nào giúp che giấu thông tin nội bộ của đối tượng trong OOD?
A. Đa hình (Polymorphism).
B. Kế thừa (Inheritance).
C. Đóng gói (Encapsulation).
D. Trừu tượng (Abstraction).
*Đáp án: C*

**Câu 150:** Trong OOD, một đối tượng phần mềm bao gồm hai thành phần cơ bản nào?
A. Dữ liệu (thuộc tính) và Xử lý (phương thức).
B. Giao diện và Cơ sở dữ liệu.
C. Lớp và Đối tượng.
D. Biến toàn cục và Hàm.
*Đáp án: A*

**Câu 151:** Vai trò chính của Giao diện người dùng (UI) là gì?
A. Xử lý các phép toán phức tạp ở backend.
B. Lưu trữ dữ liệu vĩnh viễn vào ổ cứng.
C. Là nơi diễn ra tương tác, tiếp nhận yêu cầu và phản hồi thông tin cho người sử dụng.
D. Bảo vệ hệ thống khỏi hacker.
*Đáp án: C*

**Câu 152:** Thành phần nào KHÔNG thuộc quy trình xử lý giao diện cơ bản?
A. Xử lý biến cố (Event).
B. Xử lý nhập/xuất dữ liệu.
C. Tối ưu hóa truy vấn SQL dưới database.
D. Cập nhật trạng thái hiển thị trên màn hình.
*Đáp án: C*

**Câu 153:** Xử lý nghiệp vụ (Business Logic) đóng vai trò gì?
A. Bắt các sự kiện click chuột của người dùng.
B. Vẽ các nút bấm, biểu mẫu trên màn hình.
C. Lưu trữ dữ liệu dưới dạng file vật lý.
D. Thực hiện các quy tắc tính toán, kiểm tra và ràng buộc cốt lõi của bài toán.
*Đáp án: D*

**Câu 154:** Quá trình thiết kế phần mềm dựa trên nền tảng chính nào?
A. Mã nguồn đã có sẵn.
B. Hồ sơ phân tích yêu cầu và công nghệ được chọn.
C. Ý kiến cá nhân của lập trình viên.
D. Yêu cầu phần cứng của máy chủ.
*Đáp án: B*

**Câu 155:** Đâu là lợi ích chính của việc thiết kế phần mềm trước khi lập trình?
A. Bỏ qua được bước kiểm thử.
B. Viết mã nguồn nhanh hơn mà không cần hiểu nghiệp vụ.
C. Cung cấp một bản thiết kế giúp các thành viên dễ hiểu, dễ sửa đổi và bảo trì.
D. Giảm chi phí mua bản quyền phần mềm.
*Đáp án: C*

**Câu 156:** Bước nào mô tả sự tồn tại và phụ thuộc của các thành phần ở mức tổng thể?
A. Thiết kế chi tiết.
B. Phân tích yêu cầu.
C. Thiết kế kiến trúc (tổng thể).
D. Cài đặt hệ thống.
*Đáp án: C*

**Câu 157:** Nội dung nào KHÔNG thuộc phạm vi chính của quá trình thiết kế phần mềm?
A. Thiết kế kiến trúc.
B. Khảo sát hiện trạng khách hàng.
C. Thiết kế dữ liệu.
D. Thiết kế giao diện.
*Đáp án: B*

**Câu 158:** Tính gắn kết (Cohesion) trong thiết kế mô tả điều gì?
A. Mức độ phụ thuộc lẫn nhau giữa các module khác nhau.
B. Mức độ liên quan và tập trung vào một nhiệm vụ duy nhất của các phần tử bên trong cùng một module.
C. Số lượng hàm trong một module.
D. Số lượng lỗi phát sinh khi chạy chương trình.
*Đáp án: B*

**Câu 159:** Tính kết dính/phụ thuộc (Coupling) đo lường điều gì?
A. Mức độ độc lập giữa các module với nhau.
B. Số dòng code của một class.
C. Tốc độ xử lý của thuật toán.
D. Số lượng bảng trong cơ sở dữ liệu.
*Đáp án: A*

**Câu 160:** Một thiết kế phần mềm được coi là tốt khi nó đạt tiêu chí nào về Cohesion và Coupling?
A. Cohesion thấp và Coupling cao.
B. Cohesion cao và Coupling thấp.
C. Cohesion thấp và Coupling thấp.
D. Cohesion cao và Coupling cao.
*Đáp án: B*

**Câu 161:** Kiến trúc phần mềm quyết định yếu tố gì?
A. Chi tiết từng dòng code sẽ viết như thế nào.
B. Tên của các biến trong chương trình.
C. Sự tồn tại, vai trò và cách liên kết giữa các thành phần lớn của hệ thống.
D. Màu sắc của giao diện người dùng.
*Đáp án: C*

**Câu 162:** Mô hình kiến trúc nào mà toàn bộ giao diện, xử lý nghiệp vụ và truy xuất dữ liệu nằm gọn trong một khối duy nhất?
A. Mô hình Client-Server.
B. Mô hình 3 tầng (3-tier).
C. Mô hình Microservices.
D. Mô hình Đơn nguyên (Monolithic).
*Đáp án: D*

**Câu 163:** Trong kiến trúc Client-Server, đặc điểm của máy Server là gì?
A. Chỉ dùng để hiển thị giao diện cho người dùng cuối.
B. Gửi các yêu cầu xử lý đến máy Client.
C. Cung cấp dịch vụ, lắng nghe và xử lý các yêu cầu từ nhiều máy Client.
D. Không cần kết nối mạng.
*Đáp án: C*

**Câu 164:** Kiến trúc 3 tầng (3-tier) chia ứng dụng thành các tầng nào?
A. Tầng vật lý, Tầng mạng, Tầng ứng dụng.
B. Tầng giao diện, Tầng nghiệp vụ, Tầng dữ liệu.
C. Tầng Client, Tầng trung gian, Tầng Server.
D. Tầng bảo mật, Tầng xử lý, Tầng lưu trữ.
*Đáp án: B*

**Câu 165:** Đặc điểm nổi bật của thiết kế hướng đối tượng (OOD) là gì?
A. Chia chương trình thành các hàm gọi nhau tuần tự.
B. Không quan tâm đến dữ liệu, chỉ quan tâm luồng xử lý.
C. Nhìn nhận hệ thống như một tập các đối tượng tương tác với nhau thông qua thông báo.
D. Tất cả các biến đều là biến toàn cục.
*Đáp án: C*

**Câu 166:** Tính chất nào giúp che giấu thông tin nội bộ của đối tượng trong OOD?
A. Đa hình (Polymorphism).
B. Kế thừa (Inheritance).
C. Đóng gói (Encapsulation).
D. Trừu tượng (Abstraction).
*Đáp án: C*

**Câu 167:** Trong OOD, một đối tượng phần mềm bao gồm hai thành phần cơ bản nào?
A. Dữ liệu (thuộc tính) và Xử lý (phương thức).
B. Giao diện và Cơ sở dữ liệu.
C. Lớp và Đối tượng.
D. Biến toàn cục và Hàm.
*Đáp án: A*

**Câu 168:** Vai trò chính của Giao diện người dùng (UI) là gì?
A. Xử lý các phép toán phức tạp ở backend.
B. Lưu trữ dữ liệu vĩnh viễn vào ổ cứng.
C. Là nơi diễn ra tương tác, tiếp nhận yêu cầu và phản hồi thông tin cho người sử dụng.
D. Bảo vệ hệ thống khỏi hacker.
*Đáp án: C*

**Câu 169:** Thành phần nào KHÔNG thuộc quy trình xử lý giao diện cơ bản?
A. Xử lý biến cố (Event).
B. Xử lý nhập/xuất dữ liệu.
C. Tối ưu hóa truy vấn SQL dưới database.
D. Cập nhật trạng thái hiển thị trên màn hình.
*Đáp án: C*

**Câu 170:** Xử lý nghiệp vụ (Business Logic) đóng vai trò gì?
A. Bắt các sự kiện click chuột của người dùng.
B. Vẽ các nút bấm, biểu mẫu trên màn hình.
C. Lưu trữ dữ liệu dưới dạng file vật lý.
D. Thực hiện các quy tắc tính toán, kiểm tra và ràng buộc cốt lõi của bài toán.
*Đáp án: D*

**Câu 171:** Quá trình thiết kế phần mềm dựa trên nền tảng chính nào?
A. Mã nguồn đã có sẵn.
B. Hồ sơ phân tích yêu cầu và công nghệ được chọn.
C. Ý kiến cá nhân của lập trình viên.
D. Yêu cầu phần cứng của máy chủ.
*Đáp án: B*

**Câu 172:** Đâu là lợi ích chính của việc thiết kế phần mềm trước khi lập trình?
A. Bỏ qua được bước kiểm thử.
B. Viết mã nguồn nhanh hơn mà không cần hiểu nghiệp vụ.
C. Cung cấp một bản thiết kế giúp các thành viên dễ hiểu, dễ sửa đổi và bảo trì.
D. Giảm chi phí mua bản quyền phần mềm.
*Đáp án: C*

**Câu 173:** Bước nào mô tả sự tồn tại và phụ thuộc của các thành phần ở mức tổng thể?
A. Thiết kế chi tiết.
B. Phân tích yêu cầu.
C. Thiết kế kiến trúc (tổng thể).
D. Cài đặt hệ thống.
*Đáp án: C*

**Câu 174:** Nội dung nào KHÔNG thuộc phạm vi chính của quá trình thiết kế phần mềm?
A. Thiết kế kiến trúc.
B. Khảo sát hiện trạng khách hàng.
C. Thiết kế dữ liệu.
D. Thiết kế giao diện.
*Đáp án: B*

**Câu 175:** Tính gắn kết (Cohesion) trong thiết kế mô tả điều gì?
A. Mức độ phụ thuộc lẫn nhau giữa các module khác nhau.
B. Mức độ liên quan và tập trung vào một nhiệm vụ duy nhất của các phần tử bên trong cùng một module.
C. Số lượng hàm trong một module.
D. Số lượng lỗi phát sinh khi chạy chương trình.
*Đáp án: B*

**Câu 176:** Tính kết dính/phụ thuộc (Coupling) đo lường điều gì?
A. Mức độ độc lập giữa các module với nhau.
B. Số dòng code của một class.
C. Tốc độ xử lý của thuật toán.
D. Số lượng bảng trong cơ sở dữ liệu.
*Đáp án: A*

**Câu 177:** Một thiết kế phần mềm được coi là tốt khi nó đạt tiêu chí nào về Cohesion và Coupling?
A. Cohesion thấp và Coupling cao.
B. Cohesion cao và Coupling thấp.
C. Cohesion thấp và Coupling thấp.
D. Cohesion cao và Coupling cao.
*Đáp án: B*

**Câu 178:** Kiến trúc phần mềm quyết định yếu tố gì?
A. Chi tiết từng dòng code sẽ viết như thế nào.
B. Tên của các biến trong chương trình.
C. Sự tồn tại, vai trò và cách liên kết giữa các thành phần lớn của hệ thống.
D. Màu sắc của giao diện người dùng.
*Đáp án: C*

**Câu 179:** Mô hình kiến trúc nào mà toàn bộ giao diện, xử lý nghiệp vụ và truy xuất dữ liệu nằm gọn trong một khối duy nhất?
A. Mô hình Client-Server.
B. Mô hình 3 tầng (3-tier).
C. Mô hình Microservices.
D. Mô hình Đơn nguyên (Monolithic).
*Đáp án: D*

**Câu 180:** Trong kiến trúc Client-Server, đặc điểm của máy Server là gì?
A. Chỉ dùng để hiển thị giao diện cho người dùng cuối.
B. Gửi các yêu cầu xử lý đến máy Client.
C. Cung cấp dịch vụ, lắng nghe và xử lý các yêu cầu từ nhiều máy Client.
D. Không cần kết nối mạng.
*Đáp án: C*

**Câu 181:** Kiến trúc 3 tầng (3-tier) chia ứng dụng thành các tầng nào?
A. Tầng vật lý, Tầng mạng, Tầng ứng dụng.
B. Tầng giao diện, Tầng nghiệp vụ, Tầng dữ liệu.
C. Tầng Client, Tầng trung gian, Tầng Server.
D. Tầng bảo mật, Tầng xử lý, Tầng lưu trữ.
*Đáp án: B*

**Câu 182:** Đặc điểm nổi bật của thiết kế hướng đối tượng (OOD) là gì?
A. Chia chương trình thành các hàm gọi nhau tuần tự.
B. Không quan tâm đến dữ liệu, chỉ quan tâm luồng xử lý.
C. Nhìn nhận hệ thống như một tập các đối tượng tương tác với nhau thông qua thông báo.
D. Tất cả các biến đều là biến toàn cục.
*Đáp án: C*

**Câu 183:** Tính chất nào giúp che giấu thông tin nội bộ của đối tượng trong OOD?
A. Đa hình (Polymorphism).
B. Kế thừa (Inheritance).
C. Đóng gói (Encapsulation).
D. Trừu tượng (Abstraction).
*Đáp án: C*

**Câu 184:** Trong OOD, một đối tượng phần mềm bao gồm hai thành phần cơ bản nào?
A. Dữ liệu (thuộc tính) và Xử lý (phương thức).
B. Giao diện và Cơ sở dữ liệu.
C. Lớp và Đối tượng.
D. Biến toàn cục và Hàm.
*Đáp án: A*

**Câu 185:** Vai trò chính của Giao diện người dùng (UI) là gì?
A. Xử lý các phép toán phức tạp ở backend.
B. Lưu trữ dữ liệu vĩnh viễn vào ổ cứng.
C. Là nơi diễn ra tương tác, tiếp nhận yêu cầu và phản hồi thông tin cho người sử dụng.
D. Bảo vệ hệ thống khỏi hacker.
*Đáp án: C*

**Câu 186:** Thành phần nào KHÔNG thuộc quy trình xử lý giao diện cơ bản?
A. Xử lý biến cố (Event).
B. Xử lý nhập/xuất dữ liệu.
C. Tối ưu hóa truy vấn SQL dưới database.
D. Cập nhật trạng thái hiển thị trên màn hình.
*Đáp án: C*

**Câu 187:** Xử lý nghiệp vụ (Business Logic) đóng vai trò gì?
A. Bắt các sự kiện click chuột của người dùng.
B. Vẽ các nút bấm, biểu mẫu trên màn hình.
C. Lưu trữ dữ liệu dưới dạng file vật lý.
D. Thực hiện các quy tắc tính toán, kiểm tra và ràng buộc cốt lõi của bài toán.
*Đáp án: D*

**Câu 188:** Quá trình thiết kế phần mềm dựa trên nền tảng chính nào?
A. Mã nguồn đã có sẵn.
B. Hồ sơ phân tích yêu cầu và công nghệ được chọn.
C. Ý kiến cá nhân của lập trình viên.
D. Yêu cầu phần cứng của máy chủ.
*Đáp án: B*

**Câu 189:** Đâu là lợi ích chính của việc thiết kế phần mềm trước khi lập trình?
A. Bỏ qua được bước kiểm thử.
B. Viết mã nguồn nhanh hơn mà không cần hiểu nghiệp vụ.
C. Cung cấp một bản thiết kế giúp các thành viên dễ hiểu, dễ sửa đổi và bảo trì.
D. Giảm chi phí mua bản quyền phần mềm.
*Đáp án: C*

**Câu 190:** Bước nào mô tả sự tồn tại và phụ thuộc của các thành phần ở mức tổng thể?
A. Thiết kế chi tiết.
B. Phân tích yêu cầu.
C. Thiết kế kiến trúc (tổng thể).
D. Cài đặt hệ thống.
*Đáp án: C*

**Câu 191:** Nội dung nào KHÔNG thuộc phạm vi chính của quá trình thiết kế phần mềm?
A. Thiết kế kiến trúc.
B. Khảo sát hiện trạng khách hàng.
C. Thiết kế dữ liệu.
D. Thiết kế giao diện.
*Đáp án: B*

**Câu 192:** Tính gắn kết (Cohesion) trong thiết kế mô tả điều gì?
A. Mức độ phụ thuộc lẫn nhau giữa các module khác nhau.
B. Mức độ liên quan và tập trung vào một nhiệm vụ duy nhất của các phần tử bên trong cùng một module.
C. Số lượng hàm trong một module.
D. Số lượng lỗi phát sinh khi chạy chương trình.
*Đáp án: B*

**Câu 193:** Tính kết dính/phụ thuộc (Coupling) đo lường điều gì?
A. Mức độ độc lập giữa các module với nhau.
B. Số dòng code của một class.
C. Tốc độ xử lý của thuật toán.
D. Số lượng bảng trong cơ sở dữ liệu.
*Đáp án: A*

**Câu 194:** Một thiết kế phần mềm được coi là tốt khi nó đạt tiêu chí nào về Cohesion và Coupling?
A. Cohesion thấp và Coupling cao.
B. Cohesion cao và Coupling thấp.
C. Cohesion thấp và Coupling thấp.
D. Cohesion cao và Coupling cao.
*Đáp án: B*

**Câu 195:** Kiến trúc phần mềm quyết định yếu tố gì?
A. Chi tiết từng dòng code sẽ viết như thế nào.
B. Tên của các biến trong chương trình.
C. Sự tồn tại, vai trò và cách liên kết giữa các thành phần lớn của hệ thống.
D. Màu sắc của giao diện người dùng.
*Đáp án: C*

**Câu 196:** Mô hình kiến trúc nào mà toàn bộ giao diện, xử lý nghiệp vụ và truy xuất dữ liệu nằm gọn trong một khối duy nhất?
A. Mô hình Client-Server.
B. Mô hình 3 tầng (3-tier).
C. Mô hình Microservices.
D. Mô hình Đơn nguyên (Monolithic).
*Đáp án: D*

**Câu 197:** Trong kiến trúc Client-Server, đặc điểm của máy Server là gì?
A. Chỉ dùng để hiển thị giao diện cho người dùng cuối.
B. Gửi các yêu cầu xử lý đến máy Client.
C. Cung cấp dịch vụ, lắng nghe và xử lý các yêu cầu từ nhiều máy Client.
D. Không cần kết nối mạng.
*Đáp án: C*

**Câu 198:** Kiến trúc 3 tầng (3-tier) chia ứng dụng thành các tầng nào?
A. Tầng vật lý, Tầng mạng, Tầng ứng dụng.
B. Tầng giao diện, Tầng nghiệp vụ, Tầng dữ liệu.
C. Tầng Client, Tầng trung gian, Tầng Server.
D. Tầng bảo mật, Tầng xử lý, Tầng lưu trữ.
*Đáp án: B*

**Câu 199:** Đặc điểm nổi bật của thiết kế hướng đối tượng (OOD) là gì?
A. Chia chương trình thành các hàm gọi nhau tuần tự.
B. Không quan tâm đến dữ liệu, chỉ quan tâm luồng xử lý.
C. Nhìn nhận hệ thống như một tập các đối tượng tương tác với nhau thông qua thông báo.
D. Tất cả các biến đều là biến toàn cục.
*Đáp án: C*

**Câu 200:** Tính chất nào giúp che giấu thông tin nội bộ của đối tượng trong OOD?
A. Đa hình (Polymorphism).
B. Kế thừa (Inheritance).
C. Đóng gói (Encapsulation).
D. Trừu tượng (Abstraction).
*Đáp án: C*

**Câu 201:** Trong OOD, một đối tượng phần mềm bao gồm hai thành phần cơ bản nào?
A. Dữ liệu (thuộc tính) và Xử lý (phương thức).
B. Giao diện và Cơ sở dữ liệu.
C. Lớp và Đối tượng.
D. Biến toàn cục và Hàm.
*Đáp án: A*

**Câu 202:** Vai trò chính của Giao diện người dùng (UI) là gì?
A. Xử lý các phép toán phức tạp ở backend.
B. Lưu trữ dữ liệu vĩnh viễn vào ổ cứng.
C. Là nơi diễn ra tương tác, tiếp nhận yêu cầu và phản hồi thông tin cho người sử dụng.
D. Bảo vệ hệ thống khỏi hacker.
*Đáp án: C*

**Câu 203:** Thành phần nào KHÔNG thuộc quy trình xử lý giao diện cơ bản?
A. Xử lý biến cố (Event).
B. Xử lý nhập/xuất dữ liệu.
C. Tối ưu hóa truy vấn SQL dưới database.
D. Cập nhật trạng thái hiển thị trên màn hình.
*Đáp án: C*

**Câu 204:** Xử lý nghiệp vụ (Business Logic) đóng vai trò gì?
A. Bắt các sự kiện click chuột của người dùng.
B. Vẽ các nút bấm, biểu mẫu trên màn hình.
C. Lưu trữ dữ liệu dưới dạng file vật lý.
D. Thực hiện các quy tắc tính toán, kiểm tra và ràng buộc cốt lõi của bài toán.
*Đáp án: D*

**Câu 205:** Quá trình thiết kế phần mềm dựa trên nền tảng chính nào?
A. Mã nguồn đã có sẵn.
B. Hồ sơ phân tích yêu cầu và công nghệ được chọn.
C. Ý kiến cá nhân của lập trình viên.
D. Yêu cầu phần cứng của máy chủ.
*Đáp án: B*

**Câu 206:** Đâu là lợi ích chính của việc thiết kế phần mềm trước khi lập trình?
A. Bỏ qua được bước kiểm thử.
B. Viết mã nguồn nhanh hơn mà không cần hiểu nghiệp vụ.
C. Cung cấp một bản thiết kế giúp các thành viên dễ hiểu, dễ sửa đổi và bảo trì.
D. Giảm chi phí mua bản quyền phần mềm.
*Đáp án: C*

**Câu 207:** Bước nào mô tả sự tồn tại và phụ thuộc của các thành phần ở mức tổng thể?
A. Thiết kế chi tiết.
B. Phân tích yêu cầu.
C. Thiết kế kiến trúc (tổng thể).
D. Cài đặt hệ thống.
*Đáp án: C*

**Câu 208:** Nội dung nào KHÔNG thuộc phạm vi chính của quá trình thiết kế phần mềm?
A. Thiết kế kiến trúc.
B. Khảo sát hiện trạng khách hàng.
C. Thiết kế dữ liệu.
D. Thiết kế giao diện.
*Đáp án: B*

**Câu 209:** Tính gắn kết (Cohesion) trong thiết kế mô tả điều gì?
A. Mức độ phụ thuộc lẫn nhau giữa các module khác nhau.
B. Mức độ liên quan và tập trung vào một nhiệm vụ duy nhất của các phần tử bên trong cùng một module.
C. Số lượng hàm trong một module.
D. Số lượng lỗi phát sinh khi chạy chương trình.
*Đáp án: B*

**Câu 210:** Tính kết dính/phụ thuộc (Coupling) đo lường điều gì?
A. Mức độ độc lập giữa các module với nhau.
B. Số dòng code của một class.
C. Tốc độ xử lý của thuật toán.
D. Số lượng bảng trong cơ sở dữ liệu.
*Đáp án: A*

**Câu 211:** Một thiết kế phần mềm được coi là tốt khi nó đạt tiêu chí nào về Cohesion và Coupling?
A. Cohesion thấp và Coupling cao.
B. Cohesion cao và Coupling thấp.
C. Cohesion thấp và Coupling thấp.
D. Cohesion cao và Coupling cao.
*Đáp án: B*

**Câu 212:** Kiến trúc phần mềm quyết định yếu tố gì?
A. Chi tiết từng dòng code sẽ viết như thế nào.
B. Tên của các biến trong chương trình.
C. Sự tồn tại, vai trò và cách liên kết giữa các thành phần lớn của hệ thống.
D. Màu sắc của giao diện người dùng.
*Đáp án: C*

**Câu 213:** Mô hình kiến trúc nào mà toàn bộ giao diện, xử lý nghiệp vụ và truy xuất dữ liệu nằm gọn trong một khối duy nhất?
A. Mô hình Client-Server.
B. Mô hình 3 tầng (3-tier).
C. Mô hình Microservices.
D. Mô hình Đơn nguyên (Monolithic).
*Đáp án: D*

**Câu 214:** Trong kiến trúc Client-Server, đặc điểm của máy Server là gì?
A. Chỉ dùng để hiển thị giao diện cho người dùng cuối.
B. Gửi các yêu cầu xử lý đến máy Client.
C. Cung cấp dịch vụ, lắng nghe và xử lý các yêu cầu từ nhiều máy Client.
D. Không cần kết nối mạng.
*Đáp án: C*

**Câu 215:** Kiến trúc 3 tầng (3-tier) chia ứng dụng thành các tầng nào?
A. Tầng vật lý, Tầng mạng, Tầng ứng dụng.
B. Tầng giao diện, Tầng nghiệp vụ, Tầng dữ liệu.
C. Tầng Client, Tầng trung gian, Tầng Server.
D. Tầng bảo mật, Tầng xử lý, Tầng lưu trữ.
*Đáp án: B*

**Câu 216:** Đặc điểm nổi bật của thiết kế hướng đối tượng (OOD) là gì?
A. Chia chương trình thành các hàm gọi nhau tuần tự.
B. Không quan tâm đến dữ liệu, chỉ quan tâm luồng xử lý.
C. Nhìn nhận hệ thống như một tập các đối tượng tương tác với nhau thông qua thông báo.
D. Tất cả các biến đều là biến toàn cục.
*Đáp án: C*

**Câu 217:** Tính chất nào giúp che giấu thông tin nội bộ của đối tượng trong OOD?
A. Đa hình (Polymorphism).
B. Kế thừa (Inheritance).
C. Đóng gói (Encapsulation).
D. Trừu tượng (Abstraction).
*Đáp án: C*

**Câu 218:** Trong OOD, một đối tượng phần mềm bao gồm hai thành phần cơ bản nào?
A. Dữ liệu (thuộc tính) và Xử lý (phương thức).
B. Giao diện và Cơ sở dữ liệu.
C. Lớp và Đối tượng.
D. Biến toàn cục và Hàm.
*Đáp án: A*

**Câu 219:** Vai trò chính của Giao diện người dùng (UI) là gì?
A. Xử lý các phép toán phức tạp ở backend.
B. Lưu trữ dữ liệu vĩnh viễn vào ổ cứng.
C. Là nơi diễn ra tương tác, tiếp nhận yêu cầu và phản hồi thông tin cho người sử dụng.
D. Bảo vệ hệ thống khỏi hacker.
*Đáp án: C*

**Câu 220:** Thành phần nào KHÔNG thuộc quy trình xử lý giao diện cơ bản?
A. Xử lý biến cố (Event).
B. Xử lý nhập/xuất dữ liệu.
C. Tối ưu hóa truy vấn SQL dưới database.
D. Cập nhật trạng thái hiển thị trên màn hình.
*Đáp án: C*

**Câu 221:** Xử lý nghiệp vụ (Business Logic) đóng vai trò gì?
A. Bắt các sự kiện click chuột của người dùng.
B. Vẽ các nút bấm, biểu mẫu trên màn hình.
C. Lưu trữ dữ liệu dưới dạng file vật lý.
D. Thực hiện các quy tắc tính toán, kiểm tra và ràng buộc cốt lõi của bài toán.
*Đáp án: D*

**Câu 222:** Quá trình thiết kế phần mềm dựa trên nền tảng chính nào?
A. Mã nguồn đã có sẵn.
B. Hồ sơ phân tích yêu cầu và công nghệ được chọn.
C. Ý kiến cá nhân của lập trình viên.
D. Yêu cầu phần cứng của máy chủ.
*Đáp án: B*

**Câu 223:** Đâu là lợi ích chính của việc thiết kế phần mềm trước khi lập trình?
A. Bỏ qua được bước kiểm thử.
B. Viết mã nguồn nhanh hơn mà không cần hiểu nghiệp vụ.
C. Cung cấp một bản thiết kế giúp các thành viên dễ hiểu, dễ sửa đổi và bảo trì.
D. Giảm chi phí mua bản quyền phần mềm.
*Đáp án: C*

**Câu 224:** Bước nào mô tả sự tồn tại và phụ thuộc của các thành phần ở mức tổng thể?
A. Thiết kế chi tiết.
B. Phân tích yêu cầu.
C. Thiết kế kiến trúc (tổng thể).
D. Cài đặt hệ thống.
*Đáp án: C*

**Câu 225:** Nội dung nào KHÔNG thuộc phạm vi chính của quá trình thiết kế phần mềm?
A. Thiết kế kiến trúc.
B. Khảo sát hiện trạng khách hàng.
C. Thiết kế dữ liệu.
D. Thiết kế giao diện.
*Đáp án: B*

**Câu 226:** Tính gắn kết (Cohesion) trong thiết kế mô tả điều gì?
A. Mức độ phụ thuộc lẫn nhau giữa các module khác nhau.
B. Mức độ liên quan và tập trung vào một nhiệm vụ duy nhất của các phần tử bên trong cùng một module.
C. Số lượng hàm trong một module.
D. Số lượng lỗi phát sinh khi chạy chương trình.
*Đáp án: B*

**Câu 227:** Tính kết dính/phụ thuộc (Coupling) đo lường điều gì?
A. Mức độ độc lập giữa các module với nhau.
B. Số dòng code của một class.
C. Tốc độ xử lý của thuật toán.
D. Số lượng bảng trong cơ sở dữ liệu.
*Đáp án: A*

**Câu 228:** Một thiết kế phần mềm được coi là tốt khi nó đạt tiêu chí nào về Cohesion và Coupling?
A. Cohesion thấp và Coupling cao.
B. Cohesion cao và Coupling thấp.
C. Cohesion thấp và Coupling thấp.
D. Cohesion cao và Coupling cao.
*Đáp án: B*

**Câu 229:** Kiến trúc phần mềm quyết định yếu tố gì?
A. Chi tiết từng dòng code sẽ viết như thế nào.
B. Tên của các biến trong chương trình.
C. Sự tồn tại, vai trò và cách liên kết giữa các thành phần lớn của hệ thống.
D. Màu sắc của giao diện người dùng.
*Đáp án: C*

**Câu 230:** Mô hình kiến trúc nào mà toàn bộ giao diện, xử lý nghiệp vụ và truy xuất dữ liệu nằm gọn trong một khối duy nhất?
A. Mô hình Client-Server.
B. Mô hình 3 tầng (3-tier).
C. Mô hình Microservices.
D. Mô hình Đơn nguyên (Monolithic).
*Đáp án: D*

**Câu 231:** Trong kiến trúc Client-Server, đặc điểm của máy Server là gì?
A. Chỉ dùng để hiển thị giao diện cho người dùng cuối.
B. Gửi các yêu cầu xử lý đến máy Client.
C. Cung cấp dịch vụ, lắng nghe và xử lý các yêu cầu từ nhiều máy Client.
D. Không cần kết nối mạng.
*Đáp án: C*

**Câu 232:** Kiến trúc 3 tầng (3-tier) chia ứng dụng thành các tầng nào?
A. Tầng vật lý, Tầng mạng, Tầng ứng dụng.
B. Tầng giao diện, Tầng nghiệp vụ, Tầng dữ liệu.
C. Tầng Client, Tầng trung gian, Tầng Server.
D. Tầng bảo mật, Tầng xử lý, Tầng lưu trữ.
*Đáp án: B*

**Câu 233:** Đặc điểm nổi bật của thiết kế hướng đối tượng (OOD) là gì?
A. Chia chương trình thành các hàm gọi nhau tuần tự.
B. Không quan tâm đến dữ liệu, chỉ quan tâm luồng xử lý.
C. Nhìn nhận hệ thống như một tập các đối tượng tương tác với nhau thông qua thông báo.
D. Tất cả các biến đều là biến toàn cục.
*Đáp án: C*

**Câu 234:** Tính chất nào giúp che giấu thông tin nội bộ của đối tượng trong OOD?
A. Đa hình (Polymorphism).
B. Kế thừa (Inheritance).
C. Đóng gói (Encapsulation).
D. Trừu tượng (Abstraction).
*Đáp án: C*

**Câu 235:** Trong OOD, một đối tượng phần mềm bao gồm hai thành phần cơ bản nào?
A. Dữ liệu (thuộc tính) và Xử lý (phương thức).
B. Giao diện và Cơ sở dữ liệu.
C. Lớp và Đối tượng.
D. Biến toàn cục và Hàm.
*Đáp án: A*

**Câu 236:** Vai trò chính của Giao diện người dùng (UI) là gì?
A. Xử lý các phép toán phức tạp ở backend.
B. Lưu trữ dữ liệu vĩnh viễn vào ổ cứng.
C. Là nơi diễn ra tương tác, tiếp nhận yêu cầu và phản hồi thông tin cho người sử dụng.
D. Bảo vệ hệ thống khỏi hacker.
*Đáp án: C*

**Câu 237:** Thành phần nào KHÔNG thuộc quy trình xử lý giao diện cơ bản?
A. Xử lý biến cố (Event).
B. Xử lý nhập/xuất dữ liệu.
C. Tối ưu hóa truy vấn SQL dưới database.
D. Cập nhật trạng thái hiển thị trên màn hình.
*Đáp án: C*

**Câu 238:** Xử lý nghiệp vụ (Business Logic) đóng vai trò gì?
A. Bắt các sự kiện click chuột của người dùng.
B. Vẽ các nút bấm, biểu mẫu trên màn hình.
C. Lưu trữ dữ liệu dưới dạng file vật lý.
D. Thực hiện các quy tắc tính toán, kiểm tra và ràng buộc cốt lõi của bài toán.
*Đáp án: D*

**Câu 239:** Quá trình thiết kế phần mềm dựa trên nền tảng chính nào?
A. Mã nguồn đã có sẵn.
B. Hồ sơ phân tích yêu cầu và công nghệ được chọn.
C. Ý kiến cá nhân của lập trình viên.
D. Yêu cầu phần cứng của máy chủ.
*Đáp án: B*

**Câu 240:** Đâu là lợi ích chính của việc thiết kế phần mềm trước khi lập trình?
A. Bỏ qua được bước kiểm thử.
B. Viết mã nguồn nhanh hơn mà không cần hiểu nghiệp vụ.
C. Cung cấp một bản thiết kế giúp các thành viên dễ hiểu, dễ sửa đổi và bảo trì.
D. Giảm chi phí mua bản quyền phần mềm.
*Đáp án: C*

**Câu 241:** Bước nào mô tả sự tồn tại và phụ thuộc của các thành phần ở mức tổng thể?
A. Thiết kế chi tiết.
B. Phân tích yêu cầu.
C. Thiết kế kiến trúc (tổng thể).
D. Cài đặt hệ thống.
*Đáp án: C*

**Câu 242:** Nội dung nào KHÔNG thuộc phạm vi chính của quá trình thiết kế phần mềm?
A. Thiết kế kiến trúc.
B. Khảo sát hiện trạng khách hàng.
C. Thiết kế dữ liệu.
D. Thiết kế giao diện.
*Đáp án: B*

**Câu 243:** Tính gắn kết (Cohesion) trong thiết kế mô tả điều gì?
A. Mức độ phụ thuộc lẫn nhau giữa các module khác nhau.
B. Mức độ liên quan và tập trung vào một nhiệm vụ duy nhất của các phần tử bên trong cùng một module.
C. Số lượng hàm trong một module.
D. Số lượng lỗi phát sinh khi chạy chương trình.
*Đáp án: B*

**Câu 244:** Tính kết dính/phụ thuộc (Coupling) đo lường điều gì?
A. Mức độ độc lập giữa các module với nhau.
B. Số dòng code của một class.
C. Tốc độ xử lý của thuật toán.
D. Số lượng bảng trong cơ sở dữ liệu.
*Đáp án: A*

**Câu 245:** Một thiết kế phần mềm được coi là tốt khi nó đạt tiêu chí nào về Cohesion và Coupling?
A. Cohesion thấp và Coupling cao.
B. Cohesion cao và Coupling thấp.
C. Cohesion thấp và Coupling thấp.
D. Cohesion cao và Coupling cao.
*Đáp án: B*

**Câu 246:** Kiến trúc phần mềm quyết định yếu tố gì?
A. Chi tiết từng dòng code sẽ viết như thế nào.
B. Tên của các biến trong chương trình.
C. Sự tồn tại, vai trò và cách liên kết giữa các thành phần lớn của hệ thống.
D. Màu sắc của giao diện người dùng.
*Đáp án: C*

**Câu 247:** Mô hình kiến trúc nào mà toàn bộ giao diện, xử lý nghiệp vụ và truy xuất dữ liệu nằm gọn trong một khối duy nhất?
A. Mô hình Client-Server.
B. Mô hình 3 tầng (3-tier).
C. Mô hình Microservices.
D. Mô hình Đơn nguyên (Monolithic).
*Đáp án: D*

**Câu 248:** Trong kiến trúc Client-Server, đặc điểm của máy Server là gì?
A. Chỉ dùng để hiển thị giao diện cho người dùng cuối.
B. Gửi các yêu cầu xử lý đến máy Client.
C. Cung cấp dịch vụ, lắng nghe và xử lý các yêu cầu từ nhiều máy Client.
D. Không cần kết nối mạng.
*Đáp án: C*

**Câu 249:** Kiến trúc 3 tầng (3-tier) chia ứng dụng thành các tầng nào?
A. Tầng vật lý, Tầng mạng, Tầng ứng dụng.
B. Tầng giao diện, Tầng nghiệp vụ, Tầng dữ liệu.
C. Tầng Client, Tầng trung gian, Tầng Server.
D. Tầng bảo mật, Tầng xử lý, Tầng lưu trữ.
*Đáp án: B*

**Câu 250:** Đặc điểm nổi bật của thiết kế hướng đối tượng (OOD) là gì?
A. Chia chương trình thành các hàm gọi nhau tuần tự.
B. Không quan tâm đến dữ liệu, chỉ quan tâm luồng xử lý.
C. Nhìn nhận hệ thống như một tập các đối tượng tương tác với nhau thông qua thông báo.
D. Tất cả các biến đều là biến toàn cục.
*Đáp án: C*
