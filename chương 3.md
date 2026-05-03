# CHƯƠNG 3: YÊU CẦU PHẦN MỀM (SOFTWARE REQUIREMENTS)

## PHẦN 1: Câu hỏi tự luận ngắn

1. **Yêu cầu phần mềm (Software Requirement) là gì?**
   *Gợi ý:* Là mong muốn, nhu cầu của người dùng về các chức năng, khả năng hoặc các ràng buộc mà hệ thống phần mềm cần phải có để hỗ trợ họ giải quyết một bài toán nghiệp vụ.
2. **Kể tên 2 loại yêu cầu cơ bản trong phân loại yêu cầu phần mềm theo tính chất?**
   *Gợi ý:* Yêu cầu chức năng (Functional Requirements) và Yêu cầu phi chức năng (Non-functional Requirements).
3. **Yêu cầu chức năng (Functional Requirement) là gì?**
   *Gợi ý:* Là các đặc tả về những gì hệ thống PHẢI LÀM (What system should do), bao gồm các tính năng, cách hệ thống phản ứng với các dữ liệu đầu vào và các hành vi cụ thể trong từng tình huống.
4. **Yêu cầu phi chức năng (Non-functional Requirement) là gì?**
   *Gợi ý:* Là các ràng buộc về mặt chất lượng, cách hệ thống hoạt động (How system should behave) như: hiệu năng, bảo mật, tính dễ dùng, độ tin cậy, thời gian phản hồi, khả năng bảo trì.
5. **Hãy lấy một ví dụ về yêu cầu chức năng?**
   *Gợi ý:* Hệ thống phải cho phép sinh viên đăng ký môn học trực tuyến. Hệ thống phải tính được điểm trung bình môn.
6. **Hãy lấy một ví dụ về yêu cầu phi chức năng?**
   *Gợi ý:* Trang web phải tải xong trong vòng dưới 2 giây. Hệ thống phải bảo mật thông tin bằng chuẩn mã hóa AES-256. Giao diện phải tương thích với thiết bị di động.
7. **Phân biệt Yêu cầu người dùng (User Requirements) và Yêu cầu hệ thống (System Requirements)?**
   *Gợi ý:* Yêu cầu người dùng thường viết bằng ngôn ngữ tự nhiên, tập trung vào nghiệp vụ chung. Yêu cầu hệ thống chi tiết hơn, kỹ thuật hơn, định nghĩa các chức năng và ràng buộc chính xác để lập trình viên có thể thi công.
8. **Quy trình công nghệ yêu cầu (Requirements Engineering Process) bao gồm 4 hoạt động chính nào?**
   *Gợi ý:* Thu thập (Elicitation) - Phân tích (Analysis) - Đặc tả (Specification) - Thẩm định (Validation). Ngoài ra còn Quản trị yêu cầu (Requirements Management) chạy xuyên suốt.
9. **Hoạt động Khám phá / Thu thập yêu cầu (Elicitation) sử dụng các kỹ thuật nào phổ biến?**
   *Gợi ý:* Phỏng vấn, khảo sát (bảng hỏi), quan sát thực tế (ethnography), họp Brainstorming, nghiên cứu tài liệu hiện có, xây dựng Bản mẫu (Prototyping).
10. **Lý do vì sao việc thu thập yêu cầu lại khó khăn?**
    *Gợi ý:* Khách hàng không biết rõ mình muốn gì, khó diễn đạt bằng từ ngữ, yêu cầu thay đổi liên tục, có sự xung đột lợi ích giữa các bên liên quan (Stakeholders).
11. **Tài liệu SRS (Software Requirements Specification - Đặc tả yêu cầu phần mềm) là gì?**
    *Gợi ý:* Là một tài liệu chính thức mô tả chi tiết, đầy đủ mọi yêu cầu (chức năng, phi chức năng, ràng buộc) của hệ thống phần mềm, đóng vai trò như hợp đồng kỹ thuật giữa đội phát triển và khách hàng.
12. **Tính 'Hoàn chỉnh' (Completeness) trong một tài liệu đặc tả yêu cầu có nghĩa là gì?**
    *Gợi ý:* Tài liệu phải định nghĩa đầy đủ tất cả các tính năng và phản ứng của hệ thống đối với mọi tình huống/đầu vào có thể xảy ra, không được bỏ sót.
13. **Tính 'Nhất quán' (Consistency) trong một tài liệu đặc tả yêu cầu có nghĩa là gì?**
    *Gợi ý:* Không có sự mâu thuẫn hoặc xung đột giữa các yêu cầu trong cùng một tài liệu. (Ví dụ: Không thể quy định màn hình màu đỏ ở trang 1 nhưng lại yêu cầu màu xanh ở trang 10).
14. **Stakeholder (Bên liên quan) trong dự án phần mềm là ai?**
    *Gợi ý:* Là bất kỳ ai có ảnh hưởng hoặc chịu ảnh hưởng trực tiếp/gián tiếp bởi hệ thống (Khách hàng, người dùng cuối, nhà quản lý, lập trình viên, chuyên gia nghiệp vụ...).
15. **Phương pháp phỏng vấn (Interview) có ưu điểm và nhược điểm gì?**
    *Gợi ý:* Ưu điểm: Hiểu sâu mong muốn thực sự của stakeholder. Nhược điểm: Tốn thời gian, phụ thuộc vào kỹ năng người phỏng vấn, khó diễn tả các yêu cầu kỹ thuật chi tiết.
16. **Phương pháp 'Quan sát thực tế' (Ethnography) giúp ích gì trong việc lấy yêu cầu?**
    *Gợi ý:* Giúp chuyên viên phân tích thấy được cách người dùng thực sự làm việc trong môi trường thực tế, phát hiện ra những yêu cầu 'ngầm' mà người dùng quên hoặc không thể diễn đạt qua phỏng vấn.
17. **Trong Use-case, 'Luồng cơ bản' (Basic flow / Happy path) là gì?**
    *Gợi ý:* Là kịch bản chuẩn, lý tưởng nhất trong đó mọi việc diễn ra suôn sẻ, không có lỗi, hệ thống hoàn thành mục tiêu nhanh nhất.
18. **'Luồng rẽ nhánh / Ngoại lệ' (Alternative / Exception flow) trong Use-case là gì?**
    *Gợi ý:* Là các kịch bản xảy ra khi có lỗi, người dùng nhập sai, dữ liệu không hợp lệ, hoặc chọn một cách thao tác khác không giống luồng cơ bản.
19. **Hoạt động 'Thẩm định yêu cầu' (Requirements Validation) để làm gì?**
    *Gợi ý:* Để rà soát, kiểm tra lại tài liệu yêu cầu xem có đúng với những gì khách hàng cần không, có tính khả thi không, có nhất quán và có kiểm thử được không trước khi mang đi lập trình.
20. **Một yêu cầu được coi là 'Có thể kiểm thử được' (Testable / Verifiable) khi nào?**
    *Gợi ý:* Khi có một tiêu chí rõ ràng, định lượng được để Tester có thể thiết kế bài kiểm tra xác nhận yêu cầu đó đạt hay chưa. (Ví dụ: Thay vì nói 'hệ thống chạy nhanh', phải nói 'hệ thống phản hồi dưới 2 giây').
21. **Quản lý yêu cầu (Requirements Management) giải quyết vấn đề gì?**
    *Gợi ý:* Quản lý sự thay đổi của yêu cầu trong suốt quá trình phát triển (Change requests), theo dõi tính truy vết (Traceability) từ yêu cầu đến mã nguồn và kiểm thử để tránh vỡ kế hoạch.
22. **Biểu đồ Use-case (Use-case diagram) mô tả điều gì?**
    *Gợi ý:* Mô tả tương tác giữa hệ thống với môi trường bên ngoài (các Actor/Tác nhân) và các chức năng chính (Use-case) mà hệ thống cung cấp từ góc nhìn của người dùng.
23. **Yêu cầu miền (Domain Requirements) là gì?**
    *Gợi ý:* Là các yêu cầu bắt nguồn từ lĩnh vực ứng dụng của hệ thống (ví dụ: công thức tính lãi suất ngân hàng, luật kế toán) chứ không phải do nhu cầu cá nhân của người dùng.
24. **Sự khác biệt giữa ngôn ngữ tự nhiên và mô hình hóa trực quan (ví dụ UML) khi viết đặc tả?**
    *Gợi ý:* Ngôn ngữ tự nhiên dễ hiểu với mọi người nhưng dễ mập mờ, đa nghĩa. Mô hình hóa trực quan chặt chẽ hơn, cấu trúc tốt nhưng đòi hỏi kỹ năng đọc hiểu biểu đồ.
25. **Vì sao việc sai sót ở khâu Yêu cầu lại gây hậu quả tốn kém nhất?**
    *Gợi ý:* Vì sai yêu cầu dẫn đến sai thiết kế, sai mã nguồn và sai test. Nếu phát hiện vào cuối dự án, phải làm lại (rework) toàn bộ quá trình, chi phí sửa chữa là khổng lồ so với sửa ở ngay khâu tài liệu ban đầu.


## PHẦN 2: Câu hỏi trắc nghiệm (Multiple Choice)

**Câu 1:** Yêu cầu phần mềm (Software Requirement) là gì?
A. Là ngôn ngữ lập trình dùng để viết hệ thống.
B. Là mong muốn, nhu cầu của người dùng về các chức năng và ràng buộc mà hệ thống cần phải có để giải quyết một bài toán.
C. Là máy chủ (server) cần thiết để chạy phần mềm.
D. Là thời gian dự kiến hoàn thành dự án.
*Đáp án: B*

**Câu 2:** Yêu cầu của phần mềm thường được phân thành 2 loại cơ bản nào theo tính chất?
A. Yêu cầu phần cứng và Yêu cầu mạng.
B. Yêu cầu lập trình và Yêu cầu kiểm thử.
C. Yêu cầu chức năng và Yêu cầu phi chức năng.
D. Yêu cầu giao diện và Yêu cầu mã nguồn.
*Đáp án: C*

**Câu 3:** Đâu là ví dụ về Yêu cầu chức năng (Functional Requirement)?
A. Hệ thống phải cho phép người dùng thêm mới sản phẩm vào giỏ hàng.
B. Hệ thống phải chịu tải được 10.000 người truy cập cùng lúc.
C. Màu sắc giao diện phải là màu xanh dương.
D. Hệ thống phải bảo mật bằng chuẩn RSA.
*Đáp án: A*

**Câu 4:** Đâu là ví dụ về Yêu cầu phi chức năng (Non-functional Requirement)?
A. Hệ thống phải tính được tổng số tiền.
B. Màn hình phải phản hồi cho người dùng trong thời gian tối đa 2 giây.
C. Chức năng in báo cáo hàng tháng.
D. Người dùng có quyền xóa bài viết của mình.
*Đáp án: B*

**Câu 5:** Tại sao việc đặc tả rõ ràng Yêu cầu phi chức năng lại rất quan trọng?
A. Vì nó giúp hệ thống không bị xấu.
B. Vì các ràng buộc phi chức năng (như hiệu năng, bảo mật) nếu không đạt có thể làm toàn bộ hệ thống trở nên vô dụng dù có chạy đúng chức năng.
C. Vì nó dễ viết mã nguồn hơn.
D. Vì khách hàng thích đọc nó.
*Đáp án: B*

**Câu 6:** Mục tiêu cốt lõi của kỹ sư yêu cầu (Requirements Engineer) là gì?
A. Tìm lỗi trong mã nguồn.
B. Hiểu đúng và đầy đủ nhu cầu của khách hàng để xây dựng tài liệu đặc tả chuẩn xác.
C. Làm tăng giá trị phần mềm.
D. Viết chương trình chạy nhanh.
*Đáp án: B*

**Câu 7:** Quá trình 'Elicitation' trong kỹ nghệ yêu cầu mang ý nghĩa gì?
A. Dịch mã nguồn.
B. Khám phá, khơi gợi và thu thập yêu cầu từ nhiều nguồn khác nhau (khách hàng, tài liệu, quan sát).
C. Kiểm thử hệ thống tự động.
D. Bán phần mềm cho đối tác.
*Đáp án: B*

**Câu 8:** Kỹ thuật 'Cặp đôi lập trình' (Pair programming) có thuộc quá trình thu thập yêu cầu không?
A. Có, đây là kỹ thuật quan trọng nhất.
B. Không, nó thuộc về pha lập trình (Coding), không phải pha thu thập yêu cầu.
C. Có, dùng để nói chuyện với khách hàng.
D. Không, nó thuộc pha bảo trì.
*Đáp án: B*

