# Asset Manifest

## Purpose

This file is the working source of truth for all visual assets needed for the website redesign.

---

## Design files

### Pencil макет главной страницы

- Файл: `design-concepts.pen` (в корне проекта, открывается в Pencil Desktop App)
- Содержит два варианта: V1 светлый (синий, архив) + V2 тёмный premium (актуальный)
- Статус: **в работе** — базовые секции готовы, нужно добавить кейсы, диагностику, FAQ
- Актуальная цветовая система: `#C49A8A` (акцент), `#FAF7F5` (фон), `#1A1210` (тёмный/hero)

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
- `assets/images/hero-visual-main.svg` (working source)

Purpose:

- strong main visual for the first screen
- should visually communicate websites, bots, applications, and AI/product logic

Status:

- svg source created, webp export still needed

### 2. Top format icons

Required files:

- `assets/icons/icon-bot.svg`
- `assets/icons/icon-site.svg`
- `assets/icons/icon-ai.svg`

Purpose:

- support the three quick-format cards under hero

Status:

- в Pencil-макете используются Lucide-иконки (bot, globe, cpu) — для index.html файлы по-прежнему нужны

### 3. Value block icons

Required files:

- `assets/icons/icon-routine.svg`
- `assets/icons/icon-leads.svg`
- `assets/icons/icon-speed.svg`

Purpose:

- support the "What you get" block

Status:

- в Pencil-макете используются Lucide-иконки (zap, trending-up, timer) — для index.html файлы по-прежнему нужны

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

- `assets/brand/almira.jpg` — уже есть, используется в hero__profile
- `assets/brand/almira-hero.jpg` — **ПРИОРИТЕТ №1** — крупное фото для тёмного hero

Purpose:

- Hero стал тёмным, требует полноценного портретного фото на весь правый блок
- Без фото hero выглядит незавершённо

Status:

- `almira.jpg` есть в `assets/brand/`
- `almira-hero.jpg` — нужно сгенерировать через AI (уверенный портрет, тёмный фон, premium)
- Рекомендуемый формат: вертикальный, 800×1000px+, без лишнего фона

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

---

## Production-ready priority list

This is the practical build order for the next visual stage of the project.

### Phase 1 — critical homepage assets

Must exist before the homepage can feel like a finished product:

1. `assets/images/hero-visual-main.webp`
2. `assets/icons/icon-bot.svg`
3. `assets/icons/icon-site.svg`
4. `assets/icons/icon-ai.svg`
5. `assets/icons/icon-routine.svg`
6. `assets/icons/icon-leads.svg`
7. `assets/icons/icon-speed.svg`
8. `assets/ui/diagnostics-preview.webp`

### Phase 2 — structural support assets

These make the middle of the page feel more designed and less text-based:

1. `assets/ui/process-visual-overview.webp`
2. `assets/icons/icon-process-discovery.svg`
3. `assets/icons/icon-process-format.svg`
4. `assets/icons/icon-process-structure.svg`
5. `assets/icons/icon-process-build.svg`
6. `assets/icons/icon-process-launch.svg`
7. `assets/icons/icon-scope.svg`
8. `assets/icons/icon-extra-costs.svg`
9. `assets/icons/icon-support.svg`

### Phase 3 — polish and scale

These strengthen later passes and other pages:

1. `assets/ui/solution-site-preview.webp`
2. `assets/ui/solution-bot-preview.webp`
3. `assets/ui/solution-app-preview.webp`
4. `assets/ui/solution-ai-preview.webp`
5. `assets/ui/solution-automation-preview.webp`
6. `assets/ui/glow-soft-01.webp`
7. `assets/ui/glow-soft-02.webp`
8. `assets/ui/panel-floating-01.webp`

---

## Hero visual art direction

Target file:

- `assets/images/hero-visual-main.webp`

Use:

- homepage first screen

Visual goal:

- light product-style composition
- laptop or desktop screen with UI panels
- phone screen with bot or app interface
- floating interface cards
- calm blue-tech palette
- premium, clean, clear, modern
- no neon cyberpunk, no generic AI brain imagery

Composition rules:

- more visual weight on the right side
- usable negative space for heading and CTA on the left
- clean white or soft gray background with subtle atmosphere
- realistic or polished 3D-mockup feeling

Brand fit:

- should feel intelligent and modern
- should feel feminine through taste and softness, not through decorative sweetness
- should support trust, clarity, and product thinking

---

## Icon system direction

All homepage icons should follow one system:

- SVG
- rounded geometric shapes
- soft blue gradient or two-tone blue palette
- subtle depth without cheesy 3D
- friendly but professional
- readable at small card sizes

Do not mix:

- outline-only icons from one set
- filled icons from another
- random colors
- purple neon AI motifs

Current status:

- first homepage icon set started locally in `assets/icons/`
