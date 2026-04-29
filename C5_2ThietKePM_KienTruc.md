LOGO
KHOA KỸ THUẬT – CÔNG NGHỆ
Chương 5
THIẾT KẾ PHẦN MỀM
- KIẾN TRÚC
GV biên soạn: Trần Kim Hương
tkhuong@dthu.edu.vn
Software Engineering
tkhuong@dthu.edu.vn

NỘI DUNG
KHÁI NIỆM
KIẾN
TRÚC
CÁC MÔ HÌNH KIẾN TRÚC
PHẦN
MỀM
CÔNG NGHỆ PHÂN TÁN
Software Engineering 2
tkhuong@dthu.edu.vn

KHÁI NIỆM
❖ Thiết kế kiến trúc là mô tả một cách tổng thể các thành phần
| của phần | mềm, cụ |     | thể | hơn đó | là: |     |     |     |
| -------- | ------- | --- | --- | ------ | --- | --- | --- | --- |
▪ Quyết định về sự tồn tại của các thành phần cùng với công nghệ
| tương | ứng |     |     |     |     |     |     |     |
| ----- | --- | --- | --- | --- | --- | --- | --- | --- |
▪ Quyết định về cách thức liên kết/ kết nối giữa các thành phần
| ❖ Ghi chú:  |      |      |          |                      |            |         |          |      |
| ----------- | ---- | ---- | -------- | -------------------- | ---------- | ------- | -------- | ---- |
| ▪ Không     | đi   | vào  | chi tiết | của                  | từng thành | phần    |          |      |
| ▪ Cần       | chọn | công | nghệ     | thích                | hợp theo   | yêu cầu | phi chức | năng |
|             |      |      |          | Software Engineering |            |         |          | 3    |
tkhuong@dthu.edu.vn

NỘI DUNG
CÁC KHÁI NIỆM CƠ BẢN
KIẾN
TRÚC
CÁC MÔ HÌNH KIẾN TRÚC
PHẦN
MỀM
CÔNG NGHỆ PHÂN TÁN
Software Engineering 6
tkhuong@dthu.edu.vn

2. CÁC MÔ HÌNH KIẾN TRÚC
| ❖ Xét        | 4 dạng | mô hình | kiến    | trúc |
| ------------ | ------ | ------- | ------- | ---- |
| ❖ DẠNG 1: mô |        | hình    | đơn lập |      |
A
Giao diện
|     |     |     | Dữ  | liệu |
| --- | --- | --- | --- | ---- |
và Xử lý
Software Engineering 8
tkhuong@dthu.edu.vn

2. CÁC MÔ HÌNH KIẾN TRÚC
❖ DẠNG 2: mô hình Client-Server
A B
Mạng
Giao diện Giao diện
cục bộ
và Xử lý và Xử lý
HQT
Dữ liệu
CSDL
Software Engineering 9
tkhuong@dthu.edu.vn

2. CÁC MÔ HÌNH KIẾN TRÚC
❖
| DẠNG 3: Mô |     | hình | trung | chuyển |     |     |
| ---------- | --- | ---- | ----- | ------ | --- | --- |
|            | A   |      |       |        | B   |     |
USB,
| Giao diện |     |     |     |     | Giao diện |     |
| --------- | --- | --- | --- | --- | --------- | --- |
CD,
| và Xử | lý  |     |     |     | và Xử | lý  |
| ----- | --- | --- | --- | --- | ----- | --- |
Email
| phân hệ | A   |     |     |     | phân hệ | B   |
| ------- | --- | --- | --- | --- | ------- | --- |
| Dữ liệu |     |     |     |     | Dữ liệu |     |
Software Engineering 10
tkhuong@dthu.edu.vn

2. CÁC MÔ HÌNH KIẾN TRÚC
❖
| DẠNG 4: Mô | hình | 3 tầng |
| ---------- | ---- | ------ |
A B
Internet
Giao diện Giao diện
Dữ liệu
|     |     | Xử lý |
| --- | --- | ----- |
Software Engineering 11
tkhuong@dthu.edu.vn

NỘI DUNG
CÁC KHÁI NIỆM CƠ BẢN
KIẾN
TRÚC
CÁC MÔ HÌNH KIẾN TRÚC
PHẦN
MỀM
CÔNG NGHỆ PHÂN TÁN
Software Engineering 12
tkhuong@dthu.edu.vn

3. CÔNG NGHỆ PHÂN TÁN
❖
Middleware
| ▪ Các | thành                                             | phần | trong | hệ phân   | tán giao | tiếp thế | nào? |
| ----- | ------------------------------------------------- | ---- | ----- | --------- | -------- | -------- | ---- |
| →Hệ   | thống                                             | đứng | giữa  | điều phối |          |          |      |
| ▪ Các | chuẩn                                             | phổ  | biến  |           |          |          |      |
| •     | CORBA (Common Object Request Broker Architecture) |      |       |           |          |          |      |
| •     | COM (Component Object Model)                      |      |       |           |          |          |      |
| •     | JavaBeans                                         |      |       |           |          |          |      |
Software Engineering 13
tkhuong@dthu.edu.vn

