LOGO
KHOA KỸ THUẬT – CÔNG NGHỆ
Chương 5
THIẾT KẾ PHẦN MỀM
– HƯỚNG ĐỐI TƯỢNG
GV biên soạn: Trần Kim Hương
tkhuong@dthu.edu.vn
Software Engineering
tkhuong@dthu.edu.vn

NỘI DUNG
KỸ THUẬT HƯỚNG ĐỐI TƯỢNG
THIẾT KẾ
THIẾT KẾ ĐỐI TƯỢNG
PHẦN
MỀM
HĐT
THIẾT KẾ DỮ LIỆU
Software Engineering 2
tkhuong@dthu.edu.vn

1. KỸ THUẬT HƯỚNG ĐỐI TƯỢNG
| ❖   | Hiện  |       | đang |       | trở nên   |      | phổ        | biến  |     |      |        |
| --- | ----- | ----- | ---- | ----- | --------- | ---- | ---------- | ----- | --- | ---- | ------ |
| ❖   | Là    | một   | cách |       | tiếp      | cận  | khác, nhìn |       |     | nhận | hệ     |
|     | thống |       | theo |       | các       | quan | điểm:      |       |     |      |        |
|     | ▪     | Tập   | các  |       | đối tượng |      | có         | tượng | tác | với  | nhau   |
|     | ▪     | Tương |      | tác   | giữa      | các  | đối        | tượng |     | bằng | truyền |
|     |       | thông |      | báo   |           |      |            |       |     |      |        |
|     | ▪     | Các   | đối  | tượng |           | có   | thể kế     | thừa  |     | nhau |        |
Software Engineering 3
tkhuong@dthu.edu.vn

1. KỸ THUẬT HƯỚNG ĐỐI TƯỢNG
| ❖ Đối | tượng         | phần   | mềm:  |
| ----- | ------------- | ------ | ----- |
| ▪     | Dữ liệu       | (thuộc | tính) |
| ▪     | Xử lý (phương |        | thức) |
Software Engineering 4
tkhuong@dthu.edu.vn

|     | Ưu       | điểm    |         | của       | OOD      |        |       |      |      |          |
| --- | -------- | ------- | ------- | --------- | -------- | ------ | ----- | ---- | ---- | -------- |
| ❖   | Dễ bảo   | trì:    | các     | đối tượng | được     | hiểu   | như   | các  | thực | thể hoạt |
|     | động     | độc     | lập     |           |          |        |       |      |      |          |
|     | ▪ Bao    | gói     | thông   | tin       |          |        |       |      |      |          |
|     | ▪ Liên   | kết     | lỏng    | lẻo (trao | đổi bằng | truyền | thông | báo) |      |          |
| ❖   | Dễ tái   | sử dụng |         |           |          |        |       |      |      |          |
|     | ▪ Độ     | độc     | lập cao |           |          |        |       |      |      |          |
|     | ▪ Có     | khả     | năng    | kế thừa   |          |        |       |      |      |          |
| ❖   | Dễ hiểu: |         |         |           |          |        |       |      |      |          |
▪ Một vài hệ thống có sự ánh xạ tường minh giữa thế giới thực và
|     | đối | tượng | hệ  | thống |     |     |     |     |     |     |
| --- | --- | ----- | --- | ----- | --- | --- | --- | --- | --- | --- |
Software Engineering 5
tkhuong@dthu.edu.vn

| Nội | dung của |     |     | OOD |     |     |     |
| --- | -------- | --- | --- | --- | --- | --- | --- |
❖ Xác định các tập đối tượng (gọi là lớp) và các đặc trưng của
chúng
| ❖ Phân  | định vai | trò   | và trách | nhiệm | của chúng | trong   | hệ thống  |
| ------- | -------- | ----- | -------- | ----- | --------- | ------- | --------- |
| ❖ Thiết | lập được | sự    | tương    | tác   | của chúng | để thực | hiện chức |
| năng    | của hệ   | thống | phần     | mềm   | đặt ra    |         |           |
Software Engineering 6
tkhuong@dthu.edu.vn

| ❖ Các | lớp đối  | tượng |           |        |
| ----- | -------- | ----- | --------- | ------ |
| ▪     | Bạn nhìn | thấy  | bao nhiêu | class? |
tkhuong@dthu.edu.vn

NỘI DUNG
KỸ THUẬT HƯỚNG ĐỐI TƯỢNG
THIẾT KẾ
THIẾT KẾ ĐỐI TƯỢNG
PHẦN
MỀM
HĐT
THIẾT KẾ DỮ LIỆU
Software Engineering 8
tkhuong@dthu.edu.vn

2. THIẾT KẾ ĐỐI TƯỢNG
|         |     | Quy trình | thiết kế | đối tượng |        |
| ------- | --- | --------- | -------- | --------- | ------ |
| Mô hình |     |           | 1.       |           | 2.     |
| hướng   | đối | Xác       | định đối | Vẽ sơ     | đồ lớp |
|         |     | tượng     |          | đối       | tượng  |
tượng!!!
Software Engineering 9
tkhuong@dthu.edu.vn

