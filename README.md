# data-visualization-project
# Ứng Dụng Phân Tích Dữ Liệu Trong Dự Báo Nghỉ Việc Nhân Sự

[![GitHub repo size](https://img.shields.io/github/repo-size/maihonghai2004/data-visualization-project?style=for-the-badge)](https://github.com/maihonghai2004/data-visualization-project)
[![GitHub last commit](https://img.shields.io/github/last-commit/maihonghai2004/data-visualization-project?style=for-the-badge)](https://github.com/maihonghai2004/data-visualization-project/commits/main)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

## 📊 Giới Thiệu Đồ Án

Đồ án môn "Tương Tác Dữ Liệu Trực Quan" này tập trung vào việc **ứng dụng phân tích dữ liệu để dự báo nguy cơ nghỉ việc của nhân sự (Employee Attrition Prediction)**. Mục tiêu là giúp các doanh nghiệp, đặc biệt là phòng ban Nhân sự (HR), hiểu rõ các yếu tố ảnh hưởng đến quyết định nghỉ việc của nhân viên và đưa ra các chiến lược giữ chân nhân tài hiệu quả, giảm thiểu chi phí phát sinh từ việc thay thế nhân sự.

Chúng tôi đã sử dụng bộ dữ liệu **IBM HR Analytics Employee Attrition & Performance** để thực hiện phân tích chuyên sâu, xây dựng mô hình dự đoán và trực quan hóa các insight quan trọng.

## 🚀 Tính Năng Chính

* **Phân tích Thăm dò Dữ liệu (EDA):** Khám phá cấu trúc dữ liệu, tìm kiếm các mối quan hệ và xu hướng sơ bộ.
* **Tiền xử lý Dữ liệu:** Xử lý dữ liệu bị thiếu, chuẩn hóa và mã hóa các biến để chuẩn bị cho quá trình mô hình hóa.
* **Xây dựng Mô hình Dự đoán:** Áp dụng các thuật toán học máy (ví dụ: Logistic Regression, Random Forest, Gradient Boosting) để dự đoán khả năng nghỉ việc của nhân viên.
* **Trực Quan Hóa Dữ Liệu Tương Tác:** Phát triển các biểu đồ và dashboard trực quan, dễ hiểu, giúp người dùng khám phá dữ liệu và insight một cách tương tác.
* **Báo cáo Phân tích Chuyên sâu:** Tổng hợp các phát hiện, khuyến nghị và giải pháp dựa trên dữ liệu và mô hình.

## 📂 Cấu Trúc Thư Mục

Dự án được tổ chức như sau:
data-visualization-project/
├── Data/                             # Chứa bộ dữ liệu gốc và các file dữ liệu liên quan
├── Notebooks/                        # Chứa các file Jupyter Notebooks cho phân tích và mô hình
├── Reports/                          # Chứa tài liệu báo cáo và các file xuất bản
│   ├── Báo cáo đồ án tương tác dữ liệu trực quan.docx # Báo cáo chi tiết (Word)
│   └── Dashboard_Reports.pdf         # Bản PDF của Dashboard hoặc báo cáo tóm tắt
└── dashboard_export_20250514T090006.zip # File export từ dashboard
├── README.md                         # File bạn đang đọc này


## 🛠️ Công Nghệ & Thư Viện Sử Dụng

* **Ngôn ngữ lập trình:** Python
* **Thư viện phân tích & tiền xử lý:** Pandas, NumPy
* **Thư viện trực quan hóa:** Matplotlib, Seaborn, Plotly
* **Thư viện học máy:** Scikit-learn
* **Công cụ:** Jupyter Notebook, Docker, Apache Superset 

## 📈 Dashboard & Báo Cáo

Chúng tôi đã phát triển một Dashboard tương tác mạnh mẽ nhằm cung cấp cái nhìn toàn diện và chuyên sâu về các yếu tố ảnh hưởng đến tỷ lệ nghỉ việc của nhân sự. Dashboard này giúp các nhà quản lý và phòng ban HR:

Hiểu rõ các xu hướng và mô hình trong dữ liệu nghỉ việc.
Xác định các yếu tố rủi ro chính dẫn đến việc nhân viên rời đi.
Đưa ra quyết định dựa trên dữ liệu để xây dựng các chiến lược giữ chân nhân tài hiệu quả.
Ngoài Dashboard, báo cáo chi tiết của đồ án cung cấp phân tích sâu hơn về phương pháp luận, kết quả mô hình và các khuyến nghị cụ thể.

Dashboard Report (PDF): [Dashboard_report](https://github.com/maihonghai2004/data-visualization-project/blob/8d7db46855ace3a93ff7a671d36990a65efc9d66/Dashboard_Reports.pdf) 
Báo cáo Đồ Án Chi Tiết (Word): [Báo cáo đồ án tương tác dữ liệu trực quan.docx](https://github.com/maihonghai2004/data-visualization-project/blob/8d7db46855ace3a93ff7a671d36990a65efc9d66/B%C3%A1o%20c%C3%A1o%20%C4%91%E1%BB%93%20%C3%A1n%20t%C6%B0%C6%A1ng%20t%C3%A1c%20d%E1%BB%AF%20li%E1%BB%87u%20tr%E1%BB%B1c%20quan.docx)

## 👥 Thành Viên Nhóm

Dự án được thực hiện bởi Nhóm 9, sinh viên ngành Kỹ Thuật Dữ Liệu, Trường Đại học Sư phạm Kỹ thuật TP. HCM.

Giảng viên hướng dẫn: TS. Lê Quang Thái

| STT | Họ và Tên Sinh Viên | Mã số sinh viên | Tỉ lệ % tham gia | Mô tả nhiệm vụ |
| :-- | :------------------ | :-------------- | :--------------- | :-------------- |
| 01  | Mai Hồng Hải        | 22133014        | 100%             | Xác định các nhóm nhân sự có nguy cơ nghỉ việc cao. Phân tích mô hình dự đoán, huấn luyện mô hình và đánh giá kết quả. |
| 02  | Nguyễn Công Đôn     | 22133013        | 100%             | Phụ trách Data Storytelling, trực quan hóa tình hình nhân sự, báo cáo tổng hợp và trình bày cuối. |
| 03  | Nguyễn Tấn Hùng     | 22133027        | 100%             | Phân tích EDA (Exploratory Data Analysis), xử lý dữ liệu, trực quan hóa biểu đồ phân tích các yếu tố ảnh hưởng đến quyết định nghỉ việc. |

## 📧 Liên Hệ

Nếu có bất kỳ câu hỏi hoặc góp ý nào về dự án, vui lòng liên hệ với nhóm thông qua địa chỉ email của các thành viên hoặc mở một [Issue](https://github.com/maihonghai2004/data-visualization-project/issues) trên GitHub.

---

