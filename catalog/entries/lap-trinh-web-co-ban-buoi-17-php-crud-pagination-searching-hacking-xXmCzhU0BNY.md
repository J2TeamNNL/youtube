# Lập trình web cơ bản buổi 17 PHP CRUD Pagination Searching Hacking

- **id:** `xXmCzhU0BNY`
- **url:** https://www.youtube.com/watch?v=xXmCzhU0BNY
- **published:** 2021-12-03
- **duration:** 6106s (~1h42m)
- **kind:** live
- **subtitle_source:** auto (ASR — có thể nhiễu / sai từ)
- **folder:** [`transcripts/lap-trinh-web-co-ban-buoi-17-php-crud-pagination-searching-hacking-xXmCzhU0BNY/`](../../transcripts/lap-trinh-web-co-ban-buoi-17-php-crud-pagination-searching-hacking-xXmCzhU0BNY/)
- **topics:** web, php, crud, pagination, searching, security
- **series:** Lập trình web cơ bản — buổi 17
- **channel:** UCnL9cDH4iZcLmOIF8SzNGYw

## Tóm tắt

Live buổi 17 series Lập trình web cơ bản — tiếp CRUD buổi 16 rồi làm Pagination, Searching và demo hacking. Đầu buổi dài chat / tâm sự / Q&A: cảnh báo đừng share link hosting hay demo công khai vì dễ bị hack lẫn nhau; nhắc phản biện vs cãi nhau; Q&A đồ án, PDO, tách file PHP… Khoảng ~34:40 vào bài: ôn Create + Read, thêm nút Sửa và Xóa cạnh từng bài trên danh sách. Form update lấy mã từ GET, SELECT điền sẵn form, POST rồi UPDATE theo mã. Delete gọn hơn — truyền mã, chạy DELETE (gợi ý confirm trước khi xóa). Xong đủ CRUD thì làm tìm kiếm: form search trên trang chủ, WHERE tiêu đề LIKE từ khóa, xử lý isset khi chưa search kẻo lỗi biến. Tiếp phân trang: giải thích vì sao không SELECT hết hàng triệu bài một lần, công thức số trang (làm tròn lên tổng / số bài mỗi trang), COUNT, LIMIT + OFFSET, link chuyển trang. Kết hợp giữ tham số tìm kiếm khi đổi trang. Phút cuối demo XSS: chèn HTML / script vào tiêu đề để điều hướng sang site khác hoặc lấy cookie; nhắc khái niệm SQL injection và không đưa code chưa lọc/validate lên production. Buổi sau sẽ tách file / tổ chức code gọn hơn.

## Mục lục

```
0:00 Chào live; cảnh báo share hosting/demo dễ bị hack; chat/Q&A/tâm sự (gộp)
34:39 Ôn Create+Read buổi 16; thêm nút Sửa/Xóa trên danh sách (gộp)
36:45 Form update: SELECT theo mã, điền sẵn, UPDATE (gộp)
51:46 Xóa bài: truyền mã + DELETE; gợi ý xác nhận (gộp)
54:39 CRUD đủ; bắt đầu Searching (gộp)
56:43 Form search + WHERE LIKE; isset biến tìm kiếm (gộp)
1:05:26 Xong search; phân trang: lý do + công thức số trang (gộp)
1:14:38 LIMIT / OFFSET; link trang (gộp)
1:26:15 Kết hợp pagination với searching (gộp)
1:29:20 Demo XSS/hacking; SQL injection; cảnh báo production (gộp)
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
