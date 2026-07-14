# Activation Nation — Marketing Skills Bundle

A curated set of Claude **Agent Skills** for marketing planning, research, content,
art direction, conceptualization, and brand framework work. Stored here as plain,
version-controlled files so they can be installed into any Claude surface.

## What's included

### Creative concepting & art direction
| Skill | What it does | Source |
|---|---|---|
| `creative-direction` | Naming, branding, concept development, tone of voice. Runs DIVERGE → CONNECT → CONVERGE → CHALLENGE. Calls the `creative-director` agent for deep work. | jbo-tech/claude-setup |
| `frontend-design` | Pushes bold, distinctive visual/web directions before executing. | Anthropic (official) |

### Strategic brand framework & visuals
| Skill | What it does | Source |
|---|---|---|
| `brand-guidelines` | Applies a defined color system + typography to any artifact (decks, docs, HTML). | Anthropic (official) |
| `canvas-design` | Composes visuals on a 2D canvas (layers, type, spacing) for social/marketing graphics. Includes bundled fonts. | Anthropic (official) |

### Planning, research & content
| Skill | What it does | Source |
|---|---|---|
| `marketing-plan` | Exhaustive 12-month AARRR marketing plan, fCMO-level. | coreyhaines31/marketingskills (MIT) |
| `customer-research` | ICP research, interviews, VOC, personas, JTBD, review mining. | coreyhaines31/marketingskills (MIT) |
| `content-strategy` | Topic clusters, content pillars, editorial calendar. | coreyhaines31/marketingskills (MIT) |
| `marketing-ideas` | 139-idea library for ideation when stuck. | coreyhaines31/marketingskills (MIT) |
| `competitor-profiling` | Structured competitor dossiers from URLs. | coreyhaines31/marketingskills (MIT) |

### Client servicing
| Skill | What it does | Source |
|---|---|---|
| `contact-report` | Turns a meeting transcript/recording into a client-ready agency contact report (attendees, decisions, action items w/ owners + deadlines) and drafts a Gmail recap to attendees. | Activation Nation |

### Immersive web / campaign microsites
| Skill | What it does | Source |
|---|---|---|
| `scroll-world` | Turns a brand/industry into a scroll-scrubbed "fly through the world" landing page — continuous camera flight through AI-generated isometric diorama scenes (Apple-style scroll pages). Powered by Higgsfield; ships a portable vanilla-JS scrub engine. | oso95/scroll-world (MIT) |

### Supporting agent
- `agents/creative-director.md` — provocateur creative-director persona used by `creative-direction`.

## How to install / use

These are stored as plain files (NOT in a `.claude/` config dir) so nothing
auto-executes from this repo. To activate them in a Claude environment:

- **Claude Code (local or web):** copy the skill folders into `.claude/skills/`
  in your project (and `agents/creative-director.md` into `.claude/agents/`),
  or into `~/.claude/skills/` to make them global.
- **Claude Desktop / Cowork:** add them via your Skills/Capabilities settings.

Each skill is a folder with a `SKILL.md` (YAML frontmatter + instructions);
several include a `references/` folder used at runtime.

## Licensing / attribution
- Anthropic skills: see each folder's `LICENSE.txt`.
- coreyhaines31/marketingskills: MIT License (Copyright (c) 2025 Corey Haines).
- jbo-tech/claude-setup: see source repository.

Skills were vendored from their public repositories; `evals/` test fixtures were
omitted to keep the bundle lean.
