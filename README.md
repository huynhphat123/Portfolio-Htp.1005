### 🧬 Trang web danh mục đầu tư cá nhân đáp ứng sử dụng HTML CSS Javascript | Chế độ tối/sáng của UM-XAIR
<div align="center">
<img src="https://github.com/um-xair/html-css-js-personal-portfolio-1/blob/main/images/maindarkhtp" align="center" style="width: 100%" />
<br />
<img src="https://github.com/um-xair/html-css-js-personal-portfolio-1/blob/main/images/mainlighthtp" align="center" style="width: 100%" />
</div>  
  
<br />

Dự án này triển khai một website portfolio cá nhân với HTML, CSS, và JavaScript, hỗ trợ chuyển đổi chế độ sáng và tối để cải thiện trải nghiệm người dùng.
## Cấu trúc HTML:

- Khai báo HTML5: File HTML bắt đầu với <!DOCTYPE html>.
Phần <head>:
Meta tags thiết lập bộ ký tự, chế độ xem cho thiết bị di động, và tiêu đề trang.
Thư viện CSS và Boxicons được liên kết qua thẻ <link>.
Phần <body>:
Bao gồm các phần: Header, Home, About, Services, Portfolio, Testimonial, Contact và Footer.

## JavaScript (scripts.js):

Chế độ Tối/Sáng:

Chuyển đổi giữa chế độ sáng và tối khi người dùng click vào icon tương ứng.
Sử dụng document.querySelector() để chọn các icon trong thanh điều hướng và thêm sự kiện click.
Lớp CSS 'dark-mode' được áp dụng hoặc gỡ bỏ trên thẻ <body>.
Chức năng cuộn (scroll):

Liên kết được làm nổi bật dựa trên phần nội dung hiện tại.
Thanh điều hướng sẽ trở nên "cố định" (sticky) khi người dùng cuộn xuống một khoảng nhất định.
Hiệu ứng Swiper:

Sử dụng thư viện Swiper để tạo carousel trong phần đánh giá (testimonial).
Hỗ trợ phân trang và các nút điều hướng.
Hiệu ứng cuộn (Scroll Reveal):

Thêm hiệu ứng mượt mà khi các phần tử xuất hiện trong khung nhìn.
