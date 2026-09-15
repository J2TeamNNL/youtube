# Lập trình web cơ bản buổi 27 PHP Cấu hình CSDL & Quên mật khẩu

- **id:** `QG8Ai3oR8G4`
- **url:** https://www.youtube.com/watch?v=QG8Ai3oR8G4
- **published:** 2022-01-04
- **duration:** 7356s (~2h3m)
- **kind:** live
- **subtitle_source:** auto (ASR — có thể nhiễu / sai từ)
- **folder:** [`transcripts/lap-trinh-web-co-ban-buoi-27-php-cau-hinh-csdl-va-quen-mat-khau-QG8Ai3oR8G4/`](../../transcripts/lap-trinh-web-co-ban-buoi-27-php-cau-hinh-csdl-va-quen-mat-khau-QG8Ai3oR8G4/)
- **topics:** web, php, csdl, quen-mat-khau, email
- **series:** Lập trình web cơ bản — buổi 27
- **channel:** UCnL9cDH4iZcLmOIF8SzNGYw

## Tóm tắt

Live buổi 27 series Lập trình web cơ bản — PHP cấu hình CSDL và quên mật khẩu. Đầu buổi tâm sự kênh YouTube (người theo dõi, chỉnh sửa video, tuyển phụ đề), rồi Q&A dài về shared hosting / VPS, deploy FileZilla, domain, backup và nhiều câu hỏi đồ án (form hai nút submit, đồng bộ giỏ hàng, tracking URL, AdBlock…). Phần kỹ thuật: không nhét nhiều giá trị vào một cột — minh họa cấu hình sản phẩm (RAM, màn hình…) và cách tách bảng N-N; mở rộng sang bảng cấu hình email / thông báo của khách (xóa hết rồi insert lại khi lưu). Phân biệt với quên mật khẩu: tạo bảng `forgot_password` (customer_id, token ngẫu nhiên, thời gian tạo), không gắn token cố định vào bảng customer. Flow: form nhập email → kiểm tra customer → lưu token → gửi mail chứa link đổi mật khẩu → trang đổi MK validate token → UPDATE password → xóa token; nhắc hạn 24h, cron/cron job trên hosting, rate limit chống spam gửi mail. Cuối buổi tóm tắt cơ chế và chào kết.

## Mục lục

```
0:00 Chào; tâm sự kênh theo dõi YouTube (gộp)
4:55 Trang xinh; tuyển phụ đề / cắt video (gộp)
8:03 Q&A deploy web lên hosting (gộp)
10:31 Shared hosting vs VPS / cloud (gộp)
13:44 Cấu hình VPS; domain (gộp)
17:07 Tài khoản FPT; FileZilla upload (gộp)
21:01 .htaccess; khóa sau (gộp)
23:56 Lưu file lớn; Google Drive (gộp)
26:00 Vào bài: mail & cấu hình CSDL (gộp)
26:28 Nhiều giá trị một cột; cấu hình sản phẩm (gộp)
32:19 Tách bảng cấu hình sản phẩm N-N (gộp)
34:02 Đồ án: xem đơn đã đặt phía khách (gộp)
34:27 Form hai nút submit khác action (gộp)
36:41 Xóa dữ liệu / khôi phục; backup hosting (gộp)
40:01 Google Workspace / support (gộp)
44:04 Điểm đồ án; công bằng (gộp)
46:03 Đặt tên file; bất đồng bộ JS (gộp)
52:57 Tài liệu tính năng nâng cao (gộp)
53:59 Đồng bộ giỏ hàng đa thiết bị (gộp)
55:07 Query string / tracking URL (gộp)
57:54 Sandbox Windows (gộp)
59:58 Chặn quảng cáo; detect AdBlock (gộp)
1:06:02 Nhận thiếu sót; phấn đấu học (gộp)
1:09:02 Chuyện học lập trình / đồ án (gộp)
1:14:57 Giao lưu tán gái / soft skills (gộp)
1:21:28 Cấu hình CSDL gửi mail / thông báo (gộp)
1:25:38 Bảng cấu hình email khách (xóa–insert) (gộp)
1:27:14 Quên mật khẩu ≠ cấu hình mail (gộp)
1:28:27 Flow: token + link đổi mật khẩu (gộp)
1:29:45 Tách bảng forgot_password; không gắn token vào customer (gộp)
1:31:01 Hiệu lực 24h; bot/cron xóa token (gộp)
1:32:37 Rate limit quên mật khẩu; chống spam mail (gộp)
1:36:01 Nút + trang forgot password; form email (gộp)
1:37:02 Không lộ email tồn tại / không tồn tại (gộp)
1:38:03 Query customer; gọi hàm gửi mail (gộp)
1:39:37 Insert forgot_password; PK theo customer (gộp)
1:42:48 Xóa token cũ rồi insert mới (gộp)
1:44:13 Sinh token ngẫu nhiên (gộp)
1:45:45 Build URL đổi mật khẩu kèm token (gộp)
1:48:37 Gửi mail kèm link reset (gộp)
1:50:38 Trang đổi MK; validate token (gộp)
1:55:27 Form nhập mật khẩu mới (gộp)
1:57:06 Submit: kiểm tra token lại; UPDATE password (gộp)
1:58:51 Xóa token sau khi đổi thành công (gộp)
2:00:00 Tóm tắt cơ chế; cron job trên hosting (gộp)
2:01:28 Kết thúc; đẩy code Git; chào (gộp)
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
