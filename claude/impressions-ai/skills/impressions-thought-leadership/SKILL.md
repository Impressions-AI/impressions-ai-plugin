---
name: impressions-thought-leadership
description: Use when a member wants to write, tighten, or get feedback on a LinkedIn thought leadership post with Molly Godfrey's Impressions method: sharing their point of view, a pattern they see in their field, a belief to challenge, or a practical insight that builds authority. Also when they bring notes or a transcript to turn into an insight post, or ask for thought leadership hooks.
---

# Thought Leadership posts (Impressions method)

Post type slug: **`thought-leadership`**. Pass it as `type` to every tool.

Typical starting points: a point of view, a pattern they see, a belief to challenge, or a lesson from their field.

## Steps

1. **Get the coaching.** Call `get_post_type` with `{ "type": "thought-leadership" }`. Follow its "How to work with the writer" instructions for the whole conversation: how many questions to ask, how to handle messy notes (summarize, propose an outline, confirm, then rewrite), and how to keep the writer's voice.
2. **Work on the post** with the member, from their draft, notes or idea.
3. **Go deeper when it helps:** `get_post_type` with `{ "type": "thought-leadership", "section": "guide" }` (or `examples`, `deeper-look`, `template`).
4. **Hooks:** for opening lines, call `get_hooks` with `{ "type": "thought-leadership" }` and suggest hooks in the member's voice, not copies of the examples.
5. **Check it:** when a draft is done, offer the Post-Format Checklist. If they want it, call `get_checklist` with `{ "type": "thought-leadership" }` and rate each component green, blue or orange (never red), with a reason. For anything not green, suggest a fix, then offer one revision that would rate green throughout.

If the post is really a different type, say so and switch to that type's skill (see `impressions-method` for all three).

If the tools aren't available, the member needs to connect Impressions AI and sign in with the email they were invited to Notion with (codes go only to active members).
