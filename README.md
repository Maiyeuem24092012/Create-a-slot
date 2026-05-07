# PRO-PANEL - Hệ thống Quản trị Dashboard

Dự án này là một giao diện quản trị hiện đại (Glassmorphism) tích hợp đầy đủ tính năng xác thực người dùng, bao gồm đăng nhập truyền thống, đăng ký, khôi phục mật khẩu và **Đăng nhập bằng Google**.

## 🚀 Tính năng chính

- **Đăng nhập bằng Google (Google Identity Services):** Tích hợp xác thực an toàn từ Google.
- **Giao diện Modern UI:** Sử dụng phong cách Glassmorphism với hiệu ứng blur và màu sắc Neon (Cyan).
- **Quản lý người dùng (LocalStorage):** Lưu trữ và quản lý danh sách người dùng, phân quyền (Admin/User).
- **Hệ thống OTP giả lập:** Hỗ trợ quy trình quên mật khẩu.
- **Dashboard thông minh:** Hiển thị thông tin cá nhân, ảnh đại diện và trạng thái dịch vụ (Slot).

## 🛠 Cấu trúc thư mục

- `login.html`: Trang xác thực tổng hợp (Đăng nhập, Đăng ký, Khôi phục).
- `trang chủ.html`: Giao diện điều khiển chính sau khi đăng nhập.
- `assets/`: (Nếu có) Chứa hình ảnh và các tài nguyên bổ sung.

## ⚙️ Hướng dẫn cách dùng
## link sài https://maiyeuem24092012.github.io/Create-a-slot/login.html
## 📝 Thông tin tài khoản mặc định
- **Email:** `admin@pro.com`
- **Password:** `admin123`

## ⚠️ Lưu ý
- Hệ thống yêu cầu chạy trên môi trường Web Server (Live Server, GitHub Pages, v.v.). Không thể chạy trực tiếp bằng cách mở file từ ổ đĩa (`file://`).
- Dữ liệu được lưu trữ hoàn toàn ở phía Client (LocalStorage), phù hợp cho mục đích thử nghiệm và học tập.
