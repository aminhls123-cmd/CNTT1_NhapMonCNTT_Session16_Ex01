#  Bài 1 : Hệ thống Quản lý Tài liệu Dự án Doanh nghiệp
## Phần 1: Báo cáo phân tích
- Luồng dữ liệu:

       Phần mềm 3D -  Ctrl + S -> Local SSD (Synced Folder) -> (File Watcher) -> Cloud Storage.

- Xử lý xung đột phiên bản (File Version Conflict):

      Phát hiện: Nhận diện dấu thời gian lệch giữa local và cloud.
      Tách nhánh: Tạo bản sao lưu độc lập để tránh ghi đè mất dữ liệu.

      Giải quyết: Kiểm tra thủ công, hợp nhất các phần chỉnh sửa tốt nhất và xóa file thừa.

## Phần 2: Quy trình thực thi (3 bước thiết lập chuẩn)
- Bước 1 (Đồng bộ thư mục): Cài đặt ứng dụng Google Drive và đưa toàn bộ thư mục dự án 3D vào thư mục đồng bộ
- Bước 2 (Lưu file tự động): Cấu hình phần mềm 3D lưu file trực tiếp vào thư mục đồng bộ để tự động đẩy lên Cloud ngay khi bấm Ctrl + S.
- Bước 3 (Lịch sử phiên bản): Bật Version History trên Cloud để dễ dàng khôi phục phiên bản ổn định khi gặp sự cố phần cứng.
