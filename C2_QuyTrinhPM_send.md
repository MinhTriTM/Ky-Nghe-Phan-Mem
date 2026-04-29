LOGO
KHOA SƯ PHẠM TOÁN - TIN
Chương 2
QUY TRÌNH
PHẦN MỀM
GV biên soạn: Trần Kim Hương
tkhuong@dthu.edu.vn
Software Engineering
tkhuong@dthu.edu.vn

MỤC TIÊU CHƯƠNG 2
| ❖ Trình | bày      | được | một  | số   | mô hình | phát  | triển | phần |       | mềm  |
| ------- | -------- | ---- | ---- | ---- | ------- | ----- | ----- | ---- | ----- | ---- |
| cơ      | bản      |      |      |      |         |       |       |      |       |      |
| ❖ Phân  | biệt     | được | sự   | khác | nhau    | giữa  | các   | mô   | hình; | ưu   |
| và      | nhược    | điểm | của  | từng | mô      | hình  |       |      |       |      |
| ❖ Lựa   | chọn     | được | mô   | hình | phát    | triển | phù   | hợp  | với   | từng |
| loại    | hệ thống |      | phần | mềm  |         |       |       |      |       |      |
Software Engineering 2
tkhuong@dthu.edu.vn

|         | Đặt |       | vấn  |      | đề   |     |      |         |      |       |        |      |      |      |
| ------- | --- | ----- | ---- | ---- | ---- | --- | ---- | ------- | ---- | ----- | ------ | ---- | ---- | ---- |
| ❖ Hãy   |     | cho   | biết |      | để   | tạo |      | ra được |      | một   | sản    | phẩm |      | phần |
| mềm,    |     | người |      | ta   | phải |     | thực | hiện    |      | những | công   |      | việc | nào? |
| ❖ Trình |     | lại   | sơ   | lược |      | quá |      | trình   | tiến | hành  | xây    | dựng |      | phần |
| mềm     |     | từ    | khi  | nhận |      |     | yêu  | cầu     | đến  | khi   | chuyển |      | giao | sản  |
phẩm?
Software Engineering 3
tkhuong@dthu.edu.vn

NỘI DUNG
1 KHÁI NIỆM QUY TRÌNH PHẦN MỀM
2 MÔ HÌNH QUY TRÌNH PHẦN MỀM
43 HOẠT ĐỘNG CỦA QUY TRÌNH PM
34 QL THÍCH NGHI VỚI SỰ THAY ĐỔI
45 QUY TRÌNH RUP
Software Engineering 6
tkhuong@dthu.edu.vn

1. KHÁI NIỆM QUY TRÌNH PM
❖ Quy trình phần mềm(software process) là một tập có cấu trúc
| các  | hoạt  | động         | cần   | thiết để | phát  | triển | một hệ | thống | phần   | mềm.   |
| ---- | ----- | ------------ | ----- | -------- | ----- | ----- | ------ | ----- | ------ | ------ |
| ❖ Có | nhiều | quy          | trình | phần     | mềm   | khác  | nhau.  | Tuy   | nhiên, | tất cả |
| đều  | bao   | gồm          | những | hoạt     | động: |       |        |       |        |        |
| ▪    | Đặc   | tả           |       |          |       |       |        |       |        |        |
| ▪    | Phát  | triển (Thiết | kế    | và cài   | đặt)  |       |        |       |        |        |
| ▪    | Thẩm  | định         |       |          |       |       |        |       |        |        |
| ▪    | Cải   | tiến         |       |          |       |       |        |       |        |        |
Software Engineering 7
tkhuong@dthu.edu.vn

1. KHÁI NIỆM QUY TRÌNH PM
| ❖   | Những |      | hệ  | thống |     | khác | nhau | sẽ  | cần | những |     | quy | trình | phát | triển |
| --- | ----- | ---- | --- | ----- | --- | ---- | ---- | --- | --- | ----- | --- | --- | ----- | ---- | ----- |
|     | khác  | nhau |     |       |     |      |      |     |     |       |     |     |       |      |       |
❖ Ví dụ: hệ thống thời gian thực yêu cầu phải hoàn thành đặc tả
|     | hệ    | thống  |        | trước |       | khi   | chuyển               | sang |       | giai |       | đoạn | xây   | dựng   | nó.   |
| --- | ----- | ------ | ------ | ----- | ----- | ----- | -------------------- | ---- | ----- | ---- | ----- | ---- | ----- | ------ | ----- |
|     | Nhưng |        | với    | hệ    | thống |       | thương               | mại  | điện  |      | tử,   | vừa  | đặc   | tả vừa | xây   |
|     | dựng  |        | chương |       | trình |       | một cách             | đồng |       | thời |       |      |       |        |       |
| ❖   | Tuy   | nhiên, |        | nếu   |       | không | sử                   | dụng | quy   |      | trình | phát | triển | hệ     | thống |
|     | thích |        | hợp    | có    | thể   | làm   | giảm                 | chất | lượng |      | của   | hệ   | thống | và     | tăng  |
|     | chi   | phí    | xây    | dựng. |       |       |                      |      |       |      |       |      |       |        |       |
|     |       |        |        |       |       |       | Software Engineering |      |       |      |       |      |       |        | 8     |
tkhuong@dthu.edu.vn

NỘI DUNG
1 KHÁI NIỆM QUY TRÌNH PHẦN MỀM
2 MÔ HÌNH QUY TRÌNH PHẦN MỀM
43 HOẠT ĐỘNG CỦA QUY TRÌNH PM
34 QL THÍCH NGHI VỚI SỰ THAY ĐỔI
45 QUY TRÌNH RUP
Software Engineering 9
tkhuong@dthu.edu.vn

2. MÔ HÌNH QUY TRÌNH PM
1 2
MÔ TẢ QUY TRÌNH QUY TRÌNH HOẠCH ĐỊNH
PHẦN MỀM SẴN VÀ QT LINH HOẠT
MÔ HÌNH QT PM
4 3
CÁC MÔ HÌNH QUY TRÌNH
Software Engineering 10
tkhuong@dthu.edu.vn

|     |     | 2.1 Mô |     |     | tả  |        | quy |     | trình  |     | phần |     | mềm |     |
| --- | --- | ------ | --- | --- | --- | ------ | --- | --- | ------ | --- | ---- | --- | --- | --- |
| ❖   | Khi | mô     | tả  | về  | quy | trình, |     | ta  | thường |     | nói  | về  |     |     |
▪ Các hoạt động trong những quy trình này. Ví dụ, đặc tả mô hình
|     |     | dữ  | liệu, | thiết  | kế  | giao  | diện |     | người | dùng, | …;   |       |     |     |
| --- | --- | --- | ----- | ------ | --- | ----- | ---- | --- | ----- | ----- | ---- | ----- | --- | --- |
|     | ▪   | Thứ | tự    | của    | các | hoạt  | động |     | này.  |       |      |       |     |     |
| ❖   | Các | mô  |       | tả quy |     | trình | có   | thể | gồm:  |       |      |       |     |     |
|     | ▪   | Sản | phẩm, |        | kết | quả   | đầu  | ra  | của   | một   | hoạt | động; |     |     |
▪ Vai trò, phản ánh trách nhiệm của những người tham gia vào quy
trình;
▪
Điều kiện trước và điều kiện sau (Pre- and post-conditions), là
|     |     | những |     | điều | kiện |     | phải | đảm | bảo  | trước |      | và sau | khi một | hoạt động |
| --- | --- | ----- | --- | ---- | ---- | --- | ---- | --- | ---- | ----- | ---- | ------ | ------- | --------- |
|     |     | được  |     | thực | hiện | hay | một  | sản | phẩm |       | được | tạo    | ra.     |           |
Software Engineering 11
tkhuong@dthu.edu.vn

