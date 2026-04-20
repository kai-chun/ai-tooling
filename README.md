# AI Tooling

This repository contains my practices, tooling, and experiments for building
LLM-powered systems, including prompt engineering, MCP integration,
tool usage, and evaluation workflows.

## Motivation

Instead of treating LLMs as black-box APIs, this repo focuses on:

- Designing structured prompt systems
- Building reusable tool interfaces
- Integrating external context via MCP
- Evaluating output quality systematically

---

## Architecture Overview

High-level components:

- **Prompts**: Structured templates for different tasks
- **Tools**: Function calling with schema definitions
- **Workflows**: Multi-step pipelines (RAG / agents)
- **MCP**: Context & tool integration layer
- **Evals**: Measuring output quality

See [docs/architecture.md](docs/architecture.md) for details.

---

## Setup

```bash
cp .env.example .env
pip install -r requirements.txt
```
--- 

## MCP Integration

This repo uses Model Context Protocol (MCP) to:

- Provide external tools
- Inject structured context into LLMs

More details: mcp/README.md
