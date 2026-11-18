# Mô Phỏng Vận Hành Nhà Máy Nhiệt Điện Than 3D

Ứng dụng Web 3D trực quan mô phỏng quy trình vận hành tổ máy Nhiệt điện than (Chu trình Rankine), giúp sinh viên và kỹ sư mới dễ dàng quan sát cấu tạo và thông số vận hành.

## Tính năng chính
- **Không gian 3D tương tác:** Xoay 360°, phóng to/thu nhỏ các cụm thiết bị (Kho than, Lò hơi, Tua-bin hơi nước, Tháp giải nhiệt, Trạm biến áp 500kV).
- **Bảng điều khiển SCADA thời gian thực:** Theo dõi Công suất (MW), Tốc độ vòng quay (rpm), Nhiệt độ hơi (°C), Áp suất hơi (MPa).
- **Mô phỏng trạng thái:** Nút Khởi động / Dừng khẩn cấp thay đổi trạng thái ngọn lửa lò hơi, tốc độ quay trục tua-bin và khói thải.
- **Tra cứu thiết bị:** Nhấp chuột trực tiếp vào từng thiết bị 3D để xem nguyên lý hoạt động và thông số kỹ thuật.

## Công nghệ sử dụng
- HTML5 / JavaScript (ES6 Modules)
- Three.js (Đồ họa 3D WebGL)
- Tailwind CSS (Giao diện SCADA)
