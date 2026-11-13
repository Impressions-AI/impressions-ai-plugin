---
name: reuse-a-post
description: "Impressions AI: Give a post you've already written a second life as a different post type. Use when the member says things like: “Here's a personal story post I wrote: [paste post]. Turn it into a sales content post about [my offer].”, “Here's a sales post about a client result: [paste post]. Turn the lesson in it into a thought leadership post.”"
---

# Reuse a post

Give a post you've already written a second life as a different post type.

## How to use it

Call the Impressions AI tool `get_skill` with `name: "reuse-a-post"`, and as `inputs` whatever the member has already told you. Follow what it returns for the whole conversation. Never do this skill from memory: its steps live on the Impressions AI server, kept current by the Impressions team.

If the Impressions AI tools aren't there, follow "If the tools aren't there" in the impressions-ai skill.

## Inputs

Use these exact keys inside `inputs` for `get_skill`. Fill values from the conversation; omit optional values the member has not supplied. Ask only for required information missing from the conversation.

```json
[
  {
    "name": "post",
    "description": "The post you've written",
    "required": true
  },
  {
    "name": "to_type",
    "description": "The post type to turn it into",
    "required": true
  }
]
```

## How members ask for it

- **Story to sales:** Here's a personal story post I wrote: [paste post]. Turn it into a sales content post about [my offer].
- **Result to insight:** Here's a sales post about a client result: [paste post]. Turn the lesson in it into a thought leadership post.
