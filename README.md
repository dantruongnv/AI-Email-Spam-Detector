# AI-Email-Spam-Detector
Dự án AI phân loại thư rác tự động kết nối Gmail API

Dự án môn học: **Trí tuệ nhân tạo**

## 🌟 Giới thiệu dự án
Hệ thống AI tự động phát hiện và phân loại thư rác thời gian thực, tích hợp trực tiếp với hòm thư Gmail cá nhân thông qua **Gmail API**.

## 🛠️ Công nghệ & Thuật toán sử dụng
- **Ngôn ngữ:** Python 3.x
- **Môi trường:** Google Colab / Jupyter Notebook
- **Dữ liệu huấn luyện:** SMS Spam Collection Dataset (5,572 mẫu thư rác & thư thường)
- **Thuật toán Machine Learning:** Naive Bayes Classifier
- **Trích xuất đặc trưng ngôn ngữ:** TF-IDF Vectorizer
- **Xác thực API:** Google Cloud OAuth 2.0 & Gmail API

## 🚀 Quy trình xử lý của hệ thống (Workflow)
1. **Data Preprocessing:** Tải và làm sạch dữ liệu thư rác chuẩn quốc tế.
2. **Model Training:** Huấn luyện mô hình Naive Bayes đạt độ chính xác > 97%.
3. **Gmail API Connection:** Kết nối và đọc danh sách email chưa đọc từ Hộp thư đến (Inbox).
4. **Auto-Filtering:** Đưa email qua AI để dự đoán. Nếu là thư rác (Spam), hệ thống tự động gắn nhãn SPAM và di chuyển khỏi Inbox.
