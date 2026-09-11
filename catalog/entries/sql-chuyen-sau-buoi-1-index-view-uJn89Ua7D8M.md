# SQL chuyên sâu Buổi 1 Index View

- **id:** `uJn89Ua7D8M`
- **url:** https://www.youtube.com/watch?v=uJn89Ua7D8M
- **published:** 2021-10-07
- **duration:** 5221s (~1h27m)
- **kind:** live
- **subtitle_source:** auto (ASR — có thể nhiễu / sai từ)
- **folder:** [`transcripts/sql-chuyen-sau-buoi-1-index-view-uJn89Ua7D8M/`](../../transcripts/sql-chuyen-sau-buoi-1-index-view-uJn89Ua7D8M/)
- **topics:** sql, database, index, view
- **series:** SQL chuyên sâu — buổi 1
- **channel:** UCnL9cDH4iZcLmOIF8SzNGYw

## Tóm tắt

Live buổi 1 series SQL chuyên sâu — Index & View (tách khỏi series SQL cơ bản). Chào mic/chat, xem mục lục, Q&A thiết kế bảng lương nhiều lần nhập trước khi vào bài. Demo `SELECT` trên ~1 triệu bản ghi để thấy chậm khi full scan; giải thích Index gắn với khóa chính, phân biệt clustered vs non-clustered, `CREATE INDEX`, trade-off SELECT nhanh hơn nhưng INSERT/UPDATE/DELETE chậm hơn, khi nào nên/không nên đánh Index và unique. Sang View: góc nhìn lọc cột nhạy cảm, bảo mật (không đụng bảng gốc), `CREATE VIEW` / `DROP VIEW`, View nối nhiều bảng để câu `SELECT` ngắn hơn. Cuối buổi chuyên mục “nếu hacker đọc được DB”: không lưu mật khẩu thô, hash (MD5/…), rainbow table, salt & pepper rồi chào.

## Mục lục

```
0:00 Chào live, mic/chat, mục lục & Q&A lương nhiều bảng (gộp)
15:30 Demo SELECT chậm (~1M bản ghi); vì sao cần Index
21:30 Index & khóa chính; clustered vs non-clustered
27:00 CREATE INDEX; so sánh tốc độ truy vấn
33:00 Index mapping / cấu trúc; trade-off INSERT·UPDATE·DELETE
45:00 Lời khuyên đánh Index; unique vs clustered/non-clustered
51:40 Xong Index → View: góc nhìn & lọc cột nhạy cảm
56:00 CREATE VIEW; bảo mật / khóa bảng gốc
1:00:20 View nối nhiều bảng; SELECT ngắn hơn; DROP VIEW
1:07:40 Nếu hacker đọc DB: hash, rainbow table, salt/pepper & chào (gộp)
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
