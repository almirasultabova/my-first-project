# Asset Manifest

## Purpose

This file is the working source of truth for all visual assets needed for the website redesign.

It helps keep:

- asset structure clean
- filenames consistent
- future generation and integration organized

All new images, icons, previews, and brand visuals should live inside `assets/`, not in the project root.

---

## Folder structure

- `assets/brand/` — brand photos and personal visuals
- `assets/cases/` — case cover images and curated case previews
- `assets/icons/` — icon set used across cards and UI blocks
- `assets/images/` — major visual compositions like hero images
- `assets/ui/` — UI previews such as diagnostics, process visuals, mini mockups

---

## Current available assets

### Brand

- `assets/brand/almira.jpg` — planned target path for the main portrait

Current source in project root:

- `almira.jpg`

### Case visuals already available in project

Current sources:

- `portfolio/case-telo-pomnit/img/site1.jpg`
- `portfolio/case-telo-pomnit/img/site2.jpg`
- `portfolio/case-telo-pomnit/img/screen-home.jpg`
- `portfolio/case-telo-pomnit/img/screen-diary.jpg`
- `portfolio/case-telo-pomnit/img/screen-path1.jpg`
- `portfolio/case-telo-pomnit/img/screen-path2.jpg`
- `portfolio/case-telo-pomnit/img/screen-stream1.jpg`

Planned curated homepage targets:

- `assets/cases/case-site-01.jpg`
- `assets/cases/case-bot-01.jpg`
- `assets/cases/case-automation-01.jpg`

---

## Required assets for homepage

### 1. Hero visual

Required files:

- `assets/images/hero-visual-main.webp`
- `assets/images/hero-visual-mobile.webp` (optional but recommended)

Purpose:

- strong main visual for the first screen
- should visually communicate websites, bots, applications, and AI/product logic

Status:

- missing

### 2. Top format icons

Required files:

- `assets/icons/icon-bot.svg`
- `assets/icons/icon-site.svg`
- `assets/icons/icon-ai.svg`

Purpose:

- support the three quick-format cards under hero

Status:

- missing

### 3. Value block icons

Required files:

- `assets/icons/icon-routine.svg`
- `assets/icons/icon-leads.svg`
- `assets/icons/icon-speed.svg`

Purpose:

- support the "What you get" block

Status:

- missing

### 4. Task block icons

Required files:

- `assets/icons/icon-task-leads.svg`
- `assets/icons/icon-task-services.svg`
- `assets/icons/icon-task-chat.svg`
- `assets/icons/icon-task-booking.svg`
- `assets/icons/icon-task-materials.svg`
- `assets/icons/icon-task-service.svg`

Purpose:

- give task cards more visual identity

Status:

- optional but strongly recommended

### 5. Solution catalog visuals

Required files:

- `assets/ui/solution-site-preview.webp`
- `assets/ui/solution-bot-preview.webp`
- `assets/ui/solution-app-preview.webp`
- `assets/ui/solution-ai-preview.webp`
- `assets/ui/solution-automation-preview.webp`

Purpose:

- make the solutions section feel more product-like and less text-heavy

Status:

- missing

### 6. Diagnostics preview

Required files:

- `assets/ui/diagnostics-preview.webp`

Purpose:

- show what the diagnostics tool looks like

Status:

- missing

### 7. Starter scenario visuals

Required files:

- `assets/icons/icon-starter-quick.svg`
- `assets/icons/icon-starter-expert.svg`
- `assets/icons/icon-starter-booking.svg`
- `assets/icons/icon-starter-materials.svg`
- `assets/icons/icon-starter-automation.svg`
- `assets/icons/icon-starter-support.svg`

Purpose:

- make the starter block feel more curated and finished

Status:

- optional but recommended

### 8. Process visuals

Required files:

- `assets/icons/icon-process-discovery.svg`
- `assets/icons/icon-process-format.svg`
- `assets/icons/icon-process-structure.svg`
- `assets/icons/icon-process-build.svg`
- `assets/icons/icon-process-launch.svg`

Alternative:

- `assets/ui/process-visual-overview.webp`

Purpose:

- strengthen the "How I work" section visually

Status:

- missing

### 9. Trust block icons

Required files:

- `assets/icons/icon-scope.svg`
- `assets/icons/icon-extra-costs.svg`
- `assets/icons/icon-support.svg`

Purpose:

- support the trust and transparency section

Status:

- optional but recommended

### 10. Curated case covers

Required files:

- `assets/cases/case-site-01.jpg`
- `assets/cases/case-bot-01.jpg`
- `assets/cases/case-automation-01.jpg`

Purpose:

- homepage-ready case covers with controlled cropping and presentation

Status:

- can be created from existing project screenshots

### 11. Brand portrait

Required files:

- `assets/brand/almira.jpg`
- `assets/brand/almira-portrait-02.jpg` (optional)

Purpose:

- support credibility and make the site feel personal and authored

Status:

- one source exists in root

### 12. Decorative UI assets

Required files:

- `assets/ui/glow-soft-01.webp`
- `assets/ui/glow-soft-02.webp`
- `assets/ui/panel-floating-01.webp`

Purpose:

- subtle depth and polish for sections if needed

Status:

- optional

---

## Recommended creation order

1. Move and organize existing brand + case images into `assets/`
2. Create curated case covers for homepage
3. Create or generate hero visual
4. Create icon set for top cards + value block
5. Create diagnostics preview
6. Create process and trust visuals
7. Add optional decorative UI assets

---

## Integration rule

Before connecting new visuals into `index.html` or `portfolio.html`:

- use assets from `assets/`
- avoid referencing images from scattered project folders when a curated asset exists
- prefer homepage-optimized covers instead of raw screenshots when possible
