# Morocco Open Data MCP — Issue Tracker

This is the **issues-only** repository for the Morocco Open Data MCP Server.

No code lives here. Use this repo to report bugs, request features, and give feedback.

---

## How to Open an Issue

1. Go to the [**Issues**](../../issues) tab
2. Click **New Issue**
3. Pick the right template and fill it in

---

## Issue Templates

### Bug Report
Something is broken or returning wrong results.

Please include:
- Tool name (e.g. `search_datasets`, `file_preview`, `query_data_sql`)
- What you did — input/query you used
- What you expected vs. what happened
- Are you using the **hosted server** or **self-hosted**?
- Client: Claude Desktop / Claude Code / Cursor / VS Code / other

### Feature Request
You want a new tool, filter, or behavior improvement.

Please include:
- What you're trying to accomplish
- Which dataset or data type you're working with
- Why existing tools don't cover it

### Data Quality Issue
Data returned looks wrong, stale, or incomplete.

Please include:
- Dataset name or ID
- Resource ID (if applicable)
- What looks wrong and why

### Documentation Issue
Something in the README, config examples, or tool descriptions is missing, wrong, or confusing.

---

## Hosted Server

| | URL |
|-|-----|
| MCP endpoint | `https://mcp.morinsight.dev/mcp/` |
| Health check | `https://mcp.morinsight.dev/health` |

> Runs on Render free tier — first request after inactivity may take ~30s to wake up.
> If the health check is down for more than a few minutes, open an issue with the label `server-down`.

---

## Labels

| Label | Meaning |
|-------|---------|
| `bug` | Broken or incorrect behavior |
| `feature` | New tool or capability |
| `data-quality` | Issue with data from data.gov.ma |
| `docs` | Documentation fix or improvement |
| `server-down` | Hosted server unreachable |
| `needs-repro` | More info needed to reproduce |
| `good-first-issue` | Easy fix, good for contributors |
| `wontfix` | Out of scope or upstream limitation |

---

## Links
- [data.gov.ma](https://data.gov.ma) — Morocco's national open data portal
