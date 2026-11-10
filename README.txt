NEXUS – FANTASY GAME WEBSITE TEMPLATE
Version 1.0.0

==================================================

1. GIỚI THIỆU
   ==================================================

NEXUS là một website template theo phong cách Fantasy / Magic Game,
được xây dựng bằng HTML, CSS và JavaScript.

Template được thiết kế để làm nền tảng cho:

* Website giới thiệu game Fantasy.
* Landing page cho game.
* Website cộng đồng game.
* Giao diện đăng ký và đăng nhập người chơi.
* Giao diện quản trị User/Admin.
* Dashboard người chơi.
* Giao diện quản lý tài khoản và yêu cầu Admin.

Template có thể được chỉnh sửa, đổi nội dung, hình ảnh, màu sắc,
logo và bố cục để phù hợp với dự án riêng của người sử dụng.

==================================================
2. CÔNG NGHỆ SỬ DỤNG
====================

* HTML5
* CSS3
* JavaScript
* LocalStorage của trình duyệt
* Google Fonts
* Font Awesome CDN

Không yêu cầu cài đặt PHP, Node.js, MySQL hoặc database server
để chạy bản demo hiện tại.

==================================================
3. CẤU TRÚC THƯ MỤC
===================

NEXUS-TEMPLATE/
│
├── index.html
├── style.css
│
├── admin/
│   ├── css/
│   │   ├── admin.css
│   │   ├── aprove-admin.css
│   │   ├── dkadmin.css
│   │   ├── login.css
│   │   ├── panel-admin.css
│   │   └── register.css
│   │
│   └── html/
│       ├── admin.html
│       ├── APPROVE-ADMIN.HTML
│       ├── LOGIN.html
│       ├── panel-admin.html
│       └── REGISTER-ADMIN.html
│
├── user/
│   ├── css/
│   │   ├── dnuser.css
│   │   └── game.css
│   │
│   ├── html/
│   │   ├── AN.HTML
│   │   ├── dnuser.html
│   │   └── game.html
│   │
│   └── img/
│       ├── *.png
│       ├── *.mp3
│       └── *.mp4
│
├── README.txt
├── CHANGELOG.txt
└── LICENSE.txt

==================================================
4. CÁC TRANG CHÍNH
==================

## TRANG CHỦ

File:
index.html

Chức năng:

* Landing page Fantasy.
* Điều hướng Home / World / News / Contact.
* Hiển thị hình ảnh và nội dung Fantasy.
* Video nền.
* Nhạc nền.
* Khu vực tài khoản.
* Đăng ký User.
* Liên kết đăng nhập User.
* Liên kết đăng nhập Admin.

## KHU USER

Các file chính:
user/html/dnuser.html
user/html/game.html

Chức năng:

* Đăng nhập User.
* Kiểm tra trạng thái tài khoản.
* Hiển thị thông tin người chơi.
* Dashboard Fantasy Game.
* Hiển thị Level.
* Hiển thị điểm.
* Hiển thị số trận thắng.
* Hiển thị Rank.
* Khu vực Nhiệm vụ.
* Khu vực Giải đấu.
* Khu vực Cửa hàng.
* Đăng xuất.

## KHU ADMIN

Các file chính:
admin/html/LOGIN.html
admin/html/admin.html
admin/html/panel-admin.html

Chức năng:

* Đăng nhập Admin.
* Dashboard quản trị.
* Thống kê User.
* Quản lý trạng thái User.
* Kích hoạt hoặc hủy kích hoạt User.
* Xóa User.
* Hiển thị yêu cầu Admin.
* Quản lý Admin.

## ĐĂNG KÝ ADMIN

File:
admin/html/REGISTER-ADMIN.html

Chức năng:

* Tạo yêu cầu đăng ký Admin.
* Nhập thông tin người đăng ký.
* Hỗ trợ tải ảnh.
* Gửi yêu cầu để Master Admin phê duyệt.

## PHÊ DUYỆT ADMIN