|     | 2.2 QT hoạch |     |     |     |     |     |     | định |     | sẵn | và  | QT linh |     |     | hoạt |     |
| --- | ------------ | --- | --- | --- | --- | --- | --- | ---- | --- | --- | --- | ------- | --- | --- | ---- | --- |
❖ Các quy trình hoạch định sẵn (plan-driven process) là các quy
|     | trình | mà  | trong   |     | đó      | tất | cả   | các  | hoạt | động |     | được |     | lên kế | hoạch |     |
| --- | ----- | --- | ------- | --- | ------- | --- | ---- | ---- | ---- | ---- | --- | ---- | --- | ------ | ----- | --- |
|     | trước |     | và tiến |     | độ thực |     | hiện | được |      | đánh | giá | dựa  |     | vào kế | hoạch |     |
này.
❖ Trong các quy trình linh hoạt (agile process), kế hoạch được
|     | phát | triển  |     | dần  | dần   | và   | dễ   | dàng  | thay  | đổi |       | quy | trình | để đáp |     | ứng |
| --- | ---- | ------ | --- | ---- | ----- | ---- | ---- | ----- | ----- | --- | ----- | --- | ----- | ------ | --- | --- |
|     | sự   | thay   | đổi | yêu  | cầu   | của  |      | khách | hàng. |     |       |     |       |        |     |     |
| ❖   | Hầu  | hết    | các | quy  | trình |      | thực | tế    | đều   | gồm | những |     | phần  | tử     | của | cả  |
|     | hai  | phương |     | pháp |       | này. |      |       |       |     |       |     |       |        |     |     |
Không có quy trình phần mềm đúng hay sai!
|     |     |     |     |     |     |     | Software Engineering |     |     |     |     |     |     |     |     | 12  |
| --- | --- | --- | --- | --- | --- | --- | -------------------- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
tkhuong@dthu.edu.vn

2.3 Các mô hình quy trình (1)
Mô hình thác nước
Mô hình hoạch định sẵn. Các pha đặc tả và phát triển phân biệt
và tách rời nhau.
Mô hình phát triển tiến hóa
Các pha đặc tả, phát triển và thẩm định đan xen nhau. Có thể là
mô hình hoạch định sẵn, có thể là mô hình linh hoạt.
Kỹ thuật phần mềm hướng tái sử dụng
Hệ thống được xây dựng từ những thành phần có sẵn. Có thể là
hoạch định sẵn, có thể là linh hoạt.
Mô hình xoắn ốc
Các pha vòng lặp có phân tích rủi ro. Có thể là hoạch định sẵn,
có thể là linh hoạt.
Software Engineering 15
tkhuong@dthu.edu.vn

| Mô  | hình | thác | nước | – Waterfall (1) |
| --- | ---- | ---- | ---- | --------------- |
Mô hình thác nước cổ điển
Software Engineering 17
tkhuong@dthu.edu.vn

| Mô  |     | hình |     |     | thác |     |     | nước |     |     | – Waterfall(2) |     |
| --- | --- | ---- | --- | --- | ---- | --- | --- | ---- | --- | --- | -------------- | --- |
❖ Đặc trưng:
| ▪ Các | pha   |     | diễn | ra  | tuần   | tự  | và  | độc | lập  | nhau. |        |       |
| ----- | ----- | --- | ---- | --- | ------ | --- | --- | --- | ---- | ----- | ------ | ----- |
| ▪ Kết | quả   |     | của  | mỗi | pha    | là  | đầu | vào | của  |       | pha kế | tiếp. |
| ▪ Chú | trọng |     | kiểm |     | nghiệm |     | tại | mỗi | pha. |       |        |       |
❖ Ưu điểm:
| ▪ Thực   |       | hiện | có    | hệ  | thống |      | và  | bài  | bản. |     |         |           |
| -------- | ----- | ---- | ----- | --- | ----- | ---- | --- | ---- | ---- | --- | ------- | --------- |
| ▪ Tiên   |       | liệu | chặt  | chẽ | trước |      | khi | làm. |      |     |         |           |
| ❖ Khuyết | điểm: |      |       |     |       |      |     |      |      |     |         |           |
| ▪ Khó    | khăn  |      | trong |     | việc  | thay |     | đổi  | các  | pha | đã được | thực hiện |
| → Chỉ    | thích |      | hợp   | với | dự    | án   | có  | yêu  | cầu  |     | rõ ràng |           |
Rất ít những hệ thống thương mại có yêu cầu ổn định!
Software Engineering 18
tkhuong@dthu.edu.vn

| Mô  | hình | thác | nước | – Waterfall(3) |
| --- | ---- | ---- | ---- | -------------- |
Mô hình thác nước cải tiến
Software Engineering 20
tkhuong@dthu.edu.vn

| Mô  | hình | phát | triển | tiến | hóa |
| --- | ---- | ---- | ----- | ---- | --- |
(Evolutionary development) (1)
Software Engineering 22
tkhuong@dthu.edu.vn

|     |     | Mô  |     | hình | phát |     | triển |     |     | tiến | hóa |     |     |     |     |     |
| --- | --- | --- | --- | ---- | ---- | --- | ----- | --- | --- | ---- | --- | --- | --- | --- | --- | --- |
(Evolutionary development) (2)
| Có  | hai  | phương |     | pháp |     | thực         | hiện: |     |     |              |     |     |     |     |     |     |
| --- | ---- | ------ | --- | ---- | --- | ------------ | ----- | --- | --- | ------------ | --- | --- | --- | --- | --- | --- |
| ❖   | Phát | triển  |     | thăm | dò  | (exploratory |       |     |     | development) |     |     |     |     |     |     |
▪ Làm việc với khách hàng và từng bước phát triển từ bộ yêu cầu
|     |     | được |     | hiểu rõ | và  | bổ  | sung |     | các | tính | năng |     | mới khi | khách | hàng | yêu |
| --- | --- | ---- | --- | ------- | --- | --- | ---- | --- | --- | ---- | ---- | --- | ------- | ----- | ---- | --- |
cầu.
| ❖   | Các | phiên |     | bản | thử | nghiệm |     |     | (throw-away |     |     | prototyping) |     |     |     |     |
| --- | --- | ----- | --- | --- | --- | ------ | --- | --- | ----------- | --- | --- | ------------ | --- | --- | --- | --- |
▪ Để hiểu các yêu cầu hệ thống: bắt đầu từ bộ yêu cầu không được
|     |     | hiểu   | rõ,   | để làm   |     | rõ đâu | là    | cái    | thực   |     | sự được |     | yêu cầu.    |     |     |     |
| --- | --- | ------ | ----- | -------- | --- | ------ | ----- | ------ | ------ | --- | ------- | --- | ----------- | --- | --- | --- |
| ❖   | Đặc | trưng: |       |          |     |        |       |        |        |     |         |     |             |     |     |     |
|     | ▪   | Phát   | triển | nhanh    |     | các    | phiên |        | bản    | thử | nghiệm  |     | (prototype) |     |     |     |
|     | ▪   | Nhận   |       | phản hồi |     | khách  | hàng  |        | thường |     | xuyên.  |     |             |     |     |     |
|     | ▪   | Không  |       | đặt nặng |     | tiên   | liệu  | trước. |        |     |         |     |             |     |     |     |
▪
|     |     | Cải | tiến | dần | phiên |     | bản | thử                  | nghiệm |     | thành | bản | chính | thức. |     |     |
| --- | --- | --- | ---- | --- | ----- | --- | --- | -------------------- | ------ | --- | ----- | --- | ----- | ----- | --- | --- |
|     |     |     |      |     |       |     |     | Software Engineering |        |     |       |     |       |       |     | 23  |
tkhuong@dthu.edu.vn

