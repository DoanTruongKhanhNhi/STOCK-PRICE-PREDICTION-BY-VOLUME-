# DỰ ĐOÁN GIÁ CỔ PHIẾU THEO KHỐI LƯỢNG 
## Các bước thực hiện
* Đọc và hiển thị các thông tin từ file vnstock_listing_companies.csv.
* Viết hàm find_stock để tìm mã số cổ phiếu X dựa vào mã số sinh viên (MSSV) 1 thành viên nhóm tùy theo nhóm lựa chọn
* Hiển thị thông tin tương ứng của cổ phiếu X từ file vnstock_listing_companies.csv. Các thông tin cần hiển thị bao gồm: ticker, shortName, monthlyRecords
* Thực hiện thống kê số lượng giao dịch, giá Close trung bình, giá Close cao nhất, giá Close thấp nhất của cổ phiếu X trong khoảng thời gian từ tháng 8 đến tháng 9 năm 2023.
* Từ lịch sử giao dịch trên, thêm cột (Info01) cho biết giá Close mỗi ngày là lớn hơn (giá trị 1), nhỏ hơn (giá trị -1), bằng (giá trị 0), so với giá Open của ngày đó.
* Từ lịch sử giao dịch trên, tạo thêm cột (Info02) cho biết giá Close mỗi ngày giao dịch là tăng (giá trị 1), giảm (giá trị -1), bằng (giá trị 0), so với giá Close ngày trước đó. Lưu tất cả thông tin (bao gồm cả Info01 và Info02) ra file {X}_Stock.csv.
* Từ file X_Stock.csv trên, vẽ các đường [Open, High, Low, Close] của cổ phiếu X.
* Từ file X_Stock.csv trên, vẽ các biểu đồ dạng cột chứa thông tin Volume của cổ phiếu X.
* Từ file X_Stock.csv trên, xây dựng mô hình hồi quy tuyến tính diễn tả sự phụ thuộc của giá Close với Volume của cổ phiếu X.
* Dựa vào mô hình vừa xây dựng ở bước trên, nhập 10 giá trị Volume bất kì và đưa ra dự đoán giá Close tương ứng.
