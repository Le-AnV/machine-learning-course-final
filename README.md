# Machine Learning – Practice Exercises Summary

Repo này tổng hợp toàn bộ các bài thực hành trong môn **Machine Learning**, bao gồm phân loại, hồi quy, phân cụm và MLP.
Mỗi bài được lưu trong thư mục **notebook/** và sử dụng dữ liệu trong **data/**.

---

## 📁 Cấu trúc thư mục

```
ML_REPORTFINAL/
│
├── data/
│   ├── amazon_products_sales_data_uncleaned.csv
│   ├── Mall_Customers.csv
│   └── Spam.csv
│
├── doc/
│   └── ReportFinal_ML_G8.pdf
│
├── notebook/
│   ├── Practice1_Classify Mail Spam.ipynb
│   ├── Practice2_Predicting Product Sales.ipynb
│   ├── Practice3_Clustering Customers.ipynb
│   └── Practice4_MLP_California Housing.ipynb
│
└── README.md
```

---

# 📌 Practice 1 – Classifying Spam Emails

**Người thực hiện:** _Phạm Gia Bảo – Lê Minh Duy Khang_
**Notebook:** `Practice1_Classify Mail Spam.ipynb`

**Tóm tắt nội dung:**

- Tiền xử lý văn bản: loại stopwords, ký tự đặc biệt, chuẩn hóa text.
- Chuyển đổi text → TF-IDF.
- Huấn luyện các mô hình phân loại: Logistic Regression, SVM, Naive Bayes.
- Đánh giá bằng Accuracy, Precision, Recall, F1-score.

---

# 📌 Practice 2 – Predicting Product Sales

**Người thực hiện:** _Lê Văn An_
**Notebook:** `Practice2_Predicting Product Sales.ipynb`

**Tóm tắt nội dung:**

- Làm sạch dữ liệu bán hàng Amazon.
- Xử lý missing values, outliers, mã hoá biến phân loại.
- Feature engineering: xu hướng theo mùa, độ phổ biến sản phẩm, hành vi khách hàng.
- Huấn luyện mô hình hồi quy: Linear Regression, Decision Tree, Random Forest, Gradient Boosting.
- Đánh giá bằng MSE, MAE, RMSE.

---

# 📌 Practice 3 – Customer Clustering

**Người thực hiện:** _Lê Văn An_
**Notebook:** `Practice3_Clustering Customers.ipynb`

**Tóm tắt nội dung:**

- Dùng tập dữ liệu Mall_Customers để phân cụm khách hàng.
- Khám phá dữ liệu (EDA), kiểm tra phân phối, outliers.
- Chuẩn hoá dữ liệu bằng StandardScaler.
- Thuật toán phân cụm: K-means, DBSCAN, Hierarchical.
- Đánh giá bằng Silhouette Score, Calinski-Harabasz và Davies-Bouldin.
- Trực quan hóa bằng scatter plot và dendrogram.

---

# 📌 Practice 4 – MLP Regression for House Price Prediction

**Người thực hiện:** _Dương Hưng – Nguyễn Việt Danh_
**Notebook:** `Practice4_MLP_California Housing.ipynb`

**Tóm tắt nội dung:**

- Dùng tập California Housing để dự đoán giá nhà.
- Chuẩn hoá dữ liệu và tách train/test.
- Xây dựng mô hình MLP dùng Keras: nhiều Dense layers, ReLU, output linear.
- Đánh giá bằng MSE, MAE, so sánh với Linear Regression / Decision Tree / Random Forest.
- Trực quan hoá Actual vs Predicted.

---

## 🎯 Mục đích của repo

- Tổng hợp toàn bộ bài thực hành ML trong môn học.
- Hệ thống hoá quy trình chuẩn của các bài toán ML.
