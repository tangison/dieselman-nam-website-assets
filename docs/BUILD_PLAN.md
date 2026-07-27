# BUILD PLAN

## Mode

Private client demo. The website must be noindex and excluded from public search until the client explicitly approves production release.

## Chosen interpretation

Build a visual, multi-page service website that prioritises direct contact and authentic work evidence. The project is not a booking platform, fleet-management portal, e-commerce store, or customer account system.

Alternative set aside: a single-page brochure. It was rejected because the service categories deserve individual search and conversion surfaces and Tangison projects default to multi-page architecture.

## Proposed routes

1. `/` Home
2. `/services` Service overview
3. `/services/mobile-wheel-alignment`
4. `/services/diagnostics-ecu-programming`
5. `/services/mechanical-diesel-repairs`
6. `/work` Authentic gallery and recent work
7. `/about`
8. `/contact`
9. `/brand`
10. `/privacy`
11. `/terms`
12. `/sitemap`
13. Custom 404 and 500 experiences

## Core journey

Visitor lands on a service or home page, understands the specific capability, sees authentic evidence, checks coverage or common questions, then calls or messages Stephen.

## Hero direction

- Full-bleed restored rail or Namib road image.
- Large editorial headline, never centred in a generic startup composition.
- Orange structural field should occupy a meaningful portion of the viewport.
- Floating navigation uses the transparent logo inside a circular CSS medallion.
- Two-line menu icon only. No hamburger made from three lines.
- Primary CTA: call or WhatsApp Stephen.

## Implementation constraints

- Inspect the repository before choosing the framework or dependencies.
- Use every supplied asset intentionally.
- Never regenerate the logo.
- Do not invent claims or content to fill layout holes.
- Keep the demo private and noindex.
- Use one motion engine at most.
- Preserve original images and generate responsive sources.
- Use AVIF with WebP fallback and explicit dimensions.
- Lazy-load below-fold imagery.
- Preload only the actual LCP image.
- Add the restrained linked credit `Made by Tangison Studio`.

## Acceptance criteria

- Every approved route exists and is complete.
- Phone and email links use exact verified values.
- The logo stays crisp and transparent at every size.
- No stock imagery or undocumented generated evidence.
- Desktop and mobile navigation are fully usable.
- Mobile menu has a touch-equivalent for every desktop interaction.
- Reduced-motion mode is functional.
- No generic repeated-card page rhythm.
- No dead controls, TODOs, placeholder copy, or fake content.
- Type-check, lint, production build, route checks, critical contact journey, console inspection, responsive checks, accessibility checks, SEO validation, media inspection, and available audit tooling pass before handoff.

## Deployment boundary

Do not deploy, publish, connect a domain, change DNS, or make the demo indexable unless the user gives explicit authorisation.

