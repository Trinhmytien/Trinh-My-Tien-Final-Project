
# 🎮 Phân tích Doanh thu App Store & Chiến lược Hợp tác cho Business Development

## 📘 Giới thiệu
Dự án này phân tích dữ liệu **App Store Top Apps Revenue (9/2024–9/2025)** từ Sensor Tower nhằm khám phá xu hướng doanh thu toàn cầu, xác định các **publisher, game, và thể loại dẫn đầu**, đồng thời đưa ra **đề xuất hợp tác chiến lược cho bộ phận Business Development (BD)**.

---

## 🎯 Mục tiêu
- Phân tích biến động doanh thu theo thời gian để hiểu rõ xu hướng thị trường.
- Xác định **top publishers và top games** đóng góp lớn nhất cho tổng doanh thu.
- Đánh giá **thể loại game và mô hình monetization** đang chiếm ưu thế.
- So sánh hiệu quả giữa **app mới vs app cũ**.
- Đề xuất chiến lược hợp tác và ưu tiên danh mục đối tác cho BD.

---

## 🧩 Câu hỏi nghiên cứu
1. Doanh thu App Store 9/2024–9/2025 thay đổi thế nào?  
2. Ai là publisher dẫn đầu, và thị phần top publishers biến động ra sao?  
3. Game và sub-genre nào đang chiếm ưu thế doanh thu?  
4. App ra mắt mới có khác biệt gì so với app cũ về hiệu quả?  
5. BD nên hợp tác với publisher hoặc thể loại nào để tối đa hóa doanh thu?  

---

## 🧠 Dữ liệu & Phạm vi
- **Nguồn:** Sensor Tower – App Store Top Apps Revenue (Worldwide)  
- **Thời gian:** 25/09/2024 – 24/09/2025  
- **Chỉ số chính:** Revenue, Downloads, Publisher, Publisher Country  
- **Công cụ:** Google Colab (Python), Power BI, PowerPoint  

---

## ⚙️ Phương pháp nghiên cứu (Methodology)
| Giai đoạn | Mục tiêu | Công cụ | Kết quả |
|------------|-----------|---------|----------|
| **1. Thu thập dữ liệu** | Tải dữ liệu App Store Revenue từ Sensor Tower | Colab, Pandas | Dataset gốc (.tsv, UTF-16) |
| **2. Làm sạch & tiền xử lý** | Xử lý lỗi encoding, missing values, outlier, đổi dtype | Python (Pandas, NumPy) | Dataset sạch (.csv) |
| **3. Phân tích khám phá (EDA)** | Kiểm tra phân bố, xu hướng, sự khác biệt app mới/cũ | Matplotlib, Seaborn | Histogram, Boxplot |
| **4. Trực quan hóa & Insight** | Dashboard top apps/publishers, genre, market share | Power BI (DAX, KPI Cards) | Dashboard tổng hợp |
| **5. Storytelling & Recommendation** | Rút insight và đề xuất hành động cho BD | Power BI + PowerPoint | Báo cáo & slide trình bày |

---

## 📊 Kết quả mong đợi
- Bộ dữ liệu làm sạch và chuẩn hóa.  
- Dashboard trực quan hóa doanh thu toàn cầu, top publisher, game, sub-genre, và quốc gia.  
- Phân tích chi tiết giúp BD **xác định đối tác ưu tiên** và **chiến lược thể loại**.  

---

## ⚠️ Hạn chế nghiên cứu
- Chỉ sử dụng dữ liệu **App Store (iOS)**, chưa bao gồm Google Play.  
- Thiếu dữ liệu hành vi người chơi (retention, ARPU, LTV, UA spend).  
- Không phân tích các yếu tố định tính như marketing, IP license, mùa vụ.  
- Thời gian giới hạn 12 tháng, chưa đánh giá vòng đời dài hạn.  

---

## 🚀 Hướng mở rộng
- **Mở rộng dữ liệu:** Kết hợp Google Play, Steam, hoặc AppMagic.  
- **Phân tích hành vi:** Thêm các chỉ số retention, ARPU/ARPPU.  
- **Regional Deep Dive:** So sánh theo khu vực (SEA, TWHK, China, US).  
- **Clustering:** Nhóm game/publisher theo hành vi doanh thu.  
- **Automation:** Xây dựng pipeline tự động Python → Power BI → Dashboard.  

---

## 🧭 Dự kiến kết quả & Đóng góp
### Phân tích định lượng:
- Xác định top publishers và top games đóng góp doanh thu chính.  
- Đo lường biến động doanh thu và phân loại mô hình monetization dẫn đầu.  

### Đóng góp chiến lược BD:
- Hỗ trợ **ưu tiên hợp tác** với publisher tiềm năng (cao doanh thu, ổn định).  
- Xác định **thể loại có tiềm năng cao** và **rủi ro thấp** theo biến động doanh thu.  
- Đóng góp cho chiến lược mở rộng pipeline BD trong năm tới.  

---

## 🏁 Kết luận
Phân tích doanh thu App Store là bước quan trọng để hiểu thị trường, dự báo xu hướng và xây dựng **chiến lược hợp tác bền vững**.  
Kết quả dự án giúp đội ngũ BD có cái nhìn định lượng rõ ràng, từ đó ra quyết định dựa trên dữ liệu (*data-driven decision making*).

---

## 🛠️ Công nghệ sử dụng
- **Python:** Pandas, NumPy, Matplotlib, Seaborn  
- **Power BI:** DAX, Bar & Line chart, Scatter Chart  
- **Google Colab:** EDA, Data Cleaning  
- **PowerPoint:** Storytelling & Presentation  

---

