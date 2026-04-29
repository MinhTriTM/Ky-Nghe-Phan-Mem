LOGO
KHOA KỸ THUẬT – CÔNG NGHỆ
Chương 5
THIẾT KẾ PHẦN MỀM
– GIAO DIỆN
GV biên soạn: Trần Kim Hương
tkhuong@dthu.edu.vn
Software Engineering
tkhuong@dthu.edu.vn

NỘI DUNG CHI TIẾT
GIAO DIỆN NGƯỜI DÙNG (UI)
THIẾT KẾ
PHẦN
THIẾT KẾ GIAO DIỆN NGƯỜI DÙNG
MỀM -
GIAO
XỬ LÝ GIAO DIỆN NGƯỜI DÙNG
DIỆN
THIẾT KẾ XỬ LÝ GIAO DIỆN NGƯỜI DÙNG
Software Engineering 2
tkhuong@dthu.edu.vn

1. GIAO DIỆN NGƯỜI DÙNG
❖ VAI TRÒ CỦA GIAO DIỆN
❖ GIAO DIỆN NGƯỜI DÙNG (UI)
Software Engineering 4
tkhuong@dthu.edu.vn

1.1 VAI TRÒ CỦA GIAO DIỆN
❖ Phần mềm không hoạt động độc lập
❖ Phần mềm giao tiếp với
▪ Người sử dụng
▪ Các hệ thống liên quan
❖ Cần thành phần phụ trách giao tiếp?
→ Giao diện
▪ Nơi diễn ra tương tác
▪ Định nghĩa cách thức giao tiếp
▪ Tiếp nhận và phản hồi thông tin
Software Engineering 5
tkhuong@dthu.edu.vn

|           | 1.2 Giao |      | diện | người | dùng | (UI) |
| --------- | -------- | ---- | ---- | ----- | ---- | ---- |
| ❖ Ý nghĩa | sử       | dụng |      |       |      |      |
| ❖ Cấu     | trúc tổ  | chức |      |       |      |      |
| ❖ Công    | nghệ     | giao | diện |       |      |      |
Software Engineering 7
tkhuong@dthu.edu.vn

| 1.2 Giao |               | diện | người | dùng             | (UI) |
| -------- | ------------- | ---- | ----- | ---------------- | ---- |
| HỆ       | THỐNG THỰC TẾ |      |       | HỆ THỐNG TIN HỌC |      |
| X thực   | hiện nghiệp   | vụ   |       | X                | Y    |
f1, f2, …
|        |             |     |     | Thành | phần |
| ------ | ----------- | --- | --- | ----- | ---- |
| Y thực | hiện nghiệp | vụ  |     |       |      |
giao diện
g1, g2, ….
Software Engineering 8
tkhuong@dthu.edu.vn

|         |       | 1.2 UI –  |      |        |       | Ý nghĩa |         |      |      | sử       |      | dụng  |       |     | (1)     |
| ------- | ----- | --------- | ---- | ------ | ----- | ------- | ------- | ---- | ---- | -------- | ---- | ----- | ----- | --- | ------- |
| ❖       | Thành |           | phần |        | của   |         | phần    |      | mềm  | cho      | phép |       | người |     | sử dụng |
|         | thực  | hiện      |      | nghiệp |       |         | vụ      | với  | phần | mềm      |      | thông |       | qua |         |
|         | ▪     | Cung      |      | cấp    | thông |         | tin/ dữ |      | liệu | cho      | phần |       | mềm   |     |         |
|         | ▪     | Nhận/ xem |      |        |       | các     | kết     | quả  | xử   | lý tượng |      | ứng   |       |     |         |
| ==> Xem |       |           | xét  |        | tính  | tiện    |         | dụng |      |          |      |       |       |     |         |
Software Engineering 9
tkhuong@dthu.edu.vn

|     |     | 1.2 UI – |     |     |     |     | Cấu |     | trúc |     | tổ  | chức |     |     | (2) |     |
| --- | --- | -------- | --- | --- | --- | --- | --- | --- | ---- | --- | --- | ---- | --- | --- | --- | --- |
❖
|          | Màn |      | hình  |        | giao |      | diện:   |       |       |     |            |      |      |      |            |     |
| -------- | --- | ---- | ----- | ------ | ---- | ---- | ------- | ----- | ----- | --- | ---------- | ---- | ---- | ---- | ---------- | --- |
| Thành    |     |      | phần  |        | giao |      | diện    | trong |       | hệ  | thống      | bao  |      | gồm  | các màn    |     |
| hình     |     | giao |       | diện   |      | cho  | phép    |       | người |     | dùng       | thực |      | hiện | các nghiệp |     |
| vụ       | với |      | phần  |        | mềm  |      |         |       |       |     |            |      |      |      |            |     |
| ==> Mỗi  |     |      |       | màn    |      | hình | giao    |       | diện  | cho | phép       | thực |      | hiện | đúng       | 1   |
| nghiệp   |     |      | vụ??? |        |      |      |         |       |       |     |            |      |      |      |            |     |
| == > Mỗi |     |      |       | nghiệp |      |      | vụ thực |       | hiện  |     | trên 1 màn |      | hình |      | duy nhất   | ??? |
Software Engineering 10
tkhuong@dthu.edu.vn

| VD1. UI – |     | Cấu | trúc |     | tổ chức |     |     |
| --------- | --- | --- | ---- | --- | ------- | --- | --- |
❖
| VD minh họa | màn | hình | giao | diện | pm Quản | lý nhân | sự  |
| ----------- | --- | ---- | ---- | ---- | ------- | ------- | --- |
MH_DANG_KY
MH_QLNS MH_BGĐ
MH_TNHS MH_CNCT
MH_CN_XHS
MH_TCHS
Software Engineering 11
tkhuong@dthu.edu.vn

|        |       |      | 1.2 UI – |       |         |      | Cấu   |      | trúc |       | tổ    | chức    |      | (2)     |       |       |
| ------ | ----- | ---- | -------- | ----- | ------- | ---- | ----- | ---- | ---- | ----- | ----- | ------- | ---- | ------- | ----- | ----- |
| ❖      | Đối   |      | tượng    |       | giao    |      | diện: |      |      |       |       |         |      |         |       |       |
| Màn    |       | hình |          | giao  |         | diện | bao   |      | gồm  | bên   | trong |         | các  | đối     | tượng | giao  |
| diện   |       | cho  |          | phép  |         | thể  | hiện  | các  |      | thông |       | tin/ dữ | liệu | tương   |       | ứng   |
| nghiệp |       |      | vụ       | đang  |         | xét  |       |      |      |       |       |         |      |         |       |       |
| →      | Mỗi   |      | đối      | tượng |         | giao |       | diện | thể  | hiện  |       | với     | đúng | 1 thông |       | tin/  |
|        | dữ    |      | liệu???  |       |         |      |       |      |      |       |       |         |      |         |       |       |
| →      |       | Mỗi  | thông    |       | tin/ dữ |      |       | liệu | được | thể   |       | hiện    | với  | đúng    | 1 đối |       |
|        | tượng |      |          | giao  | diện    |      | ???   |      |      |       |       |         |      |         |       |       |
Software Engineering 12
tkhuong@dthu.edu.vn

|      | VD2. UI –   |                  |           | Cấu  |       | trúc |      | tổ chức |          |      |
| ---- | ----------- | ---------------- | --------- | ---- | ----- | ---- | ---- | ------- | -------- | ---- |
| ❖ Ví | dụ minh họa |                  | các       | đối  | tượng |      | giao | diện    | trên màn | hình |
| Tiếp | nhận        | hồ sơ            |           | nhân | viên  |      |      |         |          |      |
|      |             |                  |           | Tiếp | nhận  | hồ   | sơ   | mới     |          |      |
|      |             | Mã số: ********* |           |      |       |      |      | Nam     | Nữ       |      |
|      |             | Họ và            | tên: ………. |      |       |      |      |         |          |      |
|      |             | Ngày             | sinh: ……… |      |       |      |      |         |          |      |
Địa chỉ: …………..
…………………….
|     |     |     |     | Ghi |     |     |     | Kết thúc |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | -------- | --- | --- |
Software Engineering 13
tkhuong@dthu.edu.vn

