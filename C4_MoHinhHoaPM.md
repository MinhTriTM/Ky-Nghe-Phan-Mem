LOGO
KHOA KỸ THUẬT – CÔNG NGHỆ
Chương 4
MÔ HÌNH HÓA
PHẦN MỀM
GV biên soạn: Trần Kim Hương
tkhuong@dthu.edu.vn
Software Engineering
tkhuong@dthu.edu.vn

NỘI DUNG
KHÁI NIỆM MÔ HÌNH HÓA
MÔ HÌNH NGHIỆP VỤ
MÔ
HÌNH
HÓA PM
MÔ HÌNH QUAN NIỆM
MÔ HÌNH YÊU CẦU
Software Engineering 2
tkhuong@dthu.edu.vn

MỤC TIÊU
❖ Hiểu được mô hình hoá hệ thống là gì? Và tại sao phải mô
hình hoá hệ thống.
❖ Phân biệt được các mô hình hệ thống.
❖ Có khả năng lựa chọn và ứng dụng các mô hình hệ thống vào
từng trường hợp cụ thể
❖ Lập hồ sơ phân tích yêu cầu bằng mô hình UseCase
Software Engineering 3
tkhuong@dthu.edu.vn

|     | Các   |      | giai |        | đoạn | phân         | tích  | yêu  | cầu |
| --- | ----- | ---- | ---- | ------ | ---- | ------------ | ----- | ---- | --- |
| ❖   | Khảo  | sát  | hiện | trạng  |      |              |       |      |     |
|     | ▪ Tìm | hiểu | về   | nghiệp | vụ   | hiện nay của | khách | hàng |     |
| ❖   | Xác   | định | yêu  | cầu    |      |              |       |      |     |
▪ Thỏa thuận với khách hàng về các nghiệp vụ sẽ hỗ trợ thực hiện
|     | trên | máy   | tính |      |     |     |     |     |     |
| --- | ---- | ----- | ---- | ---- | --- | --- | --- | --- | --- |
| ❖   | Lập  | hồ sơ | phân | tích | yêu | cầu |     |     |     |
▪ Sử dụng một phương pháp phân tích yêu cầu cụ thể để trình bày
|     | hồ  | sơ  | phân | tích | yêu cầu |     |     |     |     |
| --- | --- | --- | ---- | ---- | ------- | --- | --- | --- | --- |
Software Engineering 4
tkhuong@dthu.edu.vn

| Nhắc | lại Xác | định | yêu | cầu |
| ---- | ------- | ---- | --- | --- |
Khách hàng
|     |     |     | Tôi muốn |     |
| --- | --- | --- | -------- | --- |
….
Giải
thích về
|     | ….  |     | Phân | tích viên |
| --- | --- | --- | ---- | --------- |
Software Engineering 5
tkhuong@dthu.edu.vn

| Phân      | tích | yêu | cầu |     |     |
| --------- | ---- | --- | --- | --- | --- |
| Phân tích | viên |     |     |     |     |
Hồ sơ
phân tích
Thắc
mắc về
|     | ….  |     |     | Phụ trách | thiết kế |
| --- | --- | --- | --- | --------- | -------- |
Software Engineering 6
tkhuong@dthu.edu.vn

|     |     |     |      |     | Yêu     | cầu: mô | tả      | về nghiệp |       | vụ f đang |      | thực | hiện |     |     |
| --- | --- | --- | ---- | --- | ------- | ------- | ------- | --------- | ----- | --------- | ---- | ---- | ---- | --- | --- |
| ❖   | Hồ  | sơ  | phân |     | tích    | yêu     |         | cầu       | là    | gì?       |      |      |      |     |     |
|     |     |     |      |     | - Thông |         | tin của | đối       | tượng | X         |      |      |      |     |     |
|     |     |     |      |     | - Các   | bước    |         | tiến hành |       | nghiệp    | vụ f |      |      |     |     |
▪ Tài liệu mô tả ngắn gọn, chính xác và đầy đủ các yêu cầu của
|     |     |       |     |     | - Quy | tắc | xử  | lý nghiệp |     | vụ f |     |     |     |     |     |
| --- | --- | ----- | --- | --- | ----- | --- | --- | --------- | --- | ---- | --- | --- | --- | --- | --- |
|     |     | người |     | sử  | dụng. |     |     |           |     |      |     |     |     |     |     |
Mong muốn về nghiệp vụ f sẽ được hỗ trợ khi thực hiện trên máy tính
|     |       |      |      |       | - Vị  | trí     | sử dụng, giao |              |       | diện     |      |      |       |          |     |
| --- | ----- | ---- | ---- | ----- | ----- | ------- | ------------- | ------------ | ----- | -------- | ---- | ---- | ----- | -------- | --- |
|     | ▪     | Tài  | liệu | thống |       | nhất    |               | chung        |       | của nhóm |      | phát | triển | phần     | mềm |
|     |       |      |      |       | - Tốc | độ, bào |               | mật, an toàn |       |          |      |      |       |          |     |
|     | ▪     | Tài  | liệu | được  |       | sử      | dụng          |              | chính | trong    |      | giai | đoạn  | thiết kế |     |
| ❖   | Ngôn  |      | ngữ  | xây   |       | dựng    |               | hồ           | sơ    | phân     | tích | yêu  | cầu:  |          |     |
|     | ▪     | Ngôn |      | ngữ   | tự    | nhiên   |               |              |       |          |      |      |       |          |     |
|     | ▪     | Ngôn |      | ngữ   | mô    | hình    |               | hóa          |       |          |      |      |       |          |     |
| ❖   | Trình |      | bày  | hồ    | sơ    | phân    |               | tích         |       | yêu      | cầu  | như  | thế   | nào?     |     |
▪ Có rất nhiều cách khác nhau để trình bày một hồ sơ phân tích
|     |     | yêu | cầu      | phụ |      | thuộc |      | vào  |     |         |         |     |         |     |     |
| --- | --- | --- | -------- | --- | ---- | ----- | ---- | ---- | --- | ------- | ------- | --- | ------- | --- | --- |
|     |     |     | • Phương |     | pháp |       | phân | tích |     | yêu cầu | được    |     | sử dụng |     |     |
|     |     |     | • Quy    | ước |      | riêng | của  | từng |     | công    | ty dịch | vụ  | phần    | mềm |     |
Software Engineering 7
tkhuong@dthu.edu.vn

