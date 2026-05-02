# CHƯƠNG 2: QUY TRÌNH PHẦN MỀM VÀ CÁC MÔ HÌNH VÒNG ĐỜI

## PHẦN 1: Câu hỏi tự luận ngắn

1. **Quy trình phần mềm (Software process) là gì?**
   *Gợi ý:* Là một tập có cấu trúc các hoạt động cần thiết (như đặc tả, phát triển, thẩm định, cải tiến) để phát triển một hệ thống phần mềm.
2. **Kể tên 4 hoạt động cơ bản nhất của mọi quy trình phần mềm?**
   *Gợi ý:* Đặc tả (Specification), Phát triển/Thiết kế và cài đặt (Development), Thẩm định (Validation), và Cải tiến/Bảo trì (Evolution).
3. **Mô hình xây - sửa (Build and Fix) có đặc điểm gì?**
   *Gợi ý:* Không có thiết kế, không có đặc tả rõ ràng. Code trực tiếp rồi sửa lỗi. Dễ bắt đầu nhất nhưng chi phí bảo trì đắt nhất và khó quản lý nhất.
4. **Mô hình thác nước (Waterfall) là gì?**
   *Gợi ý:* Là mô hình phát triển phần mềm tuần tự, pha này nối tiếp pha kia (Yêu cầu -> Phân tích -> Thiết kế -> Cài đặt -> Kiểm thử -> Bảo trì). Phải hoàn thành pha trước mới sang pha sau.
5. **Nhược điểm lớn nhất của mô hình thác nước là gì?**
   *Gợi ý:* Thiếu linh hoạt, khó thích ứng với sự thay đổi yêu cầu của khách hàng khi dự án đang diễn ra. Sản phẩm thực tế chỉ xuất hiện ở cuối dự án.
6. **Mô hình thác nước phù hợp nhất với loại dự án nào?**
   *Gợi ý:* Phù hợp với dự án có yêu cầu rõ ràng ngay từ đầu, ổn định, ít thay đổi, dự án nhỏ hoặc những hệ thống có quy trình chuẩn mực nghiêm ngặt.
7. **Mô hình bản mẫu nhanh (Rapid Prototyping) hoạt động như thế nào?**
   *Gợi ý:* Xây dựng nhanh một phiên bản "nháp" (prototype) của phần mềm để khách hàng dùng thử và góp ý, sau đó thu thập lại yêu cầu chính xác rồi mới tiến hành xây dựng hệ thống thật.
8. **Ưu điểm của mô hình bản mẫu nhanh là gì?**
   *Gợi ý:* Giúp khách hàng hình dung rõ sản phẩm sớm, giải quyết sự không chắc chắn của yêu cầu, giảm thiểu rủi ro làm sai yêu cầu.
9. **Mô hình tiến hóa (Evolutionary / Iterative) có đặc điểm gì?**
   *Gợi ý:* Đặc trưng bởi các vòng lặp phản hồi. Phần mềm được phát triển thành nhiều phiên bản, mỗi phiên bản bổ sung thêm tính năng cho đến khi hoàn chỉnh.
10. **Sự khác biệt giữa tăng trưởng (Incremental) và lặp (Iterative) là gì?**
    *Gợi ý:* Lặp là làm đi làm lại để tinh chỉnh và làm mịn hệ thống. Tăng trưởng là xây dựng và chuyển giao từng phần (module) của hệ thống theo từng giai đoạn.
11. **Mô hình xoắn ốc (Spiral model) do ai đề xuất và đặc điểm nổi bật nhất là gì?**
    *Gợi ý:* Do Barry Boehm đề xuất. Đặc điểm nổi bật nhất là phân tích và quản lý rủi ro (Risk management) được đặt lên hàng đầu qua mỗi vòng xoắn ốc.
12. **Mỗi vòng lặp của mô hình xoắn ốc bao gồm những công việc gì?**
    *Gợi ý:* Xác định mục tiêu, Đánh giá và giảm thiểu rủi ro, Phát triển và kiểm định, Lập kế hoạch cho pha tiếp theo.
13. **Mô hình xoắn ốc phù hợp với loại dự án nào?**
    *Gợi ý:* Các dự án quy mô lớn, phức tạp, rủi ro cao và thường dành cho nội bộ (in-house) hơn là phần mềm thương mại đại trà.
14. **RUP (Rational Unified Process) là gì?**
    *Gợi ý:* RUP là một quy trình phát triển phần mềm lặp và tăng trưởng, hướng đối tượng, hướng use-case và lấy kiến trúc làm trung tâm, sử dụng UML.
15. **Kể tên 4 pha trong vòng đời của quy trình RUP?**
    *Gợi ý:* Khởi đầu (Inception), Khảo sát tỉ mỉ (Elaboration), Xây dựng (Construction), và Chuyển giao/Chuyển tiếp (Transition).
16. **Luồng công việc (Workflow) nào thường chiếm ưu thế trong pha Khởi đầu (Inception) của RUP?**
    *Gợi ý:* Luồng công việc đặc tả yêu cầu và mô hình nghiệp vụ chiếm ưu thế.
17. **Sản phẩm của pha Khởi đầu (Inception) trong RUP thường bao gồm gì?**
    *Gợi ý:* Tầm nhìn dự án, các use case ban đầu, rủi ro ban đầu, kế hoạch kinh doanh sơ bộ và quyết định có đi tiếp (go/no-go) hay không.
18. **Pha khảo sát tỉ mỉ (Elaboration) trong RUP giải quyết vấn đề gì?**
    *Gợi ý:* Làm mịn các yêu cầu, xây dựng kiến trúc nền tảng ổn định, đánh giá và giảm thiểu các rủi ro kỹ thuật nghiêm trọng.
19. **Phần mềm mã nguồn mở (Open-source) có đặc điểm gì về quy trình phát triển?**
    *Gợi ý:* Thường không có thiết kế/đặc tả hình thức từ đầu. Bắt đầu bằng một phiên bản cơ bản, sau đó phát triển dựa trên cộng đồng đóng góp và phản hồi.
20. **Tại sao không thể áp dụng một quy trình phần mềm duy nhất cho mọi dự án?**
    *Gợi ý:* Vì mỗi dự án có quy mô, ngân sách, mức độ rủi ro, thời gian và tính rõ ràng của yêu cầu khác nhau, đòi hỏi phương pháp quản lý và mô hình phù hợp riêng.
21. **Mô hình thác nước có cho phép quay lại pha trước đó dễ dàng không?**
    *Gợi ý:* Về lý thuyết nguyên bản là không. Thực tế có các vòng lặp phản hồi nhưng chi phí quay lại rất đắt đỏ.
22. **Phiên bản "Beta" thường xuất hiện nhiều nhất trong pha nào của RUP?**
    *Gợi ý:* Cuối pha Xây dựng (Construction) hoặc trong pha Chuyển giao (Transition).
23. **UML (Unified Modeling Language) đóng vai trò gì trong quy trình RUP?**
    *Gợi ý:* Là công cụ biểu diễn đồ họa trực quan (các biểu đồ) giúp giao tiếp, thiết kế và mô hình hóa hệ thống phần mềm một cách chuẩn xác.
24. **Ưu điểm của mô hình Lặp và Tăng trưởng so với mô hình Thác nước?**
    *Gợi ý:* Giao sản phẩm sớm từng phần, linh hoạt đối phó với sự thay đổi yêu cầu, phát hiện lỗi và rủi ro sớm qua từng vòng lặp.
25. **Nếu khách hàng không rành về kỹ thuật và chưa hình dung rõ yêu cầu, mô hình nào là tối ưu nhất ở giai đoạn đầu?**
    *Gợi ý:* Mô hình Bản mẫu nhanh (Rapid Prototyping) để khách hàng có cái nhìn trực quan và dễ xác định yêu cầu.

## PHẦN 2: Câu hỏi trắc nghiệm (Multiple Choice)
**Câu 1:** Quy trình phần mềm (Software Process) là gì?
A. Là một ngôn ngữ lập trình.
B. Là một tập có cấu trúc các hoạt động cần thiết để phát triển một hệ thống phần mềm.
C. Là tài liệu hướng dẫn người dùng.
D. Là quá trình cài đặt phần mềm lên máy tính.
*Đáp án: B*

**Câu 2:** Hoạt động 'Đặc tả' (Specification) trong quy trình phần mềm nhằm mục đích gì?
A. Viết mã nguồn cho hệ thống.
B. Xác định các chức năng và các ràng buộc vận hành của hệ thống phần mềm.
C. Sửa các lỗi bảo mật.
D. Kiểm thử hệ thống.
*Đáp án: B*

**Câu 3:** Hoạt động 'Phát triển' (Development) trong quy trình phần mềm bao gồm những công việc chính nào?
A. Chỉ viết tài liệu.
B. Thiết kế (Design) và Cài đặt/Lập trình (Implementation).
C. Bảo trì phần mềm.
D. Hỏi ý kiến khách hàng.
*Đáp án: B*

**Câu 4:** Hoạt động 'Thẩm định' (Validation) trong quy trình phần mềm đảm bảo điều gì?
A. Đảm bảo mã nguồn không có dòng trống.
B. Đảm bảo phần mềm thỏa mãn những yêu cầu mà khách hàng đã đặt ra.
C. Đảm bảo phần mềm được bán với giá cao nhất.
D. Đảm bảo tốc độ mạng luôn ổn định.
*Đáp án: B*

**Câu 5:** Hoạt động 'Cải tiến' (Evolution/Maintenance) trong quy trình phần mềm có ý nghĩa gì?
A. Thay đổi ngôn ngữ lập trình liên tục.
B. Sửa đổi, nâng cấp phần mềm để đáp ứng các yêu cầu thay đổi của khách hàng và thị trường.
C. Xóa toàn bộ dữ liệu cũ.
D. Làm lại giao diện mỗi tháng.
*Đáp án: B*

**Câu 6:** Mô hình 'Xây và sửa' (Build and Fix) có đặc điểm nổi bật nào?
A. Có tài liệu đặc tả và thiết kế vô cùng chi tiết.
B. Bỏ qua khâu đặc tả và thiết kế, lập trình viên trực tiếp viết code rồi sửa lỗi cho đến khi xong.
C. Chia dự án thành nhiều vòng lặp nhỏ.
D. Kiểm soát rủi ro rất tốt.
*Đáp án: B*

**Câu 7:** Nhược điểm lớn nhất của mô hình 'Xây và sửa' (Build and Fix) là gì?
A. Chi phí thiết kế quá đắt đỏ.
B. Mã nguồn lộn xộn, thiếu cấu trúc, không có tài liệu dẫn đến chi phí bảo trì khổng lồ (bảo trì là ác mộng).
C. Phát triển quá chậm.
D. Không thể chạy trên hệ điều hành Windows.
*Đáp án: B*

**Câu 8:** Mô hình phát triển phần mềm nào được xem là cổ điển và tuần tự nhất?
A. Mô hình Xoắn ốc (Spiral).
B. Mô hình Bản mẫu nhanh (Rapid Prototyping).
C. Mô hình Thác nước (Waterfall).
D. Mô hình RUP.
*Đáp án: C*

**Câu 9:** Trong mô hình Thác nước, khi nào thì pha tiếp theo mới được bắt đầu?
A. Có thể bắt đầu bất cứ lúc nào tùy thích.
B. Chỉ khi pha hiện tại đã hoàn thành và tài liệu của nó được nghiệm thu.
C. Khi khách hàng yêu cầu.
D. Khi lập trình viên thấy chán pha hiện tại.
*Đáp án: B*

**Câu 10:** Sản phẩm đầu ra của mỗi pha trong mô hình Thác nước chủ yếu là gì?
A. Chỉ là các đoạn code rời rạc.
B. Các tài liệu (documents) đã được phê duyệt.
C. Các bản dùng thử (beta).
D. Khách hàng không nhận được gì.
*Đáp án: B*

**Câu 11:** Điểm yếu cốt lõi của mô hình Thác nước trong thực tiễn là gì?
A. Khó viết code.
B. Rất thiếu linh hoạt, khó thích ứng với sự thay đổi yêu cầu của khách hàng khi dự án đang diễn ra.
C. Mô hình quá phức tạp để hiểu.
D. Đòi hỏi quá ít tài liệu.
*Đáp án: B*

**Câu 12:** Mô hình Thác nước phù hợp nhất với loại dự án nào?
A. Dự án startup làm sản phẩm mới hoàn toàn.
B. Dự án có yêu cầu cực kỳ rõ ràng, ổn định, hiểu thấu đáo từ đầu và ít có khả năng thay đổi.
C. Dự án có công nghệ liên tục thay đổi.
D. Dự án mã nguồn mở.
*Đáp án: B*