1.2 UI – Công nghệ giao diện (3)
GIAO DIỆN
CONSOLE
GIAO DIỆN ĐIỆN
THOẠI DI ĐỘNG
GIAO DIỆN
WINDOW
GIAO DIỆN
……
GIAO DIỆN
WEB
Software Engineering 14
tkhuong@dthu.edu.vn

GIAO DIỆN CONSOLE
| ❖ Cấu |      | trúc    |       |      |           |        |       |       |       |      |       |      |          |     |
| ----- | ---- | ------- | ----- | ---- | --------- | ------ | ----- | ----- | ----- | ---- | ----- | ---- | -------- | --- |
| ▪     | Màn  |         | hình  | giao | diện: chỉ |        | gồm   | một   | màn   |      | hình  | giao | diện     | duy |
|       | nhất |         | chung | cho  | mọi       | nghiệp |       | vụ    |       |      |       |      |          |     |
| ▪     | Đối  | tượng   |       | giao | diện: gồm |        |       | 2 đối | tượng |      | giao  | diện | cơ       | bản |
|       | •    | Đối     | tượng |      | tiếp nhận |        | thông | tin   |       |      |       |      |          |     |
|       | •    | Đối     | tượng |      | kết xuất  | thông  |       | tin   |       |      |       |      |          |     |
| ❖ Đặc | điểm |         |       |      |           |        |       |       |       |      |       |      |          |     |
| ▪     | Dễ   | học, dễ |       | sử   | dụng      | nhưng  |       | khó   | thể   | hiện | thông |      | tin dạng | tự  |
nhiên
| →   | thiếu |     | tính | tiện | dụng |                      |     |     |     |     |     |     |     |     |
| --- | ----- | --- | ---- | ---- | ---- | -------------------- | --- | --- | --- | --- | --- | --- | --- | --- |
|     |       |     |      |      |      | Software Engineering |     |     |     |     |     |     |     | 15  |
tkhuong@dthu.edu.vn

GIAO DIỆN WINDOWS
❖ Cấu trúc
▪ Màn hình giao diện: cho phép sử dụng nhiều màn hình giao diện với
| số  | lượng | tùy theo | người | thiết | kế  |     |     |     |
| --- | ----- | -------- | ----- | ----- | --- | --- | --- | --- |
▪ Đối tượng giao diện: gồm nhiều và đa dạng các đối tượng giao diện
• Đối tượng giao diện thư viện do môi trường lập trình cung cấp
• Đối tượng giao diện tự định nghĩa do các chuyên viên tin học thiết kế và
|     | thực | hiện dựa | trên | các đối | tượng | giao diện | đã có |     |
| --- | ---- | -------- | ---- | ------- | ----- | --------- | ----- | --- |
❖ Đặc điểm
| ▪ Cho phép |     | thể | hiện | thông tin dạng |     | tự nhiên | nhất có | thể |
| ---------- | --- | --- | ---- | -------------- | --- | -------- | ------- | --- |
▪ Cần nhiều thời gian để học và tận dụng các khả năng của đối tượng
| giao | diện | người | dùng |     |     |     |     |     |
| ---- | ---- | ----- | ---- | --- | --- | --- | --- | --- |
Software Engineering 16
tkhuong@dthu.edu.vn

GIAO DIỆN WEB
❖ Cấu trúc
▪ Màn hình giao diện: cho phép sử dụng nhiều màn hình giao diện với
| số  | lượng | tùy theo | người | thiết kế |     |     |     |
| --- | ----- | -------- | ----- | -------- | --- | --- | --- |
▪ Đối tượng giao diện: gồm nhiều và đa dạng các đối tượng giao diện
• Đối tượng giao diện thư viện do môi trường lập trình cung cấp
• Đối tượng giao diện tự định nghĩa do các chuyên viên tin học thiết kế và
|     | thực | hiện dựa | trên các | đối tượng | giao diện | đã có |     |
| --- | ---- | -------- | -------- | --------- | --------- | ----- | --- |
❖ Đặc điểm
| ▪ Cho phép |     | thể hiện | thông | tin dạng | tự nhiên | nhất có | thể |
| ---------- | --- | -------- | ----- | -------- | -------- | ------- | --- |
▪ Chuẩn hóa: HTML/ XHTML là ngôn ngữ thống nhất chung mô tả các
| đối    | tượng | giao diện | người | dùng |     |     |     |
| ------ | ----- | --------- | ----- | ---- | --- | --- | --- |
| → Tính | mang  | chuyển    |       |      |     |     |     |
Software Engineering 17
tkhuong@dthu.edu.vn

NỘI DUNG CHI TIẾT
GIAO DIỆN NGƯỜI DÙNG (UI)
THIẾT KẾ
PHẦN
THIẾT KẾ GIAO DIỆN NGƯỜI DÙNG
MỀM -
GIAO
XỬ LÝ GIAO DIỆN NGƯỜI DÙNG
DIỆN
THIẾT KẾ XỬ LÝ GIAO DIỆN NGƯỜI DÙNG
Software Engineering 18
tkhuong@dthu.edu.vn

2. THIẾT KẾ GIAO DIỆN NGƯỜI DÙNG
❖ KHÁI NIỆM
❖ NGUYÊN TẮC THIẾT KẾ GIAO DIỆN NGƯỜI DÙNG
❖ CÁC KIỂU TƯƠNG TÁC
❖ QUY TRÌNH THIẾT KẾ GIAO DIỆN NGƯỜI DÙNG
❖ KỸ THUẬT THIẾT KẾ GIAO DIỆN NGƯỜI DÙNG
Software Engineering 19
tkhuong@dthu.edu.vn

| Phân | tích |     |
| ---- | ---- | --- |
Hồ sơ
viên
phân tích
| Phụ | trách |     |
| --- | ----- | --- |
Kiến trúc về
| thiết kế | giao diện | công nghệ |
| -------- | --------- | --------- |
| Hồ       | sơ thiết  |           |
Lập trình
| kế  | giao diện |     |
| --- | --------- | --- |
viên
Software Engineering 20
tkhuong@dthu.edu.vn

2.1 KHÁI NIỆM THIẾT KẾ UI
| ❖   | Thiết | kế  | giao  | diện  |     | người | dùng |      |      |     |          |      |     |     |
| --- | ----- | --- | ----- | ----- | --- | ----- | ---- | ---- | ---- | --- | -------- | ---- | --- | --- |
|     | ▪     | Mô  | tả hệ | thống |     | các   | màn  | hình | giao |     | diện của | phần | mềm | dựa |
trên
|     |     | •   | Hồ sơ | phân |     | tích | yêu | cầu | (đặc | biệt | các | dòng | dữ liệu |     |
| --- | --- | --- | ----- | ---- | --- | ---- | --- | --- | ---- | ---- | --- | ---- | ------- | --- |
nhập/ xuất)
|     |       | •   | Công  | nghệ |      | giao | diện                 | được | chọn |     |      |     |      |     |
| --- | ----- | --- | ----- | ---- | ---- | ---- | -------------------- | ---- | ---- | --- | ---- | --- | ---- | --- |
|     | →Lưu  |     | ý xem |      | xét  | tính | tiện                 | dụng |      |     |      |     |      |     |
|     | →Hiểu |     | rõ    | khả  | năng |      | của                  | công | nghệ |     | đang | sử  | dụng |     |
|     |       |     |       |      |      |      | Software Engineering |      |      |     |      |     |      | 21  |
tkhuong@dthu.edu.vn

