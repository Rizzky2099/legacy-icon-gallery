# Legacy 

A self-contained HTML5 icon suite about **legacy**: the values, records, stories, shared memory, and future choices that people pass on.

## Run it

Open `index.html` in a modern browser. No installation, internet connection, or external files are required.

## Requirement mapping

- **Nine unified flat-design icons:** Roots, Archive, Letters, Portraits, Songbook, Timepiece, Milestones, Community, and Future use the same rounded-card, line-weight, flat-colour system.
- **Responsive HTML5 webpage:** three columns on desktop, two on tablet, one on narrow phones.
- **Image swap:** every icon is an actual `<img>` element; its source swaps between default and active SVG artwork on hover, focus, or click.
- **Distinct audiovisual feedback:** each icon has a named, distinct Web Audio effect. Hover/focus attempts playback; a click reliably enables playback in browsers that require a user gesture.
- **Accessibility:** keyboard focus works alongside mouse hover; each icon has a descriptive ARIA label while its SVG artwork is decorative, so the assessed page remains text-free.

## Illustrator note

[`legacy-icons-source.svg`](legacy-icons-source.svg) is an editable, Illustrator-ready vector source sheet for the nine icons. The live webpage uses the same SVG vector drawings as its default and active states. The local automation environment did not expose native application control, despite Illustrator 2026 being installed.
