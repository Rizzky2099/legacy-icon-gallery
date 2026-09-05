# Legacy Loom — Assignment Documentation

## Concept

**Legacy**. The suite reimagines legacy through an ancient Greek bronze aesthetic: guardianship, ancestral knowledge, olive branches, vessels, music, time, courage, bravery, and heroic stories.

## Intended audience

Young adults cataloguing or reconnecting with their family histories, particularly people who have inherited a small collection of physical and digital keepsakes but do not yet have a shared visual language for their meaning.

## Context and platform

The icon suite is designed for a responsive web-based family archive or oral-history platform. It works as a quiet discovery layer: a visitor hovers over a symbol to reveal its active state and hear a small sound connected to the associated type of memory. The page adapts from a three-column desktop grid to a two-column tablet grid and a one-column phone grid.

## Visual system

- A shared 300 × 300 icon canvas, rounded bronze tile, Greek-key corner frame, generous negative space, rounded linework, and small upper-right dot unify all nine designs.
- A warm stone background and a deliberately narrow family of bronze, terracotta, ochre, and olive tones evoke aged metal and ceramics without losing cohesion.
- Icons are intentionally text-free on the webpage, satisfying the assignment parameter. Meaning is expressed through universally recognisable silhouettes and retained in accessible ARIA labels only.

## Interaction and feedback

Each item uses an actual image-source swap from its default SVG to an active SVG, adding a bronze colour field and darkened linework. Each plays a distinct synthesized Web Audio sound that relates to the icon: shield knock, papyrus unfurl, olive-leaf rustle, clay-vessel tap, lyre chord, sunlit chime, spear strike, lion roar, and bronze helmet ring.

As an ambient layer, a fine pigment-colour cursor trail follows the visitor’s movement and fades away after 2.5 seconds. An active icon also releases a short, soft burst of its own colour. Both effects respect a visitor’s reduced-motion preference.

## Design rationale

The interaction does not hide the basic icon; instead, it intensifies it. This makes feedback immediate, restrained, and meaningful—appropriate for intimate material such as family memory rather than treating the archive as a game.
