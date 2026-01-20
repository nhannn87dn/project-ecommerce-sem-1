# Các bước để làm Team trong dự án

## Step 1: Tạo Repository
- Tạo một repository mới trên GitHub hoặc nền tảng quản lý mã nguồn mà nhóm sử dụng.
- Đặt tên repository sao cho phù hợp với dự án.

## Step 2: Mời Thành Viên Vào Repository
- Mời các thành viên trong nhóm vào repository với quyền truy cập phù hợp (ví dụ: Read, Write, Admin).

## Step 3: Tạo Local Repository
- Trưởng nhóm tạo một local repository trên máy tính cá nhân.
- Sử dụng lệnh `git init` để khởi tạo repository.
- Tiến hành init dự án với các file cần thiết.
  - Cấu trúc thư mục dự án.
  - Css Style (tailwind, scss, css thuần, ...).
  - Các utils, helpers, config cần thiết
  - Các package cần thiết (react-router, axios, ...).
  - Code nhưng component dùng chung nếu có.
- Đẩy mã nguồn lên repository remote bằng lệnh `git push`.

## Step 4: Clone Repository

- Các thành viên trong nhóm clone repository về máy tính cá nhân bằng lệnh `git clone <repository-url>`.
- Cài đặt các dependencies cần thiết bằng lệnh `npm install` hoặc `yarn install`.

## Step 5: Thiết Lập Chi Nhánh (Branch)
- Quy định cách đặt tên chi nhánh (branch) cho các thành viên (ví dụ: feature/ten-tinh-nang, bugfix/ten-loi).
- Mỗi thành viên tạo chi nhánh riêng để làm việc trên các tính năng hoặc sửa lỗi.