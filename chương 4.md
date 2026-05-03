# CHƯƠNG 4: MÔ HÌNH HÓA PHẦN MỀM (SOFTWARE MODELING)

## PHẦN 1: Câu hỏi tự luận ngắn

1. **Mô hình hóa (Modeling) là gì?**
   *Gợi ý:* Là việc sử dụng hệ thống ký hiệu (đồ họa, toán học, văn bản) để trừu tượng hóa, đơn giản hóa và mô tả các khía cạnh phức tạp của một hệ thống từ nhiều góc nhìn khác nhau.
2. **Tại sao lại cần phải mô hình hóa phần mềm trước khi viết code?**
   *Gợi ý:* Để giảm độ phức tạp, giúp các thành viên trong dự án dễ dàng hiểu, giao tiếp, kiểm tra logic nghiệp vụ và thiết kế kiến trúc trước khi tốn kém chi phí lập trình.
3. **Mô hình hóa theo 'Góc nhìn' (Perspective) mang lại lợi ích gì so với mô hình hóa 'Toàn diện'?**
   *Gợi ý:* Một hệ thống rất phức tạp không thể biểu diễn hết trong một bản vẽ. Chia theo góc nhìn (VD: cấu trúc dữ liệu, luồng xử lý) giúp làm nổi bật khía cạnh cần quan tâm và che giấu các chi tiết không liên quan, tăng hiệu quả giao tiếp.
4. **Kể tên 3 khía cạnh (góc nhìn) chính khi mô hình hóa phần mềm?**
   *Gợi ý:* Mô hình nghiệp vụ (Business Model), Mô hình quan niệm / Dữ liệu (Conceptual/Data Model), và Mô hình yêu cầu / Chức năng (Requirements Model).
5. **UML là viết tắt của từ gì và đóng vai trò gì?**
   *Gợi ý:* Unified Modeling Language (Ngôn ngữ mô hình hóa hợp nhất). Là chuẩn ngôn ngữ đồ họa để đặc tả, thiết kế và tài liệu hóa các hệ thống phần mềm hướng đối tượng.
6. **Mô hình DFD (Data Flow Diagram) tập trung mô tả điều gì?**
   *Gợi ý:* Tập trung vào luồng chảy của dữ liệu xuyên suốt hệ thống, các tiến trình xử lý dữ liệu đó, và nơi lưu trữ dữ liệu. (Phổ biến trong phương pháp hướng cấu trúc).
7. **Mô hình ERD (Entity Relationship Diagram) dùng để làm gì?**
   *Gợi ý:* Dùng để mô hình hóa cấu trúc dữ liệu tĩnh của hệ thống, xác định các thực thể, thuộc tính của thực thể và mối quan hệ giữa chúng.
8. **Sơ đồ ngữ cảnh (Context Diagram) thể hiện điều gì?**
   *Gợi ý:* Thể hiện ranh giới của hệ thống và các tương tác (luồng thông tin) giữa hệ thống với môi trường bên ngoài (các tác nhân, hệ thống khác).
9. **Đặc điểm của hệ thống trong Sơ đồ ngữ cảnh là gì?**
   *Gợi ý:* Toàn bộ hệ thống được xem như một hộp đen (black box) duy nhất ở trung tâm (thường vẽ bằng một hình tròn lớn), không hiển thị chi tiết xử lý bên trong.
10. **Sơ đồ hoạt động (Activity Diagram) trong UML tương đương với loại sơ đồ cổ điển nào?**
    *Gợi ý:* Tương đương với Lưu đồ thuật toán (Flowchart) nhưng mạnh mẽ hơn vì nó hỗ trợ mô tả các luồng xử lý song song (concurrent) và đồng bộ hóa.
11. **Trong UML, kiến trúc '4+1 View Model' bao gồm những góc nhìn nào?**
    *Gợi ý:* Logical View (Logic), Process View (Tiến trình), Development View (Triển khai), Physical View (Vật lý), và tất cả được gắn kết bởi Use-Case View (+1).
12. **Mô hình Use-case (Use-case Model) có tác dụng gì ở giai đoạn đầu dự án?**
    *Gợi ý:* Ghi nhận các chức năng (yêu cầu) mà hệ thống phải cung cấp dưới góc nhìn của người dùng (Actor), giúp xác định phạm vi hệ thống.
13. **Một Actor trong biểu đồ Use-case có thể là gì?**
    *Gợi ý:* Là con người (Khách hàng, Quản trị viên), thiết bị phần cứng, hoặc một hệ thống phần mềm khác tương tác với hệ thống đang xét.
14. **Mối quan hệ <<include>> (Bao gồm) giữa 2 Use-case có ý nghĩa gì?**
    *Gợi ý:* Một Use-case 'Base' bắt buộc gọi một Use-case 'Included' để hoàn thành luồng công việc. Thường dùng để gộp các chức năng trùng lặp.
15. **Mối quan hệ <<extend>> (Mở rộng) có điều kiện gì đặc biệt?**
    *Gợi ý:* Use-case mở rộng chỉ thực thi và chèn thêm hành vi vào Use-case cơ sở tại các Điểm mở rộng (Extension points) khi thỏa mãn một ĐIỀU KIỆN cụ thể.
16. **Trong Sơ đồ trạng thái (State Machine Diagram), điều gì làm kích hoạt sự chuyển trạng thái (Transition)?**
    *Gợi ý:* Sự xuất hiện của một Sự kiện (Event) hoặc khi thỏa mãn một Điều kiện (Guard condition).
17. **Sơ đồ trạng thái (State Diagram) thường được dùng để mô hình hóa cái gì?**
    *Gợi ý:* Vòng đời của một đối tượng phức tạp có nhiều trạng thái khác nhau (VD: Đơn hàng: Khởi tạo -> Đã thanh toán -> Đang giao -> Hoàn thành).
18. **Biểu đồ Tuần tự (Sequence Diagram) tập trung vào khía cạnh nào của hệ thống?**
    *Gợi ý:* Tập trung vào trình tự thời gian (Time-ordering) của các thông điệp (Messages) được gửi và nhận giữa các đối tượng để thực hiện một Use-case.
19. **Thanh sinh tồn (Activation / Execution occurrence) trong Sequence Diagram thể hiện điều gì?**
    *Gợi ý:* Thể hiện khoảng thời gian mà một đối tượng đang thực sự xử lý một tác vụ hoặc đang nắm quyền điều khiển.
20. **Biểu đồ Lớp (Class Diagram) đóng vai trò gì trong quá trình thiết kế phần mềm OOP?**
    *Gợi ý:* Là trung tâm của thiết kế tĩnh, mô tả các lớp, thuộc tính, phương thức và các mối quan hệ (Kế thừa, Liên kết, Phụ thuộc) giữa các lớp.
21. **Mối quan hệ Kế thừa (Generalization) trong biểu đồ lớp có ý nghĩa gì?**
    *Gợi ý:* Biểu diễn quan hệ 'Is-a', lớp con thừa hưởng các thuộc tính và hành vi của lớp cha, giúp tái sử dụng mã nguồn.
22. **Mối quan hệ Aggregation (Tụ hợp) và Composition (Cấu thành) khác nhau cốt lõi ở đâu?**
    *Gợi ý:* Aggregation là quan hệ lỏng lẻo (Part có thể tồn tại độc lập khỏi Whole). Composition là quan hệ chặt chẽ (Part bị hủy khi Whole bị hủy).
23. **Biểu đồ Triển khai (Deployment Diagram) thể hiện kiến trúc gì?**
    *Gợi ý:* Thể hiện kiến trúc phần cứng vật lý của hệ thống (các Node/Máy chủ) và cách các thành phần phần mềm (Artifacts) được phân bổ, cài đặt lên các Node đó.
24. **Forward Engineering (Sinh mã xuôi) trong các công cụ CASE (như Rational Rose) là gì?**
    *Gợi ý:* Là quá trình tự động tạo ra bộ khung mã nguồn (code skeleton) từ các biểu đồ thiết kế UML (như Class Diagram).
25. **Lợi thế lớn nhất của UML so với các ngôn ngữ mô hình hóa trước đó là gì?**
    *Gợi ý:* UML hợp nhất các phương pháp thiết kế hướng đối tượng tốt nhất, trở thành chuẩn quốc tế chung, giúp mọi người trên thế giới có chung một 'ngôn ngữ' giao tiếp kỹ thuật.


## PHẦN 2: Câu hỏi trắc nghiệm (Multiple Choice)

**Câu 1:** Mục tiêu chính của việc Mô hình hóa phần mềm (Software Modeling) là gì?
A. Chỉ để nộp bài tập lớn.
B. Giúp trừu tượng hóa hệ thống, giảm độ phức tạp, giao tiếp thiết kế dễ dàng và kiểm chứng logic trước khi tốn kém chi phí viết mã nguồn.
C. Để chương trình tự động viết code.
D. Để kiểm thử phần mềm tự động.
*Đáp án: B*

**Câu 2:** Mô hình hóa phần mềm theo 'Góc nhìn' (Perspective/View) giúp ích gì?
A. Giảm độ sáng màn hình.
B. Cho phép chia một hệ thống khổng lồ thành nhiều khía cạnh (như cấu trúc tĩnh, luồng dữ liệu động) để làm nổi bật vấn đề cần giải quyết, ẩn đi các chi tiết rối rắm không cần thiết.
C. Giúp tính toán giá cả.
D. Tăng dung lượng đĩa cứng.
*Đáp án: B*

**Câu 3:** UML (Unified Modeling Language) được mô tả chính xác nhất là gì?
A. Là một ngôn ngữ lập trình hướng đối tượng.
B. Là ngôn ngữ hình ảnh (visual language) chuẩn mực quốc tế dùng để đặc tả, xây dựng, trực quan hóa và lập tài liệu các hệ thống hướng đối tượng.
C. Là một hệ quản trị CSDL quan hệ.
D. Là một trình duyệt Web.
*Đáp án: B*

**Câu 4:** Mô hình DFD (Data Flow Diagram) khác ERD (Entity Relationship Diagram) ở điểm cốt lõi nào?
A. DFD dùng cho Java, ERD dùng cho C++.
B. DFD tập trung mô tả 'Sự vận động' của dữ liệu (Process, Flow), còn ERD tập trung mô tả 'Cấu trúc tĩnh' của dữ liệu (Thực thể, Quan hệ).
C. Không có sự khác biệt.
D. DFD không có cơ sở dữ liệu.
*Đáp án: B*

**Câu 5:** Sơ đồ Ngữ cảnh (Context Diagram) thực chất là gì trong hệ thống phân cấp DFD?
A. Là sơ đồ phức tạp nhất.
B. Là sơ đồ mức cao nhất (Mức 0), coi toàn bộ hệ thống là một tiến trình duy nhất (hộp đen) để thấy rõ sự tương tác với môi trường bên ngoài.
C. Là sơ đồ thiết kế CSDL.
D. Là sơ đồ lỗi của hệ thống.
*Đáp án: B*

**Câu 6:** Biểu đồ Use-case (Use-case Diagram) thường được sử dụng nhiều nhất trong giai đoạn nào?
A. Giai đoạn bảo trì.
B. Giai đoạn lấy yêu cầu và phân tích (Inception / Elicitation).
C. Giai đoạn lập trình chi tiết.
D. Giai đoạn triển khai lên Server.
*Đáp án: B*

**Câu 7:** Trong UML, Biểu đồ Lớp (Class Diagram) dùng để mô hình hóa cái gì?
A. Thời gian tải trang web.
B. Cấu trúc tĩnh của hệ thống hướng đối tượng: Các lớp, thuộc tính, phương thức và các mối quan hệ (Kế thừa, Liên kết, v.v.).
C. Các luồng dữ liệu chạy.
D. Các màn hình giao diện.
*Đáp án: B*

**Câu 8:** Biểu đồ Tuần tự (Sequence Diagram) nhấn mạnh vào yếu tố nào khi mô tả sự tương tác?
A. Cấu trúc thư mục của dự án.
B. Thứ tự thời gian (Time ordering) của các thông điệp được gửi qua lại giữa các đối tượng.
C. Sự kế thừa giữa các lớp.
D. Vị trí địa lý của máy chủ.
*Đáp án: B*

**Câu 9:** Trong Biểu đồ Lớp, quan hệ 'Kế thừa' (Generalization) có nghĩa là:
A. Lớp A gọi một hàm của lớp B.
B. Lớp con thừa hưởng tất cả thuộc tính và phương thức của lớp cha, đồng thời có thể định nghĩa thêm các đặc tính chuyên biệt (Mối quan hệ 'Is-a').
C. Lớp A xóa lớp B.
D. Lớp A chứa lớp B.
*Đáp án: B*

