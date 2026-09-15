# Lập trình web cơ bản buổi 29 PHP jQuery làm quen Ajax

- **id:** `HszrnYMdfAU`
- **url:** https://www.youtube.com/watch?v=HszrnYMdfAU
- **published:** 2022-01-11
- **duration:** 5842s (~1h37m)
- **kind:** live
- **subtitle_source:** auto (ASR — có thể nhiễu / sai từ)
- **folder:** [`transcripts/lap-trinh-web-co-ban-buoi-29-php-jquery-lam-quen-ajax-HszrnYMdfAU/`](../../transcripts/lap-trinh-web-co-ban-buoi-29-php-jquery-lam-quen-ajax-HszrnYMdfAU/)
- **topics:** web, php, javascript, jquery, ajax
- **series:** Lập trình web cơ bản — buổi 29
- **channel:** UCnL9cDH4iZcLmOIF8SzNGYw

## Tóm tắt

Live buổi 29 series Lập trình web cơ bản — làm quen jQuery và Ajax trên đồ án bán hàng PHP. Đầu buổi soft tip (sống cho chính mình, cân bằng với xã hội), Q&A OTP vs gửi email (OTP tốn phí, thường dùng thư viện), và tâm lý lập trình: phải tính nhiều trường hợp người dùng nhập sai, đừng cầu toàn đồ án đến mức không dám chuyển sang bài mới. Phần kỹ thuật: jQuery là thư viện JavaScript (không phải ngôn ngữ riêng), file khá nặng nên nhiều site mới bỏ CDN jQuery; học để viết JS ngắn hơn và làm cầu nối sang Ajax. Demo UX không reload: thêm giỏ hàng, gợi ý tìm kiếm / autocomplete qua request lên server. Setup chèn script jQuery, `$(document).ready`, selector, `.val()` / `.html()` / `.text()`, `$(this)`, gắn `.click()`. Livecode Ajax thêm giỏ: `data-id` + class nút, `$.ajax` (GET vs POST), callback success/error, HTTP 200, PHP trả chuỗi thành công/thất bại / `isset`. Tiếp theo tối ưu trang giỏ: nút +/- cập nhật số lượng không điều hướng, sau success cập nhật DOM (span quantity / giá / tổng) bằng jQuery, `.parent()` traversal, lưu ý JS bất đồng bộ khi cộng tổng, quantity về 0 thì xóa dòng, nút delete gọi PHP rồi `.remove()`. Cuối buổi nhắc đọc docs tiếng Anh, nghề (PHP thuần / Laravel), áp dụng vào đồ án; lộ trình gần Tết.

## Mục lục

```
0:00 Chào; hôm nay học jQuery thư viện (gộp)
1:31 Mic; soft tip nhân vật chính cuộc đời mình (gộp)
3:14 OTP vs email; dùng thư viện (gộp)
4:20 Soft tip tự tin / đừng sợ sai (gộp)
5:31 Dev phải tính nhiều trường hợp nhập sai (gộp)
7:32 Story học hành / tâm lý bi quan khi code (gộp)
10:15 Đồ án; đừng cầu toàn "hoàn hảo" (gộp)
12:00 Hoàn thiện đồ án 1 rồi nhảy đồ án mới (gộp)
15:06 Q&A Node.js / sản phẩm mang đi phỏng vấn (gộp)
16:25 jQuery là gì: thư viện JS, nặng, nhiều site bỏ (gộp)
18:03 Học jQuery để viết JS nhanh hơn; intro Ajax (gộp)
19:40 UX Ajax: thêm giỏ hàng không reload trang (gộp)
21:00 Setup: chèn script jQuery (CDN / file) (gộp)
22:30 Document ready; đợi jQuery load xong (gộp)
24:00 Selector; .val() gán / lấy giá trị (gộp)
25:30 .html() / .text(); rủi ro in HTML (XSS) (gộp)
27:00 $(this); gắn logic trong event handler (gộp)
28:30 Sự kiện change / click chạy lại khối code (gộp)
30:00 Áp dụng lên site: validate đăng ký (gộp)
30:51 Đổi số lượng / luồng đặt hàng (gộp)
31:45 Gợi ý tìm kiếm sản phẩm (Ajax search) (gộp)
33:00 Bình luận vs web bán hàng; autocomplete (gộp)
34:30 Thêm giỏ hàng bằng jQuery + Ajax (gộp)
35:02 Nút add-to-cart: class + data-id (gộp)
37:34 .click(); lấy data-id từ nút được bấm (gộp)
39:24 Gọi file PHP add-to-cart không điều hướng (gộp)
40:30 $.ajax: method GET vs POST (gộp)
41:34 Callback success / error (gộp)
43:17 HTTP status 200 = thành công (gộp)
45:17 Kiểm tra data trả về thành công / thất bại (gộp)
48:00 Đọc docs tiếng Anh; success / fail (gộp)
49:55 PHP isset($_GET['id']); trả result (gộp)
52:05 Demo thêm giỏ không reload (gộp)
52:30 Ajax giỏ hàng: +/- / xóa không đổi trang (gộp)
54:06 UX cập nhật số lượng (click / blur) (gộp)
55:32 Click update; data-id + type cộng/trừ (gộp)
58:28 Sau success: cập nhật số lượng + tổng tiền (jQuery) (gộp)
1:00:00 Tính tổng: PHP trước vs jQuery sau (gộp)
1:02:00 Cập nhật tổng từng dòng khi đổi quantity (gộp)
1:04:10 .parent() / DOM traversal; span quantity & price (gộp)
1:06:00 Client-side chỉ UX; không phải lớp bảo mật (gộp)
1:07:30 Success → quantity++; tách hàm tái sử dụng (gộp)
1:09:00 Tính lại tổng toàn bộ giỏ (gộp)
1:12:17 JS bất đồng bộ; race khi cộng tổng (gộp)
1:15:00 Quantity về 0 → xóa hẳn dòng (gộp)
1:19:30 Nút delete; Ajax delete; .remove() DOM (gộp)
1:21:00 Demo xóa sản phẩm + tính lại tổng (gộp)
1:24:00 Tổng kết Ajax giỏ; biết qua là đủ (gộp)
1:25:30 Soft tip phím tắt / docs / đọc source (gộp)
1:27:00 Tip SQL TOP / LIMIT (gộp)
1:31:30 Nghề: PHP thuần, Laravel, đa ngôn ngữ (gộp)
1:34:06 Áp dụng Ajax/jQuery vào đồ án (gộp)
1:36:00 Lộ trình tới Tết; gợi ý buổi sau; chào kết (gộp)
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
