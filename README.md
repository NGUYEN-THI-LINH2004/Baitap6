# Baitap6
## NguyenThiLinh_K225480106040
Bài tập 6: Hệ quản trị CSDL.
- Chủ đề: Câu lệnh Select.
- Yêu cầu bài tập: 
- Cho file sv_tnut.sql (1.6MB)
1. Hãy nêu các bước để import được dữ liệu trong sv_tnut.sql vào sql server của em
2. dữ liệu đầu vào là tên của sv; sđt; ngày, tháng, năm sinh của sinh viên (của sv đang làm bài tập này)
3. nhập sql để tìm xem có những sv nào trùng hoàn toàn ngày/tháng/năm với em?
4. nhập sql để tìm xem có những sv nào trùng ngày và tháng sinh với em?
5. nhập sql để tìm xem có những sv nào trùng tháng và năm sinh với em?
6. nhập sql để tìm xem có những sv nào trùng tên với em?
7. nhập sql để tìm xem có những sv nào trùng họ và tên đệm với em.
8. nhập sql để tìm xem có những sv nào có sđt sai khác chỉ 1 số so với sđt của em.
9. BẢNG SV CÓ HƠN 9000 ROWS, HÃY LIỆT KÊ TẤT CẢ CÁC SV NGÀNH KMT, SẮP XẾP THEO TÊN VÀ HỌ ĐỆM, KIỂU TIẾNG  VIỆT, GIẢI THÍCH.
10. HÃY NHẬP SQL ĐỂ LIỆT KÊ CÁC SV NỮ NGÀNH KMT CÓ TRONG BẢNG SV (TRÌNH BÀY QUÁ TRÌNH SUY NGHĨ VÀ GIẢI NHỮNG VỨNG MẮC)

# 1. Hãy nêu các bước để import được dữ liệu trong sv_tnut.sql vào sql server của em
- Đầu tiên là Mở SQL Server Management Studio(SSMS)
-  sau đó chọn database (tạo mới database và đặt tên là sv_tnut)
-  Trên menu SSMS, chọn:File > Open > File... → chọn file sv_tnut.sql ( đã tải về hoặc lưu từ upload).
-  Chọn đúng cơ sở dữ liệu sv_tnut ở thanh chọn DB (trên tab query)
-  Nhấn Execute (F5) để chạy toàn bộ script
# 2. dữ liệu đầu vào là tên của sv; sđt; ngày, tháng, năm sinh của sinh viên (của sv đang làm bài tập này)
### Nguyễn Thị Linh-0383791082, 30-09-2004
# 3. nhập sql để tìm xem có những sv nào trùng hoàn toàn ngày/tháng/năm với em?
  ![Screenshot 2025-04-24 100708](https://github.com/user-attachments/assets/ffa00199-dacb-440e-955c-3da23047fa96)
# 4. nhập sql để tìm xem có những sv nào trùng ngày và tháng sinh với em?
![Screenshot 2025-04-24 101755](https://github.com/user-attachments/assets/26802995-e517-43d4-883a-4bdcf2abd791)
# 5.nhập sql để tìm xem có những sv nào trùng tháng và năm sinh với em?
![Screenshot 2025-04-24 102401](https://github.com/user-attachments/assets/964c479b-3418-4a23-8b95-0bcd20278df4)
# 6. nhập sql để tìm xem có những sv nào trùng tên với em?
![Screenshot 2025-04-24 102651](https://github.com/user-attachments/assets/8d8fcda3-de53-4f3f-a6b9-c62dd9c651ad)
# 7. nhập sql để tìm xem có những sv nào trùng họ và tên đệm với em.
![Screenshot 2025-04-24 103352](https://github.com/user-attachments/assets/a941e11d-94b5-49a9-bb63-df2c0cfaa0ba)
# 8. nhập sql để tìm xem có những sv nào có sđt sai khác chỉ 1 số so với sđt của em.
![Screenshot 2025-04-24 184252](https://github.com/user-attachments/assets/a81ce1f8-653e-4de0-a9fe-903a6e9cc132)
# 9. BẢNG SV CÓ HƠN 9000 ROWS, HÃY LIỆT KÊ TẤT CẢ CÁC SV NGÀNH KMT, SẮP XẾP THEO TÊN VÀ HỌ ĐỆM, KIỂU TIẾNG  VIỆT, GIẢI THÍCH.
![Screenshot 2025-04-24 174724](https://github.com/user-attachments/assets/94b17519-0df7-491a-a19d-2bedd54e7d4b)
# 10. HÃY NHẬP SQL ĐỂ LIỆT KÊ CÁC SV NỮ NGÀNH KMT CÓ TRONG BẢNG SV (TRÌNH BÀY QUÁ TRÌNH SUY NGHĨ VÀ GIẢI NHỮNG VỨNG MẮC)
- Ở phần này em do không có cột giới tính lên em dùng họ đệm và một số tên riêng phổ biến nhiều cho nữ  để liệt kê ra các SV nữ của ngành KMT có trong bảng SV. Mặc dù cách này chưa đảm bảo tuyệt đối nhưng hạn chế tối đa trường hợp bị sai giới tính
![Screenshot 2025-04-24 174434](https://github.com/user-attachments/assets/0a6f1618-e678-4e42-b6dc-6af808aef47e)

