---
name: directing-a-story
description: Directs a graine qui pousse Instagram story (1 to 7 segments of 9:16, each an image or a video, no caption) before its segments are made — the argument, each segment's role and exact words, the motif riding them all and the reason to tap forward, as a JSON storyline (`write_storyboard(storyline=…)`); then makes each segment in its order, by its `index`. Use it for a story (`post_type="story"`), after its brief.
---

# Directing a story — the storyline

This skill lives on graine qui pousse's server, always in step with its tools: call `read_skill("directing-a-story")` and follow what it says — with `post_id="…"` whenever you work on a post: the answer then opens with THAT post's frame in px, brief, design level, clock and the worked examples that fit. Its other files (references, worked examples) come the same way, `read_skill("directing-a-story", file="…")`, as the skill names them. A text sent in parts says on its first line how to read the next: keep the same arguments.

No `read_skill` tool in your list? graine's connector is not connected: ask the user to connect it (`/mcp` in Claude Code, the plugin's Connectors tab in Claude).
