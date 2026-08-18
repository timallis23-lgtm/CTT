# Visual Parity Checklist

Last updated: 2026-07-30

## Completed Today

- [x] Confirmed active Astro server source path.
- [x] Updated TCD donate section to two-column layout (copy + image).
- [x] Added responsive stacking behavior for donate section.
- [x] Verified Astro production build succeeds.
- [x] Consolidated docs for current status and next passes.

## Pass 5 - Donation Page

- [ ] Build `src/pages/donation.astro` from Figma reference.
- [ ] Add donation intro, options, and tax-deductible guidance content.
- [ ] Add CTA paths from TCD/Water/Funding/About pages to `/donation`.
- [ ] Add all required donation visuals under `public/images/`.
- [ ] Validate accessibility: heading order, link text, button states.
- [ ] QA desktop/tablet/mobile against Figma.
- [ ] Run `npm run build` and fix all issues.

## Pass 6 - Water Detail Pages

- [x] Build `src/pages/water-filters-in-egypt.astro`.
- [x] Build `src/pages/the-village-drill-hybrid.astro`.
- [x] Build `src/pages/village-drill-in-kenya.astro`.
- [x] Build `src/pages/wholives.astro`.
- [x] Wire `water-projects.astro` cards/buttons to detail routes.
- [x] Add route-specific media assets and alt text (reusing `water.png` until detail art is supplied).
- [x] QA desktop/tablet/mobile against Figma. (See QA notes below.)
- [x] Run `npm run build` and fix all issues.

## Pass 7 - Funding Detail Pages

- [x] Build `src/pages/micro-enterprise-loans-in-egypt.astro`.
- [x] Build `src/pages/reliefaid.astro`.
- [x] Build `src/pages/mukinge-hospital-in-zambia.astro`.
- [x] Wire `project-funding.astro` cards/buttons to detail routes.
- [x] Add route-specific media assets and alt text (reusing `funding.png` until detail art is supplied).
- [x] QA desktop/tablet/mobile against Figma. (See QA notes below.)
- [x] Run `npm run build` and fix all issues.

## QA Notes - Pass 6 & 7 (2026-08-19)

Verified in-browser on the running dev server at desktop (1280px) and mobile (390px).

Pass results:
- [x] Listing wiring: all 4 water cards and all 3 funding cards link to the correct detail routes.
- [x] Detail structure matches the reference detail pages (banner → centred H1 → meta row → olive `detail-lead` intro → sections → lists).
- [x] `detail-lead` renders in the correct olive (#2e4f03); em-dashes render correctly.
- [x] Heading order is clean (single H1, H3 section heads); link text is descriptive.
- [x] Mobile: project cards stack full-width; banner, title, meta, and body reflow correctly.

Known follow-ups (need client assets / decisions, not blockers):
- [ ] Banner and inline photo reuse the same `water.png` / `funding.png`, so they look repetitive and are not topic-specific. Replace with per-project banner + inline images when supplied.
- [ ] `water-projects.astro` "Better Water Blog" band still links to `#` with placeholder copy — confirm target or remove.
- [ ] No original Figma frames were available in-workspace; parity was checked against the codified `Figma:` spec values in `global.css` and the existing Figma-matched reference detail pages.
