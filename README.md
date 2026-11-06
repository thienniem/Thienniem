# THIỀN NIỆM V2.2 — hai hình nền + chuyển động + tiếng mõ thật

## Tệp trong gói
- `index.html`: mã nguồn website.
- `assets/background-desktop.jpg`: hình nền ngang 16:9 bạn gửi, dùng cho máy tính.
- `assets/background-mobile.jpg`: hình nền dọc 9:16 bạn gửi, dùng cho điện thoại.
- `assets/tieng-mo.mp3`: tiếng mõ bạn gửi, được phát khi nhấn vào mõ.

## Cách chạy
Giải nén toàn bộ ZIP và giữ nguyên cấu trúc thư mục `assets` nằm cạnh `index.html`. Mở `index.html` bằng trình duyệt hiện đại hoặc đưa toàn bộ thư mục lên hosting tĩnh.

## Chuyển động hình nền
Hình nền có chuyển động Ken Burns rất nhẹ: dịch chuyển chậm theo chiều dọc và ánh sáng trung tâm thay đổi dịu. Chuyển động tắt khi thiết bị bật chế độ giảm chuyển động (`prefers-reduced-motion`). Khi đổi kích thước cửa sổ, website tự chuyển giữa ảnh ngang và ảnh dọc.

## Tích hợp âm thanh mõ
Âm thanh MP3 của bạn được đặt làm âm thanh mặc định khi nhấn mõ. File bạn gửi dài khoảng 0,275 giây, phù hợp làm tiếng gõ ngắn. Nếu muốn âm vang ngân dài hơn, có thể gửi bản thu dài hơn hoặc thêm hiệu ứng vang sau này.

## Tùy chỉnh
Bảng quản trị vẫn cho phép tải hình nền khác và âm thanh mõ tùy chỉnh. Hình nền tải lên trong quản trị sẽ ưu tiên hơn hai ảnh mặc định đóng gói trong `assets`.

## Lưu ý
Dữ liệu cài đặt hiện lưu trên trình duyệt/thiết bị. Đồng bộ nhiều người dùng và bảo mật quản trị cần backend và xác thực máy chủ.
