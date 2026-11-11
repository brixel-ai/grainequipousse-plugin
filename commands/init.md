---
description: Set up your graine qui pousse account step by step: your brand's dossier written from your website, your logo, your social accounts, your first post.
argument-hint: your brand's website (or its name and city), if you want to give it now
---

Set up my graine qui pousse account with me: $ARGUMENTS

1. Call `init`: it reads where my account stands (plan, dossier, logo, social accounts, posts)
   and gives the next step with the call that does it.
2. Take me through its steps one at a time, starting with my brand's dossier
   (`read_skill("building-a-dossier")`, then `create_dossier`). Ask me only what you cannot find
   yourself, in one short message, and never invent a fact about my brand.
3. After each step, call `init` again: it reads the account anew and gives the next. A step only
   I can do (connecting my social accounts, changing plan) comes with its link: give it to me
   and go on meanwhile.
4. Stop when it says the setup is done — or when I say so. Publish or schedule nothing unless I
   ask.

No `init` tool in your list? graine's connector is not connected yet: tell me to connect it
(`/mcp` in Claude Code, then « graine qui pousse » → Authenticate) — creating my account is part
of that page.
