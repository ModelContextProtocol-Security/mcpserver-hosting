# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

**MCP Server hosting guidance and information** — guidance for hosting and running MCP servers as infrastructure (where and how servers are deployed and hosted). It is closely related to `mcpserver-operator` (secure deployment/operation); this repo focuses specifically on the hosting angle.

## Current state

This repository is an **early-stage stub**. As of this writing it contains only a one-line `README.md` and `LICENSE` — no guidance content, code, or build system exists yet. There is no build/test/lint workflow. When adding the first real content, establish the document structure and expand this file to describe it, following the prompt-driven knowledge-system pattern used by the more mature sibling repos (see `mcpserver-audit`).

## Ecosystem context

Part of the **ModelContextProtocol-Security** organization — a family of repos covering MCP security end to end: `mcpserver-finder` (discovery), `mcpserver-audit` (auditing), `mcpserver-builder` (building), `mcpserver-operator` (operating/deploying), `mcpserver-hosting` (this repo, hosting), plus data repos (`audit-db`, `vulnerability-db`) and the `modelcontextprotocol-security.io` site. Keep terminology and guidance consistent with these siblings, especially `mcpserver-operator`.

## Contributing

`main` is protected and requires a code-owner-approved pull request. Contributions are documentation/guidance, not code.
