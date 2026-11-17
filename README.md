# 📡 Unbiased Dev Radar · MCP Server

[![Smithery Badge](https://smithery.ai/badge/unbiased-radar-mcp)](https://smithery.ai/server/unbiased-radar-mcp)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Powered by StackVerdict](https://img.shields.io/badge/Engine-StackVerdict-blue)](https://pingguye.cn/stackverdict/)

**Penetrate vendor marketing fluff.** An official [Model Context Protocol (MCP)](https://modelcontextprotocol.io/) server providing real, unfiltered sentiment, developer gripes, and pricing cliff warnings straight into **Claude Desktop**, **Cursor**, and **Windsurf**.

---

## ⚡ 1-Minute Quickstart

### Option A: Install via Smithery (Recommended)
To automatically install for Claude Desktop:
```bash
npx -y @smithery/cli install unbiased-radar-mcp --client claude
```

### Option B: Manual Setup for Claude Desktop
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

### Option C: Manual Setup for Cursor / Windsurf
In **Cursor Settings -> Features -> MCP -> Add New MCP Server**:
* **Name**: `unbiased-radar`
* **Type**: `command`
* **Command**: `python /path/to/server.py`

---

## 🛠️ Available MCP Tools

### `get_unbiased_sentiment`
Fetch real developer discussions, pricing traps, and migration regrets from Reddit & Hacker News for any software, framework, or cloud vendor.

* **Example Query**: `"Cursor"`, `"Vercel"`, `"Supabase"`, `"Cloudflare"`, `"Next.js"`
* **Output**:
  * Unbiased developer verdict
  * Top 3 candid gripes (pricing cliffs, memory leaks, latency, support lag)
  * Top community discussion threads with scores and links
  * Migration alternatives

---

## 💰 Monetization & Pro SaaS

* 🌐 **Live Web Simulator**: [https://pingguye.cn/stackverdict/](https://pingguye.cn/stackverdict/)
* ☕ **Decision Brief (Single Export)**: $4.99
* 🚀 **StackVerdict Pro License**: $19/mo (Unlimited high-frequency queries & team decision brief exports)

---

## 📄 License
MIT © [StackVerdict](https://pingguye.cn/stackverdict/) & yepinggu66
