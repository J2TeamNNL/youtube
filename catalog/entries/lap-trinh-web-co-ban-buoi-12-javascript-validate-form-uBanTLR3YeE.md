# Lập trình web cơ bản buổi 12 JavaScript Validate Form

- **id:** `uBanTLR3YeE`
- **url:** https://www.youtube.com/watch?v=uBanTLR3YeE
- **published:** 2021-11-16
- **duration:** 6169s (~1h43m)
- **kind:** live
- **subtitle_source:** auto (ASR — có thể nhiễu / sai từ)
- **folder:** [`transcripts/lap-trinh-web-co-ban-buoi-12-javascript-validate-form-uBanTLR3YeE/`](../../transcripts/lap-trinh-web-co-ban-buoi-12-javascript-validate-form-uBanTLR3YeE/)
- **topics:** web, javascript, form, regex
- **series:** Lập trình web cơ bản — buổi 12
- **channel:** UCnL9cDH4iZcLmOIF8SzNGYw

## Tóm tắt

Live buổi 12 series Lập trình web cơ bản — JavaScript Validate Form: chào, trả lời câu hỏi tồn (kiên nhẫn khi dạy, lộ trình JS xong sang PHP rồi ghép CRUD/đăng nhập thành web tin tức rồi bán hàng + đồ án nhóm), so sánh web kéo-thả vs tự gõ, rồi vào bài — vì sao phải kiểm tra dữ liệu người dùng nhập trên form đăng ký. Phân biệt validate phía client (JavaScript trên trình duyệt: phản hồi nhanh, đỡ tải server) và phía server (bước cuối bắt buộc, vì user có thể tắt JS hoặc ghi đè hàm trong DevTools). Demo dựng form: họ tên, giới tính radio (cần name chung), email, mật khẩu, nút đăng ký; không dựa vào required của HTML vì thông báo tiếng Anh / hạn chế, thay bằng span lỗi cạnh ô. onsubmit + return false để chặn gửi khi sai; debug bằng console.log và comment dần khi lỗi chính tả làm form vẫn submit. Nhiều field thì dùng biến cờ lỗi để hiện hết lỗi một lúc thay vì return ngay field đầu. Gắn regex buổi 11 (.test) cho họ tên; toán tử phủ định; radio thì getElementsByName + vòng lặp checked; nhớ xóa thông báo cũ khi nhập đúng. Giữ type email/number vì UX mobile (bàn phím, autofill). Mật khẩu: không trống, độ dài tối thiểu; thử tạo span bằng JS rồi thấy nên để span sẵn trong HTML. Nhắc lách select/ghi đè hàm — server vẫn phải kiểm tra lại. Cuối buổi chia sẻ trang GitHub profile (Spotify, blog, WakaTime), chữa bài để buổi sau.

## Mục lục

```
0:00 Chào live; Q&A dạy học/lộ trình PHP; vì sao validate (gộp)
25:01 Client vs server; tắt JS; email tồn tại vs cú pháp (gộp)
40:11 Dựng form HTML: tên, radio, email, mật khẩu, submit (gộp)
47:56 onsubmit; span lỗi; return false chặn submit (gộp)
52:01 Debug: console.log; comment dần; lỗi chính tả (gộp)
57:01 Nhiều field; biến cờ lỗi; hiện hết lỗi (gộp)
1:00:36 Regex họ tên .test; phủ định; xóa lỗi khi đúng (gộp)
1:05:06 Radio giới tính: getElementsByName, vòng lặp, checked (gộp)
1:13:38 type email/number UX mobile; mật khẩu độ dài (gộp)
1:19:07 Tạo span bằng JS; hạn chế; submit khi hợp lệ (gộp)
1:32:37 Lách select/ghi đè hàm; GitHub profile; chào (gộp)
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
