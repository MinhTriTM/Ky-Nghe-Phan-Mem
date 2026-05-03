# CHƯƠNG 7: KIỂM THỬ PHẦN MỀM

## PHẦN 1: Câu hỏi tự luận ngắn

1. **Kiểm thử phần mềm (Software Testing) là gì?**
   *Gợi ý:* Là quá trình thực thi một chương trình với mục đích tìm ra lỗi, nhằm đánh giá chất lượng hoặc tính chấp nhận được của sản phẩm.
2. **Mục đích chính của Kiểm thử phần mềm là gì?**
   *Gợi ý:* Phát hiện lỗi (bugs) hoặc bất cứ vấn đề gì về sản phẩm trước khi giao cho khách hàng, đảm bảo phần mềm hoạt động đúng như mong đợi.
3. **Thế nào là "Xác minh" (Verification) trong kiểm thử?**
   *Gợi ý:* Là quá trình kiểm tra xem phần mềm có được xây dựng ĐÚNG CÁCH hay không (Are we building the product right?). Đảm bảo phần mềm tuân thủ các đặc tả thiết kế và kiến trúc.
4. **Thế nào là "Thẩm định" (Validation) trong kiểm thử?**
   *Gợi ý:* Là quá trình kiểm tra xem phần mềm có đúng là SẢN PHẨM KHÁCH HÀNG CẦN hay không (Are we building the right product?). Đảm bảo phần mềm thỏa mãn các yêu cầu thực tế của người dùng.
5. **Rà soát phần mềm (Software Review / Inspection) mang lại lợi ích gì?**
   *Gợi ý:* Giúp phát hiện lỗi sớm ngay từ giai đoạn tài liệu (yêu cầu, thiết kế) hoặc mã nguồn mà không cần phải thực thi chương trình, từ đó giảm chi phí sửa lỗi.
6. **Kiểm thử hộp đen (Black-box testing) là phương pháp như thế nào?**
   *Gợi ý:* Là phương pháp kiểm thử dựa trên yêu cầu chức năng của phần mềm mà KHÔNG cần biết cấu trúc mã nguồn bên trong. Người kiểm thử chỉ quan tâm đến đầu vào (Input) và đầu ra (Output).
7. **Kiểm thử hộp trắng (White-box testing) tập trung vào khía cạnh nào của phần mềm?**
   *Gợi ý:* Tập trung vào cấu trúc logic, luồng điều khiển, các nhánh và thuật toán CỦA mã nguồn BÊN TRONG. Người kiểm thử cần có kiến thức về lập trình.
8. **Ai thường là người thực hiện Kiểm thử hộp trắng?**
   *Gợi ý:* Thường là Lập trình viên (Developer) hoặc Kỹ sư kiểm thử tự động có am hiểu về code.
9. **Kể tên các mức độ kiểm thử (Testing Levels) từ thấp lên cao?**
   *Gợi ý:* Kiểm thử đơn vị (Unit Testing) -> Kiểm thử tích hợp (Integration Testing) -> Kiểm thử hệ thống (System Testing) -> Kiểm thử chấp nhận (Acceptance Testing).
10. **Kiểm thử đơn vị (Unit Testing) thường kiểm tra thành phần nào?**
    *Gợi ý:* Kiểm tra các thành phần nhỏ nhất có thể hoạt động độc lập của phần mềm (ví dụ: một hàm, một lớp) để đảm bảo chúng hoạt động đúng logic.
11. **Mục tiêu của Kiểm thử tích hợp (Integration Testing) là gì?**
    *Gợi ý:* Kiểm tra sự giao tiếp, tương tác và truyền dữ liệu GIỮA CÁC module hoặc thành phần con sau khi chúng được ghép nối với nhau.
12. **Sự khác biệt giữa Kiểm thử hệ thống (System Testing) và Kiểm thử tích hợp là gì?**
    *Gợi ý:* Kiểm thử tích hợp chỉ kiểm tra nhóm module, còn Kiểm thử hệ thống kiểm tra TOÀN BỘ hệ thống phần mềm hoàn chỉnh trong một môi trường giống thực tế để đánh giá sự tuân thủ các yêu cầu.
13. **Kiểm thử chấp nhận (Acceptance Testing) do ai thực hiện và nhằm mục đích gì?**
    *Gợi ý:* Thường do khách hàng hoặc người dùng cuối (End-user) thực hiện để quyết định xem hệ thống có đáp ứng được nhu cầu nghiệp vụ và có thể đưa vào sử dụng thực tế (Go-live) hay không.
14. **Alpha Testing và Beta Testing thuộc giai đoạn kiểm thử nào?**
    *Gợi ý:* Thuộc Kiểm thử chấp nhận (Acceptance Testing). Alpha testing thực hiện tại nội bộ công ty phát triển, còn Beta testing thực hiện bởi một nhóm người dùng giới hạn ở môi trường bên ngoài.
15. **Kiểm thử chức năng (Functional Testing) là gì?**
    *Gợi ý:* Là kiểm tra xem phần mềm có thực hiện đúng các chức năng đã được mô tả trong tài liệu yêu cầu (ví dụ: đăng nhập thành công, tính toán đúng).
16. **Kể tên một số loại Kiểm thử phi chức năng (Non-functional Testing)?**
    *Gợi ý:* Kiểm thử hiệu năng (Performance Testing), Kiểm thử bảo mật (Security Testing), Kiểm thử khả năng chịu tải (Load Testing), Kiểm thử tính khả dụng (Usability Testing).
17. **Kiểm thử hồi quy (Regression Testing) được thực hiện khi nào?**
    *Gợi ý:* Được thực hiện sau khi có sự thay đổi mã nguồn (như sửa lỗi, thêm tính năng mới) nhằm đảm bảo những thay đổi này KHÔNG làm hỏng các chức năng cũ đang hoạt động tốt.
18. **Tại sao "Không thể kiểm thử triệt để" (Exhaustive testing is impossible) lại là một nguyên lý của kiểm thử?**
    *Gợi ý:* Vì số lượng các tổ hợp dữ liệu đầu vào và các đường dẫn logic trong phần mềm là khổng lồ, việc kiểm thử tất cả mọi trường hợp tốn quá nhiều thời gian và chi phí. Cần phải chọn lọc các trường hợp ưu tiên.
19. **Test Case (Kịch bản kiểm thử) bao gồm những thành phần cơ bản nào?**
    *Gợi ý:* ID, Tên kịch bản, Tiền điều kiện, Các bước thực hiện (Steps), Dữ liệu đầu vào (Input), Kết quả mong đợi (Expected Result) và Kết quả thực tế (Actual Result).
20. **Trong kỹ thuật phân vùng tương đương (Equivalence Partitioning), dữ liệu đầu vào được chia như thế nào?**
    *Gợi ý:* Chia miền dữ liệu đầu vào thành các nhóm (vùng) sao cho mọi giá trị trong cùng một nhóm được coi là tương đương nhau về mặt xử lý. Chỉ cần chọn 1-2 giá trị đại diện từ mỗi vùng để kiểm thử.
21. **Kỹ thuật phân tích giá trị biên (Boundary Value Analysis) dựa trên cơ sở nào?**
    *Gợi ý:* Dựa trên quan sát rằng phần lớn lỗi thường xảy ra ở các giá trị ranh giới (biên) của các miền dữ liệu chứ không phải ở giữa miền.
22. **Kiểm thử tự động (Automated Testing) có ưu điểm gì so với kiểm thử thủ công?**
    *Gợi ý:* Nhanh chóng, chính xác, có thể chạy lặp đi lặp lại nhiều lần (đặc biệt phù hợp cho Kiểm thử hồi quy) và tiết kiệm nguồn lực con người trong dài hạn.
23. **Khi nào thì KHÔNG nên áp dụng kiểm thử tự động?**
    *Gợi ý:* Khi giao diện phần mềm thay đổi liên tục, khi kiểm tra tính khả dụng/trải nghiệm người dùng (Usability), hoặc dự án quá nhỏ làm chi phí viết script tự động cao hơn hiệu quả mang lại.
24. **Bug Report (Báo cáo lỗi) hiệu quả cần cung cấp những thông tin gì?**
    *Gợi ý:* Tiêu đề ngắn gọn, các bước tái hiện (Steps to reproduce), kết quả thực tế, kết quả mong đợi, môi trường (OS, Browser), hình ảnh/video đính kèm và mức độ nghiêm trọng (Severity).
25. **Sự khác biệt giữa Error, Defect/Bug và Failure trong quy trình phát triển phần mềm là gì?**
    *Gợi ý:* Error (Lỗi con người tạo ra khi code) -> Defect/Bug (Khuyết tật tồn tại trong mã nguồn/sản phẩm) -> Failure (Sự cố xảy ra khi phần mềm chạy thực tế và không đáp ứng yêu cầu).


## PHẦN 2: Câu hỏi trắc nghiệm

**Câu 1:** Mục tiêu chính của Kiểm thử phần mềm là gì?
A. Chứng minh rằng phần mềm hoàn toàn không có lỗi.
B. Phát hiện ra lỗi và các vấn đề tiềm ẩn để cải thiện chất lượng sản phẩm.
C. Đo lường tốc độ gõ code của lập trình viên.
D. Tạo ra tài liệu hướng dẫn sử dụng tự động.
*Đáp án: B*

**Câu 2:** Hoạt động "Xác minh" (Verification) trong quy trình V&V (Verification and Validation) nhằm trả lời câu hỏi nào?
A. Chúng ta đã làm đúng sản phẩm khách hàng cần chưa?
B. Chúng ta có đang xây dựng sản phẩm đúng quy trình/thiết kế không?
C. Sản phẩm bán được bao nhiêu tiền?
D. Ai là người code chức năng này?
*Đáp án: B*

**Câu 3:** Hoạt động "Thẩm định" (Validation) đánh giá phần mềm dựa trên tiêu chí nào?
A. Sự tuân thủ cú pháp của ngôn ngữ lập trình.
B. Kiến trúc của cơ sở dữ liệu.
C. Mức độ đáp ứng yêu cầu và nhu cầu thực tế của khách hàng.
D. Số lượng dòng code được sinh ra.
*Đáp án: C*

**Câu 4:** Rà soát phần mềm (Software Review) có ưu điểm gì nổi bật?
A. Không cần người tham gia, hoàn toàn do máy tính thực hiện.
B. Có thể phát hiện lỗi ngay trên tài liệu, bản thiết kế trước khi viết code, giúp tiết kiệm chi phí sửa lỗi.
C. Có thể kiểm tra được hiệu năng của phần mềm khi chạy với 10.000 người dùng.
D. Thay thế hoàn toàn được Kiểm thử tự động.
*Đáp án: B*

**Câu 5:** Kiểm thử hộp đen (Black-box testing) tập trung vào yếu tố nào?
A. Cấu trúc các lệnh IF-ELSE bên trong vòng lặp.
B. Các câu lệnh SQL truy vấn cơ sở dữ liệu.
C. Đầu vào (Input) và Đầu ra (Output) để kiểm tra các chức năng của hệ thống.
D. Việc tái cấu trúc mã nguồn (Refactoring).
*Đáp án: C*

**Câu 6:** Phương pháp kiểm thử nào yêu cầu Tester phải có kiến thức về mã nguồn và cấu trúc bên trong của phần mềm?
A. Kiểm thử hộp đen (Black-box testing).
B. Kiểm thử hộp trắng (White-box testing).
C. Kiểm thử chấp nhận (Acceptance testing).
D. Kiểm thử beta (Beta testing).
*Đáp án: B*

**Câu 7:** Mức độ kiểm thử thấp nhất, tập trung vào từng thành phần mã nguồn riêng biệt (ví dụ: một hàm) gọi là gì?
A. Kiểm thử hệ thống (System Testing).
B. Kiểm thử chấp nhận (Acceptance Testing).
C. Kiểm thử tích hợp (Integration Testing).
D. Kiểm thử đơn vị (Unit Testing).
*Đáp án: D*

**Câu 8:** Sau khi các Unit đã được kiểm thử, bước tiếp theo là kiểm tra sự giao tiếp giữa các Unit đó. Đó là mức độ kiểm thử nào?
A. Kiểm thử hộp đen.
B. Kiểm thử tích hợp (Integration Testing).
C. Kiểm thử hồi quy.
D. Kiểm thử bảo mật.
*Đáp án: B*

**Câu 9:** Ai thường là người thực hiện Kiểm thử chấp nhận (Acceptance Testing) trước khi phần mềm được đưa vào sử dụng chính thức?
A. Chuyên gia bảo mật (Security Expert).
B. Quản trị cơ sở dữ liệu (DBA).
C. Khách hàng hoặc người dùng cuối (End-user).
D. Lập trình viên mới vào nghề (Junior Developer).
*Đáp án: C*

**Câu 10:** Kiểm tra xem trang web có bị sập khi có 100.000 người truy cập cùng lúc hay không thuộc loại kiểm thử nào?
A. Kiểm thử chức năng (Functional Testing).
B. Kiểm thử đơn vị (Unit Testing).
C. Kiểm thử phi chức năng - Hiệu năng/Chịu tải (Performance/Load Testing).
D. Kiểm thử giao diện (UI Testing).
*Đáp án: C*

**Câu 11:** Sau khi lập trình viên sửa một bug, Tester kiểm tra lại toàn bộ các chức năng liên quan để đảm bảo việc sửa lỗi không gây ảnh hưởng đến tính năng khác. Đó gọi là gì?
A. Kiểm thử Alpha.
B. Kiểm thử bảo mật.
C. Kiểm thử hồi quy (Regression Testing).
D. Rà soát mã nguồn.
*Đáp án: C*

**Câu 12:** Kỹ thuật Phân vùng tương đương (Equivalence Partitioning) giúp gì cho quá trình kiểm thử?
A. Tăng số lượng test case lên mức tối đa.
B. Giảm số lượng test case bằng cách chọn các giá trị đại diện cho từng vùng dữ liệu có tính chất giống nhau.
C. Loại bỏ hoàn toàn sự tham gia của con người.
D. Đảm bảo phần mềm không có lỗi bảo mật.
*Đáp án: B*

**Câu 13:** Kỹ thuật Phân tích giá trị biên (Boundary Value Analysis) dựa trên nguyên lý nào?
A. Lỗi hiếm khi xảy ra ở giữa miền dữ liệu mà thường xuất hiện ở các ranh giới của miền đó.
B. Mọi giá trị dữ liệu đều có xác suất gây lỗi như nhau.
C. Chỉ cần test với giá trị 0 và giá trị rỗng (NULL) là đủ.
D. Lỗi chỉ xuất hiện khi người dùng nhập chữ cái thay vì số.
*Đáp án: A*

**Câu 14:** Một Bug Report (Báo cáo lỗi) hiệu quả KHÔNG cần thiết phải có thông tin nào dưới đây?
A. Các bước để tái hiện lại lỗi (Steps to reproduce).
B. Kết quả mong đợi (Expected Result) và kết quả thực tế (Actual Result).
C. Mức lương của lập trình viên đã gây ra lỗi.
D. Môi trường xảy ra lỗi (Hệ điều hành, Trình duyệt...).
*Đáp án: C*