1. KHÁI NIỆM MÔ HÌNH HÓA
| ❖ Mô | hình | hóa là cách | dùng   | hệ thống |      | ký hiệu | để mô   | tả nhiều |
| ---- | ---- | ----------- | ------ | -------- | ---- | ------- | ------- | -------- |
| khía | cạnh | của vấn     | đề một | cách     | ngắn | gọn     | và trực | quan     |
| ❖ Ví | dụ   |             |        |          |      |         |         |          |
Software Engineering 8
tkhuong@dthu.edu.vn

VD MÔ HÌNH HÓA
| ❖   | Mô tả   | theo  | toàn     |         | diện:     |        |      |     |
| --- | ------- | ----- | -------- | ------- | --------- | ------ | ---- | --- |
|     | ▪ Không |       | chi tiết |         | và chuyên |        | sâu  |     |
|     | ▪ Không |       | nhấn     | mạnh    |           | đặc    | điểm |     |
|     | ▪ Không |       | mô       | tả được |           | sự vật | phức | tạp |
| ❖   | Mô tả   | theo  | góc      | nhìn:   |           |        |      |     |
|     | ▪ Tập   | trung |          | mô tả   | một       | phần   |      |     |
|     | ▪ Thể   | hiện  | một      | khía    | cạnh      |        |      |     |
|     | ▪ Làm   | nổi   | bật      | một     | đặc       | điểm   |      |     |
|     | → Hiệu  | quả   |          | hơn.    |           |        |      |     |
Software Engineering 9
tkhuong@dthu.edu.vn

1. KHÁI NIỆM MÔ HÌNH HÓA
| ❖   | Mô  | hình | hóa  | phần     |      | mềm |      |       |          |           |         |
| --- | --- | ---- | ---- | -------- | ---- | --- | ---- | ----- | -------- | --------- | ------- |
|     | ▪   | Mô   | hình | hóa      | phần | mềm | theo | nhiều | góc nhìn | khác nhau | từ tổng |
|     |     | quát | đến  | chi tiết |      |     |      |       |          |           |         |
▪ Làm nổi bật một khía cạnh của phần mềm, giúp cho tất cả thành
|     |     | viên | trong | nhóm   |      | tham   | gia xây | dựng | phần mềm | hiểu được | chức |
| --- | --- | ---- | ----- | ------ | ---- | ------ | ------- | ---- | -------- | --------- | ---- |
|     |     | năng | của   | một    | hệ   | thống. |         |      |          |           |      |
| ❖   | Các | khía | cạnh  |        | mô   | hình   | hóa     | phần | mềm      |           |      |
|     | ▪   | Mô   | hình  | nghiệp | vụ   |        |         |      |          |           |      |
|     | ▪   | Mô   | hình  | quan   | niệm |        |         |      |          |           |      |
|     | ▪   | Mô   | hình  | yêu    | cầu  |        |         |      |          |           |      |
Software Engineering 10
tkhuong@dthu.edu.vn

1. KHÁI NIỆM MÔ HÌNH HÓA
| ❖ Một | số phương                         | pháp | mô hình   | hóa yêu | cầu phần | mềm | thông |
| ----- | --------------------------------- | ---- | --------- | ------- | -------- | --- | ----- |
| dụng  | hiện nay:                         |      |           |         |          |     |       |
| ▪     | DFD (Data Flow Diagram)           |      |           |         |          |     |       |
| ▪     | ERD (Entity Relationship Diagram) |      |           |         |          |     |       |
| ▪     | UML (Unified Modelling            |      | Language) |         |          |     |       |
Software Engineering 11
tkhuong@dthu.edu.vn

