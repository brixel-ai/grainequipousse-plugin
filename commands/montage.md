---
description: Edit a film from your brand's own videos — a talk, a podcast, a few rushes — with graine qui pousse, keeping their sound and words.
argument-hint: what the film should say, and which videos to use
---

Make a montage with graine qui pousse from my brand's own videos: $ARGUMENTS

1. `read_skill("making-a-post")`, then `get_brand_context`.
2. `list_videos`, and agree with me on the videos to use — their order gives their letters
   (A, B, C…).
3. `create_post(media="montage", files=[…])` with only what I said: graine asks me the rest of
   its brief.
4. `read_skill("editing-a-montage", post_id=…)` and follow it to the end: watch the videos, show
   me their segments (`show_sources`), write the paper edit, cut its passages, design, score,
   render.
5. Check the rendered file itself (`preview_film(source="render")`, `check_sound(of="render",
   hear=true)`), then show me the post. Publish or schedule nothing unless I ask.
