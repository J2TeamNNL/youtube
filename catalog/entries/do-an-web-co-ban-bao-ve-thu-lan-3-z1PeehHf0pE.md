# Đồ án Web cơ bản - Bảo vệ thử lần 3

- **id:** `z1PeehHf0pE`
- **url:** https://www.youtube.com/watch?v=z1PeehHf0pE
- **published:** 2022-02-24
- **duration:** 7245s (~2h01m)
- **kind:** live
- **subtitle_source:** auto (ASR — có thể nhiễu / sai từ)
- **folder:** [`transcripts/do-an-web-co-ban-bao-ve-thu-lan-3-z1PeehHf0pE/`](../../transcripts/do-an-web-co-ban-bao-ve-thu-lan-3-z1PeehHf0pE/)
- **topics:** do-an, web, bao-ve-do-an, soft-skills
- **series:** Đồ án web cơ bản — bảo vệ thử lần 3
- **channel:** UCnL9cDH4iZcLmOIF8SzNGYw

## Tóm tắt

Live ~2h bảo vệ thử lần 3: phần đầu dài chờ nhóm — xem / bàn video kiến thức–lịch sử–thời sự, rồi FAQ nghề (lương, kinh nghiệm, học lập trình, mindset). Gọi lần lượt nhiều nhóm (1, 2, 11, 16, 18, 22…) nhưng phần lớn vắng / xin đợt sau; nhắc thứ bảy sẽ bảo vệ thật. Nhóm Shop Thời Trang (Nguyễn Huy Hùng + Bùi Việt): đề tài mua sắm online; đối tượng vãng lai / KH / NV / QL; góp ý ERD (chi tiết hóa đơn không phải thực thể, cột duyệt đơn trong order vs bảng lịch sử); demo đăng ký–validate, thử SQL injection login, giỏ–đặt hàng, admin; tip ưu tiên menu hóa đơn, radio thay input số. Nhóm 18 (Đoàn Nguyễn Huy, một mình): shop (Vespa / SP nhiều size); ERD tag N–N, góp ý không nhồi product_id+size vào một cột / status ở bill vs bill detail; demo đặt hàng–admin; khen tự lực nhưng nên hỏi sớm. Nhóm 17 (Hà Trung Thiện): bán quần áo; comment/rating, quên MK email; góp ý FK đánh giá gắn hóa đơn chi tiết, không xóa SP đã có trong đơn, menu danh mục dễ tràn, sắp xếp đơn theo trạng thái; kiểm tra IDOR xem đơn. Tổng kết: đừng sửa code lung tung trước bảo vệ thật; tip đọc ý chính slide; kết live.

## Mục lục

```
0:00 Chào / chờ; xem video kiến thức–lịch sử (gộp)
6:04 Cảnh báo / xem clip Q&A YouTuber (gộp)
13:00 Digression dạy học / nguyên tắc sống (gộp)
18:32 Nhắc bắt đầu bảo vệ; danh sách nhóm (gộp)
20:14 Gọi nhóm; tiếp tâm sự nghề / lương / học code (gộp)
40:00 FAQ nghề: thời gian học, sửa đồ, lương ngành (gộp)
53:41 Gọi nhóm 1 / 2 / 16…; nhiều nhóm vắng (gộp)
56:57 Nhóm 22 xin đợt 2; điểm danh tiếp (gộp)
59:08 Nhắc bảo vệ thật thứ bảy; gọi nhóm có mặt (gộp)
1:00:04 Shop Thời Trang: đề tài & đối tượng KH–NV–QL (gộp)
1:01:38 ERD: chi tiết HĐ / order; ảnh ERD (gộp)
1:04:33 Góp ý cột duyệt đơn vs bảng lịch sử (gộp)
1:06:54 Demo KH: trang chủ / đăng ký validate (gộp)
1:09:19 Hỏi validate email tồn tại / MK ≠ email (gộp)
1:11:26 Login / thử SQL injection (gộp)
1:13:56 Giỏ hàng / đặt hàng / đơn bên admin (gộp)
1:15:18 Demo admin: NV / SP / NSX / hóa đơn (gộp)
1:16:15 Góp ý UX: thêm nhanh; ưu tiên menu hóa đơn (gộp)
1:18:12 Cảm ơn nhóm Thời Trang; gọi nhóm 18 (gộp)
1:20:10 Nhóm 18 (1 TV): đề tài / công nghệ / chức năng (gộp)
1:21:33 ERD: tag N–N; token / cookie; bill–status (gộp)
1:24:00 Góp ý tách cột SP trong bill detail (gộp)
1:25:25 Status ở HĐ vs chi tiết; tên cột (gộp)
1:27:17 Demo KH: đăng nhập / đổi MK / đặt hàng (gộp)
1:29:00 Size nhiều giá trị / UX nhập khó (gộp)
1:30:25 Admin duyệt đơn; khen tự lực (gộp)
1:31:44 Kết nhóm 18; gọi nhóm tiếp (gộp)
1:32:48 Điểm danh 7 / 22 / 17 / 13; soft-skills làm 1 mình (gộp)
1:35:44 Nhóm 13 / 9 vắng; chờ nhóm 17 (gộp)
1:38:40 Nhóm 17 bán quần áo: đề tài & đối tượng (gộp)
1:41:31 ERD / comment–rating; góp ý thực thể (gộp)
1:44:21 CSDL: NSX / thể loại / order–item / quên MK (gộp)
1:46:22 Tip thuyết trình: giọng chậm khó nghe (gộp)
1:48:07 Demo KH: giỏ / bắt buộc ĐN để đặt hàng (gộp)
1:50:04 Validate ĐK / quên MK email (gộp)
1:51:24 Đặt hàng / lịch sử đơn / hủy đơn (gộp)
1:52:31 Góp ý FK đánh giá → HĐ chi tiết (gộp)
1:53:54 Admin: SP / danh mục; không xóa SP đã bán (gộp)
1:55:46 Đơn hàng: sắp xếp TT; kiểm tra IDOR (gộp)
1:58:17 Hỏi còn nhóm; nhắc đừng sửa code lung tung (gộp)
1:59:46 Tạm kết; tip đọc slide bảo vệ thật (gộp)
2:00:32 Kết live (gộp)
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
