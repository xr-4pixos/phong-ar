# Phòng AR

Thử đồ nội thất 3D trong căn phòng thật, ngay trên trình duyệt điện thoại. Không cần cài app.

- **Android (Chrome):** WebXR AR. App nhận diện sàn thật, chạm để đặt vật đúng tỉ lệ.
- **iPhone (Safari):** chế độ camera. App ước lượng mặt sàn bằng cảm biến xoay của máy.
- **Máy tính / không có camera:** chế độ Xem trước 3D trên lưới.

Đồ có sẵn: ghế, sofa, bàn trà, cây cảnh, đèn cây. Mỗi món đổi được màu, xoay được, phóng to/thu nhỏ được, xoá được, và có nút chụp ảnh.

## Chạy

App là một file `index.html` duy nhất, dùng three.js tải từ CDN. Camera và AR chỉ hoạt động khi trang được mở qua **HTTPS** (ví dụ GitHub Pages).

Bật GitHub Pages: **Settings → Pages → Deploy from a branch → `main` / `(root)`**.
