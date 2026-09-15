# Lập trình web cơ bản buổi 28 PHP Thống kê

- **id:** `T1RCc4zALNc`
- **url:** https://www.youtube.com/watch?v=T1RCc4zALNc
- **published:** 2022-01-07
- **duration:** 6249s (~1h44m)
- **kind:** live
- **subtitle_source:** auto (ASR — có thể nhiễu / sai từ)
- **folder:** [`transcripts/lap-trinh-web-co-ban-buoi-28-php-thong-ke-T1RCc4zALNc/`](../../transcripts/lap-trinh-web-co-ban-buoi-28-php-thong-ke-T1RCc4zALNc/)
- **topics:** web, php, thong-ke
- **series:** Lập trình web cơ bản — buổi 28
- **channel:** UCnL9cDH4iZcLmOIF8SzNGYw

## Tóm tắt

Live buổi 28 series Lập trình web cơ bản — PHP thống kê cho trang admin bán hàng. Đầu buổi nêu chủ đề (thống kê chủ yếu là SQL), bỏ qua xuất hóa đơn PDF/Excel (tự mò thư viện), báo tuần sau học Ajax và lộ trình bảo vệ đồ án gần Tết. Q&A dài: công nghệ Facebook (AI feed, ảnh nhiều kích cỡ, chuyển dần sang JS/React phía client, suy luận kỹ thuật khi dùng sản phẩm); chọn tỉnh/quận/huyện dạng select phụ thuộc + JSON; phân biệt tool với hack / quyền riêng tư ảnh; định kiến ngành CNTT và sống theo lương tâm; nhắc check mail/Discord khi thông báo bảo vệ; khuyên đừng nhảy Laravel khi PHP còn lơ mơ. Phần kỹ thuật: brainstorm chỉ số e-commerce (đơn theo thời gian, doanh thu, bán chạy / ế, thành viên, khách tiềm năng…), lọc theo schema hiện có (không tồn kho / mã giảm giá; địa chỉ một cột khó thống kê theo tỉnh). Live SQL: COUNT đơn + lọc khoảng thời gian; UI chọn ngày/tuần/tháng/năm; SELECT năm từ năm tạo site đến `date('Y')`; LEFT JOIN sản phẩm–chi tiết đơn–đơn, `SUM(quantity)`, `GROUP BY`, `status = 1`, `IFNULL`/`COALESCE` = 0; so sánh subquery vs JOIN; `ORDER BY` bán chạy và tie-break theo id nhập cũ; `SUM(total_price)` doanh thu; khách hàng tiềm năng JOIN + `ORDER BY` tổng chi. Cuối buổi soft tip Unicode/zero-width trong tên, validate khoảng trắng, động lực code lại sau burnout; hẹn buổi sau bình luận + đánh giá (Ajax).

## Mục lục

```
0:00 Chào; chủ đề thống kê (SQL); xuất HĐ thư viện (gộp)
2:56 Tuần sau Ajax/JS; UX không reload trang (gộp)
4:13 Lộ trình Tết; bảo vệ đồ án sớm (gộp)
4:48 Đồ án còn lại: giỏ hàng, đặt hàng, thống kê (gộp)
5:32 Q&A: Facebook dùng công nghệ gì (gộp)
7:38 AI feed / nhận diện khuôn mặt; ảnh nhiều kích cỡ (gộp)
9:11 SQL vs NoSQL; React/JS phía client (gộp)
12:44 Feed, realtime, suy luận kỹ thuật sản phẩm lớn (gộp)
23:25 Kết deep-dive Facebook; hướng mở khóa cơ bản (gộp)
25:02 Chọn tỉnh / quận / huyện (select phụ thuộc, JSON) (gộp)
31:04 Hack Facebook? Tool ≠ hack (gộp)
32:56 Quyền riêng tư ảnh “chỉ mình tôi”; giới hạn tool (gộp)
40:01 Định kiến con gái học CNTT (gộp)
42:03 Sống theo lương tâm vs định kiến người khác (gộp)
44:41 Nhắc check mail / Discord khi bảo vệ đồ án (gộp)
45:38 API → khóa sau; Laravel khi chưa rành PHP (gộp)
48:45 Tuần sau Ajax; vào bài thống kê admin (gộp)
49:00 Dashboard thống kê khi vào admin (gộp)
50:08 Brainstorm chỉ số web bán hàng (gộp)
54:03 Lọc chỉ số theo schema (không tồn kho / mã giảm giá) (gộp)
55:09 Schema quyết định thống kê; địa chỉ một cột (gộp)
58:27 Chỉ số làm được: đơn, bán chạy, doanh thu, thành viên (gộp)
59:01 Lượt truy cập / Google Analytics (gộp)
59:52 Khách hàng tiềm năng (JOIN hóa đơn) (gộp)
1:00:14 SQL không UI; COUNT đơn theo khoảng thời gian (gộp)
1:03:11 Input ngày mặc định hôm nay; tuần / tháng / năm (gộp)
1:04:42 Select năm từ năm tạo site → hiện tại (gộp)
1:07:44 Sản phẩm bán chạy / không bán chạy (gộp)
1:09:14 SELECT sản phẩm + số lượng đã bán (gộp)
1:10:44 LEFT JOIN vs INNER; GROUP BY tránh lặp (gộp)
1:12:20 SUM(quantity) AS sales (gộp)
1:13:53 JOIN orders; chỉ đơn status đã duyệt (gộp)
1:17:01 IFNULL/COALESCE = 0 cho sản phẩm chưa có đơn (gộp)
1:18:43 Viết lại bằng subquery (so sánh JOIN) (gộp)
1:23:25 IFNULL; tối ưu truy vấn thống kê (gộp)
1:24:55 ORDER BY bán chạy; tie-break id nhập cũ (gộp)
1:26:25 Doanh thu SUM(total_price) theo thời gian (gộp)
1:29:27 Khách hàng tiềm năng: LEFT JOIN + SUM + GROUP BY (gộp)
1:32:33 COUNT đơn theo customer; ORDER BY tổng chi (gộp)
1:34:04 Buổi sau: bình luận + đánh giá (Ajax) (gộp)
1:35:34 Soft tip: Unicode homoglyph / zero-width trong tên (gộp)
1:40:12 Validate khoảng trắng / ký tự đặc biệt (gộp)
1:41:00 Kết; động lực code lại sau burnout (gộp)
1:43:15 Thiên tài vs điên; chào kết (gộp)
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
