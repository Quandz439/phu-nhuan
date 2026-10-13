# PROMPT XÂY DỰNG WEBSITE TRƯỜNG THPT CHUYÊN NGHIỆP — PREMIUM EDUCATION WEBSITE

## I. VAI TRÒ VÀ MỤC TIÊU

Hãy đóng vai một Senior Front-end Developer, UI/UX Designer và chuyên gia tối ưu hiệu suất website với nhiều năm kinh nghiệm.

Nhiệm vụ của bạn là thiết kế và lập trình một website giới thiệu trường trung học phổ thông tại Việt Nam, lấy cảm hứng từ các website giáo dục hiện đại, cao cấp và chuyên nghiệp.

Website phải mang lại cảm giác uy tín, học thuật, hiện đại, có bản sắc riêng của trường học Việt Nam. Không được tạo giao diện sơ sài như một bài tập HTML cơ bản hoặc sử dụng mẫu giao diện đại trà.

**Tên dự án:** Premium High School Website.

**Tên trường mặc định:** Trường Trung học Phổ thông Phú Nhuận.

Tên trường, logo, địa chỉ, thông tin liên hệ và các nội dung giới thiệu phải dễ dàng thay đổi khi cần. Không được tự bịa thành tích, số liệu hoặc thông tin chính thức của trường. Nội dung chưa xác minh phải được đánh dấu là dữ liệu mẫu.

## II. CÔNG NGHỆ BẮT BUỘC

Sử dụng các công nghệ sau:

- HTML5: xây dựng cấu trúc trang web theo ngữ nghĩa.
- CSS3: thiết kế giao diện, responsive, animation và hiệu ứng.
- JavaScript thuần: xử lý tương tác, menu, bộ lọc, form và các thành phần động.
- Google Fonts: sử dụng font chữ phù hợp với phong cách giáo dục cao cấp, có phương án dự phòng khi không tải được font.
- Lucide Icons hoặc SVG: tạo biểu tượng nhất quán, sắc nét.
- Có thể sử dụng thư viện AOS hoặc Intersection Observer API để tạo hiệu ứng khi cuộn trang; ưu tiên giải pháp nhẹ, hạn chế phụ thuộc bên ngoài.

Không sử dụng React, Vue, Angular, TypeScript, backend hoặc framework bắt buộc phải có bước build.

Website phải có thể chạy trực tiếp bằng trình duyệt hoặc qua tiện ích Live Server trong Visual Studio Code, đồng thời có khả năng triển khai trên GitHub Pages.

## III. ĐỊNH HƯỚNG THIẾT KẾ UI/UX

### 1. Phong cách tổng thể

Thiết kế theo phong cách Premium Education, kết hợp giữa sự trang trọng của môi trường giáo dục và tính hiện đại của website doanh nghiệp cao cấp.

Bảng màu gợi ý:

- Xanh navy: `#102A43`.
- Xanh đậm phụ: `#163B5C`.
- Trắng: `#FFFFFF`.
- Nền xám sáng: `#F4F7FA`.
- Vàng champagne làm màu nhấn: `#D6B36A`.
- Màu chữ chính: `#243447`.
- Màu chữ phụ: `#627386`.

Không sử dụng quá nhiều màu sắc cùng lúc. Màu vàng chỉ dùng cho các chi tiết cần nhấn mạnh.

### 2. Typography

- Tiêu đề lớn: Be Vietnam Pro hoặc Playfair Display kết hợp với Be Vietnam Pro.
- Nội dung: Be Vietnam Pro.
- Phân cấp rõ ràng giữa tiêu đề, tiêu đề phụ, nội dung và chú thích.
- Đảm bảo chữ tiếng Việt có dấu hiển thị chính xác.
- Không dùng quá nhiều kiểu chữ trong cùng một trang.

### 3. Nguyên tắc giao diện

- Bố cục có khoảng trắng rộng, căn chỉnh chính xác.
- Hình ảnh lớn, chất lượng cao, phù hợp với trường học Việt Nam.
- Sử dụng lưới bố cục nhất quán, bo góc vừa phải và bóng đổ tinh tế.
- Animation nhẹ nhàng, không gây rối mắt.
- Các nút bấm có trạng thái hover, focus và active rõ ràng.
- Tránh sử dụng gradient quá nhiều, hiệu ứng phát sáng, màu neon hoặc các chi tiết không phù hợp với môi trường giáo dục.
- Không sử dụng emoji thay cho biểu tượng giao diện chuyên nghiệp.
- Ưu tiên thiết kế độc đáo, có hệ thống nhận diện riêng.

