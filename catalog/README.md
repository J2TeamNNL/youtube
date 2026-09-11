# Catalog

Kho nội dung có cấu trúc, dựng từ transcript trong `transcripts/`.

Bot **Catalog** đọc transcript (không sửa folder đó) rồi cập nhật các mục dưới đây.

## Cấu trúc

| Thư mục | Mục đích |
| --- | --- |
| `by-topic/` | Gom theo chủ đề |
| `by-series/` | Gom theo series / playlist |
| `by-time/` | Theo thời gian phát hành |
| `index.md` | Mục lục mọi video đã đưa vào catalog |

## Quy ước

- Nguồn gốc: `transcripts/<video-id>/meta.json` + `transcript.md`
- Không ghi đè `transcripts/`
- Giọng viết mặc định: tiếng Việt
- Mỗi mục topic/series liên kết về `video-id` và tiêu đề gốc