| Hệ  | thống |     | phân |     | tán |
| --- | ----- | --- | ---- | --- | --- |
❖ Web Service
| ▪ Thư  | viện                                               | lập trình    | dựng | sẵn |     |
| ------ | -------------------------------------------------- | ------------ | ---- | --- | --- |
| ▪ Cung | cấp                                                | dạng         | dịch | vụ  |     |
| ▪ Truy | xuất                                               | qua internet |      |     |     |
| ▪ Các  | dịch                                               | vụ phổ       | biến |     |     |
| •      | Math services                                      |              |      |     |     |
| •      | Google map                                         |              |      |     |     |
| •      | Amazon services                                    |              |      |     |     |
| ▪ Các  | chuẩn                                              | giao         | tiếp | XML |     |
| •      | SOA (Simple Access Protocol)                       |              |      |     |     |
| •      | WSDL (Web Service Description Language)            |              |      |     |     |
| •      | UDDI (Universal Description Discovery and Integran |              |      |     |     |
Software Engineering 14
tkhuong@dthu.edu.vn

VD minh họa
| ❖ Mục  | tiêu: minh họa |         | hồ   | sơ thiết | kế   | (thiết kế tổng | thể) cho |
| ------ | -------------- | ------- | ---- | -------- | ---- | -------------- | -------- |
| ứng    | dụng           | nhỏ với | công | nghệ     | được | chọn:          |          |
| ▪ Giao | diện           | Console |      |          |      |                |          |
| ▪ Xử   | lý với         | đơn thể |      |          |      |                |          |
Software Engineering 15
tkhuong@dthu.edu.vn

VD minh họa
Đề bài:
| ❖ Xét       | ứng  | dụng | rèn luyện | bài                  | tập     | về Giải  | phương     | trình | bậc |
| ----------- | ---- | ---- | --------- | -------------------- | ------- | -------- | ---------- | ----- | --- |
| 2(với       | phần | mềm  | đóng      | vai                  | trò của | Giáo     | viên). Hãy | phân  |     |
| tích, thiết |      | kế   | với công  | nghệ                 | Giao    | diện     | Console và | Xử    | lý  |
| dùng        | đơn  | thể  |           |                      |         |          |            |       |     |
|             | PHÂN | TÍCH |           |                      |         | THIẾT KẾ |            |       |     |
|             |      |      |           | Software Engineering |         |          |            |       | 16  |
tkhuong@dthu.edu.vn

VD minh họa
| ❖ Thiết kế |         |       |       |      |
| ---------- | ------- | ----- | ----- | ---- |
| ▪ Thiết    | kế tổng | thể   |       |      |
| ▪ Thiết    | kế giao | diện  | người | dùng |
| ▪ Thiết    | kế hệ   | thống | xử lý |      |
Học sinh
Giao diện
và Xử lý
Software Engineering 17
tkhuong@dthu.edu.vn

BÀI TẬP 1
| ❖ Đề | bài | 1   |     |     |     |     |     |     |     |
| ---- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
▪
|     | Xét | phần | mềm Quản | lý nhân | sự với | yêu cầu | chính | là tra cứu | hồ  |
| --- | --- | ---- | -------- | ------- | ------ | ------- | ----- | ---------- | --- |
sơ nhân viên dựa trên họ tên. Hãy phân tích, thiết kế với công
|      | nghệ      | giao    | diện Console, xử |                | lý dùng | đơn thể                | và lưu | trữ dùng |     |
| ---- | --------- | ------- | ---------------- | -------------- | ------- | ---------------------- | ------ | -------- | --- |
|      | CSDL quan |         | hệ               |                |         |                        |        |          |     |
| Phân | tích:     |         |                  |                |         |                        |        |          |     |
| → Vẽ | sơ đồ     | UseCase | các              | chức năng, đặc |         | tả UseCase, Activity,  |        |          |     |
Sequence
| Thiết | kế: |     |     |     |     |     |     |     |     |
| ----- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
→ ???
| → Thiết | kế  | tổng | thể??? |                      |     |     |     |     |     |
| ------- | --- | ---- | ------ | -------------------- | --- | --- | --- | --- | --- |
|         |     |      |        | Software Engineering |     |     |     |     | 18  |
tkhuong@dthu.edu.vn

BÀI TẬP 2
| ❖ Đề | bài | 2   |     |     |     |     |     |     |
| ---- | --- | --- | --- | --- | --- | --- | --- | --- |
▪
|     | Xét | phần mềm | Quản lý | thu chi với | yêu cầu | chính | là thống | kê  |
| --- | --- | -------- | ------- | ----------- | ------- | ----- | -------- | --- |
doanh thu theo tháng. Hãy phân tích, thiết kế với công nghệ giao
diện Console, xử lý dùng đơn thể và lưu trữ dùng CSDL quan hệ
| Phân | tích:  |         |          |           |                        |     |     |     |
| ---- | ------ | ------- | -------- | --------- | ---------------------- | --- | --- | --- |
| → Vẽ | sơ đồ  | UseCase | các chức | năng, đặc | tả UseCase, Activity,  |     |     |     |
Sequence
| Thiết | kế: |     |     |     |     |     |     |     |
| ----- | --- | --- | --- | --- | --- | --- | --- | --- |
→ ???
| → Thiết | kế  | tổng thể??? |     |     |     |     |     |     |
| ------- | --- | ----------- | --- | --- | --- | --- | --- | --- |
Software Engineering 19
tkhuong@dthu.edu.vn

| Câu | hỏi | thảo | luận |
| --- | --- | ---- | ---- |
Questions
Software Engineering 22
tkhuong@dthu.edu.vn