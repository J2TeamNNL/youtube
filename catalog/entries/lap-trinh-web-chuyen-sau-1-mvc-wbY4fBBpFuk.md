# Lập trình web chuyên sâu - 1 - MVC

- **id:** `wbY4fBBpFuk`
- **url:** https://www.youtube.com/watch?v=wbY4fBBpFuk
- **published:** 2022-03-08
- **duration:** 4777s (~1h20m)
- **kind:** live
- **subtitle_source:** auto (ASR — có thể nhiễu / sai từ)
- **folder:** [`transcripts/lap-trinh-web-chuyen-sau-1-mvc-wbY4fBBpFuk/`](../../transcripts/lap-trinh-web-chuyen-sau-1-mvc-wbY4fBBpFuk/)
- **topics:** web, php, mvc
- **series:** Lập trình web chuyên sâu — buổi 1 MVC
- **channel:** UCnL9cDH4iZcLmOIF8SzNGYw
- **transcript commit:** `7a65b50f80854d60e50a015c67841ce5bed07177`

## Tóm tắt

Live ~1h20m — **buổi 1** mở series mới **Lập trình web chuyên sâu** (sau Đồ án web cơ bản), đúng mùng 8/3. Host chào mic/chat, chúc Quốc tế Phụ nữ, nêu mục tiêu khóa: học xong đồ án là nhảy việc được (lương ~5–8 triệu trở lên), có người kèm hỏi bài/công việc, đồng hành cộng đồng. Công cụ buổi này: PhpStorm (+ Code With Me / Meet để xem code live), GitHub (repo demo), draw.io để vẽ. Cam kết giải thích **MVC** dễ hiểu nhất bằng ẩn dụ nhà hàng: khách = user ngồi yên tại `index`; bồi bàn = **Controller**; menu/đĩa = **View**; đầu bếp = **Model**; tủ lạnh = CSDL. Demo PHP thuần: `index.php` gọi controller; controller trả `menu.php` khi chưa gọi món; link `?mon=...` → nhận request → `include` model → SELECT bảng `mon_an` → nhét kết quả vào `dia.php` (view). Nhấn mạnh tách file: sửa menu/DB/view một chỗ, chỗ khác vẫn chạy; thêm món mới (cá hồi) chỉ cần DB + link menu. Cuối buổi push code lên GitHub (folder MVC cơ bản), nhắc xem commit history; Q&A ngắn rồi chào đi chơi 8/3.

## Mục lục

```
0:00 Alo / chào; chúc 8/3; mở series Web chuyên sâu (gộp)
2:33 Mục tiêu khóa: đi làm luôn, lương, có người hỏi / đồng hành (gộp)
8:18 Công cụ PhpStorm · Code With Me · GitHub; cam kết dạy MVC dễ hiểu (gộp)
13:01 Học từ 0 → xem SQL/web cơ bản trước; Q&A đăng ký học viên (gộp)
14:14 MVC là gì? Google hình; bắt đầu ẩn dụ nhà hàng 8/3 (gộp)
15:29 Vẽ draw.io: khách → bồi bàn → bàn → đưa menu → gọi món (gộp)
20:50 Ghi đơn → đầu bếp; lấy nguyên liệu tủ lạnh → chế biến → đĩa (gộp)
27:35 Map ẩn dụ → MVC: user / View / Controller / Model / DB (gộp)
33:49 Demo code: tạo index.php trang chủ (gộp)
35:35 Code With Me / Google Meet chia sẻ file; PhpStorm edu license (gộp)
46:35 Tạo controller.php + menu.php (view); include trả menu (gộp)
50:30 index.php gọi controller (không render view trực tiếp) (gộp)
52:22 Link gọi món (?mon=...); if empty → menu else xử lý đơn (gộp)
55:38 Tạo model.php; bảng mon_an + insert bò bít tết (gộp)
58:47 Model: kết nối DB, SELECT theo tên món (gộp)
1:02:38 View dia.php hiện tên + ảnh; vì sao tách nhiều file (gộp)
1:05:36 Ôn lại luồng MVC end-to-end (khách ngồi yên tại index) (gộp)
1:08:23 Lợi ích MVC: sửa 1 chỗ; thêm món cá hồi chỉ sửa menu/DB (gộp)
1:11:56 Kết lý thuyết; push GitHub repo MVC cơ bản (gộp)
1:15:09 Q&A / chờ push / tip PhpStorm (gộp)
1:18:14 Code lên GitHub; xem history; chào / đi chơi 8/3 (gộp)
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