|       | Xác     | định | đối    | tượng |     |
| ----- | ------- | ---- | ------ | ----- | --- |
| ❖ Đối | với các | thực | thể sự | vật:  |     |
▪ Kiểm xem có nhu cầu quản lý thông tin về thực thể này trong hệ
|     | thống | không? |     |     |     |
| --- | ----- | ------ | --- | --- | --- |
▪ Nếu có, xác định một lớp trong sơ đồ phân tích biểu diễn cho
|     | thực thể | này.     |          |        |     |
| --- | -------- | -------- | -------- | ------ | --- |
|     | • Xác    | định tên | lớp: tên | của sự | vật |
• Thuôc tính: bổ sung các thuộc tính mô tả đầy đủ thông tin mà hệ
|     | thống | có nhu | cầu quản | lý về | đối tượng. |
| --- | ----- | ------ | -------- | ----- | ---------- |
tkhuong@dthu.edu.vn

| Xác | định | đối | tượng |
| --- | ---- | --- | ----- |
❖ Ví dụ:
tkhuong@dthu.edu.vn

|     | Xác |       | định  |        | đối    |       | tượng |        |            |          |      |         |      |       |      |
| --- | --- | ----- | ----- | ------ | ------ | ----- | ----- | ------ | ---------- | -------- | ---- | ------- | ---- | ----- | ---- |
| ❖   | Đối | với   | thực  | thể    | thông  |       | tin:  |        |            |          |      |         |      |       |      |
|     | ▪   | Nếu   | thực  | thể    | mô tả  | thông |       | tin về |            | một      | hoạt | động    | giao | dịch  | hệ   |
|     |     | thống | thì   | chuyển | thành  |       | một   |        | lớp        | trong    | mô   | hình    | phân | tích. |      |
|     | ▪   | Nếu   | thực  | thể    | là một | dạng  |       | thông  |            | tin tổng |      | hợp     | → có | thể   | tách |
|     |     | thành | nhiều | lớp    | mới    |       | hoặc  | bổ     | sung thông |          |      | tin cho | các  | lớp   | đang |
|     |     | tồn   | tại.  |        |        |       |       |        |            |          |      |         |      |       |      |
| ❖   | Ví  | dụ:   |       |        |        |       |       |        |            |          |      |         |      |       |      |
tkhuong@dthu.edu.vn

| Xác   | định     | đối       | tượng |
| ----- | -------- | --------- | ----- |
| ❖ Đối | với thực | thể thông | tin:  |
| ▪     | Ví dụ:   |           |       |
tkhuong@dthu.edu.vn

| Xác     |     | định | đối      | tượng |            |          |     |
| ------- | --- | ---- | -------- | ----- | ---------- | -------- | --- |
| ❖ Đối   | với | thừa | tác viên | và    | tác nhân:  |          |     |
| NV quan | ly  | Thủ  | kho      |       | Khách hàng | Nhà cung | cấp |
|         |     |      |          | Khách | hàng       | Nhà cung | cấp |
Nhân Viên
tkhuong@dthu.edu.vn

2. THIẾT KẾ ĐỐI TƯỢNG
|         |     | Quy trình | thiết kế | đối tượng |        |
| ------- | --- | --------- | -------- | --------- | ------ |
| Mô hình |     |           | 1.       |           | 2.     |
| hướng   | đối | Xác       | định đối | Vẽ sơ     | đồ lớp |
|         |     | tượng     |          | đối       | tượng  |
tượng!!!
Software Engineering 15
tkhuong@dthu.edu.vn

|     | Lớp |     | đối   |     | tượng |     |      | (Class) |     |     |     |     |     |
| --- | --- | --- | ----- | --- | ----- | --- | ---- | ------- | --- | --- | --- | --- | --- |
| ❖   | Lớp | đối | tượng |     | (nhắc |     | lại) |         |     |     |     |     |     |
▪
|     |     | Tập  | hợp  | các  | đối   | tượng |      | chia        |          | sẻ chung   | cấu trúc  | (các | thuộc  |
| --- | --- | ---- | ---- | ---- | ----- | ----- | ---- | ----------- | -------- | ---------- | --------- | ---- | ------ |
|     |     | tính | và   | mối  | quan  | hệ)   | và   | hành        |          | vi.        |           |      |        |
|     | ▪   | Lớp  | là   | trừu | tượng |       | hóa  | các         |          | đối tượng, | đối tượng |      | là thể |
|     |     | hiện | của  | lớp  |       |       |      |             |          |            |           |      |        |
|     | ▪   | Biểu | diễn | một  | lớp   |       | đối  | tượng:      |          |            |           |      |        |
|     |     | •    | Tên  | lớp  |       |       |      |             |          |            |           |      |        |
|     |     | •    | Danh | sách | thuộc |       | tính | (attribute) |          |            |           |      |        |
|     |     | •    | Danh | sách | các   | hoạt  |      | động        | (method) |            |           |      |        |
tkhuong@dthu.edu.vn

|     | Sơ  | đồ  | lớp | đối | tượng |     | (class diagram) |
| --- | --- | --- | --- | --- | ----- | --- | --------------- |
❖ Là một hình thức biểu diễn lớp đối tượng (tên, thuộc tính, hành vi)
| và     | quan   | hệ   | giữa chúng | một       | cách | trực      | quan. |
| ------ | ------ | ---- | ---------- | --------- | ---- | --------- | ----- |
| ❖ Biểu | diễn   | sơ   | đồ lớp     | đối tượng |      | bằng UML: |       |
|        | ▪ Biểu | diễn | lớp        |           |      |           |       |
tkhuong@dthu.edu.vn