**Câu 15:** Mục tiêu chính của Kiểm thử phần mềm là gì?
A. Chứng minh rằng phần mềm hoàn toàn không có lỗi.
B. Phát hiện ra lỗi và các vấn đề tiềm ẩn để cải thiện chất lượng sản phẩm.
C. Đo lường tốc độ gõ code của lập trình viên.
D. Tạo ra tài liệu hướng dẫn sử dụng tự động.
*Đáp án: B*

**Câu 16:** Hoạt động "Xác minh" (Verification) trong quy trình V&V (Verification and Validation) nhằm trả lời câu hỏi nào?
A. Chúng ta đã làm đúng sản phẩm khách hàng cần chưa?
B. Chúng ta có đang xây dựng sản phẩm đúng quy trình/thiết kế không?
C. Sản phẩm bán được bao nhiêu tiền?
D. Ai là người code chức năng này?
*Đáp án: B*

**Câu 17:** Hoạt động "Thẩm định" (Validation) đánh giá phần mềm dựa trên tiêu chí nào?
A. Sự tuân thủ cú pháp của ngôn ngữ lập trình.
B. Kiến trúc của cơ sở dữ liệu.
C. Mức độ đáp ứng yêu cầu và nhu cầu thực tế của khách hàng.
D. Số lượng dòng code được sinh ra.
*Đáp án: C*

**Câu 18:** Rà soát phần mềm (Software Review) có ưu điểm gì nổi bật?
A. Không cần người tham gia, hoàn toàn do máy tính thực hiện.
B. Có thể phát hiện lỗi ngay trên tài liệu, bản thiết kế trước khi viết code, giúp tiết kiệm chi phí sửa lỗi.
C. Có thể kiểm tra được hiệu năng của phần mềm khi chạy với 10.000 người dùng.
D. Thay thế hoàn toàn được Kiểm thử tự động.
*Đáp án: B*

**Câu 19:** Kiểm thử hộp đen (Black-box testing) tập trung vào yếu tố nào?
A. Cấu trúc các lệnh IF-ELSE bên trong vòng lặp.
B. Các câu lệnh SQL truy vấn cơ sở dữ liệu.
C. Đầu vào (Input) và Đầu ra (Output) để kiểm tra các chức năng của hệ thống.
D. Việc tái cấu trúc mã nguồn (Refactoring).
*Đáp án: C*

**Câu 20:** Phương pháp kiểm thử nào yêu cầu Tester phải có kiến thức về mã nguồn và cấu trúc bên trong của phần mềm?
A. Kiểm thử hộp đen (Black-box testing).
B. Kiểm thử hộp trắng (White-box testing).
C. Kiểm thử chấp nhận (Acceptance testing).
D. Kiểm thử beta (Beta testing).
*Đáp án: B*

**Câu 21:** Mức độ kiểm thử thấp nhất, tập trung vào từng thành phần mã nguồn riêng biệt (ví dụ: một hàm) gọi là gì?
A. Kiểm thử hệ thống (System Testing).
B. Kiểm thử chấp nhận (Acceptance Testing).
C. Kiểm thử tích hợp (Integration Testing).
D. Kiểm thử đơn vị (Unit Testing).
*Đáp án: D*

**Câu 22:** Sau khi các Unit đã được kiểm thử, bước tiếp theo là kiểm tra sự giao tiếp giữa các Unit đó. Đó là mức độ kiểm thử nào?
A. Kiểm thử hộp đen.
B. Kiểm thử tích hợp (Integration Testing).
C. Kiểm thử hồi quy.
D. Kiểm thử bảo mật.
*Đáp án: B*

**Câu 23:** Ai thường là người thực hiện Kiểm thử chấp nhận (Acceptance Testing) trước khi phần mềm được đưa vào sử dụng chính thức?
A. Chuyên gia bảo mật (Security Expert).
B. Quản trị cơ sở dữ liệu (DBA).
C. Khách hàng hoặc người dùng cuối (End-user).
D. Lập trình viên mới vào nghề (Junior Developer).
*Đáp án: C*

**Câu 24:** Kiểm tra xem trang web có bị sập khi có 100.000 người truy cập cùng lúc hay không thuộc loại kiểm thử nào?
A. Kiểm thử chức năng (Functional Testing).
B. Kiểm thử đơn vị (Unit Testing).
C. Kiểm thử phi chức năng - Hiệu năng/Chịu tải (Performance/Load Testing).
D. Kiểm thử giao diện (UI Testing).
*Đáp án: C*

**Câu 25:** Sau khi lập trình viên sửa một bug, Tester kiểm tra lại toàn bộ các chức năng liên quan để đảm bảo việc sửa lỗi không gây ảnh hưởng đến tính năng khác. Đó gọi là gì?
A. Kiểm thử Alpha.
B. Kiểm thử bảo mật.
C. Kiểm thử hồi quy (Regression Testing).
D. Rà soát mã nguồn.
*Đáp án: C*

**Câu 26:** Kỹ thuật Phân vùng tương đương (Equivalence Partitioning) giúp gì cho quá trình kiểm thử?
A. Tăng số lượng test case lên mức tối đa.
B. Giảm số lượng test case bằng cách chọn các giá trị đại diện cho từng vùng dữ liệu có tính chất giống nhau.
C. Loại bỏ hoàn toàn sự tham gia của con người.
D. Đảm bảo phần mềm không có lỗi bảo mật.
*Đáp án: B*

**Câu 27:** Kỹ thuật Phân tích giá trị biên (Boundary Value Analysis) dựa trên nguyên lý nào?
A. Lỗi hiếm khi xảy ra ở giữa miền dữ liệu mà thường xuất hiện ở các ranh giới của miền đó.
B. Mọi giá trị dữ liệu đều có xác suất gây lỗi như nhau.
C. Chỉ cần test với giá trị 0 và giá trị rỗng (NULL) là đủ.
D. Lỗi chỉ xuất hiện khi người dùng nhập chữ cái thay vì số.
*Đáp án: A*

**Câu 28:** Một Bug Report (Báo cáo lỗi) hiệu quả KHÔNG cần thiết phải có thông tin nào dưới đây?
A. Các bước để tái hiện lại lỗi (Steps to reproduce).
B. Kết quả mong đợi (Expected Result) và kết quả thực tế (Actual Result).
C. Mức lương của lập trình viên đã gây ra lỗi.
D. Môi trường xảy ra lỗi (Hệ điều hành, Trình duyệt...).
*Đáp án: C*

**Câu 29:** Mục tiêu chính của Kiểm thử phần mềm là gì?
A. Chứng minh rằng phần mềm hoàn toàn không có lỗi.
B. Phát hiện ra lỗi và các vấn đề tiềm ẩn để cải thiện chất lượng sản phẩm.
C. Đo lường tốc độ gõ code của lập trình viên.
D. Tạo ra tài liệu hướng dẫn sử dụng tự động.
*Đáp án: B*

**Câu 30:** Hoạt động "Xác minh" (Verification) trong quy trình V&V (Verification and Validation) nhằm trả lời câu hỏi nào?
A. Chúng ta đã làm đúng sản phẩm khách hàng cần chưa?
B. Chúng ta có đang xây dựng sản phẩm đúng quy trình/thiết kế không?
C. Sản phẩm bán được bao nhiêu tiền?
D. Ai là người code chức năng này?
*Đáp án: B*

**Câu 31:** Hoạt động "Thẩm định" (Validation) đánh giá phần mềm dựa trên tiêu chí nào?
A. Sự tuân thủ cú pháp của ngôn ngữ lập trình.
B. Kiến trúc của cơ sở dữ liệu.
C. Mức độ đáp ứng yêu cầu và nhu cầu thực tế của khách hàng.
D. Số lượng dòng code được sinh ra.
*Đáp án: C*

**Câu 32:** Rà soát phần mềm (Software Review) có ưu điểm gì nổi bật?
A. Không cần người tham gia, hoàn toàn do máy tính thực hiện.
B. Có thể phát hiện lỗi ngay trên tài liệu, bản thiết kế trước khi viết code, giúp tiết kiệm chi phí sửa lỗi.
C. Có thể kiểm tra được hiệu năng của phần mềm khi chạy với 10.000 người dùng.
D. Thay thế hoàn toàn được Kiểm thử tự động.
*Đáp án: B*

**Câu 33:** Kiểm thử hộp đen (Black-box testing) tập trung vào yếu tố nào?
A. Cấu trúc các lệnh IF-ELSE bên trong vòng lặp.
B. Các câu lệnh SQL truy vấn cơ sở dữ liệu.
C. Đầu vào (Input) và Đầu ra (Output) để kiểm tra các chức năng của hệ thống.
D. Việc tái cấu trúc mã nguồn (Refactoring).
*Đáp án: C*

**Câu 34:** Phương pháp kiểm thử nào yêu cầu Tester phải có kiến thức về mã nguồn và cấu trúc bên trong của phần mềm?
A. Kiểm thử hộp đen (Black-box testing).
B. Kiểm thử hộp trắng (White-box testing).
C. Kiểm thử chấp nhận (Acceptance testing).
D. Kiểm thử beta (Beta testing).
*Đáp án: B*

**Câu 35:** Mức độ kiểm thử thấp nhất, tập trung vào từng thành phần mã nguồn riêng biệt (ví dụ: một hàm) gọi là gì?
A. Kiểm thử hệ thống (System Testing).
B. Kiểm thử chấp nhận (Acceptance Testing).
C. Kiểm thử tích hợp (Integration Testing).
D. Kiểm thử đơn vị (Unit Testing).
*Đáp án: D*

**Câu 36:** Sau khi các Unit đã được kiểm thử, bước tiếp theo là kiểm tra sự giao tiếp giữa các Unit đó. Đó là mức độ kiểm thử nào?
A. Kiểm thử hộp đen.
B. Kiểm thử tích hợp (Integration Testing).
C. Kiểm thử hồi quy.
D. Kiểm thử bảo mật.
*Đáp án: B*

**Câu 37:** Ai thường là người thực hiện Kiểm thử chấp nhận (Acceptance Testing) trước khi phần mềm được đưa vào sử dụng chính thức?
A. Chuyên gia bảo mật (Security Expert).
B. Quản trị cơ sở dữ liệu (DBA).
C. Khách hàng hoặc người dùng cuối (End-user).
D. Lập trình viên mới vào nghề (Junior Developer).
*Đáp án: C*

**Câu 38:** Kiểm tra xem trang web có bị sập khi có 100.000 người truy cập cùng lúc hay không thuộc loại kiểm thử nào?
A. Kiểm thử chức năng (Functional Testing).
B. Kiểm thử đơn vị (Unit Testing).
C. Kiểm thử phi chức năng - Hiệu năng/Chịu tải (Performance/Load Testing).
D. Kiểm thử giao diện (UI Testing).
*Đáp án: C*

**Câu 39:** Sau khi lập trình viên sửa một bug, Tester kiểm tra lại toàn bộ các chức năng liên quan để đảm bảo việc sửa lỗi không gây ảnh hưởng đến tính năng khác. Đó gọi là gì?
A. Kiểm thử Alpha.
B. Kiểm thử bảo mật.
C. Kiểm thử hồi quy (Regression Testing).
D. Rà soát mã nguồn.
*Đáp án: C*

**Câu 40:** Kỹ thuật Phân vùng tương đương (Equivalence Partitioning) giúp gì cho quá trình kiểm thử?
A. Tăng số lượng test case lên mức tối đa.
B. Giảm số lượng test case bằng cách chọn các giá trị đại diện cho từng vùng dữ liệu có tính chất giống nhau.
C. Loại bỏ hoàn toàn sự tham gia của con người.
D. Đảm bảo phần mềm không có lỗi bảo mật.
*Đáp án: B*

**Câu 41:** Kỹ thuật Phân tích giá trị biên (Boundary Value Analysis) dựa trên nguyên lý nào?
A. Lỗi hiếm khi xảy ra ở giữa miền dữ liệu mà thường xuất hiện ở các ranh giới của miền đó.
B. Mọi giá trị dữ liệu đều có xác suất gây lỗi như nhau.
C. Chỉ cần test với giá trị 0 và giá trị rỗng (NULL) là đủ.
D. Lỗi chỉ xuất hiện khi người dùng nhập chữ cái thay vì số.
*Đáp án: A*

**Câu 42:** Một Bug Report (Báo cáo lỗi) hiệu quả KHÔNG cần thiết phải có thông tin nào dưới đây?
A. Các bước để tái hiện lại lỗi (Steps to reproduce).
B. Kết quả mong đợi (Expected Result) và kết quả thực tế (Actual Result).
C. Mức lương của lập trình viên đã gây ra lỗi.
D. Môi trường xảy ra lỗi (Hệ điều hành, Trình duyệt...).
*Đáp án: C*

**Câu 43:** Mục tiêu chính của Kiểm thử phần mềm là gì?
A. Chứng minh rằng phần mềm hoàn toàn không có lỗi.
B. Phát hiện ra lỗi và các vấn đề tiềm ẩn để cải thiện chất lượng sản phẩm.
C. Đo lường tốc độ gõ code của lập trình viên.
D. Tạo ra tài liệu hướng dẫn sử dụng tự động.
*Đáp án: B*

**Câu 44:** Hoạt động "Xác minh" (Verification) trong quy trình V&V (Verification and Validation) nhằm trả lời câu hỏi nào?
A. Chúng ta đã làm đúng sản phẩm khách hàng cần chưa?
B. Chúng ta có đang xây dựng sản phẩm đúng quy trình/thiết kế không?
C. Sản phẩm bán được bao nhiêu tiền?
D. Ai là người code chức năng này?
*Đáp án: B*

**Câu 45:** Hoạt động "Thẩm định" (Validation) đánh giá phần mềm dựa trên tiêu chí nào?
A. Sự tuân thủ cú pháp của ngôn ngữ lập trình.
B. Kiến trúc của cơ sở dữ liệu.
C. Mức độ đáp ứng yêu cầu và nhu cầu thực tế của khách hàng.
D. Số lượng dòng code được sinh ra.
*Đáp án: C*

**Câu 46:** Rà soát phần mềm (Software Review) có ưu điểm gì nổi bật?
A. Không cần người tham gia, hoàn toàn do máy tính thực hiện.
B. Có thể phát hiện lỗi ngay trên tài liệu, bản thiết kế trước khi viết code, giúp tiết kiệm chi phí sửa lỗi.
C. Có thể kiểm tra được hiệu năng của phần mềm khi chạy với 10.000 người dùng.
D. Thay thế hoàn toàn được Kiểm thử tự động.
*Đáp án: B*

**Câu 47:** Kiểm thử hộp đen (Black-box testing) tập trung vào yếu tố nào?
A. Cấu trúc các lệnh IF-ELSE bên trong vòng lặp.
B. Các câu lệnh SQL truy vấn cơ sở dữ liệu.
C. Đầu vào (Input) và Đầu ra (Output) để kiểm tra các chức năng của hệ thống.
D. Việc tái cấu trúc mã nguồn (Refactoring).
*Đáp án: C*

**Câu 48:** Phương pháp kiểm thử nào yêu cầu Tester phải có kiến thức về mã nguồn và cấu trúc bên trong của phần mềm?
A. Kiểm thử hộp đen (Black-box testing).
B. Kiểm thử hộp trắng (White-box testing).
C. Kiểm thử chấp nhận (Acceptance testing).
D. Kiểm thử beta (Beta testing).
*Đáp án: B*

