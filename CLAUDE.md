# CLAUDE.md

Guidance for Claude Code when working in this repository.

## What this is

A local clone of NetworkChuck's Docker MCP tutorial repo — reference material and examples for
building MCP (Model Context Protocol) servers with Docker, not an original project. See
`README.md` for the full tutorial content and video link.

This is **not** part of the `home/Homelab-Stuff/` service fleet — it's a standalone learning
reference under `Docker-Stuff/local/`, unrelated to any deployed homelab service.

## Layout

- `docs/` — installation, Docker Gateway, custom servers, troubleshooting guides
- `quick-start/setup-guide.md` — 5-minute getting-started walkthrough
- `examples/dice-roller/` — a minimal working MCP server example
- `mcp-builder-prompt/` — prompt material for scaffolding new MCP servers
- `resources/` — supporting reference material

## Working in this repo

Treat this as reference/tutorial content to read from, not a project to actively develop —
if extending it with new examples, follow the existing `examples/<name>/` structure.
