# Lập trình web cơ bản buổi 22 PHP Cookies

- **id:** `27UPwj789E4`
- **url:** https://www.youtube.com/watch?v=27UPwj789E4
- **published:** 2021-12-17
- **duration:** 6071s (~1h41m)
- **kind:** live
- **subtitle_source:** auto (ASR — có thể nhiễu / sai từ)
- **folder:** [`transcripts/lap-trinh-web-co-ban-buoi-22-php-cookies-27UPwj789E4/`](../../transcripts/lap-trinh-web-co-ban-buoi-22-php-cookies-27UPwj789E4/)
- **topics:** web, php, cookie, security
- **series:** Lập trình web cơ bản — buổi 22
- **channel:** UCnL9cDH4iZcLmOIF8SzNGYw

## Tóm tắt

Live buổi 22 series Lập trình web cơ bản — PHP Cookies. Đầu buổi tâm sự Facebook feed / nhóm giải trí / đừng bắt chước câu chuyện người giàu; giới thiệu lộ trình khóa (CRUD → session/cookie → giỏ hàng → framework). Q&A dài: thẻ pre/code khi in HTML từ DB; giáo án FPT/đại học; viết tài liệu / phân tích bằng văn xuôi trước khi code tính năng đăng ký–đăng nhập. Ôn đăng xuất: unset từng key thay session_destroy (giữ giỏ hàng); flash message lỗi qua session. Vào cookie: phân biệt session (server) vs cookie (trình duyệt); ví dụ theo dõi quảng cáo, dark/light theme, giỏ hàng chưa đăng nhập. Demo "Ghi nhớ đăng nhập" (remember me): checkbox, setcookie(name, value, expire) với time()+86400*N; đọc $_COOKIE để tự tạo session khi quay lại; đăng xuất xóa cookie bằng setcookie thời gian quá khứ. Cảnh báo bảo mật: không lưu id trần trong cookie (đổi id → vào nick người khác); sinh token ngẫu nhiên mỗi user, lưu DB + cookie; hash; unique. Cuối buổi gợi ý phân quyền nhân viên/quản lý (lưu role trong DB); nhắc dạy bảo mật sớm; tâm sự định hướng nghề / lương / kết thúc.

## Mục lục

```
0:00 Chào; tâm sự Facebook/nhóm; đừng bắt chước người giàu (gộp)
8:40 Lộ trình khóa web; hôm nay Cookie; Q&A pre/code HTML (gộp)
11:27 Giáo án FPT/đại học; viết tài liệu trước khi code; Q&A signing (gộp)
30:00 Ôn đăng xuất unset vs destroy; flash lỗi session (gộp)
35:43 Vào Cookie: session vs cookie; tracking; theme; giỏ hàng (gộp)
42:21 Ghi nhớ đăng nhập (remember me); cookie tạo lại session (gộp)
49:09 Demo remember me trên form đăng nhập (gộp)
53:00 setcookie name/value/expire; lưu remember khi login (gộp)
58:08 Đọc $_COOKIE; auto-login; demo quay lại vẫn đăng nhập (gộp)
1:01:49 Đăng xuất xóa cookie (setcookie quá khứ); session vẫn tạo (gộp)
1:06:24 Bảo mật: không lưu id trần; token ngẫu nhiên; hash (gộp)
1:08:33 Phân quyền nhân viên/quản lý; token remember hoàn thiện (gộp)
1:19:47 Vì sao dạy bảo mật sớm; framework/lib; Q&A (gộp)
1:30:02 Đúc kết phân quyền; định hướng nghề/lương; chào kết (gộp)
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