1. KHÁI NIỆM MÔ HÌNH HÓA
| ❖ UML (Unified Modelling |                                           |      |      |      | Language) |       |      |           |           |      |
| ------------------------ | ----------------------------------------- | ---- | ---- | ---- | --------- | ----- | ---- | --------- | --------- | ---- |
| ▪ Là                     | ngôn                                      | ngữ  | mô   | hình | hóa       | hướng |      | đối tượng |           |      |
| ▪ Được                   | thừa                                      | nhận |      | như  | một       | chuẩn |      | mặc định  | của ngành | CNTT |
| ▪ Có                     | nhiều                                     | công | cụ   | và   | phương    |       | pháp | dựa trên  | UML       |      |
|                          | • Enterprise Architecture / Rational Rose |      |      |      |           |       |      |           |           |      |
|                          | • Rational Unified Process (RUP)          |      |      |      |           |       |      |           |           |      |
| ▪ Gồm                    | 4+1 góc                                   |      | nhìn | với  | các       | sơ    | đồ:  |           |           |      |
Software Engineering 12
tkhuong@dthu.edu.vn

1. KHÁI NIỆM MÔ HÌNH HÓA
Software Engineering 13
tkhuong@dthu.edu.vn

1. KHÁI NIỆM MÔ HÌNH HÓA
Software Engineering 14
tkhuong@dthu.edu.vn

2. MÔ HÌNH NGHIỆP VỤ
| ❖ Sơ | đồ ngữ  | cảnh | (Context diagram) |
| ---- | ------- | ---- | ----------------- |
| ❖ Sơ | đồ hoạt | động |                   |
Software Engineering 15
tkhuong@dthu.edu.vn

2. MÔ HÌNH NGHIỆP VỤ
| ❖   | Sơ  | đồ   | ngữ  |       | cảnh  | (Context diagram) |            |     |      |        |        |
| --- | --- | ---- | ---- | ----- | ----- | ----------------- | ---------- | --- | ---- | ------ | ------ |
|     | ▪   | Thể  | hiện |       | môi   | trường            | xung quanh |     | phần | mềm    |        |
|     |     | •    | Xác  | định  | giới  | hạn               | của phần   | mềm |      |        |        |
|     | ▪   | Diễn | tả   | tương |       | tác với           | các thành  |     | phần | liên   | quan   |
|     |     | •    | Sự   | phụ   | thuộc | giữa              | hệ thống   | với | mội  | trường | của nó |
Software Engineering 16
tkhuong@dthu.edu.vn

| Sơ đồ | ngữ | cảnh | của | hệ thống | ngân | hàng |
| ----- | --- | ---- | --- | -------- | ---- | ---- |
http://www.ibm.com/developerworks/vn/library/ar-archdoc2/
Software Engineering 17
tkhuong@dthu.edu.vn

| VD. Sơ | đồ ngữ   | cảnh   | của       | HT ATM |
| ------ | -------- | ------ | --------- | ------ |
|        | Ngữ cảnh | của hệ | thống ATM |        |
Software Engineering 19
tkhuong@dthu.edu.vn

2. MÔ HÌNH NGHIỆP VỤ
| ❖ Sơ | đồ  | luồng    | dữ        | liệu (DFD)         |         |       |          |
| ---- | --- | -------- | --------- | ------------------ | ------- | ----- | -------- |
| ❖ Sơ | đồ  | hoạt     | động      | (Activity diagram) |         |       |          |
| ▪    | Mô  | tả trình | tự        | xử lý công         | việc    |       |          |
| ▪    | Làm | rõ       | quy trình | nghiệp             | vụ của  | doanh | nghiệp   |
| ▪    | Làm | rõ       | sự luân   | chuyển             | dữ liệu | trong | hệ thống |
| ▪    | Mô  | tả thuật | toán      |                    |         |       |          |
Software Engineering 20
tkhuong@dthu.edu.vn

Software Engineering 21
tkhuong@dthu.edu.vn

3. MÔ HÌNH QUAN NIỆM
| ❖ Sơ | đồ thực    | thể kết | hợp   |
| ---- | ---------- | ------- | ----- |
| ❖ Mô | hình hướng | đối     | tượng |
Software Engineering 22
tkhuong@dthu.edu.vn

3. MÔ HÌNH QUAN NIỆM
| ❖ Sơ | đồ thực   | thể  | - kết hợp | (ERD)        |         |
| ---- | --------- | ---- | --------- | ------------ | ------- |
| ▪    | Mô tả mối | liên | hệ giữa   | các thực thể | dữ liệu |
▪ Được sử dụng trong thiết kế CSDL và thường được cài đặt trong
|     | CSDL quan | hệ  |     |     |     |
| --- | --------- | --- | --- | --- | --- |
Software Engineering 23
tkhuong@dthu.edu.vn

3. MÔ HÌNH QUAN NIỆM
| ❖ Ví | dụ Sơ | đồ thực | thể | - kết hợp | (ERD) |
| ---- | ----- | ------- | --- | --------- | ----- |
Software Engineering 24
tkhuong@dthu.edu.vn

3. MÔ HÌNH QUAN NIỆM
| ❖ Ví | dụ Sơ | đồ thực | thể | - kết hợp | của LIBSYS |
| ---- | ----- | ------- | --- | --------- | ---------- |
Software Engineering 25
tkhuong@dthu.edu.vn

Software Engineering 26
tkhuong@dthu.edu.vn

