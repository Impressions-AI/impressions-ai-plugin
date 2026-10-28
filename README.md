# Impressions AI

The Impressions method for LinkedIn posts (thought leadership, personal stories, sales content) in Claude and ChatGPT. For Impressions members: sign in with the email you were invited to Notion with.

This repository is a plugin marketplace for **Claude** and **ChatGPT**, built from a private source. It holds only what each app installs: a manifest, the Impressions AI connector, and one short skill that tells your AI to use it. The Impressions method itself is served by Impressions AI to signed-in members.

| Folder | For |
|---|---|
| `claude/impressions-ai` | Claude (claude.ai, the desktop app, Claude Code), listed in `.claude-plugin/marketplace.json` |
| `chatgpt/impressions-ai` | ChatGPT and Codex, listed in `.agents/plugins/marketplace.json` |

## Install

Members: sign in at **https://impressionsai.sayla.dev/welcome** for step-by-step setup with screenshots.

- **Claude** (claude.ai or the desktop app): Customize → Plugins → Add → Add marketplace → Add from a repository, enter `Impressions-AI/impressions-ai-plugin`, then install **Impressions AI** and connect it from its Connectors tab.
- **Claude Code:** `/plugin marketplace add Impressions-AI/impressions-ai-plugin`, then `/plugin install impressions-ai@impressions-ai`, then `/mcp` to connect.
- **ChatGPT desktop app:** Settings → Plugins → Add plugin marketplace, Source `Impressions-AI/impressions-ai-plugin`, Git ref `main`, then install **Impressions AI** and connect when asked.
- **Codex:** `codex plugin marketplace add Impressions-AI/impressions-ai-plugin`, then `codex plugin add impressions-ai@impressions-ai`.

Connecting asks you to sign in with the email on your Impressions membership. A code is emailed to active members only.

## Updating

- **Claude:** keep the marketplace's auto-update on and new versions arrive by themselves.
- **ChatGPT desktop app:** Settings → Plugins → Marketplace, then **Upgrade** beside Impressions AI.

Version 0.4.0.
