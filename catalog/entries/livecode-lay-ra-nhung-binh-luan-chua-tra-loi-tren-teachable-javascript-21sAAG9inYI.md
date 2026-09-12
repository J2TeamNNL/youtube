# Livecode - Lấy ra những bình luận chưa trả lời trên Teachable - JavaScript

- **id:** `21sAAG9inYI`
- **url:** https://www.youtube.com/watch?v=21sAAG9inYI
- **published:** 2021-11-07
- **duration:** 4212s (~1h10m)
- **kind:** live
- **subtitle_source:** auto (ASR — có thể nhiễu / sai từ)
- **folder:** [`transcripts/livecode-lay-ra-nhung-binh-luan-chua-tra-loi-tren-teachable-javascript-21sAAG9inYI/`](../../transcripts/livecode-lay-ra-nhung-binh-luan-chua-tra-loi-tren-teachable-javascript-21sAAG9inYI/)
- **topics:** javascript, web, teachable
- **series:** Livecode
- **channel:** UCnL9cDH4iZcLmOIF8SzNGYw

## Tóm tắt

Buổi livecode không chuẩn bị sẵn (~1h10m): host vừa dậy, chuyển lịch dạy chiều để tránh trùng, vào thẳng bài toán thực tế trên Teachable — admin gần như không có tool lọc bình luận chưa trả lời, chỉ còn email thông báo nên dễ trôi, phải xóa mail đã xử lý để biết cái mới. Phân tích DOM: bình luận cha–con, trả lời có thể chèn giữa thread chứ không chỉ xuống cuối; kế hoạch lấy cha rồi kiểm tra có reply của instructor hay chưa. Mở Inspect → Snippets, nhúng jQuery CDN, dùng selector theo `data-*-id` / class để lấy parent comments; lần lượt debug `children` vs `find`, selector `:not`, gán biến, vòng lặp. Thử logic “gắn cờ” / lấy comment con cuối rồi nhận hạn chế timestamp kiểu relative (hôm nay / gần đây) không đủ giờ–phút–giây để so sánh chính xác — chấp nhận heuristic. Chốt cách kiểm tra badge instructor (span kiểu “in chapter”), nếu không có thì `style.background` tô vàng cha chưa trả lời; chạy thử, sửa bug selector, demo highlight. Cuối buổi tóm tắt còn khoảng vài dòng jQuery, bàn bookmarklet / Tampermonkey (giới hạn ký tự URL), thử `setTimeout` vs `onload` khi nhúng script, học thêm mẹo từ chat, nhắc bookmark tìm người trên Facebook, hứa để code ở comment video rồi chào — đi nấu cơm / ngủ tiếp.

## Mục lục

```
0:00 Chào; livecode không chuẩn bị; vấn đề Teachable thiếu lọc bình luận chưa trả lời (gộp)
6:00 Admin/preview & email dễ trôi; cấu trúc bình luận cha–con trên trang (gộp)
11:27 Inspect → Snippets; bắt đầu code JS trên Teachable
13:40 DOM data-id / class; nhúng jQuery CDN; selector lấy comment (gộp)
21:13 Parent comments; vòng lặp kiểm tra đã có reply chưa (gộp)
27:40 Lấy bình luận con; debug find vs children; selector :not (gộp)
37:00 Logic gắn cờ / comment cuối; hạn chế timestamp relative (gộp)
46:40 Badge instructor (span); highlight background vàng chưa trả lời (gộp)
51:00 Chạy thử, fix bug, demo highlight trên trang (gộp)
55:10 Tóm tắt logic jQuery; bookmarklet / Tampermonkey; onload; tip FB; chào (gộp)
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
