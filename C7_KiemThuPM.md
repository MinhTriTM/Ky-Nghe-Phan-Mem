LOGO
Chương 7
KIỂM THỬ
PHẦN MỀM
TRẦN KIM HƯƠNG – KHOA SƯ PHẠM TOÁN TIN
tkhuong@dthu.edu.vn

LOGO
KHOA KỸ THUẬT – CÔNG NGHỆ
Chương 7
KIỂM THỬ
PHẦN MỀM
GV biên soạn: Trần Kim Hương
tkhuong@dthu.edu.vn
Software Engineering
tkhuong@dthu.edu.vn

NỘI DUNG
XÁC MINH & THẨM ĐỊNH
KIỂM
THỬ
RÀ SOÁT PHẦN MỀM
PHẦN
MỀM
KIỂM THỬ PHẦN MỀM
Software Engineering 4
tkhuong@dthu.edu.vn

KIỂM THỬ PHẦN MỀM
| ❖ Kiểm | thử  | là   | nhằm | đánh | giá  |      | chất | lượng    | hoặc | tính   | chấp | nhận  |
| ------ | ---- | ---- | ---- | ---- | ---- | ---- | ---- | -------- | ---- | ------ | ---- | ----- |
| được   | của  | sản  | phẩm |      |      |      |      |          |      |        |      |       |
| ❖ Kiểm | thử  | cũng |      | nhằm | phát | hiện |      | lỗi hoặc | bất  | cứ vấn | đề   | gì về |
| sản    | phẩm |      |      |      |      |      |      |          |      |        |      |       |
❖ Kiểm thử thực hiện mục đích xác minh (Verification) và thẩm
| định | (Validation) |      |     | (V&V) | nhằm                 |     | đảm | bảo | chất | lượng | và  | độ tin |
| ---- | ------------ | ---- | --- | ----- | -------------------- | --- | --- | --- | ---- | ----- | --- | ------ |
| cậy  | của          | phần | mềm |       |                      |     |     |     |      |       |     |        |
|      |              |      |     |       | Software Engineering |     |     |     |      |       |     | 5      |
tkhuong@dthu.edu.vn

KIỂM THỬ PHẦN MỀM
Validation
testing
| Để  | chỉ ra cho | người   | phát    | triển | và khách | hàng | rằng | phần |
| --- | ---------- | ------- | ------- | ----- | -------- | ---- | ---- | ---- |
| mềm | thỏa       | mãn các | yêu cầu | đưa   | ra.      |      |      |      |
Verification
testing
| Để    | chỉ ra các | tình    | huống | trong | đó các | hành | vi của | phần  |
| ----- | ---------- | ------- | ----- | ----- | ------ | ---- | ------ | ----- |
| mềm   | không      | đúng,   | không | như   | mong   | đợi  | hoặc   | không |
| tương | thích      | với đặc | tả    |       |        |      |        |       |
Software Engineering 7
tkhuong@dthu.edu.vn

1. XÁC MINH & THẨM ĐỊNH
❖ Xác minh (Verification)
▪ Kiểm tra xem phần mềm làm ra có đúng đặc tả (yêu cầu, thiết kế)
hay không
| ❖ Thẩm | định (Validation) |      |      |          |            |          |            |            |
| ------ | ----------------- | ---- | ---- | -------- | ---------- | -------- | ---------- | ---------- |
| ▪ Kiểm | tra xem           |      | phần | mềm có   | đáp ứng    | yêu cầu  | người      | dùng không |
| Đây    | là 2              | hoạt | động | cốt yếu  | để đảm     | bảo      | chất lượng |            |
| phần   | mềm,              | diễn | ra   | suốt quá | trình phát | triển!!! |            |            |
Software Engineering 8
tkhuong@dthu.edu.vn

1. XÁC MINH & THẨM ĐỊNH
Software Engineering 9
tkhuong@dthu.edu.vn

|     | Các  |      | hoạt  |        | động     |             | xác  | minh   |       |
| --- | ---- | ---- | ----- | ------ | -------- | ----------- | ---- | ------ | ----- |
| ❖   | Cơ   | sở   | cho   | hoạt   | động     | xác         | minh |        |       |
|     | ▪    | Bản  | đặc   | tả yêu | cầu      |             |      |        |       |
|     | ▪    | Các  | bản   | thiết  | kế       |             |      |        |       |
|     | ▪    | Mã   | nguồn |        |          |             |      |        |       |
| ❖   | Hoạt |      | động  | xác    | minh     |             |      |        |       |
|     | ▪    | Rà   | soát  | (thanh | tra, xét | duyệt, kiểm |      |        | toán) |
|     | ▪    | Kiểm | thử   | (đơn   | vị, tích | hợp, hệ     |      | thống) |       |
Software Engineering 10
tkhuong@dthu.edu.vn

|     | Các  |      | hoạt  |        |       | động     |       |        | thẩm  | định        |        |
| --- | ---- | ---- | ----- | ------ | ----- | -------- | ----- | ------ | ----- | ----------- | ------ |
| ❖   | Cơ   | sở   | cho   | hoạt   |       | động     | thẩm  |        | định  |             |        |
|     | ▪    | Bản  | đặc   | tả     | yêu   |          | cầu   |        |       |             |        |
|     | ▪    | Mã   | nguồn |        |       |          |       |        |       |             |        |
| ❖   | Hoạt |      | động  | thẩm   |       | định     |       |        |       |             |        |
|     | ▪    | Rà   | soát  | (thanh |       | tra, xét |       | duyệt) |       |             |        |
|     | ▪    | Kiểm | toán  |        |       |          |       |        |       |             |        |
|     | ▪    | Kiểm | thử   |        | thẩm  | định     | (chấp |        | nhận) |             |        |
|     | Hai  | hoạt | động  |        | chính |          | của   | thẩm   | định  | và xác minh | là: rà |
|     | soát | và   | kiểm  |        | thử.  |          |       |        |       |             |        |
Software Engineering 11
tkhuong@dthu.edu.vn

| Phân | loại | Xác | minh & Thẩm | định |
| ---- | ---- | --- | ----------- | ---- |
Xác minh (Verification)
Thẩm định (Validation)
| Kiểm | tra (động) |     |     |     |
| ---- | ---------- | --- | --- | --- |
Nghiệm thu Alpha
(Testing)
(Alpha Testing)
| Kiểm | tra (tĩnh) |     |     |     |
| ---- | ---------- | --- | --- | --- |
Nghiệm thu Beta
(Static Verification)
(Beta Testing)
Software Engineering 12
tkhuong@dthu.edu.vn

|     |      | Phân |     | loại |                        | Xác |     | minh (Verification) |     |     |     |     |     |
| --- | ---- | ---- | --- | ---- | ---------------------- | --- | --- | ------------------- | --- | --- | --- | --- | --- |
| ❖   | Kiểm |      | tra | động | (dynamic verification) |     |     |                     |     |     |     |     |     |
▪
|     |       | Kiểm     | tra  | bằng     | vận  | hành, chạy |                    |          | thử sản  | phẩm   |       | phần    | mềm |
| --- | ----- | -------- | ---- | -------- | ---- | ---------- | ------------------ | -------- | -------- | ------ | ----- | ------- | --- |
|     | →kiểm |          | thử  | phần     |      | mềm        | (software testing) |          |          |        |       |         |     |
|     | ▪     | Dựa      | trên | đầu      | vào  | và         | đầu                | ra       |          |        |       |         |     |
|     | ▪     | Ưu điểm: |      |          |      |            |                    |          |          |        |       |         |     |
|     |       | •        | Đơn  | giản, ít | tốn  | chi phí    |                    | (đối     | với phần | mềm    | thông | thường) |     |
|     |       | •        | Kiểm | tra      | được | yêu        | cầu                | phi chức | năng.    |        |       |         |     |
|     | ▪     | Nhược    |      | điểm:    |      |            |                    |          |          |        |       |         |     |
|     |       | •        | Phức | tạp, tốn |      | kém        | (đối               | với phần | mềm      | chuyên |       | dụng)   |     |
|     |       | •        | Phần | mềm      | phải | hoàn       |                    | thành    |          |        |       |         |     |
|     |       | •        | Có   | thể bỏ   | sót  | lỗi.       |                    |          |          |        |       |         |     |
Software Engineering 13
tkhuong@dthu.edu.vn

