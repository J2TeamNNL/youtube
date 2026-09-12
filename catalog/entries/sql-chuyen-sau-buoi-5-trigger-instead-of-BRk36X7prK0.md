# SQL chuyên sâu Buổi 5 Trigger Instead of

- **id:** `BRk36X7prK0`
- **url:** https://www.youtube.com/watch?v=BRk36X7prK0
- **published:** 2021-11-04
- **duration:** 5517s (~1h32m)
- **kind:** live
- **subtitle_source:** auto (ASR — có thể nhiễu / sai từ)
- **folder:** [`transcripts/sql-chuyen-sau-buoi-5-trigger-instead-of-BRk36X7prK0/`](../../transcripts/sql-chuyen-sau-buoi-5-trigger-instead-of-BRk36X7prK0/)
- **topics:** sql, database, trigger
- **series:** SQL chuyên sâu — buổi 5
- **channel:** UCnL9cDH4iZcLmOIF8SzNGYw

## Tóm tắt

Live buổi 5 series SQL chuyên sâu — Trigger (Instead of). Chào mic/chat, Q&A mở đầu (khóa web nâng cao/MVC, try-catch vs lỗi compile/runtime, chuyện dạy–chấm điểm) rồi mới vào bài. Ôn lại After vs Instead of: After chạy sau DML; Instead of dùng khi cần kiểm tra/can thiệp trước khi ghi. Đổi bài toán lớp/SV: thay “số lượng” bằng “số chỗ trống” (vd. tối đa 20) — mỗi lần thêm SV phải giảm chỗ trống, hết chỗ thì báo lỗi không cho INSERT. `CREATE TRIGGER` INSTEAD OF INSERT: đọc `INSERTED`, lấy chỗ trống; =0 thì `RAISERROR`/không ghi; còn chỗ thì `UPDATE` chỗ trống −1 rồi tự `INSERT INTO` SV (nhớ `BEGIN`/`ELSE` kẻo code chạy tiếp sau lỗi). DELETE thường dùng After (tăng lại chỗ trống) cho gọn; UPDATE chuyển lớp sang lớp đầy cần Instead of UPDATE (kiểm tra chỗ lớp mới, rồi điều chỉnh chỗ trống cũ/mới). Nâng cao: INSERT nhiều bản ghi — đếm theo lớp (`COUNT`/`GROUP BY` từ `INSERTED`), so với chỗ trống; `INSERT … SELECT FROM INSERTED` thay declare từng cột. Cuối buổi đoạn UPDATE nhiều dòng còn phức tạp nên hẹn chữa buổi sau; giao bài tập mới rồi chào.

## Mục lục

```
0:00 Chào live, mic/chat, Q&A mở đầu (gộp)
26:00 Vào bài: After vs Instead of; DDL vs DML
28:18 Khác After: kiểm tra trước; bài toán chỗ trống
31:10 Setup bảng lớp/SV (chỗ trống); seed dữ liệu
34:19 INSTEAD OF INSERT; INSERTED; RAISERROR hết chỗ
40:16 Thành công: UPDATE chỗ trống −1 rồi INSERT SV
42:18 BEGIN/ELSE; demo lỗi khi lớp đầy
45:34 DELETE → After tăng chỗ; UPDATE chuyển lớp đầy
54:07 INSTEAD OF UPDATE; DELETED + INSERTED
1:00:00 INSERT nhiều SV; COUNT/GROUP BY theo lớp
1:06:45 INSERT … SELECT FROM INSERTED (không declare tay)
1:27:00 Demo UPDATE nhiều dòng; tạm dừng, bài tập & chào
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