| Mô  | hình |     | phát |     |     | triển |     | tiến | hóa |     |     |
| --- | ---- | --- | ---- | --- | --- | ----- | --- | ---- | --- | --- | --- |
(Evolutionary development) (3)
❖ Ưu điểm:
| ▪ Yêu       | cầu   | ban   | đầu   | không |      | cần   | rõ   | ràng     | và    | ổn định. |       |
| ----------- | ----- | ----- | ----- | ----- | ---- | ----- | ---- | -------- | ----- | -------- | ----- |
| ▪ Thích     | ứng   | tốt   | với   | thay  |      | đổi.  |      |          |       |          |       |
| ❖ Khuyết    | điểm: |       |       |       |      |       |      |          |       |          |       |
| ▪ Tính      | quy   | trình | không |       | thể  | hiện  |      | rõ ràng  |       |          |       |
| ▪ Cấu       | trúc  | hệ    | thống | bị    | giảm | khi   |      | có yêu   | cầu   | thay     | đổi   |
| ❖ Ứng dụng: |       |       |       |       |      |       |      |          |       |          |       |
| ▪ Các       | hệ    | thống | kích  | thước |      | nhỏ   |      | và trung | bình; |          |       |
| ▪ Một       | phần  | của   | hệ    | thống |      | lớn   | (vd: | giao     | diện  | người    | dùng) |
| ▪ Các       | hệ    | thống | chỉ   | dùng  |      | trong | thời | gian     | ngắn. |          |       |
Software Engineering 24
tkhuong@dthu.edu.vn

CNPM HƯỚNG TÁI SỬ DỤNG - Reuse-
oriented software engineering (1)
Software Engineering 25
tkhuong@dthu.edu.vn

|     | CNPM HƯỚNG TÁI SỬ DỤNG - |     |     |     |     |     |     |     | Reuse- |     |     |
| --- | ------------------------ | --- | --- | --- | --- | --- | --- | --- | ------ | --- | --- |
oriented software engineering (2)
| ❖ Dựa | vào   | việc     | tái     | sử    | dụng một                    | cách     | có    | hệ thống |      |        |      |
| ----- | ----- | -------- | ------- | ----- | --------------------------- | -------- | ----- | -------- | ---- | ------ | ---- |
| ▪     | Các   | hệ thống |         | được  | tích hợp                    | từ những |       | thành    | phần | có sẵn | hoặc |
|       | từ    | các hệ   | thống   | COTS  | (Commercial-off-the-shelf). |          |       |          |      |        |      |
| ❖ Các | pha   | trong    | quy     | trình |                             |          |       |          |      |        |      |
| ▪     | Phân  | tích     | thành   | phần  | sẵn có                      |          |       |          |      |        |      |
| ▪     | Điều  | chỉnh    | yêu     | cầu;  |                             |          |       |          |      |        |      |
| ▪     | Thiết | kế hệ    | thống   | với   | kỹ thuật                    | tái sử   | dụng; |          |      |        |      |
| ▪     | Phát  | triển    | và tích | hợp   | hệ thống                    |          |       |          |      |        |      |
Hiện nay, việc tái sử dụng là phương pháp chuẩn cho việc
xây dựng nhiều loại hệ thống thương mại.
|     |     |     |     |     | Software Engineering |     |     |     |     |     | 26  |
| --- | --- | --- | --- | --- | -------------------- | --- | --- | --- | --- | --- | --- |
tkhuong@dthu.edu.vn

|     | Mô   | hình  | tăng |      | dần  |      | (Incremental delivery) (1) |       |        |       |      |       |     |      |      |     |     |
| --- | ---- | ----- | ---- | ---- | ---- | ---- | -------------------------- | ----- | ------ | ----- | ---- | ----- | --- | ---- | ---- | --- | --- |
| ❖   | Hệ   | thống | sẽ   | được |      | chia |                            | thành |        | nhiều |      | vòng, |     |      | tăng | dần |     |
|     | thay | gì    | phải | xây  | dựng |      |                            | và    | chuyển |       | giao |       | một |      | lần. | Mỗi |     |
|     | vòng | là    | một  | kết  | quả  |      | của                        |       | một    | chức  |      | năng  |     | được |      | yêu |     |
cầu
| ❖   | Yêu   | cầu   | nào | có   | thứ |                      | tự  | ưu    | tiên |     | càng | cao |     | thì | càng |     | ở   |
| --- | ----- | ----- | --- | ---- | --- | -------------------- | --- | ----- | ---- | --- | ---- | --- | --- | --- | ---- | --- | --- |
|     | trong | những |     | vòng |     | phát                 |     | triển | sớm  |     | hơn  |     |     |     |      |     |     |
|     |       |       |     |      |     | Software Engineering |     |       |      |     |      |     |     |     |      |     | 30  |
tkhuong@dthu.edu.vn

| Mô  | hình | tăng | dần | (Incremental delivery) (2) |
| --- | ---- | ---- | --- | -------------------------- |
Software Engineering 31
tkhuong@dthu.edu.vn

| Mô   | hình  |       | tăng |       |      | dần   | (Incremental delivery) (3) |      |     |      |          |         |       |
| ---- | ----- | ----- | ---- | ----- | ---- | ----- | -------------------------- | ---- | --- | ---- | -------- | ------- | ----- |
| ❖ Ưu | điểm: |       |      |       |      |       |                            |      |     |      |          |         |       |
| ▪    | Khách |       | hàng |       | sớm  |       | thấy                       | được |     | chức | năng     | của hệ  | thống |
|      | sau   | mỗi   |      | lần   | tăng | vòng. |                            |      |     |      |          |         |       |
| ▪    | Các   | vòng  |      | trước |      | sẽ    | là                         | mẫu  | thử | để   | tìm hiểu | các yêu | cầu   |
|      | cho   | những |      |       | vòng | tiếp  | theo.                      |      |     |      |          |         |       |
| ▪    | Những |       | chức |       | năng |       | có                         | độ   | ưu  | tiên | càng     | cao sẽ  | được  |
|      | kiểm  |       | thử  | càng  |      | kỹ    |                            |      |     |      |          |         |       |
Software Engineering 32
tkhuong@dthu.edu.vn

| Mô  | hình | xoắn | ốc  | - Spiral development (1) |
| --- | ---- | ---- | --- | ------------------------ |
Software Engineering 34
tkhuong@dthu.edu.vn

|     |     | Mô   |       | hình      |      | xoắn |       | ốc    |      | - Spiral development (2) |        |      |      |      |      |           |     |
| --- | --- | ---- | ----- | --------- | ---- | ---- | ----- | ----- | ---- | ------------------------ | ------ | ---- | ---- | ---- | ---- | --------- | --- |
| ❖   | Các |      | pha   | trong     |      | quy  |       | trình | phát |                          | triển  | xoắn |      | ốc:  |      |           |     |
|     | ▪   | Lập  |       | kế hoạch: |      |      | xác   | định  |      | mục                      | tiêu,  | các  |      | giải | pháp | và        | các |
|     |     | ràng |       | buộc      |      |      |       |       |      |                          |        |      |      |      |      |           |     |
|     | ▪   | Phân |       | tích      | rủi  | ro:  | phân  |       | tích | các                      | phương |      |      | án   | và   | xác định/ |     |
|     |     | giải |       | quyết     | rủi  | ro   |       |       |      |                          |        |      |      |      |      |           |     |
|     | ▪   | Kỹ   | nghệ: |           | phát |      | triển | sản   |      | phẩm                     | mức    |      | tiếp | theo |      |           |     |
|     | ▪   | Đánh |       | giá:      | đánh |      | giá   | của   |      | khách                    | hàng   |      | về   | kết  | quả  | của       | kỹ  |
nghệ
|     |     |     |     |     |     |     |     | Software Engineering |     |     |     |     |     |     |     |     | 35  |
| --- | --- | --- | --- | --- | --- | --- | --- | -------------------- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
tkhuong@dthu.edu.vn