## IV. CẤU TRÚC WEBSITE

Xây dựng website với các khu vực dưới đây. Có thể triển khai thành một website nhiều trang bằng HTML thuần, trong đó trang chủ là trang trung tâm.

### 1. Header và thanh điều hướng

Thiết kế header chuyên nghiệp gồm:

- Logo trường ở bên trái.
- Tên trường và dòng mô tả ngắn.
- Các mục điều hướng: Trang chủ, Giới thiệu, Tin tức, Hoạt động, Thành tích, Tuyển sinh, Liên hệ.
- Nút CTA nổi bật: “Thông tin tuyển sinh”.
- Menu cố định khi cuộn trang.
- Khi cuộn, header có thể thu gọn chiều cao và chuyển nền sang trắng với bóng đổ nhẹ.
- Menu trên điện thoại chuyển thành nút hamburger.
- Menu di động mở và đóng bằng JavaScript, có thể đóng bằng phím Escape và sau khi chọn mục điều hướng.

Logo cần có phương án thay thế bằng chữ viết tắt của trường nếu chưa có file logo thật.

### 2. Hero section — khu vực mở đầu

Đây là khu vực quan trọng nhất của trang chủ.

Yêu cầu thiết kế:

- Chiếm phần lớn chiều rộng màn hình.
- Hình ảnh nền lớn về khuôn viên trường, kiến trúc trường học hoặc học sinh trong môi trường học tập.
- Có lớp phủ tối vừa đủ để chữ nổi bật.
- Tiêu đề lớn: “Tri thức vững vàng — Tương lai rộng mở”.
- Đoạn giới thiệu ngắn về môi trường học tập, tinh thần sáng tạo và sự phát triển toàn diện.
- Hai nút CTA: “Khám phá nhà trường” và “Tìm hiểu tuyển sinh”.
- Có thể thêm nhãn nhỏ như “Môi trường học tập và phát triển toàn diện”.
- Hiệu ứng xuất hiện của tiêu đề và nút phải mượt mà, không làm chậm việc hiển thị nội dung.
- Có thể thêm chỉ báo cuộn xuống ở cuối khu vực.

Không sử dụng hình ảnh sai ngữ cảnh hoặc hình ảnh có watermark. Ưu tiên ảnh trường học thực tế khi người dùng cung cấp.

### 3. Khu vực giới thiệu tổng quan

Trình bày thông tin nhà trường bằng bố cục hai cột:

- Một bên là hình ảnh trường học.
- Một bên là nội dung giới thiệu.
- Có tiêu đề “Nơi nuôi dưỡng tri thức và khát vọng”.
- Giới thiệu lịch sử hình thành, định hướng giáo dục và môi trường học tập.
- Các liên kết “Tìm hiểu về chúng tôi” và “Giá trị cốt lõi”.

Bên dưới có thể trình bày ba giá trị cốt lõi:

1. Tri thức và tư duy.
2. Trách nhiệm và kỷ luật.
3. Sáng tạo và phát triển.

Nội dung chỉ là bản mẫu có thể chỉnh sửa, không được khẳng định đó là tuyên ngôn chính thức của trường nếu chưa có nguồn xác thực.

### 4. Khu vực số liệu nổi bật

Thiết kế các thẻ thống kê có hiệu ứng đếm số khi xuất hiện trong màn hình.

Các trường dữ liệu có thể gồm:

- Số năm phát triển.
- Số lượng học sinh.
- Số lượng giáo viên.
- Thành tích hoặc giải thưởng.

Chỉ hiển thị số liệu chính thức khi đã có dữ liệu xác minh. Nếu chưa có, hãy dùng nội dung như “Đang cập nhật” hoặc dữ liệu mẫu được ghi chú rõ ràng. Không bịa số liệu để làm giao diện có vẻ ấn tượng.

### 5. Khu vực tin tức và thông báo

Tạo một section tin tức chuyên nghiệp với tiêu đề “Tin tức và sự kiện”.

Mỗi thẻ tin tức gồm:

- Ảnh đại diện.
- Danh mục tin.
- Ngày đăng.
- Tiêu đề.
- Mô tả ngắn.
- Liên kết “Đọc thêm”.

Yêu cầu tính năng:

- Hiển thị tối thiểu ba thẻ tin trên màn hình desktop.
- Responsive trên tablet và mobile.
- Có nút “Xem tất cả tin tức”.
- Có thể lọc tin theo danh mục bằng JavaScript.
- Có trang chi tiết tin tức hoặc trang nội dung riêng.
- Có trạng thái hiển thị khi không có kết quả phù hợp.

Nếu không có hệ thống quản trị nội dung hoặc backend, hãy lưu dữ liệu tin tức mẫu trong một tệp JavaScript riêng và giải thích cách thêm tin mới.

### 6. Khu vực chương trình học và định hướng giáo dục

Thiết kế các thẻ nội dung về:

- Chương trình học.
- Phương pháp giảng dạy.
- Phát triển kỹ năng.
- Định hướng nghề nghiệp.
- Hoạt động nghiên cứu và sáng tạo.

Mỗi thẻ gồm biểu tượng SVG, tiêu đề, mô tả ngắn và liên kết tìm hiểu thêm.

Không khẳng định trường có chương trình đặc biệt hoặc hợp tác quốc tế nếu chưa được xác minh.

### 7. Khu vực hoạt động học sinh

Tạo một thư viện hình ảnh có phong cách tạp chí giáo dục.

Các danh mục gợi ý:

- Hoạt động học tập.
- Thể thao.
- Văn nghệ.
- Câu lạc bộ.
- Tình nguyện.
- Sự kiện ngoại khóa.

Yêu cầu:

- Bố cục ảnh dạng grid hoặc masonry giả lập bằng CSS.
- Ảnh có tỷ lệ hợp lý.
- Khi di chuột, ảnh phóng to nhẹ và xuất hiện lớp thông tin.
- Khi nhấn ảnh, mở lightbox để xem ảnh lớn.
- Có nút đóng lightbox, hỗ trợ phím Escape và nút điều hướng nếu có nhiều ảnh.
- Có thể lọc ảnh theo danh mục.

### 8. Khu vực thành tích và dấu ấn

Thiết kế section làm nổi bật các dấu ấn của nhà trường.

Có thể trình bày:

- Thành tích học tập.
- Cuộc thi học sinh giỏi.
- Hoạt động nghiên cứu khoa học.
- Hoạt động cộng đồng.
- Những câu chuyện và gương mặt tiêu biểu.

Sử dụng bố cục cân đối, hình ảnh chất lượng cao và tiêu đề rõ ràng.

Không tự tạo tên học sinh, giải thưởng, chứng nhận hoặc số liệu như thể đó là thông tin có thật. Hãy sử dụng dữ liệu mẫu có chú thích hoặc chờ người dùng cung cấp thông tin chính thức.

### 9. Khu vực tuyển sinh

Thiết kế một khu vực CTA nổi bật nhưng vẫn trang nhã.

Nội dung gồm:

- Tiêu đề “Bắt đầu hành trình học tập của bạn”.
- Giới thiệu ngắn về việc tìm hiểu chương trình tuyển sinh.
- Nút “Xem thông tin tuyển sinh”.
- Nút phụ “Liên hệ tư vấn”.

Có thể bố trí các thẻ thông tin:

- Đối tượng tuyển sinh.
- Hồ sơ cần chuẩn bị.
- Thời gian tuyển sinh.
- Hướng dẫn đăng ký.

Tất cả thông tin thời gian, điều kiện và hồ sơ phải được lấy từ dữ liệu chính thức hoặc đánh dấu là nội dung minh họa. Không tạo ra thời hạn tuyển sinh giả.

### 10. Khu vực câu hỏi thường gặp

Xây dựng FAQ bằng accordion sử dụng JavaScript.

Các câu hỏi gợi ý:

- Làm thế nào để tìm hiểu thông tin tuyển sinh?
- Nhà trường có những hoạt động ngoại khóa nào?
- Làm thế nào để liên hệ với trường?
- Có thể tìm thông tin và thông báo mới nhất ở đâu?

Yêu cầu:

- Nhấn để mở hoặc đóng câu trả lời.
- Có biểu tượng trạng thái.
- Hỗ trợ bàn phím và thuộc tính ARIA phù hợp.
- Không để câu trả lời hiển thị sai hoặc bị cắt trên điện thoại.

### 11. Khu vực liên hệ

Thiết kế section liên hệ gồm hai cột.

Cột thông tin:
- Địa chỉ.
- Số điện thoại.
- Email.
- Giờ làm việc nếu có dữ liệu.
- Liên kết bản đồ khi có địa chỉ chính xác.