2.1 KHÁI NIỆM THIẾT KẾ UI
| ❖   | Hồ    | sơ  | thiết  | kế   | giao |      | diện  | người |      | dùng |      |      |      |     |      |
| --- | ----- | --- | ------ | ---- | ---- | ---- | ----- | ----- | ---- | ---- | ---- | ---- | ---- | --- | ---- |
|     | ▪     | Tài | liệu   | mô   | tả   | hệ   | thống |       | các  | màn  | hình | giao | diện | của | phần |
|     |       | mềm | theo   |      | công |      | nghệ  |       | giao | diện | được | chọn |      |     |      |
| ➢   | Thiết |     | kế với | công |      | nghệ |       | cụ    | thể  |      |      |      |      |     |      |
o
Sử dụng các khái niệm từ khóa đặc thù của công nghệ giao diện
|     |       | được | chọn   |     |      |      |      |       |     |     |     |           |     |      |      |
| --- | ----- | ---- | ------ | --- | ---- | ---- | ---- | ----- | --- | --- | --- | --------- | --- | ---- | ---- |
| ➢   | Thiết |      | kế độc |     | lập  | công |      | nghệ  |     |     |     |           |     |      |      |
|     | o     | Sử   | dụng   | các | khái |      | niệm | chung |     | cho | các | công nghệ |     | giao | diện |
Software Engineering 22
tkhuong@dthu.edu.vn

2.2 NGUYÊN TẮC THIẾT KẾ UI
❖ Khi thiết kế UI phải tính đến kinh nghiệm, năng lực, nhu cầu của
| người   |     | dùng:      |          |     |             |     |           |     |       |     |     |
| ------- | --- | ---------- | -------- | --- | ----------- | --- | --------- | --- | ----- | --- | --- |
| ▪       | Khả | năng dùng  |          | bàn | phím, chuột |     |           |     |       |     |     |
| ▪       | Tốc | độ phản    | ứng, khả |     | năng        | nhớ | thao      | tác |       |     |     |
| ▪       | Sở  | thích, văn | hóa, lứa |     | tuổi: màu   |     | sắc, ngôn |     | ngữ,… |     |     |
| ❖ Người |     | thiết kế   | nên      |     |             |     |           |     |       |     |     |
▪ Nhận thức được các hạn chế về vật lý và tinh thần của người dùng
|     | •    | Ví dụ: khả | năng | nhớ     | ngắn | hạn | bị hạn | chế   |      |      |     |
| --- | ---- | ---------- | ---- | ------- | ---- | --- | ------ | ----- | ---- | ---- | --- |
|     | •    | Nên thừa   | nhận | ai cũng | có   | thể | nhầm   | lẫn   |      |      |     |
| ▪   | Luôn | bao gồm    | việc | làm     | bản  | mẫu | để     | người | dùng | đánh | giá |
Software Engineering 23
tkhuong@dthu.edu.vn

2.2 NGUYÊN TẮC THIẾT KẾ UI
| ❖ Các |     | nguyên | tắc | thiết |     | kế: |     |     |     |     |     |
| ----- | --- | ------ | --- | ----- | --- | --- | --- | --- | --- | --- | --- |
▪
|     | Thân | thiện |     | với người |     | dùng |     |     |     |     |     |
| --- | ---- | ----- | --- | --------- | --- | ---- | --- | --- | --- | --- | --- |
• Giao diện nên dựa vào các thuật ngữ và khái niệm hướng người
|     |     | dùng | hơn | là các |     | khái niệm | máy | tính. |     |     |     |
| --- | --- | ---- | --- | ------ | --- | --------- | --- | ----- | --- | --- | --- |
• Ví dụ, một hệ thống văn phòng nên dùng các khái niệm như thư từ,
|     |      | tài liệu, |     | thư mục,... |     | hơn | là đường | dẫn, | tên | file,... |     |
| --- | ---- | --------- | --- | ----------- | --- | --- | -------- | ---- | --- | -------- | --- |
| ▪   | Nhất | quán      |     |             |     |     |          |      |     |          |     |
• Hệ thống nên hiển thị một cách nhất quán. Các lệnh và menu nên
|     |     | có cùng |     | định | dạng, | các | dấu chấm | lệnh | nên | tương | tự nhau... |
| --- | --- | ------- | --- | ---- | ----- | --- | -------- | ---- | --- | ----- | ---------- |
| ▪   | Ít  | bất ngờ |     |      |       |     |          |      |     |       |            |
• Nếu một lệnh được thực hiện theo cách thông thường, người dùng
|     |     | có thể | dự  | đoán | được | thao | tác của | các | lệnh | tương | tự. |
| --- | --- | ------ | --- | ---- | ---- | ---- | ------- | --- | ---- | ----- | --- |
Software Engineering 24
tkhuong@dthu.edu.vn

2.2 NGUYÊN TẮC THIẾT KẾ UI
| ❖ Các | nguyên |      | lý thiết | kế (tt): |     |     |     |     |     |
| ----- | ------ | ---- | -------- | -------- | --- | --- | --- | --- | --- |
| ▪     | Có thể | khôi | phục     | được     |     |     |     |     |     |
• Hệ thống nên cung cấp một số cơ chế phục hồi lại tình trạng hoạt
|     | động  | bình | thường | sau khi  | gặp lỗi. | Cơ chế | này có    | thể bao | gồm |
| --- | ----- | ---- | ------ | -------- | -------- | ------ | --------- | ------- | --- |
|     | chức  | năng | undo,  | xác nhận | một hành | động   | hủy, xóa, | ...     |     |
| ▪   | Hướng | dẫn  | người  | dùng     |          |        |           |         |     |
• Một số hướng dẫn người dùng như hệ thống giúp đỡ, tài liệu trực
|     | tuyến   | ...   | nên được | cung cấp. |     |     |     |     |     |
| --- | ------- | ----- | -------- | --------- | --- | --- | --- | --- | --- |
| ▪   | Đa dạng | người | dùng     |           |     |     |     |     |     |
• Nên cung cấp các tiện ích tương tác cho các loại người dùng khác
nhau.
• Ví dụ, một số người dùng có khả năng nhìn hạn chế thì nên để cỡ
|     | chữ | to  | hơn. |                      |     |     |     |     |     |
| --- | --- | --- | ---- | -------------------- | --- | --- | --- | --- | --- |
|     |     |     |      | Software Engineering |     |     |     |     | 25  |
tkhuong@dthu.edu.vn

|     |       | Vấn   | đề   |     | thiết |     | kế   | trong |     |       | các |          | UI  |      |       |
| --- | ----- | ----- | ---- | --- | ----- | --- | ---- | ----- | --- | ----- | --- | -------- | --- | ---- | ----- |
| ❖   | Hai   | vấn   | đề   | cần | được  |     | quan |       | tâm | trong |     | thiết    | kế  | hệ   | thống |
|     | tương | tác   |      |     |       |     |      |       |     |       |     |          |     |      |       |
|     | ▪     | Người | dùng |     | cung  | cấp |      | thông | tin | cho   |     | hệ thống |     | bằng | cách  |
nào?
|     | ▪   | Hệ thống |     | biểu | diễn | thông |                      | tin | đến | người |     | dùng | như | thế | nào? |
| --- | --- | -------- | --- | ---- | ---- | ----- | -------------------- | --- | --- | ----- | --- | ---- | --- | --- | ---- |
|     |     |          |     |      |      |       | Software Engineering |     |     |       |     |      |     |     | 26   |
tkhuong@dthu.edu.vn

2.3 CÁC KIỂU TƯƠNG TÁC
| ❖ Thao | tác trực                 | tiếp                | (direct manipulation)  |
| ------ | ------------------------ | ------------------- | ---------------------- |
| ❖ Chọn | menu (menu selection)    |                     |                        |
| ❖ Điền | vào form (form fill-in)  |                     |                        |
| ❖ Ngôn | ngữ lệnh                 | (command language)  |                        |
| ❖ Ngôn | ngữ tự                   | nhiên               | (natural language)     |
Software Engineering 27
tkhuong@dthu.edu.vn

2.3 CÁC KIỂU TƯƠNG TÁC
Software Engineering 28
tkhuong@dthu.edu.vn

