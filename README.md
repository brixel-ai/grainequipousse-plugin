# graine qui pousse

[graine qui pousse](https://grainequipousse.com) is a social-media studio for freelancers, small
business owners, tradespeople and shop owners who run their own social media. This plugin
connects your assistant to it: the graine qui pousse connector (MCP) and its skills — how to make
a post, search the brand's library, direct a video, design an image or a film, score it (music,
voice, subtitles), edit a montage from your own videos, write the caption, and publish. Each
skill's text is served by graine qui pousse itself, so it always matches the tools of the day.

Your assistant works inside your brand's dossier — its tone of voice, personas, brand kit (logo,
palette, fonts) and media library. graine qui pousse checks every image and video, shows preview
frames, renders the final files and publishes them on Instagram, LinkedIn, Facebook, TikTok,
YouTube, Threads and X — only when you ask.

## Install

**Claude Code**

```
/plugin marketplace add brixel-ai/grainequipousse-plugin
/plugin install graine-qui-pousse@graine-qui-pousse
```

On first use, sign in to your graine qui pousse account when the connector asks (`/mcp`). Then:

- `/graine-qui-pousse:post a 20-second LinkedIn video about our new offer`
- `/graine-qui-pousse:montage a 45-second reel from my last talk`

or just ask for a post, a carousel or a video: the skills load when the request calls for them.

**Claude (web, desktop, Cowork)** — install the plugin from the Claude directory, or have your
organization's owner add this repository to its plugin marketplace. The connector appears on the
plugin's Connectors tab: connect your graine qui pousse account there. Skills need code execution
enabled.

**ChatGPT, Codex, VS Code, Cursor** — this repository is also an Agent Plugin
([agent-plugins.org](https://agent-plugins.org)): `plugin.json`, `mcp.json` and `skills/`.

## What you need

A graine qui pousse account with at least one brand. The social accounts you publish to are
connected in the app. When you connect your assistant, you choose which brands it may use and
whether it may publish or edit them; you can remove this access at any time in the app.

Images and videos are designed from your brand kit and library and rendered by graine qui pousse:
this plugin does not generate photos, video footage or voices with generative AI; the montage
effects you allow redraw frames of your own videos and photos.

## Links

- Documentation: https://grainequipousse.com/mcp-connector
- Help: https://grainequipousse.com/mcp-connector#help
- Privacy: https://grainequipousse.com/privacy
- Terms: https://grainequipousse.com/terms
- License: MIT (`LICENSE`)