**Câu 49:** Mức độ kiểm thử thấp nhất, tập trung vào từng thành phần mã nguồn riêng biệt (ví dụ: một hàm) gọi là gì?
A. Kiểm thử hệ thống (System Testing).
B. Kiểm thử chấp nhận (Acceptance Testing).
C. Kiểm thử tích hợp (Integration Testing).
D. Kiểm thử đơn vị (Unit Testing).
*Đáp án: D*

**Câu 50:** Sau khi các Unit đã được kiểm thử, bước tiếp theo là kiểm tra sự giao tiếp giữa các Unit đó. Đó là mức độ kiểm thử nào?
A. Kiểm thử hộp đen.
B. Kiểm thử tích hợp (Integration Testing).
C. Kiểm thử hồi quy.
D. Kiểm thử bảo mật.
*Đáp án: B*

**Câu 51:** Ai thường là người thực hiện Kiểm thử chấp nhận (Acceptance Testing) trước khi phần mềm được đưa vào sử dụng chính thức?
A. Chuyên gia bảo mật (Security Expert).
B. Quản trị cơ sở dữ liệu (DBA).
C. Khách hàng hoặc người dùng cuối (End-user).
D. Lập trình viên mới vào nghề (Junior Developer).
*Đáp án: C*

**Câu 52:** Kiểm tra xem trang web có bị sập khi có 100.000 người truy cập cùng lúc hay không thuộc loại kiểm thử nào?
A. Kiểm thử chức năng (Functional Testing).
B. Kiểm thử đơn vị (Unit Testing).
C. Kiểm thử phi chức năng - Hiệu năng/Chịu tải (Performance/Load Testing).
D. Kiểm thử giao diện (UI Testing).
*Đáp án: C*

**Câu 53:** Sau khi lập trình viên sửa một bug, Tester kiểm tra lại toàn bộ các chức năng liên quan để đảm bảo việc sửa lỗi không gây ảnh hưởng đến tính năng khác. Đó gọi là gì?
A. Kiểm thử Alpha.
B. Kiểm thử bảo mật.
C. Kiểm thử hồi quy (Regression Testing).
D. Rà soát mã nguồn.
*Đáp án: C*

**Câu 54:** Kỹ thuật Phân vùng tương đương (Equivalence Partitioning) giúp gì cho quá trình kiểm thử?
A. Tăng số lượng test case lên mức tối đa.
B. Giảm số lượng test case bằng cách chọn các giá trị đại diện cho từng vùng dữ liệu có tính chất giống nhau.
C. Loại bỏ hoàn toàn sự tham gia của con người.
D. Đảm bảo phần mềm không có lỗi bảo mật.
*Đáp án: B*

**Câu 55:** Kỹ thuật Phân tích giá trị biên (Boundary Value Analysis) dựa trên nguyên lý nào?
A. Lỗi hiếm khi xảy ra ở giữa miền dữ liệu mà thường xuất hiện ở các ranh giới của miền đó.
B. Mọi giá trị dữ liệu đều có xác suất gây lỗi như nhau.
C. Chỉ cần test với giá trị 0 và giá trị rỗng (NULL) là đủ.
D. Lỗi chỉ xuất hiện khi người dùng nhập chữ cái thay vì số.
*Đáp án: A*

**Câu 56:** Một Bug Report (Báo cáo lỗi) hiệu quả KHÔNG cần thiết phải có thông tin nào dưới đây?
A. Các bước để tái hiện lại lỗi (Steps to reproduce).
B. Kết quả mong đợi (Expected Result) và kết quả thực tế (Actual Result).
C. Mức lương của lập trình viên đã gây ra lỗi.
D. Môi trường xảy ra lỗi (Hệ điều hành, Trình duyệt...).
*Đáp án: C*

**Câu 57:** Mục tiêu chính của Kiểm thử phần mềm là gì?
A. Chứng minh rằng phần mềm hoàn toàn không có lỗi.
B. Phát hiện ra lỗi và các vấn đề tiềm ẩn để cải thiện chất lượng sản phẩm.
C. Đo lường tốc độ gõ code của lập trình viên.
D. Tạo ra tài liệu hướng dẫn sử dụng tự động.
*Đáp án: B*

**Câu 58:** Hoạt động "Xác minh" (Verification) trong quy trình V&V (Verification and Validation) nhằm trả lời câu hỏi nào?
A. Chúng ta đã làm đúng sản phẩm khách hàng cần chưa?
B. Chúng ta có đang xây dựng sản phẩm đúng quy trình/thiết kế không?
C. Sản phẩm bán được bao nhiêu tiền?
D. Ai là người code chức năng này?
*Đáp án: B*

**Câu 59:** Hoạt động "Thẩm định" (Validation) đánh giá phần mềm dựa trên tiêu chí nào?
A. Sự tuân thủ cú pháp của ngôn ngữ lập trình.
B. Kiến trúc của cơ sở dữ liệu.
C. Mức độ đáp ứng yêu cầu và nhu cầu thực tế của khách hàng.
D. Số lượng dòng code được sinh ra.
*Đáp án: C*

**Câu 60:** Rà soát phần mềm (Software Review) có ưu điểm gì nổi bật?
A. Không cần người tham gia, hoàn toàn do máy tính thực hiện.
B. Có thể phát hiện lỗi ngay trên tài liệu, bản thiết kế trước khi viết code, giúp tiết kiệm chi phí sửa lỗi.
C. Có thể kiểm tra được hiệu năng của phần mềm khi chạy với 10.000 người dùng.
D. Thay thế hoàn toàn được Kiểm thử tự động.
*Đáp án: B*

**Câu 61:** Kiểm thử hộp đen (Black-box testing) tập trung vào yếu tố nào?
A. Cấu trúc các lệnh IF-ELSE bên trong vòng lặp.
B. Các câu lệnh SQL truy vấn cơ sở dữ liệu.
C. Đầu vào (Input) và Đầu ra (Output) để kiểm tra các chức năng của hệ thống.
D. Việc tái cấu trúc mã nguồn (Refactoring).
*Đáp án: C*

**Câu 62:** Phương pháp kiểm thử nào yêu cầu Tester phải có kiến thức về mã nguồn và cấu trúc bên trong của phần mềm?
A. Kiểm thử hộp đen (Black-box testing).
B. Kiểm thử hộp trắng (White-box testing).
C. Kiểm thử chấp nhận (Acceptance testing).
D. Kiểm thử beta (Beta testing).
*Đáp án: B*

**Câu 63:** Mức độ kiểm thử thấp nhất, tập trung vào từng thành phần mã nguồn riêng biệt (ví dụ: một hàm) gọi là gì?
A. Kiểm thử hệ thống (System Testing).
B. Kiểm thử chấp nhận (Acceptance Testing).
C. Kiểm thử tích hợp (Integration Testing).
D. Kiểm thử đơn vị (Unit Testing).
*Đáp án: D*

**Câu 64:** Sau khi các Unit đã được kiểm thử, bước tiếp theo là kiểm tra sự giao tiếp giữa các Unit đó. Đó là mức độ kiểm thử nào?
A. Kiểm thử hộp đen.
B. Kiểm thử tích hợp (Integration Testing).
C. Kiểm thử hồi quy.
D. Kiểm thử bảo mật.
*Đáp án: B*

**Câu 65:** Ai thường là người thực hiện Kiểm thử chấp nhận (Acceptance Testing) trước khi phần mềm được đưa vào sử dụng chính thức?
A. Chuyên gia bảo mật (Security Expert).
B. Quản trị cơ sở dữ liệu (DBA).
C. Khách hàng hoặc người dùng cuối (End-user).
D. Lập trình viên mới vào nghề (Junior Developer).
*Đáp án: C*

**Câu 66:** Kiểm tra xem trang web có bị sập khi có 100.000 người truy cập cùng lúc hay không thuộc loại kiểm thử nào?
A. Kiểm thử chức năng (Functional Testing).
B. Kiểm thử đơn vị (Unit Testing).
C. Kiểm thử phi chức năng - Hiệu năng/Chịu tải (Performance/Load Testing).
D. Kiểm thử giao diện (UI Testing).
*Đáp án: C*

**Câu 67:** Sau khi lập trình viên sửa một bug, Tester kiểm tra lại toàn bộ các chức năng liên quan để đảm bảo việc sửa lỗi không gây ảnh hưởng đến tính năng khác. Đó gọi là gì?
A. Kiểm thử Alpha.
B. Kiểm thử bảo mật.
C. Kiểm thử hồi quy (Regression Testing).
D. Rà soát mã nguồn.
*Đáp án: C*

**Câu 68:** Kỹ thuật Phân vùng tương đương (Equivalence Partitioning) giúp gì cho quá trình kiểm thử?
A. Tăng số lượng test case lên mức tối đa.
B. Giảm số lượng test case bằng cách chọn các giá trị đại diện cho từng vùng dữ liệu có tính chất giống nhau.
C. Loại bỏ hoàn toàn sự tham gia của con người.
D. Đảm bảo phần mềm không có lỗi bảo mật.
*Đáp án: B*

**Câu 69:** Kỹ thuật Phân tích giá trị biên (Boundary Value Analysis) dựa trên nguyên lý nào?
A. Lỗi hiếm khi xảy ra ở giữa miền dữ liệu mà thường xuất hiện ở các ranh giới của miền đó.
B. Mọi giá trị dữ liệu đều có xác suất gây lỗi như nhau.
C. Chỉ cần test với giá trị 0 và giá trị rỗng (NULL) là đủ.
D. Lỗi chỉ xuất hiện khi người dùng nhập chữ cái thay vì số.
*Đáp án: A*

**Câu 70:** Một Bug Report (Báo cáo lỗi) hiệu quả KHÔNG cần thiết phải có thông tin nào dưới đây?
A. Các bước để tái hiện lại lỗi (Steps to reproduce).
B. Kết quả mong đợi (Expected Result) và kết quả thực tế (Actual Result).
C. Mức lương của lập trình viên đã gây ra lỗi.
D. Môi trường xảy ra lỗi (Hệ điều hành, Trình duyệt...).
*Đáp án: C*

**Câu 71:** Mục tiêu chính của Kiểm thử phần mềm là gì?
A. Chứng minh rằng phần mềm hoàn toàn không có lỗi.
B. Phát hiện ra lỗi và các vấn đề tiềm ẩn để cải thiện chất lượng sản phẩm.
C. Đo lường tốc độ gõ code của lập trình viên.
D. Tạo ra tài liệu hướng dẫn sử dụng tự động.
*Đáp án: B*

**Câu 72:** Hoạt động "Xác minh" (Verification) trong quy trình V&V (Verification and Validation) nhằm trả lời câu hỏi nào?
A. Chúng ta đã làm đúng sản phẩm khách hàng cần chưa?
B. Chúng ta có đang xây dựng sản phẩm đúng quy trình/thiết kế không?
C. Sản phẩm bán được bao nhiêu tiền?
D. Ai là người code chức năng này?
*Đáp án: B*

**Câu 73:** Hoạt động "Thẩm định" (Validation) đánh giá phần mềm dựa trên tiêu chí nào?
A. Sự tuân thủ cú pháp của ngôn ngữ lập trình.
B. Kiến trúc của cơ sở dữ liệu.
C. Mức độ đáp ứng yêu cầu và nhu cầu thực tế của khách hàng.
D. Số lượng dòng code được sinh ra.
*Đáp án: C*

**Câu 74:** Rà soát phần mềm (Software Review) có ưu điểm gì nổi bật?
A. Không cần người tham gia, hoàn toàn do máy tính thực hiện.
B. Có thể phát hiện lỗi ngay trên tài liệu, bản thiết kế trước khi viết code, giúp tiết kiệm chi phí sửa lỗi.
C. Có thể kiểm tra được hiệu năng của phần mềm khi chạy với 10.000 người dùng.
D. Thay thế hoàn toàn được Kiểm thử tự động.
*Đáp án: B*

**Câu 75:** Kiểm thử hộp đen (Black-box testing) tập trung vào yếu tố nào?
A. Cấu trúc các lệnh IF-ELSE bên trong vòng lặp.
B. Các câu lệnh SQL truy vấn cơ sở dữ liệu.
C. Đầu vào (Input) và Đầu ra (Output) để kiểm tra các chức năng của hệ thống.
D. Việc tái cấu trúc mã nguồn (Refactoring).
*Đáp án: C*

**Câu 76:** Phương pháp kiểm thử nào yêu cầu Tester phải có kiến thức về mã nguồn và cấu trúc bên trong của phần mềm?
A. Kiểm thử hộp đen (Black-box testing).
B. Kiểm thử hộp trắng (White-box testing).
C. Kiểm thử chấp nhận (Acceptance testing).
D. Kiểm thử beta (Beta testing).
*Đáp án: B*

**Câu 77:** Mức độ kiểm thử thấp nhất, tập trung vào từng thành phần mã nguồn riêng biệt (ví dụ: một hàm) gọi là gì?
A. Kiểm thử hệ thống (System Testing).
B. Kiểm thử chấp nhận (Acceptance Testing).
C. Kiểm thử tích hợp (Integration Testing).
D. Kiểm thử đơn vị (Unit Testing).
*Đáp án: D*

**Câu 78:** Sau khi các Unit đã được kiểm thử, bước tiếp theo là kiểm tra sự giao tiếp giữa các Unit đó. Đó là mức độ kiểm thử nào?
A. Kiểm thử hộp đen.
B. Kiểm thử tích hợp (Integration Testing).
C. Kiểm thử hồi quy.
D. Kiểm thử bảo mật.
*Đáp án: B*

**Câu 79:** Ai thường là người thực hiện Kiểm thử chấp nhận (Acceptance Testing) trước khi phần mềm được đưa vào sử dụng chính thức?
A. Chuyên gia bảo mật (Security Expert).
B. Quản trị cơ sở dữ liệu (DBA).
C. Khách hàng hoặc người dùng cuối (End-user).
D. Lập trình viên mới vào nghề (Junior Developer).
*Đáp án: C*

**Câu 80:** Kiểm tra xem trang web có bị sập khi có 100.000 người truy cập cùng lúc hay không thuộc loại kiểm thử nào?
A. Kiểm thử chức năng (Functional Testing).
B. Kiểm thử đơn vị (Unit Testing).
C. Kiểm thử phi chức năng - Hiệu năng/Chịu tải (Performance/Load Testing).
D. Kiểm thử giao diện (UI Testing).
*Đáp án: C*

**Câu 81:** Sau khi lập trình viên sửa một bug, Tester kiểm tra lại toàn bộ các chức năng liên quan để đảm bảo việc sửa lỗi không gây ảnh hưởng đến tính năng khác. Đó gọi là gì?
A. Kiểm thử Alpha.
B. Kiểm thử bảo mật.
C. Kiểm thử hồi quy (Regression Testing).
D. Rà soát mã nguồn.
*Đáp án: C*

**Câu 82:** Kỹ thuật Phân vùng tương đương (Equivalence Partitioning) giúp gì cho quá trình kiểm thử?
A. Tăng số lượng test case lên mức tối đa.
B. Giảm số lượng test case bằng cách chọn các giá trị đại diện cho từng vùng dữ liệu có tính chất giống nhau.
C. Loại bỏ hoàn toàn sự tham gia của con người.
D. Đảm bảo phần mềm không có lỗi bảo mật.
*Đáp án: B*

