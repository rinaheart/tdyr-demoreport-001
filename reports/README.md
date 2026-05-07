# 📑 TdyMD Viewer - Scholarly Report Studio

Chào mừng bạn đến với hệ thống quản lý và trình chiếu báo cáo khoa học hiện đại. Dự án này được thiết kế để chuyển đổi các kết quả phân tích dữ liệu (Markdown) thành một Studio báo cáo chuyên nghiệp, tối ưu cho việc đọc, trình bày và tích hợp vào các tài liệu học thuật.

## 🚀 Tính năng nổi bật

- **Tự động nhận diện (Auto-Discovery)**: Bạn chỉ việc thêm file `.md` vào thư mục này, hệ thống sẽ tự động cập nhật danh sách chọn trên giao diện web.
- **Copy định dạng chuyên sâu (Rich Text)**: Cho phép copy các bảng số liệu, định dạng IMRAD và dán trực tiếp vào **Microsoft Word** hoặc **Google Docs** mà không bị lỗi layout.
- **Trải nghiệm Đọc Pro Max**: 
  - Mục lục thông minh tự động cuộn theo vị trí đọc.
  - Chế độ Zen tập trung vào nội dung.
  - Hỗ trợ Dark Mode/Light Mode bảo vệ mắt.
  - Tiến trình đọc (Reading Progress) tinh tế.
- **Tối ưu Mobile**: Giao diện gọn gàng, menu Drawer hiện đại, hỗ trợ các thao tác chạm nhanh.

## 📂 Hướng dẫn quản lý báo cáo

Để thêm báo cáo mới vào hệ thống:

1.  Chuẩn bị file báo cáo định dạng Markdown (`.md`).
2.  Lưu file vào thư mục `reports/` này.
3.  `Commit` và `Push` lên GitHub.
4.  Sau khoảng 20 giây, báo cáo của bạn sẽ xuất hiện trong danh sách chọn của **TdyMD Viewer**.

## 🛠️ Cấu trúc thư mục

- `report.md`: Báo cáo mặc định khi mở ứng dụng.
- `reports/*.md`: Các báo cáo chuyên biệt, báo cáo theo nhóm hoặc bản nháp.
- `reports.json`: File danh mục tự động (được tạo bởi GitHub Action, không cần sửa thủ công).

---
*Phát triển bởi TdyMD Team - Phiên bản v1.0.5*
