LOGO
KHOA KỸ THUẬT – CÔNG NGHỆ
Chương 3
YÊU CẦU
PHẦN MỀM
GV biên soạn: Trần Kim Hương
tkhuong@dthu.edu.vn
Software Engineering
tkhuong@dthu.edu.vn

MỤC TIÊU CHƯƠNG 3
| ❖ Tìm | hiểu | về  | các | yêu | cầu | hệ  | thống | và  | đặc | điểm | của |
| ----- | ---- | --- | --- | --- | --- | --- | ----- | --- | --- | ---- | --- |
chúng
| ❖ Phương |       | pháp  | xác | định  | yêu                  | cầu | hệ   | thống |     |      |     |
| -------- | ----- | ----- | --- | ----- | -------------------- | --- | ---- | ----- | --- | ---- | --- |
| ❖ Các    | kỹ    | thuật | đặc | tả    | yêu                  | cầu | hệ   | thống | và  | cách | áp  |
| dụng     | những |       | kỹ  | thuật | này                  | một | cách | phù   | hợp |      |     |
|          |       |       |     |       | Software Engineering |     |      |       |     |      | 2   |
tkhuong@dthu.edu.vn

NỘI DUNG
| 1   | YC CHỨC |     | NĂNG    | &   | YC PHI | CHỨC | NĂNG |
| --- | ------- | --- | ------- | --- | ------ | ---- | ---- |
|     | ĐẶC     | TẢ  | YÊU CẦU |     |        |      |      |
2
| 33  | QUY      | TRÌNH | CÔNG |      | NGHỆ | YÊU CẦU |     |
| --- | -------- | ----- | ---- | ---- | ---- | ------- | --- |
| 44  | THU      | THẬP  | VÀ   | PHÂN | TÍCH | YÊU     | CẦU |
| 5   | THẨM     | ĐỊNH  | YÊU  |      | CẦU  |         |     |
| 6   | QUẢN     | TRỊ   | YÊU  | CẦU  |      |         |     |
| 7   | TÀI LIỆU |       | YÊU  | CẦU  | PM   |         |     |
3
tkhuong@dthu.edu.vn

|        | Đặt | vấn    |      | đề  |       |      |         |      |       |      |
| ------ | --- | ------ | ---- | --- | ----- | ---- | ------- | ---- | ----- | ---- |
| ❖ Tiêu |     | chí gì | quan |     | trọng | nhất | đối với | chất | lượng | phần |
mềm???
| ➔Phần   |       | mềm      | phải  |     | thỏa | mãn    | yêu cầu  | của người |     | dùng |
| ------- | ----- | -------- | ----- | --- | ---- | ------ | -------- | --------- | --- | ---- |
| ❖ Yêu   |       | cầu phần |       | mềm |      | là gì? |          |           |     |      |
| → Những |       | gì       | người |     | ta   | muốn   | có trong | phần      | mềm | được |
| phát    | triển |          |       |     |      |        |          |           |     |      |
Software Engineering 4
tkhuong@dthu.edu.vn

YÊU CẦU PHẦN MỀM
| ❖ Yêu | cầu phần | mềm | là gì? |     |     |
| ----- | -------- | --- | ------ | --- | --- |
| Khách | hàng     |     |        |     |     |
Tôi muốn
phần mềm
|     |     |     |     | giúp tôi thực |     |
| --- | --- | --- | --- | ------------- | --- |
hiện nghiệp
vụ ….
Tôi muốn
|     | nghiệp vụ |     |     |     |     |
| --- | --------- | --- | --- | --- | --- |
phải được
|     | thực hiện |     |     | Phân tích | viên |
| --- | --------- | --- | --- | --------- | ---- |
….
Software Engineering 5
tkhuong@dthu.edu.vn

| Một | số  |     | ví dụ |     |     |     |
| --- | --- | --- | ----- | --- | --- | --- |
❖ Tôi muốn pm giúp tôi thực hiện công việc tính lương, lập báo cáo tồn
| kho, đánh | cờ  | caro, | giải | bài tập | đại số,… |     |
| --------- | --- | ----- | ---- | ------- | -------- | --- |
❖ Tôi muốn pm giúp độc giả tra cứu sách muốn mượn, việc tra cứu
| này phải | được | thực | hiện | ở bất | kỳ nơi | nào. |
| -------- | ---- | ---- | ---- | ----- | ------ | ---- |
❖ Tôi muốn giúp tôi lập hóa đơn tiền điện và phải in được khoảng
20.000 hóa đơn của khu vực tp cao lãnh này chỉ diễn ra tối đa 1
ngày
❖
Tôi muốn pm giúp tra cứu các chuyến xe buýt trên địa bàn tỉnh đồng
tháp, việc tra cứu này được diễn ra trên sơ đồ của những tuyến xe
buýt
❖ …………………………………………
Software Engineering 6
tkhuong@dthu.edu.vn

YÊU CẦU PHẦN MỀM
| ❖   | Khái  | niệm |        |       |       |      |       |     |      |      |      |     |      |        |
| --- | ----- | ---- | ------ | ----- | ----- | ---- | ----- | --- | ---- | ---- | ---- | --- | ---- | ------ |
|     | ▪ Yêu |      | cầu    | của   |       | phần | mềm   |     | X là | mong | muốn |     | của  | người  |
|     | sử    |      | dụng   | về    | khả   | năng |       | mà  | phần | mềm  | X    | cần | phải | có để  |
|     | có    |      | thể hỗ | trợ   | cho   |      | người |     | dùng | thực | hiện | tốt | các  | nghiệp |
|     | vụ    | của  |        | mình. |       |      |       |     |      |      |      |     |      |        |
| ❖   | Yêu   | cầu  | phần   |       | mềm   |      | có    | 2   | loại |      |      |     |      |        |
|     | ▪ Yêu |      | cầu    | người |       | dùng |       |     |      |      |      |     |      |        |
|     | ▪ Yêu |      | cầu    | hệ    | thống |      |       |     |      |      |      |     |      |        |
Software Engineering 7
tkhuong@dthu.edu.vn

|     | VD1. Yêu |     |     |     | cầu |     | Người |     | dùng |
| --- | -------- | --- | --- | --- | --- | --- | ----- | --- | ---- |
❖ Một giáo viên yêu cầu viết phần mềm bài tập đại số hỗ trợ việc giải
| phương |     | trình | bậc | hai | như | sau: |     |     |     |
| ------ | --- | ----- | --- | --- | --- | ---- | --- | --- | --- |
▪ Phần mềm cho phép nhập các hệ số của phương trình ax2 + bx +
c = 0 (a,b,c là số thực khác 0) và tính toán cho ra kết quả theo
|     | quy | tắc         | giải | phương |     | trình | bậc | 2   |     |
| --- | --- | ----------- | ---- | ------ | --- | ----- | --- | --- | --- |
| Quy | tắc | giải phương |      | trình  | bậc | 2:    |     |     |     |
Cho phương trình bậc 2: ax2+bx+c=0 (với a,b,c là 3 số thực, a khác 0)
| Các      | bước | giải           | phương         | trình    |       | như sau:   |     |           |        |
| -------- | ---- | -------------- | -------------- | -------- | ----- | ---------- | --- | --------- | ------ |
| B1. Tính |      | delta = b2-4ac |                |          |       |            |     |           |        |
| B2. Xác  |      | đinh           | nghiệm         | theo     | delta |            |     |           |        |
|          |      | + Nếu          | delta<0: PT vô |          |       | nghiệm     |     |           |        |
|          |      | + Nếu          | delta=0: PT có |          |       | nghiệm     |     | kép x =x  | =-b/2a |
|          |      |                |                |          |       |            |     | 1         | 2      |
|          |      | + Nếu          | delta>0: PT có |          |       | 2 nghiệm   |     | phân biệt |        |
|          |      |                | x              | =(-b-căn |       | delta)/ 2a |     |           |        |
1
|     |     |     | x   | =(-b+căn |     | delta)/ 2a |     |     |     |
| --- | --- | --- | --- | -------- | --- | ---------- | --- | --- | --- |
2
Software Engineering 8
tkhuong@dthu.edu.vn

|     | VD2. Yêu |     |     |     |     | cầu |     | Người |     |     |     | dùng |     |     |     |
| --- | -------- | --- | --- | --- | --- | --- | --- | ----- | --- | --- | --- | ---- | --- | --- | --- |
❖
| Chủ  |     | khách  |       | sạn   | yêu      |        | cầu                  | việc     |      | phần |      | mềm  | hỗ trợ   | việc | tính |
| ---- | --- | ------ | ----- | ----- | -------- | ------ | -------------------- | -------- | ---- | ---- | ---- | ---- | -------- | ---- | ---- |
| tiền |     | thuê   | phòng |       | theo     |        | quy                  | tắc      | như  |      | sau: |      |          |      |      |
|      |     | Tính   |       | tiền  | thuê     | phòng  |                      |          |      |      |      |      |          |      |      |
|      |     | Tính   |       | tiền  | thuê     | phòng  | được                 |          | tính | theo |      | quy  | tắc sau: |      |      |
|      |     | Tiền   |       | = Số  | ngày     | thuê   | * đơn                |          | giá  | * Tỷ | lệ   | giảm | giá      |      |      |
|      |     | Số     | ngày  |       | thuê     | = Ngày | trả                  | phòng    |      | –    | Ngày | nhận | phòng    |      |      |
|      |     | Đơn    |       | giá   | dựa trên |        | bảng                 | đơn      | giá  | như  |      | sau: |          |      |      |
|      |     | -      | Loại  | phòng |          |        | Đơn                  | giá/Ngày |      |      |      |      |          |      |      |
|      |     | + Loại |       | A     |          |        | 240.000              |          |      |      |      |      |          |      |      |
|      |     | + Loại |       | B     |          |        | 220.000              |          |      |      |      |      |          |      |      |
|      |     | + Loại |       | C     |          |        | 200.000              |          |      |      |      |      |          |      |      |
|      |     | Tỷ     | lệ    | giảm  | giá      | dựa    | trên                 | quy      | tắc  | giảm |      | giá  |          |      |      |
|      |     | Nếu    | thuê  |       | quá      | 7 ngày | được                 |          | giảm |      | 10%  |      |          |      |      |
|      |     |        |       |       |          |        | Software Engineering |          |      |      |      |      |          |      | 9    |
tkhuong@dthu.edu.vn

|     | VD3. Yêu |     |     |     | cầu |     | Người |     | dùng |     |     |     |     |     |
| --- | -------- | --- | --- | --- | --- | --- | ----- | --- | ---- | --- | --- | --- | --- | --- |
❖
| Phòng |     | tổ    | chức  | cán  |     | bộ yêu | cầu  | viết | phần |     | mềm   | giúp |     | quản |
| ----- | --- | ----- | ----- | ---- | --- | ------ | ---- | ---- | ---- | --- | ----- | ---- | --- | ---- |
| lý    | hồ  | sơ    | nhân  | viên |     | (tra   | cứu, | thêm | nhân |     | viên  | mới, |     | cập  |
| nhật  |     | thông | tin   | nhân |     | viện,  | xóa, | lập  | báo  | cáo | thống |      | kê  | tình |
| hình  |     | nhân  | viên) | các  |     | thông  | tin  | cần  | quản | lý  | theo  | biểu |     | mẫu  |
sau:
|     |     |     |     |     |     | Software Engineering |     |     |     |     |     |     |     | 10  |
| --- | --- | --- | --- | --- | --- | -------------------- | --- | --- | --- | --- | --- | --- | --- | --- |
tkhuong@dthu.edu.vn

