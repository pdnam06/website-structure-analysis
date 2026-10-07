# Phân tích cấu trúc trang web

Trang tham khảo: [Bootstrap](https://getbootstrap.com/). Quan sát ngày 07/10/2026.

Header nằm đầu trang, nhận diện thương hiệu. Navigation tập hợp liên kết tài liệu, ví dụ và tài nguyên. Content mở đầu bằng tiêu đề lớn cùng nút hành động, tiếp nối các phần hướng dẫn. Footer đặt cuối trang, chia nhóm liên kết và thông tin tác giả, giấy phép. Cách phân vùng giúp người đọc nhận biết nội dung và tìm điểm đến.

## Bố cục xây dựng lại

WebKit mô phỏng bố cục trên bằng HTML/CSS thuần: header tím chứa tên trang và 4 mục menu; hero căn giữa; các section nội dung có hai cột; footer chia nhóm liên kết và chứa bản quyền. Nội dung được viết mới, không sao chép mã hoặc dùng thư viện Bootstrap.

## Tổ chức thư mục

- index.html: cấu trúc và nội dung.
- style.css: định dạng, Flexbox, Grid, Media Query.
- analysis.md: phân tích trang thực tế.
- README.md: hướng dẫn chạy.
- desktop.png, mobile.png: ảnh kết quả.

Màn hình nhỏ hơn hoặc bằng 700px chuyển nội dung và footer về một cột, menu vẫn hiển thị đủ 4 mục.
