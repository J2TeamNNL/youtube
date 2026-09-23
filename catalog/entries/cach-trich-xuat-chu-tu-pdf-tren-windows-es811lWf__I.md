# Cách trích xuất chữ từ PDF trên Windows

- **id:** `es811lWf__I`
- **url:** https://www.youtube.com/watch?v=es811lWf__I
- **published:** 2024-11-30
- **duration:** 574s (~9m34s)
- **kind:** video
- **subtitle_source:** auto
- **folder:** [`transcripts/cach-trich-xuat-chu-tu-pdf-tren-windows-es811lWf__I/`](../../transcripts/cach-trich-xuat-chu-tu-pdf-tren-windows-es811lWf__I/)
- **topics:** pdf, ocr, windows, cong-cu
- **series:** —
- **channel:** J2TeamNNL Blog

## Tóm tắt

Hướng dẫn ~9 phút 30 giây trên **Windows** (người nói đang dùng Windows 11): một PDF hơn 200 trang, hơn 100 MB, bản chất là **ảnh** nên thư viện PDF-to-text không ra chữ, còn tool online miễn phí thì chặn vì dung lượng. Cách làm là cài bộ OCR (phụ đề nghe như bản release, có gói tiếng Việt), thêm công cụ đổi PDF thành ảnh, đưa cả hai thư mục vào **PATH** (Advanced system settings → Environment) để gọi lệnh không cần gõ full path, kiểm tra ra version. Sau đó viết lệnh / file `.bat` xuất từng trang thành ảnh (tên file có dấu cách thì bọc nháy; phải tạo sẵn thư mục output) rồi nhận diện ảnh sang chữ. Kết quả nhận tương đối, và miễn phí so với dịch vụ tính phí.

## Mục lục

```
0:04 PDF 200+ trang dạng ảnh; tool online đòi trả phí
0:35 PDF-to-text không được vì không phải text layer
1:02 Tải bản release, cài, chọn ngôn ngữ tiếng Việt
1:47 Thêm thư viện OCR và công cụ xuất PDF ra ảnh
2:20 Copy đường dẫn thư viện; tìm thư mục cài
2:43 Thêm PATH trong Environment Variables
3:48 Chạy lại lệnh, thấy version là được
4:00 Viết batch vì phải xử lý ~200 trang
5:26 Lệnh xuất PDF thành ảnh (tên có dấu cách thì bọc nháy)
6:32 Tạo thư mục output nếu chưa có, rồi ra loạt ảnh
7:19 File .bat gọi OCR; sửa lại đường dẫn ảnh
9:03 OCR chạy, nhận diện tương đối và không mất phí
```

> Lưu ý: phụ đề auto ASR có thể nhiễu; ưu tiên nghe lại đoạn quan trọng nếu cần trích dẫn chính xác.