VD4. Yêu cầu Người dùng
❖ Hãng du lịch TravelGood đến gặp bạn và đề nghị
làm dự án phần mềm sau:
▪ Mô tả bài toán / yêu cầu người dùng
TravelGood muốn cung cấp cho khách hàng của họ một
ứng dụng đặt vé và lập kế hoạch du lịch. Ứng dụng này
cần cho phép khách lập kế hoạch về các chuyến bay và
khách sạn. Đầu tiên, khách hàng có thể sắp xếp một
chuyến đi, sau đó đặt vé và đặt phòng khách sạn cho
chuyến đi đó. Người dùng có thể lập kế hoạch cho
nhiều chuyến đi. Ngoài ra, phần mềm còn cho phép hủy
các chuyến đã đặt.
Software Engineering 11
tkhuong@dthu.edu.vn

|     | VD5. Yêu |     |           |     | cầu  |                      | người |      | dùng |      |     |      |
| --- | -------- | --- | --------- | --- | ---- | -------------------- | ----- | ---- | ---- | ---- | --- | ---- |
| ❖   | Một      | cửa | hàng….đề  |     |      | nghị                 | xây   | dựng |      | phần | mềm | quản |
|     | lý việc  | thu | chi       | như | sau: |                      |       |      |      |      |     |      |
|     | ▪ Mô     | tả  | bài toán/ |     | yêu  | cầu                  | người | dùng |      |      |     |      |
|     |          |     |           |     |      | Software Engineering |       |      |      |      |     | 12   |
tkhuong@dthu.edu.vn

|         | Yêu  |      | cầu   |      | người |        | dùng |      |          |     |      |     |     |
| ------- | ---- | ---- | ----- | ---- | ----- | ------ | ---- | ---- | -------- | --- | ---- | --- | --- |
| ❖ Những |      | phát |       | biểu | bằng  | ngôn   |      | ngữ  | tự nhiên |     | kết  | hợp | với |
| các     | biểu |      | mẫu   | về   | các   | dịch   | vụ   | mà   | hệ thống |     | cung | cấp | và  |
| những   |      | ràng |       | buộc | (quy  | tắc)   | về   | hoạt | động     | của | nó.  |     |     |
| ❖ Dành  |      | cho  | khách |      | hàng  | (người |      | sử   | dụng)    |     |      |     |     |
❖ Đơn giản, dễ hiểu: không có kiến thức chi tiết về kỹ thuật/
| tin | học |     |     |     |     |                      |     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | -------------------- | --- | --- | --- | --- | --- | --- | --- |
|     |     |     |     |     |     | Software Engineering |     |     |     |     |     |     | 13  |
tkhuong@dthu.edu.vn

|        | Bài | tập  |       | 1    |        |          |         |     |     |        |
| ------ | --- | ---- | ----- | ---- | ------ | -------- | ------- | --- | --- | ------ |
| ❖ Với  | vai | trò  | người |      | dùng,  | bạn muốn | có phần |     | mềm | hỗ trợ |
| nghiệp |     | vụ   | đang  | thực | hiện,  | hãy mô   | tả yêu  | cầu | của | bạn về |
| dự     | án  | phần | mềm   |      | này??? |          |         |     |     |        |
Software Engineering 15
tkhuong@dthu.edu.vn

|     |      | VD1. Yêu |        |        |       |            | cầu   |                      |      | hệ   | thống   |     |       |      |       |     |        |      |
| --- | ---- | -------- | ------ | ------ | ----- | ---------- | ----- | -------------------- | ---- | ---- | ------- | --- | ----- | ---- | ----- | --- | ------ | ---- |
| ❖   | Sau  |          | khi    | nhận   |       | thực       |       | hiện                 | phần |      | mềm     |     | bài   | tập  | đại   | số  | hỗ     | trợ  |
|     | việc |          | giải   | phương |       |            | trình |                      | bậc  | 2,   | nhóm    |     | phát  |      | triển | sẽ  | chi    | tiết |
|     | ra   | thành    |        | yêu    |       | cầu        | hệ    | thống:               |      |      |         |     |       |      |       |     |        |      |
|     | ▪    | Hệ       | thống  |        | cho   |            | phép  | người                |      | dùng | nhập    |     | thông |      | tin   | của | phương |      |
|     |      | trình    |        | đúng   |       | theo       | quy   | tắc:                 | hệ   | số   | a,b,c   |     | là số | thực | và    |     | a khác | 0    |
|     | ▪    | Hệ       | thống  |        | tính  |            | toán  | và                   | cho  |      | ra kết  | quả |       | theo | các   |     | bước   | giải |
|     |      | phương   |        |        | trình |            |       |                      |      |      |         |     |       |      |       |     |        |      |
|     | ▪    | Hệ       | thống  |        | là    | ứng        |       | dụng                 | dạng |      | windows |     | form, |      | triển |     | khai   | trên |
|     |      | môi      | trường |        |       | windows….. |       |                      |      |      |         |     |       |      |       |     |        |      |
|     |      |          |        |        |       |            |       | Software Engineering |      |      |         |     |       |      |       |     |        | 16   |
tkhuong@dthu.edu.vn

|     | VD2. Yêu |      |      |       |     | cầu   |      | hệ   | thống |      |      |        |     |      |      |
| --- | -------- | ---- | ---- | ----- | --- | ----- | ---- | ---- | ----- | ---- | ---- | ------ | --- | ---- | ---- |
| ❖   | Phần     | mềm  |      | phải  | có  | các   | chức |      | năng  |      | sau: |        |     |      |      |
|     | ▪ Thêm,  |      | cập  | nhật  |     | (tên, |      | đơn  | giá), | xóa  | loại | phòng, |     | cập  | nhật |
|     | quy      | định |      | giảm  | giá |       |      |      |       |      |      |        |     |      |      |
|     | ▪ Cho    |      | phép | người |     | dùng  |      | nhập |       | ngày | nhận | phòng, |     | ngày | trả  |
phòng
|     | ▪ Tính  |        | toán | cho |       | ra số | ngày                 |      | ở và  | áp   | dụng | công | thức | tính | ra  |
| --- | ------- | ------ | ---- | --- | ----- | ----- | -------------------- | ---- | ----- | ---- | ---- | ---- | ---- | ---- | --- |
|     | số      | tiền   | thuê |     | phòng |       | -> lưu               | lại  | kết   | quả  |      |      |      |      |     |
|     | ▪ In    | ra hóa |      | đơn | tính  | tiền  |                      | cho  | khách | hàng |      |      |      |      |     |
|     | ▪ Ứng   | dụng   |      | xây | dựng  |       | với                  | giao | diện  | form |      |      |      |      |     |
|     | ▪ …………… |        |      |     |       |       |                      |      |       |      |      |      |      |      |     |
|     |         |        |      |     |       |       | Software Engineering |      |       |      |      |      |      |      | 17  |
tkhuong@dthu.edu.vn

|     | VD3. Yêu |      |      |       |       | cầu   |                      | hệ    |      | thống |      |      |      |         |         |         |     |
| --- | -------- | ---- | ---- | ----- | ----- | ----- | -------------------- | ----- | ---- | ----- | ---- | ---- | ---- | ------- | ------- | ------- | --- |
| ❖   | Phần     | mềm  |      | phải  | có    | chức  |                      | năng: |      |       |      |      |      |         |         |         |     |
|     | ▪ Cho    | phép |      | thêm, |       | cập   | nhật,                |       | xóa  |       | hồ   | sơ   | nhận | viên    | theo    | BM1     | -   |
|     | >        | lưu  | vào  | csdl  |       |       |                      |       |      |       |      |      |      |         |         |         |     |
|     | ▪ Tra    | cứu  |      | hồ    | sơ    | nhân  | viên;                |       | pm   |       | cho  | phép |      | nhập    | vào tên | hoặc    |     |
|     | địa      | chỉ, | hoặc |       | trình | độ    | của                  |       | nhận |       | viên | và   | sau  | đó      | xuất    | ra danh |     |
|     | sách     | các  |      | nhân  |       | viên  | thông                |       | tin  | tra   | cứu  | theo |      | BM1.    |         |         |     |
|     | ▪ Lập    | báo  |      | cáo   | thông |       | kê:                  | chọn  |      |       | thời | gian |      | muốn    | thống   | kê      | và  |
|     | xuất     | ra   | kết  | quả   |       | thống | kê                   | như   |      | BM2,  |      | in   | ra   | kết quả | thống   | kê.     |     |
|     |          |      |      |       |       |       | Software Engineering |       |      |       |      |      |      |         |         |         | 19  |
tkhuong@dthu.edu.vn

|     | VD4. Yêu |     |     |     | cầu | hệ  | thống |     |     |     |     |
| --- | -------- | --- | --- | --- | --- | --- | ----- | --- | --- | --- | --- |
❖ Sau khi nhận làm phần mềm cho TravelGood đội phát triển chi tiết
| hóa | thành | các | yêu | cầu | hệ thống: |     |     |     |     |     |     |
| --- | ----- | --- | --- | --- | --------- | --- | --- | --- | --- | --- | --- |
1. Người dùng có thể lập kế hoạch một chuyến đi bằng cách chọn
một trình tự các điểm đến, rồi lưu lại. (kèm theo sơ đồ mô tả
|     | kịch | bản   | ca  | sử dụng) |          |       |       |      |         |        |     |
| --- | ---- | ----- | --- | -------- | -------- | ----- | ----- | ---- | ------- | ------ | --- |
| 2.  | Hệ   | thống | cần | là       | ứng dụng | Web,  | chạy  | được | tại tất | cả các | hệ  |
|     | điều | hành  | và  | hầu      | hết các  | trình | duyệt |      |         |        |     |
3. Ứng dụng Web phải triển khai được tại các server tiêu chuẩn
|     | như | GlassFish |     | hoặc | Tomcat |     |     |     |     |     |     |
| --- | --- | --------- | --- | ---- | ------ | --- | --- | --- | --- | --- | --- |
4. Hệ thống phải dễ sử dụng: đạt một test usability (kèm chi tiết
cụ thể)
| 5.  | …   |     |     |     |                      |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | -------------------- | --- | --- | --- | --- | --- | --- |
|     |     |     |     |     | Software Engineering |     |     |     |     |     | 21  |
tkhuong@dthu.edu.vn

|     |        | Yêu |      | cầu |      | hệ  |      | thống |      |     |      |      |      |     |     |
| --- | ------ | --- | ---- | --- | ---- | --- | ---- | ----- | ---- | --- | ---- | ---- | ---- | --- | --- |
| ❖   | Một    | tài | liệu |     | có   | cấu | trúc | mô    | tả   | chi | tiết | chức | năng | của | hệ  |
|     | thống, |     | các  |     | dịch | vụ  | và   | ràng  | buộc |     | về   | hoạt | động | của | hệ  |
thống.
| ❖   | Định | nghĩa |     |      | chính | xác  |     | cái gì               | cần | được |     | cài  | đặt.  |      |     |
| --- | ---- | ----- | --- | ---- | ----- | ---- | --- | -------------------- | --- | ---- | --- | ---- | ----- | ---- | --- |
|     | ▪    | Có    | thể | là   | một   | phần |     | của                  | hợp | đồng |     | giữa | khách | hàng | và  |
|     |      | người |     | nhận | thầu  |      |     |                      |     |      |     |      |       |      |     |
|     |      |       |     |      |       |      |     | Software Engineering |     |      |     |      |       |      | 23  |
tkhuong@dthu.edu.vn

