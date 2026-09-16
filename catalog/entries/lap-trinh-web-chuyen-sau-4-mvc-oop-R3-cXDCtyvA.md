# Lập trình web chuyên sâu - 4 - MVC & OOP

- **id:** `R3-cXDCtyvA`
- **url:** https://www.youtube.com/watch?v=R3-cXDCtyvA
- **published:** 2022-03-17
- **duration:** 6215s (~1h44m)
- **kind:** live
- **subtitle_source:** auto (ASR — có thể nhiễu / sai từ)
- **folder:** [`transcripts/lap-trinh-web-chuyen-sau-4-mvc-oop-R3-cXDCtyvA/`](../../transcripts/lap-trinh-web-chuyen-sau-4-mvc-oop-R3-cXDCtyvA/)
- **topics:** web, php, mvc, oop
- **series:** Lập trình web chuyên sâu — buổi 4 MVC & OOP
- **channel:** UCnL9cDH4iZcLmOIF8SzNGYw
- **transcript commit:** `2707df928cac2add9f17f72a26bffbfc49bfd28d`

## Tóm tắt

Live ~1h44m — **buổi 4** series **Lập trình web chuyên sâu**: chuyển MVC CRUD “nông dân” sang **OOP** trên PHP thuần, làm lại **một bảng lớp** (mã · họ · tên). Đầu buổi tâm sự dài (chuẩn bị bài, phiên bản PHP/Laravel khi dạy, độ khó ngành, lỗi production / rút kinh nghiệm) rồi ôn lại ẩn dụ nhà hàng MVC và bổ sung “quản lý” như bước vào hướng đối tượng. Livecode: `class` controller/model theo quy ước tên file, `public` method `index`/`all`, router → khởi tạo đối tượng → view. Giải thích **getter/setter** (lưu DB khác lúc in ra: họ–tên, giới tính 0/1, năm sinh → tuổi), tạm bỏ kế thừa. Tiếp tục create/store với object + INSERT; edit/update/delete kèm getter–setter; gom kết nối DB thành object/`factory` thay vì biến `$connect` rải rác. Kết: CRUD một bảng đã chạy với MVC+OOP, dễ sửa hơn procedural; buổi sau OOP hai bảng rồi Laravel.

## Mục lục

```
0:00 Alo; chuẩn bị kỹ; hứa dạy OOP dễ hiểu (gộp)
1:30 Phiên bản PHP / Laravel khi dạy trường; đồng hành (gộp)
3:00 Tâm sự: giải đáp lỗi · đi trước học viên (gộp)
6:00 Ngành IT khó · xem lại video · khóa chuyên sâu đi làm (gộp)
9:00 Truyền đạt · tuyển dụng · kết tâm sự nghề (gộp)
12:00 Tâm sự lỗi code / thiếu dấu · cảnh báo IDE (gộp)
15:00 Rút kinh nghiệm production · sự cố công ty (gộp)
21:00 Kết tâm sự; vào bài OOP hôm nay (gộp)
22:30 Ẩn dụ nhà hàng MVC + thêm “quản lý” (OOP) (gộp)
25:00 Router (Laravel có); bắt đầu bảng lớp mã·tên (gộp)
27:00 class LopController; quy ước tên file / class (gộp)
29:00 Hàm index; gọi Model lấy danh sách + view (gộp)
31:00 class Model Lop; hàm all(); new đối tượng (gộp)
33:00 View index lớp; luồng router → controller → model → view (gộp)
37:00 public function; visibility để gọi từ ngoài (gộp)
39:00 protected / kế thừa — bỏ qua hôm nay (gộp)
41:00 PHPIni Laravel digression; ý getter/setter (gộp)
43:00 Getter: lưu khác lúc in (họ–tên · giới tính · tuổi) (gộp)
46:00 Tách class object lớp; thuộc tính mã/họ/tên (gộp)
49:00 Getter họ–tên; gọi thuộc tính qua object (gộp)
52:00 Setter / viết tắt IDE; khai báo get–set (gộp)
55:00 Dùng getter khi render; format code (gộp)
58:00 Digression ngôn ngữ / tốc độ PHP vs khác (gộp)
1:01:00 Action create; form thêm lớp (gộp)
1:04:00 Form create → store; khai báo method store (gộp)
1:07:00 Store: POST → Model lưu; class Model insert (gộp)
1:09:00 Constructor / truyền giá trị; INSERT qua object (gộp)
1:11:00 Getter trong chuỗi; OOP tách lưu vs hiển thị (gộp)
1:15:00 Debug; OOP chuyển ngôn ngữ / Laravel sau dễ hơn (gộp)
1:17:00 Logic thêm prefix khi lưu trong Model (gộp)
1:19:00 Sửa Model một chỗ → form không hard-code (gộp)
1:21:00 Getter vs setter; gộp hàm lấy/lưu (gộp)
1:23:00 Link sửa theo mã; tách hàm find theo mã (gộp)
1:25:00 Edit: copy pattern; tìm lớp theo mã (gộp)
1:27:00 View edit + value getter; action update (gộp)
1:29:00 Update lớp; lỗi lặp getter/setter (gộp)
1:31:00 Fix update; delete; thuần OOP trước Laravel (gộp)
1:33:00 Delete chạy; biến connect → hướng object (gộp)
1:35:00 Class kết nối DB; tránh trùng tên hàm (gộp)
1:37:00 Factory / gom connect; bỏ khai báo nông dân (gộp)
1:39:00 Demo đủ CRUD MVC+OOP; dễ sửa hơn đồ án 1 (gộp)
1:41:00 Nên học OOP; buổi sau 2 bảng rồi Laravel; chào (gộp)
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