| Một      | số   | vấn  |     | đề   | trong |       | thiết    | kế giao | diện |
| -------- | ---- | ---- | --- | ---- | ----- | ----- | -------- | ------- | ---- |
| ❖ Phương |      | pháp |     | hiển | thị   | thông | tin, màu |         |      |
| ❖ Thời   | gian | phản |     | hồi  | của   | hệ    | thống    |         |      |
| ❖ Cách   | thức |      | xây | dựng | thông |       | báo      |         |      |
| ❖ Các    | tiện | ích  | trợ | giúp |       |       |          |         |      |
Software Engineering 29
tkhuong@dthu.edu.vn

|      | Một      | số vấn  | đề trong | thiết | kế giao | diện |
| ---- | -------- | ------- | -------- | ----- | ------- | ---- |
| ❖ Ví | dụ thông | báo lỗi |          |       |         |      |
Software Engineering 30
tkhuong@dthu.edu.vn

2.4 QUY TRÌNH THIẾT KẾ UI
❖ Thiết kế UI là một quy trình có tính lặp lại với mối liên hệ
| chặt | chẽ    | giữa | người  | dùng | và người | thiết kế. |     |     |
| ---- | ------ | ---- | ------ | ---- | -------- | --------- | --- | --- |
| ❖ Có | 3 hoạt | động | chính: |      |          |           |     |     |
▪ Phân tích người dùng: Hiểu người dùng sẽ làm gì với hệ thống;
▪ Xây dựng prototype: Xây dựng một chuỗi các prototype để thử
nghiệm;
| ▪   | Đánh  | giá   | giao diện: | Thử                  | nghiệm | các prototype | này cùng | với |
| --- | ----- | ----- | ---------- | -------------------- | ------ | ------------- | -------- | --- |
|     | người | dùng. |            |                      |        |               |          |     |
|     |       |       |            | Software Engineering |        |               |          | 35  |
tkhuong@dthu.edu.vn

2.4 QUY TRÌNH THIẾT KẾ UI
Software Engineering 37
tkhuong@dthu.edu.vn

2. THIẾT KẾ GIAO DIỆN NGƯỜI DÙNG
❖ KHÁI NIỆM
❖ NGUYÊN TẮC THIẾT KẾ GIAO DIỆN NGƯỜI DÙNG
❖ CÁC KIỂU TƯƠNG TÁC
❖ QUY TRÌNH THIẾT KẾ GIAO DIỆN NGƯỜI DÙNG
❖ KỸ THUẬT THIẾT KẾ GIAO DIỆN NGƯỜI DÙNG
Software Engineering 38
tkhuong@dthu.edu.vn

2.5 KỸ THUẬT THIẾT KẾ UI
| ❖ Các | bước  | thiết | kế UI |     |
| ----- | ----- | ----- | ----- | --- |
| ❖ Một | số kỹ | thuật | thiết | kế  |
Software Engineering 39
tkhuong@dthu.edu.vn

|     | Các |     | bước |     | thiết |     | kế  | UI  |
| --- | --- | --- | ---- | --- | ----- | --- | --- | --- |
❖
|     | Bước   | 1: Thiết |          | kế tổng     | thể   | giao  |     | diện      |
| --- | ------ | -------- | -------- | ----------- | ----- | ----- | --- | --------- |
|     | ▪ Mô   | tả       | tổng     | thể các     | màn   | hình  |     | giao diện |
|     | ▪ Sự   | tồn      | tại      |             |       |       |     |           |
|     | ▪ Liên | kết      |          |             |       |       |     |           |
| ❖   | Bước   | 2: Thiết |          | kế chi tiết |       | giao  |     | diện      |
|     | ▪ Mô   | tả       | chi tiết | từng        | màn   | hình  |     | giao diện |
|     | ▪ Sắp  | xếp/ bố  |          | trí các     | đối   | tượng |     | giao diện |
|     | ▪ Các  | biến     |          | cố cần      | xử lý |       |     |           |
Software Engineering 40
tkhuong@dthu.edu.vn

|       | Các      | bước | thiết |       | kế UI   |      |      |     |
| ----- | -------- | ---- | ----- | ----- | ------- | ---- | ---- | --- |
|       |          |      | Mô tả | tổng  | thể các | chức | năng |     |
|       |          |      |       | Thiết | kế      |      |      |     |
|       |          |      |       | tổng  | thể     |      |      |     |
| Mô tả | chi tiết | chức |       |       |         |      |      |     |
năng
|     |       |     | Sơ  | đồ  | màn hình | giao | diện |           |
| --- | ----- | --- | --- | --- | -------- | ---- | ---- | --------- |
|     | Thiết | kế  |     |     | Chi tiết | màn  | hình | giao diện |
chi tiết
Software Engineering 41
tkhuong@dthu.edu.vn

|     |       | Sơ    | đồ    |      | màn  | hình |          | giao |     | diện         |          |
| --- | ----- | ----- | ----- | ---- | ---- | ---- | -------- | ---- | --- | ------------ | -------- |
| ❖   | Khái  | niệm  |       |      |      |      |          |      |     |              |          |
|     | ▪ Một |       | trong | các  | công | cụ   | cho phép |      | mô  | tả trực quan | hệ thống |
|     | các   | màn   |       | hình | giao | diện |          |      |     |              |          |
| ❖   | Ký    | hiệu: |       |      |      |      |          |      |     |              |          |
|     |       |       |       |      |      |      |          |      | Tên | màn hình     |          |
| ✓   | Màn   | hình  |       | giao | diện |      |          |      |     |              |          |
| ✓   | Liên  | kết   | 2 màn |      | hình | giao | diện     |      |     |              |          |
Software Engineering 42
tkhuong@dthu.edu.vn

| VD. Sơ | đồ  | màn | hình | giao | diện |
| ------ | --- | --- | ---- | ---- | ---- |
MH_DANG_KY
MH_QLNS MH_BGĐ
| MH_TNHS |     |     |     | MH_CNCT |     |
| ------- | --- | --- | --- | ------- | --- |
MH_CN_XHS
MH_TCHS
Software Engineering 43
tkhuong@dthu.edu.vn

|     | Chi tiết |     |     | màn |     | hình |     | giao | diện |
| --- | -------- | --- | --- | --- | --- | ---- | --- | ---- | ---- |
KÝ HIỆU TRÊN MÀN HÌNH GIAO DIỆN
❖
|     | Dữ liệu | cần | nhập              | mới  |     |     |      |      |     |
| --- | ------- | --- | ----------------- | ---- | --- | --- | ---- | ---- | --- |
|     |         |     | Hay ……. Hay ký    |      |     |     | hiệu | khác |     |
| ❖   | Dữ liệu | kết | xuất              |      |     |     |      |      |     |
|     |         |     | Hay ****** Hay ký |      |     |     | hiệu | khác |     |
| ❖   | Dữ liệu | cập | nhật              |      |     |     |      |      |     |
|     | #####   |     | Hay ##### Hay ký  |      |     |     | hiệu | khác |     |
| ❖   | Dữ liệu | với | giá trị           | định | sẵn |     |      |      |     |
(giá trị)
|     |         |     | Hay (giá |     | trị) Hay ký |     | hiệu | khác |     |
| --- | ------- | --- | -------- | --- | ----------- | --- | ---- | ---- | --- |
| ❖   | Biến cố | cần | xử       | lý  |             |     |      |      |     |
Software Engineering 46
tkhuong@dthu.edu.vn

|            | VD. Chi tiết |     |      | màn        | hình  | giao | diện |
| ---------- | ------------ | --- | ---- | ---------- | ----- | ---- | ---- |
| ❖ Minh họa |              | màn | hình | tiếp nhận  | hồ sơ | nhân | sự   |
|            |              |     | Tiếp | nhận hồ sơ | mới   |      |      |
Mã số: *********
|     |     |     |     |     | Nam | Nữ  |     |
| --- | --- | --- | --- | --- | --- | --- | --- |
Họ và tên: ……….
Ngày sinh: ………
Địa chỉ: …………..
…………………….
|     |     |     | Ghi |     | Kết thúc |     |     |
| --- | --- | --- | --- | --- | -------- | --- | --- |
Software Engineering 47
tkhuong@dthu.edu.vn

