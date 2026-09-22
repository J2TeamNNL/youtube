# Lập trình web chuyên sâu - 8 - Laravel - CRUD

- **id:** `QFsPgDpBak0`
- **url:** https://www.youtube.com/watch?v=QFsPgDpBak0
- **published:** 2022-03-26
- **duration:** 5539s (~1h32m)
- **kind:** live
- **subtitle_source:** auto (ASR — có thể nhiễu / sai từ)
- **folder:** [`transcripts/lap-trinh-web-chuyen-sau-8-laravel-crud-QFsPgDpBak0/`](../../transcripts/lap-trinh-web-chuyen-sau-8-laravel-crud-QFsPgDpBak0/)
- **topics:** web, php, laravel, crud
- **series:** Lập trình web chuyên sâu — buổi 8 Laravel CRUD
- **channel:** UCnL9cDH4iZcLmOIF8SzNGYw
- **transcript commit:** `5031dc7b59f9cae0ca9dbc65843fbad260a2c735`

## Tóm tắt

Live ~1h32m — **buổi 8** series **Lập trình web chuyên sâu**: chuyển sang **Laravel CRUD** một bảng (demo sinh viên), sau các buổi MVC/OOP thuần. Đầu buổi quy ước từ nay **đặt tên biến / code bằng tiếng Anh**; so sánh giáo án dạy lớp (chậm từng bước) với nhịp live nhanh hơn vì đã quen MVC. Livecode trên project Laravel (Laragon): nhắc **không commit `.env`**, `composer install/update`, cấu hình DB; tạo **Model + Migration** (kèm factory/seeder) bằng Artisan thay vì viết SQL tay. Viết migration cột (họ·tên / giới tính…, độ dài string), `migrate` / cơ chế rollback; xóa scaffold mặc định dễ xung đột. **Controller** + **route** + view **Blade** danh sách (Eloquent trả object); giới thiệu **accessor** (ghép họ–tên, map giới tính male/female). Tiếp **create/store**: form Blade (radio…), named route, lấy dữ liệu từ request, validate độ dài; nhấn mạnh tách **Form Request** / không nhét validate dài trong controller. Kết: CRUD Laravel nền tảng (đọc–thêm) đã chạy; tip composer khi clone; buổi sau tiếp CRUD.

## Mục lục

```
0:00 Alo; chào; quy ước đặt tên / code tiếng Anh (gộp)
1:20 Hôm nay CRUD Laravel nhanh (đã biết MVC); giáo án lớp chậm hơn (gộp)
2:50 Mở giáo án: router · giới thiệu từng mục (gộp)
3:00 WordPad lỗi / mở Notepad; ảnh giáo án bay (gộp)
4:00 Upload tài liệu Drive; Q&A cần server để chạy web (gộp)
6:00 Q&A học khóa bao lâu đi làm được (gộp)
7:20 Tâm sự dạy sinh viên / giáo án tự soạn có thể sai (gộp)
10:00 Clone / tải code; mạng chậm (gộp)
12:00 Xóa tài liệu cũ; chỉnh giáo án (gộp)
15:00 Mở project Laravel (Laragon/www); public index (gộp)
18:00 Git: không push .env; vendor / composer (gộp)
20:00 composer install · update khi thiếu thư viện (gộp)
21:00 Seeder / data mẫu; hết web cơ bản → Laravel (gộp)
23:30 Vì sao tạo DB bằng code (migration) thay SQL tay (gộp)
25:00 Model sinh viên; đặt tên tiếng Anh (Students) (gộp)
26:00 Artisan: model + migration + factory + seeder (gộp)
27:00 Controller đã quen; Form Request validate sau (gộp)
30:00 Xóa code/scaffold mặc định trước khi migrate (gộp)
33:00 Migration: độ dài string (50); cột họ·tên; chưa 2 bảng (gộp)
36:00 .env tên DB; chạy migrate thử (gộp)
39:00 Cơ chế migrate / rollback (up–down) (gộp)
42:00 Cột id shorthand; khai báo schema gọn hơn (gộp)
45:00 Route quét lại; hàm index trên controller (gộp)
48:00 Blade: view danh sách sinh viên (+ thư mục views) (gộp)
51:00 Eloquent: hàng DB → object (khác array thủ công) (gộp)
54:00 Accessor: get họ–tên · first_name / last_name (gộp)
57:00 Laravel 8 vs 9 khác chút; ngồi mò cùng (gộp)
1:00:00 Đặt tên route ngắn / helper route() (gộp)
1:03:00 Accessor giới tính male/female; so sánh kiểu chuỗi (gộp)
1:06:00 Tip thực tế / sửa cho chạy được (gộp)
1:09:00 Named route · link create (gộp)
1:12:00 Form create Blade: first_name · sex radio (EN) (gộp)
1:14:00 Route store; method POST (gộp)
1:15:00 Lấy dữ liệu form từ Request (gộp)
1:18:00 Ép kiểu / cảnh báo IDE (gộp)
1:21:00 Validate độ dài (50); báo lỗi nhập (gộp)
1:24:00 Tách logic khỏi controller; Form Request sau (gộp)
1:27:00 Không nhét validate dài trong controller (quy ước Laravel) (gộp)
1:30:00 Tip clone: xóa vendor · composer install; chào (gộp)
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