**Câu 13:** Trong mô hình Bản mẫu nhanh (Rapid Prototyping), mục đích chính của việc tạo ra 'Bản mẫu' (Prototype) là gì?
A. Để bán luôn cho khách hàng.
B. Để giúp khách hàng hình dung trực quan về sản phẩm, từ đó làm rõ và xác nhận chính xác các yêu cầu.
C. Để kiểm tra tốc độ mạng.
D. Để thay thế hoàn toàn tài liệu thiết kế.
*Đáp án: B*

**Câu 14:** Điều gì thường xảy ra với 'Bản mẫu' (Prototype) trong mô hình Bản mẫu nhanh sau khi khách hàng đã chốt yêu cầu?
A. Nó được nâng cấp trực tiếp thành sản phẩm cuối.
B. Nó thường bị loại bỏ (vứt đi) và hệ thống thực sự được xây dựng lại từ đầu dựa trên yêu cầu đã làm rõ.
C. Nó được dùng làm hệ điều hành.
D. Khách hàng phải trả thêm tiền để giữ lại.
*Đáp án: B*

**Câu 15:** Mô hình Bản mẫu nhanh giúp giảm thiểu loại rủi ro nào lớn nhất?
A. Rủi ro phần cứng hỏng hóc.
B. Rủi ro do xác định sai hoặc thiếu yêu cầu của khách hàng.
C. Rủi ro lập trình viên nghỉ việc.
D. Rủi ro bảo mật mạng.
*Đáp án: B*

**Câu 16:** Mô hình vòng đời Tiến hóa (Evolutionary model) hoạt động theo nguyên tắc nào?
A. Làm một lèo từ đầu đến cuối không quay lại.
B. Xây dựng một phiên bản khởi đầu, sau đó đưa ra cho người dùng đánh giá và liên tục làm mịn/tinh chỉnh qua nhiều vòng lặp phản hồi.
C. Chỉ viết code mà không cần hỏi người dùng.
D. Xây dựng cấu trúc dữ liệu trước.
*Đáp án: B*

**Câu 17:** Sự khác biệt cơ bản giữa mô hình Tăng trưởng (Incremental) và mô hình Lặp (Iterative) là gì?
A. Không có sự khác biệt.
B. Tăng trưởng là chia nhỏ hệ thống và giao từng phần (thêm chức năng mới); Lặp là làm đi làm lại toàn bộ hệ thống để làm mịn, hoàn thiện hơn.
C. Tăng trưởng là làm mịn code, Lặp là thêm chức năng mới.
D. Cả hai đều giống mô hình Thác nước.
*Đáp án: B*

**Câu 18:** Mô hình Tăng trưởng (Incremental) mang lại lợi ích gì cho khách hàng?
A. Khách hàng phải đợi rất lâu mới có sản phẩm.
B. Khách hàng nhận được các chức năng cốt lõi sớm nhất, có thể đưa vào sử dụng ngay mà không cần đợi toàn bộ hệ thống hoàn thành.
C. Khách hàng không cần tham gia nghiệm thu.
D. Giá thành tăng gấp 10 lần.
*Đáp án: B*

**Câu 19:** Mô hình nào đặt trọng tâm lớn nhất vào việc 'Phân tích và Quản lý rủi ro' ở mỗi vòng lặp?
A. Thác nước.
B. Xây và sửa.
C. Bản mẫu nhanh.
D. Xoắn ốc (Spiral).
*Đáp án: D*

**Câu 20:** Ai là người đã đề xuất Mô hình Xoắn ốc (Spiral Model)?
A. Ivar Jacobson.
B. Barry Boehm.
C. Alan Turing.
D. Bill Gates.
*Đáp án: B*

**Câu 21:** Trong mô hình Xoắn ốc, mỗi vòng xoắn (loop) đại diện cho điều gì?
A. Một ngày làm việc.
B. Một pha (phase) hoặc một vòng lặp của quá trình phát triển (ví dụ: vòng 1 làm feasibility, vòng 2 làm requirements...).
C. Sự thay đổi nhân sự.
D. Một lỗi (bug) được tìm thấy.
*Đáp án: B*

**Câu 22:** Nếu tại pha 'Đánh giá rủi ro' của mô hình Xoắn ốc phát hiện rủi ro quá lớn không thể khắc phục, điều gì có thể xảy ra?
A. Lập trình viên phải làm thêm giờ.
B. Dự án có thể bị quyết định hủy bỏ (Go/No-go decision) để tránh thiệt hại lớn hơn.
C. Tiếp tục làm ngơ rủi ro đó.
D. Bắt buộc chuyển sang mô hình Thác nước.
*Đáp án: B*

**Câu 23:** Mô hình Xoắn ốc thường phù hợp nhất với loại dự án nào?
A. Dự án siêu nhỏ làm trong 1 tuần.
B. Dự án có quy mô lớn, phức tạp, rủi ro cao và thường là hệ thống nội bộ (in-house).
C. Bài tập lớn của sinh viên.
D. Website bán hàng cá nhân.
*Đáp án: B*

**Câu 24:** Hạn chế của mô hình Xoắn ốc là gì?
A. Không quản lý được rủi ro.
B. Đòi hỏi chuyên gia đánh giá rủi ro giỏi, mô hình phức tạp và tốn kém để quản lý.
C. Khách hàng không được tham gia.
D. Code sinh ra chạy chậm.
*Đáp án: B*

**Câu 25:** RUP (Rational Unified Process) là quy trình phát triển phần mềm có đặc điểm cốt lõi nào?
A. Làm theo mô hình Thác nước tuyệt đối.
B. Lặp và tăng trưởng, Hướng Use-case, Lấy kiến trúc làm trung tâm.
C. Chỉ tập trung vào code, không có tài liệu.
D. Chỉ phù hợp cho hệ thống mã nguồn mở.
*Đáp án: B*

**Câu 26:** Ngôn ngữ mô hình hóa nào gắn liền với quy trình RUP?
A. HTML.
B. UML (Unified Modeling Language).
C. C++.
D. SQL.
*Đáp án: B*

**Câu 27:** Vòng đời của quy trình RUP được chia làm 4 pha chính, đó là:
A. Phân tích, Thiết kế, Code, Test.
B. Khởi đầu (Inception), Khảo sát tỉ mỉ (Elaboration), Xây dựng (Construction), Chuyển giao (Transition).
C. Requirement, Design, Implementation, Maintenance.
D. Lập kế hoạch, Thực thi, Đánh giá, Đóng dự án.
*Đáp án: B*

**Câu 28:** Mục tiêu chính của pha 'Khởi đầu' (Inception) trong RUP là gì?
A. Lập trình xong 50% dự án.
B. Xác định phạm vi dự án, xây dựng Business Case, làm rõ các Use-case cốt lõi và đánh giá rủi ro ban đầu.
C. Viết tài liệu hướng dẫn sử dụng.
D. Giao sản phẩm cho khách hàng.
*Đáp án: B*

**Câu 29:** Pha 'Khảo sát tỉ mỉ' (Elaboration) trong RUP tập trung giải quyết vấn đề gì quan trọng nhất?
A. Xây dựng kiến trúc nền tảng (Architecture) ổn định và làm rõ hầu hết các Use-case để loại bỏ rủi ro kỹ thuật lớn.
B. Lập trình giao diện (UI) thật đẹp.
C. Tìm kiếm khách hàng mới.
D. Viết Unit Test cho toàn bộ hệ thống.
*Đáp án: A*

**Câu 30:** Trong RUP, pha 'Xây dựng' (Construction) thực hiện công việc gì chủ yếu?
A. Bắt đầu đi tìm hiểu yêu cầu khách hàng.
B. Tập trung phát triển, lập trình (coding) và tích hợp các thành phần còn lại để tạo ra sản phẩm hoàn chỉnh (đạt bản Beta).
C. Thay đổi toàn bộ kiến trúc hệ thống.
D. Đánh giá tính khả thi kinh doanh.
*Đáp án: B*

**Câu 31:** Mục tiêu của pha 'Chuyển giao' (Transition) trong RUP là gì?
A. Bỏ dự án đi làm dự án khác.
B. Kiểm thử chấp nhận, sửa các lỗi cuối cùng, huấn luyện người dùng và đưa sản phẩm vào môi trường vận hành thực tế.
C. Vẽ biểu đồ Use-case.
D. Chọn ngôn ngữ lập trình.
*Đáp án: B*

**Câu 32:** Trong RUP, các 'Luồng công việc' (Workflows) như Phân tích, Thiết kế, Kiểm thử diễn ra như thế nào?
A. Chỉ diễn ra 1 lần duy nhất theo thứ tự.
B. Diễn ra xuyên suốt tất cả 4 pha, nhưng mức độ tập trung (effort) của mỗi luồng sẽ khác nhau tùy thuộc vào pha đó.
C. Chỉ diễn ra ở pha Construction.
D. Không cần thiết thực hiện.
*Đáp án: B*

**Câu 33:** Dự án mã nguồn mở (Open-source) thường bắt đầu như thế nào?
A. Có một bản hợp đồng thiết kế 1000 trang.
B. Bắt đầu từ một cá nhân hoặc nhóm nhỏ xây dựng một phiên bản cơ bản (prototype) rồi đưa lên mạng để cộng đồng đóng góp.
C. Phải có công ty lớn tài trợ mới làm.
D. Viết tài liệu trước khi viết code.
*Đáp án: B*

**Câu 34:** Ai là người bảo trì và phát triển phần mềm mã nguồn mở (như Linux, Apache)?
A. Chỉ có tác giả ban đầu.
B. Cộng đồng các lập trình viên tình nguyện (co-developers / maintainers) trên toàn thế giới.
C. Khách hàng trả tiền mua phần mềm.
D. Microsoft.
*Đáp án: B*