3. MÔ HÌNH QUAN NIỆM
| ❖ Mô | hình | hướng |     | đối tượng |     |     |     |     |     |
| ---- | ---- | ----- | --- | --------- | --- | --- | --- | --- | --- |
▪ Mô hình đối tượng phản ánh các thực thể trong thế giới thực
|     | được  | vận | dụng | trong | hệ     | thống. Mô   | tả hệ thống           | dựa vào | lớp đối |
| --- | ----- | --- | ---- | ----- | ------ | ----------- | --------------------- | ------- | ------- |
|     | tượng | và  | các  | quan  | hệ của | nó. Một lớp | đối tượng là sự trừu  |         |         |
tượng hoá trên một tập các đối tượng có thuộc tính và phương
|       | thức | chung.    |     |       |     |     |     |     |     |
| ----- | ---- | --------- | --- | ----- | --- | --- | --- | --- | --- |
| ❖ Các | mô   | hình      | đối | tượng | gồm |     |     |     |     |
| ▪     | Mô   | hình thừa |     | kế    |     |     |     |     |     |
| ▪     | Mô   | hình kết  | hợp |       |     |     |     |     |     |
| ▪     | Mô   | hình ứng  | xử  |       |     |     |     |     |     |
Software Engineering 27
tkhuong@dthu.edu.vn

| Mô  | hình | đối | tượng | - thừa | kế  |
| --- | ---- | --- | ----- | ------ | --- |
❖ Mô hình thừa kế tổ chức các lớp đối tượng theo một cấu trúc
phân cấp
Software Engineering 28
tkhuong@dthu.edu.vn

| Mô  | hình | đối | tượng | – kết | hợp |
| --- | ---- | --- | ----- | ----- | --- |
❖ Mô hình kết hợp biểu diễn cách cấu tạo của một lớp từ
các lớp khác
Software Engineering 29
tkhuong@dthu.edu.vn

Software Engineering 30
tkhuong@dthu.edu.vn

Software Engineering 31
tkhuong@dthu.edu.vn

|               | Mô     | hình     |       | đối      | tượng                |          | – ứng   | xử    |          |     |
| ------------- | ------ | -------- | ----- | -------- | -------------------- | -------- | ------- | ----- | -------- | --- |
| ❖ Mô hình ứng |        |          | xử mô | tả tương |                      | tác giữa | các đối | tượng | nhằm     | tạo |
| ra            | một số | ứng      | xử cụ | thể      | của                  | hệ thống | mà đã   | được  | xác định |     |
| như           | là một | use case |       |          |                      |          |         |       |          |     |
|               |        |          |       |          | Software Engineering |          |         |       |          | 32  |
tkhuong@dthu.edu.vn

|          | Mô  | hình        | đối  | tượng |          | – ứng    | xử  |
| -------- | --- | ----------- | ---- | ----- | -------- | -------- | --- |
| ❖ VD: mô | tả  | use case sử | dụng | Rút   | tiền của | hệ thống | ATM |
Software Engineering 33
tkhuong@dthu.edu.vn

4. MÔ HÌNH YÊU CẦU
| ❖ Phương         | pháp     | Use Case |
| ---------------- | -------- | -------- |
| ❖ Sơ đồ Use Case |          |          |
| ❖ Đặc tả         | Use Case |          |
Software Engineering 35
tkhuong@dthu.edu.vn

4. MÔ HÌNH YÊU CẦU
| ❖   | Phương |     | pháp |     | Use Case |     |     |     |     |     |     |     |     |
| --- | ------ | --- | ---- | --- | -------- | --- | --- | --- | --- | --- | --- | --- | --- |
▪ Mô tả yêu cầu dựa trên PP phân tích tình huống, đưa ra một tập
|     |     | kịch  | bản  | tương  |      | tác   | giữa  | một  | hoặc    |       | vài tác | nhân (actor) với | hệ  |
| --- | --- | ----- | ---- | ------ | ---- | ----- | ----- | ---- | ------- | ----- | ------- | ---------------- | --- |
|     |     | thống | nhằm |        | thực |       | hiện  | một  | mục     | tiêu  | chung   |                  |     |
| ❖   | Các | kịch  | bản  |        | nên  | bao   | gồm   |      |         |       |         |                  |     |
|     | ▪   | Một   | miêu | tả     | về   | tình  | huống |      | ban đầu |       |         |                  |     |
|     | ▪   | Một   | miêu | tả     | về   | luồng | sự    | kiện |         | thông | thường  |                  |     |
|     | ▪   | Một   | miêu | tả     | về   | những |       | trục | trặc    | gì    | có thể  | xảy ra           |     |
|     | ▪   | Thông |      | tin về | các  | hoạt  | động  |      | xảy     | ra    | đồng    | thời             |     |
|     | ▪   | Một   | miêu | tả     | về   | trạng | thái  | khi  | kịch    | bản   | kết     | thúc             |     |
Software Engineering 36
tkhuong@dthu.edu.vn

