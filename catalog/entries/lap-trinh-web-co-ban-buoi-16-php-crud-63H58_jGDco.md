# Lập trình web cơ bản buổi 16 PHP CRUD

- **id:** `63H58_jGDco`
- **url:** https://www.youtube.com/watch?v=63H58_jGDco
- **published:** 2021-11-30
- **duration:** 6875s (~1h54m)
- **kind:** live
- **subtitle_source:** auto (ASR — có thể nhiễu / sai từ)
- **folder:** [`transcripts/lap-trinh-web-co-ban-buoi-16-php-crud-63H58_jGDco/`](../../transcripts/lap-trinh-web-co-ban-buoi-16-php-crud-63H58_jGDco/)
- **topics:** web, php, crud, database
- **series:** Lập trình web cơ bản — buổi 16
- **channel:** UCnL9cDH4iZcLmOIF8SzNGYw

## Tóm tắt

Live buổi 16 series Lập trình web cơ bản — PHP CRUD: chào, chat, nhắc khóa chỉ PHP cơ bản (form → CRUD đơn giản, không đi sâu framework), cảnh báo hôm nay làm đủ xem/thêm/sửa/xóa nên người mới dễ choáng. Phần đầu dài tâm sự / chia sẻ (nổi tiếng, mạng xã hội, công cụ đăng chéo nội dung…), rồi Q&A vì sao nhiều site vẫn dùng WordPress / kéo-thả dù đầy lỗ hổng nếu không cập nhật — phần lớn web trên thế giới vẫn gắn PHP/CMS. Tiếp theo nói đồ án: gợi ý đề tài tin tức / bán hàng… yêu cầu đủ CRUD, phân khách hàng–quản lý, đăng nhập/đăng ký; nhắc lộ trình waterfall — phân tích thiết kế xong mới code, không tự ý sửa database khi đã duyệt. Vào bài (~1:08): giải thích CRUD (Create Read Update Delete) và thứ tự chuẩn — phải Insert có dữ liệu trước rồi mới xem/sửa/xóa. Demo phpMyAdmin trên localhost, tạo database utf8mb4 (hỗ trợ Unicode / emoji), bảng tin tức (id tự tăng, tiêu đề, nội dung, ảnh…). Làm form thêm bài (tiêu đề, nội dung, link ảnh — chưa dạy upload file), kết nối mysqli (host / root / mật khẩu / tên DB), INSERT vào bảng; debug bằng in câu SQL / `die` dừng tại chỗ. Tiếp theo trang index: SELECT toàn bộ tin tức, vòng lặp duyệt từng hàng in danh sách; nhớ set charset utf-8 kẻo lỗi font tiếng Việt. Làm trang xem chi tiết: lấy id từ `$_GET` trên URL, SELECT đúng một bài theo mã. Cuối buổi: hôm nay xong Create + Read; sửa/xóa để buổi sau; Q&A ngắn rồi tạm dừng.

## Mục lục

```
0:00 Chào live; intro PHP CRUD xem/thêm/sửa/xóa; chat mở đầu (gộp)
2:19 Tâm sự / chia sẻ dài (nổi tiếng, MXH, công cụ đăng chéo…) (gộp)
40:19 Quay lại buổi học; Q&A WordPress / PHP / CMS kéo-thả (gộp)
48:45 Q&A đồ án: đề tài tin tức, yêu cầu CRUD, đăng nhập… (gộp)
1:08:14 Bắt đầu CRUD: thứ tự Create trước Read/Update/Delete (gộp)
1:09:11 phpMyAdmin; tạo DB utf8mb4; bảng tin tức (gộp)
1:14:02 Form thêm bài + mysqli kết nối + INSERT (gộp)
1:31:02 index.php: SELECT + vòng lặp hiển thị danh sách (gộp)
1:40:06 Xem chi tiết bài: GET id + SELECT theo mã (gộp)
1:49:23 Tóm tắt Create+Read; sửa/xóa buổi sau; Q&A chào kết (gộp)
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
