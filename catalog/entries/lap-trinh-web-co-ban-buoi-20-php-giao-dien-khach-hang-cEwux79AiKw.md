# Lập trình web cơ bản buổi 20 PHP Giao diện khách hàng

- **id:** `cEwux79AiKw`
- **url:** https://www.youtube.com/watch?v=cEwux79AiKw
- **published:** 2021-12-10
- **duration:** 5382s (~1h30m)
- **kind:** live
- **subtitle_source:** auto (ASR — có thể nhiễu / sai từ)
- **folder:** [`transcripts/lap-trinh-web-co-ban-buoi-20-php-giao-dien-khach-hang-cEwux79AiKw/`](../../transcripts/lap-trinh-web-co-ban-buoi-20-php-giao-dien-khach-hang-cEwux79AiKw/)
- **topics:** web, php, giao-dien
- **series:** Lập trình web cơ bản — buổi 20
- **channel:** UCnL9cDH4iZcLmOIF8SzNGYw

## Tóm tắt

Live buổi 20 series Lập trình web cơ bản — làm giao diện phía khách hàng (storefront) cho sản phẩm đã CRUD ở buổi trước. Đầu buổi Q&A: không nên học song song nhiều ngôn ngữ khi chưa biết hướng; chuyên sâu vs đa năng (lương / vai trò); nộp đồ án qua GitHub (public/private, username); cuối tuần sẽ phân tích & thiết kế (ERD, tài liệu, phân quyền); SQL vs NoSQL khái quát; schema chỉ thêm bảng/cột theo chức năng thật, đừng copy nhóm khác; gợi ý học thêm (W3Schools, Codecademy, Medium, Viblo). Khoảng ~22:27 vào bài: bố cục trang khách header (logo/menu) – nội dung giữa – footer; tái sử dụng bằng include (menu, footer) thay vì copy từng trang. Trang chủ/index SELECT toàn bộ sản phẩm, lưới ~3 sản phẩm/hàng (width ~33%, float), hiện ảnh–tên–giá; lưu ý đường dẫn ảnh không lộ thư mục admin. Link xem chi tiết sang trang product theo id (GET), SELECT một sản phẩm + mô tả; cấu trúc file ngắn, gọi nhau (chưa MVC — sẽ học sau). Nhắc nên có phân trang/tìm kiếm (ví dụ 6 sp/trang) nhưng buổi này chưa code; form đăng nhập tự làm. ~42:05 chuyển chữa bài SQL (thi: khoa – nhân viên – bệnh nhân): tạo bảng, ràng buộc, UNIQUE tên khoa, INSERT; thống kê COUNT/GROUP BY + JOIN tên khoa; SELECT INTO / bảng tạm–view; stored procedure theo tên khoa; trigger INSTEAD OF INSERT chống trùng tên (COUNT hoặc NOT IN) và thông báo UX. Cuối tuần: phân tích thiết kế đồ án.

## Mục lục

```
0:00 Chào; Q&A học song song ngôn ngữ; chuyên sâu vs đa năng (gộp)
10:06 Q&A nộp GitHub; cuối tuần phân tích thiết kế đồ án; admin/phân quyền (gộp)
15:46 Q&A SQL vs NoSQL; schema theo chức năng; tài nguyên học (gộp)
22:27 Vào bài: giao diện khách; bố cục header–content–footer; include menu/footer (gộp)
30:36 Trang chủ: SELECT sản phẩm; lưới 3 cột; ảnh/tên/giá; đường dẫn ảnh (gộp)
36:33 Gợi ý phân trang/tìm kiếm; link xem chi tiết theo id (gộp)
38:01 Trang chi tiết: GET id; SELECT một sp + mô tả; tách file include (gộp)
42:05 Chữa SQL: schema khoa/nhân viên/bệnh nhân; UNIQUE; INSERT (gộp)
1:05:18 Thống kê COUNT/GROUP BY; JOIN tên khoa; SELECT INTO / view (gộp)
1:10:36 Stored procedure theo tên khoa; trigger INSTEAD OF chống trùng (gộp)
1:26:08 Trigger NOT IN gọn hơn; thông báo UX; kết live (gộp)
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