**Câu 83:** Kỹ thuật Phân tích giá trị biên (Boundary Value Analysis) dựa trên nguyên lý nào?
A. Lỗi hiếm khi xảy ra ở giữa miền dữ liệu mà thường xuất hiện ở các ranh giới của miền đó.
B. Mọi giá trị dữ liệu đều có xác suất gây lỗi như nhau.
C. Chỉ cần test với giá trị 0 và giá trị rỗng (NULL) là đủ.
D. Lỗi chỉ xuất hiện khi người dùng nhập chữ cái thay vì số.
*Đáp án: A*

**Câu 84:** Một Bug Report (Báo cáo lỗi) hiệu quả KHÔNG cần thiết phải có thông tin nào dưới đây?
A. Các bước để tái hiện lại lỗi (Steps to reproduce).
B. Kết quả mong đợi (Expected Result) và kết quả thực tế (Actual Result).
C. Mức lương của lập trình viên đã gây ra lỗi.
D. Môi trường xảy ra lỗi (Hệ điều hành, Trình duyệt...).
*Đáp án: C*

**Câu 85:** Mục tiêu chính của Kiểm thử phần mềm là gì?
A. Chứng minh rằng phần mềm hoàn toàn không có lỗi.
B. Phát hiện ra lỗi và các vấn đề tiềm ẩn để cải thiện chất lượng sản phẩm.
C. Đo lường tốc độ gõ code của lập trình viên.
D. Tạo ra tài liệu hướng dẫn sử dụng tự động.
*Đáp án: B*

**Câu 86:** Hoạt động "Xác minh" (Verification) trong quy trình V&V (Verification and Validation) nhằm trả lời câu hỏi nào?
A. Chúng ta đã làm đúng sản phẩm khách hàng cần chưa?
B. Chúng ta có đang xây dựng sản phẩm đúng quy trình/thiết kế không?
C. Sản phẩm bán được bao nhiêu tiền?
D. Ai là người code chức năng này?
*Đáp án: B*

**Câu 87:** Hoạt động "Thẩm định" (Validation) đánh giá phần mềm dựa trên tiêu chí nào?
A. Sự tuân thủ cú pháp của ngôn ngữ lập trình.
B. Kiến trúc của cơ sở dữ liệu.
C. Mức độ đáp ứng yêu cầu và nhu cầu thực tế của khách hàng.
D. Số lượng dòng code được sinh ra.
*Đáp án: C*

**Câu 88:** Rà soát phần mềm (Software Review) có ưu điểm gì nổi bật?
A. Không cần người tham gia, hoàn toàn do máy tính thực hiện.
B. Có thể phát hiện lỗi ngay trên tài liệu, bản thiết kế trước khi viết code, giúp tiết kiệm chi phí sửa lỗi.
C. Có thể kiểm tra được hiệu năng của phần mềm khi chạy với 10.000 người dùng.
D. Thay thế hoàn toàn được Kiểm thử tự động.
*Đáp án: B*

**Câu 89:** Kiểm thử hộp đen (Black-box testing) tập trung vào yếu tố nào?
A. Cấu trúc các lệnh IF-ELSE bên trong vòng lặp.
B. Các câu lệnh SQL truy vấn cơ sở dữ liệu.
C. Đầu vào (Input) và Đầu ra (Output) để kiểm tra các chức năng của hệ thống.
D. Việc tái cấu trúc mã nguồn (Refactoring).
*Đáp án: C*

**Câu 90:** Phương pháp kiểm thử nào yêu cầu Tester phải có kiến thức về mã nguồn và cấu trúc bên trong của phần mềm?
A. Kiểm thử hộp đen (Black-box testing).
B. Kiểm thử hộp trắng (White-box testing).
C. Kiểm thử chấp nhận (Acceptance testing).
D. Kiểm thử beta (Beta testing).
*Đáp án: B*

**Câu 91:** Mức độ kiểm thử thấp nhất, tập trung vào từng thành phần mã nguồn riêng biệt (ví dụ: một hàm) gọi là gì?
A. Kiểm thử hệ thống (System Testing).
B. Kiểm thử chấp nhận (Acceptance Testing).
C. Kiểm thử tích hợp (Integration Testing).
D. Kiểm thử đơn vị (Unit Testing).
*Đáp án: D*

**Câu 92:** Sau khi các Unit đã được kiểm thử, bước tiếp theo là kiểm tra sự giao tiếp giữa các Unit đó. Đó là mức độ kiểm thử nào?
A. Kiểm thử hộp đen.
B. Kiểm thử tích hợp (Integration Testing).
C. Kiểm thử hồi quy.
D. Kiểm thử bảo mật.
*Đáp án: B*

**Câu 93:** Ai thường là người thực hiện Kiểm thử chấp nhận (Acceptance Testing) trước khi phần mềm được đưa vào sử dụng chính thức?
A. Chuyên gia bảo mật (Security Expert).
B. Quản trị cơ sở dữ liệu (DBA).
C. Khách hàng hoặc người dùng cuối (End-user).
D. Lập trình viên mới vào nghề (Junior Developer).
*Đáp án: C*

**Câu 94:** Kiểm tra xem trang web có bị sập khi có 100.000 người truy cập cùng lúc hay không thuộc loại kiểm thử nào?
A. Kiểm thử chức năng (Functional Testing).
B. Kiểm thử đơn vị (Unit Testing).
C. Kiểm thử phi chức năng - Hiệu năng/Chịu tải (Performance/Load Testing).
D. Kiểm thử giao diện (UI Testing).
*Đáp án: C*

**Câu 95:** Sau khi lập trình viên sửa một bug, Tester kiểm tra lại toàn bộ các chức năng liên quan để đảm bảo việc sửa lỗi không gây ảnh hưởng đến tính năng khác. Đó gọi là gì?
A. Kiểm thử Alpha.
B. Kiểm thử bảo mật.
C. Kiểm thử hồi quy (Regression Testing).
D. Rà soát mã nguồn.
*Đáp án: C*

**Câu 96:** Kỹ thuật Phân vùng tương đương (Equivalence Partitioning) giúp gì cho quá trình kiểm thử?
A. Tăng số lượng test case lên mức tối đa.
B. Giảm số lượng test case bằng cách chọn các giá trị đại diện cho từng vùng dữ liệu có tính chất giống nhau.
C. Loại bỏ hoàn toàn sự tham gia của con người.
D. Đảm bảo phần mềm không có lỗi bảo mật.
*Đáp án: B*

**Câu 97:** Kỹ thuật Phân tích giá trị biên (Boundary Value Analysis) dựa trên nguyên lý nào?
A. Lỗi hiếm khi xảy ra ở giữa miền dữ liệu mà thường xuất hiện ở các ranh giới của miền đó.
B. Mọi giá trị dữ liệu đều có xác suất gây lỗi như nhau.
C. Chỉ cần test với giá trị 0 và giá trị rỗng (NULL) là đủ.
D. Lỗi chỉ xuất hiện khi người dùng nhập chữ cái thay vì số.
*Đáp án: A*

**Câu 98:** Một Bug Report (Báo cáo lỗi) hiệu quả KHÔNG cần thiết phải có thông tin nào dưới đây?
A. Các bước để tái hiện lại lỗi (Steps to reproduce).
B. Kết quả mong đợi (Expected Result) và kết quả thực tế (Actual Result).
C. Mức lương của lập trình viên đã gây ra lỗi.
D. Môi trường xảy ra lỗi (Hệ điều hành, Trình duyệt...).
*Đáp án: C*

**Câu 99:** Mục tiêu chính của Kiểm thử phần mềm là gì?
A. Chứng minh rằng phần mềm hoàn toàn không có lỗi.
B. Phát hiện ra lỗi và các vấn đề tiềm ẩn để cải thiện chất lượng sản phẩm.
C. Đo lường tốc độ gõ code của lập trình viên.
D. Tạo ra tài liệu hướng dẫn sử dụng tự động.
*Đáp án: B*

**Câu 100:** Hoạt động "Xác minh" (Verification) trong quy trình V&V (Verification and Validation) nhằm trả lời câu hỏi nào?
A. Chúng ta đã làm đúng sản phẩm khách hàng cần chưa?
B. Chúng ta có đang xây dựng sản phẩm đúng quy trình/thiết kế không?
C. Sản phẩm bán được bao nhiêu tiền?
D. Ai là người code chức năng này?
*Đáp án: B*

**Câu 101:** Hoạt động "Thẩm định" (Validation) đánh giá phần mềm dựa trên tiêu chí nào?
A. Sự tuân thủ cú pháp của ngôn ngữ lập trình.
B. Kiến trúc của cơ sở dữ liệu.
C. Mức độ đáp ứng yêu cầu và nhu cầu thực tế của khách hàng.
D. Số lượng dòng code được sinh ra.
*Đáp án: C*

**Câu 102:** Rà soát phần mềm (Software Review) có ưu điểm gì nổi bật?
A. Không cần người tham gia, hoàn toàn do máy tính thực hiện.
B. Có thể phát hiện lỗi ngay trên tài liệu, bản thiết kế trước khi viết code, giúp tiết kiệm chi phí sửa lỗi.
C. Có thể kiểm tra được hiệu năng của phần mềm khi chạy với 10.000 người dùng.
D. Thay thế hoàn toàn được Kiểm thử tự động.
*Đáp án: B*

**Câu 103:** Kiểm thử hộp đen (Black-box testing) tập trung vào yếu tố nào?
A. Cấu trúc các lệnh IF-ELSE bên trong vòng lặp.
B. Các câu lệnh SQL truy vấn cơ sở dữ liệu.
C. Đầu vào (Input) và Đầu ra (Output) để kiểm tra các chức năng của hệ thống.
D. Việc tái cấu trúc mã nguồn (Refactoring).
*Đáp án: C*

**Câu 104:** Phương pháp kiểm thử nào yêu cầu Tester phải có kiến thức về mã nguồn và cấu trúc bên trong của phần mềm?
A. Kiểm thử hộp đen (Black-box testing).
B. Kiểm thử hộp trắng (White-box testing).
C. Kiểm thử chấp nhận (Acceptance testing).
D. Kiểm thử beta (Beta testing).
*Đáp án: B*

**Câu 105:** Mức độ kiểm thử thấp nhất, tập trung vào từng thành phần mã nguồn riêng biệt (ví dụ: một hàm) gọi là gì?
A. Kiểm thử hệ thống (System Testing).
B. Kiểm thử chấp nhận (Acceptance Testing).
C. Kiểm thử tích hợp (Integration Testing).
D. Kiểm thử đơn vị (Unit Testing).
*Đáp án: D*

**Câu 106:** Sau khi các Unit đã được kiểm thử, bước tiếp theo là kiểm tra sự giao tiếp giữa các Unit đó. Đó là mức độ kiểm thử nào?
A. Kiểm thử hộp đen.
B. Kiểm thử tích hợp (Integration Testing).
C. Kiểm thử hồi quy.
D. Kiểm thử bảo mật.
*Đáp án: B*

**Câu 107:** Ai thường là người thực hiện Kiểm thử chấp nhận (Acceptance Testing) trước khi phần mềm được đưa vào sử dụng chính thức?
A. Chuyên gia bảo mật (Security Expert).
B. Quản trị cơ sở dữ liệu (DBA).
C. Khách hàng hoặc người dùng cuối (End-user).
D. Lập trình viên mới vào nghề (Junior Developer).
*Đáp án: C*

**Câu 108:** Kiểm tra xem trang web có bị sập khi có 100.000 người truy cập cùng lúc hay không thuộc loại kiểm thử nào?
A. Kiểm thử chức năng (Functional Testing).
B. Kiểm thử đơn vị (Unit Testing).
C. Kiểm thử phi chức năng - Hiệu năng/Chịu tải (Performance/Load Testing).
D. Kiểm thử giao diện (UI Testing).
*Đáp án: C*

**Câu 109:** Sau khi lập trình viên sửa một bug, Tester kiểm tra lại toàn bộ các chức năng liên quan để đảm bảo việc sửa lỗi không gây ảnh hưởng đến tính năng khác. Đó gọi là gì?
A. Kiểm thử Alpha.
B. Kiểm thử bảo mật.
C. Kiểm thử hồi quy (Regression Testing).
D. Rà soát mã nguồn.
*Đáp án: C*

**Câu 110:** Kỹ thuật Phân vùng tương đương (Equivalence Partitioning) giúp gì cho quá trình kiểm thử?
A. Tăng số lượng test case lên mức tối đa.
B. Giảm số lượng test case bằng cách chọn các giá trị đại diện cho từng vùng dữ liệu có tính chất giống nhau.
C. Loại bỏ hoàn toàn sự tham gia của con người.
D. Đảm bảo phần mềm không có lỗi bảo mật.
*Đáp án: B*

**Câu 111:** Kỹ thuật Phân tích giá trị biên (Boundary Value Analysis) dựa trên nguyên lý nào?
A. Lỗi hiếm khi xảy ra ở giữa miền dữ liệu mà thường xuất hiện ở các ranh giới của miền đó.
B. Mọi giá trị dữ liệu đều có xác suất gây lỗi như nhau.
C. Chỉ cần test với giá trị 0 và giá trị rỗng (NULL) là đủ.
D. Lỗi chỉ xuất hiện khi người dùng nhập chữ cái thay vì số.
*Đáp án: A*

**Câu 112:** Một Bug Report (Báo cáo lỗi) hiệu quả KHÔNG cần thiết phải có thông tin nào dưới đây?
A. Các bước để tái hiện lại lỗi (Steps to reproduce).
B. Kết quả mong đợi (Expected Result) và kết quả thực tế (Actual Result).
C. Mức lương của lập trình viên đã gây ra lỗi.
D. Môi trường xảy ra lỗi (Hệ điều hành, Trình duyệt...).
*Đáp án: C*

**Câu 113:** Mục tiêu chính của Kiểm thử phần mềm là gì?
A. Chứng minh rằng phần mềm hoàn toàn không có lỗi.
B. Phát hiện ra lỗi và các vấn đề tiềm ẩn để cải thiện chất lượng sản phẩm.
C. Đo lường tốc độ gõ code của lập trình viên.
D. Tạo ra tài liệu hướng dẫn sử dụng tự động.
*Đáp án: B*

**Câu 114:** Hoạt động "Xác minh" (Verification) trong quy trình V&V (Verification and Validation) nhằm trả lời câu hỏi nào?
A. Chúng ta đã làm đúng sản phẩm khách hàng cần chưa?
B. Chúng ta có đang xây dựng sản phẩm đúng quy trình/thiết kế không?
C. Sản phẩm bán được bao nhiêu tiền?
D. Ai là người code chức năng này?
*Đáp án: B*

**Câu 115:** Hoạt động "Thẩm định" (Validation) đánh giá phần mềm dựa trên tiêu chí nào?
A. Sự tuân thủ cú pháp của ngôn ngữ lập trình.
B. Kiến trúc của cơ sở dữ liệu.
C. Mức độ đáp ứng yêu cầu và nhu cầu thực tế của khách hàng.
D. Số lượng dòng code được sinh ra.
*Đáp án: C*