**Câu 9:** Sự khác biệt chính giữa User Requirements và System Requirements là gì?
A. User Requirements viết bằng C++, System Requirements viết bằng Java.
B. User Requirements mô tả mức cao (High-level) bằng ngôn ngữ tự nhiên cho khách hàng; System Requirements mô tả chi tiết, kỹ thuật dành cho nhóm phát triển.
C. Không có sự khác biệt.
D. User Requirements dùng hình vẽ, System Requirements dùng âm thanh.
*Đáp án: B*

**Câu 10:** Khái niệm 'Requirement Volatility' (Sự biến động yêu cầu) chỉ tình trạng nào?
A. Giá phần mềm tăng lên.
B. Yêu cầu thay đổi liên tục trong suốt vòng đời của dự án do sự thay đổi của môi trường kinh doanh hoặc do hiểu sai ban đầu.
C. Dung lượng đĩa cứng thay đổi.
D. Thời gian biên dịch quá lâu.
*Đáp án: B*

**Câu 11:** Yêu cầu 'Mật khẩu người dùng phải được mã hóa' là dạng yêu cầu gì?
A. Yêu cầu về môi trường.
B. Yêu cầu phi chức năng (Security).
C. Yêu cầu chức năng.
D. Yêu cầu giao diện.
*Đáp án: B*

**Câu 12:** Trong RUP, tài liệu 'Vision' (Tầm nhìn) được dùng để làm gì?
A. Thiết kế CSDL.
B. Xác định bài toán, tầm nhìn giải pháp tổng thể, và phạm vi hệ thống ở mức độ cao nhất cho toàn bộ dự án.
C. Theo dõi lỗi.
D. Tính lương nhân sự.
*Đáp án: B*

**Câu 13:** Nếu không có bước phân tích yêu cầu, hậu quả dễ thấy nhất là gì?
A. Không sao cả, code vẫn chạy tốt.
B. Sản phẩm được tạo ra có thể không đáp ứng đúng những gì khách hàng thực sự cần (Sai mục tiêu kinh doanh).
C. Máy tính bị hỏng ổ đĩa.
D. Tốc độ gõ phím của lập trình viên tăng lên.
*Đáp án: B*

**Câu 14:** Một yêu cầu tốt (Good Requirement) KHÔNG nên có đặc điểm nào dưới đây?
A. Rõ ràng (Clear).
B. Mập mờ (Ambiguous), có thể hiểu theo nhiều nghĩa.
C. Có thể kiểm thử (Testable).
D. Đầy đủ (Complete).
*Đáp án: B*

**Câu 15:** Sử dụng kỹ thuật 'Prototyping' (Tạo bản mẫu) có lợi ích lớn nhất gì trong giai đoạn Yêu cầu?
A. Tăng số lượng lỗi phần mềm.
B. Cung cấp hình ảnh trực quan giúp người dùng dễ dàng phản hồi và làm rõ các yêu cầu phức tạp hoặc mập mờ.
C. Làm phần cứng chạy nhanh hơn.
D. Biến thành mã nguồn chính thức ngay lập tức.
*Đáp án: B*

**Câu 16:** Kỹ thuật thu thập yêu cầu 'Phân tích tài liệu' (Document Analysis) phù hợp khi nào?
A. Khi muốn biết khách hàng nghĩ gì trong đầu.
B. Khi cần hiểu các quy định pháp lý, biểu mẫu hiện có hoặc tài liệu của hệ thống cũ đang được sử dụng.
C. Khi làm hệ thống game thực tế ảo.
D. Khi muốn đánh giá giao diện người dùng.
*Đáp án: B*

**Câu 17:** Đâu là một lý do khách quan khiến việc lấy yêu cầu khó khăn?
A. Kỹ sư không biết gõ chữ.
B. Người dùng khác nhau có các góc nhìn, từ vựng và ưu tiên khác nhau (thậm chí mâu thuẫn) về cùng một hệ thống.
C. Máy tính không thể ghi âm.
D. Mạng internet quá chậm.
*Đáp án: B*

**Câu 18:** Tài liệu SRS (Software Requirements Specification) chuẩn thường theo định dạng của tổ chức nào?
A. Tổ chức y tế WHO.
B. Tổ chức IEEE (ví dụ: IEEE 830).
C. Tổ chức NATO.
D. Tổ chức liên hợp quốc.
*Đáp án: B*

**Câu 19:** Tại sao Yêu cầu Miền (Domain Requirements) lại rất quan trọng?
A. Vì nó quy định màu sắc của ứng dụng.
B. Nó phản ánh các quy luật nghiệp vụ chuyên ngành (ví dụ công thức tính thuế, y khoa). Nếu làm sai, hệ thống hoàn toàn vô dụng dù code không có lỗi.
C. Vì nó quyết định ngôn ngữ lập trình.
D. Vì nó dễ viết.
*Đáp án: B*

**Câu 20:** Biểu đồ Use-case bao gồm các thành phần cơ bản nào?
A. Mũi tên dữ liệu và Kho dữ liệu.
B. Tác nhân (Actor), Use-case (Chức năng), Mối quan hệ (Relationships) và Đường biên hệ thống (System Boundary).
C. Lớp, Thuộc tính, Phương thức.
D. Các hàm và các biến.
*Đáp án: B*

**Câu 21:** Một Actor trong Use-case có thể tương tác với bao nhiêu Use-case?
A. Chỉ được 1.
B. Nhiều (1 hoặc nhiều Use-case).
C. Không được tương tác.
D. Phải tương tác với tất cả Use-case.
*Đáp án: B*

**Câu 22:** Một Use-case 'Đăng nhập' được gọi bởi Use-case 'Thanh toán' và Use-case 'Xem hồ sơ'. Quan hệ này thường là gì?
A. Extend (Mở rộng).
B. Include (Bao hàm) - Vì 'Đăng nhập' là một bước bắt buộc để thực hiện hai chức năng kia.
C. Generalization (Kế thừa).
D. Association (Kết hợp).
*Đáp án: B*

**Câu 23:** Ký hiệu mũi tên nét đứt với từ khóa <<extend>> có chiều hướng như thế nào?
A. Từ Use-case cơ sở trỏ tới Use-case mở rộng.
B. Từ Use-case mở rộng (Extending) trỏ ngược về Use-case cơ sở (Base).
C. Từ Actor trỏ tới Use-case.
D. Hai chiều.
*Đáp án: B*

**Câu 24:** Đặc điểm nào dưới đây KHÔNG mô tả một Use-case?
A. Nó mô tả tương tác giữa người dùng và hệ thống.
B. Nó mang lại giá trị có ý nghĩa cho Actor.
C. Nó mô tả cấu trúc vật lý của cơ sở dữ liệu (Bảng, Cột, Khóa chính).
D. Nó mô tả hệ thống dưới dạng hộp đen.
*Đáp án: C*

**Câu 25:** Tại sao 'Brainstorming' (Công não) lại hiệu quả trong khâu Khám phá yêu cầu?
A. Vì nó cấm mọi người lên tiếng.
B. Nó khuyến khích mọi người đưa ra các ý tưởng sáng tạo, dù là điên rồ nhất, mà không bị phán xét, từ đó phát hiện những yêu cầu tiềm năng.
C. Vì nó tính tiền theo giờ.
D. Vì nó thay thế hoàn toàn tài liệu SRS.
*Đáp án: B*

**Câu 26:** Mối quan hệ 'Generalization' giữa hai Use-case có nghĩa là gì?
A. Cả hai Use-case không bao giờ được chạy.
B. Use-case con kế thừa, có thể thay đổi hoặc thêm vào hành vi của Use-case cha (Ví dụ: 'Thanh toán thẻ' kế thừa từ 'Thanh toán').
C. Một cái là dữ liệu, một cái là hàm.
D. Không có quan hệ này trong UML.
*Đáp án: B*

**Câu 27:** Hoạt động 'Thương lượng Yêu cầu' (Requirement Negotiation) xảy ra khi nào?
A. Khi lập trình viên muốn tăng lương.
B. Khi có sự xung đột yêu cầu giữa các bên (ví dụ: Marketing muốn thêm nhiều tính năng, Kỹ thuật bảo không kịp thời gian).
C. Khi khách hàng không chịu trả tiền.
D. Khi muốn đổi ngôn ngữ lập trình.
*Đáp án: B*

**Câu 28:** Đặc tả yêu cầu (Requirement Specification) chuyển đổi kết quả phân tích thành dạng gì?
A. Thành mã nguồn Python.
B. Thành một tài liệu chính thức (SRS) có cấu trúc, có thể được dùng làm cơ sở hợp đồng và thiết kế.
C. Thành âm thanh.
D. Thành các linh kiện phần cứng.
*Đáp án: B*

**Câu 29:** Một trong những nguyên tắc cốt lõi khi viết SRS là gì?
A. Chỉ dùng tiếng Anh.
B. Viết rõ ràng 'Hệ thống cần làm gì' (WHAT), thay vì đi sâu vào 'Làm như thế nào' (HOW - thuộc về Thiết kế).
C. Viết càng nhiều thuật ngữ khó càng tốt.
D. Sử dụng thật nhiều màu chữ khác nhau.
*Đáp án: B*

**Câu 30:** Lý do chính khiến tài liệu SRS cần có Bảng thuật ngữ (Glossary) là gì?
A. Làm tăng độ dày tài liệu.
B. Đảm bảo mọi bên (khách hàng, đội kỹ thuật) đều có chung một cách hiểu cho các khái niệm/từ viết tắt chuyên ngành trong dự án.
C. Giúp dịch sang tiếng nước ngoài.
D. Để kiểm tra lỗi chính tả tự động.
*Đáp án: B*

**Câu 31:** Kỹ thuật 'Ma trận truy vết' (Requirements Traceability Matrix) dùng để theo dõi điều gì?
A. Theo dõi chi phí điện của máy tính.
B. Theo dõi sự liên kết hai chiều từ Yêu cầu -> Thiết kế -> Mã nguồn -> Test case, đảm bảo không yêu cầu nào bị bỏ sót khi thực thi.
C. Theo dõi thời gian đi làm của nhân sự.
D. Theo dõi lịch sử duyệt web.
*Đáp án: B*

**Câu 32:** Chất lượng của một tài liệu SRS có thể được kiểm tra chéo thông qua hoạt động nào?
A. Đóng gói file ZIP.
B. Thẩm định yêu cầu (Validation) thông qua các buổi họp Duyệt xét (Reviews/Walkthroughs) với sự tham gia của nhiều bên liên quan.
C. Biên dịch bằng Compiler.
D. Đổi tên file.
*Đáp án: B*

**Câu 33:** Yêu cầu phi chức năng về 'Khả năng mở rộng' (Scalability) nghĩa là gì?
A. Màn hình có thể tự động to ra.
B. Hệ thống có thể dễ dàng tăng hiệu suất và dung lượng (thêm server, tài nguyên) khi số lượng người dùng/dữ liệu tăng vọt.
C. Tính năng có thể dùng cho nhiều công ty.
D. Phần mềm có dung lượng lớn.
*Đáp án: B*

**Câu 34:** Khái niệm 'Yêu cầu pháp lý' (Legal / Regulatory Requirements) mang tính chất gì?
A. Nên có.
B. Bắt buộc tuyệt đối (Mandatory). Nếu không tuân thủ, phần mềm sẽ không được phép triển khai (VD: Luật bảo vệ dữ liệu y tế HIPAA).
C. Có thể thương lượng bỏ qua.
D. Do lập trình viên tự nghĩ ra.
*Đáp án: B*

**Câu 35:** Câu hỏi: 'Phần mềm có được giao diện bằng 3 ngôn ngữ không?' là để lấy loại yêu cầu nào?
A. Hiệu năng.
B. Yêu cầu về Đa ngữ / Quốc tế hóa (Internationalization - Phi chức năng).
C. Yêu cầu về CSDL.
D. Yêu cầu mạng.
*Đáp án: B*

**Câu 36:** Để giảm thiểu việc hiểu lầm yêu cầu, người ta thường viết kịch bản (Scenario) như thế nào?
A. Bằng các thuật toán phức tạp.
B. Bằng một câu chuyện rõ ràng, mô tả từng bước thao tác của người dùng và phản hồi tương ứng của hệ thống trong một bối cảnh cụ thể.
C. Bằng mã nguồn hợp ngữ.
D. Không bao giờ viết kịch bản.
*Đáp án: B*

