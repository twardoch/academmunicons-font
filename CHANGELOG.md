# Changelog

All notable changes to this project are documented here.

## [Unreleased]

### Added
- CI workflow (`.github/workflows/ci.yml`) that parses every shipped font with
  fontTools on each push, so a malformed font never reaches a release.
- README "Use it on the web" section with a working `@font-face` snippet and the
  `liga` feature for plain-text icon names (e.g. `:orcid:`).
- Project icon at `docs/assets/icon.png` (monochrome line illustration).

### Changed
- `.gitignore` now excludes the generated `llms.txt` codebase snapshot.
- Rewrote `TODO.md` from a 100-item wishlist into a short, honest backlog.

## [200415] - 2020-04-15

### Initial Release
- Variable OpenType TT font with Weight (`wght`) axis from no border to reversed
  and Italic (`ital`) axis switching between circular and rounded-square borders.
- Traditional static OpenType TT fonts (Round and Square families).
- Academic icons: platforms (Academia, ArXiv, ORCID, ResearchGate, …),
  publishers and databases (IEEE, Springer, PubMed, …), course platforms
  (Coursera, Piazza), and Creative Commons marks.
- Stylistic sets `ss01`–`ss04` for the different border styles.
- Based on Academicons by James Walsh and Katja Bercic, plus Creative Commons
  icons by Ricardo Barros. Licensed under the SIL Open Font License v1.1.
