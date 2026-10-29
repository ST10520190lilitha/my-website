# Changelog

All notable changes to this project are documented in this file.

## [Part 2] - 2026-09-18

### Fixed
- Fixed a bug in `.product-table img` where `width: 200%` was forcing product
  images to overflow their table cells on smaller screens. Changed to
  `width: 100%` with `max-width: 140px`, in line with the rest of the
  responsive image rules.

### Added
- **Default CSS styles**: base rules for `html`, `img`, `a`, and headings
  (`h1`–`h3`) so every page starts from a consistent baseline.
- **Responsive images**: `img { max-width: 100%; height: auto; }` applied
  site-wide so images never overflow their containers on small screens.
- **Responsive navigation**: replaced the plain wrapping nav links with a
  CSS-only hamburger menu (hidden checkbox + label, no JavaScript) that
  appears below 700px and expands/collapses the nav links.
- **Media queries / breakpoints**: expanded from a single 600px breakpoint
  to three — 900px (tablet layout), 700px (mobile navigation), and 480px
  (small-phone typography and spacing).
- **Responsive typography**: `html` font-size scales down at the 480px
  breakpoint, shrinking heading and body text proportionally via `rem`
  units; hero and section headings also step down at each breakpoint.
- **Responsive layout**: `main`, `.hero`, `.enquiry-form`, `.intro-box`,
  `.callout`, and the embedded map all adjust padding/height at the
  tablet and mobile breakpoints instead of relying on one fixed layout.
- **Pseudo-classes**: added `:focus`/`:focus-visible` states for form
  inputs, search box, nav links, detail-list links and footer links;
  added `nav a:last-child` and `.product-table tbody tr:last-child`.

### Changed
- `header` is now `position: relative` (needed for the hamburger menu to
  position correctly) across all five pages: `index.html`,
  `Pages/about.html`, `Pages/contact.html`, `Pages/enquiry.html`,
  `Pages/products.html`.
