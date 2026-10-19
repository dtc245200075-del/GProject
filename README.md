# GProject - Bài tập Bố cục Web Responsive bằng CSS Flexbox

Dự án thực hành xây dựng bố cục trang web Responsive hoàn chỉnh sử dụng **CSS Flexbox** tối ưu cho cả Desktop và Mobile.

## 📌 Các thành phần chính của bố cục:
1. **Header**: Tiêu đề trang (`background-color: #333`).
2. **Navigation**: Thanh menu điều hướng (`background-color: #444`).
3. **Main Content (`flex: 3`)**: Khu vực hiển thị nội dung chính.
4. **Sidebar (`flex: 1`)**: Khu vực thanh bên chứa thông tin phụ (`background-color: #f4f4f4`).
5. **Footer**: Thông tin chân trang (`background-color: #333`).

## 📱 Tính năng Responsive (Media Query):
- **Desktop (màn hình rộng):** Content và Sidebar nằm song song trên 1 hàng ngang theo tỷ lệ chuẩn `3 : 1`.
- **Mobile (màn hình ≤ 768px):** Khung chứa `main-container` tự động kích hoạt `flex-direction: column`, đưa Sidebar xuống bên dưới Main Content giúp người dùng điện thoại dễ dàng theo dõi.

## 📁 Cấu trúc thư mục:
- `index.html`: Cấu trúc HTML chính thức của trang web.
- `style.css`: Toàn bộ mã định dạng CSS Flexbox và Media Queries.
- `flexbox-responsive-layout.html`: Mã nguồn mẫu bài làm tiêu chuẩn.
- `flexbox-responsive-desktop.png`: Ảnh chụp minh chứng giao diện Desktop.
- `flexbox-responsive-mobile.png`: Ảnh chụp minh chứng giao diện Mobile.
