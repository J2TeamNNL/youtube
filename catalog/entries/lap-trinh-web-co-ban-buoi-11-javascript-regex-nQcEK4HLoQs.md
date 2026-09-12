# Lập trình web cơ bản buổi 11 JavaScript Regex

- **id:** `nQcEK4HLoQs`
- **url:** https://www.youtube.com/watch?v=nQcEK4HLoQs
- **published:** 2021-11-14
- **duration:** 5197s (~1h27m)
- **kind:** live
- **subtitle_source:** auto (ASR — có thể nhiễu / sai từ)
- **folder:** [`transcripts/lap-trinh-web-co-ban-buoi-11-javascript-regex-nQcEK4HLoQs/`](../../transcripts/lap-trinh-web-co-ban-buoi-11-javascript-regex-nQcEK4HLoQs/)
- **topics:** web, javascript, regex
- **series:** Lập trình web cơ bản — buổi 11
- **channel:** UCnL9cDH4iZcLmOIF8SzNGYw

## Tóm tắt

Live buổi 11 series Lập trình web cơ bản — JavaScript Regex: chào, tâm sự giờ bắt đầu live / nuôi cún, chat cộng đồng (nhắc hứa bật mí với bạn Phương Linh), rồi meme “regex bị ghét” và cách tìm cheat sheet / tutorial cơ bản trên Google trước khi vào bài. Regex dùng để kiểm tra chuỗi có khớp mẫu hay không — bài toán trung tâm là validate form đăng ký (họ tên, email, mật khẩu, số điện thoại) phía client trước khi gửi server. Demo xây pattern email từng bước: class ký tự `[a-z]`, lượng từ `+` / `?`, cho phép `.` `_` số trong local-part và domain; nhắc giới hạn ASCII vs chữ có dấu/Unicode. Neo `^` `$` để khớp cả chuỗi (không chỉ đoạn giữa); viết tắt `\w` `\d`, dấu chấm `.`, phủ định trong ngoặc vuông. Thực hành: số điện thoại VN 10/11 số, đầu `0` hoặc `+84` (escape ký tự đặc biệt); validate tuổi nguyên 1–199 bằng cách tách trường hợp theo độ dài; số thập phân (phần nguyên + phần thập phân tùy chọn); họ tên không dấu với chữ hoa đầu mỗi từ và khoảng trắng. Gợi ý tài liệu thêm, flags `g` / `m` / `i` khi test; buổi sau sẽ gắn regex vào JavaScript để validate input thật. Giao làm lại các bài tập trong buổi, chào cuối tuần.

## Mục lục

```
0:00 Chào live; tâm sự giờ/cún; meme regex; cheat sheet (gộp)
9:01 Bắt đầu bài: Regex dùng để làm gì; form đăng ký (gộp)
12:10 Khớp chuỗi; bắt đầu xây pattern email (gộp)
15:25 Class [a-z]; lượng từ + ; local-part / domain (gộp)
25:07 Mở rộng email: _, số; chữ có dấu / Unicode (gộp)
33:12 Lượng từ ? (tùy chọn); neo ^ $ cả chuỗi (gộp)
40:01 Viết tắt \w \d; dấu chấm .; phủ định trong [] (gộp)
43:32 Bài tập: SĐT VN 10/11 số; 0 và +84 (gộp)
52:29 Validate tuổi 1–199; tách trường hợp theo độ dài (gộp)
1:03:29 Số thập phân; họ tên hoa đầu từ; flags g/m/i; chào (gộp)
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
