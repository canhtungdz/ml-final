<!-- # TÊN DỰ ÁN CỦA BẠN 🚀

Mô tả ngắn gọn về dự án.

## 🧭 1. Cấu Trúc Dự Án Chính
- data/ (Chứa dữ liệu thô và đã tiền xử lý)
- preprocessed.py (Script tiền xử lý)
- requirements.txt (Danh sách thư viện) -->

## ⚙️ 2. Hướng Dẫn Thiết Lập Môi Trường
1. **Tạo và Kích hoạt Môi trường ảo:** `python -m venv venv` sau đó `source venv/bin/activate` (hoặc cú pháp Windows).
2. **Cài đặt Thư viện:** `pip install -r requirements.txt`
3. **Chuẩn bị Dữ liệu:** chạy file preprocess.ipynb

## 👨‍💻 3. Quy Trình Làm Việc với Git (Workflow)
Sử dụng Feature-based Branching.

### A. Bắt đầu Công việc Mới
- Cập nhật `main`: `git pull origin main`
- Tạo nhánh: `git checkout -b <ten-tinh-nang>`

### B. Commit và Push
- **Quan trọng:** **Clear Output** của Notebook trước khi commit.
- Thêm và Commit: `git add .` sau đó `git commit -m "feat: Mô tả công việc"`
- Push: `git push origin <ten-tinh-nang>` (push nhánh đang làm thôi, là nhánh <ten-tinh-nang> đấy)

### C. Cập nhật Nhánh Tính năng từ `main`
- Thường xuyên lấy code mới để tránh xung đột:
  `git fetch origin main` (lấy code main mới nhất)
  `git merge origin/main` (merge code từ main vào nhánh hiện tại. )

### D. Kết thúc Công việc
- Tạo **Pull Request (PR)** trên GitHub từ `<ten-tinh-nang>` vào `main`.