# TỔNG HỢP BÀI TẬP THỰC HÀNH GIT & GITHUB
Họ và tên:Nông Anh Tú
Tài khoản GitHub: dtc245160064-cpu
Mã Sinh Viên : dtc245160064
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

Việc dùng git reset --hard để lùi commit khi đã push lên GitHub là không an toàn.

Lệnh này sẽ xóa vĩnh viễn các commit trên máy bạn và làm lệch lịch sử code so với GitHub. Khi bạn ép buộc đẩy code lên (force push), các thay đổi của đồng nghiệp có thể bị ghi đè và mất hoàn toàn, gây xung đột nghiêm trọng cho cả team.


<img width="1917" height="1020" alt="image" src="https://github.com/user-attachments/assets/169a41e7-85fd-4ade-abeb-b3300f77dc48" />
<img width="1917" height="1020" alt="image" src="https://github.com/user-attachments/assets/22358fca-65aa-4461-9203-6036ecd1739d" />


### Bài 4: Kết nối Remote Repository
<img width="1917" height="1017" alt="image" src="https://github.com/user-attachments/assets/25b13354-176f-49da-92a0-5efc6cbc53cd" />



### Bài 5: Đồng bộ Remote Repository (Clone / Pull / Push)
git pull thực chất là tổ hợp của 2 lệnh:

git fetch: Tải toàn bộ dữ liệu và các commit mới nhất từ Remote Repository về máy local nhưng chưa gộp vào code hiện tại.

git merge: Gộp (hợp nhất) các thay đổi vừa tải về vào nhánh làm việc hiện tại ở local.

<img width="1917" height="1015" alt="image" src="https://github.com/user-attachments/assets/7d2f0b46-f34e-48d7-907a-b0e820268ba1" />