**Câu 37:** Đâu là một khó khăn khách quan của quá trình 'Thẩm định Yêu cầu'?
A. Không có máy in.
B. Tài liệu yêu cầu thường rất lớn và cồng kềnh, người đọc (đặc biệt là khách hàng) rất khó để tìm ra lỗi logic ẩn sâu bên trong các trang văn bản.
C. Máy tính chạy chậm.
D. Mực in bị nhòe.
*Đáp án: B*

**Câu 38:** Sự phụ thuộc (Dependency) giữa các yêu cầu tạo ra khó khăn gì trong quản trị dự án?
A. Làm tăng dung lượng file SRS.
B. Khi thay đổi một yêu cầu, nó tạo ra hiệu ứng dây chuyền (ripple effect) buộc phải sửa đổi hàng loạt các yêu cầu khác có phụ thuộc vào nó.
C. Tốn kém giấy in.
D. Không tạo ra khó khăn gì.
*Đáp án: B*

**Câu 39:** Công cụ CASE như IBM DOORS hay Jira (cấu hình chuyên biệt) dùng để hỗ trợ công việc gì tốt nhất?
A. Chỉnh sửa ảnh.
B. Quản lý Yêu cầu (Requirements Management) và Theo dõi truy vết (Traceability).
C. Diệt virus.
D. Chơi game.
*Đáp án: B*

**Câu 40:** Nếu một yêu cầu không có tính 'Khả thi' (Feasibility) thì hậu quả là gì?
A. Nó sẽ chạy rất tốt.
B. Nó không thể thực hiện được trong giới hạn của công nghệ hiện tại, hoặc ngân sách, thời gian cho phép, dẫn đến bế tắc dự án.
C. Nó làm tăng tính bảo mật.
D. Nó giúp khách hàng vui hơn.
*Đáp án: B*

**Câu 41:** Tác nhân 'Time' (Thời gian) trong biểu đồ Use-case có thể được sử dụng khi nào?
A. Bất cứ khi nào thích.
B. Khi hệ thống có các chức năng tự động được kích hoạt theo một lịch trình định sẵn (Ví dụ: Tự động tính lãi suất lúc 12h đêm).
C. Khi muốn tính giờ làm việc.
D. Không bao giờ được dùng Thời gian làm Actor.
*Đáp án: B*

**Câu 42:** Từ 'SHOULD' trong ngôn ngữ đặc tả chuẩn (như RFC 2119) mang ý nghĩa gì?
A. Tuyệt đối bắt buộc.
B. Là điều kiện khuyến nghị, nên làm (highly recommended) nhưng có thể bỏ qua nếu có lý do kỹ thuật chính đáng.
C. Hoàn toàn không quan trọng.
D. Nghĩa là 'Không bao giờ được làm'.
*Đáp án: B*

**Câu 43:** Hoạt động 'Duyệt xét' (Review) tài liệu SRS cần sự tham gia của những ai để đạt hiệu quả cao nhất?
A. Chỉ cần 1 lập trình viên.
B. Cần một đội đa thành phần: Đại diện khách hàng (Domain expert), Kỹ sư yêu cầu (BA), Kiến trúc sư và Tester.
C. Chỉ cần giám đốc.
D. Không cần ai tham gia.
*Đáp án: B*

**Câu 44:** Đâu là điểm yếu của phương pháp phỏng vấn (Interview) lấy yêu cầu?
A. Nó diễn ra quá nhanh.
B. Nhiều khi người dùng quen làm theo bản năng nên bỏ sót thông tin, hoặc họ không biết diễn đạt các vấn đề kỹ thuật.
C. Nó làm hỏng máy tính.
D. Nó không có tính tương tác.
*Đáp án: B*

**Câu 45:** Kỹ thuật 'Tạo kịch bản' (Storyboard) thường được áp dụng mạnh mẽ nhất khi thiết kế phần nào?
A. Mã nguồn CSDL.
B. Giao diện người dùng (User Interface) và Luồng tương tác của hệ thống.
C. Thiết lập mạng.
D. Khai báo các biến.
*Đáp án: B*

**Câu 46:** Tại sao nói Quản trị yêu cầu (Requirements Management) phải diễn ra 'Xuyên suốt' dự án?
A. Vì công ty có nhiều thời gian rảnh.
B. Vì sự thay đổi yêu cầu có thể xảy ra ở bất kỳ giai đoạn nào (Design, Code, Test), cần phải liên tục đánh giá và kiểm soát sự thay đổi đó.
C. Vì nó dễ làm.
D. Vì để tính tiền khách hàng nhiều hơn.
*Đáp án: B*

**Câu 47:** Đâu là sự khác nhau giữa 'Lỗi phần mềm' (Bug) và 'Yêu cầu bị bỏ sót' (Missing Requirement)?
A. Không có sự khác nhau.
B. Lỗi phần mềm là code chạy sai so với đặc tả; Yêu cầu bị bỏ sót là chức năng khách hàng cần nhưng không hề có trong đặc tả (do đó không ai code).
C. Lỗi phần mềm do khách hàng tạo ra.
D. Lỗi phần mềm đắt hơn yêu cầu bỏ sót.
*Đáp án: B*

**Câu 48:** Việc xác định 'System Boundary' (Đường biên hệ thống) trong sơ đồ Use-case giúp giải quyết điều gì?
A. Giúp tính chu vi của sơ đồ.
B. Đóng khung ranh giới rõ ràng về việc: Phần mềm của chúng ta chịu trách nhiệm tự động hóa cái gì, và cái gì phải do con người/hệ thống ngoài xử lý.
C. Tính giá điện máy tính.
D. Vẽ cho đẹp.
*Đáp án: B*

**Câu 49:** Sự phức tạp của dự án tăng lên bao nhiêu lần nếu số lượng Yêu cầu tăng gấp đôi?
A. Tăng gấp đôi (Hàm bậc nhất).
B. Thường tăng theo hàm mũ (nhân lên rất nhiều lần), vì số lượng tương tác, phụ thuộc và xung đột tiềm ẩn giữa các yêu cầu tăng đột biến.
C. Không tăng.
D. Giảm đi một nửa.
*Đáp án: B*

**Câu 50:** Ý nghĩa của Yêu cầu phi chức năng về 'Khả năng bảo trì' (Maintainability) là:
A. Hệ thống phải làm việc được trong tủ lạnh.
B. Mã nguồn, kiến trúc và tài liệu phải được thiết kế sao cho việc tìm lỗi, sửa lỗi và nâng cấp sau này tốn ít thời gian và rủi ro nhất.
C. Chương trình chạy siêu nhanh.
D. Màu sắc giao diện dễ nhìn.
*Đáp án: B*

**Câu 51:** Tài liệu SRS (Software Requirements Specification) đóng vai trò gì?
A. Là mã nguồn thực thi.
B. Là hợp đồng kỹ thuật và cơ sở thiết kế, quy định chi tiết những gì phần mềm phải làm.
C. Là cuốn sách dạy lập trình.
D. Chỉ là bản nháp bỏ đi.
*Đáp án: B*

**Câu 52:** Quy trình Công nghệ yêu cầu (Requirements Engineering) bao gồm hoạt động nào sau đây?
A. Lắp ráp máy tính.
B. Khám phá/Thu thập, Phân tích, Đặc tả và Thẩm định yêu cầu.
C. Viết mã nguồn C++.
D. Kiểm thử bảo mật mạng.
*Đáp án: B*

**Câu 53:** Trong hoạt động 'Khám phá / Thu thập yêu cầu' (Elicitation), khó khăn lớn nhất thường gặp là gì?
A. Khách hàng không biết chính xác họ muốn gì hoặc không biết cách diễn đạt nó.
B. Người phân tích không có máy tính.
C. Khách hàng đưa quá nhiều tài liệu.
D. Không có khó khăn gì.
*Đáp án: A*

**Câu 54:** Kỹ thuật 'Phỏng vấn' (Interview) để thu thập yêu cầu có ưu điểm gì?
A. Rất nhanh chóng.
B. Có thể khám phá sâu và chi tiết về nhu cầu thực tế của người dùng thông qua giao tiếp trực tiếp.
C. Không cần chuẩn bị trước.
D. Khách hàng không cần có mặt.
*Đáp án: B*

**Câu 55:** Kỹ thuật 'Quan sát thực tế' (Ethnography) giúp phát hiện điều gì mà phỏng vấn thường bỏ sót?
A. Cách người dùng lướt web giải trí.
B. Các thói quen làm việc thực tế, những yêu cầu 'ngầm' mà người dùng làm theo bản năng nhưng không nói ra được.
C. Tính giá tiền phần mềm.
D. Cách lập trình viên viết code.
*Đáp án: B*

**Câu 56:** Hoạt động 'Thẩm định yêu cầu' (Validation) nhằm trả lời câu hỏi nào?
A. 'Chúng ta có đang xây dựng đúng hệ thống khách hàng cần không?' (Are we building the right system?)
B. 'Tốc độ CPU của máy tính là bao nhiêu?'
C. 'Mã nguồn đã được tối ưu chưa?'
D. 'Đã viết tài liệu chưa?'
*Đáp án: A*

**Câu 57:** Một yêu cầu tốt trong SRS cần phải đạt tính 'Đầy đủ' (Completeness), nghĩa là:
A. Tài liệu phải viết thật dài.
B. Phải mô tả mọi chức năng, phản ứng của hệ thống với mọi dữ liệu đầu vào và tình huống có thể xảy ra, không bỏ sót.
C. Chỉ cần viết những chức năng chính.
D. Sử dụng thật nhiều màu sắc.
*Đáp án: B*

**Câu 58:** Thuộc tính 'Nhất quán' (Consistency) của một tài liệu yêu cầu có nghĩa là:
A. Không có lỗi chính tả.
B. Không có sự mâu thuẫn hay xung đột logic giữa các yêu cầu trong cùng một tài liệu.
C. Tất cả các dòng code phải bằng nhau.
D. Khách hàng không được thay đổi.
*Đáp án: B*

**Câu 59:** Khái niệm 'Quản trị yêu cầu' (Requirements Management) giải quyết vấn đề gì trong dự án?
A. Tìm khách hàng mới.
B. Kiểm soát sự thay đổi của yêu cầu, theo dõi lịch sử và duy trì tính truy vết (Traceability) khi dự án đang tiến hành.
C. Tính lương cho kỹ sư.
D. Quản lý mạng LAN nội bộ.
*Đáp án: B*

**Câu 60:** Khái niệm 'Stakeholder' (Bên liên quan) trong quá trình lấy yêu cầu bao gồm những ai?
A. Chỉ có giám đốc công ty khách hàng.
B. Bất cứ cá nhân, nhóm hay tổ chức nào có ảnh hưởng hoặc chịu ảnh hưởng trực tiếp/gián tiếp bởi hệ thống.
C. Chỉ có lập trình viên.
D. Chỉ có người bỏ tiền mua hệ thống.
*Đáp án: B*

**Câu 61:** Tại sao Yêu cầu phi chức năng (như Thời gian phản hồi < 1s) lại khó kiểm thử (test) hơn Yêu cầu chức năng?
A. Vì nó dễ hơn.
B. Vì nó đòi hỏi các công cụ đo lường chuyên dụng, thiết lập môi trường phức tạp (tải cao) và đôi khi định nghĩa chưa đủ định lượng.
C. Vì Tester không biết đọc.
D. Vì nó không quan trọng.
*Đáp án: B*

**Câu 62:** Đâu là một Yêu cầu Miền (Domain Requirement) điển hình đối với phần mềm kế toán?
A. Nút bấm phải có hình vuông.
B. Phần mềm phải tính toán khấu hao tài sản theo đúng Thông tư số 45/2013/TT-BTC của Bộ Tài chính.
C. Trang web chạy nhanh trên Chrome.
D. Mật khẩu phải có 8 ký tự.
*Đáp án: B*

**Câu 63:** Biểu đồ Use-case (Use-case diagram) thuộc ngôn ngữ mô hình hóa nào?
A. SQL.
B. UML (Unified Modeling Language).
C. HTML.
D. C++.
*Đáp án: B*

**Câu 64:** Một Use-case mô tả điều gì?
A. Giao diện màn hình.
B. Một tập hợp các kịch bản tương tác giữa Tác nhân (Actor) và Hệ thống để hoàn thành một mục tiêu cụ thể.
C. Cấu trúc bảng trong CSDL.
D. Các biến trong lập trình.
*Đáp án: B*