|     | Mô  | hình |     | xoắn |     | ốc  |     | - Spiral development (3) |     |     |     |     |     |     |     |     |
| --- | --- | ---- | --- | ---- | --- | --- | --- | ------------------------ | --- | --- | --- | --- | --- | --- | --- | --- |
❖ Ưu điểm
| ▪   | Hiểu | rõ   | và  | giải quyết |     | tốt   | các |     | nguy | cơ   | tại | mỗi   | mức |     | tiến   | hóa |
| --- | ---- | ---- | --- | ---------- | --- | ----- | --- | --- | ---- | ---- | --- | ----- | --- | --- | ------ | --- |
| ▪   | Áp   | dụng | bản | mẫu        |     | tại   | bất | cứ  | giai | đoạn |     | tiến  | hóa | nào |        |     |
| ▪   | Giảm | được |     | nguy       | cơ  | trước |     |     | khi  | nó   | trở | thành | vấn |     | đề của | hệ  |
thống
| ❖ Khuyết |      | điểm   |       |          |       |                      |      |      |       |       |       |          |     |     |          |        |
| -------- | ---- | ------ | ----- | -------- | ----- | -------------------- | ---- | ---- | ----- | ----- | ----- | -------- | --- | --- | -------- | ------ |
| ▪        | Khó  | thuyết |       | phục     | khách |                      | hàng |      | rằng  |       | cách  | tiếp     | cận |     | tiến hóa | là     |
|          | kiểm | soát   | được. |          |       |                      |      |      |       |       |       |          |     |     |          |        |
| ▪        | Cần  | tri    | thức  | chuyên   |       | gia                  |      | đánh |       | giá   | rủi   | ro chính |     | xác | và       | dựa    |
|          | trên | chuyên |       | gia      | để    | đạt                  | được |      | thành |       | công. |          |     |     |          |        |
| ▪        | Cần  | năng   |       | lực quản |       | lý                   | cao, |      | nếu   | không |       | quản     | lý  | tốt | sẽ       | dễ rơi |
|          | vào  | trạng  | thái  | sửa      |       | đổi                  | cục  | bộ   | không |       | kế    | hoạch    |     |     |          |        |
|          |      |        |       |          |       | Software Engineering |      |      |       |       |       |          |     |     |          | 36     |
tkhuong@dthu.edu.vn

NỘI DUNG
1 KHÁI NIỆM QUY TRÌNH PHẦN MỀM
2 MÔ HÌNH QUY TRÌNH PHẦN MỀM
43 HOẠT ĐỘNG CỦA QUY TRÌNH PM
34 QL THÍCH NGHI VỚI SỰ THAY ĐỔI
45 QUY TRÌNH RUP
Software Engineering 37
tkhuong@dthu.edu.vn

3. HOẠT ĐỘNG QUY TRÌNH PM
ĐẶC TẢ
CẢI TIẾN PHÁT TRIỂN
THẨM ĐỊNH
❖ Trong mô hình thác nước, chúng được tổ chức tuần tự
❖ Trong mô hình phát triển tiến hóa chúng được tổ chức đan xen
Software Engineering 38
tkhuong@dthu.edu.vn

3. HOẠT ĐỘNG QUY TRÌNH PM
| ❖ Mục  | tiêu: |       |       |       |      |      |                      |         |      |      |        |       |       |
| ------ | ----- | ----- | ----- | ----- | ---- | ---- | -------------------- | ------- | ---- | ---- | ------ | ----- | ----- |
| ▪ Xác  | định  |       | rõ    | những |      |      | công                 | việc    | cần  | phải | làm    | trong | quy   |
| trình  | phát  |       | triển |       | phần |      | mềm                  |         |      |      |        |       |       |
| ▪ Từng |       | công  |       | việc  |      | đó   | được                 | thực    | hiện | cụ   | thể ra | sao   |       |
| → Xây  |       | dựng  |       | bất   | kỳ   | phần |                      | mềm     | nào  | cũng | phải   | thực  | hiện  |
| 4 công |       | việc, |       | nhưng |      | việc |                      | sử dụng | các  | mô   | hình   | phát  | triển |
| phần   | mềm   |       | khác  |       | nhau |      | thì                  | trình   | tự   | thực | hiện   | các   | công  |
| việc   | trên  | cũng  |       | khác  |      | nhau |                      |         |      |      |        |       |       |
|        |       |       |       |       |      |      | Software Engineering |         |      |      |        |       | 39    |
tkhuong@dthu.edu.vn

|       | Đặt | vấn  |       | đề  |      |        |     |         |      |       |
| ----- | --- | ---- | ----- | --- | ---- | ------ | --- | ------- | ---- | ----- |
| ❖Công |     | việc |       | đầu | tiên | cần    | làm | trong   | quá  | trình |
| xây   |     | dựng | phần  |     | mềm  | là gì? |     |         |      |       |
| ❖Tầm  |     | quan | trọng |     | của  | việc   | đặc | tả phần | mềm? |       |
Software Engineering 40
tkhuong@dthu.edu.vn

|     |      | 3.1 Đặc  |       |     | tả     | phần |      | mềm  |              | (1)       |      |              |
| --- | ---- | -------- | ----- | --- | ------ | ---- | ---- | ---- | ------------ | --------- | ---- | ------------ |
| ❖   | Là   | quy      | trình | tìm |        | hiểu | và   | định | nghĩa        | những     | dịch | vụ nào       |
|     | được | yêu      | cầu   |     | và     | các  | ràng | buộc | trong        | quá trình |      | vận hành     |
|     | và   | xây dựng |       | hệ  | thống. |      |      |      |              |           |      |              |
| ❖   | Quy  | trình    | xác   |     | định   | yêu  | cầu: |      |              |           |      |              |
|     |      |          |       |     |        |      |      |      | Text in here |           |      | Text in here |
Requirements
|     | Feasibility study |     |     |     |     |     |     |     | Requirements  |     | Requirements |     |
| --- | ----------------- | --- | --- | --- | --- | --- | --- | --- | ------------- | --- | ------------ | --- |
elicitation and
|     |     |     |     |     |     |     |     |     | specificatio |     |     |  validation |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | ------------ | --- | --- | ----------- |
analysis
• Nghiên cứu khả thi: • Thu thập và phân tích  • Đặc tả yêu cầu:  • Thẩm định yêu cầu:
yêu cầu:
• Ước lượng xem những  •Định nghĩa chi tiết các  • Kiểm tra tính hợp lệ của
yêu cầu của người dùng  • Các stackholder hệ  yêu cầu.  yêu cầu.
| có khả thi về mặt kỹ       |     |     |     |     | thống yêu cầu và mong  |     |     |     |     |     |     |     |
| -------------------------- | --- | --- | --- | --- | ---------------------- | --- | --- | --- | --- | --- | --- | --- |
| thuật và tài chính để xây  |     |     |     |     | muốn gì từ hệ thống?   |     |     |     |     |     |     |     |
dựng nên hệ thống hay
không
Software Engineering 41
tkhuong@dthu.edu.vn

| 3.1 Đặc | tả phần | mềm | (2) |
| ------- | ------- | --- | --- |
Quy trình xác định yêu cầu
Software Engineering 43
tkhuong@dthu.edu.vn

|       | Đặt    | vấn  | đề   |       |         |          |          |      |      |     |
| ----- | ------ | ---- | ---- | ----- | ------- | -------- | -------- | ---- | ---- | --- |
| ❖ Bỏ  | qua    | giai | đoạn | thiết | kế, sau | khi đặc  | tả và    | phân | tích |     |
| yêu   | cầu,   | có   | thể  | thực  | hiện    | cài đặt  | hệ thống |      | ngay |     |
| được  | không? |      |      |       |         |          |          |      |      |     |
| ❖ Vai | trò    | của  | bản  | thiết | kế đối  | với giai | đoạn     | cài  | đặt  | là  |
gì?
|     |     |     |     |     | Software Engineering |     |     |     |     | 44  |
| --- | --- | --- | --- | --- | -------------------- | --- | --- | --- | --- | --- |
tkhuong@dthu.edu.vn

