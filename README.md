# Bradcerb Brand

This repository is the single source of truth for Brad Erb / Bradcerb brand assets and guidelines. Agents and automation should load it before producing branded work.

Live site: https://branding.bradcerb.com

## Repository Structure

| Path | Description |
|---|---|
| `brand-kit.json` | Machine-readable brand data: colors, typography, voice, socials |
| `brand-guidelines.md` | Human and agent-readable guidelines |
| `index.html` | Visual reference page |
| `logos/` | Logo lockups (add SVG/PNG here) |
| `fonts/` | Self-hosted font files when needed |
| `assets/` | Portraits and other brand images |
| `guidelines/` | Longer brand documents |
| `samples/` | Usage examples |

## How agents should use this

1. Read `brand-kit.json` first.
2. Follow `brand-guidelines.md` for tone and usage.
3. Do not invent colors, type, or voice that contradict the kit.
4. Positions in this kit are published site copy, not new claims.

## Status

Scaffold created from the personal site tokens in `bradcerb/bradcerbv1`. Drop logo files into `logos/` and fill any empty voice fields.
