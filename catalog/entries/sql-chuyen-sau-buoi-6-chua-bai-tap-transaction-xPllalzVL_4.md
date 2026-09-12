# SQL chuyên sâu Buổi 6 Chữa bài tập Transaction

- **id:** `xPllalzVL_4`
- **url:** https://www.youtube.com/watch?v=xPllalzVL_4
- **published:** 2021-11-12
- **duration:** 5803s (~1h37m)
- **kind:** live
- **subtitle_source:** auto (ASR — có thể nhiễu / sai từ)
- **folder:** [`transcripts/sql-chuyen-sau-buoi-6-chua-bai-tap-transaction-xPllalzVL_4/`](../../transcripts/sql-chuyen-sau-buoi-6-chua-bai-tap-transaction-xPllalzVL_4/)
- **topics:** sql, database, transaction, trigger
- **series:** SQL chuyên sâu — buổi 6
- **channel:** UCnL9cDH4iZcLmOIF8SzNGYw

## Tóm tắt

Live buổi 6 series SQL chuyên sâu — chữa bài tập buổi 5 rồi mở Transaction. Chào mic/chat, nhắc nợ phần INSTEAD OF UPDATE nhiều sinh viên chuyển lớp (chỗ trống), rồi Q&A mở đầu (thi vấn đáp / chat gửi câu trả lời, buổi cuối series). Vào chữa: đếm số SV chuyển sang lớp mới, so với chỗ trống; nếu đủ thì DELETE khỏi lớp cũ rồi INSERT vào lớp mới (tránh trùng khóa chính), cập nhật chỗ trống cả hai lớp. Demo và debug lâu phần UPDATE nhiều dòng — alias bảng, WHERE theo mã lớp, lọc SV thực sự chuyển (NOT IN), chỗ trống không tăng khi WHERE sai. Giữa buổi chuyển Transaction: try/catch với lỗi runtime (FK, CHECK) khác lỗi cú pháp; BEGIN TRANSACTION đẩy nhiều câu lệnh cùng lúc, một câu lỗi thì ROLLBACK; SAVEPOINT như “save game” trước khi đánh boss. Chat ngắn học bổng/phần thưởng giấy khen. Cuối buổi chữa thêm bài kho–sản phẩm: AFTER trigger cập nhật tổng tài sản khi DELETE/INSERT/UPDATE; xóa kho còn hàng thì báo không xóa được; gợi ý kiểm tra sức chứa theo tổng số lượng. Kết thúc ~1h37m, hẹn buổi sau.

## Mục lục

```
0:00 Chào live, mic, intro chữa BT buổi 5; Q&A mở đầu (gộp)
15:00 Vào chữa: INSTEAD OF UPDATE nhiều SV chuyển lớp
20:00 Đếm chỗ trống lớp mới; DELETE rồi INSERT (tránh trùng PK)
26:00 Lỗi UPDATE nhiều dòng; alias / lọc theo INSERTED
35:00 Cập nhật chỗ trống lớp cũ và lớp mới
45:00 Debug: chỗ trống không tăng; WHERE theo mã lớp
55:00 Lọc SV chuyển (NOT IN); demo nhiều SV cùng lúc
1:04:00 Transaction: try/catch, BEGIN TRAN, COMMIT/ROLLBACK, SAVEPOINT
1:13:00 Chat học bổng / phần thưởng (gộp)
1:18:00 Chữa BT kho–sản phẩm: AFTER cập nhật tổng tài sản
1:30:00 DELETE nhiều kho; còn sản phẩm thì không xóa; sức chứa
1:35:00 Tóm tắt, Q&A cuối, chào
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