|     | Sơ   |      | đồ  |     | lớp  |     | đối |      | tượng          |     |       | (class diagram) |       |            |     |
| --- | ---- | ---- | --- | --- | ---- | --- | --- | ---- | -------------- | --- | ----- | --------------- | ----- | ---------- | --- |
| ❖   | Biểu | diễn |     | sơ  | đồ   | lớp | đối |      | tượng          |     | bằng  | UML(tt):        |       |            |     |
|     | ▪    | Mối  | kết | hợp | giữa |     | các | lớp  | (Association): |     |       |                 |       |            |     |
|     |      | •    | Mối | kết | hợp  | có  | thể | giữa | các            | đối | tượng | của             | 2 lớp | đối tượng. |     |
• Nếu 2 đối tượng của 2 lớp có mối kết hợp thì giữa 2 lớp có mối kết
hợp.
|     | ▪   | Một  | sơ  | đồ  | lớp | đối | tượng |     | sẽ  | bao | gồm | các | lớp | và các quan | hệ  |
| --- | --- | ---- | --- | --- | --- | --- | ----- | --- | --- | --- | --- | --- | --- | ----------- | --- |
|     |     | giữa |     | các | lớp |     |       |     |     |     |     |     |     |             |     |
|     | ▪   | Bản  | số  | của | mối |     | kết   | hợp |     |     |     |     |     |             |     |
tkhuong@dthu.edu.vn

|     | Sơ  | đồ   | lớp    | đối | tượng |         | (class diagram) |     |
| --- | --- | ---- | ------ | --- | ----- | ------- | --------------- | --- |
| ❖   | Xác | định | bản số | cho | mối   | kết hợp | (min,max):      |     |
▪ 1; 0..1
▪ 1..*
▪ 0..*
|     | ▪   | a..* : a là | hằng | số  |     |     |     |     |
| --- | --- | ----------- | ---- | --- | --- | --- | --- | --- |
▪ 1 = 1..1
| Diễn  | giải: |     |          |     |     |     |                  |     |
| ----- | ----- | --- | -------- | --- | --- | --- | ---------------- | --- |
| ✓ Một | bản   | yêu | cầu được | gửi | tới | cho | duy nhất 1 phòng | ban |
✓ Một phòng ban có thể có từ 0 → nhiều (0..*) bản yêu cầu gửi tới
tkhuong@dthu.edu.vn

| Ví    | dụ      |          |          |
| ----- | ------- | -------- | -------- |
| Sơ đồ | lớp của | hệ thống | bán hàng |
Software Engineering 20
tkhuong@dthu.edu.vn

NỘI DUNG
KỸ THUẬT HƯỚNG ĐỐI TƯỢNG
THIẾT KẾ
THIẾT KẾ ĐỐI TƯỢNG
PHẦN
MỀM
HĐT
THIẾT KẾ DỮ LIỆU
Software Engineering 22
tkhuong@dthu.edu.vn

3. THIẾT KẾ DỮ LIỆU
| ❖   | Kiến        | thức: các |      |       | công |      | nghệ | lưu trữ |
| --- | ----------- | --------- | ---- | ----- | ---- | ---- | ---- | ------- |
| ❖   | Kỹ năng: tổ |           |      | chức  |      | lưu  | trữ  | dữ liệu |
| ❖   | Nội         | dung:     |      |       |      |      |      |         |
|     | ▪ Thành     |           | phần |       | lưu  | trữ  |      |         |
|     | ▪ Thiết     |           | kế   | thành |      | phần | lưu  | trữ     |
|     | ▪ Thiết     |           | kế   | xử    | lý   | lưu  | trữ  |         |
Software Engineering 23
tkhuong@dthu.edu.vn

| 3.1 Thành |     |     | phần | lưu | trữ | - Khái | niệm |     |
| --------- | --- | --- | ---- | --- | --- | ------ | ---- | --- |
❖ Khái niệm:
| ▪ Thành | phần          | chịu | trách | nhiệm    | lưu trữ   | tất cả | các dữ | liệu cần |
| ------- | ------------- | ---- | ----- | -------- | --------- | ------ | ------ | -------- |
| thiết   | cho sự        | hoạt | động  | của phần | mềm       |        |        |          |
| • Dữ    | liệu do người |      | dùng  | cung     | cấp       |        |        |          |
| • Dữ    | liệu do người |      | dùng  | tính     | toán phát | sinh   |        |          |
| • Dữ    | liệu nội      | bộ   |       |          |           |        |        |          |
Software Engineering 24
tkhuong@dthu.edu.vn

|     | 3.1 Thành |     |     | phần |     | lưu | trữ |     | - Tổ | chức |     |     |
| --- | --------- | --- | --- | ---- | --- | --- | --- | --- | ---- | ---- | --- | --- |
❖ Tổ chức:
| ▪   | Thành | phần    | lưu | trữ | bao   | gồm | các  | đơn | vị lưu  | trữ | dữ   | liệu   |
| --- | ----- | ------- | --- | --- | ----- | --- | ---- | --- | ------- | --- | ---- | ------ |
| ▪   | Mỗi   | đơn vị  | lưu | trữ | tương | ứng | vùng | nhớ | trên    | bộ  | nhớ  | phụ và |
|     | có    | thể bao | gồm | bên | trong | các | đơn  | vị  | lưu trữ | dữ  | liệu | thành  |
phần
|     | Thông | tin  |     |     |     |     |     |     |     |        |     |     |
| --- | ----- | ---- | --- | --- | --- | --- | --- | --- | --- | ------ | --- | --- |
|     |       |      |     |     |     |     |     |     | Đơn | vị lưu | trữ | dữ  |
Chọn
| trong | thực   | tế và |     |     |     |     |     |     | liệu    | với các | “đơn | vị   |
| ----- | ------ | ----- | --- | --- | --- | --- | --- | --- | ------- | ------- | ---- | ---- |
| các   | “thông | tin   |     |     |     |     |     |     | lưu trữ | dữ      | liệu | con” |
con”
Software Engineering 25
tkhuong@dthu.edu.vn