|     |       | 3.2 Thiết |      |     |     | kế  | và        | cài |         | đặt | phần |     | mềm |     | (1) |
| --- | ----- | --------- | ---- | --- | --- | --- | --------- | --- | ------- | --- | ---- | --- | --- | --- | --- |
| ❖   | Thiết | kế        | phần |     |     | mềm | (software |     | design) |     |      |     |     |     |     |
▪
|     |     | Là    | quá              | trình |       | thiết     |       | kế cấu               | trúc     | của   | phần |     | mềm   | dựa | trên |
| --- | --- | ----- | ---------------- | ----- | ----- | --------- | ----- | -------------------- | -------- | ----- | ---- | --- | ----- | --- | ---- |
|     |     | những |                  | tài   | liệu  | đặc       | tả.   |                      |          |       |      |     |       |     |      |
|     | ▪   | Hoạt  | động             |       | thiết | kế        | gồm:  |                      |          |       |      |     |       |     |      |
|     |     | •     | Thiết            | kế    | kiến  | trúc      |       |                      |          |       |      |     |       |     |      |
|     |     | •     | Thiết            | kế    | giao  | diện      |       |                      |          |       |      |     |       |     |      |
|     |     | •     | Thiết            | kế    | xử    | lý (thuật |       | toán)                |          |       |      |     |       |     |      |
|     |     | •     | Thiết            | kế    | lưu   | trữ       | (cấu  | trúc                 | dữ liệu) |       |      |     |       |     |      |
| ❖   | Cài | đặt   | (implementation) |       |       |           |       |                      |          |       |      |     |       |     |      |
|     | ▪   | Dịch  | cấu              |       | trúc  | đó        | thành | chương               |          | trình | thực | thi | được. |     |      |
|     |     |       |                  |       |       |           |       | Software Engineering |          |       |      |     |       |     | 45   |
tkhuong@dthu.edu.vn

| 3.2 Thiết | kế và | cài | đặt | phần | mềm | (2) |
| --------- | ----- | --- | --- | ---- | --- | --- |
Mô hình chung của quy trình thiết kế
|     | Software Engineering |     |     |     |     | 47  |
| --- | -------------------- | --- | --- | --- | --- | --- |
tkhuong@dthu.edu.vn

|       | Đặt     | vấn     | đề      |                      |        |        |            |      |
| ----- | ------- | ------- | ------- | -------------------- | ------ | ------ | ---------- | ---- |
| ❖ Sau | khi     | cài đặt | phần    | mềm,                 | chúng  | ta có  | thể chuyển | giao |
| ngay  | cho     | người   | sử dụng | được                 | không? |        |            |      |
| ❖ Vai | trò của | việc    | đánh    | giá phần             | mềm    | là gì? |            |      |
|       |         |         |         | Software Engineering |        |        |            | 49   |
tkhuong@dthu.edu.vn

|     | 3.3 Thẩm |     |     |     | định |     | phần |     | mềm | (1)  |     |
| --- | -------- | --- | --- | --- | ---- | --- | ---- | --- | --- | ---- | --- |
❖ Xác minh (verification) và thẩm định (validation) (V & V) nhằm
| mục |      | đích | chỉ   | ra rằng |      |      |       |        |         |     |     |
| --- | ---- | ---- | ----- | ------- | ---- | ---- | ----- | ------ | ------- | --- | --- |
| ▪   | Một  | hệ   | thống | đã      | thực | hiện | theo  | đặc tả | của nó; |     |     |
| ▪   | Thỏa |      | mãn   | mọi yêu | cầu  | của  | khách | hàng.  |         |     |     |
❖
| Bao   |     | gồm     | các | quy       | trình | kiểm |     | tra, xem | xét lại | và kiểm | thử hệ |
| ----- | --- | ------- | --- | --------- | ----- | ---- | --- | -------- | ------- | ------- | ------ |
| thống |     | (system |     | testing). |       |      |     |          |         |         |        |
Software Engineering 50
tkhuong@dthu.edu.vn

| 3.3 Thẩm | định | phần | mềm | (2)  |
| -------- | ---- | ---- | --- | ---- |
Quy trình kiểm thử
Software Engineering 52
tkhuong@dthu.edu.vn

|       | Đặt  | vấn    | đề       |        |          |           |         |         |
| ----- | ---- | ------ | -------- | ------ | -------- | --------- | ------- | ------- |
| ❖ Sau | khi  | chuyển | giao     | phần   | mềm      | cho khách | hàng,   | thì mọi |
| công  | việc | đã     | kết thúc | chưa?  |          |           |         |         |
| ❖ Cải | tiến | phần   | mềm      | để làm | gì?      |           |         |         |
| ❖ Tại | sao  | không  | xây      | dựng   | hệ thống | mới mà    | lại cải | tiến hệ |
| thống | cũ?  |        |          |        |          |           |         |         |
Software Engineering 54
tkhuong@dthu.edu.vn

|     |       | 3.4 Cải |        |     | tiến   |     |       | phần                 |          | mềm |      |      | (1)  |        |     |      |
| --- | ----- | ------- | ------ | --- | ------ | --- | ----- | -------------------- | -------- | --- | ---- | ---- | ---- | ------ | --- | ---- |
| ❖   | Khi   | các     | yêu    |     | cầu    | hệ  | thống |                      | thay     | đổi |      | theo | sự   | thay   | đổi | của  |
|     | các   | yêu     | cầu    |     | nghiệp |     | vụ    | thì                  | phần     | mềm |      | phải | cải  | tiến   | và  | thay |
|     | đổi   | để      | hỗ     | trợ | khách  |     | hàng. |                      |          |     |      |      |      |        |     |      |
| ❖   | Thông |         | thường |     | chi    |     | phí   | để                   | bảo      | trì | và   | cải  | tiến | thường |     | đắt  |
|     | hơn   | nhiều   |        | so  | với    | chi | phí   |                      | xây dựng |     | phần |      | mềm. |        |     |      |
|     |       |         |        |     |        |     |       | Software Engineering |          |     |      |      |      |        |     | 55   |
tkhuong@dthu.edu.vn

| 3.4 Cải | tiến | phần | mềm | (2) |
| ------- | ---- | ---- | --- | --- |
Quy trình cải tiến hệ thống
Software Engineering 56
tkhuong@dthu.edu.vn

|     |     | Tổng |     |     | kết | (1) |     |     |     |     |     |     |     |     |     |
| --- | --- | ---- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
❖ Quy trình phần mềm là một tập có cấu trúc các hoạt động cần
|     | thiết |      | để     | phát | triển | một   | hệ thống             | phần |      | mềm.  |      |       |      |      |     |
| --- | ----- | ---- | ------ | ---- | ----- | ----- | -------------------- | ---- | ---- | ----- | ---- | ----- | ---- | ---- | --- |
| ❖   | Mô    | hình |        | quy  | trình | phần  | mềm                  | là   | biểu | diễn  | trừu | tượng |      | của  | một |
|     | quy   |      | trình. |      |       |       |                      |      |      |       |      |       |      |      |     |
| ❖   | Các   |      | mô     | hình | quy   | trình | tổng                 | quát | mô   | tả    | tổ   | chức  | của  | các  | quy |
|     | trình |      | phần   | mềm. |       |       |                      |      |      |       |      |       |      |      |     |
|     | ▪     | Ví   | dụ:    | Mô   | hình  | thác  | nước,                | mô   | hình |       | phát | triển | tiến | hóa, | mô  |
|     |       | hình |        | phát | triển | theo  | hướng                | tái  | sử   | dụng. |      |       |      |      |     |
|     |       |      |        |      |       |       | Software Engineering |      |      |       |      |       |      |      | 59  |
tkhuong@dthu.edu.vn

