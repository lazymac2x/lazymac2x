# lazymac2x

> Building **lazymac** in public — 40+ developer APIs on Cloudflare Workers, two unified MCP servers, and an API marketplace strategy. From $0 MRR upward.

## 🚀 Ship list (last 2 weeks)

| Asset | What | Link |
|-------|------|------|
| **api.lazy-mac.com** | 40+ REST APIs on CF Workers, sub-200ms p95, free tier | [hub →](https://api.lazy-mac.com) |
| **@lazymac/mcp** | Unified MCP server — 42 tools (qr, ip-geo, ai-cost, llm-router, k-privacy…) | [npm](https://www.npmjs.com/package/@lazymac/mcp) · [smithery](https://smithery.ai/server/lazymac/mcp) |
| **@lazymac/k-mcp** | Korean wedge MCP — PIPA, KRW, BRN, address, NLP | [npm](https://www.npmjs.com/package/@lazymac/k-mcp) · [smithery](https://smithery.ai/server/lazymac/k-mcp) |
| **lazymac-api-healthcheck-action** | Free GitHub Action — ping any URL on a cron | [marketplace →](https://github.com/lazymac2x/lazymac-api-healthcheck-action) |
| **lazymac API Hub Pro** | $29/mo membership — unlimited API calls | [Gumroad](https://coindany.gumroad.com/l/zlewvz) |

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

K-MCP exists because most Korean public-data APIs return XML, require Korean-only docs, and don't ship MCP. K-MCP normalizes everything to English JSON for global SaaS shipping into Korea.

```bash
npx -y @lazymac/k-mcp
```

Tools: PIPA scan, KRW + BOK rates, 사업자등록번호 lookup, address geocode, morpheme/sentiment NLP, public data (weather, holidays, transport).

## 📊 Status

- CF Workers: **40 LIVE**
- npm packages: **2 LIVE**
- Smithery servers: **2 LIVE**
- RapidAPI: **20 public / 6 private**
- Apify: **22 public actors**
- Dev.to: **24+ articles**, daily pipeline
- MRR: **$0 → working on it** 🌱

## 🧭 What I'm building toward

- Distribution > product. Built breadth before depth — learned the boring way.
- One hero MCP > 36 spread. Unified server is the new bet.
- Korean wedge as a global differentiator nobody else is doing in English.

## 💖 Sponsor this work

**GitHub Sponsors is now live** → [github.com/sponsors/lazymac2x](https://github.com/sponsors/lazymac2x)

Everything I build is free-tier first. Sponsoring keeps the free tier alive and the commit streak going.

| Tier | What you get |
|------|-------------|
| **☕ $5/mo** | My gratitude + early access to new tools |
| **🔑 $15/mo** | Pro API key (1,000 req/day across all 40+ endpoints) |
| **🚀 $29/mo** | Unlimited API calls + priority issue response |

One-time sponsorship also works — no minimum. Even $1 tells me someone finds this useful.

## 💬 Find me

- Hub: [api.lazy-mac.com](https://api.lazy-mac.com)
- Pricing: [api.lazy-mac.com/pricing](https://api.lazy-mac.com/pricing)
- Sponsor: [github.com/sponsors/lazymac2x](https://github.com/sponsors/lazymac2x)
- Dev.to: [@lazymac2x](https://dev.to/lazymac2x)

> Building publicly. Open to bug reports, PRs, mean comments, and the first paying customer.