|     | Phân |       |       | loại  |                       | Xác  |              | minh (Verification) |       |       |          |      |     |
| --- | ---- | ----- | ----- | ----- | --------------------- | ---- | ------------ | ------------------- | ----- | ----- | -------- | ---- | --- |
| ❖   | Kiểm |       | tra   | tĩnh  | (static verification) |      |              |                     |       |       |          |      |     |
|     | ▪    | Kiểm  | tra   | bằng  |                       | xét  | duyệt, rà    |                     | soát  | các   | tài liệu | phần | mềm |
|     | →    | kiểm  | chứng |       | phần                  |      | mềm          |                     |       |       |          |      |     |
|     | ▪    | Dựa   | trên  | xem   |                       | xét  | nội dung bên |                     |       | trong |          |      |     |
|     | ▪    | Ưu    | điểm: |       |                       |      |              |                     |       |       |          |      |     |
|     |      | •     | Phần  | mềm   | không                 |      | cần          | hoàn                | thành |       |          |      |     |
|     |      | •     | Không | cần   | vận                   | hành |              |                     |       |       |          |      |     |
|     |      | •     | Phát  | hiện  | được                  |      | lỗi tiềm     | ẩn                  |       |       |          |      |     |
|     | ▪    | Nhược |       | điểm: |                       |      |              |                     |       |       |          |      |     |
|     |      | •     | Phức  | tạp   |                       |      |              |                     |       |       |          |      |     |
|     |      | •     | Cần   | đội   | ngũ                   | kinh | nghiệm       |                     |       |       |          |      |     |
|     |      | •     | Tốn   | thời  | gian, công            |      | sức.         |                     |       |       |          |      |     |
Software Engineering 14
tkhuong@dthu.edu.vn

| Phân     |        | loại  |                       | thẩm  |      |       | định | (Validation) |
| -------- | ------ | ----- | --------------------- | ----- | ---- | ----- | ---- | ------------ |
| ❖ Nghiệm |        | thu   | Alpha (Alpha Testing) |       |      |       |      |              |
| ▪        | Nghiệm |       | thu                   | có    | giới | hạn   |      |              |
|          | →      | Triển | khai                  | thí   | điểm |       |      |              |
| ▪        | Chọn   | lọc   | đối                   | tượng |      | tham  | gia  |              |
| ▪        | Vận    | hành  | có                    | kiểm  |      | soát. |      |              |
| ❖ Nghiệm |        | thu   | Beta (Beta Testing)   |       |      |       |      |              |
| ▪        | Nghiệm |       | thu                   | không |      | giới  | hạn  |              |
|          | →Triển |       | khai                  | đại   | trà  |       |      |              |
| ▪        | Không  |       | hạn                   | chế   | đối  | tượng | tham | gia          |
| ▪        | Vận    | hành  | tự                    | do.   |      |       |      |              |
Software Engineering 15
tkhuong@dthu.edu.vn

NỘI DUNG
XÁC MINH & THẨM ĐỊNH
KIỂM
THỬ
RÀ SOÁT PHẦN MỀM
PHẦN
MỀM
KIỂM THỬ PHẦN MỀM
Software Engineering 16
tkhuong@dthu.edu.vn

2. RÀ SOÁT PHẦN MỀM
| ❖   | Rà soát   |     | là xem    | xét, | đánh | giá   | sản | phẩm  |     | được   | tiến hành | mỗi   |
| --- | --------- | --- | --------- | ---- | ---- | ----- | --- | ----- | --- | ------ | --------- | ----- |
|     | giai đoạn |     | để phát   | hiện | ra   | những |     | khiếm |     | khuyết | cần sửa   | trước |
|     | khi sang  |     | giai đoạn |      | sau  |       |     |       |     |        |           |       |
❖
|     | Mục     | tiêu: |            |     |        |      |      |     |       |     |     |     |
| --- | ------- | ----- | ---------- | --- | ------ | ---- | ---- | --- | ----- | --- | --- | --- |
|     | ▪ Chỉ   | ra    | các khiếm  |     | khuyết | cần  | phải | cải | thiện |     |     |     |
|     | ▪ Khẳng |       | định những |     | sản    | phẩm | đạt  | yêu | cầu   |     |     |     |
▪ Kiểm soát việc đạt chất lượng kỹ thuật tối thiểu của sản phẩm
❖ Áp dụng tại các thời điểm khác nhau trong quá trình phát triển
|     | phần | mềm. |     |     |     |                      |     |     |     |     |     |     |
| --- | ---- | ---- | --- | --- | --- | -------------------- | --- | --- | --- | --- | --- | --- |
|     |      |      |     |     |     | Software Engineering |     |     |     |     |     | 17  |
tkhuong@dthu.edu.vn

2. RÀ SOÁT PHẦN MỀM
| ❖ Các | kiểu  | rà soát   |       |       |      |     |     |     |
| ----- | ----- | --------- | ----- | ----- | ---- | --- | --- | --- |
| ▪     | Thanh | tra       |       |       |      |     |     |     |
| ▪     | Họp   | xét duyệt | không | chính | thức |     |     |     |
▪ Họp chính thức với các thành viên: khách hàng, nhà quản lý,
|     | nhân      | viên kỹ | thuật | (rà soát | kỹ thuật | chính | thức | – formal |
| --- | --------- | ------- | ----- | -------- | -------- | ----- | ---- | -------- |
|     | technical | review: | FTR)  |          |          |       |      |          |
Software Engineering 18
tkhuong@dthu.edu.vn

2. RÀ SOÁT PHẦN MỀM
| ❖ Rà | soát    | kỹ thuật | chính   | thức       | (FTR) |      |              |       |
| ---- | ------- | -------- | ------- | ---------- | ----- | ---- | ------------ | ----- |
| ▪    | Là hoạt | động     | đảm bảo | chất       | lượng | phần | mềm do những | người |
|      | đang    | tham gia | phát    | triển thực | hiện  |      |              |       |
Software Engineering 19
tkhuong@dthu.edu.vn

2. RÀ SOÁT PHẦN MỀM
| ▪   | Mục | tiêu | của  | FTR |       |      |      |         |     |        |          |      |
| --- | --- | ---- | ---- | --- | ----- | ---- | ---- | ------- | --- | ------ | -------- | ---- |
|     | •   | Phát | hiện | lỗi | trong | chức | năng | (chương |     | trình) | và triển | khai |
(implementation)
|     | •   | Kiểm  | thử  | sự phù | hợp     | của phần   | mềm   | với | yêu    | cầu       |      |     |
| --- | --- | ----- | ---- | ------ | ------- | ---------- | ----- | --- | ------ | --------- | ---- | --- |
|     | •   | Khẳng | định | phần   | đã      | đạt yêu    | cầu   |     |        |           |      |     |
|     | •   | Đảm   | bảo  | PM     | phù hợp | với các    | chuẩn | đã  | đặt ra |           |      |     |
|     | •   | Đảm   | bảo  | PM     | được    | phát triển | theo  | một | cách   | thức nhất | quán |     |
|     | •   | Làm   | cho  | dự án  | dễ quản | lý hơn     |       |     |        |           |      |     |
• Ngoài ra làm cơ sở huấn luyện các kỹ sư trẻ và có ích ngay cả cho
|     |     | những | kỹ  | sư đã | có kinh | nghiệm               |     |     |     |     |     |     |
| --- | --- | ----- | --- | ----- | ------- | -------------------- | --- | --- | --- | --- | --- | --- |
|     |     |       |     |       |         | Software Engineering |     |     |     |     |     | 20  |
tkhuong@dthu.edu.vn

| Tiến | trình | hoạt | động | rà soát |
| ---- | ----- | ---- | ---- | ------- |
Software Engineering 21
tkhuong@dthu.edu.vn

