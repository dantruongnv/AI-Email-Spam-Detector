BÁO CÁO MÔN HỌC: TRÍ TUỆ NHÂN TẠO (AI)
Đề tài: Phân loại thư rác sử dụng trí tuệ nhân tạo

---

 1. Giới thiệu tổng quan
Dự án áp dụng thuật toán Học máy **Naive Bayes** kết hợp phương pháp biểu diễn văn bản **TF-IDF** để phân loại email thành **HAM** (thư thường) hoặc **SPAM** (thư rác). Hệ thống tích hợp trực tiếp với **Gmail API** để tự kiểm tra hộp thư đến và phân loại

---

2. HƯỚNG DẪN SỬ DỤNG
 
    B1.chuẩn bị api credentials.json từ OAuth 2.0 Client IDs (Đã enable GmailAPI)

    B2.Chuyển sang dự án google collab(Link ở AI_Email_Spam_Detector.ipynb )
  
    B3. Thả file credentials.json vào dự án(Thư mục files)

    B4.Chạy từng khung code và làm theo chỉ dẫn

4. Yêu cầu môi trường & Thư viện
- Môi trường: Google Colab / Python 3.x
- Thư viện chính: `pandas`, `scikit-learn`, `google-api-python-client`, `google-auth-oauthlib`

---

4. Lưu ý Bảo mật
Tệp `credentials.json` và `token.json` chứa thông tin xác thực cá nhân nên đã được thêm vào `.gitignore`. Không tải lên GitHub các tệp chứa chìa khóa này.