| Một     | số          | kỹ  | thuật | thiết |      | kế   | UI  |
| ------- | ----------- | --- | ----- | ----- | ---- | ---- | --- |
| ❖ Lập   | sơ đồ       | màn | hình  | giao  | diện |      |     |
| ❖ Thiết | kế chi tiết |     | màn   | hình  | giao | diện |     |
Software Engineering 49
tkhuong@dthu.edu.vn

| Kỹ    | thuật    | lập | sơ  | đồ  | màn | hình        | GD        |     |
| ----- | -------- | --- | --- | --- | --- | ----------- | --------- | --- |
| Mô tả | tổng thể |     |     |     | Mô  | tả tổng     | thể màn   |     |
| chức  | năng     |     |     |     |     | hình giao   | diện      |     |
|       |          |     |     |     | Sơ  | đồ màn hình | theo cách | 1   |
|       |          |     |     |     | Sơ  | đồ màn hình | theo cách | 2   |
f1
|     |     |     |     |     | Sơ  | đồ màn hình | theo cách | 3   |
| --- | --- | --- | --- | --- | --- | ----------- | --------- | --- |
f3
|     |     |     |     |     | Sơ  | đồ màn hình | theo cách | 4   |
| --- | --- | --- | --- | --- | --- | ----------- | --------- | --- |
f2
|     |     |     |                      |     | Sơ  | đồ màn hình | theo cách | 5   |
| --- | --- | --- | -------------------- | --- | --- | ----------- | --------- | --- |
|     |     |     | Software Engineering |     |     |             |           | 50  |
tkhuong@dthu.edu.vn

❖ Cách 1:
MH_CHÍNH
MH_F1 MH_F3
MH_F2
Software Engineering 51
tkhuong@dthu.edu.vn

❖ Cách 2:
MH_F2
MH_F1 MH_F3
Software Engineering 52
tkhuong@dthu.edu.vn

❖ Cách 3:
MH_F2
MH_F1 MH_F3
MH_G
Software Engineering 53
tkhuong@dthu.edu.vn

❖ Cách 4:
MH_F12
MH_F3
MH_G
Software Engineering 54
tkhuong@dthu.edu.vn

❖ Cách 5:
MH_F123
MH_G2
MH_G1
Software Engineering 55
tkhuong@dthu.edu.vn

| Một     | số    | kỹ       | thuật | thiết |      | kế   | UI  |
| ------- | ----- | -------- | ----- | ----- | ---- | ---- | --- |
| ❖ Lập   | sơ đồ | màn      | hình  | giao  | diện |      |     |
| ❖ Thiết | kế    | chi tiết | màn   | hình  | giao | diện |     |
Software Engineering 56
tkhuong@dthu.edu.vn

| Kỹ    | thuật    | thiết | kế       | chi tiết |     | màn    | hình      |     |
| ----- | -------- | ----- | -------- | -------- | --- | ------ | --------- | --- |
| Mô tả | tổng thể |       |          |          | Mô  | tả     | tổng thể  | màn |
|       |          |       | Kỹ thuật | 1        |     |        |           |     |
| chức  | năng     |       |          |          |     | hình   | giao diện |     |
|       | X        |       |          |          |     | Nghiệp | vụ f      |     |
D1 D2
|     |      |     |     | Thể hiện | dạng | nhập | liệu của | D1   |
| --- | ---- | --- | --- | -------- | ---- | ---- | -------- | ---- |
| Xử  | lý f |     |     |          |      |      |          |      |
|     |      |     |     | Thể hiện | dạng | kết  | xuất của | D2   |
|     |      |     |     | Thực     | hiện |      | Kết      | thúc |
Software Engineering 57
tkhuong@dthu.edu.vn

| Kỹ    | thuật    | thiết | kế       | chi tiết |     | màn    |      | hình |      |     |
| ----- | -------- | ----- | -------- | -------- | --- | ------ | ---- | ---- | ---- | --- |
| Mô tả | tổng thể |       |          |          |     | Mô     | tả   | tổng | thể  | màn |
|       |          |       | Kỹ thuật | 2        |     |        |      |      |      |     |
| chức  | năng     |       |          |          |     |        | hình | giao | diện |     |
|       | X        |       |          |          |     | Nghiệp |      | vụ   | f    |     |
D1 D2
|     |      |     |     | Thể hiện | dạng |      | nhập | liệu | của | D1 với |
| --- | ---- | --- | --- | -------- | ---- | ---- | ---- | ---- | --- | ------ |
|     |      |     |     | các giá  | trị  | định | sẵn  |      |     |        |
| Xử  | lý f |     |     |          |      |      |      |      |     |        |
|     |      |     |     | Thể hiện | dạng |      | kết  | xuất | của | D2     |
|     |      |     |     | Thực     | hiện |      |      |      | Kết | thúc   |
Software Engineering 58
tkhuong@dthu.edu.vn

| Kỹ    | thuật    | thiết | kế       | chi tiết |     | màn    | hình |         |
| ----- | -------- | ----- | -------- | -------- | --- | ------ | ---- | ------- |
| Mô tả | tổng thể |       |          |          |     | Mô tả  | tổng | thể màn |
|       |          |       | Kỹ thuật | 3        |     |        |      |         |
| chức  | năng     |       |          |          |     | hình   | giao | diện    |
|       | X        |       |          |          |     | Nghiệp | vụ   | f       |
D1 D2
|     |      |     |     | Thể hiện | dạng  | nhập     | liệu | của D1 với |
| --- | ---- | --- | --- | -------- | ----- | -------- | ---- | ---------- |
|     |      |     |     | các giá  | trị   | định sẵn |      |            |
| Xử  | lý f |     |     |          |       |          |      |            |
|     |      |     |     | Thể hiện | dạng  | kết      | xuất | của D2 với |
|     |      |     |     | dạng     | chuỗi |          |      |            |
|     |      |     |     | Thực     | hiện  |          |      | Kết thúc   |
Software Engineering 59
tkhuong@dthu.edu.vn

| Kỹ    | thuật    | thiết | kế       | chi tiết |     | màn    | hình |         |
| ----- | -------- | ----- | -------- | -------- | --- | ------ | ---- | ------- |
| Mô tả | tổng thể |       |          |          | Mô  | tả     | tổng | thể màn |
|       |          |       | Kỹ thuật | 4        |     |        |      |         |
| chức  | năng     |       |          |          |     | hình   | giao | diện    |
|       | X        |       |          |          |     | Nghiệp | vụ   | f       |
D1 D2
|     |      |     |     | Thể hiện   | dạng | nhập | liệu | của D1 với |
| --- | ---- | --- | --- | ---------- | ---- | ---- | ---- | ---------- |
|     |      |     |     | dạng chuỗi |      |      |      |            |
| Xử  | lý f |     |     |            |      |      |      |            |
|     |      |     |     | Thể hiện   | dạng | kết  | xuất | của D2 với |
|     |      |     |     | biểu tượng |      |      |      |            |
|     |      |     |     | Thực       | hiện |      |      | Kết thúc   |
Software Engineering 60
tkhuong@dthu.edu.vn

| Kỹ    | thuật    | thiết | kế       | chi tiết |     | màn    | hình |         |
| ----- | -------- | ----- | -------- | -------- | --- | ------ | ---- | ------- |
| Mô tả | tổng thể |       |          |          | Mô  | tả     | tổng | thể màn |
|       |          |       | Kỹ thuật | 5        |     |        |      |         |
| chức  | năng     |       |          |          |     | hình   | giao | diện    |
|       | X        |       |          |          |     | Nghiệp | vụ   | f       |
D1 D2
|     |      |     |     | Thể hiện  | dạng  | nhập | liệu | của D1 với |
| --- | ---- | --- | --- | --------- | ----- | ---- | ---- | ---------- |
|     |      |     |     | dạng biểu | tượng |      |      |            |
| Xử  | lý f |     |     |           |       |      |      |            |
|     |      |     |     | Thể hiện  | dạng  | kết  | xuất | của D2 với |
biểu tượng
|     |     |     |     | Thực | hiện |     |     | Kết thúc |
| --- | --- | --- | --- | ---- | ---- | --- | --- | -------- |
Software Engineering 61
tkhuong@dthu.edu.vn

