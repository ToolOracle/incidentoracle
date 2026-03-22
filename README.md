# 🚨 incidentOracle

**DORA Execution MCP Server** — 12 tools | Part of [ToolOracle](https://tooloracle.io)

![Tools](https://img.shields.io/badge/MCP_Tools-12-10B898?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-00C853?style=flat-square)
![Tier](https://img.shields.io/badge/Tier-Enterprise-FF6D00?style=flat-square)
![Bus](https://img.shields.io/badge/Oracle_Bus-Connected-00C853?style=flat-square)

## Quick Connect

```bash
# Claude Desktop / Cursor / Windsurf
npx -y mcp-remote https://tooloracle.io/incident/mcp/
```

```json
// claude_desktop_config.json
{
  "mcpServers": {
    "incidentoracle": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://tooloracle.io/incident/mcp/"]
    }
  }
}
```

## Tools (12)

| Tool | Description |
|------|-------------|
| `log_incident` | Log a new ICT-related incident. First step in the DORA incident management proce |
| `classify_incident` | Classify an incident against the 6 DORA criteria (RTS 2024/1772).  |
| `major_incident_check` | Quick check: would these criteria values classify as a MAJOR incident?  |
| `initial_notification` | Generate the 4h initial notification for a MAJOR incident (ITS 2025/302 Annex I) |
| `intermediate_report` | Generate the 72h intermediate report for a MAJOR incident (ITS 2025/302).  |
| `final_report` | Generate the 1-month final report with root cause analysis and lessons learned. |
| `deadline_tracker` | Track all active MAJOR incident reporting deadlines. Shows overdue and upcoming. |
| `reclassify` | Reclassify an incident (MAJOR to NON-MAJOR or vice versa).  |
| `incident_stats` | Dashboard: total/open/major incidents, overdue deadlines, by severity/status. |
| `cyber_threat_notify` | Voluntary notification of a significant cyber threat (Art. 19(2)).  |
| `incident_log` | Full incident register with filters (status, classification, severity, search). |
| `health_check` | Server status. |

## Pricing

| Tier | Rate Limit | Price |
|------|-----------|-------|
| Free | 10 calls/day | €0 |
| Pro | 1,000 calls/day | €99/month |
| Enterprise | Unlimited | Custom |

> **Note:** This is a compliance oracle. Full tool access requires a Pro or Enterprise subscription. Free tier includes read-only assessment tools.

## Part of ToolOracle

incidentOracle is one of **42 specialized MCP servers** in the [ToolOracle](https://tooloracle.io) ecosystem — the largest collection of production-ready MCP tools for AI agents.

### DORA Coverage

**Related Oracles:**
- [FeedOracle](https://feedoracle.io) — Evidence-grade compliance data infrastructure
- [ToolOracle](https://tooloracle.io) — 42 Oracles, 390+ MCP Tools

## Links

- 🌐 Live: `https://tooloracle.io/incident/mcp/`
- 📚 Docs: [tooloracle.io/docs](https://tooloracle.io/docs)
- 🏠 Platform: [tooloracle.io](https://tooloracle.io)

---

*Built by [FeedOracle](https://feedoracle.io) — Evidence by Design*
