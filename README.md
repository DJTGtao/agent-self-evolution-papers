# agent-self-evolution-papers

Personal paper shelf for [Anthology](https://github.com/DJTGtao/anthology) — OCR’d Markdown for mobile reading, originals optional.

## Layout

```
papers/
  {slug}/
    meta.json      # title, authors, arxiv id, content hash
    content.md     # what the phone reads
    original.pdf   # optional source PDF
    assets/        # optional figures from OCR
```

## Phone (Anthology)

**Settings → GitHub papers**

| Field | Value |
|-------|--------|
| Owner | `DJTGtao` |
| Repo | `agent-self-evolution-papers` |
| Branch | `main` |
| Papers folder | `papers` |
| Token | GitHub PAT with `contents` read/write on this repo |

Then **Add → Papers**, paste arXiv abs URLs (one per line). Enable **Auto-push after import** to upload OCR results here.

## Desktop

```bash
git clone https://github.com/DJTGtao/agent-self-evolution-papers.git
# drop PDFs / edit content.md, then git push
```