**Câu 35:** Sự thành công của phần mềm mã nguồn mở dựa chủ yếu vào điều gì?
A. Tài liệu thiết kế cực kỳ nghiêm ngặt.
B. Sự tham gia đóng góp, review code và tìm lỗi của cộng đồng rộng lớn ('Với đủ con mắt, mọi lỗi đều sẽ nổi lên' - Linus's Law).
C. Kinh phí quảng cáo khổng lồ.
D. Mã nguồn được giữ bí mật tuyệt đối.
*Đáp án: B*

**Câu 36:** Tại sao 'Lập kế hoạch' (Planning) lại là một hoạt động lặp đi lặp lại trong mô hình lặp (Iterative)?
A. Vì người quản lý rảnh rỗi.
B. Vì sau mỗi vòng lặp, chúng ta có thêm thông tin thực tế, hiểu rõ rủi ro hơn nên kế hoạch cần được điều chỉnh (làm mịn) cho vòng tiếp theo.
C. Vì lập trình viên luôn làm sai kế hoạch.
D. Vì kế hoạch không quan trọng.
*Đáp án: B*

**Câu 37:** Một trong những rủi ro lớn nhất nếu không áp dụng bất kỳ mô hình vòng đời phần mềm nào (chỉ Code and Fix) là:
A. Hệ thống sẽ không thể mở rộng, bảo trì vô cùng khó khăn, dễ vượt ngân sách và thời gian, khó kiểm soát chất lượng.
B. Lập trình viên sẽ bị đuổi việc ngay ngày đầu.
C. Máy tính sẽ bị hỏng ổ cứng.
D. Code sẽ chạy quá nhanh gây lỗi.
*Đáp án: A*

**Câu 38:** Điểm mạnh của việc sử dụng 'Use-case' làm trung tâm trong RUP là gì?
A. Giúp vẽ hình đẹp hơn.
B. Đảm bảo toàn bộ quá trình phân tích, thiết kế, lập trình và kiểm thử đều bám sát và đáp ứng đúng các chức năng mà người dùng (Actor) mong muốn.
C. Giúp mã hóa CSDL nhanh hơn.
D. Thay thế ngôn ngữ lập trình.
*Đáp án: B*

**Câu 39:** Tại sao trong bài toán Winburg Mini (ví dụ thực tế), mô hình Thác nước nguyên bản không hoạt động tốt?
A. Vì hệ thống quá nhỏ.
B. Vì yêu cầu của khách hàng thay đổi và lập trình viên có thể mắc lỗi cần quay lại sửa, điều mà Thác nước nghiêm ngặt không hỗ trợ tốt.
C. Vì ngân sách quá lớn.
D. Vì dùng ngôn ngữ C++.
*Đáp án: B*

**Câu 40:** Trong RUP, 'Đường cơ sở' (Baseline) mang ý nghĩa gì?
A. Là dòng cuối cùng của mã nguồn.
B. Là một trạng thái/phiên bản của hệ thống đã được nghiệm thu tại một thời điểm, dùng làm cơ sở cho các bước phát triển hoặc thay đổi tiếp theo.
C. Là đường mạng kết nối nội bộ.
D. Là giới hạn tiền lương của dự án.
*Đáp án: B*

**Câu 41:** Hoạt động 'Kiểm thử' trong các mô hình linh hoạt (Iterative/Agile) diễn ra khi nào so với mô hình Thác nước?
A. Chỉ diễn ra ở cuối dự án.
B. Kiểm thử được thực hiện liên tục và sớm ngay từ các vòng lặp đầu tiên, thay vì đợi đến cuối như Thác nước.
C. Không cần kiểm thử.
D. Chỉ kiểm thử trên giấy.
*Đáp án: B*

**Câu 42:** Sản phẩm chuyển giao (Deliverables) ở cuối pha Khởi đầu (Inception) của RUP KHÔNG bao gồm:
A. Danh sách các Use-case.
B. Kế hoạch rủi ro ban đầu.
C. Mã nguồn hoàn chỉnh 100% không còn lỗi.
D. Mô hình nghiệp vụ sơ bộ.
*Đáp án: C*

**Câu 43:** Theo RUP, 'Kiến trúc' (Architecture) của phần mềm được chốt vững chắc nhất vào cuối pha nào?
A. Khởi đầu (Inception).
B. Khảo sát tỉ mỉ (Elaboration).
C. Xây dựng (Construction).
D. Chuyển giao (Transition).
*Đáp án: B*

**Câu 44:** Mô hình phát triển phần mềm nào thường cung cấp 'Bản phát hành Beta' (Beta release)?
A. Chỉ có mô hình Xây và sửa.
B. Mô hình RUP (Cuối pha Construction) hoặc các mô hình Lặp/Tiến hóa.
C. Mô hình Thác nước.
D. Không mô hình nào cả.
*Đáp án: B*

**Câu 45:** Vì sao khách hàng thường không thích mô hình Thác nước?
A. Vì họ phải đọc quá ít tài liệu.
B. Vì họ phải đợi đến cuối dự án (rất lâu) mới nhìn thấy và dùng thử được sản phẩm, lúc đó nếu sai yêu cầu thì sửa rất tốn kém.
C. Vì họ phải tham gia lập trình.
D. Vì mô hình này không có Tester.
*Đáp án: B*

**Câu 46:** Mô hình Lặp và Tăng trưởng giải quyết rủi ro hệ thống bị 'Big Bang' (Tích hợp và sụp đổ ở phút cuối) như thế nào?
A. Bằng cách không tích hợp hệ thống bao giờ.
B. Bằng cách tích hợp liên tục và thường xuyên qua từng vòng lặp nhỏ, phát hiện lỗi giao tiếp giữa các mô-đun từ rất sớm.
C. Bằng cách dùng máy chủ siêu mạnh.
D. Bằng cách thay đổi khách hàng.
*Đáp án: B*

**Câu 47:** UML (Unified Modeling Language) cung cấp điều gì cho kỹ sư phần mềm?
A. Khả năng biên dịch ra file .exe.
B. Một bộ ký hiệu đồ họa trực quan (các biểu đồ) để mô hình hóa, thiết kế và giao tiếp chuẩn xác về hệ thống hướng đối tượng.
C. Giao diện người dùng cho Web.
D. Một hệ quản trị CSDL quan hệ.
*Đáp án: B*

**Câu 48:** Điều gì đánh dấu sự kết thúc của pha Chuyển giao (Transition) trong RUP?
A. Sản phẩm được cài đặt, người dùng chấp nhận hệ thống, tài liệu hoàn chỉnh và sẵn sàng đi vào vận hành thực tế (Bảo trì).
B. Bắt đầu viết dòng code đầu tiên.
C. Chốt kiến trúc hệ thống.
D. Bắt đầu phân tích yêu cầu.
*Đáp án: A*

**Câu 49:** Sự kết hợp giữa Mô hình Bản mẫu nhanh và Mô hình Thác nước dẫn đến điều gì?
A. Sự sụp đổ của dự án.
B. Người ta dùng Bản mẫu nhanh để làm rõ yêu cầu, sau khi chốt yêu cầu thì áp dụng Thác nước để thiết kế và cài đặt hệ thống một cách có kỷ luật.
C. Làm dự án chậm đi gấp 10 lần.
D. Tạo ra mô hình Xây và sửa.
*Đáp án: B*

**Câu 50:** Đâu là điểm yếu của Mô hình phần mềm mã nguồn mở (Open-source)?
A. Chất lượng code kém.
B. Thường thiếu các tài liệu đặc tả và thiết kế bài bản từ đầu, có thể khó để tích hợp vào các hệ thống thương mại cần độ tin cậy và SLA khắt khe.
C. Giá thành quá cao.
D. Không có ai kiểm tra lỗi.
*Đáp án: B*

**Câu 51:** Trong mô hình Thác nước, pha Phân tích Yêu cầu tạo ra sản phẩm gì?
A. Mã nguồn C++.
B. Tài liệu đặc tả yêu cầu (SRS) được khách hàng phê duyệt.
C. Một bản mẫu (prototype) chạy được.
D. Tài liệu hướng dẫn sử dụng (User Manual).
*Đáp án: B*

**Câu 52:** Hoạt động nào thường KHÔNG xuất hiện ở các mô hình vòng đời linh hoạt (Agile/Iterative) nhưng lại bắt buộc trong Thác nước?
A. Lập trình.
B. Hoàn thiện toàn bộ tài liệu đặc tả 100% trước khi được phép viết một dòng code nào.
C. Kiểm thử.
D. Giao tiếp khách hàng.
*Đáp án: B*

**Câu 53:** Một trong những nguyên nhân khiến mô hình Thác nước thất bại là do 'Hiệu ứng đóng băng' (Freezing). Nghĩa là gì?
A. Máy tính bị treo.
B. Cố gắng đóng băng các yêu cầu (không cho thay đổi) quá sớm, trong khi nhu cầu thực tế luôn thay đổi.
C. Nhân sự bị cấm nghỉ phép.
D. Máy chủ bị quá tải.
*Đáp án: B*

**Câu 54:** Mô hình 'Xây và Sửa' (Build and Fix) được sử dụng chủ yếu ở đâu?
A. Các dự án làm phần mềm điều khiển hàng không.
B. Các dự án ngân hàng.
C. Thường được dùng một cách tự phát bởi sinh viên làm bài tập nhỏ hoặc các hacker làm tool dùng một lần.
D. Dự án của chính phủ.
*Đáp án: C*

**Câu 55:** Tại sao mô hình Bản mẫu nhanh (Rapid Prototyping) lại được gọi là 'Bản mẫu dùng một lần' (Throwaway Prototyping)?
A. Vì khách hàng sẽ vứt nó đi khi không thích.
B. Vì bản mẫu thường viết bằng mã nguồn tạm bợ, thiếu kiến trúc, chỉ nhằm mục đích làm rõ yêu cầu, sau đó sẽ bị bỏ đi để xây dựng lại hệ thống thật một cách chuẩn chỉ.
C. Vì nó bị lỗi ngay sau khi dùng.
D. Vì phần cứng không hỗ trợ.
*Đáp án: B*

**Câu 56:** Đâu KHÔNG phải là một lợi thế của mô hình Bản mẫu nhanh?
A. Giúp khách hàng hình dung rõ sản phẩm.
B. Làm rõ các yêu cầu mập mờ.
C. Sản phẩm cuối cùng (bản mẫu) luôn có kiến trúc và mã nguồn cực kỳ tối ưu, sạch sẽ để bảo trì.
D. Phát hiện sớm sự hiểu lầm giữa kỹ sư và khách hàng.
*Đáp án: C*

**Câu 57:** Mô hình Tiến hóa (Evolutionary Model) có rủi ro gì lớn nhất nếu không quản lý tốt?
A. Quá nhiều tài liệu.
B. Hệ thống có thể phát triển lộn xộn, cấu trúc bị phá vỡ qua nhiều vòng lặp (Spaghetti code) nếu không được thiết kế kiến trúc tốt từ đầu.
C. Khách hàng không bao giờ tham gia.
D. Thời gian hoàn thành quá ngắn.
*Đáp án: B*

**Câu 58:** Trong mô hình Xoắn ốc (Spiral), bán kính (khoảng cách từ tâm) của vòng xoắn tượng trưng cho điều gì?
A. Thời gian thực hiện.
B. Số lượng lập trình viên.
C. Chi phí tích lũy của dự án.
D. Độ khó của ngôn ngữ lập trình.
*Đáp án: C*

**Câu 59:** Mô hình Xoắn ốc là sự kết hợp của hai yếu tố nào?
A. Mô hình Xây và sửa + Lập trình hướng đối tượng.
B. Các tính năng của mô hình Bản mẫu (prototyping) để giảm rủi ro + Các bước kiểm soát có hệ thống của mô hình Thác nước.
C. Hệ chuyên gia + Mô hình thác nước.
D. Mã nguồn mở + Bản mẫu.
*Đáp án: B*

**Câu 60:** Một trong các công việc tại góc phần tư thứ nhất (Xác định mục tiêu, giải pháp) của mô hình Xoắn ốc là gì?
A. Viết code.
B. Lập kế hoạch bảo trì.
C. Thu thập yêu cầu, xác định mục tiêu của vòng lặp và tìm các giải pháp khả thi.
D. Kiểm thử hệ thống.
*Đáp án: C*

**Câu 61:** Góc phần tư thứ hai trong mô hình Xoắn ốc thực hiện công việc cốt lõi nào?
A. Thiết kế CSDL.
B. Đánh giá các giải pháp, nhận diện và giải quyết các rủi ro (thường bằng cách tạo bản mẫu).
C. Giao sản phẩm cho khách hàng.
D. Viết tài liệu hướng dẫn.
*Đáp án: B*

**Câu 62:** Nếu dự án phần mềm có rủi ro rất thấp, đã hiểu rõ công nghệ và yêu cầu, có nên dùng mô hình Xoắn ốc không?
A. Chắc chắn có, vì nó luôn tốt nhất.
B. Không nên, vì mô hình Xoắn ốc có chi phí quản lý rủi ro cao, phức tạp, không cần thiết cho dự án đơn giản. Nên dùng Thác nước.
C. Có, để tăng lương cho quản lý.
D. Không, vì không có chuyên gia.
*Đáp án: B*

**Câu 63:** Tính chất 'Hướng Use-case' (Use-case driven) trong RUP có nghĩa là:
A. Mọi mã nguồn đều viết bằng Use-case.
B. Các chức năng (Use-cases) do khách hàng yêu cầu là luồng chỉ đạo (sợi chỉ đỏ) dẫn dắt quá trình phân tích, thiết kế, triển khai và kiểm thử hệ thống.
C. Chỉ vẽ biểu đồ mà không code.
D. Sử dụng công cụ CASE đặc biệt.
*Đáp án: B*

**Câu 64:** Tính chất 'Lấy kiến trúc làm trung tâm' (Architecture-centric) trong RUP nhằm mục đích gì?
A. Tạo ra một kiến trúc hệ thống bền vững, làm bộ xương để gắn kết các Use-case và các thành phần lại với nhau, đảm bảo hệ thống dễ bảo trì, mở rộng.
B. Tập trung vẽ giao diện đồ họa đẹp.
C. Viết code ngắn nhất có thể.
D. Bỏ qua khâu kiểm thử.
*Đáp án: A*

**Câu 65:** Luồng công việc (Workflow) 'Mô hình hóa nghiệp vụ' (Business Modeling) trong RUP làm nhiệm vụ gì?
A. Tính toán chi phí tài chính dự án.
B. Mô hình hóa và hiểu rõ quy trình kinh doanh, ngữ cảnh tổ chức của khách hàng trước khi xây dựng phần mềm cho họ.
C. Mô hình hóa cơ sở dữ liệu vật lý.
D. Ký hợp đồng với khách hàng.
*Đáp án: B*

**Câu 66:** Trong RUP, sự lặp (Iteration) xảy ra ở đâu?
A. Chỉ ở pha Construction.
B. Bên trong tất cả 4 pha (Inception, Elaboration, Construction, Transition), mỗi pha có thể gồm một hoặc nhiều vòng lặp nhỏ.
C. Chỉ khi khách hàng yêu cầu.
D. Chỉ xảy ra khi có lỗi phần cứng.
*Đáp án: B*

**Câu 67:** Kết quả cuối cùng của một vòng lặp (Iteration) trong RUP thường là gì?
A. Một phiên bản tài liệu mới.
B. Một phiên bản thực thi được của phần mềm (Executable release), ngày càng tiệm cận với sản phẩm cuối.
C. Một bản vẽ kiến trúc.
D. Một bản báo cáo rủi ro.
*Đáp án: B*

**Câu 68:** Trong pha Khảo sát tỉ mỉ (Elaboration) của RUP, rủi ro lớn nhất thường được giải quyết là gì?
A. Rủi ro thiếu lập trình viên.
B. Rủi ro kiến trúc/kỹ thuật (Technical risks) - đảm bảo công nghệ lựa chọn có thể thực thi được các yêu cầu khắt khe (Hiệu năng, bảo mật...).
C. Rủi ro thị trường.
D. Rủi ro trễ tiến độ nộp báo cáo.
*Đáp án: B*

**Câu 69:** Nếu pha Inception (Khởi đầu) của RUP kết luận rằng dự án không khả thi về mặt tài chính hoặc công nghệ, quản lý dự án sẽ quyết định:
A. Tiếp tục làm để lấy kinh nghiệm.
B. Dừng hoặc hủy bỏ dự án (No-Go).
C. Bỏ qua pha Elaboration và vào pha Construction luôn.
D. Tự bỏ tiền túi ra làm.
*Đáp án: B*

**Câu 70:** Trong quy trình phần mềm, 'Milestone' (Cột mốc) đóng vai trò gì?
A. Là điểm bắt đầu viết code.
B. Là các điểm kiểm tra quan trọng cuối mỗi pha/vòng lặp để đánh giá xem dự án có đạt mục tiêu đề ra và có tiếp tục được hay không.
C. Là tên của một ngôn ngữ lập trình.
D. Là hạn chót để nộp tiền.
*Đáp án: B*

**Câu 71:** Một 'Quy trình phần mềm' (Software Process) chuẩn mực sẽ giúp giải quyết vấn đề gì của 'Khủng hoảng phần mềm'?
A. Giảm giá phần cứng máy tính.
B. Biến việc phát triển phần mềm từ nghệ thuật cá nhân thành một hoạt động kỹ thuật có kỷ luật, lặp lại được, dễ dự đoán và kiểm soát chất lượng.
C. Làm phần mềm chạy tự động không cần người.
D. Thay thế lập trình viên bằng AI.
*Đáp án: B*

**Câu 72:** Phương pháp luận 'Agile' (Linh hoạt) khác biệt với Thác nước ở điểm nào?
A. Agile làm dự án kéo dài hơn.
B. Agile phản hồi nhanh với thay đổi, chia dự án thành các đợt phát hành ngắn (sprint/iteration) và đề cao giao tiếp trực tiếp thay vì tài liệu nặng nề.
C. Agile bắt buộc dùng ngôn ngữ C++.
D. Agile không có khâu kiểm thử.
*Đáp án: B*

**Câu 73:** Mô hình Lặp (Iterative) cho phép sửa lỗi thiết kế ở các vòng lặp sau. Điều này mang lại lợi ích gì?
A. Giúp lập trình viên lười biếng hơn.
B. Tránh hiệu ứng 'dồn ứ lỗi' đến cuối dự án, giảm chi phí sửa chữa rủi ro kỹ thuật vì lỗi thiết kế được phát hiện sớm.
C. Làm tăng thời gian rảnh rỗi.
D. Tăng số lượng tài liệu cần viết.
*Đáp án: B*

**Câu 74:** Khái niệm 'Chuyển giao tăng trưởng' (Incremental Delivery) là gì?
A. Chỉ chuyển giao tài liệu hướng dẫn trước.
B. Sản phẩm được giao cho khách hàng theo từng phần (module/chức năng), khách hàng dùng phần này trong khi phần khác đang được xây dựng.
C. Giao hàng bằng nhiều chuyến xe.
D. Phần mềm tự nâng cấp dung lượng.
*Đáp án: B*

**Câu 75:** Mô hình 'Bản mẫu tiến hóa' (Evolutionary Prototyping) khác 'Bản mẫu dùng một lần' ở điểm nào?
A. Bản mẫu tiến hóa được làm bằng giấy.
B. Bản mẫu dùng một lần bị bỏ đi sau khi chốt yêu cầu; Bản mẫu tiến hóa được xây dựng vững chắc dần và trở thành sản phẩm cuối cùng.
C. Không khác gì.
D. Bản mẫu tiến hóa chỉ dùng cho hệ thống siêu nhỏ.
*Đáp án: B*

**Câu 76:** Đặc trưng của quy trình phát triển Mã nguồn mở là sự đóng góp 'phi tập trung' (Decentralized). Nghĩa là gì?
A. Lập trình viên làm việc cùng một văn phòng.
B. Có hàng ngàn lập trình viên độc lập trên khắp thế giới tự nguyện đóng góp mã, tìm lỗi, và sửa lỗi thông qua Internet.
C. Chỉ có 1 người duy nhất nắm giữ mã nguồn.
D. Phải tập trung tại một công ty để làm.
*Đáp án: B*

**Câu 77:** Trong mã nguồn mở, vai trò của 'Maintainer' (Người bảo trì/Quản trị viên lõi) là gì?
A. Nhận lương từ mọi người dùng.
B. Kiểm duyệt, xem xét (review) và quyết định có tích hợp (merge) đoạn code do cộng đồng đóng góp vào phiên bản chính thức của phần mềm hay không.
C. Xóa mã nguồn của người khác.
D. Cài đặt phần mềm cho khách hàng.
*Đáp án: B*

**Câu 78:** Lý do chính khiến mã nguồn mở ít có tài liệu Thiết kế (Design documents) hình thức lúc ban đầu là:
A. Vì người làm mã nguồn mở không biết viết tài liệu.
B. Vì nó thường bắt đầu từ ý tưởng/bản nháp của một cá nhân, phát triển dần qua mã nguồn (Code-driven) thay vì quy trình Thác nước tài liệu hóa.
C. Vì Internet không cho phép lưu tài liệu.
D. Vì việc viết tài liệu bị cấm.
*Đáp án: B*

**Câu 79:** Hoạt động 'Kiểm thử tích hợp' (Integration Testing) trong quy trình phần mềm nhằm mục đích gì?
A. Kiểm tra từng hàm đơn lẻ.
B. Phát hiện lỗi giao tiếp, truyền dữ liệu hoặc xung đột khi ghép nối các mô-đun/thành phần hệ thống lại với nhau.
C. Kiểm tra xem máy tính có bị sập nguồn không.
D. Kiểm tra giao diện màu sắc.
*Đáp án: B*

**Câu 80:** Vì sao khách hàng tham gia tích cực (Customer Involvement) lại rất quan trọng trong các mô hình linh hoạt/lặp?
A. Để khách hàng code thay lập trình viên.
B. Họ dùng thử bản phát hành sớm, đưa ra phản hồi chính xác kịp thời, giúp định hướng sản phẩm bám sát đúng nhu cầu thực tế.
C. Để khách hàng thanh toán nhanh hơn.
D. Để khách hàng viết tài liệu.
*Đáp án: B*

**Câu 81:** Trong RUP, 'Luồng công việc' (Workflow) Cài đặt/Thực thi (Implementation) làm nhiệm vụ gì?
A. Cài phần mềm cho khách.
B. Biên dịch thiết kế thành mã nguồn (coding), kiểm thử đơn vị, và tích hợp mã nguồn.
C. Vẽ biểu đồ UML.
D. Tính tiền dự án.
*Đáp án: B*

**Câu 82:** Mô hình phát triển nào dưới đây KHÔNG chia dự án thành nhiều vòng lặp?
A. RUP.
B. Xoắn ốc.
C. Agile.
D. Thác nước.
*Đáp án: D*

**Câu 83:** RUP sử dụng công cụ gì để xác định 'Ai làm việc gì, vào lúc nào và làm như thế nào'?
A. Bản vẽ tay.
B. Vai trò (Roles), Sản phẩm (Artifacts), và Hoạt động (Activities) trong các Luồng công việc (Workflows).
C. Sơ đồ tổ chức công ty.
D. Danh sách email.
*Đáp án: B*

**Câu 84:** Sự 'Gia tăng' (Increment) trong mô hình Tăng trưởng mang lại giá trị cốt lõi nào cho hệ thống?
A. Tăng kích thước ổ cứng.
B. Tăng thêm chức năng mới phục vụ một phần nghiệp vụ, có thể dùng độc lập được, giúp thu hồi vốn (ROI) sớm hơn.
C. Tăng số lượng lỗi.
D. Tăng độ khó của dự án.
*Đáp án: B*

**Câu 85:** Mô hình Thác nước thường được khuyến nghị cho hệ thống phần mềm nào sau đây?
A. Ứng dụng mạng xã hội.
B. Hệ thống điều khiển nhúng của máy bay hoặc y tế (Cần độ an toàn cực cao, quy trình kiểm định nghiêm ngặt 100% trước khi triển khai).
C. Website tin tức.
D. Ứng dụng game di động.
*Đáp án: B*

**Câu 86:** Trong mô hình Xoắn ốc, 'Bản mẫu' (Prototype) thường được tạo ra ở góc phần tư nào?
A. Xác định mục tiêu.
B. Đánh giá rủi ro và tìm giải pháp.
C. Phát triển và kiểm định.
D. Lập kế hoạch.
*Đáp án: B*

**Câu 87:** Khái niệm 'Bảo trì' (Maintenance) trong quy trình phần mềm truyền thống bắt đầu từ khi nào?
A. Ngay khi mới khởi động dự án.
B. Sau khi phần mềm đã hoàn thành, vượt qua kiểm thử chấp nhận và được chuyển giao cho người dùng cuối.
C. Lúc đang viết code.
D. Khi đang phân tích yêu cầu.
*Đáp án: B*

**Câu 88:** Mô hình RUP có một đặc tính là 'Định hướng rủi ro' (Risk-driven). Nghĩa là gì?
A. Luôn chọn công nghệ nguy hiểm nhất để dùng.
B. Xác định và ưu tiên giải quyết các rủi ro lớn nhất (kiến trúc, công nghệ) ngay từ các vòng lặp đầu tiên của dự án.
C. Bỏ qua mọi rủi ro.
D. Cố gắng giấu nhẹm rủi ro đi.
*Đáp án: B*

**Câu 89:** Theo định luật Conway (Conway's Law), kiến trúc của phần mềm thường phản ánh điều gì?
A. Giá tiền phần cứng.
B. Cấu trúc giao tiếp của tổ chức/nhóm phát triển ra nó.
C. Ngôn ngữ lập trình được sử dụng.
D. Tâm trạng của lập trình viên.
*Đáp án: B*

**Câu 90:** Việc quản lý 'Yêu cầu thay đổi' trong RUP được thực hiện thông qua luồng công việc nào?
A. Phân tích yêu cầu.
B. Quản lý cấu hình và thay đổi (Configuration & Change Management).
C. Triển khai.
D. Mô hình nghiệp vụ.
*Đáp án: B*

**Câu 91:** Một sản phẩm phần mềm (Software product) được chuyển giao (Deliverables) ở cuối mô hình Thác nước bao gồm những gì?
A. Chỉ là file cài đặt.
B. Mã nguồn, phần mềm chạy được, dữ liệu thiết lập, toàn bộ tài liệu (Requirement, Design, Test, User manual).
C. Máy tính chạy hệ thống đó.
D. Một tờ giấy chứng nhận.
*Đáp án: B*

**Câu 92:** Vì sao quy trình phần mềm lại cần sự 'Cải tiến' (Process Improvement)?
A. Để làm mọi việc chậm đi.
B. Để đánh giá lại cách làm việc, tìm ra các nguyên nhân gây lỗi, từ đó tối ưu hóa công cụ và quy trình để dự án sau làm tốt hơn, nhanh hơn.
C. Để tăng lương cho nhân viên.
D. Để xóa các file cũ.
*Đáp án: B*

**Câu 93:** Mô hình nào được coi là cơ sở lý thuyết gốc rễ cho hầu hết các chuẩn quy trình quản lý nhà nước về phần mềm (như DoD-STD-2167A)?
A. Mô hình Xây và sửa.
B. Mô hình Thác nước (Waterfall).
C. Mô hình Xoắn ốc.
D. Phát triển hướng test (TDD).
*Đáp án: B*

**Câu 94:** Trong RUP, pha nào thường chiếm nhiều thời gian và công sức viết mã nguồn (coding) nhất?
A. Inception.
B. Elaboration.
C. Construction (Xây dựng).
D. Transition.
*Đáp án: C*

**Câu 95:** Luồng công việc (Workflow) 'Kiểm thử' (Test) trong RUP có vai trò gì?
A. Chỉ kiểm tra phần cứng.
B. Xác minh sự tương tác của các đối tượng, kiểm tra tích hợp các chức năng xem có đáp ứng được mô hình Use-case đã vạch ra hay không.
C. Viết mã nguồn chính.
D. Thiết kế cơ sở dữ liệu.
*Đáp án: B*

**Câu 96:** Một trong những mục tiêu của pha 'Khảo sát tỉ mỉ' (Elaboration) là thiết lập một 'Đường cơ sở kiến trúc' (Architecture Baseline). Nó dùng để làm gì?
A. Là phiên bản bán cho khách hàng.
B. Là nền tảng kiến trúc vững chắc, có thể thực thi được một số Use-case lõi, đảm bảo rằng thiết kế tổng thể là khả thi và ổn định trước khi lập trình hàng loạt.
C. Là tài liệu Word duy nhất.
D. Để tính lương.
*Đáp án: B*

**Câu 97:** Điểm tương đồng giữa Mô hình Xoắn ốc và RUP là gì?
A. Đều không cần tài liệu.
B. Đều áp dụng cơ chế lặp (iterative) và quản lý rủi ro xuyên suốt quá trình phát triển.
C. Đều do Microsoft tạo ra.
D. Đều cấm giao tiếp với khách hàng.
*Đáp án: B*

**Câu 98:** Mô hình vòng đời nào KHÔNG khuyến khích việc thay đổi yêu cầu ở giai đoạn giữa dự án?
A. Mô hình Tăng trưởng.
B. Mô hình Lặp.
C. Mô hình Thác nước.
D. Mô hình Xoắn ốc.
*Đáp án: C*

**Câu 99:** Trong mô hình Lặp và Tăng trưởng, 'Phiên bản tăng trưởng' (Increment) sẽ được làm gì tiếp theo?
A. Bị xóa đi.
B. Được chuyển giao cho khách hàng hoặc tích hợp vào hệ thống hiện có để chạy kiểm thử tổng thể, làm cơ sở cho vòng lặp tiếp theo.
C. Gửi đi thi quốc tế.
D. Giấu đi không cho ai thấy.
*Đáp án: B*

**Câu 100:** Tại sao RUP lại được gọi là 'Quy trình hợp nhất' (Unified Process)?
A. Vì nó chỉ dùng 1 máy tính duy nhất.
B. Vì nó hợp nhất nhiều phương pháp luận hướng đối tượng tốt nhất (như của Booch, Rumbaugh, Jacobson) và gắn liền chặt chẽ với ngôn ngữ hợp nhất UML.
C. Vì nó thống nhất tiền lương của mọi người.
D. Vì nó hợp nhất với phần cứng.
*Đáp án: B*

**Câu 101:** Trong RUP, Use-case đóng vai trò dẫn dắt (Use-case driven). Vậy 'Use-case' là gì?
A. Là một hàm lập trình viết bằng Java.
B. Là một kịch bản mô tả chuỗi hành động mà hệ thống tương tác với một tác nhân (Actor) để đạt được một kết quả có giá trị.
C. Là một đoạn code kết nối cơ sở dữ liệu.
D. Là sơ đồ nối dây mạng.
*Đáp án: B*

**Câu 102:** Mô hình 'Sashimi' (Thác nước chồng lấn) là một biến thể của mô hình Thác nước. Nó có đặc điểm gì?
A. Cấm hoàn toàn việc viết tài liệu.
B. Cho phép các pha (Phân tích, Thiết kế, Code...) có sự gối đầu, chồng lấn lên nhau thay vì phải chờ pha trước kết thúc 100%.
C. Sử dụng cá sống để lập trình.
D. Chỉ có đúng 2 pha.
*Đáp án: B*

**Câu 103:** Lợi ích chính của mô hình Tăng trưởng (Incremental) đối với đội ngũ phát triển là gì?
A. Không bao giờ phải test code.
B. Có thể sử dụng những phần lõi đã hoàn thành làm nền tảng để phát triển, học hỏi kinh nghiệm, và tích hợp các phần mới dần dần mà không bị choáng ngợp.
C. Tăng số lượng tài liệu lên gấp 10 lần.
D. Giúp lập trình viên ngủ nhiều hơn.
*Đáp án: B*

**Câu 104:** Trong mô hình Xoắn ốc, 'Kiểm định' (Validation) ở mỗi vòng lặp đóng vai trò gì?
A. Chỉ là kiểm tra lỗi chính tả.
B. Đánh giá xem phần mềm phát triển trong vòng lặp hiện tại có giải quyết đúng mục tiêu và rủi ro đã đề ra hay không trước khi lập kế hoạch cho vòng tiếp theo.
C. Đếm số dòng code đã viết.
D. Chỉ chạy tự động bằng công cụ.
*Đáp án: B*

**Câu 105:** Sự khác biệt cốt lõi giữa RUP và Mô hình Thác nước là gì?
A. Thác nước dùng UML, RUP không dùng.
B. Thác nước là mô hình tuyến tính tuần tự; RUP là mô hình lặp và tăng trưởng qua 4 pha lớn với các luồng công việc chạy song song.
C. Thác nước phù hợp cho dự án nhỏ, RUP chỉ dùng cho phần cứng.
D. Không có sự khác biệt.
*Đáp án: B*

**Câu 106:** Vai trò 'Actor' (Tác nhân) trong phân tích Use-case (thuộc RUP) có thể là ai?
A. Chỉ là một con người thao tác máy tính.
B. Con người, một hệ thống phần mềm khác, hoặc một thiết bị phần cứng tương tác với hệ thống đang phát triển.
C. Người quản lý dự án nội bộ.
D. Công ty đối thủ.
*Đáp án: B*

**Câu 107:** Pha 'Construction' (Xây dựng) trong RUP kết thúc khi nào?
A. Khi vừa lấy xong yêu cầu.
B. Khi đã có một bản Beta của hệ thống đủ trưởng thành để chuyển giao cho người dùng cuối chạy thử nghiệm.
C. Khi hệ thống đã chạy được 10 năm.
D. Khi thiết kế xong kiến trúc.
*Đáp án: B*

**Câu 108:** Luồng công việc (Workflow) 'Phân tích' (Analysis) trong RUP có nhiệm vụ gì?
A. Biên dịch mã nguồn ra file chạy.
B. Biến các Use-case và yêu cầu thành một bản nháp kiến trúc logic (mô hình đối tượng sơ bộ) để hiểu rõ hệ thống phải làm gì.
C. Thỏa thuận giá tiền phần mềm.
D. Cấu hình máy chủ cài đặt.
*Đáp án: B*

**Câu 109:** Một 'Rủi ro kỹ thuật' (Technical Risk) thường gặp trong CNPM là:
A. Khách hàng thay đổi yêu cầu.
B. Việc sử dụng một framework/công nghệ quá mới, chưa được kiểm chứng, dẫn đến hệ thống bị sụp đổ hiệu năng.
C. Thiếu tiền trả lương.
D. Lập trình viên bị ốm.
*Đáp án: B*

**Câu 110:** Trong mô hình Xoắn ốc, góc phần tư thứ 4 (Lập kế hoạch) có nhiệm vụ gì?
A. Viết code chức năng.
B. Dựa trên kết quả đánh giá của góc phần tư thứ 3, quyết định có đi tiếp vòng lặp mới không và lập kế hoạch ngân sách, tiến độ cho vòng xoắn ốc tiếp theo.
C. Tìm lỗi giao diện.
D. Xóa bỏ các rủi ro.
*Đáp án: B*

**Câu 111:** Mô hình Lặp (Iterative) đặc biệt hữu ích khi:
A. Khách hàng đã cung cấp 1 bản yêu cầu dày 1000 trang không bao giờ đổi.
B. Yêu cầu ban đầu chỉ rõ ràng một phần, hệ thống lớn, cần nhiều vòng lặp để vừa làm vừa rút kinh nghiệm và tinh chỉnh thiết kế.
C. Làm phần mềm nhúng siêu nhỏ.
D. Dự án không có Tester.
*Đáp án: B*

**Câu 112:** Trong RUP, 'Artifact' (Sản phẩm công việc/Tác phẩm) là gì?
A. Một bức tranh nghệ thuật treo tường.
B. Bất kỳ sản phẩm nào được tạo ra, sửa đổi hoặc sử dụng trong quá trình phát triển (ví dụ: tài liệu Use-case, biểu đồ UML, mã nguồn, kế hoạch test).
C. Một phần cứng máy tính.
D. Một con bọ (bug).
*Đáp án: B*

**Câu 113:** Đâu là điểm yếu của quy trình RUP?
A. Không có tài liệu thiết kế.
B. Quá cồng kềnh, phức tạp, nhiều công cụ và quy tắc, cần một đội ngũ am hiểu UML tốt, không phù hợp cho các dự án nhỏ với chi phí hẹp.
C. Chỉ có thể dùng cho mã nguồn mở.
D. Phải code mọi thứ bằng Assembly.
*Đáp án: B*

**Câu 114:** Khái niệm 'Dự án con' (Mini-project) xuất hiện trong mô hình nào?
A. Thác nước.
B. Mô hình Lặp và Tăng trưởng, nơi mỗi vòng lặp được coi như một dự án con hoàn chỉnh chứa đủ các pha.
C. Xây và Sửa.
D. Bản mẫu dùng 1 lần.
*Đáp án: B*

**Câu 115:** Một trong những lợi ích lớn của Mã nguồn mở là sự 'Phát hành sớm và thường xuyên' (Release early, release often). Điều này nhằm:
A. Gây khó khăn cho người dùng tải về.
B. Tận dụng tối đa phản hồi của cộng đồng, phát hiện lỗi nhanh chóng và liên tục cải tiến hệ thống (Tương tự triết lý của Agile/Iterative).
C. Giảm giá trị của phần mềm.
D. Che giấu lỗi phần mềm.
*Đáp án: B*

**Câu 116:** Luồng công việc (Workflow) 'Triển khai' (Deployment) trong RUP chịu trách nhiệm cho:
A. Xác định Use-case ban đầu.
B. Đóng gói, tạo bộ cài đặt, phân phối phần mềm đến người dùng cuối, cài đặt và đào tạo người dùng.
C. Sửa mã nguồn của phần cứng.
D. Viết Unit Test.
*Đáp án: B*

**Câu 117:** Khái niệm 'Mô hình lai' (Hybrid model) trong CNPM là gì?
A. Viết một nửa code bằng Java, một nửa bằng C++.
B. Kết hợp những điểm mạnh của nhiều mô hình vòng đời khác nhau (ví dụ: Thác nước + Bản mẫu nhanh) để phù hợp với hoàn cảnh thực tế của dự án.
C. Chỉ chạy được trên 2 hệ điều hành.
D. Chỉ có khách hàng và máy tính làm việc.
*Đáp án: B*

**Câu 118:** Pha 'Inception' (Khởi đầu) trong RUP có thể bị kéo dài nếu:
A. Viết code quá nhanh.
B. Mục tiêu kinh doanh, tầm nhìn và phạm vi của dự án (Scope) không được xác định rõ ràng, hoặc rủi ro tài chính quá cao chưa thể chứng minh tính khả thi.
C. Đội kiểm thử (Tester) làm việc quá giỏi.
D. Đã chốt xong toàn bộ kiến trúc.
*Đáp án: B*

**Câu 119:** Đường cơ sở (Baseline) được tạo ra ở cuối mỗi pha/vòng lặp có tác dụng gì trong Quản lý Cấu hình?
A. Làm tăng số lượng file.
B. Là mốc chuẩn thức để kiểm soát sự thay đổi. Mọi sửa đổi sau khi chốt baseline đều phải trải qua quá trình đánh giá tác động và phê duyệt.
C. Xóa các phiên bản cũ.
D. Giảm chi phí quản lý.
*Đáp án: B*

**Câu 120:** Khi nào thì một 'Bản mẫu nhanh' (Rapid Prototype) có thể được tiến hóa thành sản phẩm thật (Evolutionary Prototyping)?
A. Luôn luôn như vậy.
B. Khi nó được phát triển bằng một ngôn ngữ, công nghệ và kiến trúc nền tảng đủ tốt và tương thích ngay từ đầu, chứ không phải code tạm bợ.
C. Khi khách hàng không thích nó.
D. Khi không còn tiền để viết lại.
*Đáp án: B*

**Câu 121:** Mô hình phát triển nào dưới đây dựa nhiều nhất vào cộng đồng tự nguyện?
A. RUP.
B. Thác nước.
C. Mã nguồn mở (Open-source Model).
D. Xoắn ốc.
*Đáp án: C*

**Câu 122:** RUP sử dụng cách tiếp cận 'Lấy kiến trúc làm trung tâm'. Kiến trúc ở đây thường được biểu diễn qua:
A. Code C++ nguyên thủy.
B. Các mô hình UML nhìn từ nhiều góc độ (4+1 View Model of Architecture) như View logic, View tiến trình, View triển khai...
C. Giao diện HTML/CSS.
D. Chỉ bằng lời nói.
*Đáp án: B*

**Câu 123:** Hoạt động 'Kiểm thử' trong RUP có đặc điểm gì nổi bật?
A. Chỉ bắt đầu ở pha Transition.
B. Khởi đầu ngay từ pha Inception (Lên kế hoạch Test), phát triển mạnh mẽ và chạy liên tục song song cùng mọi vòng lặp để đảm bảo chất lượng liên tục.
C. Chỉ dùng cho mã nguồn mở.
D. Luôn do khách hàng thực hiện.
*Đáp án: B*

**Câu 124:** Một công ty muốn phát triển hệ thống điều khiển tàu vũ trụ siêu an toàn, thời gian dài, ngân sách khổng lồ, mọi sai sót đều trả giá bằng sinh mạng. Mô hình nào hợp lý để quản lý rủi ro tốt nhất kết hợp quy trình khắt khe?
A. Xây và Sửa.
B. Bản mẫu nhanh vứt đi.
C. Xoắn ốc (với quản lý rủi ro nghiêm ngặt) hoặc Thác nước sửa đổi với các chuẩn quân sự.
D. Mã nguồn mở phi tập trung.
*Đáp án: C*

**Câu 125:** Trong RUP, 'Giai đoạn chuyển giao' (Transition phase) nếu người dùng gặp nhiều khó khăn khi sử dụng phần mềm, đội phát triển cần làm gì?
A. Bắt đầu lại pha Inception.
B. Thực hiện bảo trì thích ứng, sửa lỗi (bug fixes), nâng cấp tài liệu và huấn luyện lại người dùng cho đến khi hệ thống vận hành trơn tru.
C. Xóa mã nguồn đi làm lại.
D. Rời bỏ dự án.
*Đáp án: B*

**Câu 126:** Mô hình Tăng trưởng (Incremental) có thể đối mặt với thách thức lớn nào?
A. Khách hàng nhận được sản phẩm quá sớm.
B. Việc thiết kế một kiến trúc tổng thể mở từ ban đầu rất khó, nếu không tốt, việc 'gắn' các mô-đun tăng trưởng sau này sẽ làm vỡ kiến trúc hệ thống.
C. Không có chức năng nào hoạt động.
D. Thời gian kiểm thử bằng 0.
*Đáp án: B*

**Câu 127:** Khái niệm 'Kỹ thuật đảo ngược' (Reverse Engineering) trong bảo trì quy trình phần mềm là gì?
A. Viết code ngược từ dưới lên trên.
B. Phân tích mã nguồn của hệ thống cũ (Legacy) để khôi phục lại các tài liệu thiết kế (UML, sơ đồ) nhằm hiểu và bảo trì hệ thống đó.
C. Cài đặt phần mềm vào một máy tính mới.
D. Hủy dự án.
*Đáp án: B*

**Câu 128:** Theo SWEBOK, luồng công việc 'Đặc tả yêu cầu' (Requirements workflow) phải chỉ ra được:
A. Mọi thuật toán sắp xếp sẽ sử dụng.
B. Chính xác hệ thống sẽ làm GÌ (What it does) mà không mô tả LÀM NHƯ THẾ NÀO (How to do it).
C. Giá tiền máy chủ.
D. Thời gian nghỉ phép của lập trình viên.
*Đáp án: B*

**Câu 129:** Sự lặp lại (Iteration) trong phát triển phần mềm giúp giảm thiểu gì?
A. Chi phí điện.
B. Hiệu ứng 'Big-bang integration' (tích hợp tất cả cùng lúc rồi nổ tung vì lỗi) và sự lãng phí nếu thiết kế ban đầu sai lệch.
C. Sự tham gia của khách hàng.
D. Kỹ năng của lập trình viên.
*Đáp án: B*

**Câu 130:** Trong mô hình Lặp, tại mỗi vòng lặp chúng ta chọn một phần của hệ thống. Phần này thường được chọn dựa trên tiêu chí nào?
A. Phần dễ làm nhất làm trước.
B. Dựa trên mức độ rủi ro lớn nhất hoặc giá trị cốt lõi (Use-case quan trọng nhất) đối với khách hàng để xử lý trước.
C. Chọn ngẫu nhiên.
D. Theo vần A, B, C của tên hàm.
*Đáp án: B*

**Câu 131:** Luồng công việc (Workflow) 'Môi trường' (Environment) trong RUP có nhiệm vụ gì?
A. Dọn dẹp văn phòng công ty sạch sẽ.
B. Cung cấp, thiết lập các công cụ phát triển phần mềm (CASE tools, IDE, Server) và định nghĩa các quy trình làm việc cho đội ngũ dự án.
C. Chăm sóc sức khỏe lập trình viên.
D. Tương tác với hệ điều hành Windows.
*Đáp án: B*

**Câu 132:** Mô hình V (V-Model) là phần mở rộng của mô hình nào?
A. Bản mẫu nhanh.
B. Mô hình Thác nước (Waterfall), trong đó mỗi giai đoạn phát triển đi xuống đều có một giai đoạn kiểm thử tương ứng đi lên.
C. RUP.
D. Xoắn ốc.
*Đáp án: B*

**Câu 133:** Trong mô hình V (V-Model), pha 'Kiểm thử Chấp nhận' (Acceptance Testing) tương ứng (để xác minh) cho pha nào ở nhánh phát triển?
A. Lập trình (Coding).
B. Phân tích / Đặc tả Yêu cầu (Requirements Analysis).
C. Thiết kế chi tiết.
D. Thiết kế kiến trúc.
*Đáp án: B*

**Câu 134:** Mục tiêu của 'Kiểm thử hệ thống' (System Testing) trong mô hình V-Model tương ứng để xác minh cho pha nào?
A. Phân tích yêu cầu.
B. Thiết kế hệ thống / Thiết kế kiến trúc tổng thể.
C. Viết mã nguồn.
D. Kiểm thử đơn vị.
*Đáp án: B*

**Câu 135:** Một trong các hạn chế của mô hình V-Model giống hệt với Thác nước là:
A. Rất linh hoạt.
B. Khó phản ứng với các thay đổi yêu cầu ở giai đoạn muộn (bởi vì nhánh Test đã được lên kế hoạch dựa trên thiết kế ban đầu cứng nhắc).
C. Khách hàng thay đổi yêu cầu rất dễ.
D. Không có bước kiểm thử.
*Đáp án: B*

**Câu 136:** RUP sử dụng khái niệm 'Worker' (hay Role - Vai trò). Vai trò này mang ý nghĩa gì?
A. Là một con người cụ thể (ví dụ: anh Nguyễn Văn A).
B. Đại diện cho một tập hợp các trách nhiệm, kỹ năng mà một cá nhân hoặc nhóm có thể đảm nhận (ví dụ: Vai trò 'Nhà phân tích', 'Lập trình viên'). Một người có thể đóng nhiều vai trò.
C. Là một cái máy tính làm việc.
D. Là một đoạn code.
*Đáp án: B*

**Câu 137:** Rủi ro 'Hiểu lầm nghiệp vụ' (Business Misunderstanding) được giải quyết mạnh nhất ở pha nào của RUP?
A. Chuyển giao.
B. Khởi đầu (Inception) và Khảo sát tỉ mỉ (Elaboration) thông qua luồng công việc Mô hình hóa Nghiệp vụ và Use-case.
C. Xây dựng.
D. Lập trình.
*Đáp án: B*

**Câu 138:** Điều kiện tiên quyết để áp dụng thành công Mô hình Bản mẫu nhanh (Rapid Prototyping) là:
A. Công cụ tạo bản mẫu (như Figma, UI Builder) phải cho phép dựng hình nhanh và chỉnh sửa nhanh chóng mà không tốn quá nhiều chi phí lập trình gốc.
B. Bắt buộc phải dùng Assembly.
C. Khách hàng không được xem bản mẫu.
D. Mã nguồn phải cực kỳ an toàn.
*Đáp án: A*

**Câu 139:** Khi xây dựng phần mềm Quản lý tiền lương cho một công ty, yêu cầu nghiệp vụ phức tạp nhưng rất ổn định, đã có hệ thống cũ mẫu để tham khảo. Mô hình nào phù hợp và tiết kiệm chi phí quản lý nhất?
A. Mô hình Xây và sửa.
B. Mô hình Thác nước (Waterfall), vì mọi thứ đã rõ ràng và ổn định.
C. Bản mẫu vứt đi.
D. Mã nguồn mở.
*Đáp án: B*

**Câu 140:** Việc quản lý rủi ro trong mô hình Xoắn ốc giúp ngăn chặn hiện tượng gì?
A. Tăng lương cho kỹ sư.
B. Tiếp tục đổ tiền khổng lồ vào một dự án vốn dĩ đã có các lỗ hổng kỹ thuật hoặc kinh doanh không thể cứu vãn.
C. Tạo tài liệu.
D. Giảm giá máy tính.
*Đáp án: B*

**Câu 141:** Mô hình Lặp (Iterative) cho phép nhận 'Phản hồi' (Feedback) ở thời điểm nào?
A. Chỉ khi kết thúc toàn bộ dự án.
B. Ngay sau khi kết thúc mỗi vòng lặp (có một phiên bản chạy được), giúp nhóm điều chỉnh hướng đi kịp thời.
C. Không bao giờ.
D. Chỉ trước khi bắt đầu dự án.
*Đáp án: B*

**Câu 142:** Trong quy trình phần mềm, thuật ngữ 'Traceability' (Khả năng truy xuất nguồn gốc) nghĩa là:
A. Khả năng tìm lại đoạn code cũ đã xóa.
B. Khả năng liên kết và theo dõi một Yêu cầu (Requirement) chạy qua Thiết kế, tới Code, và cuối cùng được xác minh ở Test case nào.
C. Tìm xem ai viết đoạn code bị lỗi.
D. Truy tìm địa chỉ IP của khách hàng.
*Đáp án: B*

**Câu 143:** Khái niệm 'Phát triển dựa trên thành phần' (Component-Based Software Engineering - CBSE) tập trung vào:
A. Viết mã nguồn từ đầu (from scratch) cho mọi tính năng.
B. Tìm kiếm, lựa chọn, và lắp ráp các thành phần phần mềm (components / COTS) đã có sẵn để xây dựng hệ thống mới.
C. Bỏ qua thiết kế kiến trúc.
D. Xây dựng phần cứng.
*Đáp án: B*

**Câu 144:** Lợi ích lớn nhất của Phát triển dựa trên thành phần (CBSE) là:
A. Chạy nhanh gấp 100 lần.
B. Tiết kiệm chi phí, giảm thời gian phát triển và tăng độ tin cậy do các thành phần đã được kiểm chứng qua thời gian.
C. Làm tăng khối lượng code phải viết.
D. Giảm thiểu tài liệu hệ thống.
*Đáp án: B*

**Câu 145:** Một nhược điểm của việc sử dụng COTS (Thành phần có sẵn thương mại) trong phát triển phần mềm là:
A. Quá đắt.
B. Thiếu sự kiểm soát hoàn toàn đối với mã nguồn của thành phần đó, khó tùy biến sâu và phụ thuộc vào nhà cung cấp bên thứ 3.
C. Không thể chạy trên máy tính mới.
D. Thành phần không bao giờ có lỗi.
*Đáp án: B*

**Câu 146:** Tại sao 'Kiểm thử hồi quy' (Regression Testing) lại cực kỳ quan trọng trong mô hình Lặp/Agile?
A. Để kiểm tra xem phần cứng có bị nóng không.
B. Mỗi vòng lặp có code mới được thêm vào. Kiểm thử hồi quy đảm bảo những sửa đổi, bổ sung mới không làm hỏng các chức năng cũ đã hoạt động tốt ở vòng trước.
C. Để kiểm tra màu sắc giao diện.
D. Để giảm chi phí mạng.
*Đáp án: B*

**Câu 147:** RUP sử dụng mô hình kiến trúc nào để mô tả hệ thống phần mềm một cách toàn diện?
A. Mô hình 1 lớp.
B. Mô hình 4+1 View (Các khung nhìn: Logical, Process, Development, Physical và gắn kết bằng Use-case view).
C. Mô hình Client-Server thuần túy.
D. Mô hình thực thể kết hợp.
*Đáp án: B*

**Câu 148:** Với tư cách là sinh viên, việc học các Mô hình Vòng đời phần mềm giúp sinh viên:
A. Thuộc lòng lý thuyết để đi thi.
B. Nhận thức được quy trình công nghiệp thực tế, biết chọn 'cách tiếp cận' phù hợp với từng bài toán dự án thay vì chỉ biết 'cắm đầu vào code'.
C. Sửa máy tính giỏi hơn.
D. Làm giao diện đẹp hơn.
*Đáp án: B*

**Câu 149:** Trong thực tế, mô hình Thác nước truyền thống thường được áp dụng bằng cách 'có sửa đổi' (Modified Waterfall). Điều này nghĩa là gì?
A. Không làm tài liệu nữa.
B. Cho phép sự chồng lấn nhẹ giữa các pha và có thể quay ngược lại (vòng phản hồi) 1 pha trước đó để sửa lỗi thiết kế nếu cần.
C. Chia làm 100 pha nhỏ.
D. Chỉ viết code.
*Đáp án: B*

**Câu 151:** Trong RUP, một Use-case có thể được thực hiện (Realized) thông qua gì ở pha thiết kế?
A. Chỉ là các biến int.
B. Một sự kết hợp (Collaboration) của nhiều đối tượng tương tác với nhau để hoàn thành kịch bản của Use-case đó.
C. Một chức năng trên giao diện.
D. Không thể thực hiện được.
*Đáp án: B*

**Câu 152:** Mô hình phát triển phần mềm nào thường có xu hướng tạo ra 'Tài liệu hướng dẫn' một cách tự nhiên nhờ cộng đồng đóng góp trên các diễn đàn/Wiki?
A. Thác nước.
B. RUP.
C. Mô hình Mã nguồn mở (Open-source).
D. Bản mẫu nhanh.
*Đáp án: C*

**Câu 153:** Khái niệm 'Continuous Integration' (Tích hợp liên tục) thường gắn liền nhất với mô hình/phương pháp nào để giảm thiểu rủi ro tích hợp?
A. Thác nước cứng nhắc.
B. Các mô hình Lặp/Agile (như RUP, Scrum), nơi code được ghép lại và kiểm thử tự động hằng ngày.
C. Mô hình Xây và sửa.
D. Sashimi.
*Đáp án: B*

**Câu 154:** Một 'Dự án thất bại' do chọn sai mô hình quy trình phần mềm thường có biểu hiện gì rõ nhất ở giai đoạn cuối?
A. Chỉ có 1 lỗi duy nhất.
B. Khách hàng từ chối nghiệm thu vì sản phẩm làm ra không giống với những gì họ thực sự cần (mặc dù có thể làm đúng theo đặc tả ban đầu).
C. Chạy quá nhanh.
D. Đóng gói file .exe quá lớn.
*Đáp án: B*

**Câu 155:** Mô hình Spiral (Xoắn ốc) có một số vòng lặp tương đương với các pha của Thác nước. Tuy nhiên, nó hơn Thác nước ở chỗ:
A. Không cần viết code.
B. Ở mỗi vòng, trước khi đi sâu vào làm (như Thác nước), nó phải trải qua quá trình đánh giá rủi ro và xây dựng bản mẫu để kiểm chứng.
C. Chỉ làm trong 1 tuần.
D. Bỏ qua khâu phân tích.
*Đáp án: B*

**Câu 156:** Mô hình nào sau đây KHÔNG phù hợp cho dự án khởi nghiệp (Startup) làm một sản phẩm công nghệ hoàn toàn mới, thị trường chưa rõ ràng?
A. Bản mẫu nhanh.
B. Mô hình Thác nước (Bởi vì thị trường và yêu cầu chưa rõ, cần khả năng thay đổi linh hoạt).
C. Mô hình Lặp.
D. Mô hình Tăng trưởng.
*Đáp án: B*

**Câu 157:** Tại sao 'Thiết kế' (Design) lại quan trọng trước khi 'Cài đặt' (Implementation)?
A. Để bắt lập trình viên làm thêm giờ.
B. Như xây nhà phải có bản vẽ, thiết kế giúp định hình cấu trúc vững chắc, chia nhỏ công việc, tránh đụng độ và lỗi logic khi code.
C. Để tăng giá thành dự án.
D. Để máy tính bớt nóng.
*Đáp án: B*

**Câu 158:** Trong mô hình Xoắn ốc, 'Rủi ro' (Risk) có thể là những yếu tố nào?
A. Nhân sự thay đổi, công nghệ mới không hoạt động, vượt quá ngân sách, hoặc hiệu năng hệ thống không đạt yêu cầu.
B. Máy tính bị hỏng.
C. Hết giấy viết báo cáo.
D. Tòa nhà bị cúp điện 1 tiếng.
*Đáp án: A*

**Câu 159:** Hoạt động 'Kiểm thử đơn vị' (Unit Testing) kiểm tra cái gì?
A. Kiểm tra tốc độ của toàn bộ ứng dụng.
B. Kiểm tra chức năng của từng hàm, từng lớp (class) độc lập để đảm bảo chúng hoạt động đúng logic cốt lõi.
C. Kiểm tra cơ sở dữ liệu.
D. Kiểm tra tính bảo mật của mạng.
*Đáp án: B*

**Câu 160:** Nếu một nhóm áp dụng mô hình Bản mẫu nhanh, sau khi hoàn thành Bản mẫu và chốt yêu cầu, bước tối ưu tiếp theo nên làm là gì?
A. Giao Bản mẫu cho khách hàng sử dụng luôn.
B. Vứt Bản mẫu đó đi (nếu nó là Throwaway), và áp dụng một quy trình có kỷ luật (như Thác nước hoặc Lặp) để xây dựng hệ thống thật.
C. Tiếp tục làm Bản mẫu khác.
D. Giải tán nhóm lập trình.
*Đáp án: B*

**Câu 161:** Mô hình Lặp (Iterative) khắc phục điểm yếu nào của Thác nước?
A. Tạo ra quá ít tài liệu.
B. Việc nhận ra thiết kế sai lầm quá muộn ở cuối dự án. Lặp giúp phát hiện thiết kế sai từ sớm thông qua các vòng lặp sớm.
C. Lập trình viên không chịu code.
D. Khách hàng quá thông minh.
*Đáp án: B*

**Câu 162:** Khái niệm 'Phần mềm trung gian' (Middleware) trong việc phát triển hệ thống lớn đóng vai trò gì?
A. Là giao diện người dùng.
B. Cung cấp các dịch vụ kết nối, giao tiếp giữa các ứng dụng và thành phần hệ thống khác nhau (phổ biến trong Component-based).
C. Là trình duyệt Web.
D. Là ngôn ngữ lập trình.
*Đáp án: B*

**Câu 163:** Sự kết thúc của pha 'Elaboration' (Khảo sát tỉ mỉ) trong RUP đánh dấu một mốc quan trọng gọi là 'Lifecycle Architecture Milestone'. Tại mốc này, điều gì đã được hoàn thành?
A. Mã nguồn đã viết xong 100%.
B. Kiến trúc hệ thống đã được chốt, các Use-case quan trọng nhất đã được hiện thực hóa và phần lớn các rủi ro kỹ thuật đã được hóa giải.
C. Giao diện đã thiết kế xong màu sắc.
D. Khách hàng đã trả hết tiền.
*Đáp án: B*

**Câu 164:** Khái niệm 'Tăng trưởng' (Incremental) giúp dự án giảm thiểu rủi ro tài chính như thế nào?
A. Sử dụng công cụ rẻ tiền.
B. Do khách hàng nhận được các chức năng cốt lõi sớm, hệ thống có thể đi vào vận hành và sinh lời (ROI) một phần, ngay cả khi toàn bộ dự án chưa hoàn thiện.
C. Không trả lương cho lập trình viên.
D. Dùng máy chủ cũ.
*Đáp án: B*

**Câu 165:** Trong RUP, 'Sản phẩm trung gian' (Artifacts) của Luồng công việc 'Phân tích và Thiết kế' thường là:
A. Kế hoạch dự án.
B. Các biểu đồ UML (Class diagram, Sequence diagram...), tài liệu kiến trúc.
C. Bộ test case.
D. Mã nguồn thực thi.
*Đáp án: B*

**Câu 166:** Điều gì tạo nên sự phức tạp cao trong quản lý Mô hình Xoắn ốc?
A. Chỉ có 1 vòng lặp.
B. Việc đánh giá rủi ro (Risk Assessment) yêu cầu chuyên gia có trình độ cao và kinh nghiệm, nếu đánh giá sai dự án sẽ thất bại.
C. Dễ quản lý hơn Thác nước.
D. Chỉ phù hợp làm game.
*Đáp án: B*

**Câu 167:** Trong Mô hình Lặp, vòng lặp sau có thể thay đổi thiết kế của vòng lặp trước không?
A. Không bao giờ được phép.
B. Hoàn toàn có thể. Nhờ có phản hồi và kinh nghiệm từ vòng trước, chúng ta tinh chỉnh và cập nhật thiết kế (Refactoring).
C. Chỉ khi được giám đốc đồng ý bằng văn bản.
D. Có nhưng phải đổi ngôn ngữ lập trình.
*Đáp án: B*

**Câu 168:** Quản lý cấu hình (Configuration Management) đặc biệt quan trọng trong các mô hình lặp và tăng trưởng vì sao?
A. Vì không có việc gì làm.
B. Vì số lượng phiên bản, bản vá lỗi, tài liệu và mã nguồn thay đổi liên tục qua từng vòng lặp với tần suất cao, rất dễ gây nhầm lẫn hoặc ghi đè (overwrite) code của nhau.
C. Vì khách hàng yêu cầu thế.
D. Vì nó giúp tăng lương.
*Đáp án: B*

**Câu 169:** Chất lượng phần mềm (Software Quality) trong RUP được kiểm soát như thế nào?
A. Chỉ làm vào ngày cuối cùng của pha Transition.
B. Kiểm soát chất lượng là một nhiệm vụ liên tục (Continuous Quality Control) được đan xen trong mọi luồng công việc ở mọi pha.
C. Để khách hàng tự kiểm tra.
D. Chỉ do Project Manager kiểm tra.
*Đáp án: B*

**Câu 170:** Mô hình Bản mẫu nhanh (Rapid Prototyping) KHÔNG quan tâm đến yếu tố nào ở giai đoạn dựng bản mẫu?
A. Hiệu suất (Performance) thực tế, khả năng bảo trì, cấu trúc code bên trong, và bảo mật (chủ yếu tập trung vào 'Mặt tiền' - UI/UX và luồng nghiệp vụ để khách hàng hình dung).
B. Màu sắc giao diện.
C. Nút bấm.
D. Màn hình hiển thị.
*Đáp án: A*

**Câu 171:** Khái niệm 'Phát triển linh hoạt' (Agile) xuất phát từ Tuyên ngôn Agile (Agile Manifesto) năm 2001, trong đó tôn trọng nguyên tắc nào hơn?
A. Tài liệu toàn diện (Comprehensive documentation) thay vì phần mềm chạy tốt.
B. Cá nhân và sự tương tác (Individuals and interactions) quan trọng hơn Quy trình và công cụ (Processes and tools).
C. Đàm phán hợp đồng thay vì Hợp tác với khách hàng.
D. Tuân thủ cứng nhắc kế hoạch thay vì Thích ứng với thay đổi.
*Đáp án: B*

**Câu 172:** Pha 'Khảo sát tỉ mỉ' (Elaboration) trong RUP khác pha 'Phân tích' của Thác nước ở điểm nào?
A. Không làm gì cả.
B. Elaboration không chỉ phân tích trên giấy mà thực tế CÓ lập trình để xây dựng phần lõi kiến trúc (Architecture Baseline) nhằm xóa bỏ rủi ro, còn Thác nước phân tích xong chỉ có tài liệu.
C. Elaboration dùng C++, Thác nước dùng Java.
D. Không khác gì.
*Đáp án: B*

**Câu 173:** Một trong các 'Hoạt động' (Activities) cơ bản của Luồng công việc 'Mô hình hóa Nghiệp vụ' trong RUP là:
A. Viết CSDL.
B. Hiểu rõ cấu trúc, mục tiêu của tổ chức khách hàng, định nghĩa các 'Business Use-case' và các tác nhân nghiệp vụ.
C. Làm giao diện web.
D. Chạy test tự động.
*Đáp án: B*

**Câu 174:** Khi phát triển dự án bằng Mô hình Tăng trưởng, 'Phiên bản tăng trưởng đầu tiên' (First Increment) thường chứa tính năng gì?
A. Các chức năng râu ria, ít quan trọng.
B. Các chức năng cốt lõi nhất, có rủi ro cao nhất hoặc mang lại giá trị cao nhất cho doanh nghiệp để họ sớm sử dụng và phản hồi.
C. Giao diện màn hình đăng nhập.
D. Trang giới thiệu công ty.
*Đáp án: B*

**Câu 175:** Mô hình Lặp cho phép 'Học hỏi' (Learning) trong quá trình phát triển. Tức là sao?
A. Lập trình viên vừa làm vừa xem Youtube.
B. Quá trình làm vòng lặp 1 sẽ bộc lộ điểm yếu của thiết kế, kiến thức nghiệp vụ chưa chuẩn, giúp đội ngũ sửa đổi và làm tốt hơn ở vòng lặp 2.
C. Bắt khách hàng đi học code.
D. Thuê thầy giáo về dạy học.
*Đáp án: B*

**Câu 176:** Tại sao RUP được xem là một quy trình 'Có thể tùy chỉnh' (Tailorable)?
A. Vì giao diện phần mềm vẽ RUP có thể đổi màu.
B. Vì tùy theo quy mô, tính chất dự án mà người ta có thể cắt giảm bớt các luồng công việc, các tài liệu không cần thiết, chọn ra cách áp dụng RUP phù hợp nhất.
C. Vì RUP là phần mềm mã nguồn mở.
D. Vì RUP được viết bằng UML.
*Đáp án: B*

**Câu 177:** Khái niệm 'Phần mềm như là một Dịch vụ' (SaaS) kết hợp với Mô hình Lặp/Agile tạo ra lợi thế cạnh tranh gì lớn nhất?
A. Tốn tiền hơn.
B. Cho phép nhà phát triển triển khai tính năng mới (Updates) cực kỳ nhanh chóng và liên tục đến mọi người dùng mà họ không cần cài đặt lại.
C. Chạy trên mọi hệ điều hành.
D. Máy tính không cần kết nối mạng.
*Đáp án: B*

**Câu 178:** Công việc 'Đánh giá rủi ro' trong Mô hình Xoắn ốc thường yêu cầu:
A. Lập trình viên mới ra trường.
B. Sự tham gia của các chuyên gia dày dạn kinh nghiệm, vì nếu nhận diện rủi ro sai, toàn bộ các bước sau sẽ thất bại.
C. Máy tính tính toán tự động.
D. Chỉ cần đoán mò.
*Đáp án: B*

**Câu 179:** Trong CNPM, khi nào người ta chọn áp dụng 'Kỹ thuật đảo ngược' (Reverse Engineering)?
A. Khi mới bắt đầu dự án mới tinh.
B. Khi phải tiếp nhận bảo trì một hệ thống Legacy quá cũ, không có tài liệu, mã nguồn như một mớ bòng bong và cần hiểu kiến trúc hiện tại của nó.
C. Khi muốn sao chép game của hãng khác.
D. Khi khách hàng không trả tiền.
*Đáp án: B*

**Câu 180:** Theo SWEBOK, 'Kiểm thử phần mềm' (Software Testing) KHÔNG nhằm mục đích gì?
A. Tìm ra lỗi (bugs) trong phần mềm.
B. Xác minh sự tuân thủ các yêu cầu kỹ thuật.
C. Đánh giá các thuộc tính chất lượng (hiệu năng, bảo mật).
D. Chứng minh phần mềm hoàn hảo, vĩnh viễn không có lỗi.
*Đáp án: D*

**Câu 181:** Mô hình Mã nguồn mở có lợi thế lớn về 'Độ tin cậy' (Reliability) trong bảo mật nhờ lý do gì?
A. Mã nguồn được giấu kỹ.
B. Mã nguồn được công khai, hàng ngàn chuyên gia bảo mật có thể xem, tìm kiếm và vá lỗi hổng nhanh chóng trước khi bị khai thác diện rộng (Trái với 'Bảo mật bằng sự che giấu' của mã nguồn đóng).
C. Người làm mã nguồn mở quá giỏi.
D. Không có ai muốn hack mã nguồn mở.
*Đáp án: B*

**Câu 182:** RUP sử dụng 'Các mốc thời gian' (Milestones) tại cuối mỗi pha để làm gì?
A. Làm bảng lương.
B. Làm cơ sở để đánh giá (Review), ra quyết định Go/No-go (Đi tiếp hay dừng lại) cho toàn bộ dự án dựa trên tiêu chí khách quan.
C. Lập kế hoạch đi du lịch.
D. Xóa mã nguồn cũ.
*Đáp án: B*

**Câu 183:** Mô hình 'Xây dựng dựa trên thành phần' (CBSE) thường gắn liền với mô hình quy trình nào?
A. Thác nước.
B. Có thể gắn với mô hình Lặp/RUP, vì ở pha Elaboration ta có thể đánh giá và tích hợp các COTS/Component có sẵn thay vì tự viết code.
C. Xây và sửa.
D. Bản mẫu vứt đi.
*Đáp án: B*

**Câu 184:** Đâu là một nhược điểm tiềm ẩn của quy trình RUP khi áp dụng vào các đội/dự án quy mô nhỏ?
A. Thiếu công cụ làm việc.
B. Khối lượng tài liệu (Artifacts) và các quy tắc làm việc quá đồ sộ có thể gây cồng kềnh, giảm tốc độ phát triển và lãng phí nguồn lực.
C. Không dùng được ngôn ngữ C++.
D. Chỉ hỗ trợ Windows.
*Đáp án: B*

**Câu 185:** Yếu tố cốt lõi giúp phân biệt giữa 'Tăng trưởng' (Incremental) và 'Lặp' (Iterative) là:
A. Lặp làm trên máy Mac, Tăng trưởng trên Windows.
B. Tăng trưởng tập trung vào việc thêm các chức năng MỚI; Lặp tập trung vào việc tinh chỉnh, sửa đổi các phần ĐÃ CÓ cho hoàn thiện hơn. (RUP thường kết hợp cả hai).
C. Không có sự phân biệt.
D. Tăng trưởng dài hơn Lặp.
*Đáp án: B*

**Câu 186:** Pha 'Transition' (Chuyển tiếp/Chuyển giao) của RUP diễn ra các hoạt động nào để kết thúc dự án?
A. Kiểm thử Beta, chuyển dữ liệu cũ sang hệ thống mới (Data migration), đào tạo người dùng, điều chỉnh cấu hình hệ thống.
B. Khởi tạo Use-case.
C. Thiết kế CSDL mới.
D. Bắt đầu code các mô-đun lõi.
*Đáp án: A*

**Câu 187:** Quy trình RUP được phát triển và hỗ trợ bởi công ty nào ban đầu (trước khi IBM mua lại)?
A. Microsoft.
B. Oracle.
C. Rational Software.
D. Apple.
*Đáp án: C*

**Câu 188:** Khái niệm 'Software Crisis' (Khủng hoảng phần mềm) chủ yếu do sự lệch pha giữa hai yếu tố nào?
A. Giá mạng Internet và giá điện.
B. Sự tiến bộ vũ bão của sức mạnh phần cứng VÀ sự yếu kém/phức tạp trong năng lực quản lý/phát triển các hệ thống phần mềm lớn.
C. Lương lập trình viên và Tester.
D. Ngôn ngữ C và Java.
*Đáp án: B*

**Câu 189:** Phương pháp luận 'Agile' (như Scrum) ngày nay là phiên bản nâng cấp, đơn giản hóa và linh hoạt hơn của mô hình vòng đời nào?
A. Mô hình Thác nước.
B. Mô hình Lặp và Tăng trưởng (Iterative & Incremental).
C. Mô hình Bản mẫu.
D. Mô hình Xoắn ốc.
*Đáp án: B*

**Câu 190:** Trong mô hình Thác nước, sự tương tác với khách hàng thường diễn ra nhiều nhất ở pha nào?
A. Bảo trì.
B. Phân tích yêu cầu (Lúc đầu) và Bàn giao (Lúc cuối). Khách hàng gần như 'biến mất' trong giai đoạn Design và Code.
C. Cài đặt mã nguồn.
D. Thiết kế kiến trúc.
*Đáp án: B*

**Câu 191:** Trong RUP, 'Use-case model' (Mô hình Use-case) phục vụ chức năng chính nào?
A. Vẽ giao diện đẹp hơn.
B. Giao tiếp rõ ràng về các yêu cầu chức năng (What system must do) với khách hàng, không đi sâu vào chi tiết kỹ thuật.
C. Chạy test code tự động.
D. Sinh mã SQL.
*Đáp án: B*

**Câu 192:** Luồng công việc (Workflow) 'Cấu hình và Thay đổi' (Configuration and Change Management) giải quyết vấn đề gì khi làm việc nhóm?
A. Tính giờ làm thêm.
B. Quản lý sự đồng thời (Concurrent work), kiểm soát phiên bản mã nguồn, theo dõi lỗi (Issue tracking) và quản lý các bản build để tránh xung đột mã.
C. Tự động viết tài liệu.
D. Tính tiền khách hàng.
*Đáp án: B*

**Câu 193:** Mô hình Lặp (Iterative) cho phép nhận ra các 'lỗ hổng kiến trúc' sớm vì:
A. Kiến trúc sư thông minh hơn.
B. Ở các vòng lặp đầu, chúng ta hiện thực hóa (Code) các Use-case phức tạp/rủi ro nhất, buộc kiến trúc phải bộc lộ điểm yếu sớm nếu có.
C. Phần mềm được bán rẻ hơn.
D. Dùng UML để vẽ.
*Đáp án: B*

**Câu 194:** Mô hình Xoắn ốc KHÔNG phải là sự lựa chọn tốt khi:
A. Dự án rất lớn và quan trọng.
B. Dự án có hợp đồng cố định giá (Fixed-price contract) nghiêm ngặt với các yêu cầu không thể đổi và thời gian rất ngắn.
C. Dự án có rủi ro cao.
D. Khách hàng là nội bộ.
*Đáp án: B*

**Câu 195:** Theo bài toán Winburg Mini trong sách, sự 'hỗn độn' trong thế giới thực đòi hỏi quy trình phần mềm phải có khả năng:
A. Viết nhiều tài liệu hơn nữa.
B. Thích ứng với sự thay đổi (Yêu cầu đổi, lập trình viên mắc lỗi), dẫn đến việc phải dùng các Vòng lặp phản hồi (Feedback loops) thay vì tuyến tính.
C. Lập trình bằng ngôn ngữ C.
D. Mua máy tính đắt tiền.
*Đáp án: B*

**Câu 196:** Nếu không áp dụng bất kỳ mô hình vòng đời phần mềm nào, nhóm phát triển rất dễ rơi vào tình trạng:
A. Chạy deadline nhanh nhất.
B. Hội chứng 'Code-and-Fix', dẫn đến một hệ thống không thể kiểm soát, đầy lỗi ngầm và không thể mở rộng sau khi hoàn thành.
C. Trở thành một hệ thống mã nguồn mở tốt.
D. Khách hàng vui vẻ vì không tốn thời gian họp.
*Đáp án: B*

**Câu 197:** Chương 2 về Quy trình Phần mềm nhấn mạnh rằng không có một quy trình nào là 'Viên đạn bạc' (Silver bullet). Điều này có nghĩa là:
A. Lập trình viên không nên dùng đạn bạc.
B. Không có một mô hình phần mềm nào là hoàn hảo và giải quyết được mọi khó khăn cho mọi loại dự án. Cần chọn mô hình phù hợp với từng hoàn cảnh cụ thể.
C. Mọi dự án đều thất bại.
D. Chỉ có Thác nước là hoàn hảo.
*Đáp án: B*

**Câu 198:** Kết quả quan trọng nhất sau khi học xong về các Mô hình vòng đời phần mềm là khả năng:
A. Nhớ ngày tháng năm của từng mô hình.
B. Biết phân biệt ưu/nhược điểm, nhận diện được đặc thù của dự án thực tế để quyết định lựa chọn/cấu hình (Tailor) mô hình quy trình phù hợp nhằm đảm bảo dự án thành công.
C. Viết mã nguồn C++ giỏi hơn.
D. Biết cài phần mềm diệt virus.
*Đáp án: B*

**Câu 199:** Mô hình Thác nước (Waterfall) ngày nay tuy ít phổ biến ở dự án phần mềm nhỏ nhưng vẫn được dùng ở đâu?
A. Không còn ai dùng.
B. Các hệ thống hàng không vũ trụ, y tế, hệ thống lớn của chính phủ nơi cần sự minh bạch cực cao, quy trình chứng nhận nghiêm ngặt và yêu cầu ổn định 100% trước khi bắt đầu dự án.
C. Các ứng dụng mobile giải trí.
D. Các dự án khởi nghiệp sinh viên.
*Đáp án: B*

**Câu 200:** Mô hình tiến hóa theo hướng Lặp (Iterative) cho phép thiết kế bị thay đổi (refactor) ở các vòng lặp sau. Tính năng này mang lại lợi ích thực tế gì cho dự án?
A. Làm khách hàng giận dữ.
B. Sửa chữa kịp thời các quyết định thiết kế sai lầm ở giai đoạn đầu, giúp hệ thống không bị mắc kẹt vào một nền tảng kiến trúc tồi tệ cho đến cuối dự án (như ở mô hình Thác nước).
C. Để lập trình viên có thể copy paste mã nguồn.
D. Giảm số lượng tài liệu xuống bằng 0.
*Đáp án: B*
