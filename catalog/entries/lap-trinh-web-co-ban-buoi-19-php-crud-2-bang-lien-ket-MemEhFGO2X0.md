# Lập trình web cơ bản buổi 19 PHP CRUD 2 bảng liên kết

- **id:** `MemEhFGO2X0`
- **url:** https://www.youtube.com/watch?v=MemEhFGO2X0
- **published:** 2021-12-07
- **duration:** 6315s (~1h45m)
- **kind:** live
- **subtitle_source:** auto (ASR — có thể nhiễu / sai từ)
- **folder:** [`transcripts/lap-trinh-web-co-ban-buoi-19-php-crud-2-bang-lien-ket-MemEhFGO2X0/`](../../transcripts/lap-trinh-web-co-ban-buoi-19-php-crud-2-bang-lien-ket-MemEhFGO2X0/)
- **topics:** web, php, crud, database
- **series:** Lập trình web cơ bản — buổi 19
- **channel:** UCnL9cDH4iZcLmOIF8SzNGYw

## Tóm tắt

Live buổi 19 series Lập trình web cơ bản — CRUD hai bảng liên kết (sản phẩm + nhà sản xuất). Đầu buổi chat / tâm sự / Q&A: lịch livestream dày nên học đều đừng dồn cuối tuần; kể chuyện "tôi là ai" / mục đích sống và buổi hội thảo đa cấp; Q&A waterfall vs agile (đồ án chốt thời hạn vs phát triển thêm tính năng), nhóm đồ án / chấm theo phần từng người, mã không tồn tại thì đừng hiện lỗi PHP ra màn hình, và nên để ID trong dấu nháy SQL. Khoảng ~32:40 vào bài: quan hệ 1–n nhà sản xuất–sản phẩm, lưu mã nhà sản xuất trên bảng sản phẩm (khóa ngoại), schema đơn giản (mã, tên, ảnh, giá, mô tả — bỏ số lượng vì phức tạp kho/đơn). Tạo trang quản lý sản phẩm: SELECT danh sách, form thêm với dropdown nhà sản xuất (value = id), upload ảnh bằng enctype multipart + `$_FILES`, chuyển file từ thư mục tạm sang photo trên server. Tránh trùng tên bằng cách đặt tên theo `time()` + đuôi; chỉ lưu tên file vào DB. Tiếp theo Delete theo id; form Update SELECT điền sẵn — ô chọn file không prefill được nên hiện ảnh cũ, nếu không chọn ảnh mới thì giữ tên cũ (kiểm tra size), dropdown selected đúng nhà sản xuất. Cuối cùng JOIN hai bảng để hiện tên nhà sản xuất; SELECT product.* kèm alias cột bên kia kẻo name/id bị ghi đè. Buổi sau: giao diện khách (danh sách, chi tiết, tìm kiếm/phân trang), rồi session / đăng nhập / giỏ hàng.

## Mục lục

```
0:00 Chào live; tâm sự "tôi là ai"/mục đích sống; kể đa cấp (gộp)
13:48 Q&A waterfall vs agile; đồ án nhóm, chấm điểm, bảo vệ (gộp)
26:49 Q&A mã không tồn tại: đừng hiện lỗi code; quotes SQL quanh ID (gộp)
32:41 Vào bài: CRUD sản phẩm + nhà sản xuất; quan hệ 1-n; khóa ngoại (gộp)
42:12 Menu quản lý; SELECT danh sách; form thêm + select nhà sản xuất (gộp)
46:02 Upload ảnh: enctype, $_FILES, chuyển từ temp sang thư mục photo (gộp)
1:00:12 Trùng tên file; đặt tên theo time(); INSERT lưu tên ảnh (gộp)
1:11:00 Xóa sản phẩm (DELETE); form sửa + SELECT điền sẵn (gộp)
1:15:02 Sửa ảnh: giữ ảnh cũ nếu không chọn mới; selected nhà sản xuất (gộp)
1:28:08 JOIN 2 bảng: hiện tên nhà sản xuất; alias tránh ghi đè cột (gộp)
1:31:54 Q&A lộ trình buổi sau: giao diện khách, session, giỏ hàng (gộp)
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