|     | Tổng |     |     | kết | (2) |     |     |     |     |     |     |     |
| --- | ---- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
❖
| Công |     | nghệ | yêu | cầu | là quy | trình | phát | triển | đặc | tả phần | mềm. |     |
| ---- | --- | ---- | --- | --- | ------ | ----- | ---- | ----- | --- | ------- | ---- | --- |
❖ Quy trình thiết kế và cài đặt liên quan đến việc chuyển đổi một
| đặc | tả  | yêu | cầu | thành | hệ  | thống | phần | mềm | chạy | được. |     |     |
| --- | --- | --- | --- | ----- | --- | ----- | ---- | --- | ---- | ----- | --- | --- |
❖ Thẩm định phần mềm là quy trình kiểm tra rằng hệ thống thỏa
| mãn   |      | đặc       | tả và | đáp | ứng                  | được | nhu     | cầu  | thực | của      | người | sử  |
| ----- | ---- | --------- | ----- | --- | -------------------- | ---- | ------- | ---- | ---- | -------- | ----- | --- |
| dụng  |      | hệ thống. |       |     |                      |      |         |      |      |          |       |     |
| ❖ Cải | tiến | phần      |       | mềm | xảy                  | ra   | khi bạn | thay | đổi  | hệ thống | phần  |     |
| mềm   |      | có sẵn    | để    | đáp | ứng                  | các  | yêu cầu | mới. |      |          |       |     |
|       |      |           |       |     | Software Engineering |      |         |      |      |          |       | 60  |
tkhuong@dthu.edu.vn

NỘI DUNG
1 KHÁI NIỆM QUY TRÌNH PHẦN MỀM
2 MÔ HÌNH QUY TRÌNH PHẦN MỀM
43 HOẠT ĐỘNG CỦA QUY TRÌNH PM
34 QL THÍCH NGHI VỚI SỰ THAY ĐỔI
45 QUY TRÌNH RUP
Software Engineering 61
tkhuong@dthu.edu.vn

4. THÍCH NGHI VỚI SỰ THAY ĐỔI
| ❖   | Sự  | thay | đổi | là điều | hiển |     | nhiên | trong | những | dự  | án phần | mềm |
| --- | --- | ---- | --- | ------- | ---- | --- | ----- | ----- | ----- | --- | ------- | --- |
lớn
▪ Những thay đổi thương mại dẫn đến việc thay đổi yêu cầu hoặc
|     | phát   |     | sinh | những    | yêu  | cầu    | mới. |         |            |     |      |     |
| --- | ------ | --- | ---- | -------- | ---- | ------ | ---- | ------- | ---------- | --- | ---- | --- |
|     | ▪ Công |     | nghệ | mới      | mở   | ra khả | năng | cải     | thiện việc | cài | đặt. |     |
|     | ▪ Thay |     | đổi  | platform | đòi  | hỏi    | thay | đổi ứng | dụng.      |     |      |     |
| ❖   | Thay   | đổi | dẫn  | đến      | việc | làm    | lại  |         |            |     |      |     |
▪ Vì vậy chi phí của việc thay đổi gồm cả chi phí làm lại và chi phí
|     | cài | đặt | tính | năng | mới. |     |                      |     |     |     |     |     |
| --- | --- | --- | ---- | ---- | ---- | --- | -------------------- | --- | --- | --- | --- | --- |
|     |     |     |      |      |      |     | Software Engineering |     |     |     |     | 62  |
tkhuong@dthu.edu.vn

|     | Giảm  |       |      | thiểu   |     | chi phí    |          | làm  | lại |       |     |         |
| --- | ----- | ----- | ---- | ------- | --- | ---------- | -------- | ---- | --- | ----- | --- | ------- |
| ❖   | Tránh | thay  | đổi  | (change |     | avoidance) |          |      |     |       |     |         |
|     | ▪ Quy | trình | phần | mềm     |     | gồm        | các hoạt | động | mà  | nó có | thể | dự đoán |
trước những thay đổi có thể xảy ra khi việc làm lại được yêu cầu.
▪ Ví dụ: hệ thống nguyên mẫu (prototype system) có thể dùng để
|     | cho  | khách |      | hàng | xem     | những | tính năng  | chính | của | hệ  | thống. |     |
| --- | ---- | ----- | ---- | ---- | ------- | ----- | ---------- | ----- | --- | --- | ------ | --- |
| ❖   | Chấp | nhận  | thay | đổi  | (change |       | tolerance) |       |     |     |        |     |
▪ Quy trình được thiết kế sao cho thay đổi được thực hiện với chi
|     | phí      | khá | thấp. |      |     |      |        |      |      |     |              |     |
| --- | -------- | --- | ----- | ---- | --- | ---- | ------ | ---- | ---- | --- | ------------ | --- |
|     | ▪ Thường |     | sử    | dụng | mô  | hình | chuyển | giao | tăng | dần | (incremental |     |
delivery).
Software Engineering 63
tkhuong@dthu.edu.vn

|     | 4.1 Nguyên |     |     |     | mẫu |     | phần |     | mềm |     | (prototype) |     |     |
| --- | ---------- | --- | --- | --- | --- | --- | ---- | --- | --- | --- | ----------- | --- | --- |
❖ Một nguyên mẫu (prototype) là phiên bản đầu tiên của một hệ
| thống |     | được  | dùng |     | để demo |     | những |     | khái | niệm | và thử | các | tùy |
| ----- | --- | ----- | ---- | --- | ------- | --- | ----- | --- | ---- | ---- | ------ | --- | --- |
| chọn  |     | thiết | kế.  |     |         |     |       |     |      |      |        |     |     |
❖
| Một |     | nguyên | mẫu | có  | thể | được |     | sử  | dụng | trong | các trường |     | hợp |
| --- | --- | ------ | --- | --- | --- | ---- | --- | --- | ---- | ----- | ---------- | --- | --- |
sau:
▪ Trong quy trình công nghệ yêu cầu để giúp cho quá trình thu thập
|     | yêu | cầu | và thẩm |     | định | yêu | cầu; |     |     |     |     |     |     |
| --- | --- | --- | ------- | --- | ---- | --- | ---- | --- | --- | --- | --- | --- | --- |
▪ Trong quy trình thiết kế để tìm ra các tùy chọn và phát triển thiết
|     | kế    | giao | diện người |      | dùng; |                      |         |     |      |     |     |     |     |
| --- | ----- | ---- | ---------- | ---- | ----- | -------------------- | ------- | --- | ---- | --- | --- | --- | --- |
| ▪   | Trong |      | quy trình  | kiểm | thử   |                      | để chạy | các | kiểm | thử |     |     |     |
|     |       |      |            |      |       | Software Engineering |         |     |      |     |     |     | 64  |
tkhuong@dthu.edu.vn

|     | 3.1 Nguyên |      |       |        |       | mẫu  |         | phần |           | mềm       | (prototype) |
| --- | ---------- | ---- | ----- | ------ | ----- | ---- | ------- | ---- | --------- | --------- | ----------- |
| ❖   | Lợi        | ích  | của   | nguyên |       | mẫu: |         |      |           |           |             |
|     | ▪          | Cải  | thiện | khả    | năng  |      | sử dụng |      | hệ        | thống.    |             |
|     | ▪          | Thoả | mãn   | tốt    | hơn   | nhu  |         | cầu  | thực      | của người | dùng.       |
|     | ▪          | Cải  | thiện | chất   | lượng |      | thiết   | kế.  |           |           |             |
|     | ▪          | Cải  | thiện | khả    | năng  |      | bảo     | trì  | hệ thống. |           |             |
|     | ▪          | Giảm | bớt   | nỗ     | lực   | phát | triển.  |      |           |           |             |
Software Engineering 65
tkhuong@dthu.edu.vn