|     | Cuộc  |      |       | họp  |      |         | rà  | soát     |     |         |       |         |          |
| --- | ----- | ---- | ----- | ---- | ---- | ------- | --- | -------- | --- | ------- | ----- | ------- | -------- |
| ❖   | Thành |      | phần: |      | lãnh |         | đạo | rà soát, |     | các cá  | nhân  | rà soát | và người |
|     | tạo   | ra   | sản   | phẩm |      | được    |     | rà soát  |     | (+khách | hàng) |         |          |
| ❖   | Kết   | luận |       | đưa  | ra   | 1 trong |     | 3 quyết  |     | định    | sau:  |         |          |
|     | ▪     | Chấp |       | nhận | sản  | phẩm    |     | không    | cần | chỉnh   | sửa   |         |          |
|     | ▪     | Từ   | chối  | sản  | phẩm |         | vì  | những    | lỗi | nghiêm  | trọng |         |          |
▪ Chấp nhận cho chỉnh sửa sản phẩm, sau khi chỉnh sửa phải rà
|     |     | soát  | lại |      |     |      |     |          |     |          |     |           |      |
| --- | --- | ----- | --- | ---- | --- | ---- | --- | -------- | --- | -------- | --- | --------- | ---- |
| ❖   | Mọi | thành |     | viên |     | tham |     | gia cuộc |     | họp phải | ký  | vào quyết | định |
Software Engineering 22
tkhuong@dthu.edu.vn

|     | Sản |       | phẩm |      |     | rà      | soát    |          |       |      |         |        |
| --- | --- | ----- | ---- | ---- | --- | ------- | ------- | -------- | ----- | ---- | ------- | ------ |
| ❖   | Sản | phẩm  |      | cuộc | họp |         | rà soát |          |       |      |         |        |
|     | ▪   | Một   | báo  | cáo  | các | vấn     | đề nảy  | sinh     | do cá | nhân | rà soát | nêu ra |
|     | ▪   | Một   | danh | sách |     | các     | vấn đề  | cần giải | quyết |      |         |        |
|     | ▪   | Một   | bản  | tổng | kết | cuộc    | họp     |          |       |      |         |        |
| ❖   | Bản | tổng  | kết  | họp  |     | rà soát | phải    | chỉ      | rõ:   |      |         |        |
|     | ▪   | Đã rà | soát | cái  | gì  |         |         |          |       |      |         |        |
|     | ▪   | Ai rà | soát |      |     |         |         |          |       |      |         |        |
|     | ▪   | Tìm   | thấy | cái  | gì  | và kết  | luận    | ra sao   |       |      |         |        |
Software Engineering 23
tkhuong@dthu.edu.vn

|     | Sản     |      | phẩm |     |      | rà    | soát                 |     |       | (tt) |     |       |      |         |       |
| --- | ------- | ---- | ---- | --- | ---- | ----- | -------------------- | --- | ----- | ---- | --- | ----- | ---- | ------- | ----- |
| ❖   | Danh    | sách |      | các | vấn  | đề    | tồn                  | tại | phục  |      | vụ  |       |      |         |       |
|     | ▪ Nhận  |      | ra   | các | vùng | có    | vấn                  | đề  | trong | sản  |     | phẩm  | được | rà soát |       |
|     | ▪ Dùng  |      | như  |     | một  | danh  | sách                 | các | khoản |      | mục | để    | chỉ  | cho các | người |
|     | làm     |      | ra   | sản | phảm | cần   | chỉnh                |     | sửa   |      |     |       |      |         |       |
|     | ▪ Thiết |      | lập  | thủ | tục  | để    | đảm                  | bảo | rằng  |      | các | khoản | mục  | trong   | danh  |
|     | sách    |      | đó   | sẽ  | được | chỉnh | sửa                  |     | thực  | sự   |     |       |      |         |       |
|     |         |      |      |     |      |       | Software Engineering |     |       |      |     |       |      |         | 24    |
tkhuong@dthu.edu.vn

|     | Tiến   |       |       | hành    |       |        | rà  | soát   |       |      |       |          |      |        |      |         |
| --- | ------ | ----- | ----- | ------- | ----- | ------ | --- | ------ | ----- | ---- | ----- | -------- | ---- | ------ | ---- | ------- |
| ❖   | Mọi    | sản   |       | phẩm    |       | được   |     | tạo    | ra    | ở    | mỗi   | bước     | đều  | được   |      | rà soát |
|     | (không |       | chỉ   | sản     |       | phẩm   |     | cuối   | cùng) |      |       |          |      |        |      |         |
| ❖   | Tiến   | trình |       | phát    |       | triển  |     | chung  |       | nhất | gồm   | các      | giai | đoạn:  |      |         |
|     | ▪      | Công  |       | nghệ    | hệ    | thống  |     | (kế    | hoạch |      | triển | khai)    |      |        |      |         |
|     | ▪      | Phân  |       | tích,   | xác   | định   |     | yêu    | cầu   | phần |       | mềm (đặc |      | tả yêu | cầu) |         |
|     | ▪      | Thiết |       | kế phần |       | mềm    |     | (thiết | kế)   |      |       |          |      |        |      |         |
|     | ▪      | Lập   | trình |         | (mã   | nguồn) |     |        |       |      |       |          |      |        |      |         |
|     | ▪      | Kiểm  |       | thử     | phần  | mềm    |     | (kế    | hoạch |      | kiểm  | thử)     |      |        |      |         |
|     | ▪      | Bảo   | trì   | (kế     | hoạch |        | bảo |        | trì)  |      |       |          |      |        |      |         |
|     | →      | Rà    | soát  | bám     |       | theo   |     | sản    | phẩm  | của  | các   | giai     | đoạn | này    |      |         |
Software Engineering 25
tkhuong@dthu.edu.vn

| Các    | danh   | mục        | sản      | phẩm         | cần | rà soát |
| ------ | ------ | ---------- | -------- | ------------ | --- | ------- |
| ❖ Danh | mục rà | soát công  | nghệ     | hệ thống     |     |         |
| ❖ Danh | mục rà | soát lập   | kế hoạch | dự án        |     |         |
| ❖ Danh | mục rà | soát phân  | tích     | yêu cầu phần | mềm |         |
| ❖ Danh | mục rà | soát thiết | kế phần  | mềm          |     |         |
| ❖ Danh | mục rà | soát khâu  | lập      | trình        |     |         |
| ❖ Danh | mục rà | soát kiểm  | thử      | phần mềm     |     |         |
| ❖ Danh | mục rà | soát bảo   | trì phần | mềm          |     |         |
Software Engineering 26
tkhuong@dthu.edu.vn

NỘI DUNG
XÁC MINH & THẨM ĐỊNH
KIỂM
THỬ
RÀ SOÁT PHẦN MỀM
PHẦN
MỀM
KIỂM THỬ PHẦN MỀM
Software Engineering 27
tkhuong@dthu.edu.vn

3. KIỂM THỬ PHẦN MỀM
❖
| Mô      | hình  | chữ  |      | V – các | pha | kiểm | thử |
| ------- | ----- | ---- | ---- | ------- | --- | ---- | --- |
| ❖ Các   | hình  | thức |      | kiểm    | thử |      |     |
| ❖ Quy   | trình | kiểm |      | thử     |     |      |     |
| ❖ Thiết | kế    | dữ   | liệu | kiểm    | thử |      |     |
| ❖ Lập   | tài   | liệu | kiểm | thử     |     |      |     |
Software Engineering 28
tkhuong@dthu.edu.vn

| 3.1 Mô | hình | chữ | V – | các | pha | kiểm | thử |
| ------ | ---- | --- | --- | --- | --- | ---- | --- |
Software Engineering 29
tkhuong@dthu.edu.vn

|     | 3.1 Mô            |       | hình       |                   | chữ    | V –   | các | pha | kiểm | thử |
| --- | ----------------- | ----- | ---------- | ----------------- | ------ | ----- | --- | --- | ---- | --- |
| ❖   | Kiểm              | thử   | đơn        | vị (Unit Testing) |        |       |     |     |      |     |
|     | ▪ Kiểm            |       | tra từng   | đơn               | vị lập | trình |     |     |      |     |
|     |                   | →Các  | phương     | thức              |        |       |     |     |      |     |
|     | ▪ Thực            |       | hiện trong | môi               | trường | cô    | lập |     |      |     |
|     | ▪ Lập             | trình | viên       | thực              | hiện   |       |     |     |      |     |
|     | ▪ Unit Test Case: |       |            |                   |        |       |     |     |      |     |
Software Engineering 30
tkhuong@dthu.edu.vn

