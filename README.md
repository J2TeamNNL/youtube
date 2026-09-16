# youtube

Kho transcript + catalog từ kênh YouTube [J2TeamNNL Blog](https://www.youtube.com/channel/UCnL9cDH4iZcLmOIF8SzNGYw).

Mỗi live/video có thư mục transcript (phụ đề chuẩn hóa + metadata). Catalog gom theo series / chủ đề / thời gian. Mô tả trên YouTube gắn mục lục timestamp, Discord, hashtag topic, và trỏ về repo này.

## Liên kết

- **Discord:** [https://discord.gg/8G39DeVhDX](https://discord.gg/8G39DeVhDX)
- **Kênh YouTube:** [J2TeamNNL Blog](https://www.youtube.com/channel/UCnL9cDH4iZcLmOIF8SzNGYw)
- **Repo:** [https://github.com/J2TeamNNL/youtube](https://github.com/J2TeamNNL/youtube)

## Cấu trúc

```
transcripts/          # phụ đề thô + transcript.md theo từng video
  <slug>-<videoId>/
    meta.json
    transcript.md
    *.vtt             # khi có phụ đề
catalog/              # mục lục / series / topic (bot Catalog)
  entries/            # mỗi video một file
  by-series/          # gom theo series
  by-topic/           # gom theo chủ đề (→ hashtag mô tả YT)
  by-time/            # theo tháng phát hành
  by-kind/            # video.md / live.md
  index.md            # mục lục mọi video đã catalog
```

Chi tiết naming và `meta.kind` xem [`transcripts/README.md`](transcripts/README.md). Cách Catalog tổ chức xem [`catalog/README.md`](catalog/README.md).

## Catalog — vào nhanh

- **[Mục lục tất cả](catalog/index.md)**
- **[Theo series](catalog/by-series/README.md)** · **[Theo chủ đề](catalog/by-topic/README.md)** · **[Live](catalog/by-kind/live.md)** · **[Video](catalog/by-kind/video.md)**

### Series

| Series | File |
| --- | --- |
| Road to Interview | [catalog/by-series/road-to-interview.md](catalog/by-series/road-to-interview.md) |
| SQL | [catalog/by-series/sql.md](catalog/by-series/sql.md) |
| SQL chuyên sâu | [catalog/by-series/sql-chuyen-sau.md](catalog/by-series/sql-chuyen-sau.md) |
| Lập trình web cơ bản | [catalog/by-series/lap-trinh-web-co-ban.md](catalog/by-series/lap-trinh-web-co-ban.md) |
| Đồ án web cơ bản | [catalog/by-series/do-an-web-co-ban.md](catalog/by-series/do-an-web-co-ban.md) |
| Lập trình web chuyên sâu | [catalog/by-series/lap-trinh-web-chuyen-sau.md](catalog/by-series/lap-trinh-web-chuyen-sau.md) |
| Livecode | [catalog/by-series/livecode.md](catalog/by-series/livecode.md) |

Topic trong mỗi entry (vd `mvc`, `crud`, `php`) cũng là nguồn hashtag khi Describer cập nhật mô tả YouTube.

## Ghi chú

- Phụ đề chủ yếu là auto-caption tiếng Việt (Google ASR); một số live dài / không có track thì chỉ có stub (no-subs).
- Catalog **chỉ đọc** `transcripts/`, không ghi đè nguồn.
- Nội dung phục vụ học / tra cứu; không thay thế xem lại video gốc trên YouTube.