|     |     | Các |     | ví  | dụ    | khác |     |
| --- | --- | --- | --- | --- | ----- | ---- | --- |
|     | Đặc | tả  | yêu | cầu | người | dùng |     |
1. Phần mềm phải cung cấp một phương tiện để biểu diễn và truy nhập các
| file bên |     | ngoài | được | tạo | bằng | các công | cụ khác. |
| -------- | --- | ----- | ---- | --- | ---- | -------- | -------- |
|          | Đặc | tả    | yêu  | cầu | hệ   | thống    |          |
1.1. Người dùng cần được cung cấp tiện ích để định nghĩa kiểu của các file
ngoài.
1.2 Mỗi kiểu file ngoài có thể được biểu diễn dưới dạng một biểu tượng trên
| phần |     | hiển | thị của | người | dùng. |     |     |
| ---- | --- | ---- | ------- | ----- | ----- | --- | --- |
1.3 Mỗi kiểu file ngoài có thể có một công cụ có thể dùng cho loại file đó.
1.4 Cần cung cấp các tiện ích để người dùng có thể định nghĩa biểu tượng
cho file ngoài.
1.5 Khi một người dùng chọn một biểu tượng đại diện cho một file ngoài,
hiệu ứng của việc chọn đó là gọi công cụ tương ứng với kiểu của file đó để
| chạy | nó. |     |     |     |     |     |     |
| ---- | --- | --- | --- | --- | --- | --- | --- |
Software Engineering 24
tkhuong@dthu.edu.vn

| Bài | tập | 2   |     |     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
❖
| Với vai | trò  | phân  | tích  | viên,                | bạn | hãy | mô tả     | yêu | cầu     | hệ  |
| ------- | ---- | ----- | ----- | -------------------- | --- | --- | --------- | --- | ------- | --- |
| thống   | của  | dự án | phần  | mềm                  | từ  | yêu | cầu người |     | sử dụng |     |
| đã thu  | thập | được  | ở BT1 |                      |     |     |           |     |         |     |
|         |      |       |       | Software Engineering |     |     |           |     |         | 26  |
tkhuong@dthu.edu.vn

YÊU CẦU PHẦN MỀM
| Phân |     | loại   | yêu   | cầu  |      | theo | tính    | chất,   | có 2   | loại | yêu  | cầu |          |
| ---- | --- | ------ | ----- | ---- | ---- | ---- | ------- | ------- | ------ | ---- | ---- | --- | -------- |
| ❖    | Yêu | cầu    | chức  |      | năng |      | (nghiệp |         | vụ)    |      |      |     |          |
|      | ▪   | Nghiệp |       | vụ   | cần  | được |         | hỗ trợ  |        |      |      |     |          |
| ❖    | Yêu | cầu    | phi   | chức |      | năng |         | (chất   | lượng) |      |      |     |          |
|      | ▪   | Các    | ràng  | buộc |      | trên |         | yêu cầu | chức   | năng | (tốc | độ, | bảo mật, |
|      |     | giao   | diện, | …)   |      |      |         |         |        |      |      |     |          |
Software Engineering 27
tkhuong@dthu.edu.vn

|       | Đặt |     | vấn    |     | đề    |        |                      |          |      |       |       |     |         |      |
| ----- | --- | --- | ------ | --- | ----- | ------ | -------------------- | -------- | ---- | ----- | ----- | --- | ------- | ---- |
| ❖ Để  |     | xây | dựng   |     | được  | một    |                      | hệ thống |      | có    | thể   | sử  | dụng    | được |
| trong |     |     | thực   | tế, | trước | hết    | phải                 | đạt      | được |       | những |     | yêu cầu | gì?  |
| ❖ Yêu |     | cầu | chức   |     | năng  | có     | phải                 | quan     |      | trọng | nhất  |     | không?  |      |
| ❖ Nếu |     | ta  | không  |     | xác   | định   | đầy                  | đủ,      | rõ   | ràng  | các   | yêu | cầu     | chức |
| năng  |     |     | thì sẽ | xảy | ra    | chuyện |                      | gì?      |      |       |       |     |         |      |
|       |     |     |        |     |       |        | Software Engineering |          |      |       |       |     |         | 28   |
tkhuong@dthu.edu.vn

YÊU CẦU CHỨC NĂNG
| ❖ Yêu | cầu        | chức  | năng |      | mô                   | tả   | hệ thống |       | sẽ  | làm  | gì. Nghĩa |      | là  |
| ----- | ---------- | ----- | ---- | ---- | -------------------- | ---- | -------- | ----- | --- | ---- | --------- | ---- | --- |
| phần  | mềm        | có    | khả  | năng |                      | thực | hiện     | những |     | công | việc      | gì   | để  |
| hỗ    | trợ nghiệp |       | vụ.  |      |                      |      |          |       |     |      |           |      |     |
| ❖ Một | chức       | năng  |      | được | mô                   |      | tả thông |       | qua | dữ   | liệu đầu  | vào, |     |
| cách  | xử         | lý và | dữ   | liệu | được                 |      | kết xuất |       |     |      |           |      |     |
|       |            |       |      |      | Software Engineering |      |          |       |     |      |           |      | 29  |
tkhuong@dthu.edu.vn

| Một | số  | ví  | dụ  | - xét | yêu | cầu | chức | năng |
| --- | --- | --- | --- | ----- | --- | --- | ---- | ---- |
❖ Tôi muốn pm giúp tôi thực hiện công việc tính lương, lập báo cáo tồn
| kho, đánh | cờ  | caro, | giải bài | tập đại | số,… |     |     |     |
| --------- | --- | ----- | -------- | ------- | ---- | --- | --- | --- |
❖ Tôi muốn pm giúp độc giả tra cứu sách muốn mượn, việc tra cứu
| này phải | được | thực | hiện | ở bất kỳ | nơi nào. |     |     |     |
| -------- | ---- | ---- | ---- | -------- | -------- | --- | --- | --- |
❖ Tôi muốn giúp tôi lập hóa đơn tiền điện và phải in được khoảng
20.000 hóa đơn của khu vực tp cao lãnh này chỉ diễn ra tối đa 1
ngày
❖
Tôi muốn pm giúp tra cứu các chuyến xe buýt trên địa bàn tỉnh đồng
tháp, việc tra cứu này được diễn ra trên sơ đồ của những tuyến xe
buýt
❖ …………………………………………
Software Engineering 30
tkhuong@dthu.edu.vn

|     | Ví      |      | dụ1 - |     |               | Yêu |       |      | cầu |       | chức |     |     | năng   |     |         |     |     |
| --- | ------- | ---- | ----- | --- | ------------- | --- | ----- | ---- | --- | ----- | ---- | --- | --- | ------ | --- | ------- | --- | --- |
| ❖   | Trong   | phần |       | mềm | TouristTravel |     |       |      |     | thì:  |      |     |     |        |     |         |     |     |
|     | ▪ Người |      | dùng  |     | có            | thể |       | lập  | kế  | hoạch |      | một |     | chuyến |     | đi, đặt | vé, | đặt |
|     | phòng,  |      | lưu   | một |               | kế  | hoạch |      | để  | sau   | này  | sẽ  | đặt | vé     | đặt | phòng…  |     |     |
| ❖   | Trong   | phần |       | mềm | LIBSYS        |     |       | thì: |     |       |      |     |     |        |     |         |     |     |
▪ Người sử dụng có thể tìm kiếm tài liệu dựa trên các từ khóa có
|     | trong |     | tài     | liệu | hoặc |       | tên | tài     | liệu  |     |      |      |      |       |     |          |       |     |
| --- | ----- | --- | ------- | ---- | ---- | ----- | --- | ------- | ----- | --- | ---- | ---- | ---- | ----- | --- | -------- | ----- | --- |
|     | ▪ Hệ  |     | thống   | sẽ   | cung |       | cấp |         | những |     | giao | diện |      | thích | hợp | để       | người | sử  |
|     | dụng  |     | đọc     | được |      | các   |     | định    | dạng  |     | khác |      | nhau | của   |     | tài liệu | như:  | văn |
|     | bản   |     | (.txt), | PDF, |      | Word, |     | Excel,… |       |     |      |      |      |       |     |          |       |     |
▪ Tất cả những hoá đơn mà người sử dụng đăng ký để in sao tài
|     | liệu |     | có một |     | mã  | duy | nhất. |     |                      |     |     |     |     |     |     |     |     |     |
| --- | ---- | --- | ------ | --- | --- | --- | ----- | --- | -------------------- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|     |      |     |        |     |     |     |       |     | Software Engineering |     |     |     |     |     |     |     |     | 31  |
tkhuong@dthu.edu.vn

|      | Yêu    | cầu  | chức    | năng | –   | tính | chất  |         |
| ---- | ------ | ---- | ------- | ---- | --- | ---- | ----- | ------- |
| ❖ Về | nguyên | tắc, | các yêu | cầu  | nên | hoàn | chỉnh | và nhất |
quán.
| ❖ Hoàn | chỉnh | (complete) |     |     |     |     |     |     |
| ------ | ----- | ---------- | --- | --- | --- | --- | --- | --- |
▪ Tất cả các dịch vụ mà người dùng yêu cầu phải được định nghĩa.
| ❖ Nhất | quán(consistent) |     |     |     |     |     |     |     |
| ------ | ---------------- | --- | --- | --- | --- | --- | --- | --- |
▪ Không có bất cứ mâu thuẫn hay xung đột nào trong các mô tả về
|     | các yêu | cầu. |     |     |     |     |     |     |
| --- | ------- | ---- | --- | --- | --- | --- | --- | --- |
Trên thực tế, không thể tạo ra tài liệu các yêu cầu vừa hoàn
chỉnh vừa nhất quán được!!
|     | Rất dễ mắc lỗi |     | hay bỏ sót yêu cầu khi viết đặc tả cho các hệ |     |     |     |     |     |
| --- | -------------- | --- | --------------------------------------------- | --- | --- | --- | --- | --- |
thống phức tạp.
Các stakeholder có các nhu cầu khác nhau và thường không nhất
quán với nhau.
Software Engineering 34
tkhuong@dthu.edu.vn

YÊU CẦU CHỨC NĂNG
| ❖ Phân | loại      | yêu   | cầu | chức                 | năng | dựa       | trên  | ý nghĩa | sử  |
| ------ | --------- | ----- | --- | -------------------- | ---- | --------- | ----- | ------- | --- |
| dụng   | có 2      | nhóm  | yêu | cầu                  |      |           |       |         |     |
|        | Nhóm yêu  | cầu   |     |                      |      | Nhóm yêu  | cầu   |         |     |
|        |           |       |     |                      |      | khai thác | thông |         |     |
|        | tiếp nhận | thông |     |                      |      |           |       |         |     |
|        | tin       |       |     |                      |      | tin       |       |         |     |
|        |           |       |     | Software Engineering |      |           |       |         | 35  |
tkhuong@dthu.edu.vn

|       | Đặt      | vấn   | đề       |      |       |         |       |      |         |     |
| ----- | -------- | ----- | -------- | ---- | ----- | ------- | ----- | ---- | ------- | --- |
| ❖ Nếu | hệ       | thống | chỉ thỏa | mãn  | những | yêu     | cầu   | chức | năng    | thì |
| đã    | đủ chưa? |       |          |      |       |         |       |      |         |     |
| ❖ Ví  | dụ hệ    | thống | không    | tiện | dụng  | đối với | người |      | sử dụng | thì |
sao?
| ❖ Yêu | cầu | phi | chức năng | bao                  | gồm | những | vấn | đề  | gì? |     |
| ----- | --- | --- | --------- | -------------------- | --- | ----- | --- | --- | --- | --- |
|       |     |     |           | Software Engineering |     |       |     |     |     | 38  |
tkhuong@dthu.edu.vn