**Câu 10:** Trong Biểu đồ Lớp, quan hệ 'Cấu thành' (Composition) biểu thị điều gì?
A. Hai đối tượng không quen biết nhau.
B. Mối quan hệ 'Toàn thể - Bộ phận' rất chặt chẽ. Nếu Toàn thể bị hủy, Bộ phận cũng bị hủy theo.
C. Bộ phận có thể tồn tại độc lập.
D. Một lớp kế thừa một lớp khác.
*Đáp án: B*

**Câu 11:** Mối quan hệ 'Tụ hợp' (Aggregation) khác Composition ở chỗ nào?
A. Nó có màu khác.
B. Aggregation là quan hệ lỏng lẻo hơn. Khi đối tượng Toàn thể bị hủy, đối tượng Bộ phận vẫn có thể tồn tại độc lập.
C. Nó là quan hệ kế thừa.
D. Nó dùng cho CSDL.
*Đáp án: B*

**Câu 12:** Sơ đồ Trạng thái (State Machine Diagram) đặc biệt hữu ích khi thiết kế đối tượng nào?
A. Các đối tượng chỉ lưu tên người dùng.
B. Các đối tượng có vòng đời phức tạp, hành vi thay đổi phụ thuộc mạnh mẽ vào trạng thái hiện tại của nó (Ví dụ: Đơn hàng, Giỏ hàng, Máy ATM).
C. Các màn hình tĩnh.
D. Giao diện người dùng đồ họa.
*Đáp án: B*

**Câu 13:** Một 'Sự kiện' (Event) trong Sơ đồ Trạng thái làm nhiệm vụ gì?
A. Tạo ra lỗi chương trình.
B. Kích hoạt sự chuyển đổi (Transition) từ trạng thái này sang trạng thái khác.
C. Tắt màn hình.
D. Tính toán CSDL.
*Đáp án: B*

**Câu 14:** Sơ đồ Hoạt động (Activity Diagram) có điểm tương đồng với công cụ mô hình hóa truyền thống nào?
A. Sơ đồ mạng nội bộ.
B. Lưu đồ thuật toán (Flowchart).
C. Sơ đồ ERD.
D. Sơ đồ cấu trúc tĩnh.
*Đáp án: B*

**Câu 15:** Một lợi thế vượt trội của Activity Diagram so với Flowchart cổ điển là gì?
A. Vẽ được bằng hình vuông.
B. Có thanh Fork và Join để biểu diễn các luồng xử lý diễn ra song song (Concurrency) và sự đồng bộ hóa.
C. Không có đường thẳng.
D. Dùng cho lập trình Web.
*Đáp án: B*

**Câu 16:** Mô hình kiến trúc '4+1 View' sử dụng View nào làm trung tâm để gắn kết các View còn lại?
A. Logical View (Khung nhìn logic).
B. Use-case View / Scenario View (+1).
C. Process View (Khung nhìn tiến trình).
D. Deployment View (Khung nhìn triển khai).
*Đáp án: B*

**Câu 17:** Trong mô hình 4+1, Deployment View (Khung nhìn triển khai) cung cấp thông tin cho ai?
A. Khách hàng xem cho đẹp.
B. Kỹ sư hệ thống (System Admin), chỉ ra cách phần mềm sẽ được cài đặt lên cấu trúc phần cứng máy chủ, mạng lưới vật lý nào.
C. Người thiết kế UI/UX.
D. Lập trình viên giao diện.
*Đáp án: B*

**Câu 18:** Một Tác nhân (Actor) trong biểu đồ Use-case có thể kế thừa (Generalization) một Tác nhân khác không?
A. Không, UML cấm điều này.
B. Có, Actor con kế thừa toàn bộ quyền truy cập các Use-case của Actor cha và có thể truy cập thêm các Use-case riêng của mình.
C. Có, nhưng bị mất quyền của Actor cha.
D. Actor chỉ được kế thừa Class.
*Đáp án: B*

**Câu 19:** Mối quan hệ <<extend>> trong Use-case được dùng khi nào?
A. Để gộp 2 Use-case thành 1.
B. Để mô tả một hành vi TÙY CHỌN, hoặc một luồng ngoại lệ chỉ được chèn vào Use-case cơ sở khi thỏa mãn một điều kiện nhất định.
C. Đề bắt buộc chạy luồng đó.
D. Không tồn tại quan hệ này.
*Đáp án: B*

**Câu 20:** Đâu là ví dụ đúng về quan hệ <<include>> trong Use-case?
A. Đăng nhập <<include>> Mua hàng.
B. Use-case 'Rút tiền' <<include>> Use-case 'Xác thực mã PIN' (Rút tiền luôn luôn bắt buộc phải xác thực mã PIN).
C. Xem sản phẩm <<include>> Tắt máy.
D. In báo cáo <<include>> Hỏng máy in.
*Đáp án: B*

**Câu 21:** Trong Sequence Diagram, hình chữ nhật nét đứt chạy dọc xuống từ một Object gọi là gì?
A. Đường sinh tồn (Lifeline).
B. Thanh kích hoạt.
C. Cột thời gian.
D. Thông điệp.
*Đáp án: A*

**Câu 22:** Ký hiệu hình chữ nhật đứng (Activation Bar) đặt trên Lifeline trong Sequence Diagram mang ý nghĩa gì?
A. Máy tính bị treo.
B. Thể hiện khoảng thời gian mà Đối tượng đó đang giữ quyền điều khiển hoặc đang thực thi một hàm xử lý.
C. Đối tượng đang ngủ.
D. Lỗi bộ nhớ.
*Đáp án: B*

**Câu 23:** Một 'Thông điệp đồng bộ' (Synchronous Message) trong Sequence Diagram thể hiện hành động gì?
A. Gửi email.
B. Đối tượng gửi gọi một hàm của đối tượng nhận và PHẢI CHỜ (blocked) cho đến khi đối tượng nhận xử lý xong và trả về kết quả.
C. Gửi tin nhắn rồi đi làm việc khác.
D. Đối tượng bị xóa.
*Đáp án: B*

**Câu 24:** Biểu đồ Component (Thành phần) giúp gì cho quá trình phát triển hệ thống?
A. Vẽ giao diện nhanh hơn.
B. Chia hệ thống thành các khối (file dll, jar, dịch vụ) độc lập, có các cổng giao tiếp (Interface) rõ ràng, tăng tính tái sử dụng và quản lý phụ thuộc.
C. Viết CSDL.
D. Hiển thị bảng mã màu.
*Đáp án: B*

**Câu 25:** Ký hiệu 'Dấu cộng (+)' trước một thuộc tính trong Biểu đồ Lớp mang ý nghĩa:
A. Đây là hàm cộng.
B. Quyền truy cập là Public (Công khai).
C. Quyền truy cập là Private (Bí mật).
D. Lỗi phần mềm.
*Đáp án: B*

**Câu 26:** Ký hiệu 'Dấu trừ (-)' trước một phương thức trong Biểu đồ Lớp mang ý nghĩa:
A. Hàm bị xóa.
B. Quyền truy cập là Private (Chỉ dùng bên trong lớp đó).
C. Hàm này rất nguy hiểm.
D. Truy cập Public.
*Đáp án: B*

**Câu 27:** Ký hiệu 'Dấu thăng (#)' trước một thuộc tính trong Biểu đồ Lớp mang ý nghĩa:
A. Bình luận (Comment).
B. Quyền truy cập là Protected (Bảo vệ - Chỉ lớp đó và các lớp kế thừa nó mới được dùng).
C. Lỗi biên dịch.
D. Biến toàn cục.
*Đáp án: B*

**Câu 28:** Multiplicity (Bản số/Đa số) `1..*` trong Biểu đồ Lớp biểu thị:
A. Không có liên kết nào.
B. Từ 1 đến nhiều (Ít nhất là 1, không có giới hạn trên).
C. Đúng 100 đối tượng.
D. Bị xóa khỏi RAM.
*Đáp án: B*

**Câu 29:** Mối quan hệ 'Association' (Kết hợp) giữa Lớp GiảngVien và Lớp MonHoc thường biến thành gì khi lập trình?
A. Một lệnh if.
B. GiảngVien chứa một biến danh sách (List/Array) tham chiếu đến các đối tượng MonHoc.
C. Hai lớp gộp làm một.
D. Xóa lớp MonHoc.
*Đáp án: B*

**Câu 30:** Trong DFD mức 0 (Context Diagram), hệ thống của chúng ta được biểu diễn bằng bao nhiêu Tiến trình (Process)?
A. Hàng ngàn tiến trình.
B. Chỉ có ĐÚNG MỘT tiến trình duy nhất (đại diện cho toàn bộ hệ thống) giao tiếp với các External Entity.
C. Không có tiến trình nào.
D. Tùy ý.
*Đáp án: B*

**Câu 31:** Nguyên tắc 'Cân bằng luồng dữ liệu' (Level Balancing) trong DFD yêu cầu điều gì?
A. Màu sắc phải giống nhau.
B. Các luồng dữ liệu đi vào và đi ra của một Tiến trình ở mức cha PHẢI TƯƠNG ỨNG Y HỆT với tổng các luồng đi vào/ra của các tiến trình con ở sơ đồ phân rã mức dưới.
C. Xóa hết luồng dữ liệu.
D. Dữ liệu tự sinh ra từ hư không.
*Đáp án: B*

**Câu 32:** Một Kho dữ liệu (Data store) trong DFD có thể giao tiếp TRỰC TIẾP với một Thực thể bên ngoài (External Entity) không?
A. Luôn luôn có.
B. Không bao giờ. Mọi tương tác dữ liệu đều phải đi qua một Tiến trình (Process) để xử lý logic.
C. Chỉ khi khách hàng yêu cầu.
D. Tùy vào mạng Internet.
*Đáp án: B*

**Câu 33:** Trong mô hình ERD, một 'Thuộc tính khóa' (Key Attribute) được vẽ như thế nào (theo chuẩn Peter Chen)?
A. Vẽ bằng hình vuông đen.
B. Hình elip với tên thuộc tính được gạch chân.
C. Vẽ bằng mũi tên.
D. Không vẽ lên hình.
*Đáp án: B*

**Câu 34:** Quan hệ N-M (Nhiều - Nhiều) trong ERD (Ví dụ: SinhVien - MonHoc) thường được giải quyết thế nào khi thiết kế cơ sở dữ liệu vật lý?
A. Bỏ qua không lưu trữ.
B. Tạo ra một 'Thực thể kết hợp' (Associative Entity / Bảng trung gian) chứa Khóa ngoại của cả hai bảng để biến thành hai quan hệ 1-N.
C. Gộp 2 bảng làm 1.
D. Chỉ cho phép 1 sinh viên học 1 môn.
*Đáp án: B*

**Câu 35:** Trong UML, Ghi chú (Note) được vẽ bằng ký hiệu gì?
A. Hình tròn.
B. Hình chữ nhật có góc phải phía trên bị gập (Dog-eared rectangle).
C. Hình ngôi sao.
D. Hình thoi.
*Đáp án: B*

**Câu 36:** Khái niệm 'Forward Engineering' trong công cụ mô hình hóa mang ý nghĩa gì?
A. Lái xe về phía trước.
B. Sinh mã nguồn tự động (Code generation) từ các biểu đồ thiết kế (Ví dụ: Sinh ra các file .java từ Biểu đồ Lớp).
C. Xóa toàn bộ mã nguồn.
D. Dịch ngược mã máy.
*Đáp án: B*

**Câu 37:** Khái niệm 'Reverse Engineering' (Kỹ thuật đảo ngược) trong mô hình hóa dùng để:
A. Làm máy tính chạy lùi.
B. Phân tích mã nguồn có sẵn (thường là hệ thống cũ Legacy) để tự động trích xuất và vẽ lại các Biểu đồ UML giúp kỹ sư hiểu kiến trúc hiện tại.
C. Khôi phục file bị xóa.
D. Tắt hệ điều hành.
*Đáp án: B*

**Câu 38:** Biểu đồ Giao tiếp (Communication Diagram) và Biểu đồ Tuần tự (Sequence Diagram) đều là Biểu đồ Tương tác (Interaction). Điểm khác biệt là gì?
A. Không có khác biệt.
B. Sequence tập trung mạnh vào TRỤC THỜI GIAN dọc. Communication không có trục thời gian mà tập trung vào CẤU TRÚC LIÊN KẾT (Topology) giữa các Object.
C. Sequence Diagram chạy được code.
D. Communication dùng cho giao tiếp mạng.
*Đáp án: B*

