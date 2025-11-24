📌 Giới Thiệu Dự Án (Project Overview)
--
Đây là dự án phân tích dữ liệu chuyên sâu nhằm xác định các yếu tố chính ảnh hưởng đến tỷ lệ hủy đặt phòng của khách sạn. Mục tiêu là cung cấp các thông tin chi tiết (actionable insights) giúp ban quản lý khách sạn tối ưu hóa chiến lược đặt phòng, kênh tiếp cận khách hàng, và chính sách giá để giảm thiểu tổn thất doanh thu.

🎯 Mục Tiêu Chính
--
*Đo lường Hiệu suất: Tính toán Tỷ lệ Hủy phòng tổng thể và phân tích theo thời gian.
*Phân khúc Khách hàng: Xác định nhóm khách hàng và kênh đặt phòng có xu hướng hủy cao nhất.
*Đánh giá Yếu tố Ảnh hưởng: Phân tích tác động của thời gian đặt trước (Lead Time), loại phòng, và giá phòng trung bình lên quyết định hủy của khách hàng.
*Đưa ra Đề xuất: Cung cấp các đề xuất dựa trên dữ liệu để cải thiện doanh thu và quản lý rủi ro.

## 🛠️ Công Cụ và Công Nghệ

| Công cụ | Mục đích |
| :--- | :--- |
| **SQL/Python (Pandas)** | Thu thập, làm sạch và chuẩn hóa dữ liệu thô. |
| **Power BI / Tableau** | Xây dựng Dashboard tương tác và trực quan hóa dữ liệu. |
| **GitHub** | Quản lý phiên bản và chia sẻ mã nguồn, tài liệu dự án. |

### 💡 Các Phát Hiện Chủ Yếu (Key Findings)

Dựa trên Dashboard Phân tích, các điểm nổi bật sau đã được rút ra:

#### 1. Tác động của Thời gian Đặt trước (Lead Time)
* Tỷ lệ hủy phòng **cao nhất** đối với các đơn đặt trước **hơn 200 ngày**, cho thấy rủi ro lớn khi khách hàng đặt phòng quá sớm.
* Ngược lại, những đơn đặt sát ngày có tỷ lệ hủy thấp nhất.

#### 2. Phân Tích Kênh Đặt Phòng
* Kênh **Online** chiếm phần lớn lượng đặt phòng (**63.99%**).
* Các kênh **Corporate** và **Complementary** có tỷ lệ hủy rất thấp, cho thấy độ ổn định và tin cậy cao của các đơn hàng này.
* Kênh Online và Offline có tỷ lệ hủy tương đối cao hơn so với các kênh B2B (Corporate/Aviation).

#### 3. Phân Tích Loại Phòng và Giá
* **Room Type 6** có tỷ lệ hủy cao nhất (**42%**) và cũng là loại phòng có giá trung bình cao nhất (khoảng **$182.21**).
* **Room Type 7** có tỷ lệ hủy thấp nhất (**23%**).

#### 4. Xu hướng Hàng Tháng
* Tỷ lệ hủy có xu hướng đạt đỉnh vào các tháng mùa hè/cuối năm (Ví dụ: Tháng **8/2018** đạt **47%**), điều này đòi hỏi các chính sách hủy linh hoạt hơn trong các giai đoạn này.

***

### 🚀 Đề Xuất Hành Động (Actionable Recommendations)

Dựa trên những phát hiện trên, các đề xuất sau được đưa ra để tối ưu hóa doanh thu và quản lý rủi ro:

* **Chính sách Đặt cọc cho Đặt trước Dài hạn:** Áp dụng chính sách đặt cọc không hoàn lại hoặc linh hoạt hơn cho các đơn đặt trước **hơn 90 ngày** để giảm thiểu rủi ro hủy phòng do thay đổi kế hoạch của khách.
* **Tập trung vào Kênh B2B:** Tăng cường hợp tác với các kênh **Corporate/Aviation** vì những kênh này mang lại khách hàng có độ cam kết cao hơn.
* **Tối ưu hóa giá Room Type 6:** Xem xét điều chỉnh giá hoặc thêm ưu đãi đặc biệt để tăng tính hấp dẫn và giảm tỷ lệ hủy của loại phòng đắt nhất này.