|     | 3.1 Thành |     |      |      | phần    |     | lưu |     | trữ | - Công |     | nghệ |
| --- | --------- | --- | ---- | ---- | ------- | --- | --- | --- | --- | ------ | --- | ---- |
| ❖   | Công      |     | nghệ | lưu  | trữ:    |     |     |     |     |        |     |      |
| Có  | 2 loại    |     | công | nghệ | chính   |     |     |     |     |        |     |      |
|     | ▪         | Lưu | trữ  | với  | tập tin |     |     |     |     |        |     |      |
.txt
|     |     | •   | Tập | tin nhị | phân |     | .html |     |     |      |           |     |
| --- | --- | --- | --- | ------- | ---- | --- | ----- | --- | --- | ---- | --------- | --- |
|     |     |     |     |         |      |     |       |     |     | Khác | nhau????? |     |
.xml
.xls
|     |     | •   | Tập | tin văn | bản |     |     |     | .doc |     |     |     |
| --- | --- | --- | --- | ------- | --- | --- | --- | --- | ---- | --- | --- | --- |
.jpg
|     | ▪   | Lưu | trữ        | với | Cơ sở | dữ    | liệu |     |           |     |      |         |
| --- | --- | --- | ---------- | --- | ----- | ----- | ---- | --- | --------- | --- | ---- | ------- |
|     |     | •   | CSDL quan  |     | hệ    |       |      | Có  | bao nhiêu | mô  | hình | CSDL??? |
|     |     | •   | CSDL hướng |     | đối   | tượng |      |     |           |     |      |         |
Software Engineering 26
tkhuong@dthu.edu.vn

| 3.1 Thành |     | phần |     | lưu | trữ | -   | Công |     | nghệ |     |
| --------- | --- | ---- | --- | --- | --- | --- | ---- | --- | ---- | --- |
❖ Tập tin XML
| ▪ Bao      | gồm bên | trong  | các  | thẻ | (tag), mỗi |     | thẻ có  | thể | có  | nhiều |
| ---------- | ------- | ------ | ---- | --- | ---------- | --- | ------- | --- | --- | ----- |
| thuộc      | tính và | có thể | bao  | gồm | bên trong  |     | nhiều   | thẻ |     | con   |
| Thông      | tin     |        |      |     |            |     |         |     |     |       |
|            |         |        |      |     |            |     | Các thẻ | của | tập | tin   |
| trong thực | tế      |        | Chọn |     |            |     |         |     |     |       |
XML
Software Engineering 27
tkhuong@dthu.edu.vn

|     |       | 3.1 Thành |      |           | phần  |      | lưu  | trữ     | - Công       | nghệ     |     |
| --- | ----- | --------- | ---- | --------- | ----- | ---- | ---- | ------- | ------------ | -------- | --- |
| ❖   | Lưu   | trữ       | với  | CSDL quan |       |      | hệ   |         |              |          |     |
|     | ▪     | Bao       | gồm  | bên       | trong | các  | bảng | dữ liệu | (table). Mỗi | bảng     | có  |
|     |       | nhiều     | cột  | và        | nhiều | dòng |      |         |              |          |     |
|     | Thông |           | tin  |           |       |      |      |         |              |          |     |
|     |       |           |      |           |       |      |      |         | Các dòng     | của bảng |     |
Chọn
|     | trong | thực | tế  |     |     |     |     |     | trong CSDL quan |     | hệ  |
| --- | ----- | ---- | --- | --- | --- | --- | --- | --- | --------------- | --- | --- |
Software Engineering 28
tkhuong@dthu.edu.vn

| 3.2 Thiết |                 |       |       | kế     | thành    |       |      | phần |      |       |      | lưu     |      | trữ       |
| --------- | --------------- | ----- | ----- | ------ | -------- | ----- | ---- | ---- | ---- | ----- | ---- | ------- | ---- | --------- |
| ❖ Khái    | niệm            |       |       |        |          |       |      |      |      |       |      |         |      |           |
| ▪ Mô      | tả các          | đơn   |       | vị lưu | trữ      | theo  | công |      | nghệ |       | được |         | chọn |           |
| ▪ Lưu     | ý: chọn         |       | công  | nghệ   |          | thích | hợp  |      | loại | thông |      | tin cần |      | dùng      |
| về        | dung lượng, bảo |       |       |        | mật, tốc |       | độ,… |      |      |       |      |         |      |           |
|           | Phụ             | trách | thiết | kế     |          |       |      |      |      |       |      | Hồ      | sơ   |           |
|           |                 | Dữ    | liệu  |        |          |       |      |      |      |       |      | phân    |      | tích      |
|           |                 |       |       |        |          |       |      |      |      |       |      | Các     | công |           |
| Hồ sơ     | thiết           |       |       |        |          |       |      |      |      |       |      | nghệ    | lưu  | trữ       |
| kế dữ     | liệu            |       |       |        |          |       |      |      |      |       |      |         |      |           |
|           |                 |       |       |        |          | Có    | thể  | chọn | và   | kết   | hợp  | nhiều   | loại | công nghệ |
Software Engineering 29
tkhuong@dthu.edu.vn