Cột biểu mẫu:
- Họ và tên.
- Email.
- Số điện thoại tùy chọn.
- Chủ đề liên hệ.
- Nội dung tin nhắn.
- Checkbox đồng ý với thông báo quyền riêng tư nếu cần.
- Nút gửi thông tin.

Xử lý form:

- Kiểm tra các trường bắt buộc.
- Kiểm tra định dạng email.
- Hiển thị thông báo lỗi rõ ràng.
- Hiển thị thông báo thành công chỉ khi thao tác thực sự thành công.
- Không giả lập việc gửi email thành công nếu chưa có backend hoặc dịch vụ form.
- Nếu chỉ chạy ở phía trình duyệt, phải thông báo rằng form đang ở chế độ demo và hướng dẫn tích hợp dịch vụ nhận form thực tế.

### 12. Footer

Footer có nền xanh navy, bố cục ba hoặc bốn cột:

- Logo và giới thiệu ngắn.
- Liên kết nhanh.
- Thông tin liên hệ.
- Mạng xã hội.
- Thông báo bản quyền.
- Liên kết chính sách quyền riêng tư nếu cần.

Footer phải đồng bộ với màu sắc và phong cách toàn website.

### 13. Các trang phụ

Nếu có đủ thời gian, hãy xây dựng các trang HTML riêng:

- `about.html`: Giới thiệu nhà trường.
- `news.html`: Danh sách tin tức.
- `news-detail.html`: Chi tiết tin tức.
- `activities.html`: Hoạt động học sinh.
- `admissions.html`: Tuyển sinh.
- `contact.html`: Liên hệ.

Các trang phải sử dụng chung header, footer, hệ thống màu sắc và kiểu chữ. Không để liên kết dẫn đến trang không tồn tại.

Nếu chọn cấu trúc một trang duy nhất, các mục điều hướng phải cuộn đến đúng section thay vì tạo liên kết giả.

## V. HIỆU ỨNG VÀ TƯƠNG TÁC

Triển khai các tính năng bằng JavaScript thuần:

1. Header thay đổi khi cuộn.
2. Menu hamburger trên điện thoại.
3. Cuộn mượt đến các section.
4. Đánh dấu mục menu đang được xem.
5. Animation xuất hiện khi cuộn trang bằng Intersection Observer.
6. Hiệu ứng hover cho thẻ nội dung và hình ảnh.
7. Bộ lọc tin tức.
8. Bộ lọc thư viện ảnh.
9. Lightbox xem ảnh.
10. Accordion cho FAQ.
11. Kiểm tra dữ liệu biểu mẫu.
12. Nút quay lại đầu trang.
13. Hiệu ứng đếm số liệu khi xuất hiện trong viewport.
14. Hiển thị thông báo trạng thái cho thao tác của người dùng.

Mọi tương tác phải hoạt động thực tế. Không tạo nút chỉ để trang trí mà không có chức năng hoặc phản hồi rõ ràng.

Tôn trọng tùy chọn `prefers-reduced-motion` của người dùng và hạn chế animation không cần thiết.

## VI. RESPONSIVE DESIGN

Website phải hoạt động tốt trên:

- Desktop: từ 1200px trở lên.
- Laptop: 992px đến 1199px.
- Tablet: 768px đến 991px.
- Mobile: dưới 768px.

Yêu cầu:

- Không xuất hiện thanh cuộn ngang ngoài ý muốn.
- Menu không bị tràn.
- Hình ảnh tự điều chỉnh kích thước.
- Các cột chuyển thành một cột trên điện thoại.
- Kích thước chữ dễ đọc.
- Nút bấm đủ lớn để thao tác bằng cảm ứng.
- Không để chữ đè lên các thành phần quan trọng của hình nền.
- Kiểm tra cả chiều rộng 320px và các màn hình phổ biến khác.

Ưu tiên mobile-first khi viết CSS.

## VII. SEO, HIỆU SUẤT VÀ KHẢ NĂNG TIẾP CẬN

### SEO
- Có title và meta description riêng cho từng trang.
- Có thẻ Open Graph cơ bản.
- Dùng đúng thứ bậc H1, H2, H3.
- Sử dụng HTML ngữ nghĩa.
- Hình ảnh có alt phù hợp.
- Đường dẫn nội bộ tương đối, tương thích GitHub Pages.
- Có favicon và trang 404 nếu cấu trúc triển khai phù hợp.

