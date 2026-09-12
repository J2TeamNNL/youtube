# Lập trình web cơ bản buổi 21 PHP Signing & Hacking

- **id:** `7pWAqw9XjVM`
- **url:** https://www.youtube.com/watch?v=7pWAqw9XjVM
- **published:** 2021-12-14
- **duration:** 7456s (~2h4m)
- **kind:** live
- **subtitle_source:** auto (ASR — có thể nhiễu / sai từ)
- **folder:** [`transcripts/lap-trinh-web-co-ban-buoi-21-php-signing-hacking-7pWAqw9XjVM/`](../../transcripts/lap-trinh-web-co-ban-buoi-21-php-signing-hacking-7pWAqw9XjVM/)
- **topics:** web, php, security, signing
- **series:** Lập trình web cơ bản — buổi 21
- **channel:** UCnL9cDH4iZcLmOIF8SzNGYw

## Tóm tắt

Live buổi 21 series Lập trình web cơ bản — Signing (đăng ký / đăng nhập / đăng xuất) và demo hacking. Đầu buổi dài tâm sự + Q&A tổng hợp: họp hiệu quả, BA/PM, thuật toán khi đi làm, viết tài liệu đồ án, offline sau Tết, sống chung dịch… ~25:46 demo lỗi khi tên sản phẩm có dấu nháy (SQL hiểu nhầm kết thúc chuỗi); giới thiệu escape / addslashes để phòng SQL injection. ~49:10 vào bài Signing: sign up / sign in / sign out; chỉ làm đăng ký phía khách hàng (không cho nhân viên/quản lý tự đăng ký). Form đăng ký email + mật khẩu (UNIQUE email; tạm chưa mã hóa mật khẩu); kiểm tra trùng email trước khi INSERT; redirect sau đăng ký. Giải thích session & cookie: server nhớ phiên đăng nhập, cookie trên trình duyệt; session_start; chỉ lưu id (không dump hết thông tin user vào session). Đăng xuất: unset từng key thay vì destroy cả session (giữ giỏ hàng); chặn vào trang user khi chưa login. Form đăng nhập: SELECT theo email+password; thông báo lỗi chung. Phần hacking: XSS chèn script lấy cookie; CSRF / token ngẫu nhiên trên form; demo SQL injection login (OR 1=1). Cuối buổi: cấu trúc commit message; Git push/pull/fetch, nhánh, conflict. Buổi sau gợi ý tiếp hacking thanh tìm kiếm / xem đồ án mẫu.

## Mục lục

```
0:00 Chào; tâm sự; Q&A tổng hợp buổi trước (gộp)
22:35 Offline Sài Gòn/Hà Nội; sống chung dịch (gộp)
25:46 Demo lỗi dấu nháy SQL; escape/addslashes; phòng injection (gộp)
35:02 Q&A BA/PM; thuật toán; tài liệu đồ án; PHPStorm vs VS Code (gộp)
49:10 Vào Signing: sign up/in/out; chỉ đăng ký khách hàng (gộp)
56:00 Form đăng ký email+mật khẩu; UNIQUE; INSERT; redirect (gộp)
1:05:35 Session & cookie: vì sao cần; session_start; lưu id (gộp)
1:24:24 Đăng xuất unset; bảo vệ trang khi chưa login (gộp)
1:30:07 Form đăng nhập; SELECT email+password; lỗi chung (gộp)
1:34:44 Hacking: XSS lấy cookie; CSRF/token; SQL injection login (gộp)
1:51:03 Đồ án/Discord; Git commit message; push/pull/conflict (gộp)
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
