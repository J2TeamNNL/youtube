# youtube

Kho transcript + catalog từ kênh YouTube [J2TeamNNL Blog](https://www.youtube.com/channel/UCnL9cDH4iZcLmOIF8SzNGYw).

Mỗi live/video có thư mục transcript (phụ đề chuẩn hóa + metadata). Catalog gom theo series/chủ đề. Mô tả trên YouTube gắn mục lục timestamp và trỏ về repo này.

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
```

Chi tiết naming và `meta.kind` xem [`transcripts/README.md`](transcripts/README.md).

## Ghi chú

- Phụ đề chủ yếu là auto-caption tiếng Việt (Google ASR); một số live dài / không có track thì chỉ có stub.
- Nội dung phục vụ học / tra cứu; không thay thế xem lại video gốc trên YouTube.
