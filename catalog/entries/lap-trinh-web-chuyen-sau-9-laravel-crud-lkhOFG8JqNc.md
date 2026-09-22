# Lập trình web chuyên sâu - 9 - Laravel - CRUD

- **id:** `lkhOFG8JqNc`
- **url:** https://www.youtube.com/watch?v=lkhOFG8JqNc
- **published:** 2022-03-29
- **duration:** 6049s (~1h41m)
- **kind:** live
- **subtitle_source:** auto (ASR — có thể nhiễu / sai từ)
- **folder:** [`transcripts/lap-trinh-web-chuyen-sau-9-laravel-crud-lkhOFG8JqNc/`](../../transcripts/lap-trinh-web-chuyen-sau-9-laravel-crud-lkhOFG8JqNc/)
- **topics:** web, php, laravel, crud
- **series:** Lập trình web chuyên sâu — buổi 9 Laravel CRUD
- **channel:** UCnL9cDH4iZcLmOIF8SzNGYw
- **transcript commit:** `0cb0cc2e74243c45bacc92e932aa2d17f1595e46`

## Tóm tắt

Live ~1h41m — **buổi 9** series **Lập trình web chuyên sâu**: làm **CRUD** trên **Laravel 8** (chọn 8 thay vì 9 cho chắc/bài bản; kiến thức vẫn dùng khi lên 9). Mục tiêu: xem–thêm–sửa–xóa chỉ vài dòng nhờ framework (resource controller, Eloquent, Blade). Đầu buổi tâm sự chọn ngành / may mắn / nghĩa vụ quân sự / Q&A (Tony Phong, startup vs công ty ổn định). Tip: alias CMD/`php artisan`, Laragon PHP 7.4 + cập nhật Composer. Demo bảng **Course** (`Course` model + migration + resource controller): `id` bigIncrements, `name` unique, timestamps; `Route::resource` → index/create/store/show/edit/update/destroy. View index; format ngày với **Carbon** / accessor trên Model. Form create Blade + CSRF; store qua `Request` → Eloquent `save` / mass assignment (`fillable` vs `guarded`, trừ `_token`); `redirect()->route(...)`. Xóa bằng form spoof method `DELETE` + route-model binding / `findOrFail`. Edit/update tương tự (GET edit, PUT/PATCH update). So sánh Eloquent (object + model events) vs Query Builder (nhanh hơn, không bắt event); soft delete / restore nhắc qua; BT: tìm hiểu thêm events (`creating`/`created`/`updating`…). Cuối buổi push code, nhấn mạnh Laravel rút ngắn code so với PHP thuần MVC, khuyến khích hỏi thêm.

## Mục lục

```
0:00 Alo / chào; hôm nay Laravel CRUD xem–thêm–sửa–xóa (gộp)
2:22 Code With Me; tâm sự may mắn / tin tưởng / hi vọng (gộp)
4:43 Chọn ngành: nhu cầu · đam mê · năng lực; video ikigai (gộp)
8:07 Học lập trình để biết ≠ ai cũng theo nghề; trải nghiệm nhiều job (gộp)
10:43 Q&A nghĩa vụ quân sự / trải nghiệm nội trú (gộp)
14:41 Q&A Tony Phong; học từ dự án thực tế (gộp)
17:00 Chốt dạy Laravel 8 (không 9); alias CMD / artisan tắt (gộp)
20:52 Vào bài: tạo 2 bảng (Course / sinh viên); make:model -mcr (gộp)
22:48 Laragon PHP 7.4 · Composer · tạo model+migration+controller (gộp)
25:07 Migration Course: id · timestamps · name unique; migrate (gộp)
28:46 routes/web.php → Route resource CourseController (gộp)
29:25 Resource: index · create · store · show · edit · update · destroy (gộp)
30:19 Index: Course::all → return view; compact data (gộp)
32:18 Chỉ giữ cột cần; format ngày view / Carbon (gộp)
36:41 Accessor trên Model format created_at (Eloquent biến đổi data) (gộp)
41:59 Create: route courses/create; Blade form + CSRF → store (gộp)
44:31 Route group prefix/name; rút gọn khai báo CRUD (gộp)
49:18 Store: new Course + request → save; timestamps tự điền (gộp)
50:39 Mass assignment: fill() / except(_token); lỗi bảo mật (gộp)
53:35 $fillable vs $guarded; demo hacker thêm field ẩn (gộp)
57:14 Redirect về index bằng route name (gộp)
58:44 Destroy: form method DELETE + id; route-model binding (gộp)
1:01:21 Spoof _method DELETE trong form (HTML chỉ GET/POST) (gộp)
1:05:30 findOrFail vs find; destroy object → redirect (gộp)
1:09:54 Edit: route edit + id; findOrFail → view form (gộp)
1:12:55 Update: PUT/PATCH + fillable; update() / save (gộp)
1:17:15 Hẹn validate / request only buổi sau; Q&A Facebook/web (gộp)
1:18:26 Soft delete · restore (nhắc); Eloquent vs Query Builder (gộp)
1:29:21 Model events (creating/created/updating…); khi nào dùng QB (gộp)
1:34:01 BT về nhà: pluck/update có tạo object không; xong 1 bảng (gộp)
1:35:35 Push code; bạn mới có thể choáng — Laravel ngắn hơn PHP thuần (gộp)
1:38:45 Ôn: framework hỗ trợ nâng cấp DB/sửa 1 chỗ; khuyến khích hỏi; kết (gộp)
```

> Lưu ý: phụ đề auto ASR có thể nhiễu (Laravel↔L'Oreal, Course↔cost, …); ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
