# Morocco Open Data MCP — Issue Tracker

🚨 This repository is **only for issues**.

No source code is maintained here.

Use this repo to:

* Report bugs
* Request features
* Flag data quality problems
* Suggest documentation improvements

---

## Before Opening an Issue

Please check:

* Existing issues (open and closed)
* That the problem is reproducible
* That the server is up: https://mcp.morinsight.dev/health

Duplicate or incomplete issues may be closed.

---

## How to Open an Issue

1. Go to the **Issues** tab
2. Click **New Issue**
3. Select the appropriate template
4. Fill in all required details

---

## Issue Templates

### 🐞 Bug Report

Something is broken or returning incorrect results.

Please include:

* Tool name (e.g. `search_datasets`, `file_preview`, `query_data_sql`)
* What you did (input/query)
* Expected result vs actual result
* Environment:

  * Hosted server or self-hosted
  * Client (Claude Desktop / Claude Code / Cursor / VS Code / other)

---

### ✨ Feature Request

Suggest a new capability or improvement.

Please include:

* What you're trying to accomplish
* Relevant dataset or data type
* Why existing tools are insufficient

---

### 📊 Data Quality Issue

Data appears incorrect, outdated, or incomplete.

Please include:

* Dataset name or ID
* Resource ID (if applicable)
* Description of the issue

---

### 📚 Documentation Issue

Something is missing, incorrect, or unclear in the documentation.

Please include:

* What is wrong or confusing
* Suggested improvement (if possible)

---

## Hosted Server

| Service      | URL                               |
| ------------ | --------------------------------- |
| MCP endpoint | https://mcp.morinsight.dev/mcp/   |
| Health check | https://mcp.morinsight.dev/health |

⏱ Cold start: ~30 seconds after inactivity (Render free tier)

🚨 If the server appears down:

1. Check the health endpoint
2. Wait ~30 seconds (cold start)
3. If still down, open an issue with label `server-down`

---

## Labels

| Label              | Meaning                             |
| ------------------ | ----------------------------------- |
| `bug`              | Broken or incorrect behavior        |
| `feature`          | New capability or enhancement       |
| `data-quality`     | Issues with dataset content         |
| `docs`             | Documentation improvements          |
| `server-down`      | Hosted server unavailable           |
| `needs-repro`      | More information required           |
| `good-first-issue` | Beginner-friendly task              |
| `wontfix`          | Out of scope or upstream limitation |

> Labels are optional — maintainers will assign them if needed.

---

## Scope

This repository covers:

* MCP server behavior
* Tool execution and errors
* Data returned through MCP tools

This repository does **NOT** cover:

* Direct issues with data.gov.ma (unless exposed via MCP)
* General questions about open data outside this project

---

## Links

* Morocco Open Data Portal: https://data.gov.ma

---

Thanks for helping improve the Morocco Open Data MCP ecosystem 🙌
