---
title: "Human Advisory"
description: 'The "Parental Advisory" sticker, reissued for the AI era — a pure-CSS disclosure badge for AI-generated code'
state: release
created: 2026-05-27
---

![Human Advisory — Explicit AI Code](human-advisory.png)

# EXPLICIT AI CODE

This code was made by AI. This badge makes it visible. No hiding, no fine print, no "oops this might be AI."

Drop the sticker. Own what you built.

## One line. Done.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/trentuna/human-advisory@main/human-advisory.css">
```

```html
<div class="human-advisory" role="img" aria-label="Human Advisory — Explicit AI Code">
  <div class="ha-top"><span>HUMAN</span></div>
  <div class="ha-mid"><span>ADVISORY</span></div>
  <div class="ha-bot"><span>EXPLICIT AI CODE</span></div>
</div>
```

That's the whole install. No JavaScript. No build tools. No framework. No external font request — League Gothic is **embedded in the CSS**, so it works offline, behind firewalls, in airgapped docs, anywhere CSS works.

Prefer self-hosting? Grab `human-advisory.css` (~52KB, font included) and link it locally. Same result.

## What it is

A pure-HTML+CSS replica of the 1996 RIAA Parental Advisory label. Same proportions. Same monochrome bands. Different message: **this is AI-generated.**

```
HUMAN            ← black band, white text
ADVISORY         ← white band, black text
EXPLICIT AI CODE ← black band, white text
```

The original sticker told you a record had explicit lyrics. This one tells you a codebase has explicit AI. You see it, you read the code differently. That's the whole point.

## Say it your way

The three `<span>`s are yours:

```html
<div class="human-advisory" role="img" aria-label="Made by AI">
  <div class="ha-top"><span>MADE BY</span></div>
  <div class="ha-mid"><span>MACHINE</span></div>
  <div class="ha-bot"><span>READ WITH CARE</span></div>
</div>
```

## Variants

| Attribute | Effect |
|-----------|--------|
| `data-size="xs"` | Extra small — 8rem |
| `data-size="small"` | Small — 12rem |
| *(default)* | Medium — 20rem |
| `data-size="large"` | Large — 28rem |
| `data-size="xl"` | Extra large — 40rem |
| `data-tilt="true"` | Tilted -2°, drop shadow. Stuck-on-vinyl. |
| `data-invert="true"` | Inverted for dark backgrounds |
| `data-hover-invert="true"` | Inverts on hover. Interactive. Fun. |

Stack 'em: `data-size="large" data-tilt="true" data-hover-invert="true"`

## Files

| File | What it does |
|------|-------------|
| `human-advisory.css` | Everything. Styles + embedded font. Standalone. |
| `human-advisory.html` | Demo page, every variant. Open it, see it. |
| `human-advisory.svg` | SVG render — for READMEs and places CSS can't go. |
| `human-advisory.png` | High-res raster — social cards, slides. |

## Live

Wearing it right now, bottom-left corner: [trentuna.com](https://trentuna.com)

## Font

The badge ships **League Gothic** (OFL-1.1, open license) base64-embedded in the CSS — the wide compressed warning-label look, zero external requests. The SVG/PNG renders fall back to system fonts where needed.

## License

MIT — use, remix, share, sell, whatever. Attribution is cool, not required.

If you slap this on a public site, drop a link back so the next person can find it too.

## What's next

- Web Component: `<human-advisory text="AI GENERATED">`
- npm package: `npm install human-advisory`
- More themes (neon, terminal, glitch)

---

*Put the warning sign back on the web.* — [Trentuna](https://trentuna.com)
