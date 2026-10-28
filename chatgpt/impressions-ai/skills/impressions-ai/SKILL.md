---
name: impressions-ai
description: Use for ANY LinkedIn writing when the member has Impressions AI, or mentions Impressions, the Impressions method, a post type (thought leadership, personal story, sales content), hooks, a post's opening, or the Post-Format Checklist. Writing, rewriting, tightening, planning, repurposing, finding hooks, or checking a LinkedIn post all start here. Also when the member asks what Impressions AI is or how to use it. Always call the Impressions AI tools first; never write from memory of the method.
---

# Impressions AI

The Impressions method lives on the Impressions AI server, kept current by the Impressions team. Your own idea of it is not it.

**Before you write, rewrite, plan or check any LinkedIn post, call the Impressions AI tools and follow what they return.** Start with `list_post_types` if the post type isn't clear, then `get_post_type`, and follow its coaching for the whole conversation. If you notice you've drafted without them, say so, call them, and redo the work.

## The Impressions AI skills

The other Impressions AI skills in this plugin are ready-made ways to work: find ideas, write one post type, better hooks, check a draft and more. When the member's request fits one, use it: it calls `get_skill` for its steps. When none fits, or the member asks what they can do, call `list_skills`: the server's list is current, so it can include skills newer than this plugin. Use those through `get_skill` too.

## About Impressions AI, and where to get help

If the member asks what Impressions AI is or how to use it, use the about-impressions-ai skill. Without it, call `list_post_types` and name the post types, say they can just ask for help with a post or start from one of the Impressions AI skills, and give these:
- Help center, for setup and answers: https://impressionsai.sayla.dev/help
- Slack, to ask the Impressions community or the team: https://impressions-linkedin.slack.com
- The Toolbox shows how a post, banner or photo will look before they post it. Use the preview tools here in the chat (`preview_post`, `open_preview_tool`) when they're available. Give the web version, https://impressionsai.sayla.dev/toolbox, only if the member asks for it.

## If the tools aren't there

Don't write the post from memory. Tell the member Impressions AI isn't connected: in Claude, connect it from the plugin's Connectors tab; in ChatGPT, from the plugin. They sign in with the email they were invited to the Impressions Notion with. Setup steps are at https://impressionsai.sayla.dev/welcome.