Kịch bản LIBSYS (1)
Initial Assumption: Người dùng đã đăng nhập hệ thống LIBSYS và đã
tìm thấy tạp chí có đăng tài liệu cần tìm.
Normal:
•Người dùng chọn tài liệu cần copy. Hệ thống sẽ yêu cầu người dùng
nhập thông tin thuê bao hoặc chọn cách trả phí dùng tài liệu. Có thể
thanh toán bằng thẻ tín dụng hoặc dùng số tài khoản của một tổ chức.
•Sau đó người dùng được yêu cầu điền một form bản quyền trong đó
có chi tiết về giao dịch này, rồi submit form đó cho hệ thống LIBSYS.
•Hệ thống kiểm tra form bản quyền, nếu OK, bản PDF của tài liệu sẽ
được tải xuống máy tính của người dùng và người dùng được thông
báo về việc này. Sau đó người dùng được chọn một máy in, và tài liệu
sẽ được in tại đó. Nếu tài liệu đã được gắn cờ ‘print-only’ thì nó sẽ
được xóa khỏi máy của người dùng ngay sau khi người dùng khẳng
định rằng đã in xong.
tkhuong@dthu.edu.vn

|     | Kịch | bản |     | LIBSYS (2) |     |     |     |
| --- | ---- | --- | --- | ---------- | --- | --- | --- |
What can go wrong:
•Người dùng có thể điền form sai. Khi đó hệ thống cần hiện lại form để
người dùng sửa lại. Nếu form được submit sau đó vẫn sai thì hủy yêu
| cầu đọc | tài liệu | của | người | dùng.  |     |     |     |
| ------- | -------- | --- | ----- | ------ | --- | --- | --- |
•Hệ thống có thể không chấp nhận giao dịch thanh toán tiền. Hủy yêu
| cầu đọc | tài liệu | của | người | dùng.  |     |     |     |
| ------- | -------- | --- | ----- | ------ | --- | --- | --- |
•Việc download tài liệu có thể thất bại. Làm lại cho đến khi thành công
| hoặc | khi người | dùng | chấm | dứt phiên | làm | việc. |     |
| ---- | --------- | ---- | ---- | --------- | --- | ----- | --- |
•Có thể không in được tài liệu. Nếu bài báo không có gắn cờ ‘print-
only’ thì giữ nó trong workspace của LIBSYS. Nếu không, xóa tài liệu
| và hoàn                     | lại chi phí | cho | người | dùng.        |     |          |            |
| --------------------------- | ----------- | --- | ----- | ------------ | --- | -------- | ---------- |
| Other activities: Song song |             |     |       | download các |     | tài liệu | khác nhau. |
System state on completion: Người dùng đang ở trạng thái đăng
nhập. Nếu tài liệu có gắn cờ 'print-only' thì nó đã bị xóa khỏi LIBSYS
workspace.
tkhuong@dthu.edu.vn

4. MÔ HÌNH YÊU CẦU
| ❖ Sơ đồ | Use Case |         |      |          |                     |        |
| ------- | -------- | ------- | ---- | -------- | ------------------- | ------ |
| ▪ Sơ    | đồ mô    | tả tổng | quan | các chức | năng (Use case) của | một hệ |
thống và ai dùng chức năng nào (Actor), sử dụng ngôn ngữ UML.
❖ Sử dụng Đặc tả Use case (văn bản), Sơ đồ hoạt động (Activity
| Diagram), Sơ |     | đồ tuần  | tự  | (Sequence Diagram) để |     | bổ sung chi  |
| ------------ | --- | -------- | --- | --------------------- | --- | ------------ |
| tiết cho     | các | Use case |     |                       |     |              |
Software Engineering 39
tkhuong@dthu.edu.vn

4. MÔ HÌNH YÊU CẦU
❖ Sơ đồ Use Case
▪ Ký hiệu:
Actor Use Case
Software Engineering 40
tkhuong@dthu.edu.vn

|      |     | VD1. Giải |     |     |     |       | phương |     |        | trình |     | bậc |     | 2   |
| ---- | --- | --------- | --- | --- | --- | ----- | ------ | --- | ------ | ----- | --- | --- | --- | --- |
| Phân |     | tích      | yêu |     | cầu | (ngôn | ngữ    | tự  | nhiên) |       |     |     |     |     |
❖ Giáo viên muốn có phần mềm hỗ trợ học sinh tự rèn luyện bài
|     | tập | Giải |     | phương |        | trình | bậc   | 2 với | các | thông | tin như |     | sau: |     |
| --- | --- | ---- | --- | ------ | ------ | ----- | ----- | ----- | --- | ----- | ------- | --- | ---- | --- |
|     | ▪   | Hỗ   | trợ | giải   | phương |       | trình | bậc   | 2   |       |         |     |      |     |
• Học sinh nhập vào các hệ số a,b,c (a khác 0), phần mềm cho ra kết
|     |     |     | quả    | nghiệm |       | của | phương  | trình | với      | 2 ký số | thập  | phân   |     |     |
| --- | --- | --- | ------ | ------ | ----- | --- | ------- | ----- | -------- | ------- | ----- | ------ | --- | --- |
|     | ▪   | Tự  | rèn    | luyện  |       |     |         |       |          |         |       |        |     |     |
|     |     |     | • Học  | sinh   | nhập  |     | vào các | hệ    | số a,b,c | (a khác | 0) và | nghiệm |     | của |
|     |     |     | phương |        | trình | vừa | nhập    |       |          |         |       |        |     |     |
• Phần mềm cho kết quả đánh giá nghiệm đúng sai, nếu sai thì hiển
|     |     |     | thị | nghiệm |     | đúng |     |     |     |     |     |     |     |     |
| --- | --- | --- | --- | ------ | --- | ---- | --- | --- | --- | --- | --- | --- | --- | --- |
Software Engineering 41
tkhuong@dthu.edu.vn

