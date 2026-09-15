# Lập trình web cơ bản buổi 30 PHP jQuery Modal Signin Signup Validate

- **id:** `x_XNnYk1aiw`
- **url:** https://www.youtube.com/watch?v=x_XNnYk1aiw
- **published:** 2022-01-13
- **duration:** 6145s (~1h42m)
- **kind:** live
- **subtitle_source:** auto (ASR — có thể nhiễu / sai từ)
- **folder:** [`transcripts/lap-trinh-web-co-ban-buoi-30-php-jquery-modal-signin-signup-validate-x_XNnYk1aiw/`](../../transcripts/lap-trinh-web-co-ban-buoi-30-php-jquery-modal-signin-signup-validate-x_XNnYk1aiw/)
- **topics:** web, php, javascript, jquery, ajax, modal, validate
- **series:** Lập trình web cơ bản — buổi 30
- **channel:** UCnL9cDH4iZcLmOIF8SzNGYw

## Tóm tắt

Live buổi 30 series Lập trình web cơ bản — Modal Bootstrap + đăng ký/đăng nhập không reload và validate form bằng jQuery trên đồ án bán hàng PHP. Đầu buổi soft tip: jQuery/Ajax/Modal không bắt buộc trong đồ án (học để biết); tâm lý trân trọng kiến thức miễn phí; so sánh đầu tư nội dung với creator khác; trong ngành IT chịu khó / kiên nhẫn quan trọng hơn “thông minh”. Q&A race condition mã hóa đơn (MAX id khi hai tab thanh toán cùng lúc) và ôn CDN (server gần, cache, rủi ro phụ thuộc bên thứ ba). Phần kỹ thuật: dùng Bootstrap chỉ lấy Modal (không full UI); nút Đăng ký mở modal; include form signup, ẩn modal lúc đầu bằng class; chặn submit mặc định (`preventDefault`), đẩy form bằng `$.ajax` POST + `serialize`; PHP trả thành công/thất bại (trùng email); hiện lỗi trong modal, thành công thì `modal('toggle')` đóng và cập nhật menu guest ↔ đã đăng nhập bằng jQuery (ẩn/hiện, điền tên) không reload. Đăng nhập làm tương tự (bỏ qua livecode dài). Cuối buổi: thư viện jQuery Validate (CDN), rules required / email / password equal / độ dài, kết hợp validate rồi mới Ajax submit; soft tip debug (comment từng đoạn), đọc docs bằng vài từ khóa; gợi ý buổi sau thông báo (notify).

## Mục lục

```
0:00 Chào; jQuery/Ajax học để biết, không bắt buộc đồ án (gộp)
3:14 Preview hôm nay: kiểm tra dữ liệu + modal signin/signup (gộp)
5:23 Modal Bootstrap + đăng ký/đăng nhập + validate + Ajax (gộp)
6:03 Soft tip video: tâm lý cái miễn phí (gộp)
7:57 Soft tip tâm lý học / làm chủ bản thân (gộp)
10:27 So sánh bản thân với creator; đầu tư nội dung (gộp)
15:37 Q&A chịu khó vs thông minh trong IT (gộp)
20:20 So với bản thân trước; chọn nghề có thể theo (gộp)
23:34 Kết soft tip; vào phần hỏi đáp kỹ thuật (gộp)
23:48 Q&A học công nghệ mới vs chuyên sâu cái cũ (gộp)
26:10 Q&A đặt hàng: race MAX id hóa đơn / hai tab (gộp)
31:07 insert_id / gom INSERT trong một request (gộp)
32:31 Ôn CDN: server gần, cache, rủi ro sập bên thứ ba (gộp)
37:20 Bài hôm nay: Modal (Bootstrap) (gộp)
37:28 Chỉ dùng Modal Bootstrap; không full UI framework (gộp)
39:42 UX đăng nhập không điều hướng: modal + Ajax (gộp)
40:42 Làm đăng ký trước; kết hợp validate (gộp)
42:40 Click nút Đăng ký → mở modal (gộp)
44:29 Include file form đăng ký vào trong modal (gộp)
45:30 Ẩn modal lúc đầu bằng class; show khi bấm (gộp)
48:17 Chặn submit form; đẩy bằng jQuery Ajax (gộp)
49:52 preventDefault / không cho form submit mặc định (gộp)
52:06 $.ajax POST signup; trả về thành công / thất bại (gộp)
53:32 serialize: lấy toàn bộ field form đẩy lên (gộp)
55:54 Demo Network: form data serialize lên server (gộp)
57:16 Trùng email → thất bại; hiện lỗi trong modal (gộp)
1:01:15 Đăng ký thành công → đóng modal (gộp)
1:02:08 modal toggle / API Bootstrap Modal (gộp)
1:08:35 Debug gọi modal; thứ tự load thư viện (gộp)
1:11:02 Cập nhật menu sau đăng ký không reload (gộp)
1:16:52 Menu guest vs signed-in; ẩn/hiện + điền tên (gộp)
1:18:37 Demo đăng ký thành công + cập nhật UI (gộp)
1:20:46 Đăng nhập làm tương tự (bỏ qua livecode dài) (gộp)
1:21:03 jQuery Validate: thư viện kiểm tra form (gộp)
1:25:22 CDN / download plugin Validate; chèn script (gộp)
1:26:08 Đọc docs; cấu hình rules validate (gộp)
1:29:37 Rules: required, email, password equal, độ dài (gộp)
1:33:14 Validate xong mới submit; vẫn preventDefault + Ajax (gộp)
1:36:19 Kết hợp Validate với Ajax form (gộp)
1:40:01 Soft tip debug: comment code tìm chỗ lỗi (gộp)
1:40:20 Tổng kết Modal + Validate; buổi sau notify (gộp)
1:41:20 Q&A tiếng Anh / đọc docs bằng từ khóa (gộp)
1:42:10 Chào kết; hỏi thêm qua tin nhắn / bình luận (gộp)
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
