# Phân Tích và Xây Dựng Mô Hình Dự Đoán Nồng Độ CO Trong Không Khí


## Bộ dữ liệu: 
- [Air Quality Data Set](https://archive.ics.uci.edu/ml/datasets/Air+quality)


## Nội dung đồ án:
- Tìm hiểu về bộ dữ liệu
- Xử lý dữ liệu:
  + Datatype
  + Missing values và tạo ra 2 bộ dữ liệu mới:
    * Air Quality–REMOVE
    * Air Quality–MEAN
- EDA:
  + Thống kê mô tả
  + Ma trận tương quan
  + Regression plot
  + Residual plot
  + Histogram plot
  + Box plot
- Hướng tiếp cận:
  + Feature Scaling
  + Linear Regression
  + Decision Tree Regression
  + Random Forest Regression
  + Support Vector Regression
  + Artificial Neural Network 
  + Độ đo đánh giá:
    * R-Squared
    * Mean Squared Error (MSE) 
    * Root Mean Squared Error (RMSE)
    * Mean Absolute Error (MAE)
- Phân tích ANOVA


<center>
    <img src="https://github.com/PhamThe-KHDL/DS304.M21-Experimental-Design-and-Analysis/blob/main/FINAL%20PROJECT/Quy%20Tr%C3%ACnh%20ANOVA.png" width="400" alt="ANOVA" />
</center>

- Kết quả: Kết quả tốt nhất mà chúng tối đạt được là mô hình Support Vector Regression được huấn luyện trên bộ dữ liệu REMOVE ANOVA đơn thuộc tính, với độ đo **RMSE = 0.3789**