**Câu 65:** Trong biểu đồ Use-case, Tác nhân (Actor) được hiểu là:
A. Các hàm bên trong hệ thống.
B. Một thực thể bên ngoài (Con người hoặc hệ thống khác) tương tác với hệ thống đang được phát triển.
C. Lập trình viên viết ra hệ thống.
D. Một đoạn mã lỗi.
*Đáp án: B*

**Câu 66:** Mối quan hệ <<include>> (Bao gồm) giữa 2 Use-case có ý nghĩa gì?
A. Không có liên quan.
B. Use-case A bắt buộc phải thực thi (gọi) Use-case B như một phần thiết yếu trong quá trình hoạt động của nó.
C. Use-case A là bản phụ của Use-case B.
D. Use-case B chỉ xảy ra khi có lỗi.
*Đáp án: B*

**Câu 67:** Mối quan hệ <<extend>> (Mở rộng) giữa 2 Use-case có ý nghĩa gì?
A. Là sự kế thừa.
B. Use-case mở rộng (B) chỉ được gọi và thực thi thêm vào Use-case cơ sở (A) dưới những ĐIỀU KIỆN nhất định (tùy chọn).
C. Use-case B bắt buộc A phải chạy.
D. Hai Use-case chạy song song.
*Đáp án: B*

**Câu 68:** Khi viết đặc tả Use-case, 'Luồng sự kiện cơ bản' (Basic flow / Happy path) là gì?
A. Là kịch bản xảy ra lỗi nhiều nhất.
B. Là kịch bản lý tưởng, mọi thứ đều đúng đắn, suôn sẻ và đạt được mục tiêu một cách nhanh nhất.
C. Là luồng điện của hệ thống.
D. Là mã nguồn chương trình.
*Đáp án: B*

**Câu 69:** Các 'Luồng sự kiện rẽ nhánh / Ngoại lệ' (Alternative flows) trong Use-case mô tả gì?
A. Là lỗi do lập trình viên.
B. Các tình huống người dùng nhập sai, làm sai hoặc các tùy chọn khác khiến hệ thống không đi theo luồng lý tưởng.
C. Giao diện dự phòng.
D. Không có ý nghĩa gì.
*Đáp án: B*

**Câu 70:** Một trong những mục đích của việc tạo Bản mẫu (Prototyping) trong giai đoạn yêu cầu là:
A. Để bán luôn cho người dùng.
B. Giúp khách hàng trải nghiệm trực quan, từ đó làm rõ và xác nhận chính xác các yêu cầu còn mập mờ.
C. Để tăng kích thước phần mềm.
D. Để đào tạo lập trình viên.
*Đáp án: B*

**Câu 71:** Tài liệu Yêu cầu (SRS) thường do ai là người chủ trì viết?
A. Người dùng cuối.
B. Chuyên viên Phân tích Nghiệp vụ (Business Analyst) hoặc Chuyên viên Phân tích Hệ thống (System Analyst).
C. Giám đốc công ty.
D. Lập trình viên viết code nhanh nhất.
*Đáp án: B*

**Câu 72:** Một yêu cầu tốt phải có tính 'Khả kiểm chứng' (Verifiable / Testable). Điều này nghĩa là gì?
A. Nó có thể dịch sang tiếng nước ngoài.
B. Nó được phát biểu sao cho có thể thiết kế một quy trình (test case) rõ ràng để kiểm tra xem hệ thống có đáp ứng yêu cầu đó hay không.
C. Nó được viết bằng chữ in hoa.
D. Nó không bao giờ thay đổi.
*Đáp án: B*

**Câu 73:** Câu phát biểu yêu cầu nào sau đây là KHÔNG thể kiểm chứng (Untestable)?
A. Hệ thống phải hiển thị danh sách trong vòng 2 giây.
B. Giao diện hệ thống phải 'rất đẹp' và 'thân thiện'.
C. Người dùng phải nhập mật khẩu gồm 8 ký tự.
D. Hệ thống cho phép in hóa đơn ra máy in A4.
*Đáp án: B*

**Câu 74:** Trong Quản trị yêu cầu, tính 'Truy vết' (Traceability) có ích lợi gì?
A. Tìm được nhà của khách hàng.
B. Giúp xác định nhanh chóng những mã nguồn, biểu đồ, bài test nào sẽ bị ảnh hưởng nếu một yêu cầu thay đổi, giúp kiểm soát rủi ro.
C. Tính toán dung lượng ổ cứng.
D. Xóa dữ liệu nhanh hơn.
*Đáp án: B*

**Câu 75:** Vì sao khách hàng và đội phát triển thường có cái nhìn khác nhau về hệ thống?
A. Vì họ làm việc khác múi giờ.
B. Vì khách hàng nói theo ngôn ngữ nghiệp vụ/thực tế công việc (Problem domain), còn kỹ sư thường tư duy theo logic/công nghệ (Solution domain).
C. Vì kỹ sư không muốn làm việc.
D. Vì khách hàng không trả tiền.
*Đáp án: B*

**Câu 76:** Yêu cầu hệ thống (System Requirements) thường dành cho đối tượng người đọc chính nào?
A. Giám đốc điều hành không biết kỹ thuật.
B. Các kỹ sư thiết kế phần mềm, lập trình viên và người kiểm thử (Testers).
C. Nhân viên bán hàng.
D. Người dùng cuối tải app.
*Đáp án: B*

**Câu 77:** Kỹ thuật 'Brainstorming' (Công não) trong việc khám phá yêu cầu nhằm mục đích gì?
A. Sửa lỗi mã nguồn.
B. Kích thích sự sáng tạo của nhóm, thu thập càng nhiều ý tưởng và yêu cầu càng tốt một cách tự do trước khi chọn lọc.
C. Đuổi việc nhân viên.
D. Dừng dự án.
*Đáp án: B*

**Câu 78:** Ràng buộc (Constraints) trong yêu cầu phần mềm có thể là gì?
A. Tốc độ gõ phím của khách hàng.
B. Bắt buộc dùng ngôn ngữ Java, bắt buộc dùng CSDL Oracle, hoặc phải hoàn thành trước ngày 31/12.
C. Sở thích màu sắc cá nhân.
D. Hạn chế ăn uống trong giờ làm.
*Đáp án: B*

**Câu 79:** Theo IEEE 830, tài liệu SRS không nên chứa điều gì?
A. Các yêu cầu chức năng.
B. Chi tiết thiết kế kiến trúc và giải pháp lập trình (Nên mô tả 'Cái gì' chứ không phải 'Làm thế nào').
C. Các ràng buộc phần cứng.
D. Các yêu cầu giao diện bên ngoài.
*Đáp án: B*

**Câu 80:** Một yêu cầu bị mập mờ (Ambiguous) sẽ gây ra hậu quả gì?
A. Khách hàng sẽ thích thú.
B. Lập trình viên và Tester sẽ hiểu theo nhiều nghĩa khác nhau, dẫn đến lập trình sai ý khách hàng.
C. Phần mềm chạy nhanh hơn.
D. Máy tính không biên dịch được.
*Đáp án: B*

**Câu 81:** Sự thay đổi yêu cầu (Requirement volatility) thường do đâu?
A. Khách hàng thay đổi tư duy, mô hình kinh doanh thay đổi, môi trường luật pháp đổi, hoặc do lúc đầu hiểu sai.
B. Do máy tính bị virus.
C. Do phần cứng thay đổi hình dáng.
D. Do dùng hệ điều hành khác.
*Đáp án: A*

**Câu 82:** Một trong các công việc của Thẩm định yêu cầu (Validation) là kiểm tra tính Hiện thực (Realism). Nghĩa là gì?
A. Yêu cầu phải được vẽ bằng UML.
B. Đảm bảo yêu cầu có thể thực thi được với ngân sách, công nghệ và thời gian hiện tại của dự án.
C. Yêu cầu phải đẹp.
D. Yêu cầu phải được viết tay.
*Đáp án: B*

**Câu 83:** Phân tích yêu cầu (Analysis) khác gì Khám phá yêu cầu (Elicitation)?
A. Không khác gì.
B. Elicitation là đi lấy thông tin. Analysis là phân loại, sắp xếp, giải quyết xung đột và mô hình hóa các thông tin đó.
C. Phân tích là viết code.
D. Khám phá là tìm máy tính mới.
*Đáp án: B*

**Câu 84:** Chỉ số nào trong Yêu cầu Phi chức năng định nghĩa khả năng 'hồi phục sau lỗi' của hệ thống?
A. Tính tái sử dụng.
B. Độ bền bỉ / Khả năng phục hồi (Resilience / Recoverability).
C. Tính thẩm mỹ.
D. Tính khả chuyển.
*Đáp án: B*

**Câu 85:** Trong Use-case diagram, ký hiệu hình Oval (Hình bầu dục) dùng để biểu diễn cái gì?
A. Tác nhân (Actor).
B. Một Use-case (Chức năng).
C. Hệ thống (System Boundary).
D. Mối quan hệ.
*Đáp án: B*

**Câu 86:** Đâu là ví dụ về một Tác nhân (Actor) KHÔNG phải là con người?
A. Khách hàng.
B. Nhân viên quản trị mạng.
C. Hệ thống Cổng thanh toán quốc tế (VD: Paypal, VNPay) kết nối với hệ thống hiện tại.
D. Giám đốc.
*Đáp án: C*

**Câu 87:** Điều gì KHÔNG CÓ trong tài liệu Đặc tả Yêu cầu (SRS) chuẩn?
A. Giao diện giao tiếp.
B. Sơ đồ cấu trúc CSDL chi tiết các bảng, trường và kiểu dữ liệu (thuộc về Design document).
C. Yêu cầu hiệu năng.
D. Quy định bảo mật.
*Đáp án: B*

**Câu 88:** Trong quy trình lấy yêu cầu, tại sao lại có sự 'Xung đột yêu cầu' (Requirement Conflict)?
A. Vì các lập trình viên cãi nhau.
B. Vì các Stakeholders khác nhau (ví dụ Giám đốc muốn tiết kiệm, Nhân viên muốn nhiều tính năng tiện lợi) có các mục tiêu và ưu tiên đối nghịch nhau.
C. Vì phần mềm bị lỗi.
D. Vì khách hàng thiếu tiền.
*Đáp án: B*

**Câu 89:** Hoạt động 'Thương lượng yêu cầu' (Requirement Negotiation) có mục đích gì?
A. Mặc cả giá tiền phần cứng.
B. Giải quyết các xung đột yêu cầu giữa các Stakeholders để đạt được sự đồng thuận trước khi viết đặc tả.
C. Từ chối khách hàng.
D. Bắt lập trình viên làm thêm giờ.
*Đáp án: B*

**Câu 90:** Biểu diễn yêu cầu bằng 'Ngôn ngữ tự nhiên có cấu trúc' (Structured natural language) có ưu điểm gì so với câu văn tự do?
A. Rất khó đọc.
B. Sử dụng các biểu mẫu/cấu trúc chuẩn hóa (VD: Tiền điều kiện, Kịch bản, Hậu điều kiện) giúp giảm sự mập mờ, nhất quán và dễ đọc hơn văn xuôi tự do.
C. Không ai hiểu được.
D. Chỉ dành cho ngôn ngữ C.
*Đáp án: B*

**Câu 91:** Từ khóa 'SHALL' (Phải) và 'SHOULD' (Nên) trong tài liệu đặc tả bằng tiếng Anh (RFC 2119) khác nhau thế nào?
A. Giống hệt nhau.
B. 'SHALL' chỉ một yêu cầu bắt buộc tuyệt đối. 'SHOULD' chỉ sự khuyến nghị (tốt nhất là nên làm) nhưng có thể bỏ qua nếu có lý do chính đáng.
C. SHALL là không bắt buộc.
D. SHOULD là bắt buộc.
*Đáp án: B*

**Câu 92:** Bảng ma trận truy vết yêu cầu (Requirement Traceability Matrix - RTM) dùng để ánh xạ (map) cái gì?
A. Ánh xạ địa chỉ nhà khách hàng.
B. Ánh xạ các yêu cầu với các thành phần thiết kế, module code, và Test cases tương ứng để đảm bảo yêu cầu đã được làm và kiểm tra đầy đủ.
C. Ánh xạ màn hình máy tính.
D. Ánh xạ bảng màu giao diện.
*Đáp án: B*

**Câu 93:** Kịch bản (Scenario) trong phân tích yêu cầu có vai trò gì?
A. Làm phim.
B. Là câu chuyện mô tả một quá trình sử dụng hệ thống cụ thể, giúp khách hàng dễ hiểu và xác nhận các bước nghiệp vụ.
C. Giúp lập trình viên chơi game.
D. Không có vai trò gì.
*Đáp án: B*