YÊU CẦU PHI CHỨC NĂNG
| ❖   | Là      | những |                                     | yêu  | cầu   | không   | liên | quan     |       | trực   | tiếp đến      |      | những |
| --- | ------- | ----- | ----------------------------------- | ---- | ----- | ------- | ---- | -------- | ----- | ------ | ------------- | ---- | ----- |
|     | dịch    | vụ    | mà                                  | hệ   | thống | cung    | cấp  | đến      | người |        | dùng.         |      |       |
| ❖   | Liên    | quan  |                                     | đến  | những | thuộc   |      | tính hệ  | thống |        | (độ tin       | cậy, | thời  |
|     | gian    | trả   | lời                                 | và   | yêu   | cầu về  | mặt  | lưu      | trữ)  |        | và các        | ràng | buộc  |
|     | (khả    | năng  |                                     | của  | thiết | bị      | vào  | ra, biểu |       | diễn   | dữ            | liệu | dùng  |
|     | trong   | các   |                                     | giao | diện  | với các |      | hệ thống |       | khác). |               |      |       |
|     | Yêu cầu |       | phi chức năng có thể quan trọng hơn |      |       |         |      |          |       |        | yêu cầu chức  |      |       |
năng!!
Nếu những yêu cầu này không đạt được, hệ thống sẽ trở nên vô
dụng.
|     |     |     |     |     |     | Software Engineering |     |     |     |     |     |     | 39  |
| --- | --- | --- | --- | --- | --- | -------------------- | --- | --- | --- | --- | --- | --- | --- |
tkhuong@dthu.edu.vn

Một số ví dụ - xét yc phi chức năng
❖ Tôi muốn pm giúp độc giả tra cứu sách muốn mượn, việc tra cứu
này phải được thực hiện ở bất kỳ nơi nào.
❖ Tôi muốn giúp tôi lập hóa đơn tiền điện và phải in được khoảng
20.000 hóa đơn của khu vực tp cao lãnh này chỉ diễn ra tối đa 1
ngày
❖ Tôi muốn pm giúp tra cứu các chuyến xe buýt trên địa bàn tỉnh đồng
tháp, việc tra cứu này được diễn ra trên sơ đồ của những tuyến xe
buýt
❖ …………………………………………
Software Engineering 40
tkhuong@dthu.edu.vn

|     |      | VD1. Yêu |      |       |      |           |     | cầu  | phi chức             |      |        |      |       | năng |       |           |        |
| --- | ---- | -------- | ---- | ----- | ---- | --------- | --- | ---- | -------------------- | ---- | ------ | ---- | ----- | ---- | ----- | --------- | ------ |
| ❖   | Xây  |          | dựng |       | phần |           | mềm |      | TouristTravel        |      |        |      |       | với  | các   | yêu       | cầu    |
|     | ràng |          | buộc |       | sau: |           |     |      |                      |      |        |      |       |      |       |           |        |
|     | ▪    | Hệ       |      | thống | cần  |           | là  | ứng  | dụng                 |      | Web,   |      | chạy  |      | được  | tại       | tất cả |
|     |      | các      |      | hệ    | điều | hành      |     | và   | hầu                  | hết  | các    |      | trình |      | duyệt |           |        |
|     | ▪    | Ứng      |      | dụng  |      | Web       |     | phải | triển                | khai |        | được |       | tại  | các   | server    | tiêu   |
|     |      | chuẩn    |      |       | như  | GlassFish |     |      | hoặc                 |      | Tomcat |      |       |      |       |           |        |
|     | ▪    | Hệ       |      | thống | phải |           | dễ  | sử   | dụng                 |      | – phải |      | đạt   | một  | test  | usability |        |
|     |      |          |      |       |      |           |     |      | Software Engineering |      |        |      |       |      |       |           | 41     |
tkhuong@dthu.edu.vn

| Phân | loại | yêu                  | cầu | phi chức           |     | năng              |
| ---- | ---- | -------------------- | --- | ------------------ | --- | ----------------- |
|      | •    | Những yêu cầu đặc tả |     | hay ràng buộc hành |     | vi của phần mềm.  |
•Ví dụ yêu cầu về hiệu năng của phần mềm liên quan đến tốc độ
YC SẢN PHẨM
|     | thực thi, | lượng bộ nhớ sử dụng, độ |     |     | tin cậy, ... |     |
| --- | --------- | ------------------------ | --- | --- | ------------ | --- |
• Những yc xuất phát từ các chính sách và thủ tục về mặt tổ chức.
•Vd: yc về quy trình hoạt động định nghĩa hệ thống được sử dụng?, yc
YC TỔ CHỨC
về quy trình phát triển đặc tả ngôn ngữ lập trình, môi trường phát
triển và chuẩn về quy trình được sử dụng...
• Những yêu cầu xuất phát từ những nhân tố bên ngoài ảnh hưởng
đến hệ thống và quy trình phát triển của nó.
YC BÊN NGOÀI
|     |     | •Ví dụ yêu | cầu về tương tác, yêu cầu về mặt pháp lý, ... |     |     |     |
| --- | --- | ---------- | --------------------------------------------- | --- | --- | --- |
Software Engineering 42
tkhuong@dthu.edu.vn

YÊU CẦU PHI CHỨC NĂNG
| ❖ Phân | loại yêu | cầu phi | chức | năng |
| ------ | -------- | ------- | ---- | ---- |
Software Engineering 43
tkhuong@dthu.edu.vn

|     |     | VD1. Yêu |      |        |        | cầu   |       |                      | phi chức |       |          | năng |     |           |      |     |
| --- | --- | -------- | ---- | ------ | ------ | ----- | ----- | -------------------- | -------- | ----- | -------- | ---- | --- | --------- | ---- | --- |
| ❖   | Yêu | cầu      | phi  | chức   |        | năng  | trong |                      | hệ thống |       | LIBSYS   |      |     |           |      |     |
|     | ▪   | Yêu      | cầu  | về     | sản    |       | phẩm: |                      | LIBSYS   |       | phải     | được |     | cài đặt   | bằng |     |
|     |     | HTML     |      | mà     | không  | có    | frame |                      | hoặc     | Java  | applets. |      |     |           |      |     |
|     | ▪   | Yêu      | cầu  | về     | mặt    | tổ    | chức: |                      | Quy      | trình | xây      | dựng |     | hệ thống  |      | và  |
|     |     | các      | tài  | liệu   | chuyển |       |       | giao                 | phải     | thoả  |          | mãn  | các | quy       | tắc  | đã  |
|     |     | được     | định |        | nghĩa  | trong |       | XYZCo-SP-STAN-95.    |          |       |          |      |     |           |      |     |
|     | ▪   | Yêu      | cầu  | ngoài: |        | Hệ    | thống |                      | không    |       | được     | để   | lộ  | các thông |      | tin |
|     |     | cá       | nhân | của    | khách  |       | hàng. |                      |          |       |          |      |     |           |      |     |
|     |     |          |      |        |        |       |       | Software Engineering |          |       |          |      |     |           |      | 44  |
tkhuong@dthu.edu.vn

VD2. Yêu cầu phi chức năng
❖ Yêu cầu phi chức năng trong hệ thống MHC-PMS
▪ Yêu cầu sản phẩm: Hệ thống MHC-PMS sẽ luôn hoạt động
để các phòng khám sử dụng trong suốt giờ làm việc (từ
thứ 2 đến thứ 6, 8.30 – 17.30). Thời gian ngừng hoạt động
trong suốt giờ làm việc sẽ không vượt quá sẽ không vượt
quá 5s trong bất kỳ ngày nào.
▪ Yêu cầu tổ chức: Người sử dụng hệ thống sẽ phải tự đăng
nhập bằng thẻ nhân viên của họ.
▪ Yêu cầu bên ngoài: Hệ thống sẽ cài đặt các quy định về
tính riêng tư của bệnh nhân.
Software Engineering 45
tkhuong@dthu.edu.vn

| Bài   |      | tập |     |      |      |        |     |          |
| ----- | ---- | --- | --- | ---- | ---- | ------ | --- | -------- |
| ❖ Xác | định | yêu | cầu | chức | năng | và yêu | cầu | phi chức |
| năng  | cho  | pm  | BT1 |      |      |        |     |          |
Software Engineering 46
tkhuong@dthu.edu.vn

NỘI DUNG
| 1   | YC CHỨC |     | NĂNG    | &   | YC PHI | CHỨC | NĂNG |
| --- | ------- | --- | ------- | --- | ------ | ---- | ---- |
|     | ĐẶC     | TẢ  | YÊU CẦU |     |        |      |      |
2
| 33  | QUY      | TRÌNH | CÔNG |      | NGHỆ | YÊU CẦU |     |
| --- | -------- | ----- | ---- | ---- | ---- | ------- | --- |
| 44  | THU      | THẬP  | VÀ   | PHÂN | TÍCH | YÊU     | CẦU |
| 5   | THẨM     | ĐỊNH  | YÊU  |      | CẦU  |         |     |
| 6   | QUẢN     | TRỊ   | YÊU  | CẦU  |      |         |     |
| 7   | TÀI LIỆU |       | YÊU  | CẦU  | PM   |         |     |
47
tkhuong@dthu.edu.vn

2. ĐẶC TẢ YÊU CẦU
❖ Khái niệm
❖ Tính chất
❖ Phương pháp
Software Engineering 48
tkhuong@dthu.edu.vn

|     |      | 2. ĐẶC TẢ YÊU CẦU – |           |        |       |        |       |                      |      |        |      |       | KHÁI NIỆM |       |       |        |      |
| --- | ---- | ------------------- | --------- | ------ | ----- | ------ | ----- | -------------------- | ---- | ------ | ---- | ----- | --------- | ----- | ----- | ------ | ---- |
| ❖   | Là   | tài                 | liệu      | mô     | tả    | chi    | tiết  |                      | các  | yêu    | cầu  |       | người     | dùng  |       | và     | yêu  |
|     | cầu  |                     | hệ thống. |        |       |        |       |                      |      |        |      |       |           |       |       |        |      |
| ❖   | Yêu  |                     | cầu       | người  |       | dùng   | phải  |                      | được |        | mô   | tả    | sao       | cho   | người |        | sử   |
|     |      |                     |           |        |       |        | Ai sẽ |                      | đọc  | tài    | liệu |       |           |       |       |        |      |
|     | dụng |                     | cuối      | và     | khách |        | hàng  |                      |      | (những |      | người |           | không |       | có     | kiến |
|     |      |                     |           |        |       |        | yêu   | cầu                  |      | này??? |      |       |           |       |       |        |      |
|     | thức |                     | về kỹ     | thuật) |       | có     | thể   | hiểu                 |      | được.  |      |       |           |       |       |        |      |
| ❖   | Yêu  |                     | cầu       | hệ     | thống | là     | những |                      |      | yêu    | cầu  | chi   | tiết      | và    | có    | thể    | bao  |
|     | gồm  |                     | những     |        | thông | tin    | về    | kỹ                   |      | thuật. |      |       |           |       |       |        |      |
| ❖   | Yêu  |                     | cầu có    | thể    |       | là một |       | phần                 |      | của    | hợp  | đồng. |           |       |       |        |      |
|     | ▪    | Do                  | đó        | việc   | đặc   | tả     | yêu   |                      | cầu  | hoàn   |      | chỉnh | đến       | mức   |       | có thể | là   |
|     |      | quan                | trọng.    |        |       |        |       |                      |      |        |      |       |           |       |       |        |      |
|     |      |                     |           |        |       |        |       | Software Engineering |      |        |      |       |           |       |       |        | 49   |
tkhuong@dthu.edu.vn

