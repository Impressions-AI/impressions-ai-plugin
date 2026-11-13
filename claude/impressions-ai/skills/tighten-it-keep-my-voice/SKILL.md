---
name: tighten-it-keep-my-voice
description: "Impressions AI: A cleaner, easier-to-read version of your draft that still sounds like you. Use when the member says things like: “Here's my draft: [paste draft]. Tighten it with the Impressions method, but keep my voice and my words where you can.”, “Here's my draft: [paste draft]. Make it easier to read on LinkedIn: shorter paragraphs, cleaner spacing, one clear idea.”"
---

# Tighten it, keep my voice

A cleaner, easier-to-read version of your draft that still sounds like you.

## How to use it

Call the Impressions AI tool `get_skill` with `name: "tighten-it-keep-my-voice"`, and as `inputs` whatever the member has already told you. Follow what it returns for the whole conversation. Never do this skill from memory: its steps live on the Impressions AI server, kept current by the Impressions team.

If the Impressions AI tools aren't there, follow "If the tools aren't there" in the impressions-ai skill.

## Inputs

Use these exact keys inside `inputs` for `get_skill`. Fill values from the conversation; omit optional values the member has not supplied. Ask only for required information missing from the conversation.

```json
[
  {
    "name": "draft",
    "description": "Your draft",
    "required": true
  },
  {
    "name": "type",
    "description": "The post type",
    "required": false
  }
]
```

## How members ask for it

- **Make it clearer:** Here's my draft: [paste draft]. Tighten it with the Impressions method, but keep my voice and my words where you can.
- **Make it easier to read:** Here's my draft: [paste draft]. Make it easier to read on LinkedIn: shorter paragraphs, cleaner spacing, one clear idea.