|     | 3.1 Nguyên |          |        |       |       | mẫu  |      | phần    |        | mềm     |      | (prototype) |      |      |         |
| --- | ---------- | -------- | ------ | ----- | ----- | ---- | ---- | ------- | ------ | ------- | ---- | ----------- | ---- | ---- | ------- |
| ❖   | Phát       | triển    | nguyên |       |       | mẫu: |      |         |        |         |      |             |      |      |         |
|     | ▪          | Có thể   | dựa    |       | vào   |      | các  | công    | cụ     | và ngôn |      | ngữ         | để   | phát | triển   |
|     |            | nguyên   | mẫu.   |       |       |      |      |         |        |         |      |             |      |      |         |
|     | ▪          | Có thể   | bao    | gồm   |       | cả   | việc | loại    | bỏ     | bớt     | tính | năng        |      |      |         |
|     |            | • Nguyên |        | bản   |       | nên  | tập  | trung   | vào    | những   |      | tính        | năng | chưa | được    |
|     |            | hiểu     | rõ     | ràng; |       |      |      |         |        |         |      |             |      |      |         |
|     |            | • Kiểm   | tra    | lỗi   | không |      | nằm  | trong   | nguyên |         | mẫu; |             |      |      |         |
|     |            | • Tập    | trung  |       | vào   | các  |      | yêu cầu | chức   | năng    | hơn  | là          | các  | yêu  | cầu phi |
|     |            | chức     | năng.  |       |       |      |      |         |        |         |      |             |      |      |         |
Software Engineering 66
tkhuong@dthu.edu.vn

|     | 3.1 Nguyên |     |          |     |     | mẫu   |     |      | phần |     | mềm |     |     | (prototype) |       |       |      |
| --- | ---------- | --- | -------- | --- | --- | ----- | --- | ---- | ---- | --- | --- | --- | --- | ----------- | ----- | ----- | ---- |
| ❖   | Loại       | bỏ  | nguyên   |     | mẫu |       |     |      |      |     |     |     |     |             |       |       |      |
|     | ▪          | Các | nguyên   |     | mẫu |       | nên | bị   | loại | bỏ  |     | sau | khi | phát        | triển |       | phần |
|     |            | mềm | vì chúng |     |     | không |     | phải | là   | cái | cơ  | bản |     | để phát     |       | triển | hệ   |
thống:
|     |     | •   | Khó có     | thể    | điều  | chỉnh  |                      | hệ     | thống |      | để  | đáp  | ứng  | được    | các | yêu    | cầu   |
| --- | --- | --- | ---------- | ------ | ----- | ------ | -------------------- | ------ | ----- | ---- | --- | ---- | ---- | ------- | --- | ------ | ----- |
|     |     |     | phi chức   |        | năng; |        |                      |        |       |      |     |      |      |         |     |        |       |
|     |     | •   | Nguyên     | mẫu    |       | thường |                      | không  |       | được | tài | liệu | hóa; |         |     |        |       |
|     |     | •   | Cấu trúc   | nguyên |       |        | mẫu                  | thường |       | bị   | phá | vỡ   | do   | bị thay | đổi | nhanh; |       |
|     |     | •   | Nguyên     | mẫu    |       | có     | thể                  | không  |       | đáp  | ứng | được |      | những   |     | tiêu   | chuẩn |
|     |     |     | chất lượng |        | về    | mặt    | tổ                   | chức.  |       |      |     |      |      |         |     |        |       |
|     |     |     |            |        |       |        | Software Engineering |        |       |      |     |      |      |         |     |        | 67    |
tkhuong@dthu.edu.vn

|     |     | 3.2 Chuyển |     |     |     |     | giao |     | tăng |     | dần |     | (nhắc |     |     | lại) |     |
| --- | --- | ---------- | --- | --- | --- | --- | ---- | --- | ---- | --- | --- | --- | ----- | --- | --- | ---- | --- |
❖ Thay vì phân phối hệ thống một lần, việc phát triển và phân
|     | phối  |     | được | chia  |     | ra    | thành |      | từng | phần |     | nhỏ   | (increment). |     |       |     | Mỗi phần  |
| --- | ----- | --- | ---- | ----- | --- | ----- | ----- | ---- | ---- | ---- | --- | ----- | ------------ | --- | ----- | --- | --------- |
|     | giao  |     | cho  | khách |     | hàng  |       | chứa | một  | phần |     | tính  | năng         |     | được  |     | yêu cầu.  |
| ❖   | Những |     |      | yêu   | cầu | người |       | dùng |      | được |     | ưu    | tiên         | và  | những |     | yêu cầu   |
|     | có    | độ  | ưu   | tiên  | cao |       | nhất  | sẽ   | được |      | đặt | trong | các          |     | phần  |     | đầu tiên. |
❖ Trong quá trình phát triển, việc phân tích yêu cầu cho phần
|     | tiếp |     | theo | có  | thể   | được |      | tiến |      | hành | nhưng |     | thay |     | đổi | yêu | cầu cho |
| --- | ---- | --- | ---- | --- | ----- | ---- | ---- | ---- | ---- | ---- | ----- | --- | ---- | --- | --- | --- | ------- |
|     | phần |     | hiện | tại | không |      | được |      | chấp |      | nhận. |     |      |     |     |     |         |
Software Engineering 68
tkhuong@dthu.edu.vn

|     | 3.2 Chuyển |       |     |     |     | giao |     | tăng | dần |     | (nhắc | lại) |     |
| --- | ---------- | ----- | --- | --- | --- | ---- | --- | ---- | --- | --- | ----- | ---- | --- |
| ❖   | Phát       | triển |     | dần | dần |      |     |      |     |     |       |      |     |
▪ Phát triển từng phần hệ thống và đánh giá mỗi phần trước khi
|     |     | tiến | hành | phát | triển |      | phần | tiếp theo; |      |      |            |          |       |
| --- | --- | ---- | ---- | ---- | ----- | ---- | ---- | ---------- | ---- | ---- | ---------- | -------- | ----- |
|     | ▪   | Được | sử   | dụng | trong |      | các  | phương     | pháp |      | linh hoạt; |          |       |
|     | ▪   | Đánh | giá  | được |       | thực | hiện | bởi        | đại  | diện | người      | sử dụng/ | khách |
hàng.
| ❖   | Chuyển |       | giao | dần  |      | dần  |                      |         |     |       |      |       |     |
| --- | ------ | ----- | ---- | ---- | ---- | ---- | -------------------- | ------- | --- | ----- | ---- | ----- | --- |
|     | ▪      | Triển | khai | một  | phần |      | để                   | sử dụng | cho | người | dùng | cuối; |     |
|     | ▪      | Đánh  | giá  | thực | tế   | hơn; |                      |         |     |       |      |       |     |
|     |        |       |      |      |      |      | Software Engineering |         |     |       |      |       | 69  |
tkhuong@dthu.edu.vn

|     | 3.2 Chuyển |      |      |          | giao |      | dần   |      | (incremental delivery) |        |       |        |        |     |
| --- | ---------- | ---- | ---- | -------- | ---- | ---- | ----- | ---- | ---------------------- | ------ | ----- | ------ | ------ | --- |
| ❖   | Ưu điểm    |      | của  | chuyển   |      | giao | dần   | dần: |                        |        |       |        |        |     |
|     | ▪ Khách    |      | hàng | sớm      | được |      | bàn   | giao | sản                    | phẩm   | (từng | phần). |        |     |
|     | ▪ Các      | phần | đầu  |          | được | xem  |       | như  | một                    | nguyên | mẫu   | để     | hỗ trợ | cho |
|     | việc       | làm  | lộ   | rõ những |      | yêu  | cầu   | cho  | phần                   | sau.   |       |        |        |     |
|     | ▪ Nguy     | cơ   | thất | bại      | toàn | hệ   | thống |      | là thấp.               |        |       |        |        |     |
▪ Duy trì được ưu điểm của phát triển từng phần, do đó dễ thích
|     | nghi | với | sự  | thay | đổi | của | hệ  | thống. |     |     |     |     |     |     |
| --- | ---- | --- | --- | ---- | --- | --- | --- | ------ | --- | --- | --- | --- | --- | --- |
▪ Những dịch vụ hệ thống có độ ưu tiên cao nhất sẽ được kiểm thử
|     | nhiều | nhất |     |     |     |     |     |     |     |     |     |     |     |     |
| --- | ----- | ---- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
• Khách hàng ít gặp lỗi phần mềm ở những phần quan trọng của hệ
thống.
|     |     |     |     |     |     | Software Engineering |     |     |     |     |     |     |     | 70  |
| --- | --- | --- | --- | --- | --- | -------------------- | --- | --- | --- | --- | --- | --- | --- | --- |
tkhuong@dthu.edu.vn

