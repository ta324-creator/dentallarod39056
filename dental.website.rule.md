# PROJECT RULE — MISSING ASSETS & DEPENDENCIES

## Never Invent Missing Resources

If a required asset, file, image, SVG, logo, document, credential, or piece of information is missing, **do not generate a replacement or create your own version.**

Instead:

1. Use a clearly labeled placeholder.
2. Continue building the website around the placeholder.
3. Generate a dependency report listing exactly what is still needed from me.

The project should never become blocked because an asset is missing.

---

## Placeholder Policy

Until I provide the official asset, use placeholders such as:

- `placeholder-seccionamarilla.svg`
- `placeholder-doctoralia.svg`
- `placeholder-yelp.svg`
- `placeholder-whatclinic.svg`
- `placeholder-gobmx.svg`
- `placeholder-uabc.svg`
- `placeholder-cedula.pdf`

The placeholder should preserve the correct layout, spacing, and component structure so that replacing it later only requires swapping the file.

---

## Do Not Recreate Brand Assets

Never redraw, redesign, recreate, trace, or generate unofficial versions of third-party logos or branding.

Wait for the official asset.

This applies to:

- Logos
- Verification badges
- Government seals
- University logos
- Company branding
- Certifications
- Official icons

---

## Missing Information Report

At the end of each development session, provide a concise "Missing Assets & Information" report.

Example:

### Missing Assets

- Sección Amarilla SVG
- Doctoralia SVG
- Gob.mx logo
- Professional License (Cédula)
- Updated clinic photography

### Missing Information

- Official business hours
- Additional doctor biography
- Google Maps URL
- Family Financial Plan document

This report should only contain items that are actually preventing the project from reaching production quality.

---

## Assume Nothing

If a URL, credential, phone number, document, or business detail is missing or uncertain:

- Do not guess.
- Do not fabricate.
- Do not substitute unofficial information.

Leave a placeholder and clearly indicate what is required from me to complete that section.

The goal is to produce a production-ready website that uses only verified assets and verified information.
# PROJECT UPDATE — MOBILE NAVIGATION & RESPONSIVE STABILITY

## Clean Mobile Navigation

Redesign the mobile navigation to feel clean, modern, and distraction-free.

Requirements:

- Use a simple hamburger menu icon.
- When opened, display the navigation as an overlay or slide-out menu.
- Add a semi-transparent blurred/gradient backdrop behind the menu so users always know where they left off on the page.
- Prevent interaction with the page while the menu is open.
- Include an obvious Close (✕) button in addition to tapping outside the menu.
- Opening and closing the menu should feel smooth with subtle animations.

The experience should feel premium and intuitive, not like a default template.

---

## Mobile Overflow Audit

The website has experienced overflow issues on smaller screens.

Perform a complete responsive audit and eliminate all horizontal scrolling or layout breaks.

Check every page and every component, including:

- Header
- Navigation
- Hero
- Service cards
- Pricing tables
- Floating buttons
- Image galleries
- Google Maps embeds
- Street View embeds
- Contact forms
- Footer
- Floating cards
- Notification components

No component should extend beyond the viewport on any common mobile device.

---

## Responsive Design Standards

The website must adapt gracefully to:

- Small Android phones
- iPhones (including Mini, Standard, Plus, and Pro Max)
- Tablets
- Laptops
- Desktop monitors
- Ultra-wide displays

Content should resize, wrap, or stack naturally without breaking the design.

Never rely on horizontal scrolling for primary content.

---

## Responsive Development Rule

Every new feature added in the future must be responsive from the beginning.

Responsive behavior is a requirement—not a final polish step.

Before considering any feature complete, verify that it works correctly on small screens and does not introduce overflow, clipping, or broken layouts.

The goal is a production-ready website that feels native on mobile while maintaining the same professional experience across all screen sizes.