|            | 3.2 Thiết |           | kế          | thành          |         | phần  |      | lưu | trữ      |     |
| ---------- | --------- | --------- | ----------- | -------------- | ------- | ----- | ---- | --- | -------- | --- |
| Các        | bước      | tiến hành | thiết       | kế             | dữ liệu |       |      |     |          |     |
| ❖ B1. Lập  |           | các sơ    | đồ logic dữ |                | liệu    | thành | phần | cho | từng     | yêu |
| cầu        | nhập      | liệu      |             |                |         |       |      |     |          |     |
| ❖ B2. Tích |           | hợp các   | sơ          | đồ logic thành |         |       | phần | để  | có sơ đồ |     |
logic chung
| ❖ B3. Cải |     | tiến sơ | đồ logic của |     | B2. theo |     | các | yêu | cầu chất |     |
| --------- | --- | ------- | ------------ | --- | -------- | --- | --- | --- | -------- | --- |
lượng
|     |     |     |     | Software Engineering |     |     |     |     |     | 30  |
| --- | --- | --- | --- | -------------------- | --- | --- | --- | --- | --- | --- |
tkhuong@dthu.edu.vn

|         | 3.2 Thiết |            |          |     | kế  |      | thành |     |      | phần  | lưu   |     | trữ  |       |
| ------- | --------- | ---------- | -------- | --- | --- | ---- | ----- | --- | ---- | ----- | ----- | --- | ---- | ----- |
| ❖ Lập   |           | sơ đồ      | logic dữ |     |     | liệu | thành |     | phần |       |       |     |      |       |
|         |           |            |          |     |     |      |       |     |      | Sơ đồ | logic | dữ  | liệu | thành |
| Yêu cầu |           | nhập liệu: |          |     |     |      |       |     |      |       |       |     |      |       |
phần:
| Thông    | tin | về đối     | tượng | X    |     |     |     |     |     |        |        |     |     |       |
| -------- | --- | ---------- | ----- | ---- | --- | --- | --- | --- | --- | ------ | ------ | --- | --- | ----- |
|          |     |            |       |      |     |     |     |     |     | - Bảng | X với  | các | cột | khóa  |
| cần nhập |     | liệu trong |       | thực |     |     |     |     |     |        |        |     |     |       |
|          |     |            |       |      |     |     |     |     |     | chính  | và các | cột | dữ  | liệu, |
tế
|         |      |           |      |       |      | Phụ   | trách     | thiết | kế       | các | cột liên kết |     |     |     |
| ------- | ---- | --------- | ---- | ----- | ---- | ----- | --------- | ----- | -------- | --- | ------------ | --- | --- | --- |
| TH1.    | X là | đối tượng |      | đơn   | giản |       |           |       |          |     |              |     |     |     |
| X không |      | chứa bên  |      | trong | đối  | tượng | con khác  |       |          |     |              |     |     |     |
| TH2.    | X là | đối tượng |      | phức  | hợp  |       |           |       |          |     |              |     |     |     |
| X chứa  |      | bên trong | danh | sách  |      | các   | đối tượng |       | con khác |     |              |     |     |     |
Vd.
| Hồ sơ | đối  | tác      |     |     |     |     |     |     |     |     |     |     |     |     |
| ----- | ---- | -------- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Hồ sơ | nhân | viên     |     |     |     |     |     |     |     |     |     |     |     |     |
| Phiếu | thu  |          |     |     |     |     |     |     |     |     |     |     |     |     |
| Hóa   | đơn  | bán hàng |     |     |     |     |     |     |     |     |     |     |     |     |
Software Engineering 31
tkhuong@dthu.edu.vn

|     | VD. Tiếp |     |     | nhận |     | đối | tác |     |     |     |     |
| --- | -------- | --- | --- | ---- | --- | --- | --- | --- | --- | --- | --- |
❖ Dựa vào hồ sơ phân tích, hãy thiết kế dữ liệu phần mềm quản
| lý   | bán | hàng | khi chỉ | xem | xét | chức | năng | Tiếp | nhận | đối tác |     |
| ---- | --- | ---- | ------- | --- | --- | ---- | ---- | ---- | ---- | ------- | --- |
| ❖ Mô | tả: |      |         |     |     |      |      |      |      |         |     |
Chức năng cho phép nhân viên của cửa hàng ghi nhận thông tin
| về đối      | tác | qua 2 bước |         | như  | sau: |       |        |     |       |         |     |
| ----------- | --- | ---------- | ------- | ---- | ---- | ----- | ------ | --- | ----- | ------- | --- |
| B1. NV cung |     |            | cấp cho | phần | mềm  | thông | tin về |     | hồ sơ | của đối | tác |
B2. Phần mềm tiến hành kiểm tra tính hợp lệ và sau đó ghi nhận
| thông | tin tương |     | ứng | vào bộ | nhớ                  | phụ | (nếu | hợp | lệ) |     |     |
| ----- | --------- | --- | --- | ------ | -------------------- | --- | ---- | --- | --- | --- | --- |
|       |           |     |     |        | Software Engineering |     |      |     |     |     | 32  |
tkhuong@dthu.edu.vn

| VD. Tiếp |     | nhận | đối | tác |     |
| -------- | --- | ---- | --- | --- | --- |
❖ Cấu trúc:
|            |              |                              | Hồ sơ        | đối tác     |     |
| ---------- | ------------ | ---------------------------- | ------------ | ----------- | --- |
|            | Tên:………….... |                              | Điện         | thoại:…………. |     |
|            | Địa          | chỉ: …….....            Ngày |              | tiếp nhận:  | ……  |
|            | Quy          | tắc kiểm                     | tra tính     | hợp lệ      |     |
| Tên: không | được trống…  | Điện                         | thoại: không | được trống  |     |
Địa chỉ: không được trống.. Ngày tiếp nhận: <= ngày hiện hành
Software Engineering 33
tkhuong@dthu.edu.vn

