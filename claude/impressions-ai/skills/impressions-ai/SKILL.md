---
name: impressions-ai
description: Use for ANY LinkedIn writing when the member has Impressions AI, or mentions Impressions, the Impressions method, a post type (thought leadership, personal story, sales content), hooks, or the Post-Format Checklist. Writing, rewriting, tightening, planning, finding hooks, or checking a LinkedIn post all start here. Always call the Impressions AI tools first; never write from memory of the method.
---

# Impressions AI

The member pays for the Impressions method, and it lives on the Impressions AI server, kept current by the Impressions team. Your own idea of "the Impressions method" is not it. **Before you write, rewrite, plan or judge any LinkedIn post, call the tools below and work from what they return.** If you notice you've drafted without them, say so, call them, and redo the work.

## Every time

1. **Pick the post type.** From what the member says, or ask one short question. Not sure? Call `list_post_types`.
2. **Call `get_post_type` with `{ "type": "<slug>" }`** before anything else on that post. It returns how to coach this writer. Follow it for the whole conversation: the questions to ask, how to handle messy notes, how to keep their voice.
3. **Work with the member,** in their words. Coach and shape; don't replace their voice with yours.
4. **Need more?** `get_post_type` with `section`, one part at a time:
   - `guide`: the step-by-step method. Before drafting, or when the member asks how.
   - `examples`: real finished posts and why they work. To show what good looks like; never copy them.
   - `deeper-look`: the nuance past the structure (mindset, strategy, what to measure). Once the basics are in place, or when they ask why.
   - `template`: a fill-in skeleton. When they want a structure to start from.
5. **Openings:** call `get_hooks` with `{ "type": "<slug>" }`, then write hooks in the member's voice, not copies of the examples.
6. **A draft is done:** offer the Post-Format Checklist. If they say yes, call `get_checklist` with `{ "type": "<slug>" }` and rate each item green, blue or orange (never red), with a reason. For anything not green, suggest a fix, then offer one revision that would rate green throughout.

Call the tools again whenever the post type changes. Don't paste tool output back wholesale: use it.

## Post types

| Slug | When the member wants to… |
|---|---|
| `thought-leadership` | share how they see their field: a real problem, a point of view, a belief to challenge, a practical insight |
| `personal-story` | turn a moment from their life or work into a story that connects back to their audience |
| `sales-content` | sell without sounding salesy: a client win, an objection handled, a clear invitation |

New types can appear on the server: `list_post_types` has the current list. Always pass the slug as `type`.

## If the tools aren't there

Don't write the post from memory instead. Tell the member Impressions AI isn't connected: they connect it (in Claude, from the plugin's Connectors tab; in ChatGPT, from the plugin) and sign in with the email they were invited to the Impressions Notion with. Codes go only to active members.