| 3.1 Mô |          | hình     | chữ                   |        | V –       | các | pha | kiểm | thử |
| ------ | -------- | -------- | --------------------- | ------ | --------- | --- | --- | ---- | --- |
| ❖ Kiểm | thử tích | hợp      | (Integration Testing) |        |           |     |     |      |     |
| ▪ Kiểm | tra      | một nhóm |                       | đơn vị | lập trình |     |     |      |     |
| ▪ Kiểm | tra      | sự phối  | hợp                   | hoạt   | động      |     |     |      |     |
| ▪ Thực | hiện     | trong    | môi                   | trường | tích      | hợp |     |      |     |
Software Engineering 31
tkhuong@dthu.edu.vn

|     | 3.1 Mô |                          | hình     |      | chữ              | V –     | các | pha | kiểm | thử |
| --- | ------ | ------------------------ | -------- | ---- | ---------------- | ------- | --- | --- | ---- | --- |
| ❖   | Kiểm   | thử                      | hệ thống |      | (System Testing) |         |     |     |      |     |
|     | ▪ Kiểm | tra                      | toàn     | bộ   | hệ thống         |         |     |     |      |     |
|     | ▪ Hệ   | thống                    | hoạt     | động | như              | đặc tả? |     |     |      |     |
|     | ▪ Thực | hiện                     | trong    | môi  | trường           | giả     | lập |     |      |     |
|     | ▪ Phân | loại:                    |          |      |                  |         |     |     |      |     |
|     |        | • Functional Testing     |          |      |                  |         |     |     |      |     |
|     |        | • Non-Functional Testing |          |      |                  |         |     |     |      |     |
Software Engineering 32
tkhuong@dthu.edu.vn

| 3.1 Mô   |          | hình  | chữ        | V –                  | các  | pha     | kiểm | thử |
| -------- | -------- | ----- | ---------- | -------------------- | ---- | ------- | ---- | --- |
| ❖ Nghiệm | thu      | phần  | mềm        | (Acceptance Testing) |      |         |      |     |
| ▪ Khách  | hàng     | dùng  | thử        |                      |      |         |      |     |
| ▪ Hệ     | thống    | thỏa  | mãn nhu    | cầu?                 |      |         |      |     |
| ▪ Thực   | hiện     | trong | môi trường | vận                  | hành | thật sự |      |     |
| ▪ Phân   | loại:    |       |            |                      |      |         |      |     |
|          | • Nghiệm | thu   | Alpha      |                      |      |         |      |     |
|          | • Nghiệm | thu   | Beta       |                      |      |         |      |     |
Software Engineering 33
tkhuong@dthu.edu.vn

|     | 3.2 Các |                |           | hình |        | thức                |                       | kiểm                 | thử |
| --- | ------- | -------------- | --------- | ---- | ------ | ------------------- | --------------------- | -------------------- | --- |
| ❖   | Kỹ      | thuật          | kiểm      | thử  | tĩnh   | (static testing)    |                       |                      |     |
|     | ▪       | Thanh          | tra       | phần | mềm    |                     | (Software Inspection) |                      |     |
|     | ▪       | Model Checking |           |      |        |                     |                       |                      |     |
|     | ▪       | Không          | thực      | thi  | chương |                     | trình                 |                      |     |
| ❖   | Kỹ      | thuật          | kiểm      | thử  | động   |                     | (dynamic testing)     |                      |     |
|     | ▪       | Kiểm           | thử       | hộp  | đen    | (black-box testing) |                       |                      |     |
|     |         | •              | Kỹ thuật  | kiểm | thử    | chức                | năng                  | (functional testing) |     |
|     |         | •              | Test Case |      |        |                     |                       |                      |     |
|     | ▪       | Kiểm           | thử       | hộp  | trắng  | (white-box testing) |                       |                      |     |
|     |         | •              | Kỹ thuật  | kiểm | thử    | cấu                 | trúc                  | (structural testing) |     |
Software Engineering 34
tkhuong@dthu.edu.vn

|     | 3.2 Các |       |      |     | hình |     |      | thức | kiểm | thử |
| --- | ------- | ----- | ---- | --- | ---- | --- | ---- | ---- | ---- | --- |
| ❖   | Kỹ      | thuật | kiểm |     | thử  |     | tĩnh | - 1  |      |     |
▪
|     |     | Thanh |         | tra   | phần  | mềm   |         | (Software  | Inspection) |     |
| --- | --- | ----- | ------- | ----- | ----- | ----- | ------- | ---------- | ----------- | --- |
|     |     | •     | Micheal |       | Fagan |       | đề xuất | 1979       |             |     |
|     |     | •     | Kiểm    | tra   | bằng  |       | cách    | đọc nội    | dung        |     |
|     |     | •     | Đội     | ngũ   | thanh |       | tra độc | lập        |             |     |
|     |     | •     | Ưu      | điểm: |       |       |         |            |             |     |
|     |     |       | –       | Có    | thể   | thực  | hiện    | ở mỗi pha  |             |     |
|     |     |       | –       | Rất   | hiệu  | quả   | để      | tìm lỗi    |             |     |
|     |     | •     | Khuyết  |       | điểm: |       |         |            |             |     |
|     |     |       | –       | Đội   | ngũ   | nhiều | kinh    | nghiệm     |             |     |
|     |     |       | –       | Tốn   | kém   | thời  | gian    | và chi phí |             |     |
Software Engineering 35
tkhuong@dthu.edu.vn

|     | 3.2 Các |       |        |          | hình  |       | thức |           |       | kiểm     | thử |
| --- | ------- | ----- | ------ | -------- | ----- | ----- | ---- | --------- | ----- | -------- | --- |
| ❖   | Kỹ      | thuật | kiểm   |          | thử   | tĩnh  |      | - 2       |       |          |     |
|     | ▪       | Model |        | Checking |       |       |      |           |       |          |     |
|     |         | •     | Kiểm   | tra      | bằng  | cách  |      | chứng     | minh  |          |     |
|     |         |       | –      | Mô       | hình  | toán  | học  | sản phẩm  |       | kiểm tra |     |
|     |         |       | –      | Chứng    |       | minh  | mô   | hình đúng |       | đắn      |     |
|     |         | •     | Thực   | hiện     |       | ở pha | phân | tích      | thiết | kế       |     |
|     |         | •     | Ưu     | điểm:    |       |       |      |           |       |          |     |
|     |         |       | –      | Có       | khả   | năng  | đúng | đắn       | hoàn  | toàn     |     |
|     |         |       | –      | Có       | thể   | thực  | hiện | tự động   |       |          |     |
|     |         | •     | Khuyết |          | điểm: |       |      |           |       |          |     |
|     |         |       | –      | Phức     | tạp   | để    | mô   | hình hóa  |       |          |     |
|     |         |       | –      | Chưa     | có    | công  | cụ   | tự động   | hiệu  | quả      |     |
Software Engineering 36
tkhuong@dthu.edu.vn

|     |     | 3.2 Các   |      |      | hình |      | thức    | kiểm              | thử |
| --- | --- | --------- | ---- | ---- | ---- | ---- | ------- | ----------------- | --- |
| ❖   | Kỹ  | thuật     | kiểm |      | thử  | động | - 1     |                   |     |
|     | ▪   | Kiểm      | thử  | hộp  | đen  |      |         |                   |     |
|     |     | • Chỉ     | cần  | dựa  | vào  | đặc  | tả phần | mềm               |     |
|     |     | • Thường  |      | phát | hiện | các  | lỗi đặc | tả yêu cầu, thiết | kế  |
|     |     | • Dễ      | dàng | thực | hiện |      |         |                   |     |
|     |     | • Chi phí |      | thấp |      |      |         |                   |     |
• Xây dựng các test case  (dữ liệu) để kiểm tra các chức năng
Software Engineering 37
tkhuong@dthu.edu.vn

