# Claude Skills

Custom Claude Code skills (slash commands) for use with [Claude Code](https://claude.ai/code).

## Installation

Copy any `.md` file from this repo into `~/.claude/commands/` to make it available as a `/skill-name` command in Claude Code.

## Skills

| Skill | Description |
|-------|-------------|
| `brand-guidelines` | Apply Bevy's official brand voice, tone, colors, and style to any content artifact |
| `canvas-design` | Create beautiful visual art in .png and .pdf documents using design philosophy |
| `frontend-design` | Create distinctive, production-grade frontend interfaces with high design quality |
| `mcp-builder` | Guide for creating high-quality MCP servers in Python or TypeScript |
| `pptx` | Create, edit, read, or work with .pptx slide decks and presentations |
| `webapp-testing` | Test local web applications using Playwright — screenshots, logs, UI verification |

## Usage

In Claude Code, invoke a skill with:
```
/frontend-design build me a landing page for a SaaS product
/pptx create a pitch deck for my startup
/canvas-design make a poster inspired by brutalist architecture
/mcp-builder build an MCP server for the GitHub API
/webapp-testing check that the login flow works on localhost:3000
/brand-guidelines review this blog post for Bevy brand compliance
```