**Câu 39:** Trong Activity Diagram, Làn bơi (Swimlanes) được dùng để làm gì?
A. Vẽ hình hồ bơi cho đẹp.
B. Phân chia các hoạt động, chỉ rõ Bộ phận/Tác nhân/Hệ thống nào chịu trách nhiệm thực thi hành động đó.
C. Đếm số lượng hành động.
D. Làm tăng tốc độ hệ thống.
*Đáp án: B*

**Câu 40:** Ký hiệu hình chữ nhật bo tròn góc trong Sơ đồ Hoạt động biểu thị:
A. Một dữ liệu.
B. Một Hoạt động (Activity / Action).
C. Một điểm bắt đầu.
D. Một điểm kết thúc.
*Đáp án: B*

**Câu 41:** Trong Sequence Diagram, khi một đối tượng tự hủy, đường Lifeline kết thúc bằng ký hiệu gì?
A. Chữ T.
B. Dấu X lớn.
C. Mũi tên tròn.
D. Một hình vuông đen.
*Đáp án: B*

**Câu 42:** Biểu đồ Đối tượng (Object Diagram) có điểm tương đồng với Biểu đồ nào nhất?
A. Biểu đồ Use-case.
B. Biểu đồ Lớp (Class Diagram), vì nó là một bản chụp (snapshot) các thể hiện cụ thể của các Class cùng với dữ liệu thực tại một thời điểm.
C. Biểu đồ Triển khai.
D. Sơ đồ mạng.
*Đáp án: B*

**Câu 43:** Trong quá trình thiết kế, nếu một Class ôm đồm quá nhiều trách nhiệm (God Object), ta nên làm gì?
A. Khen thưởng lập trình viên.
B. Phân rã (Refactor) lớp đó thành nhiều lớp nhỏ hơn, mỗi lớp giữ một trách nhiệm duy nhất (Single Responsibility Principle) để dễ bảo trì.
C. Tăng kích thước RAM.
D. Xóa lớp đó đi hoàn toàn.
*Đáp án: B*

**Câu 44:** Biểu đồ Thời gian (Timing Diagram) rất quan trọng trong loại hệ thống nào?
A. Hệ thống báo điện tử.
B. Hệ thống điều khiển thời gian thực (Real-time embedded systems), nơi sự chuyển đổi trạng thái phải tuân thủ nghiêm ngặt theo các mốc thời gian (ms).
C. Game giải trí.
D. Phần mềm quản lý nhân sự.
*Đáp án: B*

**Câu 45:** Từ 'Unified' (Hợp nhất) trong UML có nguồn gốc từ đâu?
A. Từ việc hợp nhất các công ty.
B. Sự hợp nhất của 3 phương pháp thiết kế Hướng đối tượng xuất sắc nhất thời bấy giờ: Booch, OMT (Rumbaugh) và OOSE (Jacobson).
C. Từ việc hợp nhất Windows và Mac.
D. Hợp nhất phần cứng và phần mềm.
*Đáp án: B*

**Câu 46:** Mô hình Cấu trúc tĩnh (Static Modeling) bao gồm các biểu đồ nào?
A. Sequence, Activity, State.
B. Class Diagram, Object Diagram, Component Diagram, Deployment Diagram.
C. DFD, Flowchart.
D. Use-case Diagram.
*Đáp án: B*

**Câu 47:** Việc phân tích Use-case (Ví dụ: Từ Use-case Mua hàng vẽ ra Sequence Diagram tương ứng) có tác dụng gì?
A. Giúp tốn thời gian vẽ hình.
B. Ánh xạ yêu cầu của khách hàng (Use-case) thành một thiết kế logic chi tiết của hệ thống (sự tương tác giữa các lớp), đảm bảo không yêu cầu nào bị bỏ sót.
C. Để thay thế mã nguồn.
D. Tính hóa đơn cho khách.
*Đáp án: B*

**Câu 48:** Trong thiết kế hệ thống Lớn, Biểu đồ Package (Gói) giải quyết bài toán gì?
A. Quản lý kho hàng.
B. Tránh sự hỗn loạn khi có hàng trăm Class, bằng cách gom nhóm các Class có liên quan logic với nhau thành các Package để quản lý độ phụ thuộc ở cấp độ cao.
C. Đóng gói file ZIP.
D. Giải nén mã nguồn.
*Đáp án: B*

**Câu 49:** Khi chuyển đổi từ thiết kế Biểu đồ Lớp sang Lập trình thực tế, quá trình này gọi là gì?
A. Reverse Engineering.
B. Implementation / Forward Engineering.
C. Testing.
D. Deployment.
*Đáp án: B*

**Câu 50:** Tại sao UML lại có tính chuẩn mực hóa toàn cầu (ISO standard)?
A. Để bán chứng chỉ.
B. Để các kỹ sư phần mềm trên toàn thế giới, dù sử dụng ngôn ngữ lập trình khác nhau, đều có thể đọc, hiểu thiết kế và giao tiếp mà không có rào cản.
C. Để làm hệ thống chạy nhanh hơn.
D. Để ép mọi người học.
*Đáp án: B*

**Câu 51:** Biểu đồ Lớp (Class Diagram) mô tả khía cạnh nào của hệ thống?
A. Mô tả các luồng dữ liệu (Data flow).
B. Mô tả cấu trúc tĩnh của hệ thống, bao gồm các lớp, thuộc tính, phương thức và các mối quan hệ giữa chúng.
C. Mô tả thời gian chạy của hệ thống.
D. Mô tả vị trí các máy chủ vật lý.
*Đáp án: B*

**Câu 52:** Mối quan hệ Kế thừa (Generalization) trong biểu đồ lớp được sử dụng khi:
A. Hai đối tượng cần gửi tin nhắn cho nhau.
B. Một lớp con (Subclass) mang đầy đủ các đặc tính của một lớp cha (Superclass) và có thể thêm các đặc tính riêng biệt.
C. Khi muốn tạo một cơ sở dữ liệu.
D. Khi muốn vẽ giao diện người dùng.
*Đáp án: B*

**Câu 53:** Trong UML, 'Biểu đồ hoạt động' (Activity Diagram) thường được dùng để thay thế cho loại sơ đồ truyền thống nào?
A. Lưu đồ thuật toán (Flowchart) truyền thống.
B. Mô hình dữ liệu (ERD).
C. Mô hình mạng (Network Diagram).
D. Giao diện màn hình.
*Đáp án: A*

**Câu 54:** Sự khác biệt mạnh mẽ nhất của Activity Diagram (UML) so với Flowchart cổ điển là:
A. Activity Diagram vẽ bằng bút chì.
B. Activity Diagram hỗ trợ biểu diễn các luồng xử lý chạy song song (Concurrency) và sự đồng bộ hóa thông qua các thanh Fork/Join.
C. Activity Diagram không có điều kiện rẽ nhánh (if/else).
D. Flowchart không cho phép lặp.
*Đáp án: B*

**Câu 55:** Biểu đồ Tuần tự (Sequence Diagram) thuộc nhóm biểu đồ nào trong UML?
A. Biểu đồ cấu trúc (Structure Diagrams).
B. Biểu đồ tương tác / hành vi (Interaction / Behavior Diagrams).
C. Biểu đồ triển khai vật lý.
D. Biểu đồ cơ sở dữ liệu.
*Đáp án: B*

**Câu 56:** Trục dọc (từ trên xuống dưới) trong Biểu đồ Tuần tự (Sequence Diagram) đại diện cho cái gì?
A. Thời gian trôi qua.
B. Kích thước bộ nhớ RAM.
C. Số lượng người dùng hệ thống.
D. Giá tiền dự án.
*Đáp án: A*

**Câu 57:** Trong Biểu đồ Tuần tự, 'Message' (Thông điệp) thể hiện điều gì?
A. Một lỗi của chương trình.
B. Sự giao tiếp (ví dụ gọi hàm/phương thức) giữa các đối tượng theo một trình tự thời gian nhất định.
C. Một bình luận của lập trình viên.
D. Một đoạn văn bản hiển thị trên web.
*Đáp án: B*

**Câu 58:** Hình chữ nhật nét đứt chạy dọc theo 'Đường sinh tồn' (Lifeline) của một đối tượng trong Sequence Diagram được gọi là gì?
A. Điểm chết.
B. Thanh kích hoạt / Thanh sinh tồn (Activation Bar / Execution Occurrence), thể hiện đối tượng đang bận xử lý.
C. Lỗi bộ nhớ.
D. Cơ sở dữ liệu.
*Đáp án: B*

**Câu 59:** Để mô tả vòng đời của một đối tượng đơn lẻ qua các sự kiện, ta dùng sơ đồ nào?
A. Biểu đồ Use-case.
B. Sơ đồ Trạng thái (State Machine Diagram / Statechart).
C. Sơ đồ ngữ cảnh.
D. Biểu đồ lớp.
*Đáp án: B*

**Câu 60:** Trong Sơ đồ trạng thái, sự chuyển đổi (Transition) từ trạng thái A sang trạng thái B bị kích hoạt bởi:
A. Người dùng đăng xuất.
B. Sự xuất hiện của một Sự kiện (Event) đáp ứng được Điều kiện bảo vệ (Guard Condition) nếu có.
C. Mất điện máy tính.
D. Lập trình viên xóa code.
*Đáp án: B*

**Câu 61:** Biểu đồ nào trong UML dùng để mô phỏng kiến trúc vật lý (như máy chủ, mạng LAN) và việc cài đặt các phần mềm lên đó?
A. Biểu đồ Đối tượng (Object Diagram).
B. Biểu đồ Triển khai (Deployment Diagram).
C. Biểu đồ Lớp (Class Diagram).
D. Biểu đồ Trạng thái.
*Đáp án: B*

**Câu 62:** Khái niệm 'Node' trong Biểu đồ Triển khai (Deployment Diagram) đại diện cho:
A. Một nút bấm trên màn hình.
B. Một thiết bị phần cứng vật lý (như Server, PC, Router) hoặc môi trường chạy (như OS, Docker container).
C. Một hàm lập trình.
D. Một lỗi phần mềm.
*Đáp án: B*

**Câu 63:** Biểu đồ Thành phần (Component Diagram) thể hiện điều gì?
A. Cấu trúc bảng CSDL.
B. Sự tổ chức, phụ thuộc và kết nối giữa các 'thành phần phần mềm' (components) độc lập (như các file .dll, .jar, hoặc microservices).
C. Sự thay đổi của trạng thái.
D. Danh sách các nhân viên.
*Đáp án: B*

**Câu 64:** Trong quá trình thiết kế, Mối quan hệ 'Aggregation' (Tụ hợp) biểu thị điều gì?
A. Không có quan hệ gì.
B. Quan hệ 'Toàn thể - Bộ phận' (Whole-Part) lỏng lẻo, trong đó Bộ phận (Part) có thể tồn tại độc lập ngay cả khi Toàn thể (Whole) bị hủy.
C. Sự kế thừa hoàn toàn.
D. Hai đối tượng ghét nhau.
*Đáp án: B*

**Câu 65:** Mối quan hệ 'Composition' (Cấu thành) khác với Aggregation ở chỗ nào?
A. Composition dùng mũi tên nét đứt.
B. Composition là quan hệ 'Toàn thể - Bộ phận' chặt chẽ. Khi Toàn thể (Whole) bị hủy, Bộ phận (Part) cũng bị hủy theo (Ví dụ: Ngôi nhà và Phòng).
C. Composition là kế thừa.
D. Không khác nhau.
*Đáp án: B*

**Câu 66:** Một Biểu đồ Lớp (Class Diagram) bao gồm 3 phần chính nào trong một khung hình chữ nhật?
A. Tên file, Ngày tạo, Tên tác giả.
B. Tên Lớp (Class Name), Các Thuộc tính (Attributes), và Các Phương thức/Hàm (Operations/Methods).
C. Cơ sở dữ liệu, Mạng, Giao diện.
D. Lỗi, Cảnh báo, Thông báo.
*Đáp án: B*

**Câu 67:** Trong UML, ký hiệu '+' đứng trước một thuộc tính hoặc phương thức mang ý nghĩa gì?
A. Thuộc tính bị lỗi.
B. Mức truy cập Công khai (Public) - Mọi đối tượng khác đều có thể truy cập.
C. Mức truy cập Riêng tư (Private).
D. Một hàm cộng.
*Đáp án: B*

**Câu 68:** Ký hiệu '-' đứng trước một thuộc tính hoặc phương thức trong UML mang ý nghĩa gì?
A. Một hàm trừ.
B. Mức truy cập Riêng tư (Private) - Chỉ có chính lớp đó mới được phép sử dụng.
C. Bị xóa khỏi hệ thống.
D. Mức truy cập Công khai (Public).
*Đáp án: B*

