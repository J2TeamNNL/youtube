# Transcripts

Raw YouTube transcripts pushed by the Transcript bot.

## Layout

```
transcripts/
  <slug>-<videoId>/
    meta.json           # id, title, url, published_at, language, kind, folder, …
    <videoId>.<lang>.vtt  # raw captions when available
    transcript.md       # normalized plain text with timestamps
```

### Folder naming

Folders use `{slug}-{videoId}`:

- **slug**: lowercase ASCII from the Vietnamese title — strip diacritics (`đ`→`d`), non-alphanumeric → `-`, collapse runs of `-`, max ~60 chars.
- **videoId**: YouTube video id.

Examples:

- `demo-phan-bien-do-an-tot-nghiep-q6bPno1-1h0`
- `tiktok-dm-helper-9OFnxGas9Fc`
- `road-to-interview-day-4-D3RdLhbceoc`

### `meta.kind`

- `video` — regular upload / short
- `live` — live stream replay (VOD)

Catalog bot reads from here; do not put synthesized topic docs in this folder.