|     | Tự  | học | báo | cáo |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
❖
| Nghiên   |       | cứu mô   | hình | SCRUM |           |         |           |      |
| -------- | ----- | -------- | ---- | ----- | --------- | ------- | --------- | ---- |
| ❖ Nghiên |       | cứu mô   | hình | Agile |           |         |           |      |
| ❖ Nghiên |       | cứu mô   | hình | chữ   | V         |         |           |      |
| ❖ Nghiên |       | cứu mô   | hình | RUP   | (Rational | Unified | Process)  |      |
| → Trình  |       | bày cách | thức | hoạt  | động,     | ưu điểm | và khuyết | điểm |
| của      | 2     | mô hình  | trên |       |           |         |           |      |
| → Soạn   | slide | báo      | cáo  |       |           |         |           |      |
71
tkhuong@dthu.edu.vn
tkhuong@dthu.edu.vn

ƯU ĐIỂM CỦA RUP
| ❖   | Phát | triển | phần | mềm |     | theo | vòng | lặp |     |     |     |
| --- | ---- | ----- | ---- | --- | --- | ---- | ---- | --- | --- | --- | --- |
▪ Các phần được lên kế hoạch dựa vào độ ưu tiên của khách hàng
|     |      | và phân |     | phối những |     | phần | có  | độ ưu tiên | cao nhất | trước. |     |
| --- | ---- | ------- | --- | ---------- | --- | ---- | --- | ---------- | -------- | ------ | --- |
| ❖   | Quản | lý      | yêu | cầu        |     |      |     |            |          |        |     |
▪ Viết tài liệu một cách rõ ràng cho các yêu cầu khách hàng và
|     |     | theo    | dõi  | sự thay  | đổi | của | những     | yêu cầu | này.      |        |        |
| --- | --- | ------- | ---- | -------- | --- | --- | --------- | ------- | --------- | ------ | ------ |
| ❖   | Sử  | dụng    | kiến | trúc     | dựa | vào | component |         |           |        |        |
|     | ▪   | Tổ chức |      | hệ thống |     | như | một       | tập các | component | có thể | tái sử |
dụng.
|     |     |     |     |     |     |     | Software Engineering |     |     |     | 86  |
| --- | --- | --- | --- | --- | --- | --- | -------------------- | --- | --- | --- | --- |
tkhuong@dthu.edu.vn

ƯU ĐIỂM CỦA RUP
| ❖   | Mô  | hình | hóa |     | phần |     | mềm |     | một | cách | trực | quan |     |     |     |
| --- | --- | ---- | --- | --- | ---- | --- | --- | --- | --- | ---- | ---- | ---- | --- | --- | --- |
▪ Sử dụng các mô hình đồ họa UML để biểu diễn các góc nhìn tĩnh
|     |      | và động |      | của      | phần  |      | mềm. |      |      |     |      |        |       |       |            |
| --- | ---- | ------- | ---- | -------- | ----- | ---- | ---- | ---- | ---- | --- | ---- | ------ | ----- | ----- | ---------- |
| ❖   | Kiểm | tra     | chất |          | lượng |      | phần |      | mềm  |     |      |        |       |       |            |
|     | ▪    | Đảm     | bảo  |          | rằng  | phần |      | mềm  |      | đáp | ứng  | được   | các   | chuẩn | chất lượng |
|     |      | về mặt  |      | tổ       | chức. |      |      |      |      |     |      |        |       |       |            |
| ❖   | Điều | khiển   |      | các      |       | thay | đổi  | phần |      | mềm |      |        |       |       |            |
|     | ▪    | Quản    |      | lý những |       |      | thay | đổi  | phần |     | mềm  | sử     | dụng  | những | hệ thống   |
|     |      | quản    | lý   | thay     | đổi   |      | và   | các  | công | cụ  | quản | lý cấu | hình. |       |            |
Software Engineering 87
tkhuong@dthu.edu.vn

TỔNG KẾT
❖ Quy trình nên có các hoạt động để đối phó với sự thay đổi. Có
| thể   | có pha | nguyên  |     | bản |       | để  | hạn chế | những |     | thay | đổi | không | cần |
| ----- | ------ | ------- | --- | --- | ----- | --- | ------- | ----- | --- | ---- | --- | ----- | --- |
| thiết | trên   | yêu cầu |     | và  | thiết | kế. |         |       |     |      |     |       |     |
❖
| Quy  | trình | có thể |     | được |       | cấu | trúc   | hóa | cho | phát | triển | và   | phân |
| ---- | ----- | ------ | --- | ---- | ----- | --- | ------ | --- | --- | ---- | ----- | ---- | ---- |
| phối | dần   | dần    | sao | cho  | những |     | thay   | đổi | có  | thể  | được  | thực | hiện |
| mà   | không | phá    | vỡ  | toàn | bộ    | hệ  | thống. |     |     |      |       |      |      |
❖ RUP là một mô hình quy trình tổng quát hiện đại được tổ chức
| thành | các | pha | (khởi |     | động, |     | phát | triển, | xây |     | dựng | và chuyển |     |
| ----- | --- | --- | ----- | --- | ----- | --- | ---- | ------ | --- | --- | ---- | --------- | --- |
tiếp).
|     |     |     |     |     |     | Software Engineering |     |     |     |     |     |     | 90  |
| --- | --- | --- | --- | --- | --- | -------------------- | --- | --- | --- | --- | --- | --- | --- |
tkhuong@dthu.edu.vn

BÀI TẬP
| ❖ Tìm | hiểu   | và trình | bày                  | một | quy | trình | phần | mềm | (ví |
| ----- | ------ | -------- | -------------------- | --- | --- | ----- | ---- | --- | --- |
| dụ:   | SCRUM, | XP,      | 4GT,                 | …)  |     |       |      |     |     |
|       |        |          | Software Engineering |     |     |       |      |     | 91  |
tkhuong@dthu.edu.vn

CÂU HỎI ÔN TẬP
| 1) Có    | mấy    | loại  | mô hình  | tiến | trình? | Là loại  | nào? |       |          |
| -------- | ------ | ----- | -------- | ---- | ------ | -------- | ---- | ----- | -------- |
| 2) Trình | bày    |       | nội dung | của  | các    | mô hình: | thác | nước, | làm mẫu, |
| xoáy     | ốc,    | …RUP  |          |      |        |          |      |       |          |
| a)       | Nội    | dung  |          |      |        |          |      |       |          |
| b)       | Đặc    | trưng |          |      |        |          |      |       |          |
| c)       | Ưu     | nhược | điểm     |      |        |          |      |       |          |
| d)       | Cần    | yêu   | cầu gì?  |      |        |          |      |       |          |
| e)       | Thích  | hợp   | khi nào? |      |        |          |      |       |          |
| 3) Mô    | tả quy | trình | công     | nghệ | yêu    | cầu?     |      |       |          |
Software Engineering 92
tkhuong@dthu.edu.vn

CÂU HỎI ÔN TẬP
1) Ở trường hợp nào thì áp dụng quy trình phát triển phần mềm
| a) Thác      | nước    |            |         |      |      |      |        |
| ------------ | ------- | ---------- | ------- | ---- | ---- | ---- | ------ |
| b) Thác      | nước    | cải tiến   |         |      |      |      |        |
| c) Prototype |         |            |         |      |      |      |        |
| d) Xoắn      | trôn    | ốc         |         |      |      |      |        |
| 2) Trong     | các môn | học trước, | khi xây | dựng | phần | mềm, | bạn đã |
| áp dụng:     |         |            |         |      |      |      |        |
| a) Phương    | pháp    | nào?       |         |      |      |      |        |
| b) Quy       | trình   | nào?       |         |      |      |      |        |
| c) Công      | cụ nào? |            |         |      |      |      |        |
Software Engineering 93
tkhuong@dthu.edu.vn