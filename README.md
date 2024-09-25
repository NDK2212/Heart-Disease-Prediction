# Heart Disease Prediction

## Mô tả
Dự án này áp dụng thuật toán XGBoost để giải quyết một vấn đề học máy (Machine Learning) cụ thể. XGBoost là một thư viện mạnh mẽ dành cho các bài toán phân loại và hồi quy, sử dụng kỹ thuật boosting để tăng cường hiệu suất dự đoán.

## Các bước thực hiện:
1. **Tiền xử lý dữ liệu**: Chuẩn bị và làm sạch dữ liệu, bao gồm xử lý các giá trị thiếu, mã hóa các biến phân loại, và chuẩn hóa dữ liệu (nếu cần).
2. **Huấn luyện mô hình**: Áp dụng XGBoost trên tập dữ liệu đã xử lý.
3. **Đánh giá mô hình**: Đo lường độ chính xác của mô hình bằng cách sử dụng các thước đo hiệu suất như Accuracy, F1-score, ROC-AUC, hoặc MSE tùy vào loại bài toán.
4. **Điều chỉnh siêu tham số**: Sử dụng phương pháp Grid Search hoặc Random Search để tối ưu các siêu tham số của XGBoost, chẳng hạn như learning rate, max_depth, min_child_weight, v.v.

## Cài đặt
Để chạy dự án này, bạn cần cài đặt các thư viện sau:

```bash
pip install xgboost
pip install numpy
pip install pandas
pip install scikit-learn
```

## Hướng dẫn sử dụng

1. Clone repository:

```bash
git clone <URL_PROJECT>
cd <TEN_THU_MUC_PROJECT>
```

2. Chạy file huấn luyện mô hình:

```bash
python train.py
```

3. Thay đổi tham số trong file config hoặc trực tiếp trong code để điều chỉnh mô hình theo yêu cầu của bạn.

## Cấu trúc thư mục

- `data/`: Chứa tập dữ liệu đầu vào.
- `models/`: Chứa các mô hình đã được huấn luyện.
- `notebooks/`: Các notebook giải thích chi tiết các bước triển khai.
- `scripts/`: Các file mã nguồn Python chính.

## Đóng góp

Nếu bạn muốn đóng góp cho dự án, hãy tạo một pull request hoặc mở một issue để thảo luận thêm.
