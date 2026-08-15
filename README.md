# Bradcerb Design System

Public-site design system for Brad Erb. Agents should load this repo before producing personal branded work.

Live: https://branding.bradcerb.com

Inspired by RetroUI. Implemented in the [bradcerb/BradcerbV1](https://github.com/bradcerb/bradcerbv1) theme.

## Start here

1. `brand-kit.json` - machine-readable tokens, components, voice, and assets
2. `scss/` - Bootstrap 5 + Sass source
3. `css/brand.css` - compiled stylesheet for GitHub Pages
4. `brand-guidelines.md` - foundations and voice
5. `components.md` - primitive inventory
6. `index.html` - visual reference

## Styles

Bootstrap 5 customized with Sass. Tokens live in `scss/_variables.scss`. Brand extras (press-effect, hard shadows, wordmark) live in `scss/_brand.scss`.

```bash
npm install
npm run build:css
```

GitHub Pages serves the compiled `css/brand.css`. Rebuild it after you change Sass.

## Wordmark

Set **Brad Erb** in Archivo Black. That is the mark until more lockups land.

## Sources

- Theme: `bradcerb/BradcerbV1` (`src/css/site.css`)
- Inspiration: RetroUI
- Moodboard: [Figma](https://www.figma.com/file/d42XW4f4UDSD1EgcHxIsYf) (not the token source)