|     |     | 3.2 Các |          | hình    |      | thức | kiểm | thử |
| --- | --- | ------- | -------- | ------- | ---- | ---- | ---- | --- |
| ❖   | Kỹ  | thuật   | kiểm     | thử     | động | - 2  |      |     |
|     | ▪   | Kiểm    | thử      | hộp đen |      |      |      |     |
|     |     | •       | Xây dựng | dữ liệu | kiểm | thử  |      |     |
– Kỹ thuật phân tích giá trị biên – BVA (boundary value analysis)
– Kỹ thuật phân vùng tương đương - EP(equivalence Partitioning)
|     |     |     | – Kiểm | thử ngẫu     | nhiên        | (random testing) |        |     |
| --- | --- | --- | ------ | ------------ | ------------ | ---------------- | ------ | --- |
|     |     |     | – Đồ   | thị nhân-quả | (cause-efect |                  | graph) |     |
|     |     |     | – Kiểm | thử cú       | pháp         |                  |        |     |
Software Engineering 38
tkhuong@dthu.edu.vn

|      | 3.2 Các     |      |                |       | hình     |          | thức  | kiểm | thử |
| ---- | ----------- | ---- | -------------- | ----- | -------- | -------- | ----- | ---- | --- |
| ❖ Kỹ | thuật       | kiểm |                | thử   | động     |          | - 3   |      |     |
|      | ▪ Test Case |      |                |       |          |          |       |      |     |
|      | •           | Kiểm | tra            | đầu   | vào, đầu |          | ra    |      |     |
|      | •           | Dùng | kịch           | bản   | kiểm     |          | thử   |      |     |
|      | •           | Các  | đối            | tượng | kiểm     |          | tra:  |      |     |
|      |             | –    | Một            | đoạn  | mã       | nguồn    |       |      |     |
|      |             | –    | Một            | kịch  | bản      | Use Case |       |      |     |
|      |             | –    | Một            | chức  | năng     | hoàn     | chỉnh |      |     |
|      | •           | Nội  | dung Test Case |       |          |          |       |      |     |
|      |             | –    | Ngữ            | cảnh  | kiểm     | tra      |       |      |     |
|      |             | –    | Dữ             | liệu  | đầu vào  |          |       |      |     |
|      |             | –    | Kết            | quả   | đầu ra   | mong     | đợi   |      |     |
|      |             | –    | Các            | bước  | thực     | hiện     |       |      |     |
Software Engineering 39
tkhuong@dthu.edu.vn

|                 | 3.2 Các | hình   | thức      | kiểm | thử       |
| --------------- | ------- | ------ | --------- | ---- | --------- |
| ❖ Test Case của |         | trường | hợp “Nhập | sách | thất bại” |
Software Engineering 40
tkhuong@dthu.edu.vn

|     |     | 3.2 Các |           |      |      | hình       |                    | thức  |       | kiểm    |       | thử |
| --- | --- | ------- | --------- | ---- | ---- | ---------- | ------------------ | ----- | ----- | ------- | ----- | --- |
| ❖   | Kỹ  | thuật   |           | kiểm |      | thử        | động               |       |       |         |       |     |
|     | ▪   | Kiểm    |           | thử  | hộp  | trắng      |                    |       |       |         |       |     |
|     |     |         | • Dựa     | vào  | mã   | nguồn/ cấu |                    |       | trúc  | chương  | trình |     |
|     |     |         | • Thường  |      | phát | hiện       | các                | lỗi   | lập   | trình   |       |     |
|     |     |         | • Khó     | thực |      | hiện       |                    |       |       |         |       |     |
|     |     |         | • Chi phí |      | cao  |            |                    |       |       |         |       |     |
|     | ▪   | Kỹ      | thuật     | kiểm |      | thử        | hộp                | trắng |       |         |       |     |
|     |     |         | • Kiểm    | thử  |      | dựa trên   | đồ                 | thị   | điều  | khiển   |       |     |
|     |     |         | • Kiểm    | thử  |      | dựa trên   | đồ                 | thị   | luồng | dữ liệu |       |     |
|     |     |         | • Kiểm    | thử  |      | đột biến   | (mutation testing) |       |       |         |       |     |
Software Engineering 41
tkhuong@dthu.edu.vn

3. KIỂM THỬ PHẦN MỀM
| ❖ Mô    | hình     | chữ  | V –  | các  | pha kiểm | thử |
| ------- | -------- | ---- | ---- | ---- | -------- | --- |
| ❖ Các   | hình     | thức | kiểm |      | thử      |     |
| ❖ Quy   | trình    | kiểm |      | thử  |          |     |
| ❖ Thiết | kế       | dữ   | liệu | kiểm | thử      |     |
| ❖ Lập   | tài liệu |      | kiểm | thử  |          |     |
Software Engineering 48
tkhuong@dthu.edu.vn

|     | 3.3 Quy | trình |     | kiểm    | thử |     |     |     |     |
| --- | ------- | ----- | --- | ------- | --- | --- | --- | --- | --- |
|     |         |       |     | Dữ liệu | KT  |     |     |     |     |
(Test data)
| Đặc | tả YC | Kế hoạch | KT  | Ca kiểm | thử | Kết quả | KT  | Báo cáo | KT  |
| --- | ----- | -------- | --- | ------- | --- | ------- | --- | ------- | --- |
(Requirement spec) (Test plan) (Test cases) (Test result) (Test report)
|     |          | Thiết | kế kiểm |                      | Thực | hiện |     | Đánh giá |     |
| --- | -------- | ----- | ------- | -------------------- | ---- | ---- | --- | -------- | --- |
| Lập | kế hoạch |       |         |                      |      |      |     |          |     |
|     |          |       | thử     |                      | kiểm | thử  |     | kết quả  |     |
|     |          |       |         | Software Engineering |      |      |     |          | 49  |
tkhuong@dthu.edu.vn

|     | 3.3 Quy |       |         |        | trình |      |       | kiểm  |      |      | thử |              |          |
| --- | ------- | ----- | ------- | ------ | ----- | ---- | ----- | ----- | ---- | ---- | --- | ------------ | -------- |
| ❖   | Kiểm    |       | thử     | thường |       | gồm  |       | các   | bước |      |     |              |          |
|     | ▪       | Lập   | kế      | hoạch  |       |      |       |       |      |      |     |              |          |
|     | ▪       | Thiết | kế      | các    | ca    | kiểm |       | thử   |      |      |     |              |          |
|     | ▪       | Tạo   | dữ      | liệu   | kiểm  |      | thử   |       |      |      |     |              |          |
|     |         | •     | Kiểm    | thử    | với   | tất  | cả    | các   | dữ   | liệu | vào | là cần thiết |          |
|     |         |       | –       | Không  | thể   |      | kiểm  | thử   | “vét | cạn” |     |              |          |
|     |         | •     | Chọn    | tập    | các   | dữ   | liệu  | thử   | đại  | diện |     | từ miền dữ   | liệu vào |
|     |         |       | –       | Dựa    | trên  | các  | tiêu  | chuẩn |      | chọn | dữ  | liệu thử     |          |
|     | ▪       | Thực  | thi     | chương |       |      | trình | dựa   |      | trên | dữ  | liệu kiểm    | thử      |
|     |         | •     | Cung    | cấp    | dữ    | liêu | thử   |       |      |      |     |              |          |
|     |         | •     | Thực    | thi    |       |      |       |       |      |      |     |              |          |
|     |         | •     | Ghi     | nhận   | kết   | quả  |       |       |      |      |     |              |          |
|     | ▪       | Quan  | sát     |        | kết   | quả  | kiểm  | thử   |      |      |     |              |          |
|     |         | •     | So sánh |        | kết   | quả  | nhận  | được  |      | với  | kết | quả mong     | đợi      |
Software Engineering 50
tkhuong@dthu.edu.vn

