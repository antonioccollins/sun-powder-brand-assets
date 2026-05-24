# Sun Powder Press / Featured On

Show artwork and media logos for "As Featured On" sections across Sun Powder landing pages.

## Current Assets

| File | Outlet | Type |
|------|--------|------|
| `dr-gabrielle-lyon-show.jpg` | The Dr. Gabrielle Lyon Show | Podcast cover |
| `mindbodygreen-podcast.png` | The mindbodygreen Podcast (Jason Wachob) | Podcast cover |
| `the-genius-life.jpg` | The Genius Life (Max Lugavere) | Podcast cover |
| `abc7.png` | ABC 7 | TV network logo |

## Usage

Designed for square-aspect tile grids (2×2 or 4×1). Each asset is roughly 1:1 and crops cleanly with `object-fit: cover`.

Example markup:

```html
<div class="press-grid">
  <div class="press-card"><img src="press/dr-gabrielle-lyon-show.jpg" alt="The Dr. Gabrielle Lyon Show" /></div>
  <div class="press-card"><img src="press/mindbodygreen-podcast.png" alt="The mindbodygreen Podcast" /></div>
  <div class="press-card"><img src="press/abc7.png" alt="ABC 7" /></div>
  <div class="press-card"><img src="press/the-genius-life.jpg" alt="The Genius Life with Max Lugavere" /></div>
</div>
```

## Naming Convention

```
[outlet-slug].[ext]
```

Use the outlet name as the filename, lowercase with hyphens. Add new files in this format as more press is earned.