|         | VD. Tiếp |         |     | nhận | đối | tác |     |     |
| ------- | -------- | ------- | --- | ---- | --- | --- | --- | --- |
| ❖ Thiết | kế       | dữ liệu |     |      |     |     |     |     |
Doi_Tac
MaDT: Auto
|     | ▪ Cấu | trúc |     |     |      |        |     |     |
| --- | ----- | ---- | --- | --- | ---- | ------ | --- | --- |
|     |       |      |     |     | Ten: | String |     |     |
|     | ▪ Nội | dung |     |     |      |        |     |     |
DienThoai: String
DiaChi: String
|     |      |      |      |               | NgayTiepNhan: |        |      | Date         |
| --- | ---- | ---- | ---- | ------------- | ------------- | ------ | ---- | ------------ |
|     | MaDT | Ten  |      | DienThoai     |               | DiaChi |      | NgayTiepNhan |
|     | 1    | Công | ty A | 0673. 112 335 | CL,           | Đồng   | Tháp | 17/11/2016   |
|     | 2    | …    |      | ….            | …             |        |      | ….           |
Software Engineering 34
tkhuong@dthu.edu.vn

|      | VD2. Xếp |     |     |       | loại |        | học    | lực | của | học | sinh |
| ---- | -------- | --- | --- | ----- | ---- | ------ | ------ | --- | --- | --- | ---- |
| Phân | tích     | yêu | cầu | (Ngôn |      | ngữ tự | nhiên) |     |     |     |      |
❖ Với yêu cầu lập bảng xếp loại học lực, phần mềm bao gồm các
|     | người | sử   | dụng | và    | chức | năng        | như | sau: |        |      |     |
| --- | ----- | ---- | ---- | ----- | ---- | ----------- | --- | ---- | ------ | ---- | --- |
| ❖   | Nhân  | viên | văn  | phòng |      | giáo vụ: sử |     | dụng | 2 chức | năng |     |
|     | ▪ Ghi | nhận |      | bảng  | điểm |             |     |      |        |      |     |
|     | ▪ Lập | bảng |      | xếp   | loại | học lực     |     |      |        |      |     |
❖ Ban giám hiệu: chỉ sử dụng 1 chức năng là cập nhật quy tắc xếp loại
|     | học | lực |     |     |     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
Ghi chú: Chi tiết các chức năng sẽ mô tả sau, chưa xem xét hết tất cả các chức
năng
Software Engineering 35
tkhuong@dthu.edu.vn

|     | VD2. Xếp |          |          |        | loại    |      | học      |          | lực  |     | của  | học | sinh    |
| --- | -------- | -------- | -------- | ------ | ------- | ---- | -------- | -------- | ---- | --- | ---- | --- | ------- |
|     |          |          |          | Bảng   | điểm    | môn  | ….       |          |      |     |      |     |         |
|     |          |          | Lớp      | … Niên |         | khóa | …        |          |      |     |      |     |         |
|     | Học sinh |          | Điểm     |        | 15 Điểm |      | 1 tiết   | Điểm     |      | HK  |      |     |         |
|     | Ghí chú: |          |          |        |         |      |          |          |      |     |      |     |         |
|     | - Trường |          | có 9 môn |        | học …   |      |          |          |      |     |      |     |         |
|     | Điểm     | 15, điểm |          | 1 tiết | có thể  | có   | nhiều    | cột      |      |     |      |     |         |
|     | - Điểm   | số       | là số    | thực   | có giá  | trị  | từ 0 đến | 10       |      |     |      |     |         |
|     |          |          |          |        |         | Bảng |          | xếp loại | học  | lực |      |     |         |
|     |          |          |          |        |         | Lớp  | … Niên   |          | khóa | …   |      |     |         |
|     | Học sinh |          |          | TBHK1  |         |      |          | TBHK2    |      |     | TBCN |     | Học lực |
TBHK1, TBHK2: trung bình cuối học kỳ được tính dựa trên quy tắc tính điểm trung
| bình | học kỳ |     |     |     |     |     |     |     |     |     |     |     |     |
| ---- | ------ | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
TBCN: trung bình cuối năm được tính dựa trên quy tắc tính điểm trung bình cuối
năm
| Học | lực: được |     | tính | điểm | dựa | trên | quy | tắc xếp | loại | học | lực |     |     |
| --- | --------- | --- | ---- | ---- | --- | ---- | --- | ------- | ---- | --- | --- | --- | --- |
Software Engineering 36
tkhuong@dthu.edu.vn

|          | BÀI TẬP thiết |          |      | kế dữ |      | liệu  |         |      |
| -------- | ------------- | -------- | ---- | ----- | ---- | ----- | ------- | ---- |
| 1) Thiết | kế dữ         | liệu cho | chức | năng  | Lập  | phiếu | thu     |      |
| 2) Thiết | kế dữ         | liệu cho | chức | năng  | Tiếp | nhận  | nhân    | viên |
| 3) Thiết | kế dữ         | liệu cho | chức | năng  | Lập  | hóa   | đơn bán | hàng |
Software Engineering 37
tkhuong@dthu.edu.vn