|     | 3.4 Thiết |     |     | kế  |     | dữ  | liệu |     | kiểm |     | thử |     |
| --- | --------- | --- | --- | --- | --- | --- | ---- | --- | ---- | --- | --- | --- |
❖
|     | Ví  | dụ: một | textbox chỉ |     |     | cho | phép |     | nhập | số nguyên |     | từ 1 đến |
| --- | --- | ------- | ----------- | --- | --- | --- | ---- | --- | ---- | --------- | --- | -------- |
100
| →   | Ta không |          | thể nhập |      | tất | cả    | các   | giá  | trị   | từ 1 đến | 100??? |     |
| --- | -------- | -------- | -------- | ---- | --- | ----- | ----- | ---- | ----- | -------- | ------ | --- |
| ❖   | 2 kỹ     | thuật    | để thiết |      | kế  | dữ    | liệu  | kiểm | thử   |          |        |     |
|     | ▪        | Kỹ thuật | phân     | tích | giá | trị   | giới  | hạn  | – BVA |          |        |     |
|     | ▪        | Kỹ thuật | phân     | vùng |     | tương | đương |      | –     | EP       |        |     |
Software Engineering 51
tkhuong@dthu.edu.vn

|         | 3.4 Thiết |       |      | kế   | dữ   | liệu | kiểm                   | thử |     |
| ------- | --------- | ----- | ---- | ---- | ---- | ---- | ---------------------- | --- | --- |
| PP1: Kỹ |           | thuật | phân | tích | giới | hạn  | – BVA (Boundary Value  |     |     |
Analysis)
| o Kỹ | thuật | BVA sẽ         |       | chọn    | các | giá trị        | nằm tại | các điểm    | giới hạn |
| ---- | ----- | -------------- | ----- | ------- | --- | -------------- | ------- | ----------- | -------- |
| của  | phần  | vùng           |       |         |     |                |         |             |          |
| o Áp | dụng  | kỹ             | thuật | BVA cần |     | 4 test case để |         | test trường | hợp vd   |
| trên |       | là 0,1,100,101 |       |         |     |                |         |             |          |
Software Engineering 54
tkhuong@dthu.edu.vn

|         | 3.4 Thiết |       |     |      |     | kế   |     | dữ    | liệu |       | kiểm |     | thử              |     |     |
| ------- | --------- | ----- | --- | ---- | --- | ---- | --- | ----- | ---- | ----- | ---- | --- | ---------------- | --- | --- |
| PP2: Kỹ |           | thuật |     | phân |     | vùng |     | tương |      | đương |      | –   | EP (Equivalence  |     |     |
Partitioning)
| ❖   | Phân | chia dữ |      |     | liệu | đầu |         | vào  | thành |     | các lớp | tương |     | đương | nhau |
| --- | ---- | ------- | ---- | --- | ---- | --- | ------- | ---- | ----- | --- | ------- | ----- | --- | ----- | ---- |
| ❖   | Tạo  | ca      | kiểm | thử |      | cho | mỗi     | lớp  | tương |     | đương   |       |     |       |      |
|     | ▪    | Kiểm    | thử  | một | giá  |     | trị đại | diện | của   |     | lớp     |       |     |       |      |
▪ Nếu giá trị đại diện bị lỗi → các giá trị trong lớp đó cũng sẽ bị lỗi
|     |      | như | vậy   |     |     |      |     |           |     |     |        |     |     |     |     |
| --- | ---- | --- | ----- | --- | --- | ---- | --- | --------- | --- | --- | ------ | --- | --- | --- | --- |
| →   | Giảm | số  | lượng |     | ca  | kiểm |     | thử, tăng |     |     | độ phủ |     |     |     |     |
Software Engineering 58
tkhuong@dthu.edu.vn

|         | 3.4 Thiết |       |      | kế   | dữ    | liệu | kiểm  |     | thử              |     |
| ------- | --------- | ----- | ---- | ---- | ----- | ---- | ----- | --- | ---------------- | --- |
| PP2: Kỹ |           | thuật | phân | vùng | tương |      | đương | –   | EP (Equivalence  |     |
Partitioning)
o
| Trong |     | ví dụ | trên | dùng | kỹ thuật |     | này sẽ | chia làm | 3 phân | vùng |
| ----- | --- | ----- | ---- | ---- | -------- | --- | ------ | -------- | ------ | ---- |
o
Như vậy chỉ cần chọn 3 test case để test trường hợp này: -5,
| 55, 102 hoặc |     |     | 0, 10, 1000,…. |     |     |     |     |     |     |     |
| ------------ | --- | --- | -------------- | --- | --- | --- | --- | --- | --- | --- |
Software Engineering 59
tkhuong@dthu.edu.vn

|         | 3.4 Thiết |     |       |     |      | kế  |      | dữ    | liệu |       | kiểm |     | thử              |     |     |
| ------- | --------- | --- | ----- | --- | ---- | --- | ---- | ----- | ---- | ----- | ---- | --- | ---------------- | --- | --- |
| PP2: Kỹ |           |     | thuật |     | phân |     | vùng | tương |      | đương |      | –   | EP (Equivalence  |     |     |
Partitioning)
| o   | Tuy  | nhiên |         | nếu | nhập |     | số  | thập | phân |     | (55.5) hay một |     |     | ký  | tự không |
| --- | ---- | ----- | ------- | --- | ---- | --- | --- | ---- | ---- | --- | -------------- | --- | --- | --- | -------- |
|     | phải | số    | (abc)?? |     |      |     |     |      |      |     |                |     |     |     |          |
o
|     | Trong |     | trường |     | hợp |     | trên | có  | thể | chia thành |     | 5 phân |     | vùng | như |
| --- | ----- | --- | ------ | --- | --- | --- | ---- | --- | --- | ---------- | --- | ------ | --- | ---- | --- |
sau:
|     | o   | Các   | số   | nguyên |     | từ  | 1 đến | 100   |     |     |     |     |     |     |     |
| --- | --- | ----- | ---- | ------ | --- | --- | ----- | ----- | --- | --- | --- | --- | --- | --- | --- |
|     | o   | Các   | số   | nguyên |     | nhỏ |       | hơn 1 |     |     |     |     |     |     |     |
|     | o   | Các   | số   | nguyên |     | lớn | hơn   | 100   |     |     |     |     |     |     |     |
|     | o   | Không |      | phải   | số  |     |       |       |     |     |     |     |     |     |     |
|     | o   | Số    | thập | phân   |     |     |       |       |     |     |     |     |     |     |     |
Software Engineering 60
tkhuong@dthu.edu.vn

| 3.4 Thiết |     | kế dữ | liệu | kiểm | thử |
| --------- | --- | ----- | ---- | ---- | --- |
Có 2 bước:
| ▪ Xác | định | các lớp | tương | đương |     |
| ----- | ---- | ------- | ----- | ----- | --- |
| ▪ Xác | định | các ca  | kiểm  | thử   |     |
Software Engineering 61
tkhuong@dthu.edu.vn

|     |       | Xác   | định       |       |           | lớp                      |         | tương |        | đương |           |         |       |         |
| --- | ----- | ----- | ---------- | ----- | --------- | ------------------------ | ------- | ----- | ------ | ----- | --------- | ------- | ----- | ------- |
| ❖   | Dựa   | vào   | điều       |       | kiện      | đầu                      | vào/đầu |       | ra     |       |           |         |       |         |
| ❖   | Lớp   | tương |            | đương |           | (equivalence class) biểu |         |       |        |       |           | diễn    | một   | tập hợp |
|     | trạng | thái  |            |       |           |                          |         |       |        |       |           |         |       |         |
|     | ▪     | hợp   | lệ (valid) |       |           |                          |         |       |        |       |           |         |       |         |
|     | ▪     | không | hợp        | lệ    | (invalid) |                          |         |       |        |       |           |         |       |         |
|     | Điều  | kiện  | bên        | ngoài |           |                          | Các     | lớp   | tương  | đương |           | Các lớp | tương | đương   |
|     |       |       |            |       |           |                          |         |       | hợp lệ |       |           | không   |       | hợp lệ  |
| ❖   | Phân  | hoạch |            | tương |           | đương                    |         | là    | 1 quá  | trình | heuristic |         |       |         |
Software Engineering 62
tkhuong@dthu.edu.vn

