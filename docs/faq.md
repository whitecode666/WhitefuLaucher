# Câu Hỏi Thường Gặp (FAQ)

## Cài Đặt & Khởi Động

### Hỏi: Lần đầu mở FufuLauncher bị báo thiếu .NET?

**Đáp**: Tải và cài đặt .NET 8.0 từ [trang chủ Microsoft](https://dotnet.microsoft.com/download/dotnet/8.0). Nếu vẫn lỗi, thử .NET 10.0.

### Hỏi: Ứng dụng không mở được, báo lỗi "Object reference not set to an instance"?

**Đáp**: Thử các bước sau:
1. Cài đặt đầy đủ .NET 8.0 và WebView2
2. Chạy với quyền Quản trị Viên
3. Xoá cache trong thư mục `%LOCALAPPDATA%\FufuLauncher\Cache`

### Hỏi: Lỗi "Bad Image" khi khởi động?

**Đáp**: Cài đặt lại [Visual C++ Redistributable](https://learn.microsoft.com/cpp/windows/latest-supported-vc-redist) phiên bản X64.

## Game & Plugin

### Hỏi: Không tìm thấy đường dẫn game?

**Đáp**: Vào **Cài Đặt** → chọn đúng thư mục chứa `Genshin Impact Game`. Không nên dùng ký tự đặc biệt trong đường dẫn.

### Hỏi: Plugin không hoạt động?

**Đáp**:
1. Đảm bảo chạy FufuLauncher với quyền **Quản trị Viên**
2. Vào trang **Plugin** → kiểm tra plugin đã được tải chưa
3. Nhấn **Sửa chữa** nếu plugin bị lỗi

### Hỏi: FPS đã mở khoá nhưng không lên được 60fps?

**Đáp**: Kiểm tra:
1. Đã bật FPS plugin trong phần cài đặt plugin
2. Đồ hoạ trong game không bị giới hạn ở 60fps
3. Cấu hình máy có đủ mạnh không

### Hỏi: Game bị crash khi vào coop?

**Đáp**: Thử tắt một số plugin không cần thiết, hoặc dùng bản plugin ổn định (Stable) thay vì bản mới nhất (Latest).

## Tài Khoản

### Hỏi: Không đăng nhập được tài khoản MiHoYo?

**Đáp**: Kiểm tra kết nối mạng, thử làm mới trang đăng nhập. Nếu vẫn lỗi, kiểm tra tường lửa.

### Hỏi: Dữ liệu tài khoản có an toàn không?

**Đáp**: Tất cả dữ liệu tài khoản được **mã hóa và lưu trữ cục bộ** trên máy bạn. FufuLauncher không tải lên bất kỳ máy chủ nào.

## Khác

### Hỏi: Làm sao để báo lỗi hoặc góp ý?

**Đáp**: Bạn có thể:
- Tạo [Issue trên GitHub](https://github.com/whitecode666/FufuLauncher/issues)
- Tham gia [Discord](https://discord.gg/fvrYwyCR)
- Gửi feedback trong nhóm QQ

### Hỏi: FufuLauncher có vi phạm ToS của game không?

**Đáp**: Đây là công cụ hỗ trợ bên thứ ba, không sửa đổi file game. Tuy nhiên, một số tính năng plugin có thể tiềm ẩn rủi ro. Vui lòng đọc kỹ thỏa thuận người dùng trước khi sử dụng.
