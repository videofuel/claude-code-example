# AI Educational Website — Plan

## Brief
Single-page HTML site for an AI education platform called **Sphinx**.
Style: light & editorial — white bg, black type, indigo accent (#6366F1).
Placeholder images via `placehold.co`. No JS, all CSS inline.

## Sections
1. Nav — sticky, logo + links + CTA button
2. Hero — two-column: big headline left, placeholder image right (offset + shadow)
3. Logo strip — "trusted by" company names
4. Courses — 3-card grid, each with placeholder image + metadata
5. Feature callout — image left, big stat + bullet list right, on gray surface
6. Pull quote — centered testimonial
7. CTA — email signup row
8. Footer — 3-column

---

## Checklist

- [x] Create `index.html` with document shell (DOCTYPE, head, font import, CSS variables)
- [x] Build Nav
- [x] Build Hero section
- [x] Build Logo strip
- [x] Build Courses section (3 cards)
- [x] Build Feature callout section
- [x] Build Pull quote section
- [x] Build CTA section
- [x] Build Footer
- [x] Add responsive breakpoints (@media max-width: 900px)

---

## Review

**File created:** `index.html` (single file, ~330 lines, all CSS inline)

**What was built:**
- **Nav** — sticky frosted-glass bar, indigo `S` logo mark, pill CTA button
- **Hero** — two-column layout, pulsing beta badge, 76px tight headline, placeholder image with 1.5° rotation and 14px indigo drop-shadow offset, floating learner-count pill
- **Logo strip** — 7 company names in muted gray, hover brightens
- **Courses** — 3 cards with color-coded placeholder images (indigo/green/amber per difficulty), hover lift + shadow, arrow CTA that turns indigo on hover
- **Feature callout** — gray surface band, two-column (image + text), large `94%` stat, accent-left-border bullet list
- **Pull quote** — centered, serif `"` mark in indigo, testimonial, avatar placeholder
- **CTA** — inline email + submit on a pill-shaped input row
- **Footer** — 3-column grid, logo, tagline, nav links, copyright bar
- **Responsive** — single `@media (max-width: 900px)` rule collapses all grids to 1-column, hides nav links, reduces padding

**Design tokens:** white bg, `#0A0A0A` text, `#6366F1` indigo accent, Inter font, `placehold.co` for all images