| VD1. Giải | phương | trình        | bậc | 2   |
| --------- | ------ | ------------ | --- | --- |
|           |        | Giải phương  |     |     |
|           |        | trình bậc    | 2   |     |
|           |        | Tự rèn luyện |     |     |
Học sinh
Software Engineering 42
tkhuong@dthu.edu.vn

|      | VD2. Quản |     |     |       | lý nhân |        | viên |     |     |
| ---- | --------- | --- | --- | ----- | ------- | ------ | ---- | --- | --- |
| Phân | tích yêu  |     | cầu | (Ngôn | ngữ tự  | nhiên) |      |     |     |
❖ Người dùng muốn phần mềm quản lý nhân viên cho phép thực hiện
| các    | chức | năng |     | như sau: |     |     |     |     |     |
| ------ | ---- | ---- | --- | -------- | --- | --- | --- | --- | --- |
| ❖ Nhân | viên |      |     |          |     |     |     |     |     |
▪ Quản lý hồ sơ nhân viên (Thêm mới, cập nhật, xóa) dựa theo BM1
▪ Tra cứu hồ sơ nhân viên: cho phép nhập vào tên hoặc địa chỉ, hoặc trình
độ của nhân viên và sau đó phần mềm sẽ xuất ra danh sách các nhân
|     | viên | (thông | tin hồ | sơ  | nhân | viên khi | tra cứu | theo | BM1) |
| --- | ---- | ------ | ------ | --- | ---- | -------- | ------- | ---- | ---- |
▪ Lập báo cáo thống kê: yêu cầu lập báo cáo thông kê theo BM2
❖ Ban giám đốc: chỉ sử dụng 1 chức năng là cập nhật quy định tiếp
| nhận  | nhận      |      | nhân | viên | mới        |      |      |     |            |
| ----- | --------- | ---- | ---- | ---- | ---------- | ---- | ---- | --- | ---------- |
| Ghi   | chú: chưa | xem  | xét  | hết  | tất cả các | chức | năng |     |            |
| → Hãy | mô        | hình | hóa  | phân | tích yêu   | cầu  | bằng | sơ  | đồ Usecase |
Software Engineering 43
tkhuong@dthu.edu.vn

4. MÔ HÌNH YÊU CẦU
❖ Sơ đồ Use Case
Software Engineering 45
tkhuong@dthu.edu.vn

4. MÔ HÌNH YÊU CẦU
| ❖ Sơ | đồ Use Case nâng | cấp |
| ---- | ---------------- | --- |
Software Engineering 46
tkhuong@dthu.edu.vn

Software Engineering 47
tkhuong@dthu.edu.vn

|       | Mô  | tả            | Use-Case hệ |      | thống |
| ----- | --- | ------------- | ----------- | ---- | ----- |
| ❖ Đặc | tả  | Use Case (văn |             | bản) |       |
▪ Mô tả chi tiết tương tác giữa người dùng (actor) với các chức
|     | năng | của hệ | thống | (Use Case) |     |
| --- | ---- | ------ | ----- | ---------- | --- |
Software Engineering 54
tkhuong@dthu.edu.vn

|       | Mô  | tả Use-Case hệ | thống |
| ----- | --- | -------------- | ----- |
| ❖ Mẫu | đặc | tả Use Case:   |       |
tkhuong@dthu.edu.vn

|           | Mô  | tả Use-Case hệ   |       | thống |
| --------- | --- | ---------------- | ----- | ----- |
| ❖ VD1 đặc |     | tả Use-case Giao | dịch: |       |
tkhuong@dthu.edu.vn

|           | Mô  | tả Use-Case hệ   |      | thống |
| --------- | --- | ---------------- | ---- | ----- |
| ❖ VD1 đặc |     | tả Use-case Giao | dịch | (tt): |
tkhuong@dthu.edu.vn

|           | Mô  | tả Use-Case hệ  |       | thống |
| --------- | --- | --------------- | ----- | ----- |
| ❖ VD2 đặc |     | tả Use-case Rút | tiền: |       |
tkhuong@dthu.edu.vn

| Mô        | tả Use-Case hệ  |            | thống |
| --------- | --------------- | ---------- | ----- |
| ❖ VD2 đặc | tả Use-case Rút | tiền (tt): |       |
tkhuong@dthu.edu.vn

