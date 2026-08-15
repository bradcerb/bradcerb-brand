# Bradcerb components

Source of truth for primitives: the `bradcerb/BradcerbV1` theme.

Public pages use this system plus Bootstrap 5. Do not import a second component library on a public page.

## Buttons

Variants: `primary` (orange, ink text), `ink` / `dark` (night, cream text), `outline`, `ghost`, `link` (orange underline).

Sizes: sm / default / lg / icon.

Display type, uppercase, 2px tracking, 2px ink border, `press-effect` on primary, ink, and outline.

## Cards

Paper, 2px ink border, hard shadow. Optional 6px top accent: orange / blue / green / yellow / ink. Interactive cards add press-effect.

## Headings + Highlight

H1-H3 are Archivo Black uppercase. H4-H6 are Space Grotesk Bold. Highlight is an inline mark: yellow (default), orange, blue, green, ink.

## Forms

Input, textarea, select, checkbox, label. Focus uses the press-effect family (translate + shadow), never a ring.

## Feedback and overlay

Badge, accordion (FAQ), dialog, sheet (slide-in), progress, stat.

## Layout

Section (full-bleed + PixelEdge). PixelEdge is the checkerboard dissolve between bands. WindowFrame is chrome for code. Marquee is CSS-only and static under reduced motion.

## Motion

Reveal is the only entrance. Variants: slideUp, slideFromLeft, slideFromRight, stampIn, wipeIn.

## Images

Treatments: duotone, halftone, glitch, flag, none. Polaroid is separate.
