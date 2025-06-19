BÁO CÁO KIỂM THỬ API Tên Dự Án: Test Collection of APIs Ngày Kiểm Thử: 19/06/2025

Người Kiểm Thử: Nguyễn Công Bảo

Mục Tiêu Kiểm Thử: Sử dụng Postman để kiểm thử một API thực tế

Môi Trường Kiểm Thử: Postman.

Phương Pháp Kiểm Thử: Kiểm thử tự động và thủ công trên phần mềm Postman.

Kịch Bản Kiểm Thử Lần 1: Tên Kịch Bản: Kiểm thử cơ bản của 1 URL

Mục Đích: Test khả năng hoạt động của URL và phần mềm Postman

Phương Thức HTTP (GET/POST/PUT/DELETE): GET URL: https://pokeapi.co/api/v2/

Tham Số: users?size=5&is_xml=true

Kết Quả Mong Đợi: Gửi yêu cầu thành công

Kết Quả Thực Tế: Đã gửi yêu cầu thành công

Trạng Thái: Thành công Kết quả sau khi kiểm thử:
![image](https://github.com/user-attachments/assets/effff29f-8618-458b-be68-1187b05d42aa)


Kịch Bản Kiểm Thử Lần 2: Tên Kịch Bản: Kiểm thử cơ bản của một URL với một tham số

Mục Đích: Test khả năng hoạt động của URL và phần mềm Postman

Phương Thức HTTP (GET/POST/PUT/DELETE): GET

URL: https://random-data-api.com/api/v2/

Tham Số: beerType=light

Kết Quả Mong Đợi: Gửi yêu cầu thành công

Kết Quả Thực Tế: Gửi yêu cầu thất bại

Trạng Thái: Không thành công

Kết quả sau khi kiểm thử: 
![image](https://github.com/user-attachments/assets/e21b5857-a7bd-491e-8931-3c51832d9d20)


Kịch Bản Kiểm Thử Lần 1: Tên Kịch Bản: Kiểm thử cơ bản của 1 URL với một tham số truyền vào

Mục Đích: Test khả năng hoạt động của URL và phần mềm Postman

Phương Thức HTTP (GET/POST/PUT/DELETE): GET

URL: https://random-data-api.com/api/v2/

Tham Số: beerType=light

Kết Quả Mong Đợi: Gửi yêu cầu thành công

Kết Quả Thực Tế: Đã gửi yêu cầu thành công

Trạng Thái: Thành công

Kết quả sau khi kiểm thử: 
![image](https://github.com/user-attachments/assets/42951840-b0a9-4e50-9b39-1806e55e7d23)


Kết Quả Kiểm Thử: Tóm tắt kết quả kiểm thử, bao gồm số lượng kịch bản kiểm thử đã chạy, số lượng thành công, số lượng thất bại, và tỷ lệ thành công.
Số lượng kịch bản đã kiểm thử: 3

Số lần thành công: 2

Số lần thất bại: 1

Tỉ lệ thành công: 75%

Phát Hiện Lỗi: Chi tiết về lỗi, bao gồm:
ID Lỗi: 404 Not Found

Mô Tả Lỗi: Trang bạn đang tìm kiếm không tồn tại (404)

Mức Độ Ảnh Hưởng: Không

Ghi Chú/Đề Xuất: Sai URL và tham số