**Câu 116:** Rà soát phần mềm (Software Review) có ưu điểm gì nổi bật?
A. Không cần người tham gia, hoàn toàn do máy tính thực hiện.
B. Có thể phát hiện lỗi ngay trên tài liệu, bản thiết kế trước khi viết code, giúp tiết kiệm chi phí sửa lỗi.
C. Có thể kiểm tra được hiệu năng của phần mềm khi chạy với 10.000 người dùng.
D. Thay thế hoàn toàn được Kiểm thử tự động.
*Đáp án: B*

**Câu 117:** Kiểm thử hộp đen (Black-box testing) tập trung vào yếu tố nào?
A. Cấu trúc các lệnh IF-ELSE bên trong vòng lặp.
B. Các câu lệnh SQL truy vấn cơ sở dữ liệu.
C. Đầu vào (Input) và Đầu ra (Output) để kiểm tra các chức năng của hệ thống.
D. Việc tái cấu trúc mã nguồn (Refactoring).
*Đáp án: C*

**Câu 118:** Phương pháp kiểm thử nào yêu cầu Tester phải có kiến thức về mã nguồn và cấu trúc bên trong của phần mềm?
A. Kiểm thử hộp đen (Black-box testing).
B. Kiểm thử hộp trắng (White-box testing).
C. Kiểm thử chấp nhận (Acceptance testing).
D. Kiểm thử beta (Beta testing).
*Đáp án: B*

**Câu 119:** Mức độ kiểm thử thấp nhất, tập trung vào từng thành phần mã nguồn riêng biệt (ví dụ: một hàm) gọi là gì?
A. Kiểm thử hệ thống (System Testing).
B. Kiểm thử chấp nhận (Acceptance Testing).
C. Kiểm thử tích hợp (Integration Testing).
D. Kiểm thử đơn vị (Unit Testing).
*Đáp án: D*

**Câu 120:** Sau khi các Unit đã được kiểm thử, bước tiếp theo là kiểm tra sự giao tiếp giữa các Unit đó. Đó là mức độ kiểm thử nào?
A. Kiểm thử hộp đen.
B. Kiểm thử tích hợp (Integration Testing).
C. Kiểm thử hồi quy.
D. Kiểm thử bảo mật.
*Đáp án: B*

**Câu 121:** Ai thường là người thực hiện Kiểm thử chấp nhận (Acceptance Testing) trước khi phần mềm được đưa vào sử dụng chính thức?
A. Chuyên gia bảo mật (Security Expert).
B. Quản trị cơ sở dữ liệu (DBA).
C. Khách hàng hoặc người dùng cuối (End-user).
D. Lập trình viên mới vào nghề (Junior Developer).
*Đáp án: C*

**Câu 122:** Kiểm tra xem trang web có bị sập khi có 100.000 người truy cập cùng lúc hay không thuộc loại kiểm thử nào?
A. Kiểm thử chức năng (Functional Testing).
B. Kiểm thử đơn vị (Unit Testing).
C. Kiểm thử phi chức năng - Hiệu năng/Chịu tải (Performance/Load Testing).
D. Kiểm thử giao diện (UI Testing).
*Đáp án: C*

**Câu 123:** Sau khi lập trình viên sửa một bug, Tester kiểm tra lại toàn bộ các chức năng liên quan để đảm bảo việc sửa lỗi không gây ảnh hưởng đến tính năng khác. Đó gọi là gì?
A. Kiểm thử Alpha.
B. Kiểm thử bảo mật.
C. Kiểm thử hồi quy (Regression Testing).
D. Rà soát mã nguồn.
*Đáp án: C*

**Câu 124:** Kỹ thuật Phân vùng tương đương (Equivalence Partitioning) giúp gì cho quá trình kiểm thử?
A. Tăng số lượng test case lên mức tối đa.
B. Giảm số lượng test case bằng cách chọn các giá trị đại diện cho từng vùng dữ liệu có tính chất giống nhau.
C. Loại bỏ hoàn toàn sự tham gia của con người.
D. Đảm bảo phần mềm không có lỗi bảo mật.
*Đáp án: B*

**Câu 125:** Kỹ thuật Phân tích giá trị biên (Boundary Value Analysis) dựa trên nguyên lý nào?
A. Lỗi hiếm khi xảy ra ở giữa miền dữ liệu mà thường xuất hiện ở các ranh giới của miền đó.
B. Mọi giá trị dữ liệu đều có xác suất gây lỗi như nhau.
C. Chỉ cần test với giá trị 0 và giá trị rỗng (NULL) là đủ.
D. Lỗi chỉ xuất hiện khi người dùng nhập chữ cái thay vì số.
*Đáp án: A*

**Câu 126:** Một Bug Report (Báo cáo lỗi) hiệu quả KHÔNG cần thiết phải có thông tin nào dưới đây?
A. Các bước để tái hiện lại lỗi (Steps to reproduce).
B. Kết quả mong đợi (Expected Result) và kết quả thực tế (Actual Result).
C. Mức lương của lập trình viên đã gây ra lỗi.
D. Môi trường xảy ra lỗi (Hệ điều hành, Trình duyệt...).
*Đáp án: C*

**Câu 127:** Mục tiêu chính của Kiểm thử phần mềm là gì?
A. Chứng minh rằng phần mềm hoàn toàn không có lỗi.
B. Phát hiện ra lỗi và các vấn đề tiềm ẩn để cải thiện chất lượng sản phẩm.
C. Đo lường tốc độ gõ code của lập trình viên.
D. Tạo ra tài liệu hướng dẫn sử dụng tự động.
*Đáp án: B*

**Câu 128:** Hoạt động "Xác minh" (Verification) trong quy trình V&V (Verification and Validation) nhằm trả lời câu hỏi nào?
A. Chúng ta đã làm đúng sản phẩm khách hàng cần chưa?
B. Chúng ta có đang xây dựng sản phẩm đúng quy trình/thiết kế không?
C. Sản phẩm bán được bao nhiêu tiền?
D. Ai là người code chức năng này?
*Đáp án: B*

**Câu 129:** Hoạt động "Thẩm định" (Validation) đánh giá phần mềm dựa trên tiêu chí nào?
A. Sự tuân thủ cú pháp của ngôn ngữ lập trình.
B. Kiến trúc của cơ sở dữ liệu.
C. Mức độ đáp ứng yêu cầu và nhu cầu thực tế của khách hàng.
D. Số lượng dòng code được sinh ra.
*Đáp án: C*

**Câu 130:** Rà soát phần mềm (Software Review) có ưu điểm gì nổi bật?
A. Không cần người tham gia, hoàn toàn do máy tính thực hiện.
B. Có thể phát hiện lỗi ngay trên tài liệu, bản thiết kế trước khi viết code, giúp tiết kiệm chi phí sửa lỗi.
C. Có thể kiểm tra được hiệu năng của phần mềm khi chạy với 10.000 người dùng.
D. Thay thế hoàn toàn được Kiểm thử tự động.
*Đáp án: B*

**Câu 131:** Kiểm thử hộp đen (Black-box testing) tập trung vào yếu tố nào?
A. Cấu trúc các lệnh IF-ELSE bên trong vòng lặp.
B. Các câu lệnh SQL truy vấn cơ sở dữ liệu.
C. Đầu vào (Input) và Đầu ra (Output) để kiểm tra các chức năng của hệ thống.
D. Việc tái cấu trúc mã nguồn (Refactoring).
*Đáp án: C*

**Câu 132:** Phương pháp kiểm thử nào yêu cầu Tester phải có kiến thức về mã nguồn và cấu trúc bên trong của phần mềm?
A. Kiểm thử hộp đen (Black-box testing).
B. Kiểm thử hộp trắng (White-box testing).
C. Kiểm thử chấp nhận (Acceptance testing).
D. Kiểm thử beta (Beta testing).
*Đáp án: B*

**Câu 133:** Mức độ kiểm thử thấp nhất, tập trung vào từng thành phần mã nguồn riêng biệt (ví dụ: một hàm) gọi là gì?
A. Kiểm thử hệ thống (System Testing).
B. Kiểm thử chấp nhận (Acceptance Testing).
C. Kiểm thử tích hợp (Integration Testing).
D. Kiểm thử đơn vị (Unit Testing).
*Đáp án: D*

**Câu 134:** Sau khi các Unit đã được kiểm thử, bước tiếp theo là kiểm tra sự giao tiếp giữa các Unit đó. Đó là mức độ kiểm thử nào?
A. Kiểm thử hộp đen.
B. Kiểm thử tích hợp (Integration Testing).
C. Kiểm thử hồi quy.
D. Kiểm thử bảo mật.
*Đáp án: B*

**Câu 135:** Ai thường là người thực hiện Kiểm thử chấp nhận (Acceptance Testing) trước khi phần mềm được đưa vào sử dụng chính thức?
A. Chuyên gia bảo mật (Security Expert).
B. Quản trị cơ sở dữ liệu (DBA).
C. Khách hàng hoặc người dùng cuối (End-user).
D. Lập trình viên mới vào nghề (Junior Developer).
*Đáp án: C*

**Câu 136:** Kiểm tra xem trang web có bị sập khi có 100.000 người truy cập cùng lúc hay không thuộc loại kiểm thử nào?
A. Kiểm thử chức năng (Functional Testing).
B. Kiểm thử đơn vị (Unit Testing).
C. Kiểm thử phi chức năng - Hiệu năng/Chịu tải (Performance/Load Testing).
D. Kiểm thử giao diện (UI Testing).
*Đáp án: C*

**Câu 137:** Sau khi lập trình viên sửa một bug, Tester kiểm tra lại toàn bộ các chức năng liên quan để đảm bảo việc sửa lỗi không gây ảnh hưởng đến tính năng khác. Đó gọi là gì?
A. Kiểm thử Alpha.
B. Kiểm thử bảo mật.
C. Kiểm thử hồi quy (Regression Testing).
D. Rà soát mã nguồn.
*Đáp án: C*

**Câu 138:** Kỹ thuật Phân vùng tương đương (Equivalence Partitioning) giúp gì cho quá trình kiểm thử?
A. Tăng số lượng test case lên mức tối đa.
B. Giảm số lượng test case bằng cách chọn các giá trị đại diện cho từng vùng dữ liệu có tính chất giống nhau.
C. Loại bỏ hoàn toàn sự tham gia của con người.
D. Đảm bảo phần mềm không có lỗi bảo mật.
*Đáp án: B*

**Câu 139:** Kỹ thuật Phân tích giá trị biên (Boundary Value Analysis) dựa trên nguyên lý nào?
A. Lỗi hiếm khi xảy ra ở giữa miền dữ liệu mà thường xuất hiện ở các ranh giới của miền đó.
B. Mọi giá trị dữ liệu đều có xác suất gây lỗi như nhau.
C. Chỉ cần test với giá trị 0 và giá trị rỗng (NULL) là đủ.
D. Lỗi chỉ xuất hiện khi người dùng nhập chữ cái thay vì số.
*Đáp án: A*

**Câu 140:** Một Bug Report (Báo cáo lỗi) hiệu quả KHÔNG cần thiết phải có thông tin nào dưới đây?
A. Các bước để tái hiện lại lỗi (Steps to reproduce).
B. Kết quả mong đợi (Expected Result) và kết quả thực tế (Actual Result).
C. Mức lương của lập trình viên đã gây ra lỗi.
D. Môi trường xảy ra lỗi (Hệ điều hành, Trình duyệt...).
*Đáp án: C*

**Câu 141:** Mục tiêu chính của Kiểm thử phần mềm là gì?
A. Chứng minh rằng phần mềm hoàn toàn không có lỗi.
B. Phát hiện ra lỗi và các vấn đề tiềm ẩn để cải thiện chất lượng sản phẩm.
C. Đo lường tốc độ gõ code của lập trình viên.
D. Tạo ra tài liệu hướng dẫn sử dụng tự động.
*Đáp án: B*

**Câu 142:** Hoạt động "Xác minh" (Verification) trong quy trình V&V (Verification and Validation) nhằm trả lời câu hỏi nào?
A. Chúng ta đã làm đúng sản phẩm khách hàng cần chưa?
B. Chúng ta có đang xây dựng sản phẩm đúng quy trình/thiết kế không?
C. Sản phẩm bán được bao nhiêu tiền?
D. Ai là người code chức năng này?
*Đáp án: B*

**Câu 143:** Hoạt động "Thẩm định" (Validation) đánh giá phần mềm dựa trên tiêu chí nào?
A. Sự tuân thủ cú pháp của ngôn ngữ lập trình.
B. Kiến trúc của cơ sở dữ liệu.
C. Mức độ đáp ứng yêu cầu và nhu cầu thực tế của khách hàng.
D. Số lượng dòng code được sinh ra.
*Đáp án: C*

**Câu 144:** Rà soát phần mềm (Software Review) có ưu điểm gì nổi bật?
A. Không cần người tham gia, hoàn toàn do máy tính thực hiện.
B. Có thể phát hiện lỗi ngay trên tài liệu, bản thiết kế trước khi viết code, giúp tiết kiệm chi phí sửa lỗi.
C. Có thể kiểm tra được hiệu năng của phần mềm khi chạy với 10.000 người dùng.
D. Thay thế hoàn toàn được Kiểm thử tự động.
*Đáp án: B*

**Câu 145:** Kiểm thử hộp đen (Black-box testing) tập trung vào yếu tố nào?
A. Cấu trúc các lệnh IF-ELSE bên trong vòng lặp.
B. Các câu lệnh SQL truy vấn cơ sở dữ liệu.
C. Đầu vào (Input) và Đầu ra (Output) để kiểm tra các chức năng của hệ thống.
D. Việc tái cấu trúc mã nguồn (Refactoring).
*Đáp án: C*

**Câu 146:** Phương pháp kiểm thử nào yêu cầu Tester phải có kiến thức về mã nguồn và cấu trúc bên trong của phần mềm?
A. Kiểm thử hộp đen (Black-box testing).
B. Kiểm thử hộp trắng (White-box testing).
C. Kiểm thử chấp nhận (Acceptance testing).
D. Kiểm thử beta (Beta testing).
*Đáp án: B*

**Câu 147:** Mức độ kiểm thử thấp nhất, tập trung vào từng thành phần mã nguồn riêng biệt (ví dụ: một hàm) gọi là gì?
A. Kiểm thử hệ thống (System Testing).
B. Kiểm thử chấp nhận (Acceptance Testing).
C. Kiểm thử tích hợp (Integration Testing).
D. Kiểm thử đơn vị (Unit Testing).
*Đáp án: D*

**Câu 148:** Sau khi các Unit đã được kiểm thử, bước tiếp theo là kiểm tra sự giao tiếp giữa các Unit đó. Đó là mức độ kiểm thử nào?
A. Kiểm thử hộp đen.
B. Kiểm thử tích hợp (Integration Testing).
C. Kiểm thử hồi quy.
D. Kiểm thử bảo mật.
*Đáp án: B*

**Câu 149:** Ai thường là người thực hiện Kiểm thử chấp nhận (Acceptance Testing) trước khi phần mềm được đưa vào sử dụng chính thức?
A. Chuyên gia bảo mật (Security Expert).
B. Quản trị cơ sở dữ liệu (DBA).
C. Khách hàng hoặc người dùng cuối (End-user).
D. Lập trình viên mới vào nghề (Junior Developer).
*Đáp án: C*

