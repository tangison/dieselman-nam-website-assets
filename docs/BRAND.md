# BRAND

## Core idea

**Built around the machines that keep Namibia moving.**

Dieselman Nam should feel practical, technically capable, rugged, direct, and locally grounded. It must not feel like a generic American trucking template or an AI-generated mechanic landing page.

## Art direction

- Art-direction owner: industrial editorial.
- Structural anti-slop gate: Hallmark.
- Layout and responsive polish: Impeccable.
- Landing-page variance: Taste, with medium-high visual boldness, medium motion, and controlled density.
- Imagery owner: authentic supplied client footage.
- Motion owner: tangison-motion-master.
- Interaction owner: tangison-widget-master.

## Palette

| Token | Hex | Use |
|---|---|---|
| Graphite | `#202223` | Main page background |
| Workshop black | `#121313` | Deep sections and overlays |
| Diesel orange | `#E85623` | Dominant accent, CTA, rules, active states |
| Hot orange | `#FF6A2A` | Small high-energy highlights only |
| Warm steel | `#A5A4A7` | Secondary borders and technical labels |
| Bone | `#F5F1EA` | Primary light text |
| Oxide | `#521A12` | Low-light red-brown depth |
| Sand | `#CDBB9A` | Namib landscape support tone |

Orange must be prominent but controlled through large colour fields, active navigation states, horizontal rules, and typography. Do not scatter small orange pills everywhere.

## Typography direction

- Display: a condensed or industrial grotesk with strong vertical structure.
- Body: a humanist sans with excellent mobile legibility.
- Avoid Inter, Roboto, Poppins, Montserrat, and generic squared “tech” fonts.
- Use no more than two families.
- Large headings may be condensed and closely tracked.
- Body copy must remain calm, direct, and easy to scan.

The build agent must verify font licensing and choose production-safe fonts from primary sources.

## Logo system

- `dieselman-nam-full-color.svg`: primary transparent vector logo.
- `dieselman-nam-dark-surface.svg`: lightened knockout variant for very dark surfaces.
- Keep the logo proportions unchanged.
- Do not redraw, regenerate, simplify, or typeset the name independently.
- On the floating navigation, place the transparent logo inside a CSS-created circular medallion. The medallion may overlap the navigation rail.
- Maintain at least 12% of the logo width as clear space around the visible mark.

## Image language

- Authentic, tactile, documentary.
- Machinery remains dirty, used, and real.
- Preserve dust, grease, worn paint, cables, concrete, and steel.
- Use large crops and cinematic strips.
- Alternate wide horizontal movement with close mechanical detail.
- Avoid staged mechanics posing with crossed arms.
- Avoid fake sparks, smoke, neon diagnostic interfaces, impossible engine detail, and polished stock workshops.

## Layout language

- Dark base with large orange fields.
- Floating navigation with two-line menu icon, a central or optically centred circular logo medallion, and one clear contact action.
- Editorial compositions instead of repeated card grids.
- Use asymmetry, vertical captions, cropped oversized type, mechanical measurement marks, and image strips.
- No glassmorphism, random blobs, purple gradients, nested cards, generic icon circles, fake counters, or excessive rounded rectangles.
- Each page should have a distinct rhythm while remaining recognisably part of the same system.

## Widget direction

- Service categories: horizontal tabs or a stepped selector, not four identical cards.
- Work imagery: touch-friendly carousel or controlled horizontal rail.
- FAQs: accordion.
- Service process: numbered vertical track or pinned sequence only if the content justifies it.
- Navigation: floating, hide on downward scroll, return on upward scroll.
- Primary contact: persistent phone/WhatsApp action without an unprompted popup.

## Motion system

Motion communicates direction and mechanical relationship.

- Entrance curve: `cubic-bezier(0.22, 1, 0.36, 1)`.
- Exit curve: `cubic-bezier(0.4, 0, 1, 1)`.
- UI transitions: 160 to 220ms.
- Drawers and larger surfaces: 260 to 340ms.
- Hero choreography: maximum 600ms, once per page.
- Animate transforms and opacity only, except a deliberate clip-path reveal.
- The floating navigation translates vertically when hiding or returning. It does not fade.
- Images may reveal through a horizontal or vertical clip that follows the composition.
- High-frequency hover and typing interactions receive minimal motion.
- `prefers-reduced-motion` must replace movement with immediate state changes while preserving feedback.
- Use CSS and native browser APIs first. Use one animation engine only if the final composition genuinely requires it.

## Voice

Direct, competent, plain-spoken, locally grounded, and technical without jargon for its own sake.

Avoid:

- “World-class solutions”
- “Your trusted partner”
- “Cutting-edge excellence”
- “Revolutionising the industry”
- Unverified “24/7”, “guaranteed”, or “fastest” claims
- Em dashes
- Exclamation marks as decoration

