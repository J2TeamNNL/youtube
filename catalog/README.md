# Catalog

Bot **Catalog** tổng hợp nội dung có cấu trúc từ thư mục `transcripts/`.

- Đọc transcript / meta để dựng mục lục, entry, gom theo chủ đề / series / thời gian / kind.
- **Không ghi đè** `transcripts/` — chỉ đọc, không sửa nguồn.

## Cấu trúc

| Thư mục / file | Mục đích |
| --- | --- |
| `entries/` | Mỗi video một file `slug-<id>.md` (meta, tóm tắt, mục lục) |
| `by-topic/` | Gom theo chủ đề |
| `by-series/` | Gom theo series / playlist |
| `by-time/YYYY/YYYY-MM.md` | Theo tháng phát hành |
| `by-kind/` | Phân loại `video.md` / `live.md` |
| `index.md` | Mục lục mọi video đã vào catalog |

## Quy ước

- Tên entry: `slug-<id>.md` (slug tiếng Việt không dấu, nối bằng `-`, kèm video-id).
- `kind`: `video` hoặc `live`.
- Giọng viết mặc định: tiếng Việt.
- Mỗi entry liên kết về folder transcript (nếu có) và URL YouTube.
