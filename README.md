# FORECAST-TIP-EVERY-TIME-OF-GREEN-TAXI-IN-NEW-YORK-CITY
## Trong bài đồ án này, chúng tôi sẽ đi phân tích để làm sạch bộ dữ liệu “2020 Green Taxi Trip Data (January - June)” và phát triển phương pháp phù hợp cho bài toán dự đoán tiền boa trên bộ dữ liệu này.
## Để thực hiện, chúng tôi đã tìm hiểu sâu về ý nghĩa của các đặc trưng có trong bộ dữ liệu từ đó đưa ra những ràng buộc để loại bỏ hoặc thay thế những dữ liệu nhiễu, đồng thời chúng tôi có phát triển thêm các đặc trưng mới từ các đặc trưng đã có . Sau đó, chúng tôi sử dụng kĩ thuật phân tích thăm dò để kiểm tra sự tương tác giữa đặc trưng mục tiêu (tiền boa) với các đặc trưng còn lại, từ đó chọn ra những đặc trưng có tương quan với đặc trưng mục tiêu để phát triển phương pháp hồi quy cho việc dự đoán tiền boa. Bên cạnh đó, từ các đặc trưng phát triển thêm, chúng tôi vạch ra các hướng để phát triển bài toán. Cuối cùng, chúng tôi sẽ so sánh các phương pháp vơi nhau thông qua các thông số R2, Kfold validation để đưa ra phương pháp phù hợp nhất có thể cho bài toán của chúng tôi.
## Và phương pháp hồi quy đa thức với mô hình Polynomial Linear Regression cho chúng tôi kết quả khả quan nhất. Với kết quả R2 đạt đến 0.85 và K-fold validation là 0.79.
# Link các data sử dụng trong đồ án:
## 2019_Green_Taxi_Trip_Data.csv : https://drive.google.com/file/d/1IY8F2cQJ8uRA-sM5IsPrNX3vfpKmTj5b/view?usp=sharing
## Original.csv : https://drive.google.com/file/d/1IgImzOTAq2aflbPAmkJ8C66LZVfiK_6o/view?usp=sharing
## DataCleaning.csv : https://drive.google.com/file/d/1-9h6DAmemFaUczThPiqYkgO0JTp3T4-D/view?usp=sharing
