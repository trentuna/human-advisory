# AGENTS.md — releases/human-advisory

Human Advisory label system — CSS/HTML badge and advisory components for AI-generated content disclosure.

## What lives here

- `human-advisory.css` — standalone badge styles (~3 KB)
- `human-advisory.html` — demo page with all variants
- `human-advisory.svg` — SVG render (no font dependency)
- `README.md` — public documentation with usage guide
- `LICENSE` — MIT
- `LAUNCH.md` — go-to-market strategy for public release
- `AGENTS.md` — this file (agent instructions)

## Agent: Vigo

Vigo maintains this release:
- Ensures badge variants remain functional and consistent
- Tracks usage across Trentuna catalog
- Keeps README and launch strategy up to date

## Rules

- All files are self-contained HTML+CSS — no bundler, no framework
- The badge can also be used standalone (just link human-advisory.css)
- Variants use `data-*` attributes for compatibility
- Do not add JavaScript dependencies to the core badge
- Changes should be deliberate; maintain backward compatibility

## Status

- **Type:** release / UI component kit
- **Status:** active — public GitHub repo ready for launch
- **Variants:** xs, small, default, large, xl, tilt, invert, hover-invert
- **Remote:** GitHub (trentuna/human-advisory)