|     |     | 2. ĐẶC TẢ YÊU CẦU – |     |     |     |     |     |     |     |     |       | TÍNH CHẤT |     |     |     |     |
| --- | --- | ------------------- | --- | --- | --- | --- | --- | --- | --- | --- | ----- | --------- | --- | --- | --- | --- |
| ❖   | Tài | liệu                |     | mô  | tả  | yêu |     | cầu | đòi | hỏi | phải: |           |     |     |     |     |
▪
|     |     | Đầy   |     | đủ:  | mọi   | yêu   |     | cầu | của   | người | dùng      | phải | được      | mô   | tả; |      |
| --- | --- | ----- | --- | ---- | ----- | ----- | --- | --- | ----- | ----- | --------- | ---- | --------- | ---- | --- | ---- |
|     | ▪   | Không |     | mâu  |       | thuẫn |     | với | nhau; |       |           |      |           |      |     |      |
|     | ▪   | Chính |     | xác: |       | yêu   | cầu |     | không | được  | hiểu      | mơ   | hồ, chỉ   | được |     | hiểu |
|     |     | theo  |     | một  | nghĩa |       | duy |     | nhất  | giữa  | các thành |      | viên tham |      | gia | xây  |
|     |     | dựng  |     | phần |       | mềm.  |     |     |       |       |           |      |           |      |     |      |
❖
|     | Một |     | đặc | tả   | yêu       | cầu   |      | tốt | cần                  | có:        |              |     |     |     |     |     |
| --- | --- | --- | --- | ---- | --------- | ----- | ---- | --- | -------------------- | ---------- | ------------ | --- | --- | --- | --- | --- |
|     | ▪   | Ngữ |     | cảnh | (context) |       |      |     |                      |            |              |     |     |     |     |     |
|     | ▪   | Ứng |     | xử/  | ràng      |       | buộc |     | (behaviors/          |            | constraints) |     |     |     |     |     |
|     | ▪   | Có  | thể | kiểm |           | chứng |      |     | được                 | (testable) |              |     |     |     |     |     |
|     |     |     |     |      |           |       |      |     | Software Engineering |            |              |     |     |     |     | 50  |
tkhuong@dthu.edu.vn

|      | 2. ĐẶC TẢ YÊU CẦU – |      |        |        |        | PHƯƠNG PHÁP |
| ---- | ------------------- | ---- | ------ | ------ | ------ | ----------- |
| ❖ Có | 3 phương            |      | pháp   | để đặc | tả yêu | cầu         |
| ▪    | Dùng                | ngôn | ngữ tự | nhiên  |        |             |
▪
|     | Dùng | ngôn    | ngữ hình | thức |     |     |
| --- | ---- | ------- | -------- | ---- | --- | --- |
| ▪   | Dùng | mô hình |          |      |     |     |
Software Engineering 51
tkhuong@dthu.edu.vn

|     | Ngôn |     |     | ngữ | tự nhiên |     | – VD1 |
| --- | ---- | --- | --- | --- | -------- | --- | ----- |
❖ Một giáo viên yêu cầu viết phần mềm bài tập đại số hỗ trợ việc giải
| phương |     | trình |     | bậc hai như | sau: |     |     |
| ------ | --- | ----- | --- | ----------- | ---- | --- | --- |
▪ Phần mềm cho phép nhập các hệ số của phương trình ax2 + bx +
c = 0 (a,b,c là số thực khác 0) và tính toán cho ra kết quả theo
|     | quy | tắc         | giải | phương    | trình bậc | 2   |     |
| --- | --- | ----------- | ---- | --------- | --------- | --- | --- |
| Quy | tắc | giải phương |      | trình bậc | 2:        |     |     |
Cho phương trình bậc 2: ax2+bx+c=0 (với a,b,c là 3 số thực, a khac 0)
| Các      | bước | giải           | phương         | trình      | như sau: |          |        |
| -------- | ---- | -------------- | -------------- | ---------- | -------- | -------- | ------ |
| B1. Tính |      | delta = b2-4ac |                |            |          |          |        |
| B2. Xác  |      | đinh           | nghiệm         | theo delta |          |          |        |
|          |      | + Nếu          | delta<0: PT vô |            | nghiệm   |          |        |
|          |      | + Nếu          | delta=0: PT có |            | nghiệm   | kép x =x | =-b/2a |
1 2
|     |     | + Nếu | delta>0: PT có |            | 2 nghiệm   | phân | biệt |
| --- | --- | ----- | -------------- | ---------- | ---------- | ---- | ---- |
|     |     |       |                | x1=(-b-căn | delta)/ 2a |      |      |
|     |     |       |                | x2=(-b+căn | delta)/ 2a |      |      |
Software Engineering 52
tkhuong@dthu.edu.vn

|     |        | Ngôn |     |      | ngữ  |      |     | tự   | nhiên |     |      |      |      |     |        |       |      |     |
| --- | ------ | ---- | --- | ---- | ---- | ---- | --- | ---- | ----- | --- | ---- | ---- | ---- | --- | ------ | ----- | ---- | --- |
| ❖   | Yêu    | cầu  |     | được | viết | dưới |     | dạng | câu   |     | dùng |      | ngôn |     | ngữ tự | nhiên |      | với |
|     | sự     | hỗ   | trợ | của  |      | bảng | và  | biểu | đồ    | thì | dễ   | diễn |      | đạt | yêu    | cầu.  |      | Tuy |
|     | nhiên, |      | sử  | dụng |      | ngôn | ngữ | tự   | nhiên |     | sẽ   | có   | một  | số  | hạn    | chế   | như: |     |
▪ Không rõ ràng: tính chính xác rất khó đạt được nếu tài liệu khó
đọc;
|     | ▪   | Quá |     | mềm | dẻo: | cùng |     | một vấn | đề  | nhưng |     | có  | nhiều |     | cách | đặc | tả; |     |
| --- | --- | --- | --- | --- | ---- | ---- | --- | ------- | --- | ----- | --- | --- | ----- | --- | ---- | --- | --- | --- |
▪ Thiếu khả năng module hóa: cấu trúc ngôn ngữ tự nhiên không
|       |      | tương |     | xứng | với | cấu   | trúc   | của                  | các  | yêu | cầu  |     | hệ    | thống |         |     |       |     |
| ----- | ---- | ----- | --- | ---- | --- | ----- | ------ | -------------------- | ---- | --- | ---- | --- | ----- | ----- | ------- | --- | ----- | --- |
| →     | Ngôn |       | ngữ |      | tự  | nhiên | thường |                      | gây  |     | hiểu |     | nhầm, |       | và hiểu |     | không |     |
| thống |      | nhất  |     | giữa | các | thành |        | viên                 | tham | gia |      | xây | dựng  |       | phần    | mềm |       |     |
|       |      |       |     |      |     |       |        | Software Engineering |      |     |      |     |       |       |         |     |       | 54  |
tkhuong@dthu.edu.vn

|     |       | Ngôn  |      |       | ngữ |         | hình |      |        | thức |        |       |         |       |          |     |
| --- | ----- | ----- | ---- | ----- | --- | ------- | ---- | ---- | ------ | ---- | ------ | ----- | ------- | ----- | -------- | --- |
| ❖   | Yêu   |       | cầu  | được  |     | viết    | theo |      | chuẩn, |      |        | tương | tự      | ngôn  | ngữ      | lập |
|     | trình |       | hoặc | công  |     | thức    |      | toán | học.   |      |        |       |         |       |          |     |
|     | ▪     | Mô    | tả   | chính |     | xác     | rõ   | ràng |        | yêu  | cầu    | và    | kiểm    | chứng | tự động, |     |
|     |       | nhưng |      | phức  |     | tạp khó |      | diễn |        | đạt  | và hạn |       | chế khi | viết  | yêu cầu. |     |
❖
|     | Các |     | viết  | này | phù    | hợp     |     | với                  |     | một | số  | yêu | cầu, | ví dụ | yêu | cầu |
| --- | --- | --- | ----- | --- | ------ | ------- | --- | -------------------- | --- | --- | --- | --- | ---- | ----- | --- | --- |
|     | cho | hệ  | thống |     | nhúng. |         |     |                      |     |     |     |     |      |       |     |     |
| →   | Khó |     | hiểu, | khó |        | sử dụng |     |                      |     |     |     |     |      |       |     |     |
|     |     |     |       |     |        |         |     | Software Engineering |     |     |     |     |      |       |     | 55  |
tkhuong@dthu.edu.vn

|     |     | Đặc   |      | tả   |       | dùng |         | mô    | hình      |     |         |       |         |
| --- | --- | ----- | ---- | ---- | ----- | ---- | ------- | ----- | --------- | --- | ------- | ----- | ------- |
| ❖   | Yêu |       | cầu  | được |       | thể  | hiện    | dưới  | dạng      | ký  | hiệu    | hình  | vẽ, các |
|     | quy | tắc   | biểu |      | diễn, |      | các     | bước  | xây dựng  |     | và giải | thích |         |
| ❖   | Dễ  | hiểu, |      | ngắn |       | gọn, | súc     | tích  |           |     |         |       |         |
| ❖   | Ví  | dụ:   |      |      |       |      |         |       |           |     |         |       |         |
|     | ▪   | Mô    | hình |      | luồng |      | dữ liệu | DFD   |           |     |         |       |         |
|     | ▪   | Mô    | hình |      | thực  |      | thể kết | hợp   | ERD       |     |         |       |         |
|     | ▪   | Mô    | hình |      | phân  |      | tích    | hướng | đối tượng |     | UML     |       |         |
Software Engineering 56
tkhuong@dthu.edu.vn

|      | Ngôn      | ngữ     | mô  | hình             | – Ví               | dụ         |      |
| ---- | --------- | ------- | --- | ---------------- | ------------------ | ---------- | ---- |
| ❖ Sơ | đồ luồng  | dữ liệu | DFD |                  |                    |            |      |
|      | Giáo viên |         |     |                  |                    |            |      |
|      |           |         |     | Luồng            | dữ liệu            |            |      |
|      |           |         |     | D1:              | các hệ số          | a,b,c của  | tam  |
|      | D1        | D2      |     | thức bậc         | 2 P(x)=ax2+bx+c=0  |            |      |
|      |           |         |     | (a khác          | 0)                 |            |      |
|      |           |         |     | D2:              | Nghiệm             | của phương |      |
|      |           |         |     | trình P(x)=0 với |                    | 2 ký số    | thập |
Giải phương
phân
|     | trình bậc | 2   |     |     |     |     |     |
| --- | --------- | --- | --- | --- | --- | --- | --- |
Software Engineering 57
tkhuong@dthu.edu.vn

NỘI DUNG
| 1   | YC CHỨC |     | NĂNG    | &   | YC PHI | CHỨC | NĂNG |
| --- | ------- | --- | ------- | --- | ------ | ---- | ---- |
|     | ĐẶC     | TẢ  | YÊU CẦU |     |        |      |      |
2
| 33  | QUY      | TRÌNH | CÔNG |      | NGHỆ | YÊU CẦU |     |
| --- | -------- | ----- | ---- | ---- | ---- | ------- | --- |
| 44  | THU      | THẬP  | VÀ   | PHÂN | TÍCH | YÊU     | CẦU |
| 5   | THẨM     | ĐỊNH  | YÊU  |      | CẦU  |         |     |
| 6   | QUẢN     | TRỊ   | YÊU  | CẦU  |      |         |     |
| 7   | TÀI LIỆU |       | YÊU  | CẦU  | PM   |         |     |
58
tkhuong@dthu.edu.vn

3. QUY TRÌNH CÔNG NGHỆ YC (1) (nhắc lại)
| ❖ Khái | niệm | công | nghệ | yêu cầu |
| ------ | ---- | ---- | ---- | ------- |
| ❖ Hoạt | động | phân | tích | yêu cầu |
Software Engineering 59
tkhuong@dthu.edu.vn