| Kỹ  | thuật       | thiết | kế chi tiết |     |     | màn | hình |         |     |
| --- | ----------- | ----- | ----------- | --- | --- | --- | ---- | ------- | --- |
| Mô  | tả tổng thể |       |             |     | Mô  | tả  | tổng | thể màn |     |
|     |             |       | Kỹ thuật    | 6   |     |     |      |         |     |
(TAB)
|     | chức năng |     |     |     |        | hình | giao      | diện |     |
| --- | --------- | --- | --- | --- | ------ | ---- | --------- | ---- | --- |
|     | X         |     |     |     | Nghiệp |      | vụ f1, f2 |      |     |
D11 D12
| Xử  | lý f1 |     |     | Nghiệp | vụ  | f1  | Nghiệp |     | vụ f2 |
| --- | ----- | --- | --- | ------ | --- | --- | ------ | --- | ----- |
X
D21 D22
|     |       |     |     | Thực | hiện |     |     | Kết thúc |     |
| --- | ----- | --- | --- | ---- | ---- | --- | --- | -------- | --- |
| Xử  | lý f2 |     |     |      |      |     |     |          |     |
Software Engineering 62
tkhuong@dthu.edu.vn

| Kỹ  | thuật       | thiết | kế chi tiết |     |     | màn |         | hình |         |     |
| --- | ----------- | ----- | ----------- | --- | --- | --- | ------- | ---- | ------- | --- |
| Mô  | tả tổng thể |       |             |     | Mô  |     | tả tổng |      | thể màn |     |
|     |             |       | Kỹ thuật    | 6   |     |     |         |      |         |     |
(tab1)
|     | chức năng |     |     |     |        | hình |     | giao   | diện |     |
| --- | --------- | --- | --- | --- | ------ | ---- | --- | ------ | ---- | --- |
|     | X         |     |     |     | Nghiệp |      | vụ  | f1, f2 |      |     |
D11 D12
|     |       |     |     | Nghiệp   | vụ   | f1   |      | Nghiệp |      | vụ f2 |
| --- | ----- | --- | --- | -------- | ---- | ---- | ---- | ------ | ---- | ----- |
| Xử  | lý f1 |     |     |          |      |      |      |        |      |       |
|     |       |     |     | Thể hiện | dạng | nhập |      | của    | D11  |       |
|     | X     |     |     | Thể hiện | dạng | kết  | xuất | của    | D12  |       |
D21 D22
|     |       |     |     | Thực | hiện |     |     |     | Kết thúc |     |
| --- | ----- | --- | --- | ---- | ---- | --- | --- | --- | -------- | --- |
| Xử  | lý f2 |     |     |      |      |     |     |     |          |     |
Software Engineering 63
tkhuong@dthu.edu.vn

| Kỹ  | thuật       | thiết | kế chi tiết |     |     |     | màn |      | hình |         |     |
| --- | ----------- | ----- | ----------- | --- | --- | --- | --- | ---- | ---- | ------- | --- |
| Mô  | tả tổng thể |       |             |     |     | Mô  | tả  | tổng |      | thể màn |     |
|     |             |       | Kỹ thuật    | 6   |     |     |     |      |      |         |     |
(tab2)
|     | chức năng |     |     |     |     |        | hình |     | giao   | diện |     |
| --- | --------- | --- | --- | --- | --- | ------ | ---- | --- | ------ | ---- | --- |
|     | X         |     |     |     |     | Nghiệp |      | vụ  | f1, f2 |      |     |
D11 D12
|     |       |     |     | Nghiệp |     | vụ   | f1   |     | Nghiệp |      | vụ f2    |
| --- | ----- | --- | --- | ------ | --- | ---- | ---- | --- | ------ | ---- | -------- |
| Xử  | lý f1 |     |     |        |     |      |      |     |        |      |          |
|     |       |     |     |        | Thể | hiện | dạng |     | nhập   | của  | D21      |
|     | X     |     |     |        | Thể | hiện | dạng |     | kết    | xuất | của D22  |
D21 D22
|     |       |     |     | Thực |     | hiện |     |     |     | Kết thúc |     |
| --- | ----- | --- | --- | ---- | --- | ---- | --- | --- | --- | -------- | --- |
| Xử  | lý f2 |     |     |      |     |      |     |     |     |          |     |
Software Engineering 64
tkhuong@dthu.edu.vn

| VD. Thiết | kế  | GD Giải | PT bậc | 2   |
| --------- | --- | ------- | ------ | --- |
❖ Cách 1
❖ SƠ ĐỒ MÀN HÌNH
MH_CHINH
| MH_GIAI_PT |     | MH_TU_REN_LUYEN |     |     |
| ---------- | --- | --------------- | --- | --- |
Software Engineering 65
tkhuong@dthu.edu.vn

❖ Cách 1:
❖ MH_CHINH
| Phần mềm    | tự rèn | luyện | bài |
| ----------- | ------ | ----- | --- |
| tập phương  | trình  | bậc   | 2   |
| Giải phương |        | trình |     |
Tự rèn luyện
Software Engineering 66
tkhuong@dthu.edu.vn

❖ Cách 1:
❖ MH_GIAI_PT
|     | Giải phương | trình bậc | 2   |
| --- | ----------- | --------- | --- |
Phương trình:
…..X2
|     | – ….X + …. | = 0 |     |
| --- | ---------- | --- | --- |
Nghiệm:
| Phương | trình ***x2 | – ***x + *** = 0 có | *** |
| ------ | ----------- | ------------------- | --- |
nghiệm
| phân | biệt x1=*** và | x2=*** |     |
| ---- | -------------- | ------ | --- |
Đồng ý
Software Engineering 67
tkhuong@dthu.edu.vn

❖ Cách 1:
❖ MH_TU_REN_LUYEN
|             | Tự rèn | luyện | giải  |
| ----------- | ------ | ----- | ----- |
|             | phương | trình | bậc 2 |
| Giải phương | trình: |       |       |
***X2
|     | + ***X - | *** = 0 |     |
| --- | -------- | ------- | --- |
Nghiệm: …….
Kết quả:
| Sai rồi | !!! Phương       | trình | có 2 nghiệm |
| ------- | ---------------- | ----- | ----------- |
|         | x1=*** và x2=*** |       |             |
Đồng ý
Software Engineering 68
tkhuong@dthu.edu.vn

| VD. Thiết |     | kế  | GD Giải |     | PT bậc |     | 2   |
| --------- | --- | --- | ------- | --- | ------ | --- | --- |
❖ Cách 2
❖ SƠ ĐỒ MÀN HÌNH
|     | Phần mềm    | bài | tập phương |        | trình bậc | 2   |     |
| --- | ----------- | --- | ---------- | ------ | --------- | --- | --- |
|     | Giải phương |     | trình      | Tự rèn | luyện     |     |     |
Kết thúc
Software Engineering 69
tkhuong@dthu.edu.vn

|        | VD. Thiết |        |        |        | kế   | GD Giải    |        |      |       | PT bậc |     |       | 2   |
| ------ | --------- | ------ | ------ | ------ | ---- | ---------- | ------ | ---- | ----- | ------ | --- | ----- | --- |
| ❖ Cách | 2         |        |        |        |      |            |        |      |       |        |     |       |     |
| ❖ Giao | diện      | khi    | chọn   |        | chức |            | năng   | Giải |       | phương |     | trình |     |
|        |           | Phần   |        | mềm    | bài  | tập        | phương |      | trình | bậc    | 2   |       |     |
|        |           | Giải   | phương |        |      | trình      |        | Tự   | rèn   | luyện  |     |       |     |
|        |           | Phương |        | trình: |      |            |        |      |       |        |     |       |     |
|        |           |        |        | …..X2  |      | – ….X + …. |        | = 0  |       |        |     |       |     |
Nghiệm:
|     |     |     | Phương |     | trình | 2x2 | –   | 5x + 7 = 0 có |     | 2   |     |     |     |
| --- | --- | --- | ------ | --- | ----- | --- | --- | ------------- | --- | --- | --- | --- | --- |
nghiệm
|     |     |     | phân | biệt |     | x1=-1 và |      | x2=-3.5 |     |     |     |     |     |
| --- | --- | --- | ---- | ---- | --- | -------- | ---- | ------- | --- | --- | --- | --- | --- |
|     |     |     |      |      |     | Kết      | thúc |         |     |     |     |     |     |
Software Engineering 70
tkhuong@dthu.edu.vn