|      |      | VD1. Giải |       |     | phương |        |     | trình | bậc | 2   |
| ---- | ---- | --------- | ----- | --- | ------ | ------ | --- | ----- | --- | --- |
| Phân | tích | yêu cầu   | (ngôn |     | ngữ tự | nhiên) |     |       |     |     |
❖ Giáo viên muốn có phần mềm hỗ trợ học sinh tự rèn luyện bài tập Giải phương
|     | trình | bậc 2 với | các    | thông | tin như |     | sau: |     |     |     |
| --- | ----- | --------- | ------ | ----- | ------- | --- | ---- | --- | --- | --- |
|     | ▪ Hỗ  | trợ giải  | phương |       | trình   | bậc | 2    |     |     |     |
Học sinh nhập vào các hệ số a,b,c (a khác 0), phần mềm cho ra kết quả nghiệm của
|     | phương | trình     | với | 2 ký số | thập | phân |     |     |     |     |
| --- | ------ | --------- | --- | ------- | ---- | ---- | --- | --- | --- | --- |
|     | ▪ Tự   | rèn luyện |     |         |      |      |     |     |     |     |
Học sinh nhập vào các hệ số a,b,c (a khác 0) và nghiệm của phương trình vừa nhập
Phần mềm cho kết quả đánh giá nghiệm đúng sai, nếu sai thì hiển thị nghiệm đúng
|     |     |     |     |     |     |     |     | Giải phương |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | ----------- | --- | --- |
|     |     |     |     |     |     |     |     | trình bậc   | 2   |     |
Học sinh
|     |     |     |     |     |     |     |     | Tự rèn | luyện |     |
| --- | --- | --- | --- | --- | --- | --- | --- | ------ | ----- | --- |
Hãy đặc tả UseCase Giải Phương trình bậc 2, Usecase Tự rèn luyện
Software Engineering 60
tkhuong@dthu.edu.vn

| Quy tắc | giải phương |     | trình bậc | 2:  |     |     |
| ------- | ----------- | --- | --------- | --- | --- | --- |
Cho phương trình bậc 2: ax2+bx+c=0 (với a,b,c là 3 số thực, a khác 0)
| Các bước | giải           | phương         | trình      | như sau: |          |        |
| -------- | -------------- | -------------- | ---------- | -------- | -------- | ------ |
| B1. Tính | delta = b2-4ac |                |            |          |          |        |
| B2. Xác  | đinh           | nghiệm         | theo delta |          |          |        |
|          | + Nếu          | delta<0: PT vô |            | nghiệm   |          |        |
|          | + Nếu          | delta=0: PT có |            | nghiệm   | kép x =x | =-b/2a |
1 2
|     | + Nếu | delta>0: PT có |     | 2 nghiệm   | phân biệt |     |
| --- | ----- | -------------- | --- | ---------- | --------- | --- |
|     |       | x =(-b-căn     |     | delta)/ 2a |           |     |
1
|     |     | x =(-b+căn |     | delta)/ 2a |     |     |
| --- | --- | ---------- | --- | ---------- | --- | --- |
2
Software Engineering 61
tkhuong@dthu.edu.vn

|      | VD2. Quản |     |       |     | lý nhân |        | viên |     |
| ---- | --------- | --- | ----- | --- | ------- | ------ | ---- | --- |
| Phân | tích yêu  | cầu | (Ngôn |     | ngữ tự  | nhiên) |      |     |
❖ Người dùng muốn phần mềm quản lý nhân viên cho phép thực hiện
| các    | chức | năng | như | sau: |     |     |     |     |
| ------ | ---- | ---- | --- | ---- | --- | --- | --- | --- |
| ❖ Nhân | viên |      |     |      |     |     |     |     |
▪ Quản lý hồ sơ nhân viên (Thêm mới, cập nhật, xóa) dựa theo BM1
▪ Tra cứu hồ sơ nhân viên: cho phép nhập vào tên hoặc địa chỉ, hoặc trình
độ của nhân viên và sau đó phần mềm sẽ xuất ra danh sách các nhân
|     | viên | (thông | tin hồ | sơ  | nhân | viên khi | tra cứu theo | BM1) |
| --- | ---- | ------ | ------ | --- | ---- | -------- | ------------ | ---- |
▪ Lập báo cáo thống kê: yêu cầu lập báo cáo thông kê theo BM2
❖ Ban giám đốc: chỉ sử dụng 1 chức năng là cập nhật quy định tiếp
| nhận | nhận      | nhân |     | viên | mới        |      |      |     |
| ---- | --------- | ---- | --- | ---- | ---------- | ---- | ---- | --- |
| Ghi  | chú: chưa | xem  | xét | hết  | tất cả các | chức | năng |     |
Software Engineering 62
tkhuong@dthu.edu.vn

