# QLIFT Portable Design System

Status: `READY_FOR_DESIGN_EXPLORATION`  
Authority: supplied QLIFT brand guideline plus explicit user instruction to follow it closely. Exact spacing, radii, shadows, breakpoints, and UI type sizes are intentionally not frozen because the source does not define them for digital products.

## Brand intent

QLIFT is a Vietnamese home-elevator brand that should feel professional, refined, approachable, safe, and precise. The visual system must make a high-consideration technical purchase understandable to homeowners while remaining credible to architects, technicians, and operators.

The design should feel like engineered architecture, not generic luxury and not SaaS decoration. Trust comes from measured hierarchy, legible explanations, transparent process states, strong photography, and disciplined brand geometry.

## Authoritative color tokens

| Token | Value | Primary role |
|---|---:|---|
| `qlift-blue` | `#343B9D` | Brand structure, navigation, headings, selected states, primary product chrome |
| `qlift-red` | `#FD172B` | Conversion CTA, urgent status, precise accents; use sparingly |
| `charcoal` | `#262626` | Body text, high-contrast dark surfaces |
| `metallic-silver` | `#C4C8CE` | Technical dividers, borders, neutral controls |
| `ivory` | `#F7F6F2` | Warm editorial/background surface |
| `mist-blue` | `#E8EAF6` | Information grouping, selected/quiet brand surface |
| `teal` | `#277C78` | Positive/service/success states when semantically appropriate |
| `champagne` | `#C4A265` | Restrained architectural accent, not a generic gold gradient |
| `architectural-beige` | `#DED3C4` | Warm material/context surface |

Do not recolor the logo, invent gradients, or allow red and blue to compete across every surface. Public conversion pages may use red for the single primary CTA; CRM screens should reserve red for primary conversion or true critical status so operational alerts remain legible.

## Typography

- Primary family: Montserrat.
- Secondary family: Gilroy, only when licensed client-provided files are available and Vietnamese glyph coverage is verified.
- Prototype fallback: use Montserrat for all roles rather than imitating Gilroy with an unrelated fashionable font.
- Body line height: follow the supplied 120–150% range, favoring the more generous end for long homeowner education and the tighter end for compact CRM labels.
- Do not set long body copy in all caps. Use uppercase only for short labels or navigational cues where readability remains strong.
- Public surfaces: confident, spacious display hierarchy with plain-language body copy.
- Admin/CRM: compact but calm hierarchy; tabular figures and status labels must scan quickly.

## Logo and brand marks

- Preserve supplied proportions, clear space, minimum-size intent, contrast rules, and approved color variants.
- Never stretch, crop, rotate, outline, recolor, add effects, or place over low-contrast imagery.
- Current PNGs are temporary PDF renders. Use them for prototype work only; replace every instance together when official vectors arrive.
- The geometric blue/red patterns may appear as cropped framing, section transitions, watermarks, or sparse wayfinding. They must not become a noisy full-page wallpaper.

## Layout and composition

- Use architectural alignment: clear vertical datum lines, measured asymmetry, confident image crops, and controlled negative space.
- Public site: image-led architectural storytelling with very low visible text density. Let full-bleed imagery and technical diagrams carry meaning; avoid stacking interchangeable rounded cards or explaining the whole business on one screen.
- CRM: stable left navigation, clear page title/action zone, filterable data views, contextual detail panels, and visible lifecycle/status progression.
- Square or low-radius geometry is the default. Choose final radii during exploration; do not introduce pill-shaped containers except for compact tags or segmented controls.
- Elevation should express hierarchy, not decoration. Prefer borders, tonal surfaces, spacing, and layering before heavy shadow.

## Public copy-density contract

