# TỔNG HỢP BÀI TẬP THỰC HÀNH GIT & GITHUB
Họ và tên:Nông Anh Tú
Tài khoản GitHub: dtc245160064-cpu

---

## DANH SÁCH REPOSITORY DỰ ÁN

**Link Repository Bài 4:**
  https://github.com/dtc245160064-cpu/git-basic-practice

**Link Repository Bài 6:**
  https://github.com/dtc245160064-cpu/personal-portfolio

## 📷 MINH CHỨNG VÀ KẾT QUẢ THỰC HÀNH

### Bài 1 & Bài 2: Khởi tạo và Quản lý Staging Area
<img width="1917" height="1018" alt="image" src="https://github.com/user-attachments/assets/90c3851a-58cb-4b89-86cb-ab1979e95e38" />
<img width="1917" height="1017" alt="image" src="https://github.com/user-attachments/assets/1307a0c5-7712-4f75-8dc2-4d2a398bb322" />

Staging Area đóng vai trò như một vùng đệm kiểm duyệt, giúp bạn chọn lọc chính xác những thay đổi nào đủ điều kiện để đóng gói thành một bản lưu (commit). Nếu không có nó, mỗi lần lưu bạn sẽ buộc phải nộp toàn bộ các file đang sửa dở dang hoặc file rác cá nhân, làm lịch sử dự án trở nên lộn xộn và rất khó kiểm soát.

<img width="1917" height="1020" alt="image" src="https://github.com/user-attachments/assets/3bf00375-4100-4306-ad27-0b2854aca84d" />
<img width="1917" height="1015" alt="image" src="https://github.com/user-attachments/assets/a11a1a24-659d-4004-b07b-bab84aa901f3" />


### Bài 3: Lịch sử Commit và Reset


### Bài 4: Kết nối Remote Repository
<!-- Kéo thả hoặc dán ảnh chụp lệnh git remote -v vào bên dưới -->


### Bài 5: Đồng bộ Remote Repository (Clone / Pull / Push)
<!-- Kéo thả hoặc dán ảnh trước/sau khi git pull vào bên dưới -->


**Câu hỏi tư duy Bài 5:** *Lệnh `git pull` thực chất là tổ hợp của 2 lệnh nào?*
* **Trả lời:** `git pull` là sự kết hợp của lệnh `git fetch` (tải dữ liệu từ remote về) và `git merge` (gộp các thay đổi vừa tải vào nhánh làm việc ở local).

### Bài 6: Quy trình làm việc hoàn chỉnh (Portfolio & Revert)
<!-- Kéo thả hoặc dán ảnh minh chứng log của Bài 6 vào bên dưới -->


---

**Câu hỏi tư duy Bài 3 (Bổ sung):** *Việc dùng `git reset --hard` để lùi commit khi đã push lên GitHub có an toàn không?*
* **Trả lời:** Không an toàn. Lệnh này sẽ xóa vĩnh viễn các commit ở local và làm lệch lịch sử code với GitHub. Nếu ép buộc đẩy code lên (`force push`), các thay đổi của đồng nghiệp có thể bị ghi đè và mất hoàn toàn.
