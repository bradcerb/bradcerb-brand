# Bradcerb Brand Guidelines

Personal kit for Brad Erb.

## Who this is

Brad Erb. Public name: Bradcerb.

Published tagline: I build and teach AI work loops that turn recurring work into reliable, human-supervised systems.

One-liner: Brad Erb helps mission-minded organizations put AI and agents to work, amplifying what their teams already do well, without losing the human part.

## Lanes

- **This kit:** digital strategy, AI and agents, writing, speaking.
- **Transform:** builder proof only. Never pitch SEO from this kit.

## Voice

Warm, pastoral, direct. Coffee-shop test: would Brad say this to one person across a table?

Short declarative sentences. Specific over abstract. Honest about what AI cannot do.

Mechanics:

- Hyphens with spaces ( - ), never em dashes
- No exclamation marks on asks or CTAs
- No fabricated metrics
- No AI-transition filler

Avoid: game-changing, revolutionary, unlock your potential, synergy, cutting-edge, "in today's fast-paced world", stakeholders, leverage (as a verb), SEO expert.

## Visual system

Inspired by RetroUI. Cream paper, pure ink, hard offset shadows, no blur. Implemented in the BradcerbV1 theme. Public pages use Bootstrap 5 + Sass from this repo.

Public pages are always light mode. A `night` band is a section treatment, not a theme.

### Color

| Token | Hex | Use |
|---|---|
| cream | `#fbf7ef` | Page background |
| paper | `#ffffff` | Cards |
| ink | `#000000` | Text, borders, shadows |
| ink-muted | `#6b6b6b` | Secondary text |
| night | `#111111` | Dark bands |
| orange | `#f97316` | Primary accent and buttons |
| blue | `#2563eb` | Supporting accent |
| yellow | `#ffdb32` | Highlight boxes |
| green | `#22c55e` | Success / supporting |

### Type

- Display (H1-H3, buttons): Archivo Black, uppercase
- Heading (H4-H6, cards): Space Grotesk Bold
- Body: Inter
- Mono / labels: Space Mono

Scale (desktop): H1 72 / H2 56 / H3 40 / H4 32 / H5 24 / H6 16.

### Shadow and radius

Hard offset only. 2 / 4 / 6 / 8 px. Ink. Zero blur. Public UI is square.

### Interaction

`press-effect` is the only hover and press treatment. Focus-visible is a 2px ink outline, offset 2px. Never a ring fade.

### Motion

Entrances go through Reveal. Workhorse is slideUp. stampIn is for badges and stats. wipeIn is for images. No standalone fades.

Honor `prefers-reduced-motion` in CSS, in JS, and with an alternate render when the experience itself must change.

### Icons

`@tabler/icons-react` only. 2px stroke, round caps.

### Images

Treatments: duotone, halftone, glitch (hover, desktop only), flag, none. Polaroid is its own frame.

Kept assets:

- Portrait: `assets/personas/brad-erb/brad-erb-portrait.png`
- Avatar: `logos/avatar/brad-erb-avatar.png`
- Bust: `assets/photos/bust.png` (classical sculpture, not a person)
- Cityscape: `assets/photos/cityscape.png`

Do not use the statue crop. Do not add work-sample images to this kit.

## Logo

Wordmark is **Brad Erb** in Archivo Black, ink on cream or cream on night. Favicon and apple-touch icon live under `logos/`.
