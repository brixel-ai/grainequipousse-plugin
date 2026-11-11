---
description: Make a social-media post for your brand with graine qui pousse: an image, a carousel, a video or a reel.
argument-hint: what the post is about (and where it goes, if you know)
---

Make a post with graine qui pousse: $ARGUMENTS

1. `read_skill("making-a-post")`, then `get_brand_context` (it lists my brands when there are
   several: ask me which one). If I said nothing about the post above, ask me what it is about,
   in one message.
2. `create_post` with ONLY what I said: graine asks me the rest of its brief.
3. Follow the procedure each answer ends with, step by step, up to the caption — reading each
   step's skill with the post's `post_id`.
4. A video: once rendered, check the rendered file itself — `preview_film(post_id,
   source="render")` and `check_sound(post_id, of="render", hear=true)`.
5. Show me the post (`show_post`). Publish or schedule nothing unless I ask.
