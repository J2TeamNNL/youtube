# Lập trình web chuyên sâu - 3 - MVC - CRUD 2 bảng

- **id:** `3V5iGyUyfxA`
- **url:** https://www.youtube.com/watch?v=3V5iGyUyfxA
- **published:** 2022-03-13
- **duration:** 5922s (~1h39m)
- **kind:** live
- **subtitle_source:** auto (ASR — có thể nhiễu / sai từ)
- **folder:** [`transcripts/lap-trinh-web-chuyen-sau-3-mvc-crud-2-bang-3V5iGyUyfxA/`](../../transcripts/lap-trinh-web-chuyen-sau-3-mvc-crud-2-bang-3V5iGyUyfxA/)
- **topics:** web, php, mvc, crud
- **series:** Lập trình web chuyên sâu — buổi 3 MVC CRUD 2 bảng
- **channel:** UCnL9cDH4iZcLmOIF8SzNGYw
- **transcript commit:** `7a18ffe558cbac811acb0623110d4eccf56acded`

## Tóm tắt

Live ~1h39m — **buổi 3** series **Lập trình web chuyên sâu**: mở rộng MVC CRUD từ một bảng sang **hai bảng** (`lớp` + `sinh_vien`) trên PHP thuần. Đầu buổi tâm sự dài (bạn thiếu tự tin / niềm tin, quảng cáo–riêng tư iOS, mẹo Excel–Google, tiếng Anh…) rồi vào bài: tạo bảng lớp (tạm bỏ khóa ngoại), menu danh sách lớp / sinh viên, tách **controller theo entity** (không còn một controller tổng). Làm CRUD lớp trước (index view → create/store → edit/update → delete, redirect sau POST). Khi CRUD sinh viên cần select lớp: controller sinh viên **gọi Model lớp** lấy danh sách; form create/edit có `<select>` mã lớp; store/update truyền thêm mã lớp. Livecode hơi “loạn” vì require Model qua lại và copy-paste thư mục lớp → sinh viên; nhấn mạnh hôm nay mức nông dân, buổi sau OOP sẽ gọn hơn. Cuối buổi ôn: hai bảng phải tách Model/controller và gọi chéo hàm; xin lỗi nhịp hơi chậm, hẹn OOP.

## Mục lục

```
0:00 Alo; CRUD 2 bảng nhanh nhờ copy–paste; xin tâm sự trước (gộp)
1:01 Tâm sự bạn IT thiếu tự tin / việc làm / tán gái (gộp)
3:14 Niềm tin · làm chủ số phận · không tin bói toán (gộp)
6:11 Video / quảng cáo Facebook; iOS chặn theo dõi (gộp)
9:15 Privacy vs quảng cáo cá nhân hóa (gộp)
10:07 Lộ trình: hôm nay 2 bảng; buổi sau OOP; tái dùng code cũ (gộp)
12:15 Tâm sự học tiếng Anh · cô cấp 3 · IELTS (gộp)
15:17 Quảng cáo lộ · mẹo Excel ngày tháng / sheet.new (gộp)
18:18 Mẹo Google · chủ động tra cứu thay vì nhớ mẹo (gộp)
22:53 Excel hấp dẫn vs nhớ công thức; chuẩn bị vào bài (gộp)
24:25 Meet / Code With Me; link lớp trưởng (gộp)
25:06 Bắt đầu: thêm bảng lớp (mã · tên); tạm bỏ khóa ngoại (gộp)
27:31 Menu danh sách lớp / sinh viên; gọi controller (gộp)
30:11 Tách controller: lớp vs sinh viên (thay controller tổng) (gộp)
33:35 Đổi tên / copy cấu trúc; thư mục views theo entity (gộp)
36:37 View index lớp; Model lấy danh sách; hiển thị bảng (gộp)
39:39 Href mất controller — truyền controller trên URL (gộp)
41:09 PHP 7 null coalescing cho controller/action (gộp)
42:43 Create lớp: form → store; Model INSERT; redirect (gộp)
48:23 Edit/update lớp theo mã; quên redirect rồi bổ sung (gộp)
53:15 Delete lớp; copy pattern CRUD xong một bảng (gộp)
55:08 Nhược điểm require Model trong controller; file connect (gộp)
58:01 Ôn MVC 1 bảng ổn; sang sinh viên cần gắn lớp (gộp)
61:00 Sinh viên phải có lớp; LEFT JOIN / gán mặc định (gộp)
63:03 Vấn đề: controller SV gọi Model lớp cho <select> (gộp)
65:35 Global / require Model lớp từ controller SV (gộp)
70:18 Cách “nông dân” function connect; buổi sau OOP gọn hơn (gộp)
73:22 Edit SV: truyền mã lớp; update kèm lớp (gộp)
77:57 Delete SV; giải thích phải có hàm gọi chéo Model (gộp)
79:28 Copy CRUD lớp → sinh viên; select options lớp (gộp)
84:10 Tip: hạn chế hard-code tên bảng/cột khi đổi schema (gộp)
85:40 Store SV + mã lớp; debug nhảy nhầm controller (gộp)
88:03 Edit SV load lớp; lỗi biến connect / escape SQL (gộp)
91:48 Framework sẽ bớt viết SQL tay; sức mạnh “nông dân” vs FW (gộp)
93:19 Ôn: CRUD 2 bảng = gọi Model entity khác; hẹn OOP (gộp)
94:49 Xin lỗi nhịp hôm nay; buổi sau OOP một bảng rồi hai bảng (gộp)
96:19 Học tích cực khi code loạn; push code / chào kết (gộp)
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
