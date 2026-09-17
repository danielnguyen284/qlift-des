# QLIFT Brand System Source

This repository is the clean source package for building and reviewing the reusable `QLIFT Core Design System v0.1` in Claude Design.

It converts the supplied 54-page QLIFT brand guideline into explicit, searchable instructions and separate visual assets. Claude Design should read this repository instead of inferring the brand from the QLIFT application code, Stitch HTML, or one large PDF alone.

## Start here

1. Read `CLAUDE_DESIGN_IMPORT.md`.
2. Read `brand/00-index.md` and the eight linked brand files.
3. Load `tokens/brand-tokens.json` for machine-readable authoritative values.
4. Inspect the separate logo and pattern files under `assets/`.
5. Inspect the matching guideline-page references under `references/guideline-pages/` before interpreting a visual rule.
6. Use `digital/DESIGN.md` and `digital/CONTENT_GUARDRAILS.md` for current QLIFT digital-product application rules.

## Authority order

1. Current explicit QLIFT project decisions.
2. Supplied QLIFT brand guideline, normalized in `brand/` and evidenced in `references/`.
3. Authoritative values in `tokens/brand-tokens.json`.
4. Digital application rules in `digital/`.
5. Concept imagery for art direction only.

If two sources conflict, do not guess. Record the conflict and request review.

## Repository boundaries

This repository intentionally excludes:

- the unapproved Next.js implementation;
- Stitch-generated HTML and synthetic content;
- competitor material;
- customer-portal concepts;
- demo contact information and office-application identities from the guideline;
- invented products, specifications, certifications, prices, projects, testimonials, metrics, warranty terms, or service promises.

## Asset status

- Logo PNGs are high-resolution temporary renders extracted from the guideline. They are suitable for design exploration, not final production masters.
- Pattern SVGs are temporary vector extractions from the guideline.
- Concept JPEGs are generated visual-direction material, not completed QLIFT products or projects.
- Official vector logo masters, licensed Gilroy files, and approved real photography are still missing.

See `provenance/SOURCE.md` and `assets/README.md` for details.

