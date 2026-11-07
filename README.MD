# THIỀN NIỆM — bản viết lại V2.3

## Cấu trúc thư mục (giữ nguyên tên tệp)
```text
thien_niem_v23/
├── index.html
├── README.MD
└── assets/
    ├── bg-mobile.jpg
    ├── bg-pc.jpg
    └── tieng mõ.mp3
```

## Đã sửa theo yêu cầu
1. **Ảnh nền:** tự gọi `assets/bg-mobile.jpg` trên điện thoại và `assets/bg-pc.jpg` trên máy tính. Ảnh có hiệu ứng chuyển động chậm kiểu Ken Burns và ánh sáng dịu. Khi trình duyệt bật chế độ giảm chuyển động, animation tự tắt.
2. **Tiếng mõ:** nút mõ phát trực tiếp tệp `assets/tieng mõ.mp3`. Đường dẫn có dấu cách và tiếng Việt được URL-encode đúng. Nếu tải lên âm thanh riêng trong Quản trị > Mõ & dùi, tệp tùy chỉnh sẽ được ưu tiên.
3. **Tên địa danh:** mỗi từ là một dòng ngang, ví dụ `Núi` / `Trí` / `Tuệ`, không xoay từng ký tự thành chữ dọc.
4. **Kéo thả địa danh:** giữ chuột hoặc chạm kéo tên địa danh đến vị trí mong muốn. Khi thả, tọa độ theo phần trăm được tự lưu riêng cho bố cục điện thoại hoặc máy tính. Nhấn nhanh tên địa danh để mở nội dung.
5. **Menu hai bên:** rút gọn chiều rộng, nút ôm sát chữ, màu xanh ngọc trong suốt, nền có blur để giảm che khuất phong cảnh.

## Cách chạy
- Giải nén toàn bộ ZIP.
- Không đổi tên hoặc di chuyển thư mục `assets`.
- Mở `index.html` bằng trình duyệt hoặc tải toàn bộ thư mục lên hosting.
- Nếu trình duyệt chặn âm thanh khi mở file trực tiếp, hãy chạy qua localhost/hosting và nhấn nút mõ sau khi trang tải xong.

## Dữ liệu
Tọa độ địa danh và thiết lập lưu trong localStorage; tệp ảnh/âm thanh tải lên từ bảng quản trị lưu trong IndexedDB của trình duyệt. Dữ liệu không tự đồng bộ sang thiết bị khác. Muốn quản trị công khai an toàn và đồng bộ nhiều người dùng cần backend, đăng nhập và cơ sở dữ liệu.


## Bổ sung V2.4 — kéo thả mõ
- Giữ và kéo mõ bằng chuột trên máy tính hoặc chạm giữ rồi vuốt trên điện thoại.
- Có thể kéo mõ lên/xuống hoặc sang trái/phải đến vị trí mong muốn.
- Khi thả tay/chuột, vị trí được tự lưu vào localStorage.
- Tọa độ mõ trên điện thoại và máy tính được lưu riêng.
- Nhấn nhanh vào mõ (không kéo) vẫn phát tiếng mõ và cộng Công Đức/Giọt Từ Bi.
