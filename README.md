# Student-Smart-Printing-Service
SSPS là phần mềm hỗ trợ in ấn được phát triển như một phần dự án trường đại học nhằm hỗ trợ dịch vụ in ấn cho sinh viên trong khuôn viên trường.

# Công nghệ sử dụng
+ ReactJS
+ MongoDB

## Mô tả
Hệ thống cung cấp nhiều chức năng như là in tài liệu, coi lịch sử in, báo cáo hệ thống, mua giấy in, quản lý máy in,...

## Cài đặt
+ Cách 1: Truy cập trang web đã được deploy https://sspscn07.vercel.app 
+ Cách 2: Clone hoặc tải file từ repository này
```c
git clone https://github.com/SleepyCat79/Student-Smart-Printing-Service.git
```
+ Truy vấn vào thư mục Source Code và giải nén file ssps-fe-main.zip của project
+ Sử dụng npm để cài đặt các dependencies
    ```c
    npm install
    ```
+ Khởi động ứng dụng
    ```c
    npm start
    ```

## Hướng dẫn sử dụng
Lưu ý: vì ứng dụng vẫn đang trong giai đoạn phát triển nên một số chức năng sẽ không được đầy đủ như mong muốn
# Tài khoản để sử dụng ứng dụng

+ Các tài khoản có sẵn trong dữ liệu mẫu:
    + Tài khoản sinh viên:
        Username: vochihoa6@gmail.com
        Password: bất kỳ

    + Tài khoản SPSO:
        Username: admin@example.com
        Password: bất kỳ

# Nhóm chức năng của sinh viên
+ In tài liệu
+ Ở giao diện Đặt in, bạn có thể gửi một yêu cầu in với các bước sau:
    + Đăng tải file
    + Chọn vị trí máy in. Lưu ý rằng máy in đang ngưng hoạt động sẽ không được hiển thị
    + Thiết lập cấu hình in (Lưu ý: Số trang in có thể vượt quá số dư nếu vậy thì yêu cầu in sẽ bị từ chối)
    + Đơn vị trang in mặc định là A4, ngoài ra 1 trang A3 = 2 trang A4

+ Nạp giấy
+ Ở giao diện Nạp giấy, bạn có thể gửi một yêu cầu mua trang với các bước sau:
    + Chọn phương thức thanh toán
    + Chọn số trang cần mua
    + Hệ thống sẽ tự động tính toán tổng tiền dựa trên đơn giá
    + Xác nhận thanh toán
+ Lịch sử in: Ở giao diện Lịch sử in, bạn có thể xem lại toàn bộ các yêu cầu in đã gửi từ giao diện Đặt in của mình.

# Nhóm chức năng của nhân viên quản lý (SPSO)
+ Quản lý máy in
+ Ở giao diện Quản lý máy in, bạn có thể sử dụng các chức năng như:
    + Thêm máy in mới
    + Xem thông số máy in
    + Bật/tắt máy in
+ Lịch sử in: Ở giao diện Lịch sử in, bạn có thể xem lại toàn bộ các yêu cầu in được thực hiện của hệ thống.