**Câu 94:** Khái niệm 'Yêu cầu do luật pháp quy định' (Regulatory Requirements) thuộc nhóm nào?
A. Yêu cầu chức năng đồ họa.
B. Một loại yêu cầu Miền/Phi chức năng bắt buộc phải tuân thủ (ví dụ: Bảo mật dữ liệu cá nhân theo luật GDPR).
C. Sở thích của quản lý.
D. Không cần quan tâm.
*Đáp án: B*

**Câu 95:** Tại sao cần 'Đánh giá độ ưu tiên' (Prioritization) của các yêu cầu?
A. Để biết yêu cầu nào dài nhất.
B. Trong điều kiện tài nguyên (thời gian, tiền bạc) giới hạn, ưu tiên giúp xác định những yêu cầu cốt lõi nhất phải làm trước (Must-have).
C. Để xóa bỏ yêu cầu.
D. Để chọc giận khách hàng.
*Đáp án: B*

**Câu 96:** Khi thay đổi một yêu cầu, hệ thống quản trị yêu cầu phải làm gì?
A. Mặc kệ nó.
B. Đánh giá tác động (Impact Analysis) để xem thay đổi này ảnh hưởng đến những mô-đun nào, tốn thêm bao nhiêu thời gian và tiền bạc trước khi phê duyệt.
C. Đuổi việc người đưa ra thay đổi.
D. Xóa hệ thống đi làm lại.
*Đáp án: B*

**Câu 97:** Trong biểu đồ Use-case, Actor (Tác nhân) luôn nằm ở đâu so với Hệ thống (System Boundary)?
A. Nằm bên trong hệ thống.
B. Nằm bên ngoài đường biên hệ thống (System Boundary), tương tác từ ngoài vào.
C. Nằm giữa các Use-case.
D. Tùy ý vẽ đâu cũng được.
*Đáp án: B*

**Câu 98:** Cách tốt nhất để phát hiện các yêu cầu 'bị bỏ sót' (Missing requirements) trong giai đoạn thẩm định là gì?
A. Viết code thật nhanh.
B. Sử dụng các Checklist chuẩn, review cùng nhiều nhóm Stakeholders và sử dụng Kịch bản (Scenarios)/Bản mẫu để người dùng dễ nhận ra cái còn thiếu.
C. Không làm gì, chờ khách hàng kiện.
D. Dùng máy quét virus.
*Đáp án: B*

**Câu 99:** Sự 'Lão hóa' (Aging) của tài liệu Yêu cầu nghĩa là gì?
A. Giấy bị ố vàng.
B. Tài liệu không được cập nhật song song với sự thay đổi của mã nguồn trong quá trình bảo trì, dẫn đến tài liệu trở nên sai lệch và vô giá trị.
C. File Word bị lỗi font.
D. Không ai thèm đọc.
*Đáp án: B*

**Câu 100:** Trong RUP, tài liệu 'Tầm nhìn' (Vision Document) được tạo ra chủ yếu ở pha nào?
A. Pha Chuyển giao.
B. Pha Khởi đầu (Inception) để mô tả bài toán, các giải pháp và phạm vi chung nhất của dự án.
C. Pha Xây dựng.
D. Pha Bảo trì.
*Đáp án: B*

**Câu 101:** Nếu khách hàng yêu cầu 'Hệ thống phải dễ sử dụng', chuyên viên phân tích nên phản hồi thế nào để yêu cầu này có tính kiểm chứng (Testable)?
A. Đồng ý và ghi đúng câu đó vào SRS.
B. Yêu cầu khách hàng lượng hóa, ví dụ: 'Người dùng mới có thể thực hiện giao dịch A trong vòng dưới 3 phút mà không cần người hướng dẫn'.
C. Từ chối yêu cầu này vì quá vô lý.
D. Bảo lập trình viên tự nghĩ ra giao diện đẹp.
*Đáp án: B*

**Câu 102:** Hoạt động nào giúp xác định 'Tác nhân' (Actor) của hệ thống một cách hiệu quả nhất?
A. Hỏi lập trình viên xem họ biết những ai.
B. Xác định ai/cái gì cung cấp dữ liệu cho hệ thống, ai/cái gì nhận dữ liệu từ hệ thống và ai quản trị hệ thống.
C. Xác định số lượng máy tính trong công ty.
D. Không cần xác định Tác nhân.
*Đáp án: B*

**Câu 103:** Mức độ chi tiết của tài liệu SRS phụ thuộc nhiều nhất vào yếu tố nào?
A. Sở thích của người viết.
B. Quy mô, độ phức tạp của dự án, và quy trình phát triển được chọn (Agile thường viết ít SRS hơn Thác nước).
C. Màu sắc của hệ điều hành.
D. Số lượng trang giấy in.
*Đáp án: B*

**Câu 104:** Khái niệm 'Tiền điều kiện' (Pre-condition) trong đặc tả một Use-case là gì?
A. Số tiền khách hàng phải trả.
B. Các điều kiện hoặc trạng thái bắt buộc hệ thống phải thỏa mãn TRƯỚC KHI Use-case này có thể bắt đầu thực thi.
C. Là mã PIN của người dùng.
D. Chỉ là phần giới thiệu mở bài.
*Đáp án: B*

**Câu 105:** Khái niệm 'Hậu điều kiện' (Post-condition) trong đặc tả một Use-case là gì?
A. Lời chào tạm biệt người dùng.
B. Trạng thái của hệ thống SAU KHI Use-case thực thi thành công (Ví dụ: Tiền trong tài khoản bị trừ, Giao dịch được lưu).
C. Máy tính tự động tắt.
D. Điều kiện để sửa lỗi.
*Đáp án: B*

**Câu 106:** Trong RUP, tài liệu 'Đặc tả bổ sung' (Supplementary Specification) dùng để lưu trữ gì?
A. Code C++ viết thêm.
B. Các yêu cầu phi chức năng (Non-functional), các ràng buộc và các luật nghiệp vụ chung KHÔNG thuộc riêng về một Use-case cụ thể nào.
C. Hình ảnh quảng cáo công ty.
D. Bảng chấm công của kỹ sư.
*Đáp án: B*

**Câu 107:** Thuật ngữ 'Scope Creep' (Sự phình to phạm vi/Yêu cầu rình rập) mô tả hiện tượng gì?
A. Khách hàng không chịu đưa yêu cầu.
B. Yêu cầu của dự án liên tục bị thêm mới hoặc thay đổi một cách không kiểm soát trong quá trình phát triển, làm vỡ ngân sách và thời gian.
C. Phần mềm chạy quá nhanh.
D. Kích thước file cài đặt bị lớn.
*Đáp án: B*

**Câu 108:** Làm sao để hạn chế 'Scope Creep' hiệu quả nhất?
A. Từ chối làm việc với khách hàng.
B. Có tài liệu Baseline yêu cầu rõ ràng, có quy trình đánh giá và phê duyệt thay đổi (Change Control Board) khắt khe.
C. Chỉ viết code theo cảm hứng.
D. Tắt điện thoại khi khách hàng gọi.
*Đáp án: B*

**Câu 109:** Khi một yêu cầu chức năng thay đổi, điều gì khác trong dự án cần được xem xét cập nhật theo?
A. Chỉ cần sửa dòng chữ trong file Word.
B. Phải cập nhật lại Mã nguồn (Code), Biểu đồ thiết kế (Design), Tài liệu Test (Test cases) và Tài liệu hướng dẫn người dùng.
C. Mua máy tính mới.
D. Chỉ cần thông báo miệng.
*Đáp án: B*

**Câu 110:** Câu phát biểu nào sau đây mang đặc tính của Yêu cầu Bảo mật (Security Requirement)?
A. Hệ thống phải có nút Login.
B. Mật khẩu của người dùng phải được mã hóa bằng thuật toán SHA-256 trước khi lưu vào CSDL và hệ thống sẽ tự động khóa tài khoản sau 3 lần đăng nhập sai.
C. Giao diện có màu xám đậm.
D. Phần mềm tải xuống mất 1 phút.
*Đáp án: B*

**Câu 111:** Phương pháp thu thập yêu cầu 'JAD' (Joint Application Design) có đặc điểm gì?
A. Làm việc một mình trong phòng kín.
B. Tổ chức các buổi hội thảo tập trung (workshop) có sự tham gia cùng lúc của người dùng, chuyên gia nghiệp vụ và đội kỹ thuật để làm rõ và chốt yêu cầu nhanh chóng.
C. Chỉ gọi điện thoại.
D. Nhắn tin qua email.
*Đáp án: B*

**Câu 112:** Cấu trúc 'Shall' trong IEEE 830 thể hiện điều gì?
A. Gợi ý có thể làm hoặc không.
B. Tính bắt buộc tuyệt đối, hệ thống PHẢI có chức năng hoặc thỏa mãn ràng buộc đó.
C. Một chức năng vô dụng.
D. Không có ý nghĩa.
*Đáp án: B*

**Câu 113:** Tại sao 'Độ đo' (Metrics) lại cần thiết cho Yêu cầu Phi chức năng?
A. Để tài liệu trông chuyên nghiệp hơn.
B. Vì những khái niệm như 'nhanh', 'an toàn', 'dễ dùng' rất cảm tính. Phải có độ đo (ví dụ: < 1 giây, chống được tấn công DDoS) mới có thể kiểm thử (Verify) một cách khách quan.
C. Để lấy lý do tăng giá phần mềm.
D. Không cần độ đo.
*Đáp án: B*

**Câu 114:** Trong RUP, biểu đồ Use-case đóng vai trò gì ở pha Inception?
A. Chỉ vẽ cho đẹp.
B. Xác định phạm vi (Scope) của hệ thống: hệ thống làm gì (bên trong biên) và ai tương tác với nó (các Actor bên ngoài biên).
C. Để sinh tự động ra code.
D. Để tính thời gian gõ phím.
*Đáp án: B*

**Câu 115:** Thuộc tính 'Khả năng theo vết ngược' (Backward Traceability) trong quản lý yêu cầu là gì?
A. Kiểm tra xem ai đã xóa file.
B. Khả năng truy xuất từ một dòng code hoặc thiết kế ngược trở lại xem nó phục vụ cho Yêu cầu (Requirement) nào, từ đó biết có cần thiết hay không.
C. Lùi lịch thời gian dự án.
D. Khôi phục hệ điều hành.
*Đáp án: B*

**Câu 116:** Kỹ thuật 'Tạo kịch bản' (Scenarios) giúp giải quyết khó khăn gì trong thu thập yêu cầu?
A. Giúp làm ra giao diện đẹp.
B. Giúp khách hàng dễ hình dung bối cảnh thực tế hệ thống sẽ được dùng như thế nào, thay vì phải đọc các mô tả trừu tượng và khô khan.
C. Giúp lập trình viên học C++.
D. Giảm thời gian đánh máy.
*Đáp án: B*

**Câu 117:** Một sai lầm phổ biến khi viết Yêu cầu là 'Thiết kế thay vì Đặc tả'. Ví dụ nào minh họa cho sai lầm này?
A. 'Hệ thống phải lưu trữ thông tin sinh viên'.
B. 'Hệ thống phải lưu tên sinh viên vào một mảng String 2 chiều và sắp xếp bằng thuật toán QuickSort'. (Đây là 'Làm thế nào', không phải 'Làm gì').
C. 'Hệ thống cho phép đăng nhập'.
D. 'Hệ thống in hóa đơn A4'.
*Đáp án: B*

**Câu 118:** Vì sao Yêu cầu Miền (Domain Requirements) nếu không đáp ứng được sẽ dẫn đến hậu quả nghiêm trọng?
A. Khách hàng sẽ thấy chán.
B. Vì nó chứa các luật nghiệp vụ, công thức tính toán cốt lõi. Nếu tính lương sai luật hoặc tính lãi sai công thức, hệ thống không thể sử dụng.
C. Giao diện sẽ bị mờ.
D. Máy tính sẽ hỏng.
*Đáp án: B*

**Câu 119:** Biểu đồ Use-case KHÔNG thể hiện điều gì?
A. Danh sách các Actor.
B. Luồng dữ liệu chi tiết, các lệnh if-else hoặc thứ tự thời gian bên trong một chức năng (cần dùng Sequence hoặc Activity Diagram).
C. Các Use-case chính.
D. Mối liên hệ giữa Actor và Use-case.
*Đáp án: B*