### Hiệu suất
- Dùng ảnh có kích thước hợp lý.
- Sử dụng `loading="lazy"` cho ảnh nằm ngoài màn hình đầu tiên.
- Có thể dùng WebP khi có nguồn ảnh phù hợp.
- Tránh tải nhiều thư viện không cần thiết.
- Hạn chế CSS và JavaScript dư thừa.
- Không chặn việc hiển thị nội dung vì animation.
- Có phương án dự phòng khi font hoặc ảnh bên ngoài không tải được.

### Khả năng tiếp cận
- Đảm bảo độ tương phản chữ và nền.
- Có trạng thái focus rõ ràng.
- Dùng nhãn cho form.
- Hỗ trợ bàn phím.
- Dùng ARIA khi cần, không thay thế HTML ngữ nghĩa bằng các thuộc tính ARIA không cần thiết.

## VIII. CẤU TRÚC TỆP DỰ ÁN

Hãy tạo dự án theo cấu trúc sau:

```text
premium-high-school/
├── index.html
├── about.html
├── news.html
├── news-detail.html
├── activities.html
├── admissions.html
├── contact.html
├── 404.html
├── README.md
├── .nojekyll
├── assets/
│   ├── images/
│   │   ├── hero-school.webp
│   │   ├── school-campus.webp
│   │   ├── news/
│   │   └── activities/
│   ├── icons/
│   │   └── favicon.svg
│   └── fonts/
├── css/
│   ├── style.css
│   ├── responsive.css
│   └── pages.css
└── js/
    ├── main.js
    ├── news.js
    ├── gallery.js
    └── contact.js
```

Có thể điều chỉnh cấu trúc cho hợp lý, nhưng phải giữ mã nguồn có tổ chức, không gộp toàn bộ HTML, CSS và JavaScript vào một tệp quá dài.

Không tạo tệp rỗng chỉ để làm đẹp cấu trúc. Nếu một trang hoặc tính năng chưa được triển khai, hãy ghi rõ thay vì tạo liên kết giả.

## IX. QUY TẮC VIẾT MÃ

- Đặt tên class dễ hiểu và nhất quán.
- Tách nội dung, giao diện và hành vi thành các tệp riêng.
- Sử dụng CSS variables cho màu sắc, font, khoảng cách và bo góc.
- Tránh lạm dụng `!important`.
- Không dùng JavaScript inline nếu không cần thiết.
- Không dùng các hàm hoặc thư viện lỗi thời.
- Không nhúng thông tin bí mật hoặc API key vào mã nguồn.
- Không phụ thuộc vào đường dẫn tuyệt đối kiểu `/assets/...` nếu có thể làm hỏng website khi triển khai tại GitHub Pages.
- Dùng đường dẫn tương đối phù hợp cho tài nguyên và trang nội bộ.
- Kiểm tra tên tệp, chữ hoa/chữ thường và đường dẫn chính xác.
- Các ảnh minh họa phải có nguồn hợp pháp và không sử dụng hình ảnh có watermark.

## X. HƯỚNG DẪN TRIỂN KHAI GITHUB PAGES

Tạo file `README.md` bằng tiếng Việt, hướng dẫn chi tiết:

### Bước 1: Chuẩn bị
- Cài đặt Visual Studio Code.
- Tạo thư mục dự án.
- Mở thư mục trong VS Code.
- Chạy bằng Live Server để kiểm tra website.

### Bước 2: Tạo repository
- Đăng nhập GitHub.
- Tạo repository mới, ví dụ `premium-high-school`.
- Đặt repository ở chế độ Public nếu cần sử dụng GitHub Pages theo cấu hình thông thường.
- Đưa toàn bộ tệp dự án lên repository.

### Bước 3: Triển khai
- Mở repository.
- Chọn Settings.
- Chọn Pages.
- Trong phần Build and deployment, chọn Deploy from a branch.
- Chọn nhánh `main` và thư mục `/ (root)`.
- Lưu cấu hình và chờ quá trình triển khai hoàn thành.

### Bước 4: Truy cập
Với repository thông thường, URL dự kiến có dạng:

`https://TEN-TAI-KHOAN.github.io/TEN-REPOSITORY/`

Đây chỉ là mẫu URL. Hãy hướng dẫn người dùng thay thế bằng tên tài khoản và repository thật.