**Câu 69:** Ký hiệu '#' đứng trước một thuộc tính/phương thức trong UML mang ý nghĩa gì?
A. Dấu thăng hashtag.
B. Mức truy cập Được bảo vệ (Protected) - Lớp cha và các lớp con kế thừa từ nó mới được phép truy cập.
C. Bình luận code.
D. Lỗi biên dịch.
*Đáp án: B*

**Câu 70:** Mối quan hệ 'Association' (Kết hợp) giữa 2 lớp thường được chuyển đổi thành gì khi lập trình?
A. Một bình luận trong code.
B. Một thuộc tính con trỏ/tham chiếu (Reference/Pointer) lưu giữ địa chỉ của đối tượng kia để gọi hàm.
C. Một file ảnh.
D. Một biến kiểu số nguyên.
*Đáp án: B*

**Câu 71:** Khái niệm 'Đa số' (Multiplicity) trên đường nối của Biểu đồ Lớp thể hiện điều gì?
A. Số lượng máy tính cần mua.
B. Xác định số lượng thể hiện (Instance) của một lớp có thể liên kết với một thể hiện của lớp kia (VD: 1..*, 0..1).
C. Số lần chạy của vòng lặp.
D. Số phiên bản phần mềm.
*Đáp án: B*

**Câu 72:** Mô hình Dữ liệu quan niệm (Conceptual Data Model) thường sử dụng sơ đồ nào?
A. Biểu đồ Use-case.
B. Biểu đồ Thực thể Kết hợp (ERD - Entity Relationship Diagram) hoặc Class Diagram ở mức tổng quan.
C. Sơ đồ triển khai.
D. Sơ đồ trạng thái.
*Đáp án: B*

**Câu 73:** Trong mô hình ERD, Thực thể (Entity) đại diện cho cái gì?
A. Một câu lệnh if-else.
B. Một sự vật, đối tượng, khái niệm trong thế giới thực cần được lưu trữ thông tin (VD: Khách hàng, Hóa đơn).
C. Giao diện máy tính.
D. Nút bấm trên bàn phím.
*Đáp án: B*

**Câu 74:** Biểu đồ Đối tượng (Object Diagram) khác Biểu đồ Lớp (Class Diagram) ở điểm nào?
A. Không khác gì.
B. Biểu đồ Lớp mô tả khuôn mẫu tổng quát; Biểu đồ Đối tượng là 'bức ảnh chụp' (Snapshot) các đối tượng có dữ liệu thật cụ thể tại một thời điểm chạy.
C. Object Diagram dùng cho C++.
D. Class Diagram chỉ dành cho Java.
*Đáp án: B*

**Câu 75:** Đâu là một 'Khung nhìn' (View) trong Mô hình Kiến trúc '4+1 View' của Philippe Kruchten?
A. View người dùng (User View).
B. View Logic (Logical View), View Tiến trình (Process View), View Triển khai (Deployment View), View Cài đặt (Development View), và View Use-case (+1).
C. View đồ họa (Graphic View).
D. View cơ sở dữ liệu (Database View).
*Đáp án: B*

**Câu 76:** Khung nhìn Use-case (+1) trong mô hình '4+1 View' có vai trò gì?
A. Chỉ để vẽ cho đẹp.
B. Làm trung tâm kết nối, chứng minh và xác nhận rằng 4 khung nhìn kiến trúc kia thực sự đáp ứng đúng các chức năng nghiệp vụ khách hàng cần.
C. Tính toán giá phần mềm.
D. Chứa mã nguồn chương trình.
*Đáp án: B*

**Câu 77:** Lợi ích của Kỹ thuật Đảo ngược (Reverse Engineering) đối với Mô hình hóa là gì?
A. Xóa mã nguồn đi viết lại.
B. Tự động trích xuất các biểu đồ UML (như Class Diagram) từ một kho mã nguồn cũ có sẵn, giúp kỹ sư nhanh chóng hiểu cấu trúc dự án Legacy.
C. Dịch ngược giao diện thành hình vẽ.
D. Biến phần mềm thành phần cứng.
*Đáp án: B*

**Câu 78:** Sơ đồ nào trong UML phù hợp nhất để mô tả luồng điều khiển của một thuật toán có nhiều vòng lặp và rẽ nhánh?
A. Biểu đồ Lớp.
B. Biểu đồ Hoạt động (Activity Diagram).
C. Sơ đồ Ngữ cảnh.
D. Biểu đồ Triển khai.
*Đáp án: B*

**Câu 79:** Cấu trúc 'Phân rã chức năng' (Functional Decomposition) là đặc trưng của phương pháp nào?
A. Phương pháp thiết kế Hướng đối tượng.
B. Phương pháp phân tích và thiết kế Hướng cấu trúc (Top-down approach).
C. Phương pháp Agile.
D. Phương pháp thiết kế CSDL.
*Đáp án: B*

**Câu 80:** Hạn chế của sơ đồ DFD (Data Flow Diagram) là gì?
A. Vẽ quá tốn mực.
B. Khó thể hiện rõ luồng điều khiển (Control flow), sự rẽ nhánh, vòng lặp và thứ tự thời gian thực thi (Nó chỉ biểu diễn dữ liệu chảy đi đâu).
C. Không thể hiện được dữ liệu.
D. Chỉ dùng cho máy tính cũ.
*Đáp án: B*

**Câu 81:** Trong DFD, ký hiệu mũi tên biểu diễn cái gì?
A. Một hàm số toán học.
B. Luồng dữ liệu (Data flow) đang di chuyển từ nơi này sang nơi khác.
C. Một mối quan hệ kế thừa.
D. Dòng điện của máy chủ.
*Đáp án: B*

**Câu 82:** Mô hình hệ thống (System Model) khác với hệ thống thực tế ở điểm nào?
A. Mô hình đắt tiền hơn.
B. Mô hình là sự trừu tượng hóa, chỉ giữ lại các chi tiết quan trọng cần phân tích và bỏ đi các chi tiết rườm rà không liên quan của hệ thống thực tế.
C. Hệ thống thực tế được vẽ trên giấy.
D. Không có sự khác biệt.
*Đáp án: B*

**Câu 83:** Ký hiệu hình kim cương (Rhombus/Diamond) trong Activity Diagram dùng để làm gì?
A. Tượng trưng cho sự giàu có.
B. Nút Quyết định (Decision node), tại đó luồng xử lý rẽ nhánh theo các điều kiện (Guard conditions) khác nhau.
C. Chấm dứt chương trình.
D. Tạo đối tượng mới.
*Đáp án: B*

**Câu 84:** Thanh dọc đậm (Fork bar) trong Activity Diagram có ý nghĩa gì?
A. Ngăn cấm người dùng truy cập.
B. Nút rẽ nhánh song song (Fork node), chia một luồng xử lý thành nhiều luồng chạy đồng thời cùng một lúc.
C. Một vòng lặp vô tận.
D. Sự hợp nhất dữ liệu.
*Đáp án: B*

**Câu 85:** Trong Biểu đồ Tuần tự, 'Synchronous Message' (Thông điệp đồng bộ) được vẽ bằng mũi tên nét liền, mũi nhọn đặc. Nó thể hiện điều gì?
A. Người gửi gửi tin xong đi làm việc khác ngay.
B. Người gửi gửi thông điệp (gọi hàm) và PHẢI CHỜ người nhận xử lý xong, trả về kết quả rồi mới được chạy tiếp.
C. Máy tính bị treo.
D. Lỗi kết nối mạng.
*Đáp án: B*

**Câu 86:** Trong Biểu đồ Tuần tự, 'Asynchronous Message' (Thông điệp không đồng bộ) thường vẽ bằng mũi tên có mũi nhọn mở. Nó thể hiện điều gì?
A. Lập trình viên không biết viết code.
B. Người gửi gửi thông điệp và TIẾP TỤC làm việc khác ngay lập tức mà KHÔNG CẦN CHỜ người nhận xử lý xong.
C. Người gửi phải chờ cả ngày.
D. Không có dữ liệu gửi đi.
*Đáp án: B*

**Câu 87:** Ký hiệu mũi tên nét đứt trong Biểu đồ Tuần tự mang ý nghĩa gì?
A. Mất kết nối mạng.
B. Thông điệp trả về (Return Message), trả lại kết quả hoặc quyền điều khiển cho đối tượng đã gọi trước đó.
C. Lỗi chương trình.
D. Hủy đối tượng.
*Đáp án: B*

**Câu 88:** Biểu đồ Giao tiếp (Communication Diagram / Collaboration Diagram) có nội dung tương đương với sơ đồ nào nhưng nhấn mạnh vào sự liên kết cấu trúc hơn là trục thời gian?
A. Biểu đồ Trạng thái.
B. Biểu đồ Tuần tự (Sequence Diagram).
C. Sơ đồ ERD.
D. Biểu đồ Hoạt động.
*Đáp án: B*

**Câu 89:** Một 'Package Diagram' (Biểu đồ Gói) dùng để làm gì trong UML?
A. Đóng gói phần mềm ra đĩa CD.
B. Tổ chức, gom nhóm các phần tử (như các Class, Use-case) liên quan lại với nhau thành các module lớn hơn (Packages) để dễ quản lý.
C. Tạo hộp quà tặng khách hàng.
D. Xóa bớt code rác.
*Đáp án: B*

**Câu 90:** Phương pháp phân tích hướng đối tượng (OOA) tìm kiếm cái gì từ tài liệu yêu cầu (ngôn ngữ tự nhiên)?
A. Tìm lỗi chính tả.
B. Tìm các Danh từ (Nouns) để làm ứng viên cho Đối tượng/Lớp, và Động từ (Verbs) để làm ứng viên cho Phương thức/Hành vi.
C. Tìm đoạn văn hay nhất.
D. Đếm số chữ trong tài liệu.
*Đáp án: B*

**Câu 91:** Biểu đồ UML nào thường được dùng TRONG GIAI ĐOẠN ĐẦU để thảo luận yêu cầu với khách hàng phi kỹ thuật?
A. Biểu đồ Lớp chi tiết (Class Diagram).
B. Biểu đồ Use-case (Use-case Diagram) và có thể là Biểu đồ Hoạt động (Activity Diagram).
C. Biểu đồ Triển khai (Deployment Diagram).
D. Mã nguồn C++.
*Đáp án: B*

**Câu 92:** Khi nào thì biểu đồ Lớp (Class Diagram) trở thành một 'Mô hình thiết kế' (Design Model) chi tiết?
A. Khi nó mới chỉ có 1 hình vuông.
B. Khi nó được bổ sung đầy đủ kiểu dữ liệu của biến, kiểu trả về của hàm, các lớp trung gian (Controller/Helper) và các mẫu thiết kế (Design Patterns).
C. Khi nó được vẽ bằng màu đỏ.
D. Khi xóa hết thuộc tính.
*Đáp án: B*

**Câu 93:** Khái niệm 'Mô hình hóa động' (Dynamic Modeling) tập trung vào khía cạnh nào của hệ thống?
A. Cấu trúc bảng CSDL không thay đổi.
B. Sự tương tác, thay đổi trạng thái, và luồng thông tin theo thời gian khi hệ thống đang chạy (Ví dụ: Sequence, State, Activity).
C. Vị trí đặt máy chủ mạng.
D. Dung lượng đĩa cứng.
*Đáp án: B*

**Câu 94:** Trong Biểu đồ Lớp, ký hiệu 'Italic' (In nghiêng) ở tên lớp hoặc tên phương thức mang ý nghĩa gì?
A. Cho đẹp mắt.
B. Đó là một Lớp trừu tượng (Abstract Class) hoặc Phương thức trừu tượng (Abstract Method) - chưa được cài đặt chi tiết.
C. Bị lỗi cú pháp.
D. Bị xóa khỏi hệ thống.
*Đáp án: B*

**Câu 95:** Biểu đồ 'Thời gian' (Timing Diagram) là một dạng đặc biệt của Biểu đồ Tuần tự, nhưng tập trung vào:
A. Lịch trình đi làm của nhân viên.
B. Sự thay đổi trạng thái của đối tượng theo các khoảng thời gian (ràng buộc thời gian thực) rất nghiêm ngặt.
C. Thời gian tải trang web.
D. Đo tuổi thọ phần cứng.
*Đáp án: B*