**Câu 120:** Khái niệm 'Kỹ thuật Phân tích nghiệp vụ' (Business Analysis) khác Công nghệ phần mềm ở điểm nào?
A. Phân tích nghiệp vụ chỉ viết code.
B. Phân tích nghiệp vụ tập trung vào cải tiến quy trình công ty, tìm giải pháp kinh doanh (có thể không dùng phần mềm); CNPM tập trung vào chế tạo phần mềm để giải quyết bài toán đó.
C. Hai lĩnh vực là một.
D. Phân tích nghiệp vụ không quan tâm đến khách hàng.
*Đáp án: B*

**Câu 121:** Trong việc thu thập yêu cầu, tài liệu 'Bảng câu hỏi / Khảo sát' (Questionnaire) có ưu thế khi nào?
A. Khi muốn hỏi thật sâu một cá nhân.
B. Khi hệ thống có số lượng người dùng rất lớn, rải rác ở nhiều nơi và cần thu thập ý kiến định lượng (thống kê) nhanh chóng.
C. Khi khách hàng không biết chữ.
D. Khi muốn kiểm thử tốc độ mạng.
*Đáp án: B*

**Câu 122:** Đâu là một khó khăn khi sử dụng 'Bản mẫu nhanh' (Throw-away prototype) để lấy yêu cầu?
A. Nó làm khách hàng sợ hãi.
B. Khách hàng có thể lầm tưởng rằng phần mềm đã gần hoàn thành và hối thúc giao hàng, hoặc bắt nhóm phát triển dùng luôn cái bản nháp đó làm sản phẩm thật.
C. Nó tốn quá nhiều giấy.
D. Nó chạy quá nhanh.
*Đáp án: B*

**Câu 123:** Trong RUP, để quản lý độ ưu tiên của Use-case, người ta thường dùng tiêu chí nào?
A. Chọn cái dài nhất làm trước.
B. Giá trị mang lại cho nghiệp vụ (Business value) và Mức độ rủi ro về mặt kiến trúc/công nghệ (Architectural significance & Risk).
C. Chọn ngẫu nhiên.
D. Theo sở thích của Tester.
*Đáp án: B*

**Câu 124:** Nếu một yêu cầu phát biểu: 'Hệ thống phải có độ tin cậy 99.999% uptime', thì yêu cầu này thuộc loại:
A. Yêu cầu chức năng.
B. Yêu cầu phi chức năng (Độ sẵn sàng / Availability).
C. Yêu cầu pháp lý.
D. Yêu cầu giao diện.
*Đáp án: B*

**Câu 125:** Mối quan hệ 'Generalization' (Tổng quát hóa / Kế thừa) giữa 2 Use-case có nghĩa là gì?
A. Chúng không liên quan.
B. Một Use-case con thừa kế hành vi và ý nghĩa của Use-case cha, nhưng có thể thêm hoặc ghi đè hành vi riêng (VD: 'Thanh toán' là cha, 'Thanh toán thẻ' là con).
C. Use-case A chạy xong mới đến B.
D. Hai Use-case là một.
*Đáp án: B*

**Câu 126:** Tại sao 'Yêu cầu do luật định' (Regulatory requirements) thường không thể thương lượng được (Non-negotiable)?
A. Vì khách hàng khó tính.
B. Vì nếu vi phạm luật pháp (như quy định về kế toán, thuế, bảo mật thông tin cá nhân), phần mềm sẽ bị cấm vận hành và công ty bị phạt.
C. Vì lập trình viên thích thế.
D. Vì nó dễ viết code hơn.
*Đáp án: B*

**Câu 127:** Khái niệm 'Kỹ sư Cầu nối' (Bridge Software Engineer / BrSE) thường đảm nhận công việc gì?
A. Xây dựng phần mềm cho kỹ sư cầu đường.
B. Làm cầu nối giao tiếp, dịch và truyền đạt yêu cầu nghiệp vụ từ khách hàng (thường là nước ngoài) cho đội ngũ phát triển (Offshore) hiểu và thực thi.
C. Sửa lỗi mạng LAN.
D. Chỉ kiểm thử tự động.
*Đáp án: B*

**Câu 128:** Khi đặc tả Yêu cầu Giao diện Người dùng (User Interface Requirements), ta nên cung cấp gì?
A. Mã nguồn giao diện CSS chi tiết.
B. Các ràng buộc về sự nhất quán, phác thảo màn hình (Mockups/Wireframes), tiêu chuẩn phản hồi và luật thiết kế (VD: Cảnh báo lỗi màu đỏ).
C. Chỉ cần ghi 'Giao diện thân thiện'.
D. Cơ sở dữ liệu.
*Đáp án: B*

**Câu 129:** Một trong các kỹ thuật Thẩm định Yêu cầu (Validation) hiệu quả nhất là:
A. Không làm gì cả.
B. Kiểm tra chéo (Reviews/Inspections) bởi một nhóm độc lập bao gồm Khách hàng, Tester và Kiến trúc sư để tìm mâu thuẫn.
C. Gõ lại toàn bộ tài liệu.
D. Nén file PDF.
*Đáp án: B*

**Câu 130:** Theo ISO/IEC 25010, tiêu chí 'Tính tương thích' (Compatibility) yêu cầu hệ thống phải:
A. Chạy nhanh nhất.
B. Có khả năng trao đổi thông tin, chia sẻ dữ liệu chung và chạy ổn định trên cùng một môi trường phần cứng/phần mềm với các hệ thống khác mà không bị xung đột.
C. Giao diện đẹp nhất.
D. Mã hóa 100%.
*Đáp án: B*

**Câu 131:** Tại sao cần xác định 'Phạm vi' (Scope) dự án ngay từ pha Yêu cầu?
A. Để giới hạn tiền lương.
B. Để rạch ròi đường ranh giới những tính năng NÀO SẼ ĐƯỢC LÀM, và quan trọng không kém là những tính năng NÀO SẼ KHÔNG ĐƯỢC LÀM trong dự án này, tránh bị mập mờ.
C. Để chọn ngày nghỉ lễ.
D. Không cần thiết.
*Đáp án: B*

**Câu 132:** Nếu không có bước Khám phá yêu cầu, hậu quả hiển nhiên nhất là:
A. Phần mềm hoàn thành sớm hơn 10 lần.
B. Sản phẩm làm ra giải quyết sai vấn đề, không ai dùng, lãng phí thời gian và tiền bạc.
C. Code sẽ chạy hoàn hảo.
D. Khách hàng cho thêm tiền.
*Đáp án: B*

**Câu 133:** Yêu cầu 'Hệ thống phải có khả năng sao lưu dữ liệu tự động vào 23:00 hằng ngày' là yêu cầu:
A. Phi chức năng.
B. Chức năng (Một hành vi cụ thể hệ thống phải làm).
C. Yêu cầu về người dùng.
D. Không phải là yêu cầu.
*Đáp án: B*

**Câu 134:** Thuật ngữ 'Glossary' (Bảng thuật ngữ) trong tài liệu SRS dùng để làm gì?
A. Định nghĩa các từ vựng chuyên ngành nghiệp vụ, viết tắt để mọi người (khách hàng, kỹ sư) đều hiểu chung một nghĩa thống nhất, tránh hiểu lầm.
B. Liệt kê tên lập trình viên.
C. Là danh sách lỗi.
D. Liệt kê giá tiền phần mềm.
*Đáp án: A*

**Câu 135:** Hoạt động 'Mô hình hóa yêu cầu' (Requirements Modeling) chuyển đổi yêu cầu văn bản thành gì?
A. Thành âm thanh.
B. Thành các biểu đồ trực quan (như Use-case, Activity diagram, Data Flow Diagram) để dễ hiểu luồng dữ liệu và logic.
C. Thành mã nguồn chạy được.
D. Thành cơ sở dữ liệu vật lý.
*Đáp án: B*

**Câu 136:** Yêu cầu 'Hệ thống phải được viết bằng Java và chạy trên máy chủ Linux' thuộc loại yêu cầu gì?
A. Yêu cầu chức năng nghiệp vụ.
B. Ràng buộc thiết kế / Yêu cầu môi trường vận hành (Design/Environment Constraints).
C. Yêu cầu hiệu năng.
D. Sở thích của khách hàng.
*Đáp án: B*

**Câu 137:** Công việc của 'Requirements Manager' (Quản trị yêu cầu) sử dụng công cụ CASE như Jira, RequisitePro để làm gì?
A. Chơi game trong giờ làm.
B. Lưu trữ các yêu cầu, theo dõi các phiên bản thay đổi, kiểm soát quyền phê duyệt, và duy trì các liên kết truy vết (traceability links) tới mã nguồn/test case.
C. Gõ văn bản Word nhanh hơn.
D. Viết mã nguồn tự động.
*Đáp án: B*

**Câu 138:** Khái niệm 'Người dùng cuối' (End-user) khác với 'Khách hàng' (Client/Customer) ở điểm nào?
A. Giống hệt nhau.
B. Khách hàng là người trả tiền mua phần mềm (có thể không dùng). Người dùng cuối là người trực tiếp thao tác với phần mềm hằng ngày.
C. Người dùng cuối là người trả tiền.
D. Khách hàng làm ra phần mềm.
*Đáp án: B*

**Câu 139:** Tại sao 'Kiểm thử hộp đen' (Black-box testing) lại gắn liền chặt chẽ với Tài liệu Đặc tả Yêu cầu (SRS)?
A. Vì hộp đen có màu đen.
B. Vì Kiểm thử hộp đen chỉ dựa trên Đặc tả Yêu cầu (Đầu vào -> Đầu ra mong đợi) để kiểm tra xem phần mềm có thỏa mãn tính năng đã cam kết hay không mà không nhìn vào Code.
C. Vì hộp đen là tên phần mềm.
D. Vì nó dễ làm hơn.
*Đáp án: B*

**Câu 140:** Nếu tài liệu Yêu cầu mâu thuẫn (Inconsistent), lập trình viên thường sẽ phản ứng thế nào?
A. Họ sẽ viết ra 2 phiên bản.
B. Họ phải đoán mò ý khách hàng, hoặc tự quyết định chọn 1 phương án theo ý mình, rất dễ dẫn đến làm sai nghiệp vụ thực tế.
C. Họ sẽ bỏ việc.
D. Họ tự động sửa lại SRS.
*Đáp án: B*

**Câu 141:** Trong biểu đồ Use-case, Actor (Tác nhân) KHÔNG được phép có mối quan hệ gì với Actor khác?
A. Actor có thể kế thừa (Generalization) Actor khác.
B. Actor có thể gọi <<include>> Actor khác (Sai: Quan hệ include chỉ dành cho 2 Use-case).
C. Actor không tương tác với hệ thống.
D. Actor luôn là con người.
*Đáp án: B*

**Câu 142:** Tác nhân 'Hệ thống tính thuế bên thứ 3' (Third-party Tax System) là loại Actor gì?
A. Actor chính (Primary Actor - Người chủ động yêu cầu).
B. Actor phụ / Hệ thống hỗ trợ (Secondary Actor - Hệ thống được phần mềm của chúng ta gọi đến để lấy/xử lý dữ liệu).
C. Không phải Actor.
D. Là Use-case.
*Đáp án: B*

**Câu 143:** Mối quan hệ 'Association' (Kết hợp) trong biểu đồ Use-case là:
A. Là kế thừa.
B. Là đường thẳng nối giữa Actor và Use-case, biểu thị việc Actor đó tham gia tương tác với Use-case.
C. Là dấu chấm hỏi.
D. Là quan hệ bao hàm.
*Đáp án: B*

**Câu 144:** Khi lập trình viên nói: 'Yêu cầu này không khả thi (infeasible) để thực hiện', nguyên nhân có thể do:
A. Hết cà phê.
B. Yêu cầu vượt quá giới hạn công nghệ hiện tại (Ví dụ: Dự báo tương lai chính xác 100%), rào cản vật lý, hoặc chi phí/thời gian cho phép.
C. Khách hàng đổi ý.
D. Phần cứng chạy quá chậm.
*Đáp án: B*

**Câu 145:** Điều gì tạo nên một 'Yêu cầu Tốt' (Good Requirement)?
A. Rõ ràng, không mập mờ, nhất quán, đầy đủ, khả thi, đo lường/kiểm thử được và có khả năng truy vết.
B. Viết càng dài càng tốt.
C. Chỉ cần sếp đồng ý.
D. Dùng thật nhiều thuật ngữ phức tạp.
*Đáp án: A*

