# em-dash-astro

Community Transformation Trust website built with Astro.

## Canonical Storage Location

All current project work is now stored under:

- `C:\Users\StairCodes\Desktop\CTT\em-dash-astro` (canonical copy)
- `C:\Users\StairCodes\Desktop\CTT\TIM DEV SITE\em-dash-astro` (active dev server source)

## What Was Completed Today (2026-07-30)

- Confirmed the active dev server path for `/tcd-projects`.
- Updated `src/pages/tcd-projects.astro` donate section from single-column to two-column layout.
- Added donate image block beside donate heading/button.
- Added responsive behavior so donate section stacks cleanly on smaller screens.
- Verified successful production build after the changes.

## Project Scope

This Astro project now includes:

- Home page
- TCD projects page
- Water projects page
- Project funding page
- About page
- Annual report pages (2022-2026)
- TCD detail pages (Myanmar, Indonesia, Cairo, Seed Fund, Uganda)

## Main Paths

- Pages: `src/pages/`
- Global styles: `src/styles/global.css`
- Shared layout: `src/layouts/Layout.astro`
- Images: `public/images/`
- Detail images: `public/images/details/`
- Report images: `public/images/reports/`

## Run Locally

```bash
cd "C:\Users\StairCodes\Desktop\CTT\em-dash-astro"
npm install
npm run dev -- --host 0.0.0.0
```

If PowerShell blocks npm scripts, use:

```powershell
& "C:\Program Files\nodejs\npm.cmd" run dev -- --host 0.0.0.0
```

## Build

```powershell
& "C:\Program Files\nodejs\npm.cmd" run build
```

## Clear To-Do List

### Pass 5 - Donation Page

- [ ] Create `src/pages/donation.astro` to match Figma layout and copy.
- [ ] Add complete donation flow content blocks (purpose, options, instructions, tax note).
- [ ] Connect donate CTAs from key pages to `/donation`.
- [ ] Add required donation-related imagery/assets to `public/images/`.
- [ ] Verify mobile/tablet/desktop spacing and hierarchy.
- [ ] Run build and visual QA against Figma reference.

### Pass 6 - Water Detail Pages

- [ ] Create `src/pages/water-filters-in-egypt.astro`.
- [ ] Create `src/pages/the-village-drill-hybrid.astro`.
- [ ] Create `src/pages/village-drill-in-kenya.astro`.
- [ ] Create `src/pages/wholives.astro`.
- [ ] Link cards/buttons from `water-projects.astro` to each detail page.
- [ ] Add page-specific images/content assets for each detail page.
- [ ] Run build and do parity QA at desktop/tablet/mobile.

### Pass 7 - Funding Detail Pages

- [ ] Create `src/pages/micro-enterprise-loans-in-egypt.astro`.
- [ ] Create `src/pages/reliefaid.astro`.
- [ ] Create `src/pages/mukinge-hospital-in-zambia.astro`.
- [ ] Link cards/buttons from `project-funding.astro` to each detail page.
- [ ] Add page-specific images/content assets for each funding page.
- [ ] Run build and parity QA at desktop/tablet/mobile.

## Notes

- `visual-parity-checklist.md` tracks parity status and next passes.
- Keep all new work under `C:\Users\StairCodes\Desktop\CTT\em-dash-astro`.