### Bước 5: Cập nhật website
- Chỉnh sửa nội dung và hình ảnh.
- Commit và push các thay đổi lên GitHub.
- Kiểm tra lại trang sau khi GitHub Pages cập nhật.

Giải thích rõ rằng website HTML/CSS/JavaScript tĩnh không tự cung cấp cơ sở dữ liệu, tài khoản đăng nhập hoặc chức năng gửi email phía máy chủ. Những chức năng đó cần backend hoặc dịch vụ bên ngoài.

## XI. QUY TRÌNH THỰC HIỆN

Thực hiện theo trình tự sau:

**Giai đoạn 1 — Lập kế hoạch**
- Xác định kiến trúc website.
- Xây dựng bảng màu và hệ thống typography.
- Lập danh sách các trang, section và tính năng.

**Giai đoạn 2 — Xây dựng giao diện**
- Viết HTML có cấu trúc rõ ràng.
- Xây dựng CSS cho desktop và mobile.
- Tạo các thành phần dùng chung.
- Thêm hình ảnh và biểu tượng phù hợp.

**Giai đoạn 3 — Lập trình tương tác**
- Viết JavaScript cho các tính năng đã yêu cầu.
- Kiểm tra tất cả các nút, liên kết, menu và biểu mẫu.
- Đảm bảo trạng thái lỗi và thành công được xử lý chính xác.

**Giai đoạn 4 — Kiểm thử**
- Kiểm tra đường dẫn và lỗi tải tài nguyên.
- Kiểm tra responsive trên nhiều kích thước màn hình.
- Kiểm tra console để tìm lỗi JavaScript.
- Kiểm tra điều hướng, bàn phím và biểu mẫu.
- Kiểm tra đường dẫn hoạt động khi triển khai dưới một repository GitHub Pages.

**Giai đoạn 5 — Bàn giao**
- Hoàn thiện toàn bộ mã nguồn.
- Viết README.
- Hướng dẫn cách thay logo, màu sắc, nội dung, hình ảnh và thông tin trường.
- Hướng dẫn triển khai GitHub Pages.
- Liệt kê những tính năng đang hoạt động, những tính năng cần dịch vụ bên ngoài và các dữ liệu còn cần bổ sung.

## XII. TIÊU CHÍ NGHIỆM THU

Website chỉ được xem là hoàn thành khi đáp ứng các tiêu chí:

1. Giao diện cao cấp, thống nhất và phù hợp với một trường THPT.
2. Có đầy đủ các section và trang đã cam kết.
3. HTML, CSS và JavaScript được tách biệt hợp lý.
4. Tất cả nút bấm và liên kết đều hoạt động đúng.
5. Menu di động hoạt động tốt.
6. Form không báo gửi thành công giả.
7. Không có dữ liệu thành tích hoặc tuyển sinh bịa đặt.
8. Không có lỗi JavaScript nghiêm trọng.
9. Không bị tràn ngang trên màn hình nhỏ.
10. Có README hướng dẫn chạy và triển khai GitHub Pages.
11. Có thể thay đổi nội dung mà không phải viết lại toàn bộ giao diện.
12. Không yêu cầu cài đặt backend hoặc quy trình build để chạy phiên bản cơ bản.

## XIII. YÊU CẦU ĐẦU RA CUỐI CÙNG

Bắt đầu xây dựng dự án ngay sau khi phân tích yêu cầu.

Nếu đang hoạt động trong môi trường lập trình có quyền tạo và sửa tệp, hãy trực tiếp tạo toàn bộ mã nguồn vào đúng cấu trúc dự án, sau đó chạy các bước kiểm tra có thể thực hiện.

Nếu chỉ hoạt động trong cửa sổ trò chuyện, hãy xuất mã nguồn theo từng tệp với tiêu đề và đường dẫn chính xác, bảo đảm nội dung các tệp liên kết với nhau. Chia thành nhiều phần nếu cần, nhưng không được tuyên bố đã tạo hoặc kiểm thử tệp khi chưa thực sự thực hiện.

Không chỉ đưa ra bản phác thảo hoặc đoạn code minh họa. Hãy ưu tiên sản phẩm có thể chạy được, có thiết kế hoàn chỉnh, chức năng rõ ràng và dễ triển khai.

**Mục tiêu cuối cùng:** Một website giới thiệu trường THPT mang phong cách cao cấp, chuyên nghiệp, hiện đại, hoạt động ổn định, dễ bảo trì và có thể xuất bản công khai bằng GitHub Pages.# phu-nhuan