|     | Đề  |     | bài | tập |     | 1   |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
❖ Dựa vào hồ sơ phân tích, hãy thiết kế dữ liệu phần mềm quản
| lý   | bán | hàng | khi | chỉ | xem | xét | chức | năng | Lập | phiếu | thu |
| ---- | --- | ---- | --- | --- | --- | --- | ---- | ---- | --- | ----- | --- |
| ❖ Mô | tả: |      |     |     |     |     |      |      |     |       |     |
Chức năng cho phép nhân viên của cửa hàng ghi nhận thông tin
| về phiếu    |     | thu | qua 2 bước |     |      | như | sau:  |        |     |       |     |
| ----------- | --- | --- | ---------- | --- | ---- | --- | ----- | ------ | --- | ----- | --- |
| B1. NV cung |     |     | cấp        | cho | phần | mềm | thông | tin về |     | phiếu | thu |
B2. Phần mềm tiến hành kiểm tra tính hợp lệ và sau đó ghi nhận
| thông | tin tương |     | ứng |     | vào | bộ nhớ | phụ | (nếu | hợp | lệ) |     |
| ----- | --------- | --- | --- | --- | --- | ------ | --- | ---- | --- | --- | --- |
Software Engineering 38
tkhuong@dthu.edu.vn

| Đề  | bài |     | tập | 1   |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
❖ Cấu trúc:
|     |     |     |                                     |     | Phiếu | thu | tiền       |            |
| --- | --- | --- | ----------------------------------- | --- | ----- | --- | ---------- | ---------- |
|     |     | Họ  | và Tên:…………....                     |     |       |     | CMND:…………. |            |
|     |     | Địa | chỉ: ……..............          Ngày |     |       |     |            | thu: ……... |
Số tiền: ………………
|         |       |      | Quy    | tắc | kiểm tra   | tính | hợp   | lệ  |
| ------- | ----- | ---- | ------ | --- | ---------- | ---- | ----- | --- |
| Họ Tên: | không | được | trống… |     | CMND: được |      | trống |     |
Địa chỉ: được trống..                Ngày thu: <=ngày hiện hành
| Số tiền: không |     | được | rỗng |     |     |     |     |     |
| -------------- | --- | ---- | ---- | --- | --- | --- | --- | --- |
Software Engineering 39
tkhuong@dthu.edu.vn

|         | Giải |     | bài  |     | tập |     | 1   |     |     |     |     |     |     |
| ------- | ---- | --- | ---- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ❖ Thiết | kế   | dữ  | liệu |     |     |     |     |     |     |     |     |     |     |
KhachHang
|     |     |      |     |            |             | Phiếu |      | thu        |           |     |          |                |        |
| --- | --- | ---- | --- | ---------- | ----------- | ----- | ---- | ---------- | --------- | --- | -------- | -------------- | ------ |
|     |     |      |     |            | MaPT: Auto  |       |      |            |           |     |          | MaKH: Auto     |        |
| ▪   | Cấu | trúc |     |            |             |       |      |            |           |     |          |                |        |
|     |     |      |     |            | Ngaylap:    |       | Date |            |           |     |          | HoTen:         | String |
| ▪   | Nội | dung |     |            |             |       |      |            |           |     |          |                |        |
|     |     |      |     |            | SoTien: Int |       |      |            |           |     |          | CMND: String   |        |
|     |     |      |     |            | MaKH: Int   |       |      |            |           |     |          | DiaChi: String |        |
|     |     | MaPT |     |            | Ngaylap     |       |      |            | SoTien    |     | MaKH     |                |        |
|     |     | 1    |     | 17/11/2016 |             |       |      | 20.000.000 |           | 2   |          |                |        |
|     |     | MaKH |     |            |             | HoTen |      |            | CMND      |     | DiaChi   |                |        |
|     |     | 1    |     | Nguyễn     |             | Văn   | An   |            | 112345678 |     | CL, Đồng | Tháp           |        |
|     |     | 2    |     | …          |             |       |      |            | ….        |     | …        |                |        |
Software Engineering 40
tkhuong@dthu.edu.vn

|     | Đề  | bài |     | tập |     | 2   |     |     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
❖ Dựa vào hồ sơ phân tích, hãy thiết kế dữ liệu phần mềm quản
| lý           | bán   | hàng   | khi | chỉ  | xem  |      | xét chức   | năng     |            | Tiếp | nhận  |      | Nhân   | viên   |
| ------------ | ----- | ------ | --- | ---- | ---- | ---- | ---------- | -------- | ---------- | ---- | ----- | ---- | ------ | ------ |
| ❖ Mô         | tả:   |        |     |      |      |      |            |          |            |      |       |      |        |        |
| Chức         | năng  | cho    |     | phép | nhân |      | viên phòng |          | tổ         | chức | của   | công |        | ty ghi |
| nhận         | thông | tin về |     | hồ   | sơ   | của  | nhân       | viên     | qua 2 bước |      |       | như  | sau:   |        |
| B1. NV phòng |       |        | tổ  | chức |      | cung | cấp        | cho phần |            | mềm  | thông |      | tin về | hồ     |
| sơ nhân      |       | viên   |     |      |      |      |            |          |            |      |       |      |        |        |
B2. Phần mềm tiến hành kiểm tra tính hợp lệ và sau đó ghi thông
| tin tương |     | ứng | vào | bộ  | nhớ |     | phụ (nếu | hợp |     | lệ) |     |     |     |     |
| --------- | --- | --- | --- | --- | --- | --- | -------- | --- | --- | --- | --- | --- | --- | --- |
Software Engineering 42
tkhuong@dthu.edu.vn