**Câu 96:** Nếu một đối tượng chỉ tồn tại trong suốt quá trình chạy của một hàm và sau đó bị hủy, thì trong Sequence Diagram đối tượng đó thể hiện thế nào?
A. Không bao giờ được vẽ.
B. Lifeline của nó bắt đầu từ lúc được tạo ra (mũi tên Create) và kết thúc bằng biểu tượng chữ X (Destroy / Hủy đối tượng).
C. Kéo dài vô tận.
D. Biến thành Actor.
*Đáp án: B*

**Câu 97:** Công cụ CASE hỗ trợ 'Mô hình hóa' như Rational Rose mang lại lợi ích tự động hóa nào?
A. Tự pha cà phê.
B. Tự động đồng bộ hóa: Thay đổi trên Biểu đồ Lớp có thể tự cập nhật vào mã nguồn và ngược lại (Round-trip engineering).
C. Tự động tính lương cho lập trình viên.
D. Tự động đăng bài lên mạng xã hội.
*Đáp án: B*

**Câu 98:** Trong sơ đồ Hoạt động (Activity Diagram), ký hiệu 'Swimlanes' (Làn bơi) dùng để làm gì?
A. Vẽ hồ bơi cho lập trình viên.
B. Phân chia các hoạt động/hành động cho các vai trò, tác nhân hoặc bộ phận khác nhau chịu trách nhiệm thực thi chúng.
C. Tăng kích thước bản in.
D. Xóa các luồng điều kiện.
*Đáp án: B*

**Câu 99:** Khái niệm 'Ngữ nghĩa' (Semantics) của UML đảm bảo điều gì?
A. Đảm bảo biểu đồ trông đẹp nhất.
B. Đảm bảo mọi ký hiệu trong UML đều có quy tắc và ý nghĩa rõ ràng, thống nhất, không bị hiểu nhầm bởi các kỹ sư khác nhau.
C. Đảm bảo code không có lỗi.
D. Không ai hiểu được UML.
*Đáp án: B*

**Câu 100:** Tại sao UML lại có tới 14 loại biểu đồ khác nhau (trong UML 2.x)?
A. Vì tác giả thích vẽ nhiều hình.
B. Vì phần mềm quá phức tạp, không một biểu đồ nào có thể thể hiện toàn bộ hệ thống; cần các loại biểu đồ khác nhau để chiếu các 'khung nhìn' tĩnh/động khác nhau.
C. Để bán được nhiều sách hơn.
D. Vì mỗi quốc gia dùng 1 biểu đồ.
*Đáp án: B*

**Câu 101:** Trong DFD (Sơ đồ luồng dữ liệu), hình tròn (hoặc elip) thường được dùng để ký hiệu cái gì?
A. Nơi lưu trữ dữ liệu (Data store).
B. Tiến trình (Process) - Nơi dữ liệu được biến đổi hoặc xử lý.
C. Thực thể bên ngoài (External Entity).
D. Luồng điều khiển (Control flow).
*Đáp án: B*

**Câu 102:** Trong DFD, ký hiệu hai đường thẳng song song nằm ngang thường biểu diễn cái gì?
A. Một chức năng tính toán.
B. Kho dữ liệu (Data store) như file hoặc bảng cơ sở dữ liệu.
C. Khách hàng.
D. Máy in.
*Đáp án: B*

**Câu 103:** Đâu là một quy tắc BẮT BUỘC khi vẽ sơ đồ DFD?
A. Dữ liệu có thể tự động sinh ra mà không cần đầu vào.
B. Luồng dữ liệu không được đi trực tiếp từ Kho dữ liệu này sang Kho dữ liệu khác mà không qua một Tiến trình (Process) xử lý.
C. Thực thể bên ngoài có thể tự động lấy dữ liệu từ Kho dữ liệu.
D. Chỉ được dùng mực đỏ.
*Đáp án: B*

**Câu 104:** Mức độ chi tiết của sơ đồ DFD được thể hiện qua các 'Mức' (Levels). Sơ đồ DFD mức 0 (Level 0) thường được gọi là gì?
A. Sơ đồ chi tiết nhất.
B. Sơ đồ ngữ cảnh (Context Diagram).
C. Sơ đồ dữ liệu vật lý.
D. Sơ đồ mã nguồn.
*Đáp án: B*

**Câu 105:** Trong quá trình 'Phân rã' (Decomposition) DFD, điều gì quan trọng nhất cần phải giữ vững?
A. Tên lập trình viên không đổi.
B. Sự cân bằng luồng dữ liệu (Data Flow Balancing): Đầu vào/Đầu ra ở mức cha phải hoàn toàn khớp với Tổng Đầu vào/Đầu ra ở các tiến trình con phân rã.
C. Thay đổi toàn bộ kho dữ liệu.
D. Tăng số lượng thực thể bên ngoài lên gấp đôi.
*Đáp án: B*

**Câu 106:** Mối quan hệ 1-N (One-to-Many) trong sơ đồ ERD có ý nghĩa gì?
A. Không có liên quan.
B. Một bản ghi của thực thể A có thể liên kết với nhiều bản ghi của thực thể B (Ví dụ: Một Phòng ban có Nhiều Nhân viên).
C. Một thực thể có nhiều tên.
D. Mỗi người chỉ có một máy tính.
*Đáp án: B*

**Câu 107:** Trong mô hình ERD, 'Khóa chính' (Primary Key) của một thực thể có vai trò gì?
A. Để khóa phần mềm lại.
B. Là thuộc tính có giá trị duy nhất dùng để xác định phân biệt từng bản ghi (instance) của thực thể đó (VD: Mã sinh viên).
C. Để lập trình nhanh hơn.
D. Để kết nối Internet.
*Đáp án: B*

**Câu 108:** Khái niệm 'Khóa ngoại' (Foreign Key) trong mô hình dữ liệu dùng để làm gì?
A. Dịch dữ liệu sang tiếng nước ngoài.
B. Là thuộc tính của thực thể này nhưng trỏ đến Khóa chính của thực thể khác, dùng để thiết lập mối quan hệ giữa chúng.
C. Không cho phép người ngoài truy cập.
D. Tăng tốc độ ổ cứng.
*Đáp án: B*

**Câu 109:** Trong ERD, quan hệ N-M (Many-to-Many) thường được xử lý như thế nào trước khi thiết kế vật lý CSDL?
A. Xóa bỏ hoàn toàn.
B. Phân rã thành hai quan hệ 1-N bằng cách tạo ra một Thực thể trung gian (Associative Entity).
C. Chuyển thành quan hệ 1-1.
D. Bỏ qua không thiết kế.
*Đáp án: B*

**Câu 110:** Sơ đồ UML nào phù hợp nhất để vẽ và mô tả lại một Sơ đồ ERD theo cách tiếp cận Hướng đối tượng?
A. Biểu đồ Use-case.
B. Biểu đồ Lớp (Class Diagram) - Ở mức Conceptual, các Lớp tương đương với Thực thể, Liên kết tương đương với Relationship.
C. Sơ đồ hoạt động.
D. Sơ đồ trạng thái.
*Đáp án: B*

**Câu 111:** Đâu là điểm yếu của phương pháp phân tích Hướng cấu trúc (DFD) so với Hướng đối tượng (UML)?
A. DFD không dùng được trên máy tính.
B. DFD tách rời Dữ liệu (ERD) và Xử lý (DFD), khiến việc đồng bộ, thay đổi và tái sử dụng khó khăn. Hướng đối tượng (UML) đóng gói cả hai vào Class.
C. DFD quá hiện đại.
D. DFD chạy tốn điện hơn.
*Đáp án: B*

**Câu 112:** Trong Activity Diagram, ký hiệu hình Oval đen đặc có viền ngoài biểu diễn cái gì?
A. Một lỗi chết người.
B. Điểm kết thúc của toàn bộ luồng hoạt động (Final Node / Activity Final).
C. Điểm bắt đầu dự án.
D. Một nút bấm giao diện.
*Đáp án: B*

**Câu 113:** Khái niệm 'Đa hình' (Polymorphism) trong biểu đồ Lớp (UML) cho phép điều gì?
A. Cho phép phần mềm tự đổi màu nền.
B. Cho phép gọi cùng một tên phương thức nhưng các đối tượng thuộc các lớp con khác nhau sẽ thực thi hàm đó theo cách khác nhau.
C. Cho phép vẽ nhiều hình dạng lộn xộn.
D. Không cho phép lớp nào kế thừa.
*Đáp án: B*

**Câu 114:** Một 'Giao diện' (Interface) trong UML Class Diagram khác gì một Lớp (Class) thông thường?
A. Giao diện có màu xanh.
B. Interface chỉ khai báo tên các phương thức (hành vi) mà không có phần cài đặt thân hàm (no implementation), buộc các lớp 'implements' nó phải tự viết code.
C. Giao diện là màn hình web.
D. Class không có tên.
*Đáp án: B*

**Câu 115:** Ký hiệu mũi tên nét đứt, đầu tam giác rỗng trong Biểu đồ Lớp mang ý nghĩa gì?
A. Sự kế thừa lớp thông thường.
B. Sự Thực thi (Realization) - Một Lớp thực thi (implements) các phương thức đã được khai báo trong một Interface.
C. Lỗi kết nối mạng.
D. Quan hệ chứa đựng.
*Đáp án: B*

**Câu 116:** Trong Sequence Diagram, khung 'alt' (Alternative) đại diện cho khối logic lập trình nào?
A. Vòng lặp for/while.
B. Cấu trúc điều kiện rẽ nhánh (if/else). Chỉ một trong các nhánh điều kiện được thực thi.
C. Khai báo biến.
D. Kết thúc chương trình.
*Đáp án: B*

**Câu 117:** Trong Sequence Diagram, khung 'loop' đại diện cho khối logic lập trình nào?
A. Điều kiện if/else.
B. Sự lặp lại một tập hợp các thông điệp nhiều lần cho đến khi điều kiện thoát được thỏa mãn.
C. Tạo đối tượng mới.
D. Gửi thông báo lỗi.
*Đáp án: B*

**Câu 118:** Sự 'Tự gọi' (Self-Message) trong Biểu đồ Tuần tự xảy ra khi nào?
A. Khi mất mạng.
B. Khi một đối tượng gửi một thông điệp (gọi một hàm bên trong chính nó) để tự xử lý logic nội bộ.
C. Khi người dùng tự nói chuyện một mình.
D. Khi xóa đối tượng.
*Đáp án: B*

**Câu 119:** Mô hình 'Client-Server' có thể được biểu diễn rõ ràng nhất bằng loại biểu đồ UML nào?
A. Sơ đồ trạng thái.
B. Biểu đồ Triển khai (Deployment Diagram) kết hợp với Biểu đồ Thành phần (Component Diagram).
C. Biểu đồ Lớp.
D. Biểu đồ Use-case.
*Đáp án: B*

**Câu 120:** Biểu đồ 'Máy Trạng thái' (State Machine Diagram) cực kỳ hữu ích cho hệ thống nào?
A. Trang web đọc báo tĩnh.
B. Hệ thống điều khiển nhúng, thiết bị phần cứng (như máy ATM, máy bán nước) hoặc đối tượng có quy trình nghiệp vụ dài, trạng thái biến đổi rõ rệt.
C. Ứng dụng máy tính bỏ túi.
D. Phần mềm nghe nhạc.
*Đáp án: B*

**Câu 121:** Lý do chính khiến Kiến trúc sư phần mềm phải vẽ Biểu đồ Thành phần (Component Diagram) là gì?
A. Để vẽ màn hình cho người dùng.
B. Để thấy được cách hệ thống lớn được lắp ghép từ các thư viện, dịch vụ, file thực thi độc lập (đảm bảo tính Tái sử dụng và Dễ bảo trì).
C. Tính toán giá tiền mua server.
D. Không có lợi ích gì.
*Đáp án: B*

**Câu 122:** Khi chuyển đổi từ OOA (Phân tích Hướng đối tượng) sang OOD (Thiết kế Hướng đối tượng), mô hình Lớp sẽ thay đổi thế nào?
A. Bị xóa đi làm lại bằng DFD.
B. Được thêm vào các chi tiết công nghệ (Kiểu dữ liệu thực tế, các lớp Controller quản lý luồng, các lớp Giao diện và Truy cập CSDL).
C. Sẽ chuyển thành sơ đồ trạng thái.
D. Mất đi các thuộc tính.
*Đáp án: B*

**Câu 123:** Nguyên lý 'Single Responsibility' (Đơn trách nhiệm) khi thiết kế Biểu đồ Lớp khuyên chúng ta điều gì?
A. Mỗi lớp phải có hàng ngàn dòng code.
B. Mỗi lớp chỉ nên làm một nhiệm vụ duy nhất và có một lý do duy nhất để thay đổi.
C. Tất cả các chức năng dồn vào 1 lớp.
D. Mỗi lớp chỉ có 1 biến.
*Đáp án: B*