- Homepage visual density: `2/10`. The interface should be understood by scanning images, short headings, and clear actions.
- Hero: one optional eyebrow, one headline of at most 7 Vietnamese words and 2 lines, one supporting sentence of at most 18 words, one primary CTA, and one compact call action. No other visible text.
- Hero exclusions: no feature bullets, statistics, badges, trust strip, mini-navigation, secondary paragraph, technical explanation, testimonial, or multi-card overlay.
- Standard marketing section: headline at most 8 words, supporting copy at most 25 words, and one visual or one action. Use at most one short supporting paragraph.
- The homepage previews decisions; detail belongs on Product, Solution, Process, Calculator, FAQ, and Knowledge pages. Use progressive disclosure instead of placing all explanations on Home.
- Reduce decorative labels and repeated eyebrows. Section position and imagery should carry hierarchy.
- These limits apply to public marketing surfaces, not dense CRM records where operational completeness is necessary.

## Core component families

### Shared

- Global header/navigation, footer, language/search affordances.
- Primary lead CTA, call action, form controls, validation, confirmation.
- Buttons, links, badges, status indicators, tabs, accordions, dialogs, toast/notification.
- Image frame and caption with `Hình ảnh định hướng` treatment for generated concepts.
- Empty, loading, error, success, offline, and permission-denied states.

### Public website

- Panoramic architectural hero, trust/value proof, product comparison, solution selector, process timeline.
- Calculator/configurator stepper with progress, summary, confidence notes, save/lead handoff.
- Project/case-study editorial modules that distinguish verified cases from concept imagery.
- Knowledge/article, FAQ, contact card, consultation form, sticky mobile contact actions.

### CRM and operations

- Dashboard KPI/queue modules, data table/list, pipeline board, filters/saved views.
- Person/company/elevator detail header, lifecycle timeline, activity log, task composer.
- Survey and configuration workspace, quotation builder, approval/version state, document viewer.
- Project milestone tracker, maintenance calendar, work-order dispatch, technician assignment, incident severity/status, audit trail.

## Interaction principles

- Every public path should offer a natural route to `Đăng ký tư vấn`; the phone action remains visible in header/mobile action areas without interrupting reading.
- Use the literal prototype placeholder `HOTLINE CHÍNH THỨC — BỔ SUNG TRƯỚC PRODUCTION`; never copy demo contact details from the guideline.
- Progressive disclosure is required for technical configuration. Explain why an input is needed and what changes in the result.
- Preserve context between CRM list and detail views. Destructive or irreversible actions require clear confirmation and consequence text.
- Show status, owner, next action, and date consistently across lead, project, installation, maintenance, and incident domains.
- Motion should be restrained and purposeful: orientation, state change, and hierarchy. Respect reduced-motion preferences.

## Imagery

- Current architectural scenes are AI-generated concepts approved for design/prototype use only.
- Use `hero-residential-atrium-concept-v1.jpg` as a full-bleed panoramic hero covering the entire hero canvas. Preserve the elevator/atrium as the dominant subject, place the minimal copy only in natural negative space or on a restrained contrast scrim, and do not convert the composition into a text column plus small image.
- Do not label concept scenes as completed QLIFT projects or infer dimensions, products, materials, engineering feasibility, or performance from them.
- Production replacement needs real product details, installation photography, and signed-off project metadata.

## Accessibility and usability

- Design toward WCAG 2.2 AA: text contrast, visible focus, keyboard sequence, semantic form grouping, error identification, target size, and reduced motion.
- Do not rely on brand color alone for status. Pair color with text/icon/pattern.
- Tables and boards require an accessible list/table alternative and meaningful mobile reduction.
- Vietnamese diacritics must remain clear at every size/weight. Validate Montserrat/Gilroy coverage before production.

## Avoid

- Purple gradients, glassmorphism, generic SaaS bento layouts, endless card grids, inflated pill buttons, and decorative blobs.
- A centered hero with two generic CTAs and a floating dashboard mockup.
- Text-dominant heroes, long value-proposition paragraphs, feature bullets, statistics, badges, or cards above the fold.
- Unsupported superlatives, fake metrics, invented customer logos, fake testimonials, fake projects, or fake specifications.
- Treating the CRM as a visual clone of the public marketing site; it shares identity, not density or task grammar.
