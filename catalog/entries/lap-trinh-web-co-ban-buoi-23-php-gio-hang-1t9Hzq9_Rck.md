# Lập trình web cơ bản buổi 23 PHP Giỏ hàng

- **id:** `1t9Hzq9_Rck`
- **url:** https://www.youtube.com/watch?v=1t9Hzq9_Rck
- **published:** 2021-12-18
- **duration:** 5926s (~1h39m)
- **kind:** live
- **subtitle_source:** auto (ASR — có thể nhiễu / sai từ)
- **folder:** [`transcripts/lap-trinh-web-co-ban-buoi-23-php-gio-hang-1t9Hzq9_Rck/`](../../transcripts/lap-trinh-web-co-ban-buoi-23-php-gio-hang-1t9Hzq9_Rck/)
- **topics:** web, php, gio-hang
- **series:** Lập trình web cơ bản — buổi 23
- **channel:** UCnL9cDH4iZcLmOIF8SzNGYw

## Tóm tắt

Live buổi 23 series Lập trình web cơ bản — PHP Giỏ hàng. Đầu buổi tâm sự Windows 11 / máy làm việc; Q&A auto-save code (VS Code); quảng cáo Facebook không chỉ dựa cookie (độ tuổi, giới tính, vùng miền); cookie Netflix / export phiên; khuyên học CNTT tập trung một hướng trước khi dàn trải. Vào bài: mục tiêu thêm / tăng / giảm / xóa / xem giỏ; nút «Thêm vào giỏ» theo id sản phẩm; dùng `$_SESSION` (không DB / cookie cho giỏ). Mã giả các case: giỏ trống → thêm; trùng sản phẩm → tăng số lượng; sản phẩm mới → thêm phần tử. Demo mảng session `id => quantity`. Xem giỏ: ảnh, tên, giá, số lượng, tổng, nút xóa; cảnh báo N truy vấn nếu query từng SP khi view. Tối ưu: lúc thêm lần đầu kết nối DB lấy đủ thông tin (ảnh, tên, giá) + quantity=1 lưu vào session đa chiều; lần sau chỉ `++`; view in lại từ session (giữ giá lúc đặt — UX). Update quantity nút +/- (`update_cart`); không âm; =1 rồi giảm thì `unset`. Xóa một SP / xóa cả giỏ; kiểm tra giỏ trống; nhắc validate & bảo vệ đồ án. Cuối buổi tâm sự tiêu chí đồ án / dạy sinh viên; Q&A session hết hạn; chia sẻ đồ án cũ (admin, khách hàng).

## Mục lục

```
0:00 Chào; tâm sự Windows 11 / máy làm việc (gộp)
8:40 Auto-save code; Q&A quảng cáo Facebook & cookie (gộp)
12:11 Q&A Cookie Netflix; định hướng học CNTT (gộp)
21:33 Giới thiệu buổi: giỏ hàng — thêm/tăng/giảm/xóa/xem (gộp)
23:21 Kiểm tra đăng nhập session; nút Thêm vào giỏ (gộp)
27:19 Mã giả: giỏ trống / trùng SP / SP mới (gộp)
31:30 Demo session array; lưu id + số lượng (gộp)
39:00 Xem giỏ hàng; UI ảnh/tên/giá/SL/xóa (gộp)
44:17 Vấn đề N truy vấn khi view từng SP (gộp)
49:45 Tối ưu: lưu đủ thông tin SP vào session khi thêm (gộp)
53:03 DB lần đầu thêm; lần sau chỉ ++ quantity (gộp)
56:10 In giỏ từ session; Session Viewer / print_r (gộp)
59:21 Update quantity +/- ; không âm; =1 thì xóa (gộp)
1:04:13 Giỏ trống UX; update_cart increase/decrease (gộp)
1:08:29 Xóa một SP (unset); xóa cả giỏ; empty check (gộp)
1:10:00 Validate; nhắc đồ án / bảo vệ (gộp)
1:12:37 Tâm sự tiêu chí đồ án / dạy sinh viên (gộp)
1:22:09 Q&A session vs tối ưu; Discord; đồ án cũ (gộp)
1:25:40 Demo đồ án cũ / admin / chào kết (gộp)
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
