# phan_tich_du_lieu_va_hoc_sau
***Tuần 1***
Nguyễn Bách Việt_2374802010555
Lớp:252_71ITDS30203_0301

# Công nghệ sử dụng
-Python 3
-Pandas
-NumPy
-Jupyter Notebook / Python script
#Cách hoạt động
-Dữ liệu đầu vào được đọc từ file dulieuxettuyendaihoc.csv
-Thực hiện phân loại dữ liệu định tính và định lượng
-Xác định thang đo và kiểu dữ liệu phù hợp cho từng biến
-Thống kê và xử lý dữ liệu thiếu:
-Biến DT (Dân tộc): thay thế giá trị thiếu bằng 0
-Các biến điểm số: thay thế giá trị thiếu bằng Mean
-Tính điểm trung bình môn (TBM1, TBM2, TBM3) cho các năm lớp 10, 11 và 12
-Phân loại học lực (XL1, XL2, XL3) dựa trên điểm trung bình
-Chuẩn hóa điểm trung bình từ thang điểm 10 sang thang điểm 4 bằng Min-Max Normalization
-Xác định kết quả xét tuyển đại học (KQXT) dựa trên khối thi và điểm thi DH1, DH2, DH3
-Lưu dữ liệu sau xử lý ra file processed_dulieuxettuyendaihoc.csv
#Kết quả
-Dữ liệu sau xử lý không còn giá trị thiếu
-Các biến mới được tạo gồm:
-Điểm trung bình môn theo từng năm
-Biến xếp loại học lực
-Biến chuẩn hóa thang điểm 4
-Biến kết quả xét tuyển (đậu/rớt)
-Dữ liệu đã được chuẩn hóa và sẵn sàng cho các bước phân tích và học máy tiếp theo-
