---
name: impressions-method
description: Use when a member wants help with LinkedIn content using the Impressions method (Impressions AI), or isn't sure which kind of post to write. Covers the three post types (thought leadership, personal story, sales content), choosing between them, writing or revising a draft, finding hooks, and checking a finished post against the Post-Format Checklist. Use it whenever the member mentions Impressions or the method, or asks for a LinkedIn post and has this plugin installed.
---

# The Impressions method

Impressions AI serves the Impressions method for LinkedIn writing from the Impressions AI server. The method itself (how to coach, structures, hooks, examples, the checklist) comes from the server's tools, always current. Don't write from memory of it: call the tools.

## Post types

Always pass the **slug** as `type`.

| Post type | Slug | Use when the writer wants to… |
|---|---|---|
| Thought Leadership | `thought-leadership` | share how they see their field: a real problem, their point of view, a practical insight |
| Personal Story | `personal-story` | turn a moment from their life or work into a story that connects and links back to their audience |
| Sales Content | `sales-content` | sell without feeling salesy: a client story or point of view, objections handled, a clear invitation |

Post types can be added on the server: `list_post_types` gives the current list.

## Tools

| Tool | When |
|---|---|
| `list_post_types` | Unsure which type fits, or to show the member their options. |
| `get_post_type` with `type` | Before working on a post: how to coach the writer, and the introduction. **Follow its coaching instructions.** |
| `get_post_type` with `type` and `section` | For more depth: `guide`, `examples`, `deeper-look`, or `template`. |
| `get_hooks` with `type` | The member wants hook ideas, or the opening is weak. |
| `get_checklist` with `type` | A draft is done: offer to rate it against the Post-Format Checklist. |

## How to work

1. Pick the post type from what the member says (or ask, briefly, if it's unclear). Then use that type's skill: `impressions-thought-leadership`, `impressions-personal-story`, or `impressions-sales-content`.
2. Keep the member's own voice. Use the tools' content to coach and shape their words, not to replace them.
3. Don't paste tool output back wholesale; use it.

## If the tools aren't available

The member needs to connect the Impressions AI connector and sign in with the email on their membership. A code is emailed only to active members. Point them to the install page in this plugin's README.