|        | VD. Thiết |      |        | kế   |        | GD Giải |        |       | PT bậc |       | 2   |
| ------ | --------- | ---- | ------ | ---- | ------ | ------- | ------ | ----- | ------ | ----- | --- |
| ❖ Cách | 2         |      |        |      |        |         |        |       |        |       |     |
| ❖ Giao | diện      | khi  | chọn   | chức |        | năng    | Giải   |       | phương | trình |     |
|        |           | Phần | mềm    |      | bài    | tập     | phương | trình | bậc    | 2     |     |
|        |           | Giải | phương |      | trình  |         | Tự     | rèn   | luyện  |       |     |
|        |           | Giải | phương |      | trình: |         |        |       |        |       |     |
|        |           |      |        | 3X2  | + 7X - | 10 = 0  |        |       |        |       |     |
Nghiệm: …….
|     |     | Kết | quả:  |                |     |          |       |             |     |     |     |
| --- | --- | --- | ----- | -------------- | --- | -------- | ----- | ----------- | --- | --- | --- |
|     |     |     | Sai   | rồi !!! Phương |     |          | trình | có 2 nghiệm |     |     |     |
|     |     |     |       | x1=1 và        |     | x2=-3.33 |       |             |     |     |     |
|     |     |     |       |                |     | Kết      | thúc  |             |     |     |     |
Software Engineering 71
tkhuong@dthu.edu.vn

Bài tập
| BT1. Thiết | kế giao | diện    | cho pm Quản | lý nhân  | sự      |     |
| ---------- | ------- | ------- | ----------- | -------- | ------- | --- |
| ▪ Sơ       | đồ tổng | thể màn | hình        |          |         |     |
| ▪ Chi tiết | từng    | màn     | hình        |          |         |     |
| BT2. Thiết | kế giao | diện    | cho pm xếp  | loại học | lực của | học |
sinh
| BT3. Thiết | kế giao | diện | cho pm Quản | lý thu | chi |     |
| ---------- | ------- | ---- | ----------- | ------ | --- | --- |
Software Engineering 72
tkhuong@dthu.edu.vn

| Đề  | bài | BT1 |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- |
❖ Xét phần mềm Quản lý nhân sự với yêu cầu chính là tra cứu hồ sơ
nhân viên dựa trên họ tên. Hãy phân tích thiết kế với công nghệ
Windows, xử lý dùng đơn thể và lưu trữ dùng CSDL quan hệ (chỉ xét
| các thuộc | tính Họ | tên, giới | tính, ngày | sinh, địa | chỉ) |       |     |
| --------- | ------- | --------- | ---------- | --------- | ---- | ----- | --- |
| PHÂN      | TÍCH    |           |            |           |      | THIẾT | KẾ  |
Software Engineering 73
tkhuong@dthu.edu.vn

|      | BT1. Quản |     |     |       |     | lý nhân |        | viên |     |     |
| ---- | --------- | --- | --- | ----- | --- | ------- | ------ | ---- | --- | --- |
| Phân | tích      | yêu | cầu | (Ngôn |     | ngữ tự  | nhiên) |      |     |     |
❖ Người dùng muốn phần mềm quản lý nhân viên cho phép thực hiện
| các    |     | chức | năng | như |     | sau: |     |     |     |     |
| ------ | --- | ---- | ---- | --- | --- | ---- | --- | --- | --- | --- |
| ❖ Nhân |     | viên |      |     |     |      |     |     |     |     |
▪
Quản lý hồ sơ nhân viên (Thêm mới, cập nhật, xóa) dựa theo BM1
▪ Tra cứu hồ sơ nhân viên: cho phép nhập vào tên hoặc địa chỉ, hoặc trình
độ của nhân viên và sau đó phần mềm sẽ xuất ra danh sách các nhân
|     |     | viên | (thông | tin hồ |     | sơ nhân | viên khi | tra | cứu theo | BM1) |
| --- | --- | ---- | ------ | ------ | --- | ------- | -------- | --- | -------- | ---- |
▪ Lập báo cáo thống kê: yêu cầu lập báo cáo thông kê theo BM2
❖ Ban giám đốc: chỉ sử dụng 1 chức năng là cập nhật quy định tiếp
| nhận |           | nhận | nhân |     | viên | mới        |      |      |     |     |
| ---- | --------- | ---- | ---- | --- | ---- | ---------- | ---- | ---- | --- | --- |
| Ghi  | chú: chưa |      | xem  | xét | hết  | tất cả các | chức | năng |     |     |
Software Engineering 74
tkhuong@dthu.edu.vn

|                     | BT1. Quản        |     |      |      |            | lý   | nhân |                                       | viên  |     |     |       |       |     |       |
| ------------------- | ---------------- | --- | ---- | ---- | ---------- | ---- | ---- | ------------------------------------- | ----- | --- | --- | ----- | ----- | --- | ----- |
| BM1      Hồ         |                  | sơ  | nhân | viên |            |      |      |                                       |       |     |     |       |       |     |       |
|                     |                  |     |      |      |            |      |      | BM2                             Thống |       |     |     | kê    | trình | độ  |       |
| Họ và               | tên: ………… Giới   |     |      |      | tính: ………  |      |      |                                       |       |     |     |       |       |     |       |
|                     |                  |     |      |      |            |      |      |                                       | Trình | độ  | Số  | lượng |       |     | Tỷ lệ |
| Ngày                | sinh: ………... Địa |     |      |      | chỉ: ……….. |      |      |                                       |       |     |     |       |       |     |       |
|                     |                  |     |      |      |            |      |      | Trung                                 | cấp   |     |     |       |       |     |       |
| Đơn vị: …………… Trình |                  |     |      |      | độ: ……….   |      |      |                                       |       |     |     |       |       |     |       |
| Ghi chú:            |                  |     |      |      |            |      |      | Cao đẳng                              |       |     |     |       |       |     |       |
| - Tuổi              | nhân             |     | viên | theo | quy        | định |      |                                       |       |     |     |       |       |     |       |
Đại học
| Nam từ |     | 18 đến |       | 60, Nữ | từ     | 18 đến | 55  |     |     |     |     |     |     |     |     |
| ------ | --- | ------ | ----- | ------ | ------ | ------ | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|        |     |        |       |        |        |        |     | Sau | đại | học |     |     |     |     |     |
| - Công | ty  | có     | 5 đơn | vị     | và chỉ | chấp   |     |     |     |     |     |     |     |     |     |
Ghi chú:
| nhận      | 4 trình          |     | độ: Trung |       | cấp, Cao             |           |                      |     |           |             |      |         |      |     |     |
| --------- | ---------------- | --- | --------- | ----- | -------------------- | --------- | -------------------- | --- | --------- | ----------- | ---- | ------- | ---- | --- | --- |
|           |                  |     |           |       |                      |           |                      | Số  | lượng: Số | lượng       | nhân | viên    |      |     |     |
| đẳng, Đại |                  |     | học, Sau  | đại   | học                  |           |                      |     |           |             |      |         |      |     |     |
|           |                  |     |           |       |                      |           |                      | Tỷ  | lệ = Số   | lượng/ Tổng |      | số nhân | viên |     |     |
|           |                  |     | QUY TẮC   |       | KIỂM TRA TÍNH HỢP LỆ |           |                      |     |           |             |      |         |      |     |     |
| Họ và     | tên: không       |     |           | được  | rỗng                 |           |                      |     |           |             |      |         |      |     |     |
| Giới      | tính: Nam hay Nữ |     |           |       |                      |           |                      |     |           |             |      |         |      |     |     |
| Ngày      | sinh: tương      |     |           | ứng   | tuổi                 | từ 20 đến | 40                   |     |           |             |      |         |      |     |     |
| Địa       | chỉ: không       |     | được      | trống |                      |           |                      |     |           |             |      |         |      |     |     |
|           |                  |     |           |       |                      |           | Software Engineering |     |           |             |      |         |      |     | 75  |
tkhuong@dthu.edu.vn