**Câu 146:** Một 'Ràng buộc phi chức năng' ví dụ như: 'Chỉ nhân viên có quyền Quản lý mới được xóa dữ liệu' thuộc danh mục nào?
A. Khả năng mở rộng.
B. Bảo mật và Phân quyền (Security & Authorization).
C. Hiệu năng.
D. Tính dễ sử dụng.
*Đáp án: B*

**Câu 147:** Hoạt động 'Phân tích yêu cầu' thường tạo ra các mô hình (models). Việc này giúp ích gì?
A. Làm tốn giấy in.
B. Giúp phát hiện sự không hoàn chỉnh, mâu thuẫn trong logic nghiệp vụ dễ dàng hơn so với việc đọc hàng trăm trang văn bản chữ.
C. Để chương trình chạy nhanh hơn.
D. Không có lợi ích gì.
*Đáp án: B*

**Câu 148:** Tài liệu Yêu cầu (SRS) có cần bảo trì không?
A. Không, viết xong là vứt.
B. Có, nó là một tài liệu 'sống', phải được quản lý cấu hình và cập nhật liên tục song song với sự tiến hóa của mã nguồn và dự án.
C. Chỉ bảo trì khi khách trả thêm tiền.
D. Không ai quan tâm.
*Đáp án: B*

**Câu 149:** Ai là người chịu rủi ro cao nhất nếu tài liệu SRS bị viết sai?
A. Khách hàng.
B. Lập trình viên.
C. Nhóm phát triển phần mềm (Thường phải làm lại miễn phí nếu hiểu sai ý, hoặc khách hàng từ chối nghiệm thu, gây thiệt hại nghiêm trọng về chi phí).
D. Nhà mạng.
*Đáp án: C*

**Câu 150:** Khái niệm 'Kỹ sư Yêu cầu' (Requirements Engineer) là gì?
A. Người bảo vệ máy chủ.
B. Người chuyên nghiệp trong việc thu thập, phân tích, đặc tả, thương lượng và quản lý các yêu cầu của dự án phần mềm.
C. Kỹ sư xây dựng.
D. Người viết mã nguồn duy nhất.
*Đáp án: B*

**Câu 151:** Trong RUP, để mô tả chi tiết một luồng xử lý bên trong Use-case, người ta thường dùng tài liệu gì?
A. Giao diện màn hình.
B. Bản Đặc tả Use-case (Use-case Specification) bao gồm: Tiền điều kiện, Luồng cơ bản, Luồng rẽ nhánh, Hậu điều kiện.
C. Mã nguồn C#.
D. Sơ đồ mạng.
*Đáp án: B*

**Câu 152:** Hoạt động 'Duyệt xét yêu cầu' (Requirement Review) thường được thực hiện theo hình thức nào?
A. Một người tự đọc.
B. Tổ chức cuộc họp chính thức (Formal meeting) với các bên liên quan (Khách hàng, BA, Tester, Developer) để đọc và chất vấn từng dòng yêu cầu tìm lỗi.
C. Chạy test tự động.
D. Ngồi uống cà phê.
*Đáp án: B*

**Câu 153:** Lý do chính khiến việc 'Khám phá yêu cầu' (Elicitation) không thể kết thúc trong 1 lần gặp mặt là:
A. Vì công ty xa nhau.
B. Khách hàng thường phát sinh ý tưởng mới hoặc nhận ra điều mình thực sự cần khi dự án tiến triển, và yêu cầu nghiệp vụ thực tế có tính biến động (Volatility).
C. Vì lập trình viên không hiểu ngôn ngữ.
D. Vì phần cứng hỏng.
*Đáp án: B*

**Câu 154:** Tính 'Khả năng đọc hiểu' (Readability) của SRS rất quan trọng vì:
A. Vì máy tính không đọc được.
B. Tài liệu này được đọc bởi nhiều thành phần khác nhau, từ người không có chuyên môn kỹ thuật (Khách hàng, Giám đốc) đến kỹ sư chuyên sâu.
C. Vì nó dài.
D. Vì không ai đọc.
*Đáp án: B*

**Câu 155:** Đâu là lợi ích của việc ghi rõ 'Nguồn gốc' (Source) của mỗi yêu cầu trong SRS?
A. Tính tiền khách hàng dễ hơn.
B. Khi có xung đột hoặc cần làm rõ, ta biết chính xác phải liên hệ với ai hoặc bộ phận nào đã đưa ra yêu cầu đó.
C. Làm tài liệu đẹp hơn.
D. Máy tính biên dịch tốt hơn.
*Đáp án: B*

**Câu 156:** Thuộc tính 'Rõ ràng, không mập mờ' (Unambiguous) của yêu cầu giúp ngăn chặn hiện tượng gì?
A. Hết dung lượng đĩa.
B. Sự diễn giải sai lệch (Developer hiểu một đằng, Khách hàng hiểu một nẻo) dẫn đến sản phẩm bị từ chối.
C. Giao diện bị xấu.
D. Mạng bị chậm.
*Đáp án: B*

**Câu 157:** Đâu là công cụ CASE thường được dùng để vẽ biểu đồ Use-case và quản lý mô hình yêu cầu?
A. Microsoft Paint.
B. Rational Rose, Enterprise Architect, Visual Paradigm, StarUML.
C. Microsoft Excel.
D. Windows Notepad.
*Đáp án: B*

**Câu 158:** Mức độ ưu tiên 'Must-have' trong phân loại yêu cầu (ví dụ: MoSCoW) có ý nghĩa gì?
A. Nên có nhưng không bắt buộc.
B. Là những yêu cầu bắt buộc, sống còn, nếu thiếu nó thì hệ thống hoàn toàn không có giá trị và không thể nghiệm thu.
C. Làm cuối cùng.
D. Dành cho bản cập nhật năm sau.
*Đáp án: B*

**Câu 159:** Mức độ ưu tiên 'Nice-to-have' (Nên có) trong phân loại yêu cầu có ý nghĩa gì?
A. Không bao giờ làm.
B. Là tính năng tốt, làm tăng sự hài lòng, nhưng nếu ngân sách hoặc thời gian bị ép, có thể bị cắt bỏ mà không làm hệ thống sập.
C. Bắt buộc phải làm trước.
D. Là tính năng quan trọng nhất.
*Đáp án: B*

**Câu 160:** Sự thay đổi một yêu cầu (Change Request) cần trải qua quy trình đánh giá tác động để làm gì?
A. Hủy bỏ dự án ngay.
B. Đo lường mức độ ảnh hưởng đến kiến trúc, thời gian, chi phí và nguồn lực trước khi quyết định đồng ý thay đổi hay không.
C. Mắng mỏ khách hàng.
D. Giảm lương lập trình viên.
*Đáp án: B*

**Câu 161:** Kỹ thuật 'Nguyên mẫu giao diện' (UI Mockups / Wireframes) giúp lấy yêu cầu rất tốt vì:
A. Vì nó dễ lập trình.
B. Con người thường tiếp thu hình ảnh (Visuals) dễ hơn văn bản chữ, giúp khách hàng tưởng tượng rõ ràng cách họ sẽ tương tác với hệ thống.
C. Vì nó đắt tiền.
D. Vì nó chạy được luôn.
*Đáp án: B*

**Câu 162:** Yêu cầu 'Hệ thống phải tuân thủ chuẩn kế toán Việt Nam 200' là loại yêu cầu nào?
A. Yêu cầu phần cứng.
B. Yêu cầu miền / Pháp lý (Domain / Regulatory constraints).
C. Yêu cầu về màu sắc.
D. Yêu cầu bảo trì.
*Đáp án: B*

**Câu 163:** Yêu cầu 'Mã nguồn hệ thống phải được viết rõ ràng, có comment và thiết kế theo mô hình MVC' là yêu cầu:
A. Phi chức năng (Khả năng bảo trì / Maintainability).
B. Chức năng.
C. Yêu cầu kinh doanh.
D. Yêu cầu pháp lý.
*Đáp án: A*

**Câu 164:** Mục tiêu của 'Phân tích Yêu cầu' là xây dựng một 'Mô hình khái niệm' (Conceptual Model) mô tả:
A. Giải pháp công nghệ chi tiết (Code bằng ngôn ngữ gì).
B. Bản chất của bài toán nghiệp vụ (Problem domain), cấu trúc dữ liệu và các luồng chức năng độc lập với nền tảng công nghệ (Solution independent).
C. Màu sắc của web.
D. Giá của phần cứng.
*Đáp án: B*

**Câu 165:** Thuộc tính 'Chính xác' (Correctness) của SRS được xác định bằng cách nào?
A. Chạy phần mềm.
B. Được chính khách hàng hoặc người đại diện nghiệp vụ (Domain expert) phê duyệt và xác nhận là mô tả đúng ý định của họ.
C. Hỏi lập trình viên.
D. Đo bằng máy tính.
*Đáp án: B*

**Câu 166:** Trong quy trình lấy yêu cầu, một 'Kịch bản' (Scenario) tốt cần bao gồm những gì?
A. Chỉ có dòng kết luận.
B. Bối cảnh (Tình trạng ban đầu), Luồng sự kiện chính, Các sự kiện ngoại lệ, và Trạng thái cuối cùng của hệ thống.
C. Chỉ có tên người dùng.
D. Mã nguồn thuật toán.
*Đáp án: B*

**Câu 167:** Khi khách hàng đưa ra yêu cầu: 'Tôi muốn một ứng dụng giống hệt Facebook', cách xử lý đúng của kỹ sư yêu cầu là gì?
A. Viết code ngay lập tức.
B. Sử dụng các kỹ thuật phân tích (Phỏng vấn, Câu hỏi) để 'khai quật' (elicit) chính xác các tính năng cốt lõi khách hàng thực sự cần, thay vì một mô tả quá chung chung và phi thực tế.
C. Từ chối luôn.
D. Yêu cầu khách hàng nộp 1 tỷ.
*Đáp án: B*

**Câu 168:** Vì sao Yêu cầu hệ thống cần được đánh số định danh duy nhất (Unique ID)?
A. Cho đẹp mắt.
B. Để dễ dàng tham chiếu, truy vết (Traceability) trong các tài liệu thiết kế, test case và khi quản lý sự thay đổi.
C. Để máy tính tự lập trình.
D. Tránh lỗi chính tả.
*Đáp án: B*

**Câu 169:** Khi nhiều Tác nhân (Actor) có chung một hành vi tương tác với hệ thống, ta có thể dùng thiết kế gì trong biểu đồ Use-case?
A. Xóa các Actor đi.
B. Sử dụng quan hệ Kế thừa (Generalization) giữa các Actor để tránh vẽ lặp lại Use-case (VD: Khách hàng và Quản trị viên đều kế thừa từ 'Người dùng đăng nhập').
C. Vẽ thêm 100 đường nối.
D. Biến Actor thành hệ thống.
*Đáp án: B*

**Câu 170:** Yêu cầu phi chức năng về 'Khả năng sử dụng' (Usability) thường được đo lường bằng gì?
A. Dung lượng ổ cứng.
B. Thời gian học cách dùng phần mềm, số lần thao tác nhầm của người dùng mới, và thời gian thực hiện xong 1 tác vụ.
C. Số lượng lập trình viên.
D. Bảo mật của hệ thống.
*Đáp án: B*

**Câu 171:** Sự khác biệt giữa 'Xác minh' (Verification) và 'Thẩm định' (Validation) yêu cầu là:
A. Xác minh: Tài liệu có đúng chuẩn định dạng, cấu trúc không? Thẩm định: Tài liệu có phản ánh đúng nhu cầu thực sự của khách hàng không?
B. Không khác nhau.
C. Xác minh là viết code, Thẩm định là viết tài liệu.
D. Thẩm định là cài hệ điều hành.
*Đáp án: A*

**Câu 172:** Yêu cầu 'Dữ liệu không được phép bị mất khi mất điện đột ngột' là:
A. Yêu cầu chức năng.
B. Yêu cầu phi chức năng về Độ tin cậy / Khả năng phục hồi (Reliability/Recoverability).
C. Yêu cầu giao diện.
D. Không có ý nghĩa.
*Đáp án: B*

**Câu 173:** Nếu không có công cụ Quản lý Yêu cầu (RM Tools) trong một dự án siêu lớn, điều gì dễ xảy ra?
A. Mọi thứ vẫn ổn.
B. Sự hỗn loạn do hàng ngàn yêu cầu thay đổi, không biết code này phục vụ yêu cầu nào, và tester không biết lấy gì để kiểm tra hệ thống.
C. Máy tính chạy nhanh hơn.
D. Khách hàng luôn vui vẻ.
*Đáp án: B*