| Dựa    | vào      | điều                  | kiện | đầu | vào |
| ------ | -------- | --------------------- | ---- | --- | --- |
| ❖ Điều | kiện đầu | vào (input condition) |      |     |     |
▪
Giá trị: A
| ▪     | Dãy giá trị: [1..100] |                       |     |     |     |
| ----- | --------------------- | --------------------- | --- | --- | --- |
| ▪     | Tập giá trị: {A,B,C}  |                       |     |     |     |
| ▪     | Boolean: là           | số nguyên             |     |     |     |
| ❖ Một | số nguyên             | tắc                   |     |     |     |
| ▪     | A → A, not A          |                       |     |     |     |
| ▪     | [1..100] →            | x<1, 1<=x<=100, x>100 |     |     |     |
| ▪     | {A,B,C} →             | A, B, C, not{A,B,C}   |     |     |     |
| ▪     | Là số nguyên          | → true, false         |     |     |     |
Software Engineering 69
tkhuong@dthu.edu.vn

|      | Dựa                | vào            | điều      | kiện  | đầu | vào     |
| ---- | ------------------ | -------------- | --------- | ----- | --- | ------- |
| ❖ Ví | dụ: nhập           | vào            | số nguyên | dương | nhỏ | hơn 100 |
|      | ▪ Chuỗi            | ký tự, invalid |           |       |     |         |
|      | ▪ Số thực, invalid |                |           |       |     |         |
|      | ▪ x<=0, invalid    |                |           |       |     |         |
|      | ▪ 1<=x<100, valid  |                |           |       |     |         |
|      | ▪ x>=100, invalid  |                |           |       |     |         |
Software Engineering 70
tkhuong@dthu.edu.vn

|     | Dựa                   | vào        |                          | điều |            | kiện         |          | đầu | vào       |        |
| --- | --------------------- | ---------- | ------------------------ | ---- | ---------- | ------------ | -------- | --- | --------- | ------ |
| ❖   | Ví dụ: chuỗi          |            | có                       | 7 ký | tự         | (chữ         | cái), ký | tự  | đầu là ký | tự hoa |
|     | ▪ Length < 7, invalid |            |                          |      |            |              |          |     |           |        |
|     | ▪ Length > 7, invalid |            |                          |      |            |              |          |     |           |        |
|     | ▪ 7 ký                | tự, ký     | tự                       | đầu  | hoa, valid |              |          |     |           |        |
|     | ▪ 7 ký                | tự, ký     | tự                       | đầu  | không      | hoa, invalid |          |     |           |        |
|     | ▪ Ký                  | tự đặc     | biệt: #, *, &,.., invaid |      |            |              |          |     |           |        |
|     | ▪ Chuỗi               | số, invaid |                          |      |            |              |          |     |           |        |
Software Engineering 71
tkhuong@dthu.edu.vn

|      | Dựa              | vào     | điều             | kiện | đầu | vào |
| ---- | ---------------- | ------- | ---------------- | ---- | --- | --- |
| ❖ Ví | dụ: tọa          | độ điểm | 3<=x<=7, 5<=y<=9 |      |     |     |
|      | ▪ x<3, invalid   |         |                  |      |     |     |
|      | ▪ 3<=x<=7, valid |         |                  |      |     |     |
|      | ▪ x>7, invalid   |         |                  |      |     |     |
|      | ▪ y<5, invalid   |         |                  |      |     |     |
|      | ▪ 5<=y<=9, valid |         |                  |      |     |     |
|      | ▪ y>9, invalid   |         |                  |      |     |     |
|      | ▪ x, y khác      | ký      | tự số, invalid   |      |     |     |
Software Engineering 72
tkhuong@dthu.edu.vn

|        | Dựa          | vào   | điều  | kiện  | đầu     | ra        |        |
| ------ | ------------ | ----- | ----- | ----- | ------- | --------- | ------ |
| ❖ Phân | lớp          | tương | đương | tương | ứng với | điều kiện | đầu ra |
| ❖ Ví   | dụ: xếp      | loại  |       |       |         |           |        |
|        | ▪ 0<=x<3 →   | D     |       |       |         |           |        |
|        | ▪ 3<=x<5 →   | C     |       |       |         |           |        |
|        | ▪ 5<=x<7 →   | B     |       |       |         |           |        |
|        | ▪ 7<=x<=10 → |       | A     |       |         |           |        |
Software Engineering 75
tkhuong@dthu.edu.vn

|     | Xác      | định          | các    | ca kiểm   |         | thử     |           |      |
| --- | -------- | ------------- | ------ | --------- | ------- | ------- | --------- | ---- |
| ❖   | Gán Mã   | ID cho        | mỗi    | lớp tương | đương   |         |           |      |
| ❖   | Viết các | test case phủ |        | nhiều     | nhất có | thể các | lớp hợp   | lệ → |
|     | phủ toàn | bộ các        | lớp    | hợp lệ    |         |         |           |      |
| ❖   | Viết các | test case phủ |        | nhiều     | nhất có | thể các | lớp không | hợp  |
|     | lệ → phủ | toàn          | bộ các | lớp không | hợp     | lệ      |           |      |
Software Engineering 76
tkhuong@dthu.edu.vn

| Lập | tài liệu | kiểm | thử |
| --- | -------- | ---- | --- |
❖ Test cases
❖ Bug report
Software Engineering 81
tkhuong@dthu.edu.vn

Test cases
❖ Là một tình huống kiểm tra, được thiết kế để kiểm tra một đối
|     | tượng |      | có  | thỏa | mãn    | yêu  | cầu  | đặt | ra  | hay không. |      |      |      |     |
| --- | ----- | ---- | --- | ---- | ------ | ---- | ---- | --- | --- | ---------- | ---- | ---- | ---- | --- |
| ❖   | 3     | bước | cơ  | bản  |        |      |      |     |     |            |      |      |      |     |
|     | ▪     | Mô   | tả: | đặc  | tả các | điều | kiện | cần | cố  | để tiến    | hành | kiểm | tra. |     |
▪ Nhập: đặc tả đối tượng hoặc dữ liệu cần thiết, được sử dụng làm
|     |      | đầu  | vào      | để   | thực   | hiện | kiểm    | tra. |      |        |        |      |      |     |
| --- | ---- | ---- | -------- | ---- | ------ | ---- | ------- | ---- | ---- | ------ | ------ | ---- | ---- | --- |
|     | ▪    | Kết  | quả      | mong |        | chờ: | kết quả | trả  | về   | từ đối | tượng  | kiểm | tra. |     |
| ❖   | Test |      | scenario |      | → test | case | →       | Test |      | Step   |        |      |      |     |
|     | ▪    | Test | Step:    |      | một    | hành | động    | để   | thực | hiện   | và đáp | ứng  | mong | đợi |
|     | ▪    | Test | Case:    |      | danh   | sách | các     | test | step |        |        |      |      |     |
▪ Test Scenario: danh sách các test case và phối hợp của chúng.
Software Engineering 82
tkhuong@dthu.edu.vn

|                         | Test cases – |      |                  |          | Nội  |            | dung    |      |      |      |
| ----------------------- | ------------ | ---- | ---------------- | -------- | ---- | ---------- | ------- | ---- | ---- | ---- |
| 1. ID: định             |              | danh | phân             | biệt     | các  | test cases |         |      |      |      |
| 2. Test case name: mô   |              |      |                  | tả       | ngắn |            | gọn mục | tiêu | của  | test |
| 3. Precondition: điều   |              |      |                  | kiện     | tiên | quyết      | để      | thực | hiện | test |
| 4. Test step: các       |              |      | bước             | thực     |      | hiện       | cùng dữ | liệu | test |      |
| 5. Expected result: kết |              |      |                  | quả      | mong |            | đợi     |      |      |      |
| 6. Actual result: kết   |              |      |                  | quả thực |      | tế         |         |      |      |      |
| 7. Status: kết          |              | quả  | test (Pass/Fail) |          |      |            |         |      |      |      |
| 8. Tester: người        |              |      | thực             | hiện     | test |            |         |      |      |      |
| 9. Date: ngày           |              | test |                  |          |      |            |         |      |      |      |
| 10. Remark: ghi         |              |      | chú              |          |      |            |         |      |      |      |
Software Engineering 83
tkhuong@dthu.edu.vn

