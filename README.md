# Apple stock prediction

**Ngôn ngữ lập trình:** Python

**Nền tảng lập trình:** Jupyter Notebook

**Các file nằm trong thư mục:**
+ file ipynb: stockprediction.ipynb (file source code chính)
+ file csv: apple_data.csv (file dữ liệu)

**Giới thiệu:**

Nhiều mô hình khác nhau sẽ được sử dụng để dự báo giá Đóng cửa điều chỉnh cho dữ liệu giá cổ phiếu của Công Ty Apple. Từ các chỉ số phân tích kỹ thuật đơn giản
(như đường Trung bình động – Moving Average), thuật toán Hồi quy tuyến tính (Linear Regression), các mô hình máy học từ đơn giản (k-Nearest Neighbor) đến phức tạp hơn (Prophet). Các phương pháp sẽ được ứng dụng lần lượt và so sánh kết quả để tìm ra được đâu là mô hình mang lại hiệu quả tối ưu nhất.

**Dữ liệu:**

Dữ liệu trong bài làm là dữ liệu giá đóng cửa điều chỉnh của Tập đoàn Apple, với interval cho mỗi điểm dữ liệu là 1 ngày, được lấy trong giai đoạn từ ngày 01/01/2012 đến ngày 31/03/2024. Dữ liệu được lấy trực tiếp từ Yahoo Finance thông qua API của yfinance.
