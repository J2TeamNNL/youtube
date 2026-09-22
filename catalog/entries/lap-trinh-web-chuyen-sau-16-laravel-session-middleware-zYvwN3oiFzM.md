# Lập trình web chuyên sâu - 16 - Laravel - Session & Middleware

- **id:** `zYvwN3oiFzM`
- **url:** https://www.youtube.com/watch?v=zYvwN3oiFzM
- **published:** 2022-04-19
- **duration:** 6797s (~1h53m)
- **kind:** live
- **subtitle_source:** auto (ASR — có thể nhiễu / sai từ)
- **folder:** [`transcripts/lap-trinh-web-chuyen-sau-16-laravel-session-middleware-zYvwN3oiFzM/`](../../transcripts/lap-trinh-web-chuyen-sau-16-laravel-session-middleware-zYvwN3oiFzM/)
- **topics:** web, php, laravel, session, middleware
- **series:** Lập trình web chuyên sâu — buổi 16 Laravel - Session & Middleware
- **channel:** UCnL9cDH4iZcLmOIF8SzNGYw
- **transcript commit:** `4b155b4a092c461b6a7eb0f4177869e7fda977b3`

## Tóm tắt

Live ~1h53m — **buổi 16** series **Lập trình web chuyên sâu**: **Laravel Session & Middleware**. Đầu buổi tâm sự / setup mic; vào bài giải thích **middleware** (luôn kiểm tra quyền trước khi vào route/controller) và vai trò **session** trong đăng nhập. Livecode: cấu hình auth/login (email–password), route bảo vệ bằng middleware, form đăng nhập Blade + CSRF, kiểm tra credentials, redirect khi chưa login; thử đăng nhập / giữ session; logout; nhấn mạnh mọi request nhạy cảm phải qua middleware. Kết: auth flow cơ bản chạy trên Laravel; khuyến khích luyện thêm.

## Mục lục

```
0:00 Alo / mic / setup nghe (gộp)
5:00 Tâm sự đầu buổi; vào lớp (gộp)
10:00 Chốt tâm sự; hướng vào bài Session & Middleware (gộp)
17:00 Giới thiệu ý tưởng đăng nhập / phiên làm việc (gộp)
25:00 Vì sao cần middleware kiểm tra quyền (gộp)
33:00 Gợi ý học đăng nhập; cấu trúc auth (gộp)
40:00 Middleware luôn kiểm tra trước controller (gộp)
45:00 Ví dụ chỉ cho phép user đã login (gộp)
50:00 Tránh để logic auth rải trong controller (gộp)
53:00 Laravel auth scaffolding / gợi ý (gộp)
57:00 Password mặc định / hash (gộp)
1:01:00 So sánh các cách auth tương tự (gộp)
1:05:00 Khai báo route + middleware group (gộp)
1:09:00 Debug / chờ môi trường (gộp)
1:12:00 Thử đăng nhập; kiểm tra session (gộp)
1:16:00 Form login; gợi ý field (gộp)
1:21:00 Password field; validate input (gộp)
1:25:00 Redirect lại khi fail / chưa auth (gộp)
1:29:00 Đi hết các route cần bảo vệ (gộp)
1:33:00 Tạo / hoàn thiện flow đăng nhập (gộp)
1:36:00 Sau login: quay lại trang trước (gộp)
1:41:00 Kiểm tra middleware trên request (gộp)
1:45:00 Sửa route / quay lại ô login (gộp)
1:49:00 Bắt buộc đăng nhập mới dùng được (gộp)
1:53:00 Q&A ngắn; chào kết (gộp)
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
