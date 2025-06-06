# 📌 G12_BTL Nhập Môn Công Nghệ Phần Mềm

## 🔥 Nguyên tắc làm việc trên Git

### 📌 **Nhánh chính (Main Branch)**
- `master`: Chứa phiên bản ổn định, không commit trực tiếp lên đây.

### 🔄 **Quy trình làm việc**
1. **Tạo nhánh mới khi làm tính năng**:
   ```sh
   git checkout -b feature/tên-tính-năng
   ```
2. **Làm việc và commit thay đổi**:
   ```sh
   git add .
   git commit -m "tên-người-commit + Mô tả ngắn gọn về thay đổi"
   Ví dụ: git commit -m "anhs + [Fix]Chỉnh sửa tính năng đăng nhập"
   ```
   #### 🔍 **Quy tắc commit message**
    Sử dụng format sau:
    ```
    [Loại commit] Mô tả ngắn gọn
    ```
    Ví dụ:
    ```
    [Feature] Thêm chức năng đăng nhập
    [Fix] Sửa lỗi hiển thị trên trang chủ
    [Refactor] Cải thiện hiệu suất API
    ```
3. **Đẩy code lên GitHub**:
   ```sh
   git push origin feature/tên-tính-năng
   ```
4. **Tạo Pull Request (PR) để review và merge vào `master`**.
5. **Có thể dùng git desktop dùng cho tiện**



### 🛑 **Không push code trực tiếp lên `master`**
Tất cả thay đổi phải thông qua Pull Request và review bởi ít nhất 1 thành viên.

### 🎯 **Quy tắc Code Review**
- Kiểm tra lỗi logic, bảo mật.
- Tuân thủ coding convention của nhóm.
- Cung cấp feedback rõ ràng.



## ✨ Thành viên: Nguyễn Mai Hương

- Công việc đảm nhận: Viết kế hoạch test, thực hiện kiểm thử và báo cáo kết quả.
- 📁 Thư mục cá nhân: [`Test_NguyenMaiHuong`](./Test_NguyenMaiHuong)
- 📄 Tài liệu đính kèm:
  - [Kế hoạch kiểm thử (Test Plan)](./Test_NguyenMaiHuong/TestPlan-SystemTesting.docx)
  - [Báo cáo kết quả test (System Test Report)](./Test_NguyenMaiHuong/G12_SystemTest.xlsx)