**Câu 150:** Kiểm tra xem trang web có bị sập khi có 100.000 người truy cập cùng lúc hay không thuộc loại kiểm thử nào?
A. Kiểm thử chức năng (Functional Testing).
B. Kiểm thử đơn vị (Unit Testing).
C. Kiểm thử phi chức năng - Hiệu năng/Chịu tải (Performance/Load Testing).
D. Kiểm thử giao diện (UI Testing).
*Đáp án: C*

**Câu 151:** Sau khi lập trình viên sửa một bug, Tester kiểm tra lại toàn bộ các chức năng liên quan để đảm bảo việc sửa lỗi không gây ảnh hưởng đến tính năng khác. Đó gọi là gì?
A. Kiểm thử Alpha.
B. Kiểm thử bảo mật.
C. Kiểm thử hồi quy (Regression Testing).
D. Rà soát mã nguồn.
*Đáp án: C*

**Câu 152:** Kỹ thuật Phân vùng tương đương (Equivalence Partitioning) giúp gì cho quá trình kiểm thử?
A. Tăng số lượng test case lên mức tối đa.
B. Giảm số lượng test case bằng cách chọn các giá trị đại diện cho từng vùng dữ liệu có tính chất giống nhau.
C. Loại bỏ hoàn toàn sự tham gia của con người.
D. Đảm bảo phần mềm không có lỗi bảo mật.
*Đáp án: B*

**Câu 153:** Kỹ thuật Phân tích giá trị biên (Boundary Value Analysis) dựa trên nguyên lý nào?
A. Lỗi hiếm khi xảy ra ở giữa miền dữ liệu mà thường xuất hiện ở các ranh giới của miền đó.
B. Mọi giá trị dữ liệu đều có xác suất gây lỗi như nhau.
C. Chỉ cần test với giá trị 0 và giá trị rỗng (NULL) là đủ.
D. Lỗi chỉ xuất hiện khi người dùng nhập chữ cái thay vì số.
*Đáp án: A*

**Câu 154:** Một Bug Report (Báo cáo lỗi) hiệu quả KHÔNG cần thiết phải có thông tin nào dưới đây?
A. Các bước để tái hiện lại lỗi (Steps to reproduce).
B. Kết quả mong đợi (Expected Result) và kết quả thực tế (Actual Result).
C. Mức lương của lập trình viên đã gây ra lỗi.
D. Môi trường xảy ra lỗi (Hệ điều hành, Trình duyệt...).
*Đáp án: C*

**Câu 155:** Mục tiêu chính của Kiểm thử phần mềm là gì?
A. Chứng minh rằng phần mềm hoàn toàn không có lỗi.
B. Phát hiện ra lỗi và các vấn đề tiềm ẩn để cải thiện chất lượng sản phẩm.
C. Đo lường tốc độ gõ code của lập trình viên.
D. Tạo ra tài liệu hướng dẫn sử dụng tự động.
*Đáp án: B*

**Câu 156:** Hoạt động "Xác minh" (Verification) trong quy trình V&V (Verification and Validation) nhằm trả lời câu hỏi nào?
A. Chúng ta đã làm đúng sản phẩm khách hàng cần chưa?
B. Chúng ta có đang xây dựng sản phẩm đúng quy trình/thiết kế không?
C. Sản phẩm bán được bao nhiêu tiền?
D. Ai là người code chức năng này?
*Đáp án: B*

**Câu 157:** Hoạt động "Thẩm định" (Validation) đánh giá phần mềm dựa trên tiêu chí nào?
A. Sự tuân thủ cú pháp của ngôn ngữ lập trình.
B. Kiến trúc của cơ sở dữ liệu.
C. Mức độ đáp ứng yêu cầu và nhu cầu thực tế của khách hàng.
D. Số lượng dòng code được sinh ra.
*Đáp án: C*

**Câu 158:** Rà soát phần mềm (Software Review) có ưu điểm gì nổi bật?
A. Không cần người tham gia, hoàn toàn do máy tính thực hiện.
B. Có thể phát hiện lỗi ngay trên tài liệu, bản thiết kế trước khi viết code, giúp tiết kiệm chi phí sửa lỗi.
C. Có thể kiểm tra được hiệu năng của phần mềm khi chạy với 10.000 người dùng.
D. Thay thế hoàn toàn được Kiểm thử tự động.
*Đáp án: B*

**Câu 159:** Kiểm thử hộp đen (Black-box testing) tập trung vào yếu tố nào?
A. Cấu trúc các lệnh IF-ELSE bên trong vòng lặp.
B. Các câu lệnh SQL truy vấn cơ sở dữ liệu.
C. Đầu vào (Input) và Đầu ra (Output) để kiểm tra các chức năng của hệ thống.
D. Việc tái cấu trúc mã nguồn (Refactoring).
*Đáp án: C*

**Câu 160:** Phương pháp kiểm thử nào yêu cầu Tester phải có kiến thức về mã nguồn và cấu trúc bên trong của phần mềm?
A. Kiểm thử hộp đen (Black-box testing).
B. Kiểm thử hộp trắng (White-box testing).
C. Kiểm thử chấp nhận (Acceptance testing).
D. Kiểm thử beta (Beta testing).
*Đáp án: B*

**Câu 161:** Mức độ kiểm thử thấp nhất, tập trung vào từng thành phần mã nguồn riêng biệt (ví dụ: một hàm) gọi là gì?
A. Kiểm thử hệ thống (System Testing).
B. Kiểm thử chấp nhận (Acceptance Testing).
C. Kiểm thử tích hợp (Integration Testing).
D. Kiểm thử đơn vị (Unit Testing).
*Đáp án: D*

**Câu 162:** Sau khi các Unit đã được kiểm thử, bước tiếp theo là kiểm tra sự giao tiếp giữa các Unit đó. Đó là mức độ kiểm thử nào?
A. Kiểm thử hộp đen.
B. Kiểm thử tích hợp (Integration Testing).
C. Kiểm thử hồi quy.
D. Kiểm thử bảo mật.
*Đáp án: B*

**Câu 163:** Ai thường là người thực hiện Kiểm thử chấp nhận (Acceptance Testing) trước khi phần mềm được đưa vào sử dụng chính thức?
A. Chuyên gia bảo mật (Security Expert).
B. Quản trị cơ sở dữ liệu (DBA).
C. Khách hàng hoặc người dùng cuối (End-user).
D. Lập trình viên mới vào nghề (Junior Developer).
*Đáp án: C*

**Câu 164:** Kiểm tra xem trang web có bị sập khi có 100.000 người truy cập cùng lúc hay không thuộc loại kiểm thử nào?
A. Kiểm thử chức năng (Functional Testing).
B. Kiểm thử đơn vị (Unit Testing).
C. Kiểm thử phi chức năng - Hiệu năng/Chịu tải (Performance/Load Testing).
D. Kiểm thử giao diện (UI Testing).
*Đáp án: C*

**Câu 165:** Sau khi lập trình viên sửa một bug, Tester kiểm tra lại toàn bộ các chức năng liên quan để đảm bảo việc sửa lỗi không gây ảnh hưởng đến tính năng khác. Đó gọi là gì?
A. Kiểm thử Alpha.
B. Kiểm thử bảo mật.
C. Kiểm thử hồi quy (Regression Testing).
D. Rà soát mã nguồn.
*Đáp án: C*

**Câu 166:** Kỹ thuật Phân vùng tương đương (Equivalence Partitioning) giúp gì cho quá trình kiểm thử?
A. Tăng số lượng test case lên mức tối đa.
B. Giảm số lượng test case bằng cách chọn các giá trị đại diện cho từng vùng dữ liệu có tính chất giống nhau.
C. Loại bỏ hoàn toàn sự tham gia của con người.
D. Đảm bảo phần mềm không có lỗi bảo mật.
*Đáp án: B*

**Câu 167:** Kỹ thuật Phân tích giá trị biên (Boundary Value Analysis) dựa trên nguyên lý nào?
A. Lỗi hiếm khi xảy ra ở giữa miền dữ liệu mà thường xuất hiện ở các ranh giới của miền đó.
B. Mọi giá trị dữ liệu đều có xác suất gây lỗi như nhau.
C. Chỉ cần test với giá trị 0 và giá trị rỗng (NULL) là đủ.
D. Lỗi chỉ xuất hiện khi người dùng nhập chữ cái thay vì số.
*Đáp án: A*

**Câu 168:** Một Bug Report (Báo cáo lỗi) hiệu quả KHÔNG cần thiết phải có thông tin nào dưới đây?
A. Các bước để tái hiện lại lỗi (Steps to reproduce).
B. Kết quả mong đợi (Expected Result) và kết quả thực tế (Actual Result).
C. Mức lương của lập trình viên đã gây ra lỗi.
D. Môi trường xảy ra lỗi (Hệ điều hành, Trình duyệt...).
*Đáp án: C*

**Câu 169:** Mục tiêu chính của Kiểm thử phần mềm là gì?
A. Chứng minh rằng phần mềm hoàn toàn không có lỗi.
B. Phát hiện ra lỗi và các vấn đề tiềm ẩn để cải thiện chất lượng sản phẩm.
C. Đo lường tốc độ gõ code của lập trình viên.
D. Tạo ra tài liệu hướng dẫn sử dụng tự động.
*Đáp án: B*

**Câu 170:** Hoạt động "Xác minh" (Verification) trong quy trình V&V (Verification and Validation) nhằm trả lời câu hỏi nào?
A. Chúng ta đã làm đúng sản phẩm khách hàng cần chưa?
B. Chúng ta có đang xây dựng sản phẩm đúng quy trình/thiết kế không?
C. Sản phẩm bán được bao nhiêu tiền?
D. Ai là người code chức năng này?
*Đáp án: B*

**Câu 171:** Hoạt động "Thẩm định" (Validation) đánh giá phần mềm dựa trên tiêu chí nào?
A. Sự tuân thủ cú pháp của ngôn ngữ lập trình.
B. Kiến trúc của cơ sở dữ liệu.
C. Mức độ đáp ứng yêu cầu và nhu cầu thực tế của khách hàng.
D. Số lượng dòng code được sinh ra.
*Đáp án: C*

**Câu 172:** Rà soát phần mềm (Software Review) có ưu điểm gì nổi bật?
A. Không cần người tham gia, hoàn toàn do máy tính thực hiện.
B. Có thể phát hiện lỗi ngay trên tài liệu, bản thiết kế trước khi viết code, giúp tiết kiệm chi phí sửa lỗi.
C. Có thể kiểm tra được hiệu năng của phần mềm khi chạy với 10.000 người dùng.
D. Thay thế hoàn toàn được Kiểm thử tự động.
*Đáp án: B*

**Câu 173:** Kiểm thử hộp đen (Black-box testing) tập trung vào yếu tố nào?
A. Cấu trúc các lệnh IF-ELSE bên trong vòng lặp.
B. Các câu lệnh SQL truy vấn cơ sở dữ liệu.
C. Đầu vào (Input) và Đầu ra (Output) để kiểm tra các chức năng của hệ thống.
D. Việc tái cấu trúc mã nguồn (Refactoring).
*Đáp án: C*

**Câu 174:** Phương pháp kiểm thử nào yêu cầu Tester phải có kiến thức về mã nguồn và cấu trúc bên trong của phần mềm?
A. Kiểm thử hộp đen (Black-box testing).
B. Kiểm thử hộp trắng (White-box testing).
C. Kiểm thử chấp nhận (Acceptance testing).
D. Kiểm thử beta (Beta testing).
*Đáp án: B*

**Câu 175:** Mức độ kiểm thử thấp nhất, tập trung vào từng thành phần mã nguồn riêng biệt (ví dụ: một hàm) gọi là gì?
A. Kiểm thử hệ thống (System Testing).
B. Kiểm thử chấp nhận (Acceptance Testing).
C. Kiểm thử tích hợp (Integration Testing).
D. Kiểm thử đơn vị (Unit Testing).
*Đáp án: D*

**Câu 176:** Sau khi các Unit đã được kiểm thử, bước tiếp theo là kiểm tra sự giao tiếp giữa các Unit đó. Đó là mức độ kiểm thử nào?
A. Kiểm thử hộp đen.
B. Kiểm thử tích hợp (Integration Testing).
C. Kiểm thử hồi quy.
D. Kiểm thử bảo mật.
*Đáp án: B*

**Câu 177:** Ai thường là người thực hiện Kiểm thử chấp nhận (Acceptance Testing) trước khi phần mềm được đưa vào sử dụng chính thức?
A. Chuyên gia bảo mật (Security Expert).
B. Quản trị cơ sở dữ liệu (DBA).
C. Khách hàng hoặc người dùng cuối (End-user).
D. Lập trình viên mới vào nghề (Junior Developer).
*Đáp án: C*

**Câu 178:** Kiểm tra xem trang web có bị sập khi có 100.000 người truy cập cùng lúc hay không thuộc loại kiểm thử nào?
A. Kiểm thử chức năng (Functional Testing).
B. Kiểm thử đơn vị (Unit Testing).
C. Kiểm thử phi chức năng - Hiệu năng/Chịu tải (Performance/Load Testing).
D. Kiểm thử giao diện (UI Testing).
*Đáp án: C*

**Câu 179:** Sau khi lập trình viên sửa một bug, Tester kiểm tra lại toàn bộ các chức năng liên quan để đảm bảo việc sửa lỗi không gây ảnh hưởng đến tính năng khác. Đó gọi là gì?
A. Kiểm thử Alpha.
B. Kiểm thử bảo mật.
C. Kiểm thử hồi quy (Regression Testing).
D. Rà soát mã nguồn.
*Đáp án: C*

**Câu 180:** Kỹ thuật Phân vùng tương đương (Equivalence Partitioning) giúp gì cho quá trình kiểm thử?
A. Tăng số lượng test case lên mức tối đa.
B. Giảm số lượng test case bằng cách chọn các giá trị đại diện cho từng vùng dữ liệu có tính chất giống nhau.
C. Loại bỏ hoàn toàn sự tham gia của con người.
D. Đảm bảo phần mềm không có lỗi bảo mật.
*Đáp án: B*

**Câu 181:** Kỹ thuật Phân tích giá trị biên (Boundary Value Analysis) dựa trên nguyên lý nào?
A. Lỗi hiếm khi xảy ra ở giữa miền dữ liệu mà thường xuất hiện ở các ranh giới của miền đó.
B. Mọi giá trị dữ liệu đều có xác suất gây lỗi như nhau.
C. Chỉ cần test với giá trị 0 và giá trị rỗng (NULL) là đủ.
D. Lỗi chỉ xuất hiện khi người dùng nhập chữ cái thay vì số.
*Đáp án: A*

**Câu 182:** Một Bug Report (Báo cáo lỗi) hiệu quả KHÔNG cần thiết phải có thông tin nào dưới đây?
A. Các bước để tái hiện lại lỗi (Steps to reproduce).
B. Kết quả mong đợi (Expected Result) và kết quả thực tế (Actual Result).
C. Mức lương của lập trình viên đã gây ra lỗi.
D. Môi trường xảy ra lỗi (Hệ điều hành, Trình duyệt...).
*Đáp án: C*