**Câu 124:** Nếu vẽ một Biểu đồ Lớp mà tất cả các đường kết nối đều chĩa vào một Lớp trung tâm khổng lồ, đó là dấu hiệu của lỗi thiết kế gì?
A. Lỗi phần cứng máy chủ.
B. Lớp 'Chúa trời' (God Object / God Class) - ôm đồm quá nhiều chức năng, vi phạm nguyên lý thiết kế, cực kỳ khó bảo trì.
C. Lớp siêu việt tốt nhất.
D. Lớp đó không có lỗi.
*Đáp án: B*

**Câu 125:** Mục tiêu của 'Cân bằng luồng dữ liệu' (Level Balancing) trong DFD là để:
A. Làm đẹp bản vẽ.
B. Đảm bảo không có dữ liệu nào đột nhiên 'biến mất' hoặc 'tự sinh ra' khi phân rã hệ thống từ mức tổng quan xuống mức chi tiết.
C. Giảm số lượng dữ liệu xuống 0.
D. Tăng giá thành phần mềm.
*Đáp án: B*

**Câu 126:** Khi lập trình viên nhận được Biểu đồ Use-case, họ dùng nó để làm gì?
A. Sao chép y nguyên ra màn hình web.
B. Hiểu bức tranh tổng thể các chức năng của hệ thống, từ đó dùng các kịch bản (Scenario) để định hướng lập trình và viết test case kiểm tra.
C. Gửi cho nhà mạng.
D. Làm tài liệu xin việc.
*Đáp án: B*

**Câu 127:** Sự khác biệt giữa Mô hình Hóa hệ thống (System Modeling) và Lập trình (Coding) là gì?
A. Không có sự khác biệt.
B. Mô hình hóa là thiết kế bản vẽ kỹ thuật kiến trúc; Lập trình là thi công, xây dựng thực tế dựa trên bản vẽ đó.
C. Mô hình hóa chạy được, code không chạy được.
D. Lập trình dùng giấy, mô hình dùng máy tính.
*Đáp án: B*

**Câu 128:** Một 'Nút Quyết định' (Decision Node) trong Activity Diagram có tối đa bao nhiêu luồng đầu ra?
A. Chỉ được 1.
B. Từ 2 luồng trở lên, mỗi luồng phải đi kèm một điều kiện (Guard condition) mutually exclusive (loại trừ lẫn nhau).
C. Không có luồng ra.
D. Vô số mà không cần điều kiện.
*Đáp án: B*

**Câu 129:** Nút 'Hợp nhất' (Merge Node) trong Activity Diagram dùng để:
A. Tạo ra lỗi.
B. Gom các luồng rẽ nhánh (từ Decision Node) trở lại thành một luồng xử lý duy nhất.
C. Tắt chương trình.
D. Chạy vòng lặp vô hạn.
*Đáp án: B*

**Câu 130:** Nút 'Join' (Đồng bộ hóa) trong Activity Diagram khác nút 'Merge' (Hợp nhất) ở điểm nào?
A. Giống hệt nhau.
B. Join chờ TẤT CẢ các luồng xử lý song song (song song thực sự) hoàn thành rồi mới gộp lại đi tiếp; Merge chỉ đón nhận 1 trong các luồng rẽ nhánh điều kiện đi tới.
C. Merge chờ tất cả luồng, Join chỉ chờ 1.
D. Cả hai đều đóng phần mềm.
*Đáp án: B*

**Câu 131:** Khái niệm 'Luồng đối tượng' (Object Flow) trong Activity Diagram là gì?
A. Luồng chạy của dòng điện.
B. Mô tả cách một đối tượng được truyền từ hành động (action) này sang hành động khác, và sự thay đổi trạng thái của nó.
C. Sự di chuyển của màn hình máy tính.
D. Danh sách các lỗi.
*Đáp án: B*

**Câu 132:** Trong OOA (Object-Oriented Analysis), việc tìm kiếm các 'Lớp ứng viên' thường bắt đầu từ việc đọc tài liệu gì?
A. Sách dạy lập trình C.
B. Tài liệu Đặc tả Yêu cầu (SRS) hoặc Kịch bản Use-case, đặc biệt chú ý đến các Danh từ chỉ người, vật, hoặc khái niệm nghiệp vụ.
C. Đọc mã nguồn Assembly.
D. Đọc tạp chí thời trang.
*Đáp án: B*

**Câu 133:** Khi mô hình hóa, nếu phát hiện một Lớp chỉ có 1 thuộc tính và không có phương thức nào, kỹ sư thường làm gì?
A. Giữ nguyên và viết code.
B. Hủy bỏ Lớp đó và chuyển nó thành một thuộc tính (Attribute) của một Lớp khác quan trọng hơn để tránh làm phức tạp thiết kế.
C. Đuổi việc người phân tích.
D. Nhân đôi lớp đó lên.
*Đáp án: B*

**Câu 134:** Mối quan hệ 'Phụ thuộc' (Dependency) vẽ bằng mũi tên nét đứt trong Biểu đồ Lớp có nghĩa là gì?
A. Sự kế thừa hoàn toàn.
B. Sự thay đổi của Lớp A có thể ảnh hưởng đến Lớp B (ví dụ Lớp B dùng Lớp A làm tham số truyền vào của một hàm), nhưng B không 'sở hữu' A.
C. Hai lớp không liên quan.
D. Lớp A kế thừa lớp B.
*Đáp án: B*

**Câu 135:** Biểu đồ nào tập trung mạnh nhất vào việc chỉ ra thông điệp nào được gửi TRƯỚC, thông điệp nào gửi SAU?
A. Biểu đồ Use-case.
B. Biểu đồ Tuần tự (Sequence Diagram).
C. Sơ đồ ERD.
D. Sơ đồ Ngữ cảnh.
*Đáp án: B*

**Câu 136:** Một trong những lợi thế của việc sử dụng công cụ CASE vẽ UML (như Enterprise Architect) là 'Traceability' (Truy vết). Nghĩa là:
A. Tìm được vị trí người dùng.
B. Cho phép click vào một Use-case và truy vết thẳng đến các Sequence Diagram, Class Diagram và Code thực thi tương ứng với chức năng đó.
C. Truy vết tốc độ mạng LAN.
D. Truy tìm hacker.
*Đáp án: B*

**Câu 137:** Khi thiết kế Biểu đồ Lớp, tại sao các 'Thuộc tính' (Attributes) thường được thiết lập ở chế độ Private (-)?
A. Cho đẹp mắt.
B. Tuân thủ nguyên lý Đóng gói (Encapsulation), bảo vệ dữ liệu khỏi việc bị chỉnh sửa trực tiếp và tùy tiện từ bên ngoài, chỉ cho phép chỉnh sửa qua các hàm Public (Getter/Setter).
C. Để chương trình chạy nhanh.
D. Làm tăng dung lượng mã nguồn.
*Đáp án: B*

**Câu 138:** Kiến trúc 'MVC' (Model - View - Controller) có thể được ánh xạ vào Biểu đồ Lớp như thế nào?
A. Tất cả đều vẽ trong 1 lớp.
B. Lớp Entity/Model lưu dữ liệu; Lớp Boundary/View xử lý giao diện; Lớp Control chứa luồng nghiệp vụ xử lý chính.
C. Bỏ qua lớp Controller.
D. Chỉ có lớp View.
*Đáp án: B*

**Câu 139:** Khái niệm 'Cường độ' (Cardinality / Multiplicity) `0..1` trong Biểu đồ Lớp có nghĩa là gì?
A. Có vô hạn đối tượng.
B. Một đối tượng bên này có thể KHÔNG liên kết (0), hoặc liên kết TỐI ĐA VỚI MỘT (1) đối tượng bên kia.
C. Luôn luôn bắt buộc phải có 1 đối tượng.
D. Phải có ít nhất 2 đối tượng.
*Đáp án: B*

**Câu 140:** Ký hiệu `*` (dấu sao) trong Multiplicity của Biểu đồ Lớp mang ý nghĩa gì?
A. Lỗi cú pháp.
B. Nhiều (Từ 0 đến vô hạn).
C. Đúng 100 đối tượng.
D. Thuộc tính bí mật.
*Đáp án: B*

**Câu 141:** Việc tạo ra một Mô hình Hệ thống Tốt sẽ giúp tiết kiệm chi phí ở giai đoạn nào nhiều nhất?
A. Giai đoạn lấy yêu cầu.
B. Giai đoạn Bảo trì, vì mã nguồn được cấu trúc tốt, rõ ràng và dễ mở rộng/sửa lỗi.
C. Giai đoạn triển khai máy chủ.
D. Giai đoạn thanh toán tiền điện.
*Đáp án: B*

**Câu 142:** Mô hình 4+1 View giúp trả lời câu hỏi gì trong phát triển phần mềm?
A. Cách viết mã nguồn C++.
B. Giúp đảm bảo rằng kiến trúc hệ thống phục vụ đầy đủ yêu cầu của nhiều nhóm đối tượng khác nhau (Khách hàng, Lập trình viên, Quản trị hệ thống, Kỹ sư tích hợp).
C. Tính toán dung lượng ổ cứng tối đa.
D. Xác định thời gian ăn trưa.
*Đáp án: B*

**Câu 143:** Một 'Actor' trong Use-case có thể là một Hệ thống CSDL bên ngoài không?
A. Không, Actor phải là người.
B. Có, nếu hệ thống phần mềm của chúng ta tương tác (gửi/nhận dữ liệu) với Hệ thống CSDL đó thì nó đóng vai trò là một Actor hỗ trợ.
C. Chỉ khi khách hàng cho phép.
D. Hệ thống CSDL luôn nằm bên trong hệ thống của chúng ta.
*Đáp án: B*

**Câu 144:** Trong Activity Diagram, luồng chạy vào một Action có thể từ mấy nhánh?
A. Chỉ được 1.
B. Có thể từ nhiều nhánh đi vào, và khi 1 nhánh đi tới thì Action đó lập tức được kích hoạt (trừ khi dùng nút Join).
C. Không có luồng đi vào.
D. Bắt buộc phải qua nút Decision trước.
*Đáp án: B*

**Câu 145:** Nếu không có Biểu đồ Triển khai (Deployment Diagram), Kỹ sư hệ thống (System Admin) sẽ gặp khó khăn gì?
A. Không biết viết mã HTML.
B. Không biết hệ thống cần bao nhiêu Server vật lý, cài đặt CSDL ở đâu, Web server ở đâu, cấu hình mạng, tường lửa và giao thức kết nối thế nào.
C. Không biết giao diện có màu gì.
D. Không biết ai là khách hàng.
*Đáp án: B*

**Câu 146:** Khi làm việc với các hệ thống Legacy (Di sản) phức tạp, sơ đồ UML đầu tiên người ta thường cố gắng thiết lập lại là gì?
A. Sơ đồ trạng thái của 1 nút bấm.
B. Sơ đồ Lớp ở mức cấu trúc và Sơ đồ Thành phần để nhìn thấy bức tranh tổng quát của hệ thống cũ.
C. Sơ đồ mạng LAN.
D. Sơ đồ triển khai.
*Đáp án: B*

**Câu 147:** Mô hình Hướng đối tượng mang lại sự 'Tái sử dụng' (Reusability) thông qua cơ chế nào?
A. Copy/Paste mã nguồn.
B. Đóng gói (Encapsulation), Kế thừa (Generalization) và Lập trình giao diện (Polymorphism) tạo ra các Class độc lập, có thể dùng lại ở dự án khác.
C. Xóa bỏ tài liệu thiết kế.
D. Không cho phép người ngoài đọc code.
*Đáp án: B*

**Câu 148:** Việc vẽ biểu đồ UML quá chi tiết ở ngay ngày đầu tiên của một dự án Agile/Scrum có phải là cách tiếp cận tốt không?
A. Rất tốt, bắt buộc phải làm.
B. Không, Agile đề cao 'Mô hình hóa linh hoạt' (Agile Modeling) - chỉ vẽ ở mức cần thiết (barely good enough) để hiểu thiết kế, không lãng phí thời gian vẽ quá chi tiết khi yêu cầu sẽ thay đổi.
C. Làm Agile không được phép dùng UML.
D. Chỉ vẽ khi khách hàng trả thêm tiền.
*Đáp án: B*

