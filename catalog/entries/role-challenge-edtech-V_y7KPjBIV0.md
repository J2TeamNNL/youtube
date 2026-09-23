# Role challenge - EdTech

- **id:** `V_y7KPjBIV0`
- **url:** https://www.youtube.com/watch?v=V_y7KPjBIV0
- **published:** 2026-01-08
- **duration:** 3266s (~54m26s)
- **kind:** video
- **subtitle_source:** auto
- **folder:** [`transcripts/role-challenge-edtech-V_y7KPjBIV0/`](../../transcripts/role-challenge-edtech-V_y7KPjBIV0/)
- **topics:** phong-van-nghe-nghiep, edtech, laravel, hieu-nang
- **series:** —
- **channel:** J2TeamNNL Blog

## Tóm tắt

Video ~54 phút, nói **song ngữ** (Việt trước, Anh sau) về cách làm một bài **role challenge / phỏng vấn** cho sản phẩm EdTech. Bài 1: monitor báo API chậm, connection quá tải, error rate cao, một số trường bị đơ sau khi vừa thêm điểm danh và thông báo realtime cho phụ huynh. Chẩn đoán: xem log và git, tái hiện local (nhắc Telescope/Clockwork nếu Laravel), thấy N+1 và query thừa, luồng đi ngược từ học sinh lên trường. Hướng sửa theo version để dễ rollback: đẩy thông báo sang queue, SQL increment thay vì select-rồi-update, eager load, rồi điểm danh theo trường một lần. Có đoạn đánh đổi: nhét cả object vào job thì dữ liệu có thể đã đổi; cache thống kê và job chạy mỗi ngày thì nhanh hơn nhưng kém tức thời. Bài 2 (tech lead): khoảng 500 trường Indonesia sắp tăng mạnh — ưu tiên rate limit / bớt realtime thừa và ổn định database trước chi phí AWS; crash app thì hot-fix sớm. Bài 3: hai tuần, chia người giữa sửa hiệu năng, tính năng riêng cho Indo (đủ mức demo) và monitor/alerting; không dồn cả team vào một việc. Cuối video nhận xét đề bài và cách dùng AI để tóm tắt, vẫn phải nghĩ kiến trúc và code sạch trước khi nhờ AI viết tiếp.

## Mục lục

```
0:00 Mở đầu song ngữ: cách làm bài challenge
1:30 Bài 1: API chậm, connection quá tải, app trường đơ
3:00 Giả thuyết: điểm danh mới, thông báo phụ huynh, data tăng
4:30 Log, git blame, pair; tái hiện local (Telescope/Clockwork)
9:00 N+1, query thừa, luồng đi ngược từ lá lên gốc
10:30 Tách thông báo sang queue; SQL increment
15:00 Version 2: increment, mỗi query rất ngắn
16:30 Version 3: chống N+1, ship từng bản để dễ rollback
19:30 Version 4: điểm danh cả trường một lần, một query
22:30 Đánh đổi job: đừng serialize cả object
27:00 Cache thống kê, cập nhật một lần mỗi ngày
28:30 Bài 2: tech lead, ~500 trường Indo sắp nhân quy mô
30:00 Realtime sập, memory PHP, chi phí AWS, trễ liên vùng
31:30 Ưu tiên rate limit; không phải cập nhật nào cũng realtime
33:00 Chi phí hạ tầng để sau, đừng cắt trải nghiệm khách
34:30 Một database chậm ảnh hưởng mọi trường; nghĩ tới region
36:00 Thứ tự: rate limit, database, hot-fix crash app
39:00 Bài 3: ba việc trong hai tuần (hiệu năng / tính năng Indo / monitor)
40:30 Không dồn cả team vào một phương án
42:00 Chia người: hiệu năng luôn có; tính năng đủ demo
45:00 Monitor và alerting kẻo khách crash rồi bỏ đi
46:30 Hai tuần đủ để demo cho khách và CEO
48:00 Đông người không làm xong nhanh hơn
49:30 Cảm nhận đề challenge
51:00 Dùng AI để tóm tắt nhưng vẫn thiết kế trước
54:00 Kết
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