**Câu 183:** Mục tiêu chính của Kiểm thử phần mềm là gì?
A. Chứng minh rằng phần mềm hoàn toàn không có lỗi.
B. Phát hiện ra lỗi và các vấn đề tiềm ẩn để cải thiện chất lượng sản phẩm.
C. Đo lường tốc độ gõ code của lập trình viên.
D. Tạo ra tài liệu hướng dẫn sử dụng tự động.
*Đáp án: B*

**Câu 184:** Hoạt động "Xác minh" (Verification) trong quy trình V&V (Verification and Validation) nhằm trả lời câu hỏi nào?
A. Chúng ta đã làm đúng sản phẩm khách hàng cần chưa?
B. Chúng ta có đang xây dựng sản phẩm đúng quy trình/thiết kế không?
C. Sản phẩm bán được bao nhiêu tiền?
D. Ai là người code chức năng này?
*Đáp án: B*

**Câu 185:** Hoạt động "Thẩm định" (Validation) đánh giá phần mềm dựa trên tiêu chí nào?
A. Sự tuân thủ cú pháp của ngôn ngữ lập trình.
B. Kiến trúc của cơ sở dữ liệu.
C. Mức độ đáp ứng yêu cầu và nhu cầu thực tế của khách hàng.
D. Số lượng dòng code được sinh ra.
*Đáp án: C*

**Câu 186:** Rà soát phần mềm (Software Review) có ưu điểm gì nổi bật?
A. Không cần người tham gia, hoàn toàn do máy tính thực hiện.
B. Có thể phát hiện lỗi ngay trên tài liệu, bản thiết kế trước khi viết code, giúp tiết kiệm chi phí sửa lỗi.
C. Có thể kiểm tra được hiệu năng của phần mềm khi chạy với 10.000 người dùng.
D. Thay thế hoàn toàn được Kiểm thử tự động.
*Đáp án: B*

**Câu 187:** Kiểm thử hộp đen (Black-box testing) tập trung vào yếu tố nào?
A. Cấu trúc các lệnh IF-ELSE bên trong vòng lặp.
B. Các câu lệnh SQL truy vấn cơ sở dữ liệu.
C. Đầu vào (Input) và Đầu ra (Output) để kiểm tra các chức năng của hệ thống.
D. Việc tái cấu trúc mã nguồn (Refactoring).
*Đáp án: C*

**Câu 188:** Phương pháp kiểm thử nào yêu cầu Tester phải có kiến thức về mã nguồn và cấu trúc bên trong của phần mềm?
A. Kiểm thử hộp đen (Black-box testing).
B. Kiểm thử hộp trắng (White-box testing).
C. Kiểm thử chấp nhận (Acceptance testing).
D. Kiểm thử beta (Beta testing).
*Đáp án: B*

**Câu 189:** Mức độ kiểm thử thấp nhất, tập trung vào từng thành phần mã nguồn riêng biệt (ví dụ: một hàm) gọi là gì?
A. Kiểm thử hệ thống (System Testing).
B. Kiểm thử chấp nhận (Acceptance Testing).
C. Kiểm thử tích hợp (Integration Testing).
D. Kiểm thử đơn vị (Unit Testing).
*Đáp án: D*

**Câu 190:** Sau khi các Unit đã được kiểm thử, bước tiếp theo là kiểm tra sự giao tiếp giữa các Unit đó. Đó là mức độ kiểm thử nào?
A. Kiểm thử hộp đen.
B. Kiểm thử tích hợp (Integration Testing).
C. Kiểm thử hồi quy.
D. Kiểm thử bảo mật.
*Đáp án: B*

**Câu 191:** Ai thường là người thực hiện Kiểm thử chấp nhận (Acceptance Testing) trước khi phần mềm được đưa vào sử dụng chính thức?
A. Chuyên gia bảo mật (Security Expert).
B. Quản trị cơ sở dữ liệu (DBA).
C. Khách hàng hoặc người dùng cuối (End-user).
D. Lập trình viên mới vào nghề (Junior Developer).
*Đáp án: C*

**Câu 192:** Kiểm tra xem trang web có bị sập khi có 100.000 người truy cập cùng lúc hay không thuộc loại kiểm thử nào?
A. Kiểm thử chức năng (Functional Testing).
B. Kiểm thử đơn vị (Unit Testing).
C. Kiểm thử phi chức năng - Hiệu năng/Chịu tải (Performance/Load Testing).
D. Kiểm thử giao diện (UI Testing).
*Đáp án: C*

**Câu 193:** Sau khi lập trình viên sửa một bug, Tester kiểm tra lại toàn bộ các chức năng liên quan để đảm bảo việc sửa lỗi không gây ảnh hưởng đến tính năng khác. Đó gọi là gì?
A. Kiểm thử Alpha.
B. Kiểm thử bảo mật.
C. Kiểm thử hồi quy (Regression Testing).
D. Rà soát mã nguồn.
*Đáp án: C*

**Câu 194:** Kỹ thuật Phân vùng tương đương (Equivalence Partitioning) giúp gì cho quá trình kiểm thử?
A. Tăng số lượng test case lên mức tối đa.
B. Giảm số lượng test case bằng cách chọn các giá trị đại diện cho từng vùng dữ liệu có tính chất giống nhau.
C. Loại bỏ hoàn toàn sự tham gia của con người.
D. Đảm bảo phần mềm không có lỗi bảo mật.
*Đáp án: B*

**Câu 195:** Kỹ thuật Phân tích giá trị biên (Boundary Value Analysis) dựa trên nguyên lý nào?
A. Lỗi hiếm khi xảy ra ở giữa miền dữ liệu mà thường xuất hiện ở các ranh giới của miền đó.
B. Mọi giá trị dữ liệu đều có xác suất gây lỗi như nhau.
C. Chỉ cần test với giá trị 0 và giá trị rỗng (NULL) là đủ.
D. Lỗi chỉ xuất hiện khi người dùng nhập chữ cái thay vì số.
*Đáp án: A*

**Câu 196:** Một Bug Report (Báo cáo lỗi) hiệu quả KHÔNG cần thiết phải có thông tin nào dưới đây?
A. Các bước để tái hiện lại lỗi (Steps to reproduce).
B. Kết quả mong đợi (Expected Result) và kết quả thực tế (Actual Result).
C. Mức lương của lập trình viên đã gây ra lỗi.
D. Môi trường xảy ra lỗi (Hệ điều hành, Trình duyệt...).
*Đáp án: C*

**Câu 197:** Mục tiêu chính của Kiểm thử phần mềm là gì?
A. Chứng minh rằng phần mềm hoàn toàn không có lỗi.
B. Phát hiện ra lỗi và các vấn đề tiềm ẩn để cải thiện chất lượng sản phẩm.
C. Đo lường tốc độ gõ code của lập trình viên.
D. Tạo ra tài liệu hướng dẫn sử dụng tự động.
*Đáp án: B*

**Câu 198:** Hoạt động "Xác minh" (Verification) trong quy trình V&V (Verification and Validation) nhằm trả lời câu hỏi nào?
A. Chúng ta đã làm đúng sản phẩm khách hàng cần chưa?
B. Chúng ta có đang xây dựng sản phẩm đúng quy trình/thiết kế không?
C. Sản phẩm bán được bao nhiêu tiền?
D. Ai là người code chức năng này?
*Đáp án: B*

**Câu 199:** Hoạt động "Thẩm định" (Validation) đánh giá phần mềm dựa trên tiêu chí nào?
A. Sự tuân thủ cú pháp của ngôn ngữ lập trình.
B. Kiến trúc của cơ sở dữ liệu.
C. Mức độ đáp ứng yêu cầu và nhu cầu thực tế của khách hàng.
D. Số lượng dòng code được sinh ra.
*Đáp án: C*

**Câu 200:** Rà soát phần mềm (Software Review) có ưu điểm gì nổi bật?
A. Không cần người tham gia, hoàn toàn do máy tính thực hiện.
B. Có thể phát hiện lỗi ngay trên tài liệu, bản thiết kế trước khi viết code, giúp tiết kiệm chi phí sửa lỗi.
C. Có thể kiểm tra được hiệu năng của phần mềm khi chạy với 10.000 người dùng.
D. Thay thế hoàn toàn được Kiểm thử tự động.
*Đáp án: B*

**Câu 201:** Kiểm thử hộp đen (Black-box testing) tập trung vào yếu tố nào?
A. Cấu trúc các lệnh IF-ELSE bên trong vòng lặp.
B. Các câu lệnh SQL truy vấn cơ sở dữ liệu.
C. Đầu vào (Input) và Đầu ra (Output) để kiểm tra các chức năng của hệ thống.
D. Việc tái cấu trúc mã nguồn (Refactoring).
*Đáp án: C*

**Câu 202:** Phương pháp kiểm thử nào yêu cầu Tester phải có kiến thức về mã nguồn và cấu trúc bên trong của phần mềm?
A. Kiểm thử hộp đen (Black-box testing).
B. Kiểm thử hộp trắng (White-box testing).
C. Kiểm thử chấp nhận (Acceptance testing).
D. Kiểm thử beta (Beta testing).
*Đáp án: B*

**Câu 203:** Mức độ kiểm thử thấp nhất, tập trung vào từng thành phần mã nguồn riêng biệt (ví dụ: một hàm) gọi là gì?
A. Kiểm thử hệ thống (System Testing).
B. Kiểm thử chấp nhận (Acceptance Testing).
C. Kiểm thử tích hợp (Integration Testing).
D. Kiểm thử đơn vị (Unit Testing).
*Đáp án: D*

**Câu 204:** Sau khi các Unit đã được kiểm thử, bước tiếp theo là kiểm tra sự giao tiếp giữa các Unit đó. Đó là mức độ kiểm thử nào?
A. Kiểm thử hộp đen.
B. Kiểm thử tích hợp (Integration Testing).
C. Kiểm thử hồi quy.
D. Kiểm thử bảo mật.
*Đáp án: B*

**Câu 205:** Ai thường là người thực hiện Kiểm thử chấp nhận (Acceptance Testing) trước khi phần mềm được đưa vào sử dụng chính thức?
A. Chuyên gia bảo mật (Security Expert).
B. Quản trị cơ sở dữ liệu (DBA).
C. Khách hàng hoặc người dùng cuối (End-user).
D. Lập trình viên mới vào nghề (Junior Developer).
*Đáp án: C*

**Câu 206:** Kiểm tra xem trang web có bị sập khi có 100.000 người truy cập cùng lúc hay không thuộc loại kiểm thử nào?
A. Kiểm thử chức năng (Functional Testing).
B. Kiểm thử đơn vị (Unit Testing).
C. Kiểm thử phi chức năng - Hiệu năng/Chịu tải (Performance/Load Testing).
D. Kiểm thử giao diện (UI Testing).
*Đáp án: C*

**Câu 207:** Sau khi lập trình viên sửa một bug, Tester kiểm tra lại toàn bộ các chức năng liên quan để đảm bảo việc sửa lỗi không gây ảnh hưởng đến tính năng khác. Đó gọi là gì?
A. Kiểm thử Alpha.
B. Kiểm thử bảo mật.
C. Kiểm thử hồi quy (Regression Testing).
D. Rà soát mã nguồn.
*Đáp án: C*

**Câu 208:** Kỹ thuật Phân vùng tương đương (Equivalence Partitioning) giúp gì cho quá trình kiểm thử?
A. Tăng số lượng test case lên mức tối đa.
B. Giảm số lượng test case bằng cách chọn các giá trị đại diện cho từng vùng dữ liệu có tính chất giống nhau.
C. Loại bỏ hoàn toàn sự tham gia của con người.
D. Đảm bảo phần mềm không có lỗi bảo mật.
*Đáp án: B*

**Câu 209:** Kỹ thuật Phân tích giá trị biên (Boundary Value Analysis) dựa trên nguyên lý nào?
A. Lỗi hiếm khi xảy ra ở giữa miền dữ liệu mà thường xuất hiện ở các ranh giới của miền đó.
B. Mọi giá trị dữ liệu đều có xác suất gây lỗi như nhau.
C. Chỉ cần test với giá trị 0 và giá trị rỗng (NULL) là đủ.
D. Lỗi chỉ xuất hiện khi người dùng nhập chữ cái thay vì số.
*Đáp án: A*

**Câu 210:** Một Bug Report (Báo cáo lỗi) hiệu quả KHÔNG cần thiết phải có thông tin nào dưới đây?
A. Các bước để tái hiện lại lỗi (Steps to reproduce).
B. Kết quả mong đợi (Expected Result) và kết quả thực tế (Actual Result).
C. Mức lương của lập trình viên đã gây ra lỗi.
D. Môi trường xảy ra lỗi (Hệ điều hành, Trình duyệt...).
*Đáp án: C*

**Câu 211:** Mục tiêu chính của Kiểm thử phần mềm là gì?
A. Chứng minh rằng phần mềm hoàn toàn không có lỗi.
B. Phát hiện ra lỗi và các vấn đề tiềm ẩn để cải thiện chất lượng sản phẩm.
C. Đo lường tốc độ gõ code của lập trình viên.
D. Tạo ra tài liệu hướng dẫn sử dụng tự động.
*Đáp án: B*

**Câu 212:** Hoạt động "Xác minh" (Verification) trong quy trình V&V (Verification and Validation) nhằm trả lời câu hỏi nào?
A. Chúng ta đã làm đúng sản phẩm khách hàng cần chưa?
B. Chúng ta có đang xây dựng sản phẩm đúng quy trình/thiết kế không?
C. Sản phẩm bán được bao nhiêu tiền?
D. Ai là người code chức năng này?
*Đáp án: B*

**Câu 213:** Hoạt động "Thẩm định" (Validation) đánh giá phần mềm dựa trên tiêu chí nào?
A. Sự tuân thủ cú pháp của ngôn ngữ lập trình.
B. Kiến trúc của cơ sở dữ liệu.
C. Mức độ đáp ứng yêu cầu và nhu cầu thực tế của khách hàng.
D. Số lượng dòng code được sinh ra.
*Đáp án: C*

**Câu 214:** Rà soát phần mềm (Software Review) có ưu điểm gì nổi bật?
A. Không cần người tham gia, hoàn toàn do máy tính thực hiện.
B. Có thể phát hiện lỗi ngay trên tài liệu, bản thiết kế trước khi viết code, giúp tiết kiệm chi phí sửa lỗi.
C. Có thể kiểm tra được hiệu năng của phần mềm khi chạy với 10.000 người dùng.
D. Thay thế hoàn toàn được Kiểm thử tự động.
*Đáp án: B*

**Câu 215:** Kiểm thử hộp đen (Black-box testing) tập trung vào yếu tố nào?
A. Cấu trúc các lệnh IF-ELSE bên trong vòng lặp.
B. Các câu lệnh SQL truy vấn cơ sở dữ liệu.
C. Đầu vào (Input) và Đầu ra (Output) để kiểm tra các chức năng của hệ thống.
D. Việc tái cấu trúc mã nguồn (Refactoring).
*Đáp án: C*

**Câu 216:** Phương pháp kiểm thử nào yêu cầu Tester phải có kiến thức về mã nguồn và cấu trúc bên trong của phần mềm?
A. Kiểm thử hộp đen (Black-box testing).
B. Kiểm thử hộp trắng (White-box testing).
C. Kiểm thử chấp nhận (Acceptance testing).
D. Kiểm thử beta (Beta testing).
*Đáp án: B*