|     | 3. QUY TRÌNH CÔNG NGHỆ YC (2) (nhắc |      |      |      |      |             |       |                      |     |          |        |     |      |      | lại) |
| --- | ----------------------------------- | ---- | ---- | ---- | ---- | ----------- | ----- | -------------------- | --- | -------- | ------ | --- | ---- | ---- | ---- |
| ❖   | Khái                                | niệm |      | công |      | nghệ        |       | yêu                  |     | cầu      |        |     |      |      |      |
|     | ▪ Requirements                      |      |      |      |      | engineering |       |                      |     | (RE)     |        |     |      |      |      |
|     | ▪ Tập                               |      | hợp  | các  |      | tác         | vụ    | và                   | kỹ  | thuật    | để dẫn |     | đến  | việc | hiểu |
|     | rõ                                  | các  | yêu  |      | cầu  | được        |       | gọi                  |     | là công  | nghệ   | yêu |      | cầu. |      |
|     | ▪ Đứng                              |      | ở    | góc  |      | độ          | quy   | trình                |     | phần     | mềm,   |     | công | nghệ | yêu  |
|     | cầu                                 | là   | hoạt |      | động |             | chính |                      | bắt | đầu      | trong  |     | suốt | hoạt | động |
|     | giao                                |      | tiếp | và   | tiếp |             | tục   | trong                |     | các hoạt | động   |     | mô   | hình | hóa. |
|     |                                     |      |      |      |      |             |       | Software Engineering |     |          |        |     |      |      | 60   |
tkhuong@dthu.edu.vn

3. QUY TRÌNH CÔNG NGHỆ YC (3) (nhắc lại)
| ❖   | Các   | hoạt   |      | động  |     | phân             |                  | tích yêu   | cầu? |         |               |       |     |
| --- | ----- | ------ | ---- | ----- | --- | ---------------- | ---------------- | ---------- | ---- | ------- | ------------- | ----- | --- |
|     | ▪     | Nghiên |      | cứu   |     | khả              | thi(Feasibility  |            |      | study); |               |       |     |
|     | ▪     | Thu    | thập |       | yêu | cầu(Requirements |                  |            |      |         | elicitation); |       |     |
|     | ▪     | Phân   | tích |       | yêu | cầu(Requirements |                  |            |      |         | analysis);    |       |     |
|     | ▪     | Thẩm   |      | định  |     | yêu              | cầu(Requirements |            |      |         | validation);  |       |     |
|     | ▪     | Quản   |      | trị   | yêu | cầu(Requirements |                  |            |      |         | management).  |       |     |
|     | Thực  |        | tế,  | RE    | là  | một              | hoạt             | động       | có   | tính    | lặp lại       | trong | đó  |
|     | những |        | quy  | trình |     | này              | đan              | xen nhau!! |      |         |               |       |     |
Software Engineering 61
tkhuong@dthu.edu.vn

3. QUY TRÌNH CÔNG NGHỆ YC (4) (nhắc lại)
Software Engineering 62
tkhuong@dthu.edu.vn

|     |     | Nghiên |        |        |       | cứu    |       | khả                  |      | thi    |       |     |        |        |      |       |       |
| --- | --- | ------ | ------ | ------ | ----- | ------ | ----- | -------------------- | ---- | ------ | ----- | --- | ------ | ------ | ---- | ----- | ----- |
| ❖   | Mục |        | tiêu   | của    |       | nghiên |       | cứu                  |      | khả    |       | thi | là     | đi     | đến  | kết   | luận: |
|     | Có  |        | nên    | phát   |       | triển  | hệ    | thống                |      |        | hay   |     | không? |        |      |       |       |
| ❖   | Một |        | nghiên |        | cứu   |        | ngắn, |                      | tập  | trung, |       |     | nhằm   |        | kiểm | tra   | xem   |
|     | ▪   | Hệ     | thống  |        | có    | đóng   |       | góp                  | cho  |        | các   |     | mục    | tiêu   | của  | tổ    | chức  |
|     |     | hay    |        | không? |       |        |       |                      |      |        |       |     |        |        |      |       |       |
|     | ▪   | Hệ     | thống  |        | có    | thể    | được  |                      | phát |        | triển |     | bằng   |        | công | nghệ  | hiện  |
|     |     | hành   |        | và     | trong | phạm   |       | vi                   | ngân |        | sách  |     | hay    | không? |      |       |       |
|     | ▪   | Hệ     | thống  |        | có    | thể    | được  |                      | tích |        | hợp   |     | với    | các    | hệ   | thống | khác  |
|     |     | đang   |        | được   |       | sử     | dụng  | hay                  |      | không? |       |     |        |        |      |       |       |
|     |     |        |        |        |       |        |       | Software Engineering |      |        |       |     |        |        |      |       | 64    |
tkhuong@dthu.edu.vn

|       | Câu | hỏi  | ôn  | tập    |     |     |      |     |          |
| ----- | --- | ---- | --- | ------ | --- | --- | ---- | --- | -------- |
| ❖ Yêu | cầu | phần | mềm | là gì? | Có  | mấy | loại | yêu | cầu phần |
mềm?
| ❖ Yêu    | cầu | chức | năng? | Yêu    | cầu  | phi | chức | năng? |        |
| -------- | --- | ---- | ----- | ------ | ---- | --- | ---- | ----- | ------ |
| ❖ Phương |     | pháp | mô    | tả tài | liệu | yêu | cầu  | (hồ   | sơ yêu |
cầu)?
| ❖ Các | hoạt | động | trong | quy | trình | công | nghệ | yêu | cầu? |
| ----- | ---- | ---- | ----- | --- | ----- | ---- | ---- | --- | ---- |
Software Engineering 66
tkhuong@dthu.edu.vn

NỘI DUNG
| 1   | YC CHỨC |     | NĂNG    | &   | YC PHI | CHỨC | NĂNG |
| --- | ------- | --- | ------- | --- | ------ | ---- | ---- |
|     | ĐẶC     | TẢ  | YÊU CẦU |     |        |      |      |
2
| 33  | QUY      | TRÌNH | CÔNG |      | NGHỆ | YÊU CẦU |     |
| --- | -------- | ----- | ---- | ---- | ---- | ------- | --- |
| 44  | THU      | THẬP  | VÀ   | PHÂN | TÍCH | YÊU     | CẦU |
| 5   | THẨM     | ĐỊNH  | YÊU  |      | CẦU  |         |     |
| 6   | QUẢN     | TRỊ   | YÊU  | CẦU  |      |         |     |
| 7   | TÀI LIỆU |       | YÊU  | CẦU  | PM   |         |     |
67
tkhuong@dthu.edu.vn

4. THU THẬP VÀ PHÂN TÍCH YC
| ❖ Các  | vấn  | đề khó | khăn  | thu thập | yêu cầu |
| ------ | ---- | ------ | ----- | -------- | ------- |
| ❖ Hoạt | động | quy    | trình | thu thập | yêu cầu |
| ❖ Lập  | danh | sách   | các   | yêu cầu  |         |
Software Engineering 68
tkhuong@dthu.edu.vn

THU THẬP YÊU CẦU
Khách hàng
Tôi muốn
….
Giải
thích về
…. Phân tích viên
Software Engineering 69
tkhuong@dthu.edu.vn

|     |       | Thu thập |       |     |        | yêu  |       | cầu |     |        |       |      |     |       |
| --- | ----- | -------- | ----- | --- | ------ | ---- | ----- | --- | --- | ------ | ----- | ---- | --- | ----- |
| ❖   | Quá   |          | trình | thu | thập   |      | yêu   | cầu | quá | quá    | trình | phối | hợp | giữa  |
|     | khách |          | hàng  |     | (người |      | dùng) |     | và  | chuyên | viên  | tin  | học | (phân |
|     | tích  | viên)    |       | để  | cùng   | hiểu |       | yêu | cầu | như    | nhau. |      |     |       |
| ❖   | Khách |          | hàng: |     |        |      |       |     |     |        |       |      |     |       |
|     | ▪     | Đưa      | ra    | các | yêu    | cầu; |       |     |     |        |       |      |     |       |
▪ Giải thích/ trình bày chi tiết về các nghiệp vụ có liên quan.
| ❖   | Chuyên |     |      | viên | tin học:  |       |      |      |        |     |      |     |     |     |
| --- | ------ | --- | ---- | ---- | --------- | ----- | ---- | ---- | ------ | --- | ---- | --- | --- | --- |
|     | ▪      | Tư  | vấn  | sự   | cần       | thiết | thực |      | sự của | yêu | cầu; |     |     |     |
|     | ▪      | Tìm | hiểu |      | về nghiệp |       | vụ   | liên | quan.  |     |      |     |     |     |
Software Engineering 70
tkhuong@dthu.edu.vn

|     |       | 4.1 Các |      |     |       | vấn | đề      | khó  |     | khăn |     |       | thu | thập  |     | yc    |
| --- | ----- | ------- | ---- | --- | ----- | --- | ------- | ---- | --- | ---- | --- | ----- | --- | ----- | --- | ----- |
| ❖   | Khách |         | hàng |     | không |     | biết họ | thật | sự  | cần  |     | gì;   |     |       |     |       |
| ❖   | Khách |         | hàng |     | diễn  | đạt | các     | yêu  | cầu | bằng |     | những |     | thuật | ngữ | riêng |
|     | của   | họ;     |      |     |       |     |         |      |     |      |     |       |     |       |     |       |
❖
|     | Các | khách |     | hàng |     | khác | nhau | có  | các |     | yêu | cầu | xung | đột | nhau; |     |
| --- | --- | ----- | --- | ---- | --- | ---- | ---- | --- | --- | --- | --- | --- | ---- | --- | ----- | --- |
❖ Các nhân tố về mặt tổ chức và chính trị có thể ảnh hưởng đến
|     | yêu | cầu  | hệ     | thống; |       |       |        |      |      |     |       |     |      |      |     |     |
| --- | --- | ---- | ------ | ------ | ----- | ----- | ------ | ---- | ---- | --- | ----- | --- | ---- | ---- | --- | --- |
| ❖   | Các | yêu  | cầu    |        | thay  | đổi   | trong  | suốt |      | quá | trình |     | phân | tích |     |     |
|     | ▪   | Phát | sinh   |        | các   | khách | hàng   | mới  |      |     |       |     |      |      |     |     |
|     | ▪   | Môi  | trường |        | doanh |       | nghiệp | thay | đổi. |     |       |     |      |      |     |     |
Software Engineering 71
tkhuong@dthu.edu.vn

|      | 4.2 Hoạt |           | động     | quy | trình | thu         | thập | yc (1) |
| ---- | -------- | --------- | -------- | --- | ----- | ----------- | ---- | ------ |
| ❖ Mô | hình     | xoắn      | ốc trong | quy | trình | thu thập    | yêu  | cầu    |
|      |          |           |          |     | Đánh  | giá độ ưu   | tiên |        |
|      |          | Phân loại | và tổ    |     |       |             |      |        |
|      |          |           |          |     | và    | thương thảo |      |        |
chức
Prioritization and
Classification and
negotiation
organization
|     |     | Phát hiện | mới |     | Viết          | tài liệu |     |     |
| --- | --- | --------- | --- | --- | ------------- | -------- | --- | --- |
|     |     | Discovery |     |     | Documentation |          |     |     |
Software Engineering 72
tkhuong@dthu.edu.vn

|     |      | 4.2 Hoạt |     |     |     | động |     | quy | trình |     | thu |     | thập | yc (2) |
| --- | ---- | -------- | --- | --- | --- | ---- | --- | --- | ----- | --- | --- | --- | ---- | ------ |
| ❖   | Phát | hiện     |     | yêu | cầu |      |     |     |       |     |     |     |      |        |
▪
|     |      | Tương |     | tác | với | khách | hàng | để  | tìm ra | yêu | cầu | của | họ. |     |
| --- | ---- | ----- | --- | --- | --- | ----- | ---- | --- | ------ | --- | --- | --- | --- | --- |
| ❖   | Phân | loại  |     | và  | tổ  | chức  |      |     |        |     |     |     |     |     |
▪ Phân nhóm các yêu cầu có liên quan đến nhau và tổ chức chúng
|     |     | thành | các |     | cụm | có quan |     | hệ gắn | kết | với | nhau. |     |     |     |
| --- | --- | ----- | --- | --- | --- | ------- | --- | ------ | --- | --- | ----- | --- | --- | --- |
❖ Đặt thứ tự ưu tiên và giải quyết mâu thuẫn giữa các yêu cầu
|     | ▪             | Xếp     | thứ | tự    |     | ưu tiên |     | cho các | yêu  | cầu | và  | giải | quyết | các xung |
| --- | ------------- | ------- | --- | ----- | --- | ------- | --- | ------- | ---- | --- | --- | ---- | ----- | -------- |
|     |               | đột/mâu |     | thuẫn |     | giữa    | các | yêu     | cầu. |     |     |      |       |          |
| ❖   | Documentation |         |     |       |     | – Viết  | tài | liệu    |      |     |     |      |       |          |
▪ Ghi lại các yêu cầu làm tài liệu đầu vào cho vòng xoắn tiếp theo.
tkhuong@dthu.edu.vn

