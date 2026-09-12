# SQL chuyên sâu Buổi 4 Trigger After

- **id:** `Oc-IlA-1jxc`
- **url:** https://www.youtube.com/watch?v=Oc-IlA-1jxc
- **published:** 2021-10-28
- **duration:** 4325s (~1h12m)
- **kind:** live
- **subtitle_source:** auto (ASR — có thể nhiễu / sai từ)
- **folder:** [`transcripts/sql-chuyen-sau-buoi-4-trigger-after-Oc-IlA-1jxc/`](../../transcripts/sql-chuyen-sau-buoi-4-trigger-after-Oc-IlA-1jxc/)
- **topics:** sql, database, trigger
- **series:** SQL chuyên sâu — buổi 4
- **channel:** UCnL9cDH4iZcLmOIF8SzNGYw

## Tóm tắt

Live buổi 4 series SQL chuyên sâu — Trigger (After). Chào mic/chat, tâm sự ngắn rồi Q&A (mật khẩu, tối ưu INSERT/UPDATE/DELETE, tiện ích web…) trước khi vào bài. Giới thiệu Trigger: kích hoạt theo sự kiện; ba loại (login / After / Instead of) — buổi này học After (chạy sau DML). Demo bảng lớp + sinh viên: INSERT SV nhưng số lượng lớp không tự cập nhật → cần Trigger. `CREATE TRIGGER` AFTER INSERT: bảng `INSERTED`, gán biến mã lớp, `UPDATE` số lượng +1; `CREATE OR ALTER`. AFTER DELETE: bảng `DELETED`, số lượng −1. AFTER UPDATE: bản chất INSERT+DELETE — lấy mã lớp cũ từ `DELETED`, mã mới từ `INSERTED`. Nâng cao: INSERT nhiều bản ghi cùng lúc → biến scalar lỗi (subquery nhiều dòng); dùng `COUNT` + `GROUP BY` / `JOIN` bảng `INSERTED` để cộng đúng theo lớp. Tổng kết After; Instead of để buổi sau. Cuối buổi chia sẻ đời thường rồi chào.

## Mục lục

```
0:00 Chào live, mic/chat, Q&A mở đầu (gộp)
14:18 Vào bài Trigger: khái niệm; After vs Instead of
23:54 Setup bảng lớp/SV; bài toán số lượng tự động
25:49 CREATE TRIGGER AFTER INSERT; bảng INSERTED
35:12 AFTER DELETE; bảng DELETED; số lượng −1
39:00 AFTER UPDATE: DELETED + INSERTED; đổi lớp SV
45:17 INSERT nhiều bản ghi; lỗi scalar; COUNT/GROUP BY
54:43 JOIN INSERTED cập nhật nhiều lớp (nâng cao)
1:02:20 Tổng kết After; preview Instead of buổi sau
1:04:10 Chia sẻ cuối buổi & chào (gộp)
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
