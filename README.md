<div align="center">
   <img src="https://raw.githubusercontent.com/huynhphat123/Portfolio-Htp.1005/main/images/mainlighthtp.png" align="center" style="width: 100%" />
   <br />
   <img src="https://raw.githubusercontent.com/huynhphat123/Portfolio-Htp.1005/main/images/maindarkhtp.png" align="center" style="width: 100%" />
</div>  
  
  
<br />

Mã HTML và JavaScript này triển khai chức năng chế độ tối và sáng cho trang web danh mục đầu tư cá nhân.

## Cấu trúc HTML:

- Tệp HTML bắt đầu với khai báo `<!DOCTYPE html>`, cho biết đây là tài liệu HTML5.
- Trong phần `<head>`, có các thẻ meta để xác định bộ ký tự, cấu hình viewport và tiêu đề cho trang web.
- Các thư viện CSS ngoài, bao gồm CSS tùy chỉnh và Boxicons, được liên kết bằng các thẻ `<link>`.
- Phần `<body>` chứa nội dung chính của trang web, bao gồm các phần cho trang chủ, giới thiệu, dịch vụ, danh mục đầu tư, đánh giá và liên hệ, cùng với phần footer.

## JavaScript (scripts.js):

- Mã JavaScript xử lý chức năng chuyển đổi giữa chế độ tối và sáng, khi nhấp vào biểu tượng tương ứng.
- Biểu tượng menu cho thanh điều hướng và biểu tượng chế độ tối được chọn bằng `document.querySelector()`.
- Các trình lắng nghe sự kiện (event listeners) được thêm vào các biểu tượng này để chuyển đổi các lớp và áp dụng các kiểu CSS cho chế độ tối.
- Chức năng liên kết mục đã cuộn (scroll section active link) làm nổi bật liên kết mục đang hiển thị trong thanh điều hướng dựa trên phần hiện tại trong cửa sổ xem.
- Chức năng thanh điều hướng dính (sticky navbar) thêm một lớp vào tiêu đề khi người dùng cuộn xuống một điểm nhất định.
- Thư viện Swiper được sử dụng để tạo ra một carousel đánh giá với phân trang và các nút điều hướng.
- Các hiệu ứng scroll reveal được triển khai để tạo hiệu ứng hoạt hình cho các phần tử khi người dùng cuộn trang, mang lại trải nghiệm người dùng mượt mà.

### Chức năng Chế độ Tối và Sáng:

- Khi nhấp vào biểu tượng chế độ tối, giao diện trang web sẽ chuyển đổi giữa chế độ tối và sáng.
- Chức năng này được thực hiện bằng cách chuyển đổi các lớp trên phần tử `body`, điều này sẽ áp dụng các kiểu CSS cho chế độ tối và sáng.
- Biểu tượng chế độ tối cũng thay đổi hình ảnh của nó để chỉ ra chế độ hiện tại (biểu tượng mặt trời cho chế độ sáng và biểu tượng mặt trăng cho chế độ tối).

## Giải thích về các phần cụ thể:

- Chức năng chế độ tối và sáng được điều khiển bởi JavaScript, nó thêm hoặc loại bỏ các lớp CSS dựa trên sự tương tác của người dùng.
- Phương thức `classList.toggle()` được sử dụng để chuyển đổi lớp 'dark-mode' trên phần tử `body`, điều này kích hoạt các kiểu CSS cho chế độ tối.
- Các trình lắng nghe sự kiện được thêm vào biểu tượng chế độ tối để phát hiện các cú nhấp chuột và chuyển đổi lớp chế độ tối theo đó.
- Các hiệu ứng scroll reveal được triển khai để thêm sự thú vị thị giác và nâng cao trải nghiệm người dùng bằng cách tạo hoạt ảnh cho các phần tử khi cuộn trang.

<br />

## Connect with Me 🌐
<a href="[https://www.tiktok.com/@html.devlyss](https://www.tiktok.com/@phattuan50)" target="_blank">
<img src=https://img.shields.io/badge/tiktok-%23000000.svg?&style=for-the-badge&logo=tiktok&logoColor=white alt=tiktok  height="50" width="210"" />
</a>
<a href="mailto:phathuynh897@gmail.com" target="_blank">
<img src="https://img.shields.io/badge/email-%23000000.svg?&style=for-the-badge&logo=gmail&logoColor=white" alt="email" height="50" width="210" />
</a>
