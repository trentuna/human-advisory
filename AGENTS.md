# AGENTS.md — releases/human-advisory

Human Advisory badge — CSS/HTML sticker for AI-generated code, inspired by the RIAA Parental Advisory label.

## What lives here

- `human-advisory.css` — standalone badge styles (~3 KB)
- `human-advisory.html` — demo page with all variants
- `human-advisory.svg` — SVG render (no font dependency)
- `README.md` — public documentation
- `LICENSE` — MIT
- `LAUNCH.md` — go-to-market strategy
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

- **Type:** release / UI component
- **Status:** ready to push — all final edits applied, commit c3a8952 pending
- **Variants:** xs, small, default, large, xl, tilt, invert, hover-invert
- **Remote:** pending — needs trentuna org access. Create `trentuna/human-advisory` on GitHub and Vigo pushes.
- **GH token (vigilio-desto):** not a member of trentuna org
- **Last:** hover border stays black, font note added, README explains SVG fallback
