# **Pizza Sales Analysis – Power BI Dashboard**

## Mục tiêu dự án
Phân tích dữ liệu bán hàng của chuỗi cửa hàng pizza nhằm đánh giá hiệu suất kinh doanh, hành vi mua hàng của khách, và các yếu tố ảnh hưởng đến doanh thu.  
Dự án giúp doanh nghiệp **nắm bắt xu hướng bán hàng**, **tối ưu chiến lược marketing**, và **cải thiện hiệu quả vận hành**.

---

## Nguồn dữ liệu
**Dataset:** `pizza_sales.csv`  
Bao gồm thông tin chi tiết về:
- Mã đơn hàng, ngày và giờ đặt hàng  
- Loại pizza, kích cỡ, số lượng, giá bán  
- Tổng giá trị đơn hàng  

---

## Phân tích & Chỉ số chính (KPIs)
Các chỉ số được tính toán bằng **SQL**, sau đó trực quan hóa bằng **Power BI**:

- **Total Revenue:** Tổng doanh thu từ tất cả đơn hàng  
- **Average Order Value (AOV):** Giá trị trung bình mỗi đơn hàng  
- **Total Pizzas Sold:** Tổng số pizza đã bán  
- **Total Orders:** Tổng số đơn hàng  
- **Average Pizzas per Order:** Trung bình số pizza trong mỗi đơn  

---

## Các biểu đồ và insight chính
1. **Daily Trend for Total Orders** – Biểu đồ cột thể hiện xu hướng đặt hàng theo ngày trong tuần  
2. **Hourly Trend for Orders** – Biểu đồ đường xác định khung giờ cao điểm  
3. **Sales by Pizza Category & Size** – Biểu đồ tròn thể hiện tỷ trọng doanh thu theo loại và kích cỡ pizza  
4. **Total Pizzas Sold by Category** – Biểu đồ phễu so sánh số lượng pizza bán ra giữa các danh mục  
5. **Top 5 Best Sellers / Bottom 5 Worst Sellers** – Biểu đồ xếp hạng sản phẩm bán chạy nhất và kém nhất  

**Một số insight nổi bật:**
- Doanh thu đạt đỉnh vào cuối tuần, đặc biệt là khung giờ 18:00–21:00  
- Size **L** và **M** chiếm hơn 70% tổng doanh thu  
- Dòng **Classic Pizza** có hiệu suất cao nhất trong các danh mục  

---

## Công cụ sử dụng
- **SQL (MySQL / SQL Server)** – Tính toán KPIs  
- **Power BI Desktop** – Trực quan hóa dữ liệu  
- **Excel** – Chuẩn bị dữ liệu và kiểm tra kết quả  

---

## Cách sử dụng
1. Tải file dự án: [`Pizza_Sales_Analysis.pbix`]([./Pizza_Sales_Analysis.pbix](https://github.com/xbumbleboo/Pizza-Sales-Analysis/blob/main/Pizza%20Sales%20Analysis.pbix))  
2. Mở bằng **Power BI Desktop** (phiên bản mới nhất)  
3. Chọn tab **Report View** để xem toàn bộ dashboard tương tác  
4. Có thể thay đổi filter hoặc slicer để xem chi tiết theo thời gian, loại pizza, kích cỡ,...


---

## 📬 Tác giả
**Tên:** Châu Nguyễn Quỳnh  
**Vai trò:** Data Analyst | SQL & Power BI Enthusiast
