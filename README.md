# House Price Prediction using Advanced Regression Techniques (Accuracy ~= 90%)

# Author: Ung Minh Hoài

[Kaggle dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview). 

Phân tích bao gồm EDA mở rộng và một số phương pháp xử lý được áp dụng cho các giá trị còn thiếu trong tập dữ liệu.

Một mô hình hồi quy tuyến tính được xây dựng. Nó được so sánh với các mô hình được xây dựng bằng RFE cũ đơn giản, và sau đó với các mô hình được xây dựng bằng kỹ thuật hồi quy Ridge và Lasso.

Cũng đã thử với các tham số của mô hình (chẳng hạn như nhân đôi giá trị của alpha) và cũng thử mô hình với một số tính năng bị loại bỏ.


## Explained 

Đầu tiên, các mô hình tuyến tính hoạt động dựa trên giả định rằng phân phối của biến độc lập và biến mục tiêu là tương tự nhau. Do đó, việc biết về độ lệch của dữ liệu giúp chúng ta tạo ra các mô hình tuyến tính tốt hơn.

https://www.analyticsvidhya.com/blog/2020/07/what-is-skewness-statistics/