**Câu 149:** Mục tiêu cuối cùng của toàn bộ chương 'Mô hình hóa phần mềm' là gì?
A. Học thuộc cách vẽ mũi tên.
B. Cung cấp bộ công cụ tư duy và đồ họa chuẩn mực giúp nhóm dự án giao tiếp, thiết kế cấu trúc vững chắc và kiểm soát độ phức tạp trước khi lập trình.
C. Chỉ để thi trắc nghiệm lấy điểm cao.
D. Làm phức tạp hóa việc phát triển phần mềm.
*Đáp án: B*

**Câu 150:** Tại sao thiết kế kiến trúc phần mềm lại được coi là quyết định sống còn của dự án?
A. Để báo cáo cho quản lý.
B. Kiến trúc tốt tạo nền móng vững chắc giúp mở rộng dễ dàng và giảm thiểu tác động của những thay đổi trong tương lai. Nếu kiến trúc sai, dự án có thể thất bại hoàn toàn.
C. Để tăng số lượng file mã nguồn.
D. Không quan trọng bằng giao diện.
*Đáp án: B*

**Câu 151:** Trong quy trình phần mềm hướng đối tượng (như RUP), mô hình nào thường được phát triển ĐẦU TIÊN?
A. Mô hình Lớp (Class Model).
B. Mô hình Use-case (Use-case Model) để xác định yêu cầu và phạm vi chức năng.
C. Mô hình Triển khai.
D. Mô hình cơ sở dữ liệu vật lý.
*Đáp án: B*

**Câu 152:** Mối quan hệ 'Bao hàm' (Include) trong Use-case có đặc điểm gì quan trọng?
A. Không bắt buộc phải chạy.
B. Hành vi của Use-case Include là BẮT BUỘC để hoàn thành luồng sự kiện của Use-case gốc, và nó thường được dùng để tránh lặp code (gom các bước chung).
C. Chỉ chạy khi có lỗi.
D. Nó là một Use-case cha.
*Đáp án: B*

**Câu 153:** Điều kiện để một Use-case Mở rộng (Extend) được kích hoạt là gì?
A. Nó tự động chạy bất cứ lúc nào.
B. Nó chỉ chạy khi đạt đến một 'Điểm mở rộng' (Extension Point) cụ thể trong Use-case gốc VÀ thỏa mãn một 'Điều kiện' (Guard condition).
C. Khi mất mạng Internet.
D. Nó bắt buộc chạy trước Use-case gốc.
*Đáp án: B*

**Câu 154:** Trong Sơ đồ Lớp, ký hiệu hình Thoi (Diamond) RỖNG đặt ở một đầu của liên kết mang ý nghĩa gì?
A. Mối quan hệ Kế thừa.
B. Mối quan hệ Tụ hợp (Aggregation) - Thể hiện mối quan hệ 'Toàn thể - Bộ phận' lỏng lẻo.
C. Mối quan hệ Phụ thuộc.
D. Giao diện (Interface).
*Đáp án: B*

**Câu 155:** Trong Sơ đồ Lớp, ký hiệu hình Thoi ĐẶC (đen) mang ý nghĩa gì?
A. Mối quan hệ Tụ hợp.
B. Mối quan hệ Cấu thành (Composition) - Quan hệ 'Toàn thể - Bộ phận' chặt chẽ, bộ phận sống chết theo toàn thể.
C. Mối quan hệ Kết hợp (Association).
D. Mối quan hệ Kế thừa.
*Đáp án: B*

**Câu 156:** Một lớp (Class) 'Hóa Đơn' và lớp 'Chi tiết Hóa Đơn' thường có mối quan hệ gì?
A. Kế thừa.
B. Cấu thành (Composition) - Vì Chi tiết Hóa Đơn không có ý nghĩa tồn tại nếu Hóa Đơn bị hủy bỏ.
C. Phụ thuộc.
D. Tụ hợp lỏng lẻo.
*Đáp án: B*

**Câu 157:** Biểu đồ Lớp (Class Diagram) được coi là tài liệu trung tâm cho ai trong đội dự án?
A. Giám đốc bán hàng.
B. Lập trình viên, vì nó ánh xạ trực tiếp nhất ra mã nguồn (khai báo class, thuộc tính, hàm).
C. Nhân viên marketing.
D. Tester kiểm tra giao diện.
*Đáp án: B*

**Câu 158:** Cụm từ 'Mô hình hóa Trạng thái' (State Modeling) mô tả điều gì của một đối tượng?
A. Tốc độ mạng tải đối tượng.
B. Mô tả các trạng thái khác nhau mà một đối tượng có thể trải qua trong suốt vòng đời của nó và cách nó phản ứng lại các sự kiện (Events).
C. Màu sắc của đối tượng trên màn hình.
D. Giá tiền đối tượng.
*Đáp án: B*

**Câu 159:** Trong Sơ đồ Trạng thái (State Diagram), một trạng thái (State) đại diện cho:
A. Một chức năng tính toán.
B. Một điều kiện hoặc hoàn cảnh trong vòng đời của đối tượng, nơi nó thỏa mãn một số điều kiện, thực hiện hành động, hoặc chờ sự kiện.
C. Lỗi cú pháp.
D. Luồng dữ liệu.
*Đáp án: B*

**Câu 160:** Khi mô hình hóa một 'Hệ thống Máy rút tiền ATM', Sơ đồ Trạng thái rất quan trọng để quản lý cái gì?
A. Quản lý số người xếp hàng.
B. Quản lý vòng đời phiên giao dịch (Ví dụ: Chờ thẻ -> Kiểm tra mã PIN -> Đang chọn chức năng -> Trả tiền -> Hoàn thành), tránh lỗi thao tác ngoài ý muốn.
C. Tốc độ mạng nội bộ.
D. Nhiệt độ của máy ATM.
*Đáp án: B*

**Câu 161:** Đâu là điểm khác biệt lớn nhất giữa Sơ đồ Hoạt động (Activity Diagram) và Sơ đồ Trạng thái (State Diagram)?
A. Activity Diagram có nhiều màu sắc hơn.
B. Activity tập trung vào Luồng xử lý công việc (Control flow từ hành động này sang hành động khác). State tập trung vào Sự thay đổi trạng thái của 1 thực thể do các Sự kiện tác động.
C. State Diagram chỉ dùng cho C++.
D. Activity Diagram không có nút kết thúc.
*Đáp án: B*

**Câu 162:** Biểu đồ Tuần tự (Sequence Diagram) là loại biểu đồ tốt nhất để làm gì?
A. Mô tả cơ sở dữ liệu.
B. Khám phá và đặc tả logic tương tác (trình tự gọi hàm, gửi thông điệp theo thời gian) giữa các đối tượng để hoàn thành kịch bản của một Use-case.
C. Mô tả mạng vật lý.
D. Vẽ giao diện HTML.
*Đáp án: B*

**Câu 163:** Trong Biểu đồ Tuần tự, trục ngang (từ trái sang phải) thể hiện điều gì?
A. Thời gian trôi qua.
B. Các Đối tượng (Objects/Actors) tham gia vào sự tương tác.
C. Các biến số.
D. Dung lượng đĩa cứng.
*Đáp án: B*

**Câu 164:** Tại sao trong thiết kế hướng đối tượng, ta nên hạn chế các mối quan hệ Phụ thuộc (Dependency) đan chéo chằng chịt?
A. Làm vẽ biểu đồ bị xấu.
B. Làm tăng độ kết dính (Coupling) của hệ thống, dẫn đến hiện tượng 'Spaghetti code' rất khó bảo trì và dễ sinh lỗi lan truyền khi có thay đổi.
C. Tốn dung lượng ổ đĩa.
D. Làm chương trình chạy quá nhanh.
*Đáp án: B*

**Câu 165:** Mẫu thiết kế (Design Pattern) thường được biểu diễn bằng biểu đồ UML nào?
A. Biểu đồ Use-case.
B. Biểu đồ Lớp (Class Diagram) kết hợp với Biểu đồ Tuần tự (Sequence) để chỉ ra cấu trúc tĩnh và cách các lớp tương tác.
C. Biểu đồ trạng thái.
D. Sơ đồ ngữ cảnh.
*Đáp án: B*

**Câu 166:** Mô hình Dữ liệu logic (Logical Data Model) khác Mô hình vật lý (Physical Data Model) ở điểm nào?
A. Mô hình logic chạy được trên mạng.
B. Mô hình logic bỏ qua chi tiết công nghệ lưu trữ. Mô hình vật lý đặc tả cụ thể kiểu dữ liệu thực tế trên hệ quản trị CSDL cụ thể (VD: VARCHAR(50) trên SQL Server).
C. Mô hình vật lý chỉ vẽ bằng tay.
D. Không khác gì.
*Đáp án: B*

**Câu 167:** Một Lớp Trừu tượng (Abstract Class) khác Lớp Cụ thể (Concrete Class) ở chỗ:
A. Lớp trừu tượng có giao diện đẹp hơn.
B. Lớp trừu tượng không thể khởi tạo trực tiếp thành đối tượng (Instance), nó chỉ đóng vai trò làm khung mẫu cho các lớp con kế thừa.
C. Lớp cụ thể bị lỗi nhiều hơn.
D. Lớp trừu tượng luôn trống rỗng.
*Đáp án: B*

**Câu 168:** Trong UML, 'Package' (Gói) hoạt động giống khái niệm nào nhất trong ngôn ngữ lập trình?
A. Giống một lệnh if-else.
B. Giống như Namespace trong C# / C++ hoặc Package trong Java, dùng để tổ chức mã nguồn, tránh xung đột tên.
C. Giống vòng lặp for.
D. Giống một biến số nguyên.
*Đáp án: B*

**Câu 169:** Việc vẽ Biểu đồ Hoạt động (Activity Diagram) rất phù hợp cho ai trong giai đoạn phân tích?
A. Chuyên viên mạng (Network Admin).
B. Chuyên viên phân tích nghiệp vụ (BA) dùng để mô hình hóa Quy trình kinh doanh (Business Workflow) của khách hàng.
C. Khách hàng xem để giải trí.
D. Người quản lý tài chính.
*Đáp án: B*

**Câu 170:** Đâu là một ví dụ về một 'Sự kiện' (Event) kích hoạt chuyển đổi trạng thái trong State Diagram?
A. Màu sắc của cửa sổ Windows.
B. Người dùng nhấn nút 'Submit', hoặc Nhiệt độ vượt quá 100 độ C, hoặc Hết thời gian chờ (Timeout).
C. Độ phân giải màn hình.
D. Tên của lập trình viên.
*Đáp án: B*

**Câu 171:** Khái niệm 'Stereotype' (Khuôn mẫu) trong UML (vd: <<control>>, <<entity>>, <<boundary>>) dùng để làm gì?
A. Nghe nhạc âm thanh nổi.
B. Mở rộng từ vựng của UML, giúp phân loại và làm rõ chức năng/đặc tính riêng của một thành phần mà không cần tạo ký hiệu mới hoàn toàn.
C. Dùng để xóa dữ liệu.
D. Dùng để vẽ giao diện 3D.
*Đáp án: B*

**Câu 172:** Một Lớp Điều khiển (Control Class) trong mô hình phân tích có nhiệm vụ gì?
A. Lưu trữ dữ liệu xuống đĩa cứng.
B. Điều phối luồng xử lý (Control flow) phức tạp, đóng vai trò kết nối giữa Lớp Giao diện (Boundary) và Lớp Dữ liệu (Entity).
C. Hiển thị nút bấm ra màn hình.
D. Tự động tính lương nhân viên.
*Đáp án: B*

**Câu 173:** Một Lớp Biên (Boundary Class) làm nhiệm vụ gì?
A. Lưu mật khẩu người dùng.
B. Là giao diện để Hệ thống giao tiếp với bên ngoài (Ví dụ: Màn hình người dùng (UI), hoặc API kết nối với hệ thống khác).
C. Thực hiện thuật toán AI.
D. Tính toán thuế.
*Đáp án: B*

**Câu 174:** Tại sao kỹ sư thường vẽ Sơ đồ Ngữ cảnh (Context Diagram) vào lúc bắt đầu dự án?
A. Để kết thúc dự án nhanh.
B. Để xác định và thống nhất ranh giới (Boundary) của hệ thống: Chúng ta sẽ làm cái gì và hệ thống của chúng ta sẽ giao tiếp với những ai bên ngoài.
C. Để vẽ CSDL vật lý.
D. Để tính giá điện.
*Đáp án: B*

**Câu 175:** Trong DFD, một luồng dữ liệu (Data Flow) chỉ truyền đi 'Dữ liệu', nó không được truyền đi cái gì?
A. Không được truyền chữ.
B. Không truyền 'Luồng điều khiển' (Control flags như: Kích hoạt, Dừng, Chờ). Luồng điều khiển thuộc về Sơ đồ điều khiển hoặc Activity Diagram.
C. Không được truyền số.
D. Không được truyền file ảnh.
*Đáp án: B*