| Phát |     | hiện | yêu | cầu | (1) |     |     |     |
| ---- | --- | ---- | --- | --- | --- | --- | --- | --- |
❖
| Quy | trình | thu thập | thông                | tin   | về hệ thống | đề xuất | và   | các |
| --- | ----- | -------- | -------------------- | ----- | ----------- | ------- | ---- | --- |
| hệ  | thống | sẵn có,  | gạn lọc              | ra    | các yêu cầu | người   | dùng | và  |
| yêu | cầu   | hệ thống | từ các               | thông | tin này.    |         |      |     |
|     |       |          | Software Engineering |       |             |         |      | 74  |
tkhuong@dthu.edu.vn

|     |       | Thu thập      |        |       |       |       | yêu   |        |                      | cầu   |        | từ     |           | đâu? (2) |       |       |     |
| --- | ----- | ------------- | ------ | ----- | ----- | ----- | ----- | ------ | -------------------- | ----- | ------ | ------ | --------- | -------- | ----- | ----- | --- |
| ❖   | Làm   |               | việc   | với   | khách |       |       | hàng   |                      | để    | tìm    |        | hiểu      | thông    | tin   | về    |     |
|     | ▪     | Miền          | ứng    |       | dụng, |       |       |        |                      |       |        |        |           |          |       |       |     |
|     | ▪     | Các           | dịch   |       | vụ    | mà    | hệ    | thống  |                      | cần   |        | cung   | cấp       | và       |       |       |     |
|     | ▪     | Các           | ràng   |       | buộc  |       | về    | vận    | hành                 |       | hệ     | thống. |           |          |       |       |     |
| ❖   | Những |               | người  |       |       | có    | thể   | cần    |                      | tham  |        | gia:   | khách     |          | hàng, | người | sử  |
|     | dụng, |               | lập    | trình |       | viên, |       | chuyên |                      |       | gia    | kĩ     | thuật,... |          |       |       |     |
|     | ▪     | stakeholders. |        |       |       |       |       |        |                      |       |        |        |           |          |       |       |     |
| ❖   | Tài   | liệu          | về     | hoạt  |       | động  |       | doanh  |                      |       | nghiệp |        |           |          |       |       |     |
| ❖   | Đặc   |               | tả của | các   |       | hệ    | thống |        |                      | tương |        | tự.    |           |          |       |       |     |
|     |       |               |        |       |       |       |       |        | Software Engineering |       |        |        |           |          |       |       | 75  |
tkhuong@dthu.edu.vn

|       | Các      | phương      |          |          | pháp                 | thu   | thập      | và phân |            | tích | yc  |
| ----- | -------- | ----------- | -------- | -------- | -------------------- | ----- | --------- | ------- | ---------- | ---- | --- |
| ❖ Lấy | yêu      |             | cầu      |          |                      |       |           |         |            |      |     |
|       | ▪ Phỏng  |             | vấn      |          |                      |       |           |         |            |      |     |
|       | ▪ Quan   |             | sát      |          |                      |       |           |         |            |      |     |
|       | ▪ Điều   | tra         | bằng     | bảng     | câu                  | hỏi   |           |         |            |      |     |
|       | ▪ Nghiên |             | cứu      | tài liệu |                      |       |           |         |            |      |     |
|       | ▪ Joint  | Application |          |          | Design               | – JAD |           |         |            |      |     |
|       | ▪ Làm    | bản         | mẫu      |          |                      |       |           |         |            |      |     |
| ❖ Đặc |          | tả yêu      | cầu      |          |                      |       |           |         |            |      |     |
|       | ▪ Danh   |             | mục các  | khái     | niệm                 |       |           |         |            |      |     |
|       | ▪ Mô     | hình        | hóa/Dùng |          | ký pháp              | đồ    | hoạ (kịch | bản     | - usecase) |      |     |
|       |          |             |          |          | Software Engineering |       |           |         |            |      | 78  |
tkhuong@dthu.edu.vn

|     |     | 4.3 Lập |     |      |        | danh  |      | sách                 |     | yêu |      | cầu  |     |     |     |      |
| --- | --- | ------- | --- | ---- | ------ | ----- | ---- | -------------------- | --- | --- | ---- | ---- | --- | --- | --- | ---- |
| ❖   | Mục | tiêu:   |     |      | xác    | định  |      | rõ các               |     | bộ  | phận | hỗ   | trợ | tin | học | hóa, |
|     | các | nghiệp  |     |      | vụ     | sẽ    | được |                      | hỗ  | trợ | và   | mức  | độ  | hỗ  | trợ |      |
| ❖   | Kết | quả:    |     | Danh |        | sách  |      | các                  |     | yêu | cầu  | phần |     | mềm | với | các  |
|     | yêu | cầu:    |     |      |        |       |      |                      |     |     |      |      |     |     |     |      |
|     | ▪   | Yêu     | cầu |      | nghiệp |       | vụ   |                      |     |     |      |      |     |     |     |      |
|     | ▪   | Yêu     | cầu |      | chất   | lượng |      |                      |     |     |      |      |     |     |     |      |
|     | ▪   | Yêu     | cầu |      | hệ     | thống |      |                      |     |     |      |      |     |     |     |      |
|     |     |         |     |      |        |       |      | Software Engineering |     |     |      |      |     |     |     | 79   |
tkhuong@dthu.edu.vn

| Yêu    | cầu  | nghiệp    | vụ  |
| ------ | ---- | --------- | --- |
| ❖ Công | việc |           |     |
| ❖ Biểu | mẫu  |           |     |
| ❖ Quy  | định |           |     |
| ❖ Công | thức |           |     |
| ❖ Cách | thức | tiến hành |     |
Software Engineering 80
tkhuong@dthu.edu.vn

| Yêu | cầu | chất | lượng |
| --- | --- | ---- | ----- |
❖
| Tính   | tiến  | hóa   |     |
| ------ | ----- | ----- | --- |
| ❖ Tính | hiệu  | quả   |     |
| ❖ Tính | dễ sử | dụng  |     |
| ❖ Tính | tương | thích |     |
Software Engineering 81
tkhuong@dthu.edu.vn

| Yêu    | cầu | hệ   | thống |
| ------ | --- | ---- | ----- |
| ❖ Tính | an  | toàn |       |
| ❖ Tính | bảo | mật  |       |
Software Engineering 82
tkhuong@dthu.edu.vn

NỘI DUNG
| 1   | YC CHỨC |     | NĂNG    | &   | YC PHI | CHỨC | NĂNG |
| --- | ------- | --- | ------- | --- | ------ | ---- | ---- |
|     | ĐẶC     | TẢ  | YÊU CẦU |     |        |      |      |
2
| 33  | QUY      | TRÌNH | CÔNG |      | NGHỆ | YÊU CẦU |     |
| --- | -------- | ----- | ---- | ---- | ---- | ------- | --- |
| 44  | THU      | THẬP  | VÀ   | PHÂN | TÍCH | YÊU     | CẦU |
| 5   | THẨM     | ĐỊNH  | YÊU  |      | CẦU  |         |     |
| 6   | QUẢN     | TRỊ   | YÊU  | CẦU  |      |         |     |
| 7   | TÀI LIỆU |       | YÊU  | CẦU  | PM   |         |     |
83
tkhuong@dthu.edu.vn

5. THẨM ĐỊNH YÊU CẦU
| ❖ Thẩm | định     | yêu           | cầu là chứng    | tỏ rằng | các  | yêu      | cầu định |
| ------ | -------- | ------------- | --------------- | ------- | ---- | -------- | -------- |
| nghĩa  | được     | hệ thống      | mà khách        | hàng    | thực | sự muốn. |          |
| ❖ Tiêu | chí thẩm | định          |                 |         |      |          |          |
| ▪ Hiệu | lực      | – Validity    |                 |         |      |          |          |
| ▪ Nhất | quán     | – Consistency |                 |         |      |          |          |
| ▪ Đầy  | đủ -     | completeness  |                 |         |      |          |          |
| ▪ Thực | tế       | - Realism     |                 |         |      |          |          |
| ▪ Kiểm | định     | được          | - Verifiability |         |      |          |          |
Software Engineering 84
tkhuong@dthu.edu.vn

5. THẨM ĐỊNH YÊU CẦU (2)
❖
| Phương |       |           | pháp  | thẩm  |            | định |                      | yêu         | cầu   |     |          |       |        |         |      |
| ------ | ----- | --------- | ----- | ----- | ---------- | ---- | -------------------- | ----------- | ----- | --- | -------- | ----- | ------ | ------- | ---- |
| ▪      | Xem   | xét       | lại   | yêu   | cầu        |      | (Requirements        |             |       |     | reviews) |       |        |         |      |
|        | −     | Phân      | tích  |       | một        | cách | có                   | hệ          | thống | các | yêu      | cầu   | (không |         | dùng |
|        |       | công      | cụ    | tự    | động);     |      | lấy                  | ý           | kiến  | của | khách    | hàng; |        | tiến    | hành |
|        |       | thường    |       | xuyên |            |      |                      |             |       |     |          |       |        |         |      |
| ▪      | Phiên |           | bản   | thử   | nghiệm     |      | (Prototyping)        |             |       |     |          |       |        |         |      |
|        | −     | Sử        | dụng  | một   | mô         | hình |                      | chạy        | được  |     | của hệ   | thống |        | để kiểm | tra  |
|        |       | các       | yêu   | cầu.  |            |      |                      |             |       |     |          |       |        |         |      |
| ▪      | Sinh  | test-case |       |       | (test-case |      |                      | generation) |       |     |          |       |        |         |      |
|        | −     | Phát      | triển |       | các        | test | cho                  | các         | yêu   | cầu | để       | kiểm  | tra    | khả     | năng |
|        |       | test      | được  | hay   | không.     |      |                      |             |       |     |          |       |        |         |      |
|        |       |           |       |       |            |      | Software Engineering |             |       |     |          |       |        |         | 85   |
tkhuong@dthu.edu.vn

6. QUẢN TRỊ YÊU CẦU (1)
|     |     |        | Yêu  | cầu   | phần |        | mềm  | luôn     | luôn | thay | đổi! |
| --- | --- | ------ | ---- | ----- | ---- | ------ | ---- | -------- | ---- | ---- | ---- |
| ❖   | Môi | trường |      | doanh |      | nghiệp | và   | kĩ thuật | thay | đổi  |      |
|     | ▪   | Phần   | cứng | mới   |      | → giao | diện | mới.     |      |      |      |
▪ Luật thay đổi, nhu cầu doanh nghiệp thay đổi → thay đổi chức
năng
| ❖   | Khách |      | hàng, | người |      | sử  | dụng | thay đổi |     |     |     |
| --- | ----- | ---- | ----- | ----- | ---- | --- | ---- | -------- | --- | --- | --- |
|     | ▪     | Thay | đổi   | chức  | năng |     |      |          |     |     |     |
❖ Xung đột giữa các yêu cầu mới nảy sinh, và giữa yêu cầu mới
|     | với | yêu | cầu | cũ  |     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
Software Engineering 86
tkhuong@dthu.edu.vn

