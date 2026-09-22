# Lập trình web chuyên sâu - 8 - Laravel - CRUD

- **id:** `QFsPgDpBak0`
- **url:** https://www.youtube.com/watch?v=QFsPgDpBak0
- **published:** 2022-03-26
- **duration:** 5539s (~1h32m)
- **kind:** live
- **subtitle_source:** auto (ASR — có thể nhiễu / sai từ)
- **folder:** [`transcripts/lap-trinh-web-chuyen-sau-8-laravel-crud-QFsPgDpBak0/`](../../transcripts/lap-trinh-web-chuyen-sau-8-laravel-crud-QFsPgDpBak0/)
- **topics:** web, php, laravel, crud
- **series:** Lập trình web chuyên sâu — buổi 8 Laravel - CRUD
- **channel:** UCnL9cDH4iZcLmOIF8SzNGYw
- **transcript commit:** `5031dc7b59f9cae0ca9dbc65843fbad260a2c735`

## Tóm tắt

Live ~1h32m — **buổi 8** series **Lập trình web chuyên sâu**: bắt đầu **Laravel CRUD** sau buổi cài đặt. Đầu buổi nhắc từ nay đặt tên biến/class bằng **tiếng Anh**; ôn tài liệu / so sánh Laravel với PHP thuần MVC; bàn phiên bản Laravel (8/9) và PHP. Livecode: tạo **Model + Migration** (bảng students), cấu hình `.env` / kết nối DB, `migrate`, chỉnh cột (`first_name`…), tạo **Controller**, action `index` + view **Blade** liệt kê; accessor/getter nối họ–tên; khai báo **route** (`web.php`), form create → `store` (Request + Eloquent), CSRF; thảo luận trách nhiệm Controller vs Model / service; ghi chú deploy (`composer install`, lock). Kết: list + create chạy trên Laravel; buổi sau tiếp CRUD (edit/update/delete).

## Mục lục

```
0:00 Alo; chào lớp; từ nay đặt tên tiếng Anh (gộp)
1:30 Bài hôm nay: Laravel CRUD — đơn giản nhưng dạy từ từ (gộp)
3:00 Tài liệu / soạn bài; WordPad lỗi → Notepad (gộp)
6:00 Dạy trường vs đi làm; tài liệu Laravel (gộp)
9:00 Laravel vs PHP thuần; Pocket / tài liệu trả phí (gộp)
12:00 Không bám code cũ; công ty vẫn Laravel 8 (gộp)
15:00 PHP version ↔ Laravel 8/9; cài / Composer (gộp)
18:00 Chạy project; vendor không đẩy git (gộp)
20:00 composer update / install khi thiếu lib (gộp)
23:00 Model + Migration thay tạo DB tay (gộp)
25:00 make:model Student -m; thư mục Model/Migration (gộp)
27:00 Controller / Request — bỏ Form Request hôm nay (gộp)
30:00 Migration: ý nghĩa; cột id / timestamps (gộp)
33:00 Schema students: first_name…; kiểu dữ liệu (gộp)
35:00 File .env — cấu hình kết nối CSDL (gộp)
37:00 Chạy migrate; nullable / default (gộp)
40:00 Kiểu cột; fillable / Eloquent (gộp)
43:00 Tạo Controller từng bước (artisan / tay) (gộp)
45:00 Hàm index; lấy danh sách sinh viên (gộp)
48:00 View Blade index; truyền $students (gộp)
51:00 Loop Blade; hiển thị cột (gộp)
53:00 View chỉ hiển thị; logic ở Model/Controller (gộp)
56:00 Accessor/getter: nối first_name + last_name (gộp)
59:00 getAttribute Eloquent / helper (gộp)
1:02:00 Truyền dữ liệu ra view; format hiển thị (gộp)
1:05:00 Insert thủ công vs Eloquent (gộp)
1:07:00 Route web.php; tránh hard-code URL (gộp)
1:10:00 Đặt tên route; sửa route ít đụng view (gộp)
1:12:00 Nút Create; form Blade (gộp)
1:14:00 Route store (POST); CSRF token (gộp)
1:17:00 IDE / gõ tắt; đọc Request (gộp)
1:19:00 store: request → Student; Eloquent save (gộp)
1:20:30 fillable / mass assignment (gộp)
1:22:30 Controller trung chuyển; Model xử lý data (gộp)
1:25:00 Tách service; tránh nhồi logic Controller (gộp)
1:28:00 Push code; vendor vs composer.lock / install (gộp)
1:30:00 Q&A; inbox; chào kết (gộp)
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
