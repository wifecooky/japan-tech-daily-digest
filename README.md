# Japan Tech Daily Digest

Automated, trilingual daily digest for the Japanese tech ecosystem.

Collects articles from 13 sources — Hatena Bookmark, Zenn, Qiita, PublicKey, Japanese tech company blogs, and Hacker News — then uses AI to score, filter, and translate into English, Chinese, and Japanese.

Built with [digest-factory](https://github.com/wifecooky/digest-factory).

## Sources

| Category | Sources |
|----------|---------|
| Community | はてブ Tech, Zenn, Qiita Popular |
| Media | PublicKey |
| Company Blogs | Yahoo Japan Tech, Mercari Engineering, Cookpad Tech, CyberAgent Developers, Retty Tech |
| News | Google News Japan Tech (ja/en/zh), Hacker News |

## Quick Start

```bash
npm install
cd frontend && npm install && cd ..
export OPENAI_API_KEY=sk-...
npm run generate-daily
cd frontend && npm run build && npm run preview
```

## Pipeline

| Command | Description |
|---------|-------------|
| `npm run collect` | Fetch articles from all sources |
| `npm run filter` | AI editorial selection (Japan tech-focused) |
| `npm run translate` | Translate to en/zh/ja |
| `npm run generate-daily` | Full pipeline |
| `npm run newsletter` | Send via Buttondown |

## Contact

[@wifecooky](https://x.com/wifecooky)