|     |     | Quản  |       | lý     | yêu   |      | cầu                  |       |      |              |         |        |     |       |       |      |          |
| --- | --- | ----- | ----- | ------ | ----- | ---- | -------------------- | ----- | ---- | ------------ | ------- | ------ | --- | ----- | ----- | ---- | -------- |
| ❖   | Để  | quản  | lý    | yêu    | cầu,  |      | cần                  | xác   | định |              |         |        |     |       |       |      |          |
|     | ▪   | Định  | danh  |        | yêu   | cầu: | Mỗi                  | yêu   | cầu  |              | có định | danh   |     | riêng |       | để   | tiện     |
|     |     | cho   | việc  | tham   | chiếu |      | giữa                 | các   |      | yêu          | cầu     | và lần |     | vết   |       |      |          |
|     | ▪   | Quy   | trình |        | quản  | lý   | thay                 | đổi:  |      | các          | hoạt    | động   |     | đánh  |       | giá  | ảnh      |
|     |     | hưởng |       | và chi | phí   | của  | thay                 |       | đổi  |              |         |        |     |       |       |      |          |
|     | ▪   | Chính |       | sách   | lần   | vết: | cách                 |       | ghi  | lại          | và lưu  |        | trữ | quan  |       | hệ   | giữa     |
|     |     | các   | yêu   | cầu    | và    | giữa | mỗi                  |       | yêu  | cầu          | với     | thiết  |     | kế    | tương |      | ứng      |
|     |     | với   | nó    |        |       |      |                      |       |      |              |         |        |     |       |       |      |          |
|     | ▪   | Công  | cụ    | hỗ     | trợ:  | hỗ   | trợ                  | thực  |      | hiện         | các     | công   |     | việc  |       | trên | một      |
|     |     | cách  | có    | hiệu   | quả.  |      | CASE                 | tool, |      | spreadsheet, |         |        | cơ  | sở    | dữ    |      | liệu.... |
|     |     |       |       |        |       |      | Software Engineering |       |      |              |         |        |     |       |       |      | 87       |
tkhuong@dthu.edu.vn

Quản lý thay đổi
Xác định
vấn đề
| Phân | tích vấn | đề,  | Phân | tích thay   | đổi | Thực hiện  |
| ---- | -------- | ---- | ---- | ----------- | --- | ---------- |
| đặc  | tả thay  | đổi  |      | &           |     | thay đổi   |
|      |          |      | đánh | giá chi phí |     |            |
Yêu cầu đã
chỉnh sửa
tkhuong@dthu.edu.vn

|       | Đặt   | vấn |     | đề   |     |                      |     |     |          |     |     |          |     |
| ----- | ----- | --- | --- | ---- | --- | -------------------- | --- | --- | -------- | --- | --- | -------- | --- |
| ❖ Sau | khi   | đã  | xác | định |     | yêu                  | cầu |     | hệ thống |     | và  | yêu      | cầu |
| của   | người |     | sử  | dụng | hệ  | thống                |     | thì | tiếp     | tục | làm | gì?      |     |
| ❖ Cấu | trúc  | của |     | một  | tài | liệu                 | đặc |     | tả yêu   |     | cầu | hệ thống |     |
| gồm   | những |     | nội | dung |     | gì?                  |     |     |          |     |     |          |     |
|       |       |     |     |      |     | Software Engineering |     |     |          |     |     |          | 90  |
tkhuong@dthu.edu.vn

7. CÁCH VIẾT TÀI LIỆU YÊU CẦU
❖
|     | Tài    | liệu  | yêu      |      | cầu    | phần   |                      | mềm   |       | là yêu  |      | cầu   | chính |      | thức  | về   |
| --- | ------ | ----- | -------- | ---- | ------ | ------ | -------------------- | ----- | ----- | ------- | ---- | ----- | ----- | ---- | ----- | ---- |
|     | những  |       | gì mà    |      | đội    | phát   | triển                |       | hệ    | thống   | phải |       | cài   | đặt. |       |      |
| ❖   | Nên    | bao   | gồm      |      | cả     | định   |                      | nghĩa |       | yêu cầu |      | người |       | dùng | và    | đặc  |
|     | tả yêu |       | cầu      | hệ   | thống. |        |                      |       |       |         |      |       |       |      |       |      |
| ❖   | Đây    | không |          | phải |        | là tài | liệu                 |       | thiết | kế,     | chỉ  | nên   |       | định | nghĩa | về   |
|     | cái    | gì    | hệ thống |      |        | sẽ hỗ  |                      | trợ,  | chứ   | không   |      | đi    | vào   | chi  | tiết  | việc |
|     | mô     | tả    | cài đặt  |      | như    | thế    | nào.                 |       |       |         |      |       |       |      |       |      |
|     |        |       |          |      |        |        | Software Engineering |       |       |         |      |       |       |      |       | 91   |
tkhuong@dthu.edu.vn

7. CÁCH VIẾT TÀI LIỆU YÊU CẦU
| ❖ Tài | liệu | đặc tả   | yêu cầu dựa | theo | chuẩn | IEEE |
| ----- | ---- | -------- | ----------- | ---- | ----- | ---- |
| 1.    | Giới | thiệu    |             |      |       |      |
| 2.    | Mô   | tả chung |             |      |       |      |
| 3.    | Yêu  | cầu chi  | tiết        |      |       |      |
| 4.    | Phụ  | lục (nếu | có)         |      |       |      |
Software Engineering 93
tkhuong@dthu.edu.vn

|      | Tài  | liệu      | đặc      | tả yc | chuẩn   | IEEE (1) |
| ---- | ---- | --------- | -------- | ----- | ------- | -------- |
| 1.   | Giới | thiệu     |          |       |         |          |
| 1.1. | Mục  | đích      |          |       |         |          |
| 1.2. | Phạm | vi        |          |       |         |          |
| 1.3. | Định | nghĩa     | (thuật   | ngữ,  | từ viết | tắt)     |
| 1.4. | Tài  | liệu tham | khảo     |       |         |          |
| 1.5. | Mô   | tả cấu    | trúc tài | liệu  |         |          |
Software Engineering 94
tkhuong@dthu.edu.vn

|      | Tài   | liệu  | đặc   | tả yc    | chuẩn | IEEE (2) |
| ---- | ----- | ----- | ----- | -------- | ----- | -------- |
| 2.   | Mô tả | chung |       |          |       |          |
| 2.1. | Tổng  | quan  | về    | sản phẩm |       |          |
| 2.2. | Chức  | năng  | sản   | phẩm     |       |          |
| 2.3. | Đối   | tượng | người | dùng     |       |          |
| 2.4. | Ràng  | buộc  | tổng  | thể      |       |          |
| 2.5. | Giả   | thiết | và sự | lệ thuộc |       |          |
Software Engineering 95
tkhuong@dthu.edu.vn

|          | Tài | liệu |       | đặc  |      | tả   | yc chuẩn | IEEE (2) |
| -------- | --- | ---- | ----- | ---- | ---- | ---- | -------- | -------- |
| 3.       | Yêu | cầu  | chi   |      | tiết | (1)  |          |          |
| 3.1.     | Yêu | cầu  | chức  |      | năng |      |          |          |
| 3.1.1.   | Yêu | cầu  |       | chức |      | năng | 1        |          |
| 3.1.1.1. |     | Giới | thiệu |      |      |      |          |          |
| 3.1.1.2. |     | Dữ   | liệu  | vào  |      |      |          |          |
| 3.1.1.3. |     | Xử   | lý    |      |      |      |          |          |
| 3.1.1.4. |     | Kết  | quả   |      |      |      |          |          |
| 3.1.2.   | Yêu | cầu  |       | chức |      | năng | 2        |          |
………………
Software Engineering 96
tkhuong@dthu.edu.vn

| Tài    |       | liệu | đặc    |       | tả yc | chuẩn |      | IEEE (2) |      |
| ------ | ----- | ---- | ------ | ----- | ----- | ----- | ---- | -------- | ---- |
| 3. Yêu |       | cầu  | chi    | tiết  | (2)   |       |      |          |      |
| 3.2.   | Yêu   | cầu  | giao   | diện  | ngoài |       |      |          |      |
| 3.2.1. | Giao  | diện | người  |       | dùng  |       |      |          |      |
| 3.2.2. | Giao  | diện | phần   |       | cứng  |       |      |          |      |
| 3.2.3. | Giao  | diện | phần   |       | mềm   |       |      |          |      |
| 3.2.4. | Giao  | diện | truyền |       | thông |       |      |          |      |
| 3.3.   | Yêu   | cầu  | hiệu   | suất  |       |       |      |          |      |
| 3.4.   | Ràng  | buộc |        | thiết | kế    |       |      |          |      |
| 3.5.   | Thuộc | tính | (tính  |       | bảo   | mật,  | tính | bảo      | trì) |
| 3.6.   | Các   | yêu  | cầu    | khác  |       |       |      |          |      |
| Phụ    | lục   |      |        |       |       |       |      |          |      |
Software Engineering 97
tkhuong@dthu.edu.vn

|          | Câu    |      | hỏi    |      |     |       |       |       |       |      |      |          |      |
| -------- | ------ | ---- | ------ | ---- | --- | ----- | ----- | ----- | ----- | ---- | ---- | -------- | ---- |
| 1) Phân  |        | tích | yêu    | cầu  |     | nghĩa | là    | gì?   |       |      |      |          |      |
| 2) Mục   | tiêu   |      | của    | phân |     | tích  | yêu   | cầu   | là    | gì?  |      |          |      |
| 3) Các   | công   |      | đoạn   |      | của | quy   | trình |       | phân  | tích |      | yêu cầu? |      |
| 4) Những |        | khó  |        | khăn | của |       | phân  | tích  | yêu   |      | cầu? |          |      |
| 5) Có    | những  |      | loại   | yêu  |     | cầu   | nào?  |       |       |      |      |          |      |
| 6) Nêu   | những  |      |        | yêu  | cầu | phi   | chức  |       | năng? |      |      |          |      |
| 7) Nêu   | các    |      | nguyên |      | lý  | của   | phân  |       | tích  | yêu  | cầu? |          |      |
| 8) Các   | phương |      |        | pháp |     | thu   | thập  | thông |       | tin  | cho  | các yêu  | cầu? |
| 9) Đặc   | tả     | yêu  |        | cầu  | cần | có    | những |       | tính  | chất |      | gì?      |      |
Software Engineering 98
tkhuong@dthu.edu.vn

|          | Câu  | hỏi     |      |         |         |      |       |         |      |
| -------- | ---- | ------- | ---- | ------- | ------- | ---- | ----- | ------- | ---- |
| 1) Nội   | dung | thẩm    | định | yêu cầu | là gì?  |      |       |         |      |
| 2) Các   |      | phương  | pháp | mô hình | hóa để  | phân | tích  | yêu cầu | là   |
| những    |      | phương  | pháp | nào?    |         |      |       |         |      |
| 3) Trình |      | bày nội | dung | đặc tả  | yêu cầu | theo | chuẩn | IEEE    | 830- |
1998
| 4) Ai | sẽ  | sử dụng | tài liệu | yêu cầu?             |     |     |     |     |     |
| ----- | --- | ------- | -------- | -------------------- | --- | --- | --- | --- | --- |
|       |     |         |          | Software Engineering |     |     |     |     | 99  |
tkhuong@dthu.edu.vn

BÀI TẬP
| ❖ Hãy | thu thập | và phân | tích | yêu | cầu theo | các đề | tài đã |
| ----- | -------- | ------- | ---- | --- | -------- | ------ | ------ |
chọn
| ▪ Viết | tài liệu | đặc tả | yêu cầu              | theo | chuẩn | IEEE |     |
| ------ | -------- | ------ | -------------------- | ---- | ----- | ---- | --- |
|        |          |        | Software Engineering |      |       |      | 100 |
tkhuong@dthu.edu.vn