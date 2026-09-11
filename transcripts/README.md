# Transcripts

Raw YouTube transcripts pushed by the Transcript bot.

## Layout

```
transcripts/
  <video-id>/
    meta.json      # id, title, url, published_at, language
    transcript.vtt # or .txt / .json depending on source
    transcript.md  # normalized plain text with optional timestamps
```

Catalog bot reads from here; do not put synthesized topic docs in this folder.
