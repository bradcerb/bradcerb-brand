# RetroUI components

Source of truth for primitives: `bradcerb/bradcerbcom` → `resources/js/components/retroui/`.

Public pages use RetroUI + layout + modules only. Never import `components/ui/*` (shadcn) on a public page.

## Buttons — RetroButton

Variants: `primary` (orange, ink text), `ink` (night, cream text), `outline` (paper), `ghost`, `link` (orange underline).

Sizes: sm / default / lg / icon.

Display type, uppercase, 2px tracking, 2px ink border, `press-effect` on primary/ink/outline.

## Cards — RetroCard

Paper, 2px ink border, shadow-brutal. Optional 6px top accent: orange / blue / green / yellow / ink. `interactive` adds press-effect.

## Headings — RetroHeading + Highlight

H1-H3 are Archivo Black uppercase. H4-H6 are Space Grotesk Bold. `Highlight` is an inline mark: yellow (default), orange, blue, green, ink.

## Forms

Input, textarea, select, checkbox, label. Focus uses the press-effect family (translate + shadow), never a ring.

## Feedback and overlay

Badge, accordion (FAQ), dialog, sheet (slide-in), progress, stat (SSR final value, count-up on hydrate).

## Layout

Section (full-bleed + PixelEdge + content-visibility). PixelEdge is the checkerboard dissolve between bands. WindowFrame is retro chrome for code. Marquee is CSS-only and static under reduced motion.

## Motion

Reveal / RevealItem is the only entrance. Variants: slideUp, slideFromLeft, slideFromRight, stampIn, wipeIn. Stagger default 0.07s.

## Images

RetroImage treatments: duotone, halftone, glitch, flag, none. Polaroid is separate.
