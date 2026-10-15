# Project 1: Business / Profile Card

**Level:** Easy  |  **Time:** 2-3 hours  |  **Files:** HTML + CSS only

## What you'll practice
- Box model (padding, margin, border)
- Flexbox centering
- Border-radius and colors
- Hover and transition basics
- Typography (font-size, weight, line-height)

## Design
Open `design/` in your browser (drag the .svg file into Chrome). Orange text on the mockup is a measurement note, not part of the design. Don't copy the notes into your page.

## Colors
| Variable | Hex | Used for |
|---|---|---|
| `--bg` | `#0F172A` | page background |
| `--card` | `#1E293B` | card background |
| `--accent` | `#38BDF8` | title text, avatar, hover fill |
| `--text` | `#F1F5F9` | main text |
| `--muted` | `#94A3B8` | secondary text |
| `--line` | `#334155` | borders and divider |

## Fonts
Inter (400, 500, 600, 700)
Link (already in the starter): `https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap`

## Icons
Free to use from `icons/` (24x24, stroke style, from the Feather icon set style). Use them as `<img src="icons/mail.svg">`. To change the color with CSS, paste the SVG inline in your HTML and set `color:` on it.

## Layout and spacing notes
- Page: full viewport height, card centered both ways with flexbox.
- Card: 400px wide, padding 40px, radius 24px.
- Avatar: 112px circle with initials (no image needed), 28px gap to the name.
- Name 28px bold. Title 16px in accent. Bio 14px muted, line-height 1.6.
- Three link buttons: full width, 44px tall, 1px border, radius 10px, 14px gap.
- Hover: button background becomes accent, text turns dark, transition 0.2s.

## Your checklist
- [ ] Center the card with display:flex on body
- [ ] Set box-sizing: border-box on everything
- [ ] Build the avatar circle with border-radius: 50%
- [ ] Style the three link buttons as <a> tags
- [ ] Add hover + focus-visible states
- [ ] Add the divider line with border-top
- [ ] Use CSS variables for every color
- [ ] Make the card shrink nicely on a 360px phone

## Stretch goals (optional)
- [ ] Add a dark/light toggle using a class on body
- [ ] Add a subtle box-shadow and make the card lift on hover

## How to work
1. Look at the design for 2 minutes. Sketch the boxes on paper (what is inside what).
2. Write the HTML first, with no styling. Use semantic tags.
3. Add CSS in layers: layout, spacing, colors, typography, then hover/focus states.
4. Compare with the design. Zoom the browser to 200% and also resize to 360px wide.
5. Commit to Git when done.
