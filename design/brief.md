# Design brief

Source: the interview, without Stitch
Mood: calm, curious, precise, funny. A modern, vibrant dark canvas inspired by Josh W. Comeau with rich violet accents, springy playful badges, and crisp monospace details.

## Style

- Style: Playful, with a Technical touch: monospace metadata and compact layout.
- Feel: calm, curious, precise, funny.
- Personal detail: a delicate four-point star icon next to the name as an artistic painter's mark.
- Motion: small and springy on hover and keyboard focus. When the visitor prefers reduced motion, nothing moves.

## Colours

| Token | Light | Dark | Used for |
|---|---|---|---|
| background | #fdfcff | #0b1021 | page background: clean crisp surface in light, deep night blue in dark |
| surface | #f3f1fb | #141d38 | cards, badges, skill stickers |
| text | #161426 | #f3f4fd | headings, body text, outlines |
| muted | #5a5770 | #9ca8c9 | headline under the name, dates, labels |
| accent | #6d28d9 | #a78bfa | links, focus ring, buttons: electric violet |
| on-accent | #ffffff | #0b1021 | text on an accent-coloured button |

## Type

| Role | Font | Size | Weight |
|---|---|---|---|
| headings | "Bricolage Grotesque", system-ui, sans-serif | name clamp(2.25rem, 5vw, 3.5rem), section 1.5rem, project 1.25rem | 700 |
| body | "Rubik", system-ui, sans-serif | 1rem, line height 1.6 | 400 |
| details | "JetBrains Mono", ui-monospace, Menlo, Consolas, monospace | dates and labels 0.875rem | 400 |

## Shapes

- Corner radius: 0.75rem on cards, fully round on buttons and skill badges.
- Borders: 1.5px in the muted colour thinned out around cards and badges.
- Shadows: subtle offset shadow, 3px down and right in dark mode.

## Layout

- One column, at most 46rem, centred, with 1.25rem space at the sides on phones; structured and compact.
- 3.5rem between sections, 1.25rem between items in a list.
- Projects: cards with a subtle outline, two columns from 40rem.

## Components

- Links: accent colour, underlined; brighter on hover, and keyboard focus shows a 2px accent ring.
- Projects: surface background, 1.5px border, 1.25rem inner space, title in heading font.
- Skills: rounded stickers: surface background, subtle border, fully round, tilted slightly.
- Section headings: in the heading font, weight 700, with a small monospace prefix.

## Signature

- Move: Stickers with a spring
- Guide: guides/ui-behaviors/physics-based-easing.md
- Where: the skill badges wobble and grow a little on hover and focus.

## Sections

1. `bio`: the name, headline and bio.
2. `projects`: the goal is a job, so the projects lead.
3. `links`: GitHub, LinkedIn and email.
4. `cv`: experience, education and skills.