File:
admin/html/APPROVE-ADMIN.HTML

Chức năng:

* Xem yêu cầu đăng ký Admin.
* Phê duyệt yêu cầu.
* Quản lý yêu cầu Admin.

==================================================
5. CÁCH CHẠY
============

Cách 1 – Mở trực tiếp

1. Giải nén toàn bộ thư mục NEXUS-TEMPLATE.
2. Mở file:
   index.html
3. Website có thể chạy trực tiếp trên trình duyệt.

Khuyến nghị sử dụng:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox

Cách 2 – Chạy bằng Live Server

Nếu sử dụng Visual Studio Code:

1. Cài extension "Live Server".
2. Mở thư mục NEXUS-TEMPLATE bằng Visual Studio Code.
3. Nhấn chuột phải vào index.html.
4. Chọn "Open with Live Server".
5. Website sẽ được mở trong trình duyệt.

==================================================
6. HỆ THỐNG DỮ LIỆU
===================

Phiên bản hiện tại sử dụng LocalStorage của trình duyệt để lưu
dữ liệu demo như:

* User.
* Trạng thái User.
* Admin request.
* Trạng thái đăng nhập.
* Thông tin phiên đăng nhập.

Điều này có nghĩa dữ liệu hiện tại được lưu trên trình duyệt
của người sử dụng, không phải trên máy chủ.

==================================================
7. GIỚI HẠN HIỆN TẠI
====================

Đây là front-end template/demo và KHÔNG phải hệ thống backend
production hoàn chỉnh.

Template hiện tại không cung cấp:

* Database server.
* API server.
* Xác thực tài khoản phía server.
* Mã hóa mật khẩu phía server.
* Phân quyền bảo mật phía server.
* Hệ thống thanh toán.
* Hệ thống multiplayer thực tế.
* Máy chủ game.
* Đồng bộ dữ liệu giữa nhiều thiết bị.

Không nên sử dụng phiên bản hiện tại làm hệ thống tài khoản
production nếu chưa bổ sung backend và các biện pháp bảo mật
phù hợp.

==================================================
8. TÙY CHỈNH TEMPLATE
=====================

Người mua có thể tùy chỉnh:

* Logo.
* Tên website.
* Màu sắc.
* Font chữ.
* Nội dung.
* Hình ảnh.
* Video.
* Nhạc.
* Nội dung Fantasy.
* Form đăng ký.
* Giao diện User.
* Giao diện Admin.
* Dashboard.
* Các trang HTML.

==================================================
9. TÀI NGUYÊN BÊN THỨ BA
========================

Template có tham chiếu đến một số tài nguyên bên thứ ba như:

* Google Fonts.
* Font Awesome.

Quyền sử dụng các tài nguyên bên thứ ba tuân theo giấy phép và
điều khoản riêng của từng nhà cung cấp.

Người mua có trách nhiệm kiểm tra giấy phép của các tài nguyên
được sử dụng trong dự án cuối cùng.

==================================================
10. HÌNH ẢNH / AUDIO / VIDEO
============================

Các file trong thư mục:

user/img/

bao gồm hình ảnh, âm thanh và video được sử dụng cho giao diện
demo.

Trước khi phân phối thương mại, người bán phải xác minh quyền
sử dụng và quyền phân phối lại đối với từng tài nguyên.

Nếu một tài nguyên không được phép phân phối lại, tài nguyên đó
phải được thay thế hoặc loại bỏ khỏi gói sản phẩm thương mại.

==================================================
11. HỖ TRỢ
==========

Template được cung cấp dưới dạng source code để người mua có thể
tự chỉnh sửa theo nhu cầu.

Người mua nên đọc toàn bộ tài liệu trước khi triển khai template
vào dự án thực tế.

Không có bảo đảm rằng template phù hợp với mọi hệ thống,
máy chủ, trình duyệt hoặc môi trường production.

==================================================
12. PHIÊN BẢN
=============

Current Version:
1.0.0

See CHANGELOG.txt for version history.

==================================================
END
===
