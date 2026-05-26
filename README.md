# Human Advisory — Explicit AI Code badge

A pure-CSS replica of the classic RIAA **Parental Advisory — Explicit Content** sticker, reimagined for the AI age. Drop it on your website, repo, docs, or demo to warn humans: **explicit AI-generated code ahead**.

![screenshot](human-advisory.svg)

## Why

AI-generated code is everywhere. Most of it is invisible — no label, no disclosure, no warning. The Human Advisory badge puts that warning back. It says: *this was made by a machine, read with care*.

Inspired by the 1996 Parental Advisory label. Same proportions, same bold monochrome bands. Different warning.

## Usage

### 1. Link the CSS + font

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=League+Gothic&display=swap" rel="stylesheet">
<link rel="stylesheet" href="human-advisory.css">
```

### 2. Drop the badge

```html
<div class="human-advisory" role="img" aria-label="Human Advisory — Explicit AI Code">
  <div class="ha-top"><span>HUMAN</span></div>
  <div class="ha-mid"><span>ADVISORY</span></div>
  <div class="ha-bot"><span>EXPLICIT AI CODE</span></div>
</div>
```

That's it. No JavaScript. No build step. No framework.

### Custom text

Change the three `<span>` contents to anything you want:

```html
<div class="human-advisory" role="img" aria-label="Advisory Notice">
  <div class="ha-top"><span>WARNING</span></div>
  <div class="ha-mid"><span>HUMAN</span></div>
  <div class="ha-bot"><span>READ WITH CARE</span></div>
</div>
```

## Variants

| Attribute | Effect |
|-----------|--------|
| `data-size="xs"` | Extra small — 8rem width |
| `data-size="small"` | Small — 12rem width |
| *(default)* | Default — 20rem width |
| `data-size="large"` | Large — 28rem width |
| `data-size="xl"` | Extra large — 40rem width |
| `data-tilt="true"` | Rotated -2° with drop shadow (sticker-on-vinyl look) |
| `data-invert="true"` | Inverted colors for dark backgrounds |
| `data-hover-invert="true"` | Invert colors on hover (interactive) |

Combine attributes freely: `data-size="large" data-tilt="true"`

## Files

| File | Purpose |
|------|---------|
| `human-advisory.css` | Standalone badge styles (~3 KB) |
| `human-advisory.html` | Demo page with all variants |
| `human-advisory.svg` | SVG render (no font dependency) |

## License

MIT — free to use, modify, and distribute. Attribution welcome, not required.

If you use this badge on a public site, consider linking back to the repo so others can find it.

## Future ideas

- **Hover-invert** — interactive badge that inverts on hover (implemented, see `data-hover-invert`)
- **Animated** — subtle band animation (pulse, scroll, blink)
- **JS binding** — programmatic `setText(top, mid, bot)` helper
- **npm package** — install via `npm install human-advisory`
- **Web Component** — `<human-advisory text="AI GENERATED">` custom element
- **Dark reader** — detects `prefers-color-scheme: dark` and auto-inverts
- **Accessibility** — improved screen-reader descriptions for dynamic text

---

*Put the warning sign back on the web.* — Trentuna
