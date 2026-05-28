# lazymac2x

**Building production-grade AI tools at the API + MCP layer — pay-once, lifetime, MIT.**

[![Gumroad](https://img.shields.io/badge/Gumroad-coindany-pink)](https://coindany.gumroad.com) [![dev.to](https://img.shields.io/badge/dev.to-lazymac2x-black)](https://dev.to/lazymac2x) [![Cloudflare Workers](https://img.shields.io/badge/Cloudflare-Workers-orange)](https://api.lazy-mac.com) [![MCP](https://img.shields.io/badge/MCP-server-blue)](https://modelcontextprotocol.io)

I ship developer tools as Cloudflare Workers + MCP servers — drop-in for Claude Desktop, Cursor, Continue, and any MCP-compatible agent. **100+ public repos**, **200+ API endpoints**, **8 paid products** on Gumroad. One license, lifetime updates, MIT source.

---

## 🚀 Top Products

| Product | Type | Price | One-liner |
|---|---|---|---|
| [AI Citation Coverage MCP — Pro](https://coindany.gumroad.com/l/ai-citation-coverage-mcp-pro) | MCP | $19 | Claim-level RAG citation scoring — catch hallucinations pre-emit |
| [Prompt Anti-Pattern Detector — Pro](https://coindany.gumroad.com/l/prompt-anti-pattern) | MCP | $19 | 24+ prompt bloat / collision / injection-surface rules |
| [LLM Response Determinism Checker — Pro](https://coindany.gumroad.com/l/llm-response-determ) | MCP | $29 | Same prompt N times → drift score across 6 providers |
| [Prompt-Leak Detector API](https://coindany.gumroad.com/l/prompt-leak-detector) | REST + MCP | $25 | 30+ leak signatures — stop echoing your system prompt |
| [AI Output Watermark Detector](https://coindany.gumroad.com/l/ai-output-watermark) | REST + MCP | $19 | Statistical AI-text detection across OpenAI / Anthropic / Llama |
| [AI Output Schema Validator MCP](https://coindany.gumroad.com/l/ai-output-schema-va) | MCP | $5 → $19 | Catch malformed LLM JSON + auto-repair without re-prompt |
| [LLM Token Budget Forecaster](https://coindany.gumroad.com/l/llm-token-budget-fo) | MCP | $5 → $19 | Project month-end LLM bill before invoice arrives |
| [Finops Minibar](https://chromewebstore.google.com/detail/finops-minibar) | Chrome ext | $5 → $19 | Real-time spend across 7 AI providers in one toolbar |

Every license is **one-time, lifetime updates, MIT-licensed open source**.

---

## 🧰 100+ Free MCP + API Servers

**Live at**: https://api.lazy-mac.com — 200+ endpoints, free tier, no signup.

### Categories
- **AI Cost / Finops** — `ai-cost-optimizer`, `llm-cost-optimizer`, `token-budget-allocator`, `prompt-cache-maximizer`, `ai-spend-tracker`, `stream-cost-meter`
- **Prompt Engineering** — `prompt-anti-pattern-detector`, `prompt-leak-detector`, `prompt-injection-firewall`, `prompt-determinism-scorer`, `prompt-diet`
- **Security** — `mcpwatch` (OWASP MCP Top 10 scanner), `code-pattern-risk-scanner`, `vuln-scanner-worker`, `graphql-dos-shield`
- **API Tooling** — `api-cost-auditor`, `api-flow-analyzer`, `api-payload-auditor`, `api-changelog-tracker`, `webhook-reliability-suite`
- **Korea-specific** — `k-privacy-scanner`, `k-address-geocoder`, `korean-business-validator`, `korean-content-seo`, `govdata-korea`
- **Agent / Memory** — `agent-memory`, `agent-trace-auditor`, `agent-action-risk`, `agent-loop-detector`, `agent-workflow-engine`

Every server: REST + MCP (JSON-RPC 2.0), Cloudflare Workers, zero cold start, free tier.

---

## 🔧 Install Any MCP Server (One Line)

```bash
npx mcpize add lazymac/<server-name>
```

Then add to `claude_desktop_config.json` (Claude Desktop), `~/.cursor/mcp.json` (Cursor), or wherever your MCP client expects.

---

## 🛡️ MCPWatch — Security Scanner for MCP Servers

[**lazymac2x/mcpwatch**](https://github.com/lazymac2x/mcpwatch) — "Have I Been Pwned for MCP servers".

Runs the **10 OWASP MCP Top 10** checks against any public MCP server. CLI, GitHub Action, public leaderboard, hosted scanner. MIT. Pro Report $49 (in development).

```bash
npx mcpwatch-scanner /path/to/your/mcp
```

---

## 📈 Stack

**Edge**: Cloudflare Workers + Hono + D1 + R2 + Workers AI + Vectorize + Workers Analytics Engine
**Models**: Anthropic Claude Sonnet 4.6 / Opus 4.7, OpenAI, Groq, Together, Bedrock, Cloudflare Workers AI
**Distribution**: npm, mcp.so, smithery, modelcontextprotocol/registry, Gumroad, Polar
**Open source license**: MIT across all repos

---

## 📬 Contact

- **Sales / support**: [coindany.gumroad.com](https://coindany.gumroad.com)
- **Issues + roadmap**: open one on any repo, response within 24h
- **dev.to writing**: [dev.to/lazymac2x](https://dev.to/lazymac2x)

---

**One-time licenses. Lifetime updates. Open source. Ship faster.**
