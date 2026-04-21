# lazymac2x

> Building **lazymac** in public — 40+ developer APIs on Cloudflare Workers, two unified MCP servers, Korean data tools, and an Apify scraper suite. From $0 MRR upward.

## 🚀 Ship list

| Asset | What | Link |
|-------|------|------|
| **api.lazy-mac.com** | 40+ REST APIs on CF Workers, sub-200ms p95, free tier | [hub →](https://api.lazy-mac.com) |
| **@lazymac/mcp** | Unified MCP server — 42 tools (qr, ip-geo, ai-cost, llm-router, k-privacy…) | [npm](https://www.npmjs.com/package/@lazymac/mcp) · [smithery](https://smithery.ai/server/lazymac/mcp) |
| **@lazymac/k-mcp** | Korean wedge MCP — PIPA, KRW, BRN, address, NLP | [npm](https://www.npmjs.com/package/@lazymac/k-mcp) · [smithery](https://smithery.ai/server/lazymac/k-mcp) |
| **Korean Company Scraper** | English JSON firmographics from KRX + DART — no Korean required | [Apify →](https://apify.com/lazymac/korean-company-scraper) |
| **lazymac-api-healthcheck-action** | Free GitHub Action — ping any URL on a cron | [marketplace →](https://github.com/lazymac2x/lazymac-api-healthcheck-action) |
| **lazymac API Hub Pro** | $9/mo — unlimited API calls across all endpoints | [Gumroad](https://coindany.gumroad.com/l/zlewvz) |

## 🛠 Install the MCP

```json
{
  "mcpServers": {
    "lazymac": {
      "command": "npx",
      "args": ["-y", "@lazymac/mcp"]
    }
  }
}
```

Drops 42 tools into Claude Code, Cursor, Windsurf in one block. Free 100 req/day per IP.

## 🇰🇷 Korean wedge

Korean public data is the moat. Most Korean APIs return XML, require Korean-only docs, and don't ship MCP or REST. I normalize everything to English JSON for global teams expanding into Korea.

**K-MCP** — drop into any MCP client:
```bash
npx -y @lazymac/k-mcp
```
Tools: PIPA compliance scan, KRW + BOK rates, BRN (사업자등록번호) lookup, address geocode, morpheme/sentiment NLP, public data (weather, holidays, transport).

**Korean Company Scraper** — pull KRX + DART firmographics at $0.10/company:
```python
from apify_client import ApifyClient
client = ApifyClient("YOUR_TOKEN")
run = client.actor("lazymac/korean-company-scraper").call(run_input={
    "companyNames": ["Samsung Electronics", "Kakao", "NAVER"],
    "includeFinancials": True
})
```

No Korean language required. Returns `name_en`, `stock_code`, `industry`, `established`, `dart_corp_code`.

## 📊 Status

- CF Workers: **40 LIVE**
- npm packages: **2 LIVE** (@lazymac/mcp · @lazymac/k-mcp)
- Smithery servers: **2 LIVE**
- RapidAPI: **20 public**
- Apify actors: **23 public** (incl. Korean Company Scraper)
- Dev.to: **24+ articles**, daily pipeline
- MRR: **$0 → first revenue push active** 🌱

## 🧭 Strategy

- **Korean data as a global wedge** — nobody else ships Korean gov/exchange data as clean English JSON APIs + MCP
- **Distribution > product** — Apify PPE + GitHub Sponsors + Gumroad running in parallel
- **24/7 autonomous** — Mac Mini runs all bots, pipelines, and content generation while I sleep

## 💖 Sponsor

**[github.com/sponsors/lazymac2x](https://github.com/sponsors/lazymac2x)** ← GitHub Sponsors is live

Everything I build ships with a free tier. Sponsoring keeps free tier alive and gets you API access.

| Tier | Price | What you get |
|------|-------|-------------|
| **Supporter** | $5/mo | Gratitude + early access to new tools |
| **Developer** | $15/mo | Pro API key — 1,000 req/day across all 40+ endpoints |
| **Builder** | $29/mo | Unlimited API calls + priority support + Korean data tools |

One-time sponsorship works too. Even $1 tells me someone finds this useful.

## 💬 Find me

- Hub: [api.lazy-mac.com](https://api.lazy-mac.com)
- Pricing: [api.lazy-mac.com/pricing](https://api.lazy-mac.com/pricing)
- Sponsor: [github.com/sponsors/lazymac2x](https://github.com/sponsors/lazymac2x)
- Apify: [apify.com/lazymac](https://apify.com/lazymac)
- Dev.to: [@lazymac2x](https://dev.to/lazymac2x)

> Building publicly. Open to bug reports, PRs, mean comments, and the first paying customer.
