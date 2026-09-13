# Lập trình web cơ bản buổi 24 PHP Đặt hàng

- **id:** `yndPkfUMozI`
- **url:** https://www.youtube.com/watch?v=yndPkfUMozI
- **published:** 2021-12-22
- **duration:** 7010s (~1h57m)
- **kind:** live
- **subtitle_source:** auto (ASR — có thể nhiễu / sai từ)
- **folder:** [`transcripts/lap-trinh-web-co-ban-buoi-24-php-dat-hang-yndPkfUMozI/`](../../transcripts/lap-trinh-web-co-ban-buoi-24-php-dat-hang-yndPkfUMozI/)
- **topics:** web, php, dat-hang, gio-hang
- **series:** Lập trình web cơ bản — buổi 24
- **channel:** UCnL9cDH4iZcLmOIF8SzNGYw

## Tóm tắt

Live buổi 24 series Lập trình web cơ bản — PHP Đặt hàng. Đầu buổi giới thiệu: sau giỏ hàng là lưu đơn; phần cơ bản chưa cần cổng thanh toán thẻ/ngân hàng (third-party). Tâm sự xem video về không bỏ cuộc / hoài bão / mục tiêu theo cột mốc; chia sẻ kênh công nghệ và sở thích. Q&A kiểm tra tồn kho khi đặt; thiết kế bảng sản phẩm (biến thể cấu hình — đừng nhồi quá nhiều cột, tách quan hệ). Thiết kế order: lưu người nhận (tên, SĐT, địa chỉ) tách khỏi customer vì người đặt ≠ người nhận; gợi ý danh bạ nhiều địa chỉ; khóa chính / auto-increment; hóa đơn chi tiết khóa kép (`order_id` + `product_id`). Nhắc viết tài liệu và tiêu chí bảo vệ đồ án. Code: form đặt hàng trên trang giỏ — tính tổng tiền, điền sẵn thông tin từ session user (UX), nút đặt hàng. Tạo bảng `orders` (customer, người nhận, status, thời gian, tổng tiền) + `order_detail`. Flow: insert order → lấy id → loop giỏ session insert chi tiết → lưu tổng → xóa giỏ → `header` redirect thông báo. Cảnh báo race khi nhiều request đặt cùng lúc / `lastInsertId`; so sánh giỏ multi-device (Shopee lưu server) với session local. Cuối buổi: DNS / Cloudflare / VPN; khóa học hết phần ngôn ngữ.

## Mục lục

```
0:00 Chào; giới thiệu đặt hàng — chưa thanh toán online (gộp)
1:42 Tâm sự video không bỏ cuộc / hoài bão (gộp)
13:30 Định hướng; mục tiêu cột mốc (gộp)
16:30 Chia sẻ kênh công nghệ / sở thích (gộp)
31:00 Q&A tồn kho khi đặt; làm nhóm (gộp)
34:00 Thiết kế DB sản phẩm / biến thể cấu hình (gộp)
41:40 Order: người nhận vs khách hàng (gộp)
45:00 Danh bạ nhiều địa chỉ; tư duy developer (gộp)
48:00 Khóa chính / auto-increment; hóa đơn chi tiết (gộp)
51:12 Tài liệu đồ án; tiêu chí bảo vệ (gộp)
1:04:30 Form đặt hàng; UX điền sẵn địa chỉ user (gộp)
1:13:34 Tổng tiền; nút đặt hàng + form người nhận (gộp)
1:16:30 Tạo bảng orders / status / thời gian đặt (gộp)
1:20:00 order_detail; khóa kép order_id + product_id (gộp)
1:27:00 Flow insert order + loop chi tiết từ session (gộp)
1:33:00 Cột tổng tiền; Insert từ cart session (gộp)
1:39:00 Race concurrent order / last insert id (gộp)
1:46:30 Insert detail; clear giỏ; header redirect (gộp)
1:51:00 Ôn 1-n order–detail; cart multi-device (gộp)
1:53:20 DNS / Cloudflare / VPN; chào kết (gộp)
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
