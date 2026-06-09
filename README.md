# Memorial standalone options — Sonia & Amir Plot

Each option is now fully standalone:

- `option-4-journey-map/`
- `option-5-family-archive/`
- `option-6-pastel-blue/`
- `option-7-cinematic/`

Each folder includes:

- `index.html` — the option page
- `gallery-full.html` — gallery page for that option
- `assets/` — CSS, JS, images, PDFs, and OG image

Implemented notes:

- Decorative icon containers include `aria-hidden="true"`.
- `<main id="main">` includes `tabindex="-1"` for skip-link focus.
- Option 4 PDF links open in a new tab with `target="_blank" rel="noopener noreferrer"` and screen-reader text.
- Unique meta descriptions and Open Graph/Twitter social preview tags were added.
- `og:image` points to `assets/og-sonia-amir.webp`.
- Option 6 heading no longer uses a hardcoded `<br>`.
- Header no longer contains design-selection navigation; it now uses association-site placeholders.
- Footer includes a subtle association-context line.
- Contrast was strengthened for smaller muted text in Options 6 and 7.

Before going live, replace `/` and `/memorials/` in the header with the real association URLs, and if needed replace the logo placeholder with the real logo.