Ví dụ
| ❖ Test Case của | trường | hợp “Nhập | sách | thất bại” |
| --------------- | ------ | --------- | ---- | --------- |
Software Engineering 84
tkhuong@dthu.edu.vn

Bug Report
❖ Cung cấp thông tin chi tiết về sự cố hoặc lỗi cho những bên
liên quan
| ▪ Người | phát triển: | sửa   | lỗi      |         |           |         |
| ------- | ----------- | ----- | -------- | ------- | --------- | ------- |
| ▪ Người | quản lý:    | quyết | định tài | nguyên, | cấp phát, | ưu tiên |
▪ Nhân viên hỗ trợ kỹ thuật: nắm bắt thông tin thực hiện, chuẩn bị
| ▪ Kiểm | thử viên: | cần | biết trạng | thái của | hệ thống | hiện tại |
| ------ | --------- | --- | ---------- | -------- | -------- | -------- |
Software Engineering 85
tkhuong@dthu.edu.vn

| Bug report –                |       | Nội                     | dung   |        |     |
| --------------------------- | ----- | ----------------------- | ------ | ------ | --- |
| 1. ID: định danh            | lỗi   |                         |        |        |     |
| 2. Function name: chức      |       | năng                    | bị     | lỗi    |     |
| 3. Problem summary: mô      |       |                         | tả lỗi |        |     |
| 4. How to reproduce it: các |       |                         | bước   | tạo ra | lỗi |
| 5. Reported by: người       |       | báo                     | cáo    |        |     |
| 6. Date: ngày               | báo   | cáo                     |        |        |     |
| 7. Assigned to: giao        |       | ai sửa                  | lỗi    |        |     |
| 8. Status: tình             | trạng | lỗi (open/fixed/closed) |        |        |     |
| 9. Comment: ghi             | chú   |                         |        |        |     |
Software Engineering 86
tkhuong@dthu.edu.vn

|      |      | VD1. Giải |     |       |     |     | phương |        |     | trình | bậc | 2   |
| ---- | ---- | --------- | --- | ----- | --- | --- | ------ | ------ | --- | ----- | --- | --- |
| Phân | tích | yêu       | cầu | (ngôn |     | ngữ | tự     | nhiên) |     |       |     |     |
❖ Giáo viên muốn có phần mềm hỗ trợ học sinh tự rèn luyện bài tập Giải phương trình bậc
|     | 2 với | các | thông    |        | tin như | sau:  |     |       |     |     |     |     |
| --- | ----- | --- | -------- | ------ | ------- | ----- | --- | ----- | --- | --- | --- | --- |
|     | ▪     | Hỗ  | trợ giải | phương |         | trình |     | bậc 2 |     |     |     |     |
Học sinh nhập vào các hệ số a,b,c (a khác 0), phần mềm cho ra kết quả nghiệm của
|     | phương |     | trình     | với | 2 ký | số  | thập | phân |     |     |     |     |
| --- | ------ | --- | --------- | --- | ---- | --- | ---- | ---- | --- | --- | --- | --- |
|     | ▪      | Tự  | rèn luyện |     |      |     |      |      |     |     |     |     |
Học sinh nhập vào các hệ số a,b,c (a khác 0) và nghiệm của phương trình vừa nhập
Phần mềm cho kết quả đánh giá nghiệm đúng sai, nếu sai thì hiển thị nghiệm đúng
|     | Quy | tắc giải | phương |     | trình | bậc |     | 2:  |     |     |     |     |
| --- | --- | -------- | ------ | --- | ----- | --- | --- | --- | --- | --- | --- | --- |
2: ax2+bx+c=0 (với
|     | Cho phương |      | trình          |                | bậc        |       |     |            | a,b,c | là 3 số thực, a khác |     | 0)  |
| --- | ---------- | ---- | -------------- | -------------- | ---------- | ----- | --- | ---------- | ----- | -------------------- | --- | --- |
|     | Các        | bước | giải           | phương         |            | trình | như | sau:       |       |                      |     |     |
|     | B1. Tính   |      | delta = b2-4ac |                |            |       |     |            |       |                      |     |     |
|     | B2. Xác    | đinh | nghiệm         |                | theo       | delta |     |            |       |                      |     |     |
|     |            |      | + Nếu          | delta<0: PT vô |            |       |     | nghiệm     |       |                      |     |     |
|     |            |      | + Nếu          | delta=0: PT có |            |       |     | nghiệm     | kép x | =x =-b/2a            |     |     |
|     |            |      |                |                |            |       |     |            | 1     | 2                    |     |     |
|     |            |      | + Nếu          | delta>0: PT có |            |       |     | 2 nghiệm   | phân  | biệt                 |     |     |
|     |            |      |                |                | x =(-b-căn |       |     | delta)/ 2a |       |                      |     |     |
1
|     |     |     |     |     | x =(-b+căn |     |     | delta)/ 2a |     |     |     |     |
| --- | --- | --- | --- | --- | ---------- | --- | --- | ---------- | --- | --- | --- | --- |
2
Software Engineering 87
tkhuong@dthu.edu.vn

| Giải        | VD 1      |     |        |           |        |          |
| ----------- | --------- | --- | ------ | --------- | ------ | -------- |
| ❖ Điều kiện | TestCase  |     |        |           |        |          |
| Điều kiện   | Lớp hợp   | lệ  | Mã     | Lớp không | hợp lệ | Mã không |
|             |           |     | hợp lệ |           |        | hợp lệ   |
| a           | a số thực |     | v1     | a = 0     |        | x1       |
|             | a <>0     |     | v2     | a ký tự   |        | x2       |
|             |           |     |        | a null    |        | x3       |
| b           | b số thực |     | v3     | b ký tự   |        | x4       |
|             |           |     |        | b null    |        | x5       |
| c           | c số thực |     | v4     | c ký tự   |        | x6       |
|             |           |     |        | c null    |        | x7       |
Software Engineering 88
tkhuong@dthu.edu.vn

| Giải VD 1 |     |     |     |     |     |     |
| --------- | --- | --- | --- | --- | --- | --- |
❖ Thiết kế TestCase
| TestCase | Mô tả | Đầu    | ra mong  | muốn   | Mã kiểm        | tra |
| -------- | ----- | ------ | -------- | ------ | -------------- | --- |
| 1        | a = 2 | Phương | trình vô | nghiệm | v1, v2, v3, v4 |     |
b = -5
c = 7
| 2   | ………… | ……….. |     |     | ………….  |     |
| --- | ---- | ----- | --- | --- | ------ | --- |
| 3   | ………. | …………. |     |     | ……………. |     |
Software Engineering 89
tkhuong@dthu.edu.vn

BÀI TẬP 1
| ❖ Kiểm     | thử chức | năng           | đăng | nhập  | hệ thống |
| ---------- | -------- | -------------- | ---- | ----- | -------- |
| ▪ Username |          |                |      |       |          |
| ▪ Password |          |                |      |       |          |
| 1) Xác     | định các | lớp tương      |      | đương |          |
| 2) Thiết   | kế các   | test case kiểm |      | thử   |          |
Software Engineering 90
tkhuong@dthu.edu.vn

BÀI TẬP 2
| ❖ Thiết | kế test cases cho |               |      | chức            | năng | sau đây |
| ------- | ----------------- | ------------- | ---- | --------------- | ---- | ------- |
| ▪       | Input:            |               |      |                 |      |         |
|         | • Điểm            | lý thuyết: là | số   | thực, >=0 và    |      | <=7     |
|         | • Điểm            | thực hành: là |      | số thực, >=0 và |      | <=3     |
| ▪       | Output: xếp       | loại          | nếu  | LT+TH           |      |         |
|         | • >=0 và          | <5 → loại     | C    |                 |      |         |
|         | • >=5 và          | <8 → loại     | B    |                 |      |         |
|         | • >=8 và          | <=10 →        | loại | A               |      |         |
91
tkhuong@dthu.edu.vn

Thảo luận
Software Engineering 92
tkhuong@dthu.edu.vn