| Đề  | bài | tập | 2   |       |      |      |     |
| --- | --- | --- | --- | ----- | ---- | ---- | --- |
|     |     |     |     | Hồ sơ | Nhân | viên |     |
❖ Cấu trúc:
|     |     | Họ                                   | và Tên:………….... |     |     | Giới | tính:………….  |
| --- | --- | ------------------------------------ | --------------- | --- | --- | ---- | ----------- |
|     |     | CMND: ……..............          Ngày |                 |     |     |      | sinh: ……... |
Địa chỉ: ………………
|         |       | Trinh độ: …………….         Đơn |         |                       |      |     | vị:………….. |
| ------- | ----- | ---------------------------- | ------- | --------------------- | ---- | --- | --------- |
|         |       |                              | Quy tắc | kiểm tra              | tính | hợp | lệ        |
| Họ Tên: | không | được                         | trống…  | Giới tính: Nam hay Nữ |      |     |           |
CMND: không được trống..       Ngày sinh: tương ứng độ tuổi từ 20-50
| Địa chỉ: không |     | được | rỗng………….. |     |     |     |     |
| -------------- | --- | ---- | ---------- | --- | --- | --- | --- |
Trình độ: 1 trong 3 trình độ Cao đẳng, Đại học và Sau đại học
| Đơn vị: 1 trong |     | các | đơn vị hiện | nay của | công | ty  |     |
| --------------- | --- | --- | ----------- | ------- | ---- | --- | --- |
Software Engineering 43
tkhuong@dthu.edu.vn

|     | Đề  |     | bài | tập |     | 3   |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
❖ Dựa vào hồ sơ phân tích, hãy thiết kế dữ liệu phần mềm quản
| lý   | bán | hàng | khi | chỉ | xem | xét | chức | năng | Lập | hóa | đơn |
| ---- | --- | ---- | --- | --- | --- | --- | ---- | ---- | --- | --- | --- |
| ❖ Mô | tả: |      |     |     |     |     |      |      |     |     |     |
Chức năng cho phép nhân viên của cửa hàng ghi nhận thông tin
| lập hóa     |     | đơn | qua 2 bước |     |      | như | sau:  |     |        |      |             |
| ----------- | --- | --- | ---------- | --- | ---- | --- | ----- | --- | ------ | ---- | ----------- |
| B1. NV cung |     |     | cấp        | cho | phần | mềm | thông |     | tin về | việc | lập hóa đơn |
B2. Phần mềm tiến hành kiểm tra tính hợp lệ và sau đó ghi thông
| tin tương |     | ứng | vào | bộ  | nhớ | phụ | (nếu | hợp | lệ) |     |     |
| --------- | --- | --- | --- | --- | --- | --- | ---- | --- | --- | --- | --- |
Software Engineering 47
tkhuong@dthu.edu.vn

|       |      | Đề  |       | bài   |       | tập             |                    | 3    |          |          |      |       |          |     |
| ----- | ---- | --- | ----- | ----- | ----- | --------------- | ------------------ | ---- | -------- | -------- | ---- | ----- | -------- | --- |
|       |      |     |       |       |       |                 |                    | Hóa  | đơn      | bán hàng |      |       |          |     |
| ❖     | Cấu  |     | trúc: |       |       |                 |                    |      |          |          |      |       |          |     |
|       |      |     |       |       |       | Khách           | hàng:…………....……... |      |          |          |      |       |          |     |
|       |      |     |       |       |       | Địa chỉ: ……………… |                    |      |          |          |      |       |          |     |
|       |      |     |       |       |       | Ngày            | lập:…………….         |      |          |          |      |       |          |     |
|       |      |     |       |       |       | STT             | Mặt                | hàng | Số lượng | Đơn      | giá  | Thành | tiền     |     |
|       |      |     |       |       |       | 1               | …..                |      | …..      | ….       |      | ……    |          |     |
|       |      |     |       |       |       |                 |                    |      |          |          | Tổng |       | tiền: …. |     |
|       | Quy  | tắc | kiểm  | tra   | tính  | hợp             | lệ                 |      |          |          |      |       |          |     |
| Khách | hàng |     | (Họ   | Tên): | không | được            |                    |      |          |          |      |       |          |     |
|       |      |     |       |       |       |                 |                    |      |          |          | Quy  | tắc   | xử lý    |     |
trống…
|     |               |     |        |     |     |      |      |     | Đơn giá   | =  theo    | quy   | định     | của công  | ty (k nhập) |
| --- | ------------- | --- | ------ | --- | --- | ---- | ---- | --- | --------- | ---------- | ----- | -------- | --------- | ----------- |
| Địa | chỉ: được     |     | trống… |     |     |      |      |     |           |            |       |          |           |             |
|     |               |     |        |     |     |      |      |     | Thành     | tiền =  số | lượng |          | * Đơn giá |             |
| Mặt | hàng: 1 trong |     |        | các | mặt | hàng | hiện | có  |           |            |       |          |           |             |
|     |               |     |        |     |     |      |      |     | Tổng tiền | =   tổng   |       | tiền của | từng mặt  | hàng        |
| của | công          | ty  |        |     |     |      |      |     |           |            |       |          |           |             |
Số lượng: >0
Software Engineering 48
tkhuong@dthu.edu.vn

| Câu | hỏi | thảo | luận |
| --- | --- | ---- | ---- |
Questions
Software Engineering 52
tkhuong@dthu.edu.vn