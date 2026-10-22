# Bowen Ventures site: brand rules

Every page and change must follow these rules.

## Colors
Defined once in `:root` at the top of `styles.css`. Never hard-code a hex value elsewhere; use the variables.

| Variable | Value | Use |
|---|---|---|
| `--accent` | `#1b2e47` | Main brand navy: buttons, headings, card and link accents |
| `--accent-dark` | `#121f31` | Hover and focus state for navy elements |
| `--accent-secondary` | `#b8995a` | Gold: thin lines and borders only (header rule, card tops) |

- Navy was sampled from `assets/logo-mark.png`. Gold matches the vertical line in `assets/logo-wide.png`.
- Do not use gold for body text or text on white. It fails contrast requirements.
- Keep the rest of the palette neutral (white, light gray, dark gray text).

## Logo files
- `assets/logo-wide.png` (800x190): horizontal logo. Use in the header on every page, wrapped in a link to the home page, with `alt="Bowen Ventures"`.
- `assets/logo-mark.png` (1000x1000): square B icon. Use as the favicon on every page: `<link rel="icon" type="image/png" href="assets/logo-mark.png">`.
- Do not recolor, stretch, crop, or recreate the logos. Scale by width only and keep the aspect ratio.

## Layout
- Mobile first. Write base styles for phones, then add `@media (min-width: ...)` rules for larger screens.
- Every page needs `<meta name="viewport" content="width=device-width, initial-scale=1">`.
- No horizontal scrolling at any width.

## Technology
- Plain HTML and CSS only. No frameworks, build tools, or CSS preprocessors.
- JavaScript only if a feature cannot work without it, and then only a small, plain script.
- One shared stylesheet: `styles.css`.

## Tone
- Professional and direct. Short sentences, concrete benefits, no hype, no slang, no filler.
- Speak to COOs and CFOs of growing companies about time and money saved.
