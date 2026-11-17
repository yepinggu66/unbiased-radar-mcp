# 📡 Unbiased Dev Radar · MCP Server (v1.1.0)

[![GitHub Release](https://img.shields.io/github/v/release/yepinggu66/unbiased-radar-mcp)](https://github.com/yepinggu66/unbiased-radar-mcp/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Powered by StackVerdict](https://img.shields.io/badge/Engine-StackVerdict-blue)](https://pingguye.cn/stackverdict/)

**Penetrate vendor marketing fluff & cloud billing traps.** An official [Model Context Protocol (MCP)](https://modelcontextprotocol.io/) server providing real, unfiltered developer sentiment, pricing cliff warnings, and true Total Cost of Ownership (TCO) calculations straight into **Claude Desktop**, **Cursor**, and **Windsurf**.

---

## ⚡ 1-Minute Quickstart

### Claude Desktop Configuration
Add the following to your `claude_desktop_config.json`:
```json
{
  "mcpServers": {
    "unbiased-radar": {
      "command": "python",
      "args": ["server.py"]
    }
  }
}
```

### Cursor / Windsurf Configuration
In **Cursor Settings -> Features -> MCP -> Add New MCP Server**:
* **Name**: `unbiased-radar`
* **Type**: `command`
* **Command**: `python /path/to/server.py`

---

## 🛠️ Available MCP Tools

### 1. `get_unbiased_sentiment`
Fetch real developer discussions, pricing traps, and migration regrets from Reddit & Hacker News for any software, framework, or cloud vendor.

* **Example Query**: `"Cursor"`, `"Vercel"`, `"Supabase"`, `"Cloudflare"`, `"Next.js"`
* **Output**:
  * Unbiased developer verdict
  * Top 3 candid gripes (pricing cliffs, memory leaks, latency, support lag)
  * Top community discussion threads with scores and links
  * Migration alternatives

### 2. `calculate_cloud_tco` ⭐ NEW
Calculate true monthly Total Cost of Ownership (TCO), billing cliffs, and egress fee penalties comparing cloud vendors (e.g. `Vercel vs Cloudflare`, `Supabase vs Firebase`, `AWS`).

* **Example Arguments**:
  ```json
  {
    "vendor_a": "vercel",
    "vendor_b": "cloudflare",
    "team_size": 5,
    "traffic_tier": "growth"
  }
  ```
* **Output**:
  * Head-to-head monthly cost projection
  * Egress tax warnings & seat cliff triggers
  * Tailored 1-page executive Decision Brief link

---

## 💰 Monetization & Pro SaaS

* 🌐 **Live Web Simulator**: [https://pingguye.cn/stackverdict/](https://pingguye.cn/stackverdict/)
* ☕ **Decision Brief (Single Export)**: $4.99
* 🚀 **StackVerdict Pro License**: $19/mo (Unlimited high-frequency queries & team decision brief exports)

---

## 📄 License
MIT © [StackVerdict](https://pingguye.cn/stackverdict/) & yepinggu66
