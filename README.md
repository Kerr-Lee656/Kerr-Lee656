# Kerr Lee

**I build [ToolScope](https://toolscope.app) — a curated directory of open-source tools.**

Most "awesome lists" are link dumps. ToolScope is the opposite: every project is
individually checked before it goes in — does it actually run, is it still
maintained, would a working developer get real value from it. About one in five
candidates gets rejected.

---

## ToolScope

| | |
|---|---|
| **Live** | [toolscope.app](https://toolscope.app) |
| **Entries** | 7,274 open-source projects and online tools |
| **Categories** | 35 |
| **Rejection rate** | 21.6% of reviewed candidates are excluded |
| **Languages** | Full Chinese / English, both UI and data |
| **Free** | Browsing, search, filtering, favourites |
| **Paid** | Written comparison reports and digests (Pro) |

Every entry carries a summarised description, use cases, and honest pros/cons.
Nothing on the site is resold, relicensed, or rehosted — every tool links back to
its own publisher.

## How the data gets in

```
Telegram channels + GitHub Search
        │
        ▼
  dedupe by repo / domain ──► already listed? stop
        │
        ▼
  LLM usefulness review ──► reject  →  archive with reason
        │                    review  →  candidate pool
        ▼
  accept + stars ≥ 100  →  bilingual enrichment  →  publish
```

Two rules I do not compromise on:

1. **Usefulness first.** A project is included because it solves a problem, not
   because it is trending.
2. **No silent imports.** AI-generated summaries are reviewed; nothing ships with
   placeholder text.

## Stack

Next.js 16 · TypeScript · SQLite · Python (ingestion, enrichment, validation)
Server-rendered, self-hosted, no tracking scripts.

## Repositories

- [`toolscope`](https://github.com/Kerr-Lee656/toolscope) — data-quality tooling
  and the editorial rules behind the directory
- [`echobird-pulse`](https://github.com/Kerr-Lee656/echobird-pulse) — Python
  pipeline for bilingual signal collection

---

<sub>Contact: [toolscope.app/contact](https://toolscope.app/contact)</sub>
