# Task 2 HTML5

Người thực hiện: Trung Kiên

Ngày thực hiện: 24/3, 26/3, 31/3


Mục lục:

[1. Phân biệt HTML và HTML5?](#html1)

[2. Tổng hợp thẻ HTML/HTML5](#html2)

--------

## 1. Phân biệt HTML và HTML5 <a name="html1"/>

| # | HTML | HTML5 |
|---|---|---|
| Definition | HTML viết tắt của từ Hyper Text Markup Language có nghĩa là Ngôn ngữ đánh dấu siêu văn bản. HTML được dùng để phát triển Website.	| HTML5 là phiên bản mới của HTML với các chức năng mới. Trong đó Markup là yếu tố cốt lõi để tương tác với công nghệ web cho việc cấu trúc và trình bày nội dung. |
| Multi-media support	| HTML không hỗ trợ Video và Âm thanh |	HTML5 được tích hợp sẵn chức năng hỗ trợ video, âm thanh. |
| Geographical support | HTML hỗ trợ theo dõi vị trí người dùng nhưng quá trình này rất khó khăn nếu người dùng sử dụng thiết bị di động. |	HTML5 sử dụng Javascript Gelocation API để theo dõi vị trí bất cứ người dùng nào đang truy cập website. |
| Storage	| HTML sử dụng bộ nhớ cache của trình duyệt làm bộ nhớ tam thời. | HTML5 có nhiều tùy chọn để lưu trữ ví dụ như Application cache, SQL database, Web storage. Chúng ta có thể chạy JS trong nền bằng JS API có sẵn cho việc lưu trữ. |
| Communication | Trong HTML, giao tiếp giữa Client và Server bằng Streaming là Long Pooling (vì chúng không hỗ trợ Web Socket) | Trong HTML5, hỗ trợ Web Socket, giúp giao tiếp song song giữa Server và Client. |
| Browser compatibility | HTML tương thích với tất cả các trình duyệt (vì nó đã tồn tại quá lâu) | Trong HTML5, chúng ta có nhiều thẻ mới và bỏ đi một số thẻ. Vì thế, chỉ có một số trình duyệt hỗ trợ hoàn toàn HTML5. |
| Graphics support | Trong HTML, muốn làm đồ họa vector thì phải sử dụng Sliver light, Adobe Flash, VML... | Trong HTML5 Đồ họa vector được hỗ trợ mặc định với Canvas và SVG. |
| Threading | Trong HTML, giao diện trình duyệt tương tác với người dùng và Javascript trong cùng luồng. Điều này khiến cho hiệu suất trang web thấp | Trong HTML5, với JavaScript Web Worker API cho phép Javascript và Giao diện trình duyệt chạy trên các luồng khác nhau. | 
| Error handling | HTML không thể xử lý cú pháp không chính xác và các lỗi. | HTML5 có thể xử lý cú pháp không chính xác và các lỗi khác. |


## 2. Tổng hợp thẻ HTML <a name="html2"/>

- Thẻ <code>!DOCTYPE html</code>: dùng để khai báo loại tập tin
- Thẻ <code>html</code>: khai báo cho trình duyệt biết nội dung bên trong là HTML
- Thẻ <code>head</code>: chưa các thẻ bao gồm thông tin về trang web, như <code>meta, title,...</code>
- Thẻ <code>title</code>: khai báo tiêu đề của trang web
- Thẻ <code>meta</code>: chứa các thuộc tính dữ liệu của trang web như: <code>charset</code>: thông tin về bảng mã sử dụng trong trang web, <code>name</code>,...
- Thẻ <code>body</code>: chứa nội dung trang web
- Các thẻ định dạng văn bản: <code>h1, h2, p, strong, u, i, code,...</code>
- Thẻ <code>style</code> được dùng để thêm các định dạng CSS (Cascading style sheet)
- Tạo danh sách bằng cách dùng thẻ <code>ul</code> (hoặc <code>ol</code>) và <code>li</code> 
- Thẻ <code>div</code>: dùng để xác định một phần hoặc một bộ phận trong tài liệu HTML, tạo thành 1 container để có thể thêm các CSS, hoặc thao tác với JavaScript nhanh chóng.
- Thẻ <code>input</code>: dùng để tạo vùng cho người dùng nhập dữ liệu đầu vào. Có nhiều loại thuộc tính input khác nhau <code>button, text, password,...</code>
- Thẻ <code>img</code>: dùng để thêm hình ảnh vào tài liệu HTML.
- Thẻ <code>script</code>: dùng để thêm các lệnh/khối lệnh JavaScript
- Thẻ <code>table</code>: dùng để tạo bảng, bao gồm thêm các thẻ <code>tr, td, th</code> bên trong.
- Thẻ <code>area</code>: dùng để xác định một khu vực trong hình ảnh, có thể thực hiện các thao tác trên khu vực đó
- Thẻ <code>audio</code>: dùng để nhúng nội dung âm thanh vào tài liệu HTML, có 3 định dạng được hỗ trợ: MP3, WAV, OGG
- Thẻ <code>b</code>: in đậm văn bản
- Thẻ <code>base</code>: chỉ định một URL cơ sở hoặc đích cho các URL tương đối trong tài liệu
- Thẻ <code>br</code>: chèn 1 dòng trống vào tài liệu
- Thẻ <code>button</code>: tạo một nút có thể nhấp vào
- Thẻ <code>canvas</code>: dùng để vẽ đồ họa, thường dùng với các lệnh JavaScript