**Câu 176:** Sự phụ thuộc vòng (Circular Dependency) giữa các Packages trong UML (Gói A phụ thuộc B, B phụ thuộc C, C lại phụ thuộc A) gây ra vấn đề gì?
A. Giao diện đẹp hơn.
B. Hệ thống bị khóa cứng với nhau, không thể tái sử dụng, test hoặc bảo trì độc lập bất kỳ gói nào trong vòng lặp đó (Khủng hoảng kiến trúc).
C. Chạy nhanh gấp đôi.
D. Không bị sao cả.
*Đáp án: B*

**Câu 177:** Làm sao để phá vỡ Sự phụ thuộc vòng (Circular Dependency)?
A. Xóa mã nguồn đi.
B. Áp dụng nguyên lý 'Đảo ngược phụ thuộc' (Dependency Inversion Principle) thông qua việc sử dụng Interfaces (Giao diện) trung gian.
C. Thay lập trình viên.
D. Cài đặt hệ điều hành khác.
*Đáp án: B*

**Câu 178:** Mô hình Cấu trúc tĩnh (Static Modeling) và Mô hình Hành vi động (Dynamic Modeling) có quan hệ thế nào?
A. Khắc tinh của nhau.
B. Bổ trợ chặt chẽ. Mô hình tĩnh cung cấp bộ khung các Lớp (Class), Mô hình động mô tả cách các Lớp đó tương tác qua thời gian để hoàn thành chức năng.
C. Cả hai là một.
D. Chỉ dùng một cái là đủ.
*Đáp án: B*

**Câu 179:** Trong UML, 'Ghi chú' (Note/Comment) được vẽ bằng hình gì?
A. Hình elip.
B. Hình chữ nhật có góc phải bên trên bị gập xuống, nối với phần tử cần chú thích bằng một đường nét đứt.
C. Hình tròn.
D. Hình ngôi sao.
*Đáp án: B*

**Câu 180:** Mục đích của việc sử dụng 'Làn bơi' (Swimlanes/Partitions) trong Activity Diagram là gì?
A. Làm tăng màu sắc bản vẽ.
B. Chỉ rõ rõ ràng ai (hoặc hệ thống/mô-đun nào) chịu trách nhiệm thực thi một hành động (Action) cụ thể trong một quy trình kinh doanh tổng thể.
C. Giấu đi những lỗi code.
D. Tính giá thành.
*Đáp án: B*

**Câu 181:** Sự kết hợp (Association) giữa hai Lớp được coi là 'Có hướng' (Directed Association) khi nào?
A. Khi nó bị lỗi.
B. Khi có mũi tên ở một đầu, nghĩa là Lớp A biết và gọi Lớp B, nhưng Lớp B hoàn toàn không biết sự tồn tại của Lớp A (giảm Coupling).
C. Khi có đường nét đứt.
D. Khi hai lớp hợp nhất làm 1.
*Đáp án: B*

**Câu 182:** Phương pháp Phân rã (Decomposition) trong thiết kế có mục đích chính là:
A. Làm tăng độ khó.
B. Kiểm soát sự phức tạp bằng cách chia một vấn đề lớn, khó hiểu thành nhiều vấn đề con nhỏ hơn, dễ hiểu và dễ trị (Divide and Conquer).
C. Làm giảm tốc độ phần mềm.
D. Viết ít code hơn.
*Đáp án: B*

**Câu 183:** Mô hình hóa (Modeling) giúp 'Phát hiện sớm lỗi thiết kế' (Early Error Detection). Điều này có ý nghĩa gì về chi phí?
A. Làm chi phí tăng cao.
B. Giúp tiết kiệm lượng lớn tiền bạc và thời gian vì việc sửa 1 lỗi trên giấy/bản vẽ rẻ hơn gấp hàng chục lần so với việc sửa nó khi đã viết xong mã nguồn.
C. Tốn kém giấy in.
D. Không có lợi ích kinh tế.
*Đáp án: B*

**Câu 184:** Tại sao 'Biểu đồ Lớp' lại là bản lề để kết nối các biểu đồ khác trong thiết kế UML?
A. Vì nó dễ vẽ nhất.
B. Vì nó cung cấp từ vựng tĩnh (các Object). Các biểu đồ Sequence, Activity, State đều mượn các Object từ Biểu đồ Lớp để cho chúng 'tương tác' hoặc 'đổi trạng thái'.
C. Vì nó dùng nhiều màu sắc.
D. Vì nó không cần dùng máy tính.
*Đáp án: B*

**Câu 185:** Trong một dự án Agile, sơ đồ UML thường được sử dụng như thế nào?
A. Vẽ hoàn hảo 100% trước khi làm.
B. Thường được vẽ phác thảo (trên bảng trắng - whiteboard sketches) để thảo luận, giải quyết một vấn đề kiến trúc khó, sau đó có thể chụp ảnh lưu lại rồi vào việc code.
C. Bị cấm hoàn toàn.
D. Khách hàng vẽ thay lập trình viên.
*Đáp án: B*

**Câu 186:** Nếu không có mô hình hóa phần mềm, việc bảo trì hệ thống của một lập trình viên mới (Maintainer) sẽ gặp khó khăn gì?
A. Màn hình bị tối đi.
B. Họ phải tự 'dò mìn' đọc hàng vạn dòng code vô cảm, mất rất nhiều thời gian để tưởng tượng lại cấu trúc và rất dễ sửa chỗ này làm hỏng chỗ kia.
C. Chương trình chạy chậm.
D. Ngôn ngữ lập trình bị thay đổi.
*Đáp án: B*

**Câu 187:** Đâu là một 'Khung nhìn Triển khai' (Deployment View) trong mô hình 4+1?
A. Sơ đồ Use-case.
B. Sơ đồ Triển khai (Deployment Diagram) mô tả Topology phần cứng, máy chủ, mạng và cách phân phối các Component phần mềm lên đó.
C. Sơ đồ Lớp.
D. Sơ đồ Trạng thái.
*Đáp án: B*

**Câu 188:** Ký hiệu hình trụ tròn (Cylinder) trong Sơ đồ Triển khai hoặc DFD thường đại diện cho cái gì?
A. Màn hình hiển thị.
B. Cơ sở dữ liệu (Database) hoặc kho lưu trữ dữ liệu (Data store).
C. Đường truyền mạng.
D. Lập trình viên.
*Đáp án: B*

**Câu 189:** Khi có sự mâu thuẫn giữa Mã nguồn thực tế và Biểu đồ Thiết kế, cái nào là 'Sự thật' (Truth) cuối cùng của hệ thống?
A. Biểu đồ Thiết kế.
B. Mã nguồn thực tế đang chạy trên Server, vì tài liệu (Biểu đồ) có thể đã bị lão hóa (out-of-sync) nếu không bảo trì tài liệu tốt.
C. Lời nói của giám đốc.
D. Tài liệu Marketing.
*Đáp án: B*

**Câu 190:** Đâu là lý do chính khiến nhiều công ty bỏ qua bước Mô hình hóa UML?
A. Vì UML đã hết hạn sử dụng.
B. Áp lực tiến độ (deadline), ảo tưởng rằng 'chỉ cần code chạy là xong', hoặc đội ngũ thiếu kỹ năng phân tích thiết kế chuẩn mực.
C. Vì giá công cụ vẽ quá rẻ.
D. Vì không có máy tính.
*Đáp án: B*

**Câu 191:** Khái niệm 'Kỹ thuật viên Phần mềm' (Software Engineer) đòi hỏi sự thay đổi tư duy như thế nào so với một 'Coder' (Thợ gõ code)?
A. Gõ phím bằng 10 ngón nhanh hơn.
B. Sử dụng công cụ thiết kế (Mô hình hóa) để kiến tạo giải pháp tổng thể, bền vững và chất lượng trước khi đi vào việc hiện thực hóa bằng các dòng lệnh.
C. Biết dùng nhiều bàn phím cơ.
D. Thuộc lòng mã lệnh.
*Đáp án: B*

**Câu 192:** Biểu đồ Giao tiếp (Communication Diagram) và Biểu đồ Tuần tự (Sequence Diagram) là hai biểu đồ có thể 'Chuyển đổi qua lại' (Isomorphic) cho nhau. Khác biệt là gì?
A. Không có khác biệt.
B. Sequence tập trung mạnh vào TRỤC THỜI GIAN; Communication tập trung vào CẤU TRÚC LIÊN KẾT (Topology) giữa các đối tượng truyền tin.
C. Chỉ có Sequence mới chạy được code.
D. Communication dùng cho phần cứng.
*Đáp án: B*

**Câu 193:** Sự kết thúc hoàn hảo của chương 'Mô hình hóa phần mềm' là học viên có khả năng gì?
A. Vẽ được hình tròn chuẩn.
B. Biết cách trừu tượng hóa một bài toán thế giới thực thành các biểu đồ thiết kế UML chuẩn mực, tạo nền tảng vững chắc để chuyển giao cho pha Lập trình.
C. Nhớ ngày sinh của người tạo ra UML.
D. Dùng Excel tốt hơn.
*Đáp án: B*

**Câu 194:** Trong Sequence Diagram, khi một đối tượng gửi một thông điệp đi và tự hủy (bị xóa khỏi bộ nhớ), thông điệp đó kết thúc bằng ký hiệu gì ở Lifeline?
A. Chữ A.
B. Chữ X lớn (Hủy đối tượng / Object Destruction).
C. Chữ O.
D. Mũi tên tròn.
*Đáp án: B*

**Câu 195:** Biểu đồ Đối tượng (Object Diagram) có điểm tương đồng nhất với biểu đồ nào?
A. Sơ đồ mạng.
B. Biểu đồ Lớp (Class Diagram), vì nó chính là sự cụ thể hóa (instantiation) của Biểu đồ Lớp tại một thời điểm chạy (runtime).
C. Sơ đồ DFD.
D. Biểu đồ Use-case.
*Đáp án: B*

**Câu 196:** Trong biểu đồ Use-case, việc một Tác nhân (Actor) kế thừa một Tác nhân khác mang ý nghĩa gì?
A. Actor con sẽ bị xóa khỏi hệ thống.
B. Actor con sẽ có tất cả các quyền tương tác (truy cập các Use-case) mà Actor cha có, và có thể tương tác thêm các Use-case của riêng nó.
C. Actor cha sẽ bị mất quyền.
D. Không ai có quyền.
*Đáp án: B*

**Câu 197:** Việc thiết kế Mô hình Lớp tốt (áp dụng các Design Pattern, SOLID) giúp giải quyết vấn đề lớn nhất nào của CNPM?
A. Giảm lượng RAM tiêu thụ.
B. Tính dễ bảo trì (Maintainability) và Tính linh hoạt khi có sự thay đổi yêu cầu đột ngột từ khách hàng (Software Brittleness).
C. Giảm tiền mua màn hình.
D. Tăng tốc độ mạng LAN.
*Đáp án: B*

**Câu 198:** Biểu đồ Hoạt động (Activity Diagram) có thể được vẽ riêng cho một Use-case không?
A. Tuyệt đối không.
B. Rất phổ biến. Người ta dùng Activity Diagram để minh họa lại một cách trực quan các bước xử lý (Basic và Exception flows) đã viết dạng văn bản trong đặc tả Use-case đó.
C. Chỉ dùng cho cơ sở dữ liệu.
D. Phải vẽ chung cho toàn bộ hệ thống.
*Đáp án: B*

**Câu 199:** Đặc trưng của Biểu đồ Thành phần (Component Diagram) là gì?
A. Liệt kê tên nhân viên.
B. Sử dụng các Interface (Cổng giao tiếp) dạng Lollipops/Sockets để biểu diễn cách một Component cung cấp dịch vụ và Component khác tiêu thụ dịch vụ đó.
C. Vẽ đường đi của dữ liệu.
D. Hiển thị thời gian trôi qua.
*Đáp án: B*

**Câu 200:** Theo quan điểm của CNPM, việc bỏ qua Mô hình hóa hệ thống tương đương với hành động gì trong đời thực?
A. Xây một tòa nhà chọc trời mà không cần bất kỳ một bản thiết kế kiến trúc nào, cứ xếp gạch đến đâu hay đến đó.
B. Trồng cây không cần tưới nước.
C. Đi xe đạp không cần mũ bảo hiểm.
D. Ăn cơm không cần đũa.
*Đáp án: A*