**Câu 174:** Trong RUP, pha Inception coi việc xác định danh sách các 'Rủi ro rình rập' (Risks) liên quan đến yêu cầu là:
A. Không cần thiết.
B. Nhiệm vụ trọng tâm, nếu yêu cầu quá rủi ro về mặt khả thi công nghệ/nghiệp vụ, dự án có thể bị dừng.
C. Làm cuối cùng.
D. Chỉ tester mới làm.
*Đáp án: B*

**Câu 175:** Khi đặc tả Use-case: 'Hệ thống kiểm tra thông tin thẻ tín dụng của khách hàng thông qua Cổng thanh toán quốc tế'. Cổng thanh toán quốc tế đóng vai trò gì?
A. Use-case chính.
B. Tác nhân hệ thống hỗ trợ (Secondary Actor).
C. Giao diện người dùng.
D. Luồng ngoại lệ.
*Đáp án: B*

**Câu 176:** Một nhược điểm của tài liệu SRS viết hoàn toàn bằng văn bản tự do (Free-form text) là gì?
A. Quá ngắn.
B. Dễ gây mập mờ, hiểu nhầm, khó cấu trúc thông tin, và khó tự động hóa việc truy vết yêu cầu.
C. Màu sắc xấu.
D. Không in được.
*Đáp án: B*

**Câu 177:** Điều gì tạo nên sự thành công của một tài liệu SRS?
A. Được viết bằng font chữ đẹp.
B. Nó trở thành tiếng nói chung duy nhất, là nền tảng tin cậy cho cả đội ngũ kỹ thuật (để thiết kế, code, test) và khách hàng (để nghiệm thu).
C. Có dung lượng > 10GB.
D. Không bao giờ bị sửa đổi.
*Đáp án: B*

**Câu 178:** Đâu là rủi ro khi 'Cố định yêu cầu' (Requirement Freezing) quá sớm trong một môi trường kinh doanh biến động?
A. Lập trình viên rảnh rỗi.
B. Dự án phát triển một hệ thống mà khi ra mắt (sau 1 năm) nó đã trở nên lỗi thời, không còn phù hợp với nghiệp vụ mới của công ty.
C. Tăng lương cho nhân sự.
D. Làm máy tính chạy nhanh hơn.
*Đáp án: B*

**Câu 179:** Nguyên tắc 80/20 (Pareto) trong quản lý yêu cầu ngụ ý điều gì?
A. 80% code sai, 20% đúng.
B. Thường thì 20% các tính năng quan trọng nhất mang lại 80% giá trị cốt lõi của phần mềm (Nên ưu tiên tập trung làm 20% này trước trong mô hình Agile/Lặp).
C. 80% lập trình viên làm, 20% nghỉ.
D. 80% thời gian là ngủ.
*Đáp án: B*

**Câu 180:** Khi một Yêu cầu MỚI được khách hàng đưa ra giữa giai đoạn Lập trình (Coding), Quản lý dự án cần làm gì đầu tiên?
A. Lập tức bắt lập trình viên gõ code thêm vào.
B. Đánh giá tác động (Impact Analysis) của yêu cầu đó lên cấu trúc hiện tại, thời gian và chi phí, sau đó thương lượng với khách hàng trước khi quyết định.
C. Từ chối thẳng thừng.
D. Xóa hệ thống cũ.
*Đáp án: B*

**Câu 181:** Khái niệm 'Kỹ thuật viên Phân tích Hệ thống' (System Analyst) cần những kỹ năng chính nào?
A. Chỉ cần biết gõ phím.
B. Hiểu biết kỹ thuật (Software Engineering), kỹ năng giao tiếp tốt, tư duy phản biện, kỹ năng mô hình hóa (UML) và khả năng đàm phán.
C. Chỉ cần vẽ giao diện đồ họa.
D. Chỉ cần biết sửa lỗi mạng.
*Đáp án: B*

**Câu 182:** Yêu cầu 'Hệ thống phải có khả năng thêm mới, sửa, xóa, và xem thông tin Khách hàng' gọi chung là loại chức năng gì?
A. Trí tuệ nhân tạo.
B. Chức năng CRUD (Create, Read, Update, Delete) - Yêu cầu chức năng cơ bản.
C. Chức năng mạng LAN.
D. Yêu cầu phi chức năng.
*Đáp án: B*

**Câu 183:** Một Use-case có tên là 'Đăng nhập'. Luồng ngoại lệ (Exception Flow) có thể là gì?
A. Khách hàng nhập đúng tài khoản và vào hệ thống.
B. Người dùng nhập sai mật khẩu quá 3 lần, hệ thống khóa tài khoản và gửi email cảnh báo.
C. Trang web tải nhanh.
D. Màu nền của trang web.
*Đáp án: B*

**Câu 184:** Nếu không có bảng 'Glossary' (Thuật ngữ) trong dự án Y tế, 'Patient' (Bệnh nhân) có thể bị hiểu nhầm thành gì?
A. Bác sĩ.
B. Các bộ phận khác nhau hiểu khác nhau (Ví dụ: Hệ thống tài chính hiểu Patient là 'Người trả tiền', Bác sĩ hiểu là 'Người được điều trị'), dẫn đến xây CSDL sai lệch.
C. Bệnh viện.
D. Thuốc.
*Đáp án: B*

**Câu 185:** Theo quan điểm Agile, tài liệu yêu cầu (như User Story) được đặc trưng bởi:
A. Dài 500 trang.
B. Ngắn gọn, linh hoạt, đóng vai trò như 'Một lời hứa sẽ thảo luận chi tiết hơn' thay vì một bản hợp đồng thiết kế khô cứng.
C. Không bao giờ thay đổi.
D. Viết bằng mã C++.
*Đáp án: B*

**Câu 186:** Khái niệm 'User Story' (Câu chuyện người dùng) có cấu trúc chuẩn như thế nào?
A. Code -> Bug -> Fix.
B. 'Với tư cách là [Loại người dùng], tôi muốn [Tính năng], để tôi có thể đạt được [Mục tiêu/Giá trị]'.
C. Tôi cần phần mềm màu xanh.
D. Không có cấu trúc.
*Đáp án: B*

**Câu 187:** Một tài liệu SRS tốt giúp giảm chi phí bảo trì (Maintenance cost) như thế nào?
A. Bằng cách in SRS ra giấy.
B. Khi có lỗi hoặc cần mở rộng, người bảo trì đọc SRS để hiểu bản chất luồng nghiệp vụ gốc thay vì phải ngồi 'dò mìn' hàng vạn dòng code vô cảm.
C. Nó làm phần mềm tự vá lỗi.
D. Tester tự động bị đuổi việc.
*Đáp án: B*

**Câu 188:** Yêu cầu 'Mọi giao dịch thanh toán phải tuân theo chuẩn an ninh thẻ quốc tế PCI-DSS' là gì?
A. Yêu cầu về màu sắc.
B. Ràng buộc nghiệp vụ / Yêu cầu bảo mật pháp lý.
C. Yêu cầu chức năng.
D. Không phải yêu cầu.
*Đáp án: B*

**Câu 189:** Tại sao 'Kiểm thử hộp đen' cần dùng tài liệu Đặc tả (SRS) làm nền tảng?
A. Vì Tester không biết đọc.
B. Hộp đen chỉ quan tâm Input và Output. SRS chính là tài liệu định nghĩa Input vào phải ra Output gì. Tester dùng nó làm 'đáp án chuẩn' để thiết kế các Test case.
C. Vì hộp đen là tên phần mềm.
D. Vì Code bị mã hóa.
*Đáp án: B*

**Câu 190:** Khi lấy yêu cầu cho một Hệ thống Nhúng (Embedded System) như ABS của xe hơi, loại yêu cầu nào là TỐI QUAN TRỌNG?
A. Giao diện đẹp mắt.
B. Yêu cầu phi chức năng về Thời gian thực (Real-time response) và Độ tin cậy (Reliability/Safety-critical).
C. Giá tiền rẻ.
D. Nhiều màu sắc.
*Đáp án: B*

**Câu 191:** Kỹ thuật 'Tạo Bản mẫu' (Prototyping) trong giai đoạn yêu cầu thường tốn kém hơn nhưng lại tiết kiệm tiền cho dự án vì:
A. Bản mẫu bán được giá cao.
B. Nó xóa bỏ sự hiểu nhầm từ sớm. Chi phí sửa một lỗi ở giai đoạn lấy yêu cầu rẻ hơn gấp 10-100 lần việc sửa lỗi đó khi đã code xong.
C. Máy tính chạy bản mẫu nhanh hơn.
D. Lập trình viên không cần làm gì.
*Đáp án: B*

**Câu 192:** Trong quy trình phần mềm, pha 'Yêu cầu' là:
A. Pha cuối cùng.
B. Pha nền tảng đầu tiên, quyết định sự thành bại và định hướng mọi giai đoạn phía sau của toàn bộ dự án.
C. Chỉ có trên giấy.
D. Pha không cần thiết.
*Đáp án: B*

**Câu 193:** Sự xung đột (Conflict) yêu cầu giữa Giám đốc (Cần tiết kiệm tiền) và Nhân viên (Cần giao diện trực quan 3D tốn kém) sẽ được giải quyết ở bước nào?
A. Lập trình.
B. Thương lượng yêu cầu (Requirements Negotiation).
C. Kiểm thử bảo mật.
D. Chuyển giao hệ thống.
*Đáp án: B*

**Câu 194:** Kỹ thuật nào hữu ích nhất để hiểu quy trình làm việc HIỆN TẠI (As-Is) của khách hàng trước khi làm phần mềm mới?
A. Chạy test tự động.
B. Nghiên cứu tài liệu hiện có (văn bản, biểu mẫu cũ) và Quan sát thực địa (Ethnography) cách họ làm việc hằng ngày.
C. Vẽ giao diện UI 3D.
D. Thiết kế CSDL Oracle.
*Đáp án: B*

**Câu 195:** Theo định luật phân tích, 'Lỗi càng phát hiện muộn, chi phí sửa chữa càng...'
A. Giảm đi theo cấp số nhân.
B. Tăng lên theo cấp số nhân (hàm mũ).
C. Không đổi.
D. Bằng 0.
*Đáp án: B*

**Câu 196:** Hoạt động 'Kiểm soát phiên bản' (Version control) cho tài liệu SRS giúp ích gì?
A. Chống in lậu.
B. Lưu lại lịch sử thay đổi của yêu cầu, ai thay đổi, lúc nào và lý do; giúp nhóm luôn biết bản nào là bản cập nhật mới nhất đang có hiệu lực.
C. Tiết kiệm giấy.
D. Máy tính xử lý văn bản nhanh hơn.
*Đáp án: B*

**Câu 197:** Mức độ chi tiết của 'Yêu cầu người dùng' (User Requirements) thường là:
A. Mã giả (Pseudo-code) của thuật toán.
B. Phát biểu ở mức cao (High-level), bằng ngôn ngữ tự nhiên, tập trung vào dịch vụ hệ thống cung cấp phục vụ mục tiêu kinh doanh.
C. Cấu trúc bảng SQL chi tiết.
D. Kiến trúc server vật lý.
*Đáp án: B*

**Câu 198:** Mục tiêu cuối cùng của toàn bộ giai đoạn 'Kỹ nghệ yêu cầu' (Requirements Engineering) là:
A. Làm kiệt sức kỹ sư.
B. Tạo ra một bản Đặc tả Yêu cầu (SRS) chất lượng, được sự đồng thuận của mọi bên, làm nền tảng vững chắc cho thiết kế, thi công và kiểm thử hệ thống.
C. Viết được 10.000 dòng code.
D. Có được một bản demo giao diện.
*Đáp án: B*

**Câu 199:** Một chuyên viên BA (Business Analyst) giỏi cần có khả năng gì?
A. Chỉ cần biết lập trình.
B. Không chỉ ghi chép (như thư ký), mà phải biết 'khai quật', đặt câu hỏi Tại sao (Why), và phân tích để tìm ra cái khách hàng THỰC SỰ CẦN chứ không chỉ là cái họ NÓI HỌ MUỐN.
C. Không cần giao tiếp.
D. Chỉ vẽ hình.
*Đáp án: B*

**Câu 200:** Nếu SRS quá dài và khó đọc, một công cụ hữu ích để tóm tắt sự tương tác chức năng cho khách hàng xem là:
A. Mã nguồn Assembly.
B. Biểu đồ Use-case (Use-case Diagram) đi kèm với Kịch bản (Scenarios).
C. Biểu đồ Venn.
D. Lệnh SQL.
*Đáp án: B*
