# Sun Powder Design System

Brand + UI system for **Sun Powder — drinkable skin defense.** Dermatologist-formulated, taken orally, turns skin into hydrated UV-resistant armor. Voice: clinical, calm, empowering. Visual identity: whitepaper meets beach-sign — sober navy-on-cream typography beside loud heat-orange UV warnings.

## Structure

```
colors_and_type.css  — design tokens (CSS vars), @font-face, type scale, utility classes
SKILL.md             — agent entrypoint: read-first rules + brand voice
index.html           — design-system overview (live tour of tokens + components)
fonts/               — Söhne (body/display) + Söhne Breit + Söhne Mono
assets/
  logo/              — full lockup (navy/white/blue), wordmark, S-mark
  product/           — stick-pack photography (3 SKUs)
  icons/             — benefit icons: Regenerate, Resist, Reduce, Reverse, Restore
  bg/                — brand backgrounds (sunset grain, etc.)
preview/             — static cards shown in the design-system review pane
ui_kits/
  ecommerce/pdp.html — product detail page built on the tokens
```

## Core rules (see SKILL.md for the full list)
1. Import `colors_and_type.css` before anything else — never hardcode hex values or fonts.
2. Three heights of type: display (Söhne Breit), body (Söhne), mono (Söhne Mono).
3. Navy on cream is the default. Orange is an accent — UV warnings, CTAs, the S-mark — not a wash.
4. Benefit icons come in five named colors: Regenerate (green), Resist (blue), Reduce (red), Reverse (gold), Restore (orange).
5. Logo clear space = height of the S-mark. Min lockup width 120 px. Min icon 24 px.

## Open flags
- Benefit-icon SVGs are hand-built approximations from Figma screenshots — swap for final vector exports when available
- Product photography and logos are live from client-supplied assets
