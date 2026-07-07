# Khởi Động Game

## Tổng Quan

Dịch vụ khởi động game (GameLauncherService) là một trong những module cốt lõi của FufuLauncher. Nó không chỉ đơn giản khởi động tiến trình game mà còn tích hợp kiểm tra đường dẫn, xây dựng tham số, DLL injection (cho các tính năng như mở khoá FPS, loại bỏ sương mù) và khởi chạy công cụ bên ngoài (BetterGI).

## 1. Kiểm Tra Môi Trường Trước Khi Khởi Động

### 1.1 Kiểm Tra Đường Dẫn
Dịch vụ đọc đường dẫn game từ cài đặt, xác minh thư mục tồn tại. Nếu không hợp lệ, quy trình sẽ dừng lại và báo lỗi.

### 1.2 Xác Định File Thực Thi
FufuLauncher hỗ trợ cả máy chủ Trung Quốc và Quốc tế. Hệ thống tìm kiếm theo thứ tự ưu tiên:

1. `GenshinImpact.exe` (máy chủ Quốc tế)
2. `YuanShen.exe` (máy chủ Trung Quốc)

Nếu không tìm thấy file nào, hệ thống sẽ báo lỗi và yêu cầu kiểm tra thư mục cài đặt.

## 2. Hướng Dẫn Khởi Động Game

### Bước 1: Thiết Lập Đường Dẫn Game
1. Vào trang **Cài Đặt**
2. Tìm mục **Đường dẫn cài đặt game**
3. Nhấn **Duyệt** và chọn thư mục chứa game (thư mục có file `GenshinImpact.exe` hoặc `YuanShen.exe`)
4. Nhấn **Áp dụng** để lưu

> **Mẹo**: Nên để FufuLauncher tự động phát hiện đường dẫn.

### Bước 2: Kiểm Tra Cấu Hình
Trong tab chính, bạn có thể xem:
- Phiên bản game hiện tại
- Máy chủ (CN/OS)
- Dung lượng ổ đĩa
- Phiên bản mới nhất
- Trạng thái tài nguyên tải trước

### Bước 3: Khởi Động
Nhấn nút **Khởi Động Game** trên màn hình chính.

## 3. Các Tính Năng Liên Quan

### 3.1 Chế Độ Khởi Động Thường
Khi không bật chế độ injection, game sẽ khởi động bình thường với các tham số đã cấu hình.

### 3.2 Chế Độ Khởi Động Injection
Khi bật chế độ này:
- FPS được mở khoá (lên đến 60fps+)
- Loại bỏ sương mù
- Các tính năng Control Panel khác

> **Yêu cầu**: Chạy FufuLauncher với **quyền Quản trị Viên**

### 3.3 Giám Sát Tiến Trình
Sau khi game khởi động, hệ thống tự động giám sát:
- Nút khởi động chuyển thành **Đóng Game**
- Khi game tắt, nút tự động chuyển lại thành **Khởi Động Game**

### 3.4 Tích Hợp BetterGI
Nếu bật tích hợp BetterGI:
- Tự động mở BetterGI khi game khởi động
- Tự động đóng BetterGI khi tắt game (nếu cấu hình)

## 4. Xử Lý Sự Cố

### Không tìm thấy file game
- Kiểm tra lại đường dẫn game trong Cài Đặt
- Đảm bảo thư mục chứa file `GenshinImpact.exe` hoặc `YuanShen.exe`

### Injection thất bại
- Chạy FufuLauncher với **quyền Quản trị Viên**
- Tắt tạm thời phần mềm diệt virus
- Kiểm tra plugin đã được tải chưa

### Version không khớp
- Dùng **trình khởi động chính thức của MiHoYo** để cập nhật game lên phiên bản mới nhất

> **Khuyến nghị**: Luôn dùng trình khởi động chính thức của MiHoYo để cập nhật và sửa chữa file game.
