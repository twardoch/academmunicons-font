# Academmunicons TODO

The fonts are the product and they ship today. Everything below is a
convenience layer on top — none of it blocks using the font. Ordered by how
much a real user would feel its absence.

## Web packaging

- [ ] Generate WOFF2 (and WOFF) from the existing TTFs for smaller web payloads
- [ ] Ship a ready-to-include `academmunicons.css` with `@font-face` + named icon classes
- [ ] Publish an npm package (`academmunicons`) so `npm install` and a CDN (jsDelivr) just work
- [ ] Subset the variable font to the PUA range only, to trim bytes

## Reproducible build

- [ ] Add a `build.sh` that regenerates the TTFs from `sources/Academmunicons.vfj`
      (documents the FontLab dependency; VFJ needs FontLab to edit)
- [ ] Once a build exists, have CI build fonts and deploy the Jekyll site to GitHub Pages

## Coverage

- [ ] Add missing academic-platform icons (e.g. Semantic Scholar) — design work, needs FontLab
- [ ] Interactive icon gallery page with copy-to-clipboard names

## Quality

- [x] CI job validates every font parses with fontTools
- [ ] Add a `fontbakery` / `gftools qa` pass for deeper OpenType conformance checks
