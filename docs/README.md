# [FufuLauncher (芙芙启动器)](https://github.com/whitecode666/FufuLauncher)

![Platform](https://img.shields.io/badge/Platform-Windows%2010%2F11-brightgreen)
![License](https://img.shields.io/badge/License-MIT-orange)
![.NET](https://img.shields.io/badge/.NET-8.0-blue)
![WinUI](https://img.shields.io/badge/UI-WinUI%203-8A2BE2)

> Trình khởi động Genshin Impact bên thứ ba được xây dựng bằng WinUI 3, hỗ trợ injection, điểm danh tự động và nhiều tính năng tiện ích.

[中文](./README.md) | [English](./README-en.md)

---

## 📸 Ảnh chụp màn hình

> *(Thêm ảnh chụp ứng dụng tại đây)*

---

## ✨ Tính năng

### 🔐 Quản lý Tài khoản
- Chuyển đổi nhanh giữa nhiều tài khoản, không cần nhập lại mật khẩu
- Mã hóa lưu trữ cục bộ, bảo vệ thông tin tài khoản
- Hỗ trợ đăng nhập QR Code MiHoYo

### 📅 Điểm danh tự động
- Điểm danh MiHoYo/HoYoLab hàng ngày chỉ một cú nhấp chuột
- Hỗ trợ điểm danh Cloud Game
- Tự động hoàn thành tác vụ cộng đồng (like, đọc, chia sẻ)

### 🎮 Quản lý Game
- Tự động phát hiện đường dẫn cài đặt game
- Cập nhật thông báo phiên bản theo thời gian thực
- Tải trước tài nguyên game và xác minh tính toàn vẹn
- Chuyển đổi máy chủ (Chính thức/Bilibili/Quốc tế)

### ⚡ Công cụ tiện ích
- **Máy tính nuôi dưỡng**: Tính toán tài nguyên cần thiết cho nhân vật và vũ khí
- **Auto Clicker**: Tự động hóa thao tác bàn phím/chuột
- **Giám sát FPS**: Hiển thị FPS trong game theo thời gian thực
- **Chụp màn hình**: Chụp ảnh màn hình game chỉ một cú nhấp chuột
- **Lịch sử Cầu nguyện**: Xem và phân tích dữ liệu gacha
- **Theo dõi Thành tựu**: Theo dõi tiến độ thành tựu

### 🚀 Tham số khởi động
- Tùy chỉnh độ phân giải và chế độ cửa sổ
- Preset tham số khởi động tùy chỉnh
- Hỗ trợ nhiều màn hình

### 🔧 Injection
- Hỗ trợ DLL injection
- Hệ thống quản lý preset
- Hỗ trợ plugin mở rộng

### 🎨 Tùy chỉnh giao diện
- Nền tùy chỉnh (hình ảnh/video/trình chiếu)
- Màu chủ đề tùy chỉnh
- Hiệu ứng Acrylic/Mica
- Điều chỉnh độ trong suốt

---

## 📥 Cài đặt & Sử dụng

### Yêu cầu hệ thống
- **Hệ điều hành**: Windows 10/11 (64-bit)
- **Runtime**: [.NET 8.0](https://dotnet.microsoft.com/download/dotnet/8.0) trở lên
- **Runtime**: [Microsoft Edge WebView2](https://developer.microsoft.com/microsoft-edge/webview2/) (thường được cài sẵn trên Windows 10+)
- **Runtime**: Visual C++ Redistributable v14

### Bắt đầu nhanh

1. **Lần chạy đầu**: Thỏa thuận người dùng sẽ hiển thị, vui lòng đọc và đồng ý để tiếp tục
2. **Chọn đường dẫn game**: Vào trang "Cài đặt" để chọn thư mục cài đặt game (khuyên dùng tự động phát hiện)
3. **Đăng nhập**: Đăng nhập tài khoản MiHoYo/HoYoLab tại trang "Tài khoản" để sử dụng tính năng điểm danh
4. **Khởi động game**: Nhấn "Khởi động Game" trên trang chính

> ⚠️ **Lưu ý quan trọng**:
> - Chuyển đổi tài khoản cần **quyền Quản trị viên**
> - Nên chọn đường dẫn game trước, sau đó chạy chương trình với quyền Quản trị viên
> - Tính năng injection yêu cầu **quyền Quản trị viên**
> - Nền video động có thể không ổn định, khuyên dùng hình ảnh tĩnh

---

## 🏗️ Công nghệ sử dụng

- **UI Framework**: WinUI 3 (Windows App SDK)
- **Ngôn ngữ**: C# (.NET 8.0)
- **Kiến trúc**: MVVM (CommunityToolkit.Mvvm)
- **Cơ sở dữ liệu**: SQLite (lưu trữ cài đặt cục bộ)
- **Injection**: DLL injection gốc
- **Backend**: Windows Native APIs + HTTP APIs

---

## 🤝 Đóng góp

Mọi đóng góp dưới dạng Issue và Pull Request đều được hoan nghênh! Vui lòng làm theo các bước:

1. Fork repository
2. Tạo nhánh tính năng (`git checkout -b feature/TinhNangMoi`)
3. Commit thay đổi (`git commit -m 'Thêm tính năng mới'`)
4. Đẩy lên nhánh (`git push origin feature/TinhNangMoi`)
5. Mở Pull Request

### Báo cáo vấn đề
- [Báo cáo lỗi](https://github.com/whitecode666/FufuLauncher/issues/new?template=bug_report.yml)
- [Yêu cầu tính năng](https://github.com/whitecode666/FufuLauncher/issues/new?template=feature_request.yml)

---

## 📄 Giấy phép

Dự án này được cấp phép theo [MIT License](../LICENSE).

Bản quyền © 2026 whitecode666

---

## 🌟 Ủng hộ dự án

Nếu bạn thấy dự án này hữu ích, hãy cho nó một ⭐ trên GitHub nhé!

[![Star History Chart](https://api.star-history.com/svg?repos=whitecode666/FufuLauncher&type=date&legend=top-left)](https://www.star-history.com/#whitecode666/FufuLauncher&type=date&legend=top-left)

---

## 📞 Liên hệ

- [GitHub Issues](https://github.com/whitecode666/FufuLauncher/issues)
- [Telegram](https://github.com/whitecode666/FufuLauncher)

---

*Phần mềm này là công cụ bên thứ ba được phát triển độc lập và không có liên kết với miHoYo hoặc các công ty con của họ.*
*Vui lòng ủng hộ phiên bản game chính thức.*
