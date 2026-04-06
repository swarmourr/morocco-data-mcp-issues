name: "🐞 Bug Report"
description: Report something that is broken or incorrect
title: "[Bug]: "
labels: ["bug"]
body:

* type: markdown
  attributes:
  value: |
  Thanks for reporting a bug 🙌
  Please fill out the details below to help us reproduce and fix the issue.

* type: input
  id: tool
  attributes:
  label: Tool Name
  description: Which MCP tool were you using?
  placeholder: e.g. search_datasets, file_preview, query_data_sql
  validations:
  required: true

* type: textarea
  id: steps
  attributes:
  label: What did you do?
  description: Describe the exact steps or input/query used
  placeholder: |
  1. Called tool with...
  2. Used query...
  3. Got response...
  validations:
  required: true

* type: textarea
  id: expected
  attributes:
  label: Expected Behavior
  description: What should have happened?
  validations:
  required: true

* type: textarea
  id: actual
  attributes:
  label: Actual Behavior
  description: What actually happened?
  validations:
  required: true

* type: dropdown
  id: environment
  attributes:
  label: Environment
  description: Where are you running MCP?
  options:
  - Hosted server (mcp.morinsight.dev)
  - Self-hosted
  validations:
  required: true

* type: dropdown
  id: client
  attributes:
  label: Client
  description: Which client are you using?
  options:
  - Claude Desktop
  - Claude Code
  - Cursor
  - VS Code
  - Other
  validations:
  required: true

* type: textarea
  id: logs
  attributes:
  label: Logs / Error Messages
  description: Paste any relevant logs or error messages
  placeholder: Paste here...
  validations:
  required: false

* type: textarea
  id: additional
  attributes:
  label: Additional Context
  description: Any other details that might help
  validations:
  required: false
