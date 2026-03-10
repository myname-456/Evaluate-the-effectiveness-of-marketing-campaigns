# Evaluate-the-effectiveness-of-marketing-campaigns
Đánh giá hiệu quả của các chiến dịch Marketing đã và đang thực hiện nhằm mục đích có thể loại bỏ các chiến dịch kém hiệu quả và tập trung nguồn lực cho các chiến dịch đạt được hiệu quả cao.

**Tổng quan dự án (Project Overview):** 
Dự án này tập trung vào việc phân tích dữ liệu từ các chiến dịch Marketing (Facebook Ads, Google Ads, Email Marketing) để đánh giá hiệu quả đầu tư. Mục tiêu chính là xác định các kênh mang lại giá trị cao nhất, tối ưu hóa chi phí thu hút khách hàng (CAC) và cải thiện tỷ lệ lợi nhuận trên chi phí quảng cáo (ROAS).

🎯 **Bài toán Kinh doanh (Business Problem)**

Doanh nghiệp đang vận hành nhiều chiến dịch trên các nền tảng khác nhau nhưng gặp khó khăn trong việc:

Xác định kênh nào thực sự mang lại chuyển đổi (Conversions).

Kiểm soát chi phí thu hút khách hàng (CAC) đang có xu hướng tăng cao.

Phân bổ ngân sách không hiệu quả giữa các nhóm khách hàng khác nhau.

🛠 **Công cụ & Kỹ thuật sử dụng (Tech Stack)**

SQL: Truy vấn và hợp nhất dữ liệu từ nhiều nguồn (Sales, Marketing, CRM).

Python (Pandas, Matplotlib/Seaborn): Làm sạch dữ liệu và phân tích tương quan giữa chi phí và doanh thu.

Power BI: Xây dựng Dashboard tương tác để theo dõi các chỉ số thời gian thực.

Marketing Metrics: CAC, ROAS, ROI, Conversion Rate, CTR.

📈 **Quy trình thực hiện (Workflow)**

Data Collection: Kết hợp dữ liệu chi phí quảng cáo và dữ liệu doanh thu từ hệ thống CRM.

Data Processing: Xử lý dữ liệu "messy", định dạng lại các cột ngày tháng và loại bỏ các bản ghi trùng lặp bằng Python/SQL.

Exploratory Data Analysis (EDA):

Phân tích hiệu quả theo từng kênh (Channel Performance).

Tính toán tỷ lệ chuyển đổi (Conversion Rate) theo từng nhóm đối tượng.

Dashboarding: Trực quan hóa hành trình khách hàng và hiệu quả ngân sách.

🖥 **Dashboard Preview**
<img width="1198" height="672" alt="Overview" src="https://github.com/user-attachments/assets/bebdccc4-181d-482a-b539-ff8ee5f06163" />

<img width="1173" height="664" alt="Segment by channel" src="https://github.com/user-attachments/assets/85ca90cf-3020-4cab-b0d0-9b1eb8474034" />

<img width="1162" height="671" alt="Segment by season" src="https://github.com/user-attachments/assets/5e81d0d4-0ac3-4d77-abc6-804fa0a7df0c" />

**Dữ liệu sử dụng trong dự án**: https://drive.google.com/drive/folders/1PcvnlnHWTJbgeTGRmYIcgS84z3IgGHJh?usp=drive_link
