# Plugin

## Tổng Quan

FufuLauncher hỗ trợ plugin thông qua cơ chế DLL injection. Plugin được inject vào tiến trình game khi game đang ở trạng thái tạm dừng (suspended), sau đó tiếp tục luồng chính của game.

## Cách Thức Hoạt Động

1. Tạo tiến trình game (suspended)
2. Inject module core của FufuLauncher
3. Quét và inject các plugin DLL bằng kỹ thuật Remote Thread
4. Tiếp tục luồng chính của game

## Quản Lý Plugin

### Trang Plugin
Vào trang **Plugin** để quản lý tất cả plugin:
- **Danh sách plugin**: Xem tất cả plugin có sẵn
- **Cài đặt plugin**: Chọn phiên bản Stable hoặc Latest
- **Sửa chữa plugin**: Sửa plugin bị lỗi
- **Xoá plugin**: Gỡ cài đặt plugin

### Plugin Có Sẵn

#### 1. FPS Unlocker
- Mở khoá giới hạn FPS trong game
- Hỗ trợ lên đến 60fps+ (tuỳ cấu hình máy)
- Yêu cầu bật injection mode

#### 2. Loại Bỏ Sương Mù
- Xoá hiệu ứng sương mù trong game
- Cải thiện tầm nhìn

#### 3. Controller Hot-Swap
- Hỗ trợ chuyển đổi nóng giữa các tay cầm
- **Lưu ý**: Có thể gây crash game khi dùng cùng các plugin khác

#### 4. Chế Độ Cửa Sổ
- Tuỳ chỉnh chế độ cửa sổ game
- Chế độ không viền, toàn màn hình, v.v.

### Chọn Phiên Bản Plugin

| Phiên bản | Mô tả |
|---|---|
| **Stable (Ổn định)** | Phiên bản đã kiểm tra kỹ, ít lỗi |
| **Latest (Mới nhất)** | Phiên bản mới nhất, có thể chưa ổn định |

> **Khuyến nghị**: Dùng bản Stable nếu bạn muốn trải nghiệm ổn định.

## Yêu Cầu

- **Quyền Quản trị Viên**: Plugin cần quyền admin để inject vào game
- **.NET Runtime**: Đã cài đặt .NET 8.0
- **Visual C++ Redistributable**: Đã cài đặt

## Lưu Ý Quan Trọng

1. Plugin là công cụ bên thứ ba, tiềm ẩn rủi ro tài khoản
2. Luôn cập nhật plugin lên phiên bản mới nhất để tương thích với game
3. Nếu game crash, thử tắt bớt plugin không cần thiết
4. Không dùng plugin vi phạm ToS của game

## Xử Lý Sự Cố

### Plugin không hoạt động
1. Chạy FufuLauncher với quyền Quản trị Viên
2. Kiểm tra plugin đã được tải trong trang Plugin
3. Nhấn **Sửa chữa** để tải lại plugin
4. Khởi động lại ứng dụng

### Game crash khi dùng plugin
1. Thử chuyển sang plugin bản Stable
2. Tắt bớt plugin không cần thiết
3. Kiểm tra xem có xung đột plugin không

### Plugin biến mất
1. Kiểm tra thư mục plugin
2. Tải lại plugin từ trang Plugin
3. Kiểm tra tường lửa không chặn kết nối
