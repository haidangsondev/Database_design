## Phân Tích và Thiết Kế Cơ Sở Dữ Liệu cho Website Bán Hàng 

### 1. Tổng Quan Dự Án
Dự án Phân Tích và Thiết Kế Cơ Sở Dữ Liệu cho Website Bán Hàng nhằm tạo ra một cấu trúc cơ sở dữ liệu vững chắc để hỗ trợ các chức năng của một nền tảng bán hàng trực tuyến. Cơ sở dữ liệu này được thiết kế để quản lý sản phẩm, khách hàng, đơn hàng, thanh toán và các thành phần cần thiết khác một cách hiệu quả, đảm bảo tính toàn vẹn, bảo mật và khả năng mở rộng.

Hệ thống sẽ lưu trữ thông tin chi tiết về sản phẩm, người dùng, đơn hàng, danh mục, đánh giá và các khía cạnh quan trọng khác của một cửa hàng trực tuyến, hỗ trợ giao dịch theo thời gian thực và cung cấp một nền tảng dữ liệu đáng tin cậy cho hoạt động và nhu cầu phân tích kinh doanh của website.

### 2. Các giai đoạn thiết kế 
#### 2.1 Phân tích và mô tả hệ thống 
- Phân tích hệ thống của các trang thương mại điện tử lớn như Tiki và Shopee bao gồm nhiều bước để xác định và thiết kế các chức năng, quy trình kinh doanh và yêu cầu người dùng, phân tích cơ sở dữ liệu,.. nhằm đáp ứng nhu cầu phức tạp của khách hàng và nhà cung cấp. 
  ![](./img/image.png)
  
  ![](./img/image1.png)
  
- Mô tả  hệ thống nhằm xác định các chức năng và các yêu cầu  đã phân tích từ các sàng thương mại điện tử lớn để xác định rõ các quy trình tiếp theo. Mô tả là bước thiết yếu để hiểu rõ hệ thống cần và phải có những gì. 
  ![](./img/image2.png)
  ![](../database_design/img/image4.png)
  ![](../database_design/img/image5.png)
  Và các usecase khác....
  ##### => Các chức năng sau khi phân tích và mô tả hệ thống: 
- **Admin**
    - Quản lí kho
    - Quản lí người dùng
    - Quản lí doanh thu
- **Nhân viên**
    - Quản lí khuyến mãi
    - Quản lí danh mục
    - Quản lí tồn kho 
    - Quản lí đơn hàng
    - Quản lí khách hàng
    - Quản lí sản phẩm
    - Quản lí tin tức 
    - Quản lí thống kê
    - Quản lí vận chuyển
- **Giao hàng** 
    - Quản lí đơn giao 
    - Quản lí vận chuyển
- **Khách hàng** 
    - Quản lí giỏ hàng
    - Quản lí đơn hàng cá nhân
    - Quản lí tài khoản
    - Đăng ký tài khoản
    - Tìm kiếm sản phẩm, xem sản phẩm, liên hệ,...
  #### 2.2 Đặc tả usecase 
- Đặc tả usecase sẽ mô tả một chức năng cụ thể đã phân tích ở hệ thống cung cấp cho người dùng và các bước thực hiện của từng chức năng đó.
  ###### ***Usecase Đăng ký***
![](../database_design/img/image6.png)
![](../database_design/img/image7.png)
  ###### ***Usecase Đặt hàng***
![](../database_design/img/image8.png)
![](../database_design/img/image9.png)
  ###### ***Usecase Tìm kiếm sản phẩm***
![](../database_design/img/image10.png)
![](../database_design/img/image11.png)
#### 2.3 Thiết kế thành phần dữ liệu 
  ###### ***Mô hình dữ liệu ở mức quan niệm (CDM)***
![](../database_design/img/image12.png)
