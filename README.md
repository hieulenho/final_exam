# FINAL_EXAM
---

## 📌 Nội dung chính

### 1. Làm sạch và tiền xử lý dữ liệu
- Chuyển đổi `Date` về định dạng datetime, đặt làm index
- Tính toán lợi suất logarit hàng ngày (`log return`)
- Xóa các dòng chứa NaN

### 2. Phân tích kỹ thuật cơ bản
- Tính và trực quan hóa các chỉ báo:
  - **SMA (Simple Moving Average)**: trung bình động đơn giản 20, 50 ngày
  - **EMA (Exponential Moving Average)**: trung bình động hàm mũ
  - **RSI (Relative Strength Index)**: chỉ báo sức mạnh tương đối

### 3. Phân tích thống kê
- Phân phối lợi suất hàng ngày (histogram)
- Tính **độ biến động theo tháng** (standard deviation)
- Phân tích tương quan giữa giá đóng cửa và các chỉ báo

### 4. Học máy cơ bản
- Tạo biến mục tiêu `Target`: giá hôm sau cao hơn hôm nay → 1, ngược lại → 0
- Chọn đặc trưng: SMA, EMA, RSI
- Chia tập train/test
- Huấn luyện mô hình **Logistic Regression**
- Đánh giá mô hình bằng **confusion matrix** và **classification report**

---

## 📈 Kết quả nổi bật

- Giá ADBE có xu hướng tăng đều, đặc biệt sau các sự kiện công nghệ lớn.
- SMA và EMA thể hiện tốt tín hiệu xu hướng.
- Logistic Regression đạt độ chính xác ~52%, tuy nhiên bị mất cân bằng lớp → cần cải tiến mô hình.
- Đề xuất thêm các chỉ báo kỹ thuật và mô hình mạnh hơn như Random Forest, XGBoost nếu mở rộng.

---

## Tác giả

> Thực hiện bởi: **Lê Nho Minh Hiếu**    
> Trường Đại học Công Nghê - VNU

---