TRA CỨU HỒ SƠ NHÂN VIÊN
| Tên | nhân viên | :…………....… |     |     |
| --- | --------- | ---------- | --- | --- |
(2)
(1)
DANH SÁCH NHÂN VIÊN
| STT            | Họ tên | Giới tính | Địa chỉ | Tuổi   |
| -------------- | ------ | --------- | ------- | ------ |
| 1              | ****** | ******    | ******  | ****** |
| 2              | ****** | ******    | ******  | ****** |
| Mô tả sự kiện: |        |           |         |        |
(1) Load form: phần mềm hiển thị textbox cho phép người dùng nhập
| chuỗi và | danh sách | nhân viên | rỗng |     |
| -------- | --------- | --------- | ---- | --- |
(2) Textbox: Người dùng nhập chuỗi tên cần tìm và phần mềm tìm gần
đúng theo chuỗi nhập, hiển thị thông tin nhân viên vào danh sách
| nhân viên |     |     |     |     |
| --------- | --- | --- | --- | --- |
Software Engineering 76
tkhuong@dthu.edu.vn

|      | Đề   |     | BT2. Xếp |       |     | loại   |        | học | lực | của | học | sinh |
| ---- | ---- | --- | -------- | ----- | --- | ------ | ------ | --- | --- | --- | --- | ---- |
| Phân | tích | yêu | cầu      | (Ngôn |     | ngữ tự | nhiên) |     |     |     |     |      |
❖ Với yêu cầu lập bảng xếp loại học lực, phần mềm bao gồm các
|     | người | sử   | dụng | và    | chức | năng        | như | sau: |        |      |     |     |
| --- | ----- | ---- | ---- | ----- | ---- | ----------- | --- | ---- | ------ | ---- | --- | --- |
| ❖   | Nhân  | viên | văn  | phòng |      | giáo vụ: sử |     | dụng | 2 chức | năng |     |     |
|     | ▪ Ghi | nhận |      | bảng  | điểm |             |     |      |        |      |     |     |
|     | ▪ Lập | bảng |      | xếp   | loại | học lực     |     |      |        |      |     |     |
❖ Ban giám hiệu: chỉ sử dụng 1 chức năng là cập nhật quy tắc xếp loại
|     | học | lực |     |     |     |     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
Ghi chú: Chi tiết các chức năng sẽ mô tả sau, chưa xem xét hết tất cả các chức
năng
Software Engineering 77
tkhuong@dthu.edu.vn

|     | Đề       | BT2. Xếp |          |        |         |      | loại     |       | học      | lực |      | của | học | sinh |
| --- | -------- | -------- | -------- | ------ | ------- | ---- | -------- | ----- | -------- | --- | ---- | --- | --- | ---- |
|     |          |          |          | Bảng   | điểm    | môn  | ….       |       |          |     |      |     |     |      |
|     |          |          | Lớp      | … Niên |         | khóa | …        |       |          |     |      |     |     |      |
|     | Học sinh |          | Điểm     |        | 15 Điểm |      | 1 tiết   |       | Điểm     | HK  |      |     |     |      |
|     | Ghí chú: |          |          |        |         |      |          |       |          |     |      |     |     |      |
|     | - Trường |          | có 9 môn |        | học …   |      |          |       |          |     |      |     |     |      |
|     | Điểm     | 15, điểm |          | 1 tiết | có thể  | có   | nhiều    | cột   |          |     |      |     |     |      |
|     | - Điểm   | số       | là số    | thực   | có giá  | trị  | từ 0 đến |       | 10       |     |      |     |     |      |
|     |          |          |          |        |         | Bảng |          | xếp   | loại học | lực |      |     |     |      |
|     |          |          |          |        |         | Lớp  | … Niên   |       | khóa     | …   |      |     |     |      |
|     | Học sinh |          |          | TBHK1  |         |      |          | TBHK2 |          |     | TBCN |     | Học | lực  |
TBHK1, TBHK2: trung bình cuối học kỳ được tính dựa trên quy tắc tính điểm trung
| bình | học kỳ |     |     |     |     |     |     |     |     |     |     |     |     |     |
| ---- | ------ | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
TBCN: trung bình cuối năm được tính dựa trên quy tắc tính điểm trung bình cuối
năm
| Học | lực: được |     | tính | điểm | dựa | trên | quy | tắc | xếp loại | học | lực |     |     |     |
| --- | --------- | --- | ---- | ---- | --- | ---- | --- | --- | -------- | --- | --- | --- | --- | --- |
Software Engineering 78
tkhuong@dthu.edu.vn

|        | Đề        | BT2. Xếp   |        |        | loại | học | lực          | của         |                  | học     | sinh  |
| ------ | --------- | ---------- | ------ | ------ | ---- | --- | ------------ | ----------- | ---------------- | ------- | ----- |
| Quy    | tắc tính  | điểm trung | bình   | học    | kỳ   |     |              |             |                  |         |       |
|        |           |            |        |        |      |     | Quy tắc      | xếp         | loại             | học lực |       |
| TBHK   | = TTB/SMH |            |        |        |      |     |              |             |                  |         |       |
|        |           |            |        |        |      |     | TBCN         | < 5.0: Loại |                  | Yếu     |       |
|        |           |            |        |        |      |     | TBCN >= 5 và |             | TBCN < 6.5: Loại |         | Trung |
| SMH là | số môn    | học (hiện  | nay là | 9 môn) |      |     |              |             |                  |         |       |
bình
| TTB | là tổng trung | bình | các môn | (TBMH) |     |     |                 |     |                |      |     |
| --- | ------------- | ---- | ------- | ------ | --- | --- | --------------- | --- | -------------- | ---- | --- |
|     |               |      |         |        |     |     | TBCN >= 6.5 và  |     | TBCN < 8: Loại |      | Khá |
|     |               |      |         |        |     |     | TBCN >= 8: Loại |     |                | Giỏi |     |
TBMH = (TB15 + 2*TB1T + 3*DHK)/6
| TB15 là | trung | bình của             | các bài | kiểm  | tra        |     |     |     |     |     |     |
| ------- | ----- | -------------------- | ------- | ----- | ---------- | --- | --- | --- | --- | --- | --- |
| thường  | xuyên |                      |         |       |            |     |     |     |     |     |     |
| TB1T là | trung | bình của             | các bài | kiểm  | tra 1 tiết |     |     |     |     |     |     |
| DHK là  | điểm  | thi cuối học         | kỳ      |       |            |     |     |     |     |     |     |
|         | Quy   | tắc tính             | điểm    | trung | bình cuối  | năm |     |     |     |     |     |
|         | TBCN  | = TBHK1 + 2*TBHK2)/3 |         |       |            |     |     |     |     |     |     |
Software Engineering 79
tkhuong@dthu.edu.vn

| Đề  | bài | BT3 |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- |
❖ Xét phần mềm Quản lý thu chi với yêu cầu chính là Thống kê doanh
thu tháng. Hãy phân tích thiết kế với công nghệ Windows, xử lý dùng
| đơn thể | và lưu | trữ dùng | CSDL quan | hệ  |       |     |
| ------- | ------ | -------- | --------- | --- | ----- | --- |
| PHÂN    | TÍCH   |          |           |     | THIẾT | KẾ  |
Software Engineering 80
tkhuong@dthu.edu.vn

| Câu | hỏi | thảo | luận |
| --- | --- | ---- | ---- |
Questions
Software Engineering 90
tkhuong@dthu.edu.vn