|                     | VD2. Quản        |     |      |      |            | lý  | nhân |                                       | viên  |     |     |       |       |     |       |
| ------------------- | ---------------- | --- | ---- | ---- | ---------- | --- | ---- | ------------------------------------- | ----- | --- | --- | ----- | ----- | --- | ----- |
|                     |                  |     |      |      |            |     |      | BM2                             Thống |       |     |     | kê    | trình | độ  |       |
| BM1      Hồ         |                  | sơ  | nhân | viên |            |     |      |                                       |       |     |     |       |       |     |       |
|                     |                  |     |      |      |            |     |      |                                       | Trình | độ  | Số  | lượng |       |     | Tỷ lệ |
| Họ và               | tên: ………… Giới   |     |      |      | tính: ………  |     |      |                                       |       |     |     |       |       |     |       |
|                     |                  |     |      |      |            |     |      | Trung                                 | cấp   |     |     |       |       |     |       |
| Ngày                | sinh: ………... Địa |     |      |      | chỉ: ……….. |     |      |                                       |       |     |     |       |       |     |       |
| Đơn vị: …………… Trình |                  |     |      |      | độ: ……….   |     |      | Cao đẳng                              |       |     |     |       |       |     |       |
Ghi chú:
|           |         |        |           |        |           |        |     | Đại     | học       |             |      |         |      |     |     |
| --------- | ------- | ------ | --------- | ------ | --------- | ------ | --- | ------- | --------- | ----------- | ---- | ------- | ---- | --- | --- |
| - Tuổi    | nhân    |        | viên      | theo   | quy       | định   |     |         |           |             |      |         |      |     |     |
|           |         |        |           |        |           |        |     | Sau     | đại       | học         |      |         |      |     |     |
| Nam từ    |         | 18 đến |           | 60, Nữ | từ        | 18 đến | 55  |         |           |             |      |         |      |     |     |
| - Công    | ty      | có     | 5 đơn     | vị     | và chỉ    | chấp   |     | Ghi     | chú:      |             |      |         |      |     |     |
|           |         |        |           |        |           |        |     | Số      | lượng: Số | lượng       | nhân | viên    |      |     |     |
| nhận      | 4 trình |        | độ: Trung |        | cấp, Cao  |        |     |         |           |             |      |         |      |     |     |
|           |         |        |           |        |           |        |     | Tỷ      | lệ = Số   | lượng/ Tổng |      | số nhân | viên |     |     |
| đẳng, Đại |         |        | học, Sau  |        | đại học   |        |     |         |           |             |      |         |      |     |     |
| → Hãy     |         | đặc    | tả        | hoạt   | động      | của    | các | Usecase |           |             |      |         |      |     |     |
Software Engineering 63
tkhuong@dthu.edu.vn

4. MÔ HÌNH YÊU CẦU
| ❖ Sơ | đồ tuần | tự  |
| ---- | ------- | --- |
tkhuong@dthu.edu.vn

4. MÔ HÌNH YÊU CẦU
| ❖ Sơ | đồ Tuần | tự  |
| ---- | ------- | --- |
Software Engineering 74
tkhuong@dthu.edu.vn

| VD1. Giải | phương | trình | bậc | 2   |
| --------- | ------ | ----- | --- | --- |
Software Engineering 76
tkhuong@dthu.edu.vn

| VD2. Quản | lý nhân | viên |
| --------- | ------- | ---- |
Software Engineering 77
tkhuong@dthu.edu.vn

Bài tập
| 1) PM xếp | loại  | học     | lực học | sinh |     |
| --------- | ----- | ------- | ------- | ---- | --- |
| a) Vẽ     | sơ đồ | UseCase |         |      |     |
b) Chọn 1 UseCase để: đặc tả UseCase, Activity, Sequence, Class
Diagram
| 2) PM tính   | tiền | thuê   | phòng  | khách | sạn |
| ------------ | ---- | ------ | ------ | ----- | --- |
| 3) PM Quản   |      | lý học | sinh   |       |     |
| 4) PM Quản   |      | lý thu | chi    |       |     |
| 5) PM quản   | lý   | nhập   | xuất   |       |     |
| 6) PM quản   | lý   | khách  | sạn    |       |     |
| 7) PM QL thư |      | viện   | trường |       |     |
Software Engineering 78
tkhuong@dthu.edu.vn

|      |     | Đề   |     | BT1. Xếp |       |     |     | loại |        | học | lực | của | học | sinh |
| ---- | --- | ---- | --- | -------- | ----- | --- | --- | ---- | ------ | --- | --- | --- | --- | ---- |
| Phân |     | tích | yêu | cầu      | (Ngôn |     | ngữ | tự   | nhiên) |     |     |     |     |      |
❖ Với yêu cầu lập bảng xếp loại học lực, phần mềm bao gồm các
|     | người |     | sử   | dụng | và    | chức |      | năng   | như | sau: |        |      |     |     |
| --- | ----- | --- | ---- | ---- | ----- | ---- | ---- | ------ | --- | ---- | ------ | ---- | --- | --- |
| ❖   | Nhân  |     | viên | văn  | phòng |      | giáo | vụ: sử |     | dụng | 2 chức | năng |     |     |
|     | ▪     | Ghi | nhận |      | bảng  | điểm |      |        |     |      |        |      |     |     |
|     | ▪     | Lập | bảng |      | xếp   | loại | học  | lực    |     |      |        |      |     |     |
❖ Ban giám hiệu: chỉ sử dụng 1 chức năng là cập nhật quy tắc xếp loại
|     | học | lực |     |     |     |     |     |     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
Ghi chú: Chi tiết các chức năng sẽ mô tả sau, chưa xem xét hết tất cả các chức
năng
| →   | Hãy | vẽ  | sơ  | đồ  | UseCase |     |     |     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | ------- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
Software Engineering 79
tkhuong@dthu.edu.vn

|     | Đề       | BT1. Xếp |          |        |         |      | loại     |       | học      | lực |      | của | học | sinh |
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
Software Engineering 80
tkhuong@dthu.edu.vn

|        | Đề        | BT1. Xếp   |        |        | loại | học | lực          | của         |                  | học     | sinh  |
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
Software Engineering 81
tkhuong@dthu.edu.vn