**Câu 217:** Mức độ kiểm thử thấp nhất, tập trung vào từng thành phần mã nguồn riêng biệt (ví dụ: một hàm) gọi là gì?
A. Kiểm thử hệ thống (System Testing).
B. Kiểm thử chấp nhận (Acceptance Testing).
C. Kiểm thử tích hợp (Integration Testing).
D. Kiểm thử đơn vị (Unit Testing).
*Đáp án: D*

**Câu 218:** Sau khi các Unit đã được kiểm thử, bước tiếp theo là kiểm tra sự giao tiếp giữa các Unit đó. Đó là mức độ kiểm thử nào?
A. Kiểm thử hộp đen.
B. Kiểm thử tích hợp (Integration Testing).
C. Kiểm thử hồi quy.
D. Kiểm thử bảo mật.
*Đáp án: B*

**Câu 219:** Ai thường là người thực hiện Kiểm thử chấp nhận (Acceptance Testing) trước khi phần mềm được đưa vào sử dụng chính thức?
A. Chuyên gia bảo mật (Security Expert).
B. Quản trị cơ sở dữ liệu (DBA).
C. Khách hàng hoặc người dùng cuối (End-user).
D. Lập trình viên mới vào nghề (Junior Developer).
*Đáp án: C*

**Câu 220:** Kiểm tra xem trang web có bị sập khi có 100.000 người truy cập cùng lúc hay không thuộc loại kiểm thử nào?
A. Kiểm thử chức năng (Functional Testing).
B. Kiểm thử đơn vị (Unit Testing).
C. Kiểm thử phi chức năng - Hiệu năng/Chịu tải (Performance/Load Testing).
D. Kiểm thử giao diện (UI Testing).
*Đáp án: C*

**Câu 221:** Sau khi lập trình viên sửa một bug, Tester kiểm tra lại toàn bộ các chức năng liên quan để đảm bảo việc sửa lỗi không gây ảnh hưởng đến tính năng khác. Đó gọi là gì?
A. Kiểm thử Alpha.
B. Kiểm thử bảo mật.
C. Kiểm thử hồi quy (Regression Testing).
D. Rà soát mã nguồn.
*Đáp án: C*

**Câu 222:** Kỹ thuật Phân vùng tương đương (Equivalence Partitioning) giúp gì cho quá trình kiểm thử?
A. Tăng số lượng test case lên mức tối đa.
B. Giảm số lượng test case bằng cách chọn các giá trị đại diện cho từng vùng dữ liệu có tính chất giống nhau.
C. Loại bỏ hoàn toàn sự tham gia của con người.
D. Đảm bảo phần mềm không có lỗi bảo mật.
*Đáp án: B*

**Câu 223:** Kỹ thuật Phân tích giá trị biên (Boundary Value Analysis) dựa trên nguyên lý nào?
A. Lỗi hiếm khi xảy ra ở giữa miền dữ liệu mà thường xuất hiện ở các ranh giới của miền đó.
B. Mọi giá trị dữ liệu đều có xác suất gây lỗi như nhau.
C. Chỉ cần test với giá trị 0 và giá trị rỗng (NULL) là đủ.
D. Lỗi chỉ xuất hiện khi người dùng nhập chữ cái thay vì số.
*Đáp án: A*

**Câu 224:** Một Bug Report (Báo cáo lỗi) hiệu quả KHÔNG cần thiết phải có thông tin nào dưới đây?
A. Các bước để tái hiện lại lỗi (Steps to reproduce).
B. Kết quả mong đợi (Expected Result) và kết quả thực tế (Actual Result).
C. Mức lương của lập trình viên đã gây ra lỗi.
D. Môi trường xảy ra lỗi (Hệ điều hành, Trình duyệt...).
*Đáp án: C*

**Câu 225:** Mục tiêu chính của Kiểm thử phần mềm là gì?
A. Chứng minh rằng phần mềm hoàn toàn không có lỗi.
B. Phát hiện ra lỗi và các vấn đề tiềm ẩn để cải thiện chất lượng sản phẩm.
C. Đo lường tốc độ gõ code của lập trình viên.
D. Tạo ra tài liệu hướng dẫn sử dụng tự động.
*Đáp án: B*

**Câu 226:** Hoạt động "Xác minh" (Verification) trong quy trình V&V (Verification and Validation) nhằm trả lời câu hỏi nào?
A. Chúng ta đã làm đúng sản phẩm khách hàng cần chưa?
B. Chúng ta có đang xây dựng sản phẩm đúng quy trình/thiết kế không?
C. Sản phẩm bán được bao nhiêu tiền?
D. Ai là người code chức năng này?
*Đáp án: B*

**Câu 227:** Hoạt động "Thẩm định" (Validation) đánh giá phần mềm dựa trên tiêu chí nào?
A. Sự tuân thủ cú pháp của ngôn ngữ lập trình.
B. Kiến trúc của cơ sở dữ liệu.
C. Mức độ đáp ứng yêu cầu và nhu cầu thực tế của khách hàng.
D. Số lượng dòng code được sinh ra.
*Đáp án: C*

**Câu 228:** Rà soát phần mềm (Software Review) có ưu điểm gì nổi bật?
A. Không cần người tham gia, hoàn toàn do máy tính thực hiện.
B. Có thể phát hiện lỗi ngay trên tài liệu, bản thiết kế trước khi viết code, giúp tiết kiệm chi phí sửa lỗi.
C. Có thể kiểm tra được hiệu năng của phần mềm khi chạy với 10.000 người dùng.
D. Thay thế hoàn toàn được Kiểm thử tự động.
*Đáp án: B*

**Câu 229:** Kiểm thử hộp đen (Black-box testing) tập trung vào yếu tố nào?
A. Cấu trúc các lệnh IF-ELSE bên trong vòng lặp.
B. Các câu lệnh SQL truy vấn cơ sở dữ liệu.
C. Đầu vào (Input) và Đầu ra (Output) để kiểm tra các chức năng của hệ thống.
D. Việc tái cấu trúc mã nguồn (Refactoring).
*Đáp án: C*

**Câu 230:** Phương pháp kiểm thử nào yêu cầu Tester phải có kiến thức về mã nguồn và cấu trúc bên trong của phần mềm?
A. Kiểm thử hộp đen (Black-box testing).
B. Kiểm thử hộp trắng (White-box testing).
C. Kiểm thử chấp nhận (Acceptance testing).
D. Kiểm thử beta (Beta testing).
*Đáp án: B*

**Câu 231:** Mức độ kiểm thử thấp nhất, tập trung vào từng thành phần mã nguồn riêng biệt (ví dụ: một hàm) gọi là gì?
A. Kiểm thử hệ thống (System Testing).
B. Kiểm thử chấp nhận (Acceptance Testing).
C. Kiểm thử tích hợp (Integration Testing).
D. Kiểm thử đơn vị (Unit Testing).
*Đáp án: D*

**Câu 232:** Sau khi các Unit đã được kiểm thử, bước tiếp theo là kiểm tra sự giao tiếp giữa các Unit đó. Đó là mức độ kiểm thử nào?
A. Kiểm thử hộp đen.
B. Kiểm thử tích hợp (Integration Testing).
C. Kiểm thử hồi quy.
D. Kiểm thử bảo mật.
*Đáp án: B*

**Câu 233:** Ai thường là người thực hiện Kiểm thử chấp nhận (Acceptance Testing) trước khi phần mềm được đưa vào sử dụng chính thức?
A. Chuyên gia bảo mật (Security Expert).
B. Quản trị cơ sở dữ liệu (DBA).
C. Khách hàng hoặc người dùng cuối (End-user).
D. Lập trình viên mới vào nghề (Junior Developer).
*Đáp án: C*

**Câu 234:** Kiểm tra xem trang web có bị sập khi có 100.000 người truy cập cùng lúc hay không thuộc loại kiểm thử nào?
A. Kiểm thử chức năng (Functional Testing).
B. Kiểm thử đơn vị (Unit Testing).
C. Kiểm thử phi chức năng - Hiệu năng/Chịu tải (Performance/Load Testing).
D. Kiểm thử giao diện (UI Testing).
*Đáp án: C*

**Câu 235:** Sau khi lập trình viên sửa một bug, Tester kiểm tra lại toàn bộ các chức năng liên quan để đảm bảo việc sửa lỗi không gây ảnh hưởng đến tính năng khác. Đó gọi là gì?
A. Kiểm thử Alpha.
B. Kiểm thử bảo mật.
C. Kiểm thử hồi quy (Regression Testing).
D. Rà soát mã nguồn.
*Đáp án: C*

**Câu 236:** Kỹ thuật Phân vùng tương đương (Equivalence Partitioning) giúp gì cho quá trình kiểm thử?
A. Tăng số lượng test case lên mức tối đa.
B. Giảm số lượng test case bằng cách chọn các giá trị đại diện cho từng vùng dữ liệu có tính chất giống nhau.
C. Loại bỏ hoàn toàn sự tham gia của con người.
D. Đảm bảo phần mềm không có lỗi bảo mật.
*Đáp án: B*

**Câu 237:** Kỹ thuật Phân tích giá trị biên (Boundary Value Analysis) dựa trên nguyên lý nào?
A. Lỗi hiếm khi xảy ra ở giữa miền dữ liệu mà thường xuất hiện ở các ranh giới của miền đó.
B. Mọi giá trị dữ liệu đều có xác suất gây lỗi như nhau.
C. Chỉ cần test với giá trị 0 và giá trị rỗng (NULL) là đủ.
D. Lỗi chỉ xuất hiện khi người dùng nhập chữ cái thay vì số.
*Đáp án: A*

**Câu 238:** Một Bug Report (Báo cáo lỗi) hiệu quả KHÔNG cần thiết phải có thông tin nào dưới đây?
A. Các bước để tái hiện lại lỗi (Steps to reproduce).
B. Kết quả mong đợi (Expected Result) và kết quả thực tế (Actual Result).
C. Mức lương của lập trình viên đã gây ra lỗi.
D. Môi trường xảy ra lỗi (Hệ điều hành, Trình duyệt...).
*Đáp án: C*

**Câu 239:** Mục tiêu chính của Kiểm thử phần mềm là gì?
A. Chứng minh rằng phần mềm hoàn toàn không có lỗi.
B. Phát hiện ra lỗi và các vấn đề tiềm ẩn để cải thiện chất lượng sản phẩm.
C. Đo lường tốc độ gõ code của lập trình viên.
D. Tạo ra tài liệu hướng dẫn sử dụng tự động.
*Đáp án: B*

**Câu 240:** Hoạt động "Xác minh" (Verification) trong quy trình V&V (Verification and Validation) nhằm trả lời câu hỏi nào?
A. Chúng ta đã làm đúng sản phẩm khách hàng cần chưa?
B. Chúng ta có đang xây dựng sản phẩm đúng quy trình/thiết kế không?
C. Sản phẩm bán được bao nhiêu tiền?
D. Ai là người code chức năng này?
*Đáp án: B*

**Câu 241:** Hoạt động "Thẩm định" (Validation) đánh giá phần mềm dựa trên tiêu chí nào?
A. Sự tuân thủ cú pháp của ngôn ngữ lập trình.
B. Kiến trúc của cơ sở dữ liệu.
C. Mức độ đáp ứng yêu cầu và nhu cầu thực tế của khách hàng.
D. Số lượng dòng code được sinh ra.
*Đáp án: C*

**Câu 242:** Rà soát phần mềm (Software Review) có ưu điểm gì nổi bật?
A. Không cần người tham gia, hoàn toàn do máy tính thực hiện.
B. Có thể phát hiện lỗi ngay trên tài liệu, bản thiết kế trước khi viết code, giúp tiết kiệm chi phí sửa lỗi.
C. Có thể kiểm tra được hiệu năng của phần mềm khi chạy với 10.000 người dùng.
D. Thay thế hoàn toàn được Kiểm thử tự động.
*Đáp án: B*

**Câu 243:** Kiểm thử hộp đen (Black-box testing) tập trung vào yếu tố nào?
A. Cấu trúc các lệnh IF-ELSE bên trong vòng lặp.
B. Các câu lệnh SQL truy vấn cơ sở dữ liệu.
C. Đầu vào (Input) và Đầu ra (Output) để kiểm tra các chức năng của hệ thống.
D. Việc tái cấu trúc mã nguồn (Refactoring).
*Đáp án: C*

**Câu 244:** Phương pháp kiểm thử nào yêu cầu Tester phải có kiến thức về mã nguồn và cấu trúc bên trong của phần mềm?
A. Kiểm thử hộp đen (Black-box testing).
B. Kiểm thử hộp trắng (White-box testing).
C. Kiểm thử chấp nhận (Acceptance testing).
D. Kiểm thử beta (Beta testing).
*Đáp án: B*

**Câu 245:** Mức độ kiểm thử thấp nhất, tập trung vào từng thành phần mã nguồn riêng biệt (ví dụ: một hàm) gọi là gì?
A. Kiểm thử hệ thống (System Testing).
B. Kiểm thử chấp nhận (Acceptance Testing).
C. Kiểm thử tích hợp (Integration Testing).
D. Kiểm thử đơn vị (Unit Testing).
*Đáp án: D*

**Câu 246:** Sau khi các Unit đã được kiểm thử, bước tiếp theo là kiểm tra sự giao tiếp giữa các Unit đó. Đó là mức độ kiểm thử nào?
A. Kiểm thử hộp đen.
B. Kiểm thử tích hợp (Integration Testing).
C. Kiểm thử hồi quy.
D. Kiểm thử bảo mật.
*Đáp án: B*

**Câu 247:** Ai thường là người thực hiện Kiểm thử chấp nhận (Acceptance Testing) trước khi phần mềm được đưa vào sử dụng chính thức?
A. Chuyên gia bảo mật (Security Expert).
B. Quản trị cơ sở dữ liệu (DBA).
C. Khách hàng hoặc người dùng cuối (End-user).
D. Lập trình viên mới vào nghề (Junior Developer).
*Đáp án: C*

**Câu 248:** Kiểm tra xem trang web có bị sập khi có 100.000 người truy cập cùng lúc hay không thuộc loại kiểm thử nào?
A. Kiểm thử chức năng (Functional Testing).
B. Kiểm thử đơn vị (Unit Testing).
C. Kiểm thử phi chức năng - Hiệu năng/Chịu tải (Performance/Load Testing).
D. Kiểm thử giao diện (UI Testing).
*Đáp án: C*

**Câu 249:** Sau khi lập trình viên sửa một bug, Tester kiểm tra lại toàn bộ các chức năng liên quan để đảm bảo việc sửa lỗi không gây ảnh hưởng đến tính năng khác. Đó gọi là gì?
A. Kiểm thử Alpha.
B. Kiểm thử bảo mật.
C. Kiểm thử hồi quy (Regression Testing).
D. Rà soát mã nguồn.
*Đáp án: C*

**Câu 250:** Kỹ thuật Phân vùng tương đương (Equivalence Partitioning) giúp gì cho quá trình kiểm thử?
A. Tăng số lượng test case lên mức tối đa.
B. Giảm số lượng test case bằng cách chọn các giá trị đại diện cho từng vùng dữ liệu có tính chất giống nhau.
C. Loại bỏ hoàn toàn sự tham gia của con người.
D. Đảm bảo phần mềm không có lỗi bảo mật.
*Đáp án: B*
