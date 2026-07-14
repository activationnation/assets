---
tags: [claude-skill, creative, web, 3d]
category: Creative & Web
status: installed
installed: 2026-06-13
source: https://github.com/oso95/scroll-world
license: MIT
requires: [Higgsfield, ffmpeg, python3-pillow]
---

# scroll-world

Build an immersive scroll-scrubbed **"fly through the world"** landing page for any
brand or industry. As the visitor scrolls, a pre-rendered camera flies from outside
each scene into its interior, then flows to the next scene with no cuts — one
continuous connected flight (Emons-style isometric diorama, or any art direction).

## When to use
- A "3D world" / "browse-through-the-industry" hero
- A scroll cinematic or diorama landing page
- A premium hero, campaign microsite, or product-launch page where an immersive
  scroll experience would elevate the design
- Turning a business into a scrollable world

## How it works
Interviews for topic, story beats, and brand kit → generates cohesive scenes
(GPT Image) + seamless camera clips (Seedance i2v) via **Higgsfield** → wires a
portable, framework-agnostic vanilla-JS scroll-scrub engine (plain HTML, Next.js, Vue).

## ⚠️ Notes
- Consumes **Higgsfield credits** (image + video generation) — confirm before running.
- Author flags it as experimental / AI-generated. Do a small test pass first.
- Needs `ffmpeg`/`ffprobe`; `python3` + Pillow optional (transparent-scene knockout).

## Related
- [[3d-web-experience]] · [[frontend-design]] · [[creative-direction]]

## Install locations
- Mac: `~/.claude/skills/scroll-world/`
- Repo (source of truth): `activationnation/assets` → `/skills/scroll-world` + `.claude/skills/scroll-world`
