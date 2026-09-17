# QLIFT Core Design System v0.1 — Acceptance Checklist

Use this checklist before publishing the reusable system or starting the full Claude Design project.

Decision values:

- `PASS`: complete and verified for design use.
- `PASS_WITH_BLOCKERS`: safe for prototype work with explicit unresolved production inputs.
- `REVISE`: system drift or missing foundation must be corrected before use.

## 1. Provenance and authority

- [ ] System name is exactly `QLIFT Core Design System v0.1`.
- [ ] Brand guideline, root `DESIGN.md`, `CONTENT.md`, `PROJECT_CONTEXT.md`, and `ASSET_MANIFEST.md` are recorded as sources.
- [ ] Current Next.js code, legacy sample HTML, Stitch `code.html`, and the TPEC seed were not used as design-system sources.
- [ ] Optional Stitch screenshots are identified as visual-language references only.
- [ ] Conflicts and missing sources are visible rather than silently resolved.

## 2. Authoritative brand foundations

- [ ] All nine supplied colors match their exact hex values.
- [ ] Semantic roles do not make QLIFT Red compete with routine blue actions and Admin states.
- [ ] Montserrat is primary throughout the specimen.
- [ ] Gilroy is absent unless licensed files and Vietnamese coverage are verified.
- [ ] Vietnamese diacritics render clearly at every demonstrated size and weight.
- [ ] Body line height remains within the supplied 120–150% guidance.
- [ ] Logo proportions, color, contrast, clear-space intent, and minimum-size intent are preserved.
- [ ] No logo recolor, crop, stretch, outline, gradient, shadow, or effect appears.
- [ ] Pattern use is sparse and functional rather than decorative wallpaper.

## 3. Token governance

- [ ] `AUTHORITATIVE` and `PROPOSED` token groups are separate.
- [ ] Proposed type sizes, spacing, breakpoints, radii, elevation, control sizes, density, and motion are not attributed to the guideline.
- [ ] Tokens use semantic roles rather than page-specific color names.
- [ ] Public and Admin density modes remain related but distinct.
- [ ] A future change can be made at token/component level without manually editing every screen.

## 4. Public system quality

- [ ] Public specimen is image-first and visibly low-density.
- [ ] Hero image remains full-bleed and owns at least 75% of the perceived composition.
- [ ] Hero copy stays within the approved quantitative budget.
- [ ] Hero contains no stats, badges, bullets, trust strip, testimonial, specifications, cards, or floating UI.
- [ ] Primary CTA and call action are distinct and legible.
- [ ] Standard section/component examples avoid text walls and repetitive cards.
- [ ] Concept imagery has a persistent `Hình ảnh định hướng` treatment.
- [ ] Generated imagery is not presented as real product, project, material, or engineering evidence.

## 5. Admin/CRM system quality

- [ ] Admin looks operational, not like a marketing page with tables placed inside cards.
- [ ] Status, owner, next action, and relevant date are consistently scannable.
- [ ] Table and list patterns show selection, loading, empty, partial, error, permission, and pagination behavior.
- [ ] Pipeline/board has a usable tablet/mobile alternative.
- [ ] Detail, activity, task, document, approval/version, and audit patterns are reusable.
- [ ] Destructive/financial/lifecycle actions have confirmation and consequence treatment.
- [ ] Status never depends on color alone.
- [ ] No synthetic people, project values, product specs, SLAs, certifications, or metrics are presented as QLIFT facts.

## 6. Component and state completeness

- [ ] Shared, Public, and Admin/CRM component inventories are separate and complete enough for the documented IA.
- [ ] Buttons include primary, secondary, tertiary, destructive, disabled, loading, focus, hover, and active states.
- [ ] Forms include persistent labels, required/optional treatment, help, inline error, error summary, loading, success, and recovery.
- [ ] Navigation includes desktop, mobile, keyboard, current-page, expanded, and collapsed behavior.
- [ ] Loading, empty, no-result, offline, permission, error, success, overdue, archived, and audit states are represented.
- [ ] Components are reusable families, not one-off compositions for the validation specimens.

## 7. Responsive and accessibility quality

- [ ] Public specimen covers small phone, tablet, desktop, and large desktop behavior.
- [ ] Admin specimen is desktop-first with deliberate tablet/mobile reduction.
- [ ] Vietnamese copy can grow without fixed-height clipping.
- [ ] Reading and focus order remain logical after reflow.
- [ ] Visible focus, keyboard access, touch targets, labels, errors, and non-color states target WCAG 2.2 AA.
- [ ] Reduced-motion behavior is defined.
- [ ] Hover is never the only way to discover information or an action.
- [ ] Table/list alternatives preserve critical information without horizontal traps.

## 8. Visual-language integrity

- [ ] The system feels like engineered architecture for a family home.
- [ ] It avoids generic luxury, generic SaaS, purple gradients, glassmorphism, blobs, oversized pills, and endless card grids.
- [ ] Negative space, architectural imagery, technical clarity, and restrained material colors work together.
- [ ] Public and Admin share brand identity without sharing the same composition or density.
- [ ] Motion supports orientation, feedback, and state change rather than spectacle.

## 9. Publish decision

Record:

- Decision: `PASS`, `PASS_WITH_BLOCKERS`, or `REVISE`.
- Reviewer and date.
- System draft/version reviewed.
- Failed checklist items.
- Explicit blockers that remain safe for prototype work.
- Corrections required before publication.
- Published system identity/version after approval.

Do not begin Gate 2 with an unpublished or `REVISE` system.
