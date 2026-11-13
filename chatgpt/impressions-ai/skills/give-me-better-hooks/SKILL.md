---
name: give-me-better-hooks
description: "Impressions AI: Opening lines for your idea or draft, in each of the Impressions hook styles. Use when the member says things like: “Give me hook options for a post about [my idea]. Use the Impressions hook styles for [thought leadership / personal story / sales content].”, “Here's my opening line: \"[my first line].\" Give me five stronger versions in different styles.”"
---

# Give me better hooks

Opening lines for your idea or draft, in each of the Impressions hook styles.

## How to use it

Call the Impressions AI tool `get_skill` with `name: "give-me-better-hooks"`, and as `inputs` whatever the member has already told you. Follow what it returns for the whole conversation. Never do this skill from memory: its steps live on the Impressions AI server, kept current by the Impressions team.

If the Impressions AI tools aren't there, follow "If the tools aren't there" in the impressions-ai skill.

## Inputs

Use these exact keys inside `inputs` for `get_skill`. Fill values from the conversation; omit optional values the member has not supplied. Ask only for required information missing from the conversation.

```json
[
  {
    "name": "idea_or_draft",
    "description": "Your idea, draft or current first line",
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

- **Hooks for a new idea:** Give me hook options for a post about [my idea]. Use the Impressions hook styles for [thought leadership / personal story / sales content].
- **Fix a weak opening:** Here's my opening line: "[my first line]." Give me five stronger versions in different styles.
