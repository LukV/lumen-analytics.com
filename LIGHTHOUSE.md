# GitHub Pages Lighthouse Checklist

- **P** Preload one hero font weight only if above-the-fold text still flashes too long; keep remaining weights as normal stylesheet loads.
- **P** Serve the architecture SVG inline (already done) and keep raster images out of the hero unless compressed to modern formats.
- **A11Y** Verify contrast after every color tweak and keep keyboard close behavior for mobile nav (Escape/outside click already wired).
- **SEO** Add Open Graph and Twitter meta tags before launch so social previews are deterministic.
- **BP** Keep third-party scripts to one or zero; Cloudflare email decode is currently the only runtime script dependency.
- **OPS** Run Lighthouse in mobile mode on production URL after each push and track regressions in a short changelog note.
