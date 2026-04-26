---
name: company-design-system
description: Use this skill whenever building, styling, or reviewing any UI for the company — websites, web apps, dashboards, marketing pages, internal tools, components, artifacts, mockups, or design documents. Covers typography (H1–H6 + body sizes), spacing scale, border radius scale, the four official color themes (Main, Dark, Agentic AI, Odyssey), the custom background gradients for light/dark mode, page layout primitives (container, section, hero, nav, footer, two-column, three-column, responsive grid), and core components (cards, slider/carousel, logo ticker, buttons, badges, stats). Trigger this skill any time the user mentions "our design system", "brand colors", "company theme", "the design tokens", or asks to apply, switch, or reference any of the four themes by name — and any time they ask to build a section, hero, footer, card grid, or any multi-column layout. Always consult this skill before picking colors, font sizes, paddings, radii, or laying out any page so the output stays on-brand and never lets content stick to the viewport edges.
---

# Company Design System

The single source of truth for UI tokens across all company products. Use these values verbatim — do not invent intermediate sizes, off-palette colors, or one-off radii.

## Typography

All sizes use a 1.25 modular scale. Default font family is `Proxima Nova, system-ui, sans-serif`. Headings use `font-weight: 600` unless noted; body uses `400`.

| Token     | Size (rem) | Size (px) | Line height | Weight |
| --------- | ---------- | --------- | ----------- | ------ |
| `h1`      | 3.052      | 48.83     | 1.1         | 700    |
| `h2`      | 2.441      | 39.06     | 1.15        | 700    |
| `h3`      | 1.953      | 31.25     | 1.2         | 600    |
| `h4`      | 1.563      | 25.00     | 1.3         | 600    |
| `h5`      | 1.25       | 20.00     | 1.4         | 600    |
| `h6`      | 1.0        | 16.00     | 1.5         | 600    |
| `body-lg` | 1.125      | 18.00     | 1.6         | 400    |
| `body-md` | 1.0        | 16.00     | 1.6         | 400    |
| `body-sm` | 0.875      | 14.00     | 1.5         | 400    |
| `body-xs` | 0.75       | 12.00     | 1.4         | 400    |
| `caption` | 0.6875     | 11.00     | 1.3         | 500    |

## Spacing

4 px base unit. Use these tokens for padding, margin, and gap. Do not use raw pixel values.

| Token | Value  |
| ----- | ------ |
| `xs`  | 4 px   |
| `sm`  | 8 px   |
| `md`  | 12 px  |
| `lg`  | 16 px  |
| `xl`  | 24 px  |
| `2xl` | 32 px  |
| `3xl` | 48 px  |
| `4xl` | 64 px  |
| `5xl` | 96 px  |
| `6xl` | 128 px |

## Radius

| Token         | Value   | Use for                      |
| ------------- | ------- | ---------------------------- |
| `radius-none` | 0       | Edge-to-edge surfaces        |
| `radius-xs`   | 2 px    | Tags, micro-elements         |
| `radius-sm`   | 4 px    | Inputs, small buttons        |
| `radius-md`   | 8 px    | Buttons, dropdowns           |
| `radius-lg`   | 12 px   | Cards, panels                |
| `radius-xl`   | 16 px   | Modals, large containers     |
| `radius-2xl`  | 24 px   | Hero surfaces, feature cards |
| `radius-full` | 9999 px | Pills, avatars               |

## Colors

Four official themes. Each provides the same token set so components can swap themes by changing one variable scope.

### Theme 1 — Main (default light)

| Token           | Hex       |
| --------------- | --------- |
| `primary`       | `#0054FF` |
| `primary-hover` | `#003E9C` |
| `secondary`     | `#3376FF` |
| `accent`        | `#A033FF` |
| `success`       | `#179E60` |
| `warning`       | `#F68C00` |
| `danger`        | `#EB2E2E` |
| `bg`            | `#FFFFFF` |
| `surface`       | `#F0F6FF` |
| `border`        | `#DADDE3` |
| `text`          | `#0C1C3C` |
| `text-muted`    | `#8E98A8` |

### Theme 2 — Dark

| Token           | Hex       |
| --------------- | --------- |
| `primary`       | `#0054FF` |
| `primary-hover` | `#112F6B` |
| `secondary`     | `#3376FF` |
| `accent`        | `#A033FF` |
| `success`       | `#179E60` |
| `warning`       | `#F68C00` |
| `danger`        | `#EB2E2E` |
| `bg`            | `#000000` |
| `surface`       | `#0A0A0A` |
| `border`        | `#262626` |
| `text`          | `#F5F7FA` |
| `text-muted`    | `#8E98A8` |

### Theme 3 — Agentic AI

A cool, electric palette on a light periwinkle mesh background. Pair with `bg-main-mesh` by default.

| Token           | Hex       |
| --------------- | --------- |
| `primary`       | `#0054FF` |
| `primary-hover` | `#003E9C` |
| `secondary`     | `#3376FF` |
| `accent`        | `#A033FF` |
| `success`       | `#179E60` |
| `warning`       | `#F68C00` |
| `danger`        | `#EB2E2E` |
| `bg`            | `#FFFFFF` |
| `surface`       | `#F0F6FF` |
| `border`        | `#DADDE3` |
| `text`          | `#0C1C3C` |
| `text-muted`    | `#4E5971` |

### Theme 4 — Odyssey

A warm, exploratory palette inspired by deep-space sunsets.

| Token           | Hex       |
| --------------- | --------- |
| `primary`       | `#0054FF` |
| `primary-hover` | `#112F6B` |
| `secondary`     | `#3376FF` |
| `accent`        | `#A033FF` |
| `success`       | `#179E60` |
| `warning`       | `#F68C00` |
| `danger`        | `#EB2E2E` |
| `bg`            | `#000000` |
| `surface`       | `#0A0A0A` |
| `border`        | `#262626` |
| `text`          | `#F5F7FA` |
| `text-muted`    | `#8E98A8` |

## Background Gradients

Four official background gradients. Pair each theme with the gradient noted below. Apply to `body` or the top-level container — never to individual components.

| Gradient            | Pair with               | Tone  |
| ------------------- | ----------------------- | ----- |
| `bg-main-solid`     | **Main** (default)      | Light |
| `bg-dark`           | Dark                    | Dark  |
| `bg-main-mesh`      | **Agentic AI** (custom) | Light |
| `bg-odyssey-aurora` | **Odyssey** (custom)    | Dark  |

### `bg-main-solid` — Main theme (default)

A clean, flat surface — no gradient. Use the `bg` token directly so the page color follows the theme.

```css
background: var(--bg); /* #FFFFFF in Main */
```

### `bg-dark` — Dark theme

A clean, flat surface — no gradient. Use the `bg` token directly so the page color follows the theme.

```css
background: var(--bg); /* #000000 in Dark */
```

### `bg-main-mesh` — Agentic AI theme (custom)

Use the source image directly. File: `assets/main-theme-bg.png`.

```css
background:
  url("./assets/main-theme-bg.png") center / cover no-repeat fixed,
  var(--surface); /* solid fallback while the image loads */
```

### `bg-odyssey-aurora` — Odyssey theme (custom)

Use the source image directly. File: `assets/odyssey-theme-bg.png`.

```css
background:
  url("./assets/odyssey-theme-bg.png") center / cover no-repeat fixed,
  var(--surface); /* solid fallback while the image loads */
```

> Both images are 1920×1080. Use `background-size: cover` so they scale to any viewport. Keep the solid-color fallback so layout colors stay correct before the image loads or if it fails.

## Layout

### Container

Every page must wrap content in a `.container`. Sections themselves run edge-to-edge for full-width backgrounds, but the **container** caps line-length and provides the horizontal padding that keeps content off the viewport edges. Never let a section's children touch `100vw`.

```css
.container {
  max-width: 1280px;
  margin: 0 auto;
  padding: 0 var(--space-xl); /* 24px gutter on desktop */
}

@media (max-width: 640px) {
  .container {
    padding: 0 var(--space-lg);
  } /* 16px gutter on mobile */
}
```

### Section

A `section` is a vertical content block. It owns the **vertical** rhythm of the page; the container inside it owns the **horizontal** rhythm. Every section gets generous top/bottom padding so blocks breathe. Pair a section with a container; never put content directly inside a section.

```css
.section {
  padding: var(--space-5xl) 0; /* 96px top/bottom on desktop */
}

@media (max-width: 640px) {
  .section {
    padding: var(--space-3xl) 0;
  } /* 48px on mobile */
}
```

```html
<section class="section">
  <div class="container">
    <!-- content -->
  </div>
</section>
```

Each section should open with a `.section-header` containing an eyebrow tag, an `<h2>` title, and a lede paragraph. Headers cap at ~720 px so titles don't stretch to full width.

### Alternating section backgrounds

Sections must alternate their background to create vertical rhythm down the page. **The body itself stays a flat `var(--bg)` for every theme** — alternation is owned by the section, not the page. This keeps the visual cadence consistent across themes and lets each theme decide what its "accent" stripe looks like.

The pattern is the same for every theme: every other section uses the theme's flat `bg` token, and the alternates use a theme-specific accent layer (a flat `surface` for Main/Dark, the custom mesh/aurora image for Agentic AI/Odyssey). Concretely:

| Theme          | Default sections (`.section`) | Alternate sections (`.section.section-alt`) |
| -------------- | ----------------------------- | ------------------------------------------- |
| **Main**       | `var(--bg)` (#FFFFFF)         | `var(--surface)` (#F0F6FF)                  |
| **Dark**       | `var(--bg)` (#000000)         | `var(--surface)` (#0A0A0A)                  |
| **Agentic AI** | `var(--bg)` (#FFFFFF)         | `bg-main-mesh` image                        |
| **Odyssey**    | `var(--bg)` (#000000)         | `bg-odyssey-aurora` image                   |

Apply the alternation by adding the `.section-alt` class to every other section in source order. **The section that immediately follows the hero is a default `.section` (no `section-alt`)** — this matters for Agentic AI and Odyssey, where the hero already shows the mesh/aurora image, so the next section must drop back to flat `bg` to start the gradient → bg → gradient → bg cadence. From there, every second section is `.section-alt`.

```html
<body>
  <section class="hero"><!-- gradient in AAI/Odyssey, flat bg in Main/Dark --></section>
  <section class="section"><!-- flat bg --></section>
  <section class="section section-alt"><!-- accent layer --></section>
  <section class="section"><!-- flat bg --></section>
  <section class="section section-alt"><!-- accent layer --></section>
  <!-- ...and so on -->
</body>
```

```css
/* Body stays flat for every theme — alternation is owned by sections. */
body {
  background: var(--bg);
}

/* Default section: flat bg (matches the body, so the boundary is invisible). */
.section,
.hero {
  background: var(--bg);
}

/* Accent stripe — Main & Dark use the surface token. */
.section-alt {
  background: var(--surface);
}

/* Agentic AI: accent stripes use the mesh image. */
[data-theme="agentic-ai"] .section-alt {
  background:
    url("./assets/main-theme-bg.png") center / cover no-repeat,
    var(--surface); /* solid fallback */
}

/* Odyssey: accent stripes use the aurora image. */
[data-theme="odyssey"] .section-alt {
  background:
    url("./assets/odyssey-theme-bg.png") center / cover no-repeat,
    var(--surface); /* solid fallback */
}
```

Notes:
- The image-backed alternates use `background-attachment: scroll` (the default) — not `fixed` — because the image is now bound to the section, not the viewport. Each striped section gets its own framing of the image rather than one shared parallax window.
- Because the section, not the body, owns the image, the previous body-level `bg-main-mesh` / `bg-odyssey-aurora` recipes are no longer applied to `body` when sections handle the alternation. Keep the body background as `var(--bg)`.
- The hero never takes `.section-alt`. In Agentic AI and Odyssey the hero shows the gradient via the per-theme override below; in Main and Dark it stays flat.
- The first non-hero section is always a default `.section` (flat bg). The first `.section-alt` is the **second** non-hero section. This is what creates the gradient → bg → gradient → bg rhythm in Agentic AI and Odyssey, and the bg → surface → bg → surface rhythm in Main and Dark.

#### Hero exception for Agentic AI & Odyssey

In **Agentic AI** and **Odyssey** the hero is the page's opener and benefits from the same mesh/aurora image used by the alternating stripes — without it, the first paint looks abruptly flat before the rhythm starts. In **Main** and **Dark**, leave the hero on flat `var(--bg)`.

| Theme          | Hero background        |
| -------------- | ---------------------- |
| **Main**       | `var(--bg)` (flat)     |
| **Dark**       | `var(--bg)` (flat)     |
| **Agentic AI** | `bg-main-mesh` image   |
| **Odyssey**    | `bg-odyssey-aurora` image |

```css
/* Hero stays flat by default (covers Main and Dark). */
.hero {
  background: var(--bg);
}

/* Agentic AI: hero shows the mesh image. */
[data-theme="agentic-ai"] .hero {
  background:
    url("./assets/main-theme-bg.png") center / cover no-repeat,
    var(--surface);
}

/* Odyssey: hero shows the aurora image. */
[data-theme="odyssey"] .hero {
  background:
    url("./assets/odyssey-theme-bg.png") center / cover no-repeat,
    var(--surface);
}
```

The hero still does **not** take the `.section-alt` class — alternation counting is unchanged. This is purely a per-theme override on `.hero` itself.

### Hero

The hero is the first section on the page. It always fills the viewport (`min-height: 100vh`) so it acts as a full-height opener regardless of how much content sits inside it. Content is vertically centered via flex. Use heavier vertical padding than a normal section, an `<h1>`, and one or two CTAs.

```css
.hero {
  padding: var(--space-6xl) 0 var(--space-5xl); /* 128px top, 96px bottom */
  min-height: 100vh; /* full viewport height on every theme */
  display: flex;
  align-items: center; /* vertically center the inner container */
  text-align: center;
}
.hero > .container {
  width: 100%; /* needed because .hero is now a flex parent */
}
.hero h1 {
  max-width: 900px;
  margin: 0 auto var(--space-xl);
}
.hero-lede {
  max-width: 640px;
  margin: 0 auto var(--space-2xl);
}
```

The `min-height: 100vh` rule applies in every theme — the page should always open with the hero filling the screen, whether it's a flat `bg` (Main/Dark) or the mesh/aurora image (Agentic AI/Odyssey).

### Nav

Sticky top navigation. Uses a translucent `surface` background with `backdrop-filter: blur(12px)` so content scrolls subtly behind it. Contains: brand mark on the left, anchor links in the middle, and the theme switcher on the right.

```css
.nav {
  position: sticky;
  top: 0;
  z-index: 100;
  background: color-mix(in srgb, var(--surface) 92%, transparent);
  backdrop-filter: blur(12px);
  border-bottom: 1px solid var(--border);
}
.nav-inner {
  max-width: 1280px;
  margin: 0 auto;
  padding: var(--space-lg) var(--space-xl);
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: var(--space-xl);
}
```

### Footer

Bottom footer. Uses the `surface` background, sits flush to the bottom of the page, and contains a 4-column grid (brand + tagline taking 2 fractions, plus three link columns).

```css
.footer {
  background: var(--surface);
  border-top: 1px solid var(--border);
  padding: var(--space-4xl) 0 var(--space-2xl);
}
.footer-grid {
  display: grid;
  grid-template-columns: 2fr 1fr 1fr 1fr;
  gap: var(--space-3xl);
}
.footer-bottom {
  border-top: 1px solid var(--border);
  padding-top: var(--space-xl);
}
```

Collapse `footer-grid` to `1fr 1fr` at ≤960 px and `1fr` at ≤640 px.

### Two-column layout

A balanced 1:1 split for marketing and editorial sections. Stacks to a single column under 960 px.

```css
.col-2 {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: var(--space-3xl); /* 48px */
  align-items: center;
}
@media (max-width: 960px) {
  .col-2 {
    grid-template-columns: 1fr;
  }
}
```

### Three-column layout

Equal-width columns for capability lists, value props, or dense overviews. Collapses to two columns on tablet, one on mobile.

```css
.col-3 {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: var(--space-xl); /* 24px */
}
@media (max-width: 960px) {
  .col-3 {
    grid-template-columns: 1fr 1fr;
  }
}
@media (max-width: 640px) {
  .col-3 {
    grid-template-columns: 1fr;
  }
}
```

### Responsive grid

For card collections where the column count should adapt to available width, use `auto-fit` with a sensible minimum so columns reflow naturally instead of locking to a fixed count.

```css
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: var(--space-lg);
}
```

Use `minmax(220px, 1fr)` for stat tiles, `minmax(280px, 1fr)` for cards, and `minmax(180px, 1fr)` for compact swatch grids.

## Components

### Cards

The standard card uses `surface` background, a 1-px `border` outline, `radius-xl`, and `space-2xl` padding. Hover lifts the card 4 px and recolors the border to `primary` for affordance.

```css
.card {
  background: var(--surface);
  border: 1px solid var(--border);
  border-radius: var(--radius-xl);
  padding: var(--space-2xl);
  transition:
    transform 0.2s,
    border-color 0.2s;
}
.card:hover {
  transform: translateY(-4px);
  border-color: var(--primary);
}
```

Optional internal slots: a `card-icon` badge (48 × 48, `radius-md`, tinted-primary background), an `h5` title, and a body paragraph in `text-muted`. For larger marketing-style "feature cards", use `radius-2xl` and `space-3xl` padding instead.

### Slider / Carousel

Use a horizontal track of full-width slides with `transform: translateX()` for the transition. Provide both arrow controls and clickable dots, and auto-advance every 5–6 seconds.

```css
.slider-stage {
  overflow: hidden;
  border-radius: var(--radius-xl);
}
.slider-track {
  display: flex;
  transition: transform 0.4s cubic-bezier(0.4, 0, 0.2, 1);
}
.slider-slide {
  flex: 0 0 100%;
}
.slider-dot {
  width: 8px;
  height: 8px;
  border-radius: var(--radius-full);
  background: var(--border);
  transition:
    width 0.18s,
    background 0.18s;
}
.slider-dot.active {
  background: var(--primary);
  width: 24px; /* active dot stretches into a pill */
}
```

### Logo ticker

Infinite-scroll horizontal marquee. Duplicate the logo list inline so the animation can translate by `-50%` for a seamless loop. Add a fade overlay on both edges using gradients masked to the surface color.

```css
.ticker {
  overflow: hidden;
  position: relative;
}
.ticker::before,
.ticker::after {
  content: "";
  position: absolute;
  top: 0;
  bottom: 0;
  width: 96px;
  pointer-events: none;
  z-index: 2;
}
.ticker::before {
  left: 0;
  background: linear-gradient(to right, var(--surface), transparent);
}
.ticker::after {
  right: 0;
  background: linear-gradient(to left, var(--surface), transparent);
}

.ticker-track {
  display: flex;
  gap: var(--space-5xl);
  width: max-content;
  animation: scroll 30s linear infinite;
}
@keyframes scroll {
  from {
    transform: translateX(0);
  }
  to {
    transform: translateX(-50%);
  }
}
```

### Buttons

Three variants. All buttons share `radius-md`, `space-md var(--space-xl)` padding, and a `body-sm` 600-weight label.

| Variant     | Use for                        | Background           | Text        |
| ----------- | ------------------------------ | -------------------- | ----------- |
| `primary`   | Main page action, one per view | `--primary`          | `#FFFFFF`   |
| `secondary` | Alternates to primary          | transparent + border | `--text`    |
| `ghost`     | Tertiary or in-surface action  | transparent          | `--primary` |

Hover states: primary → `--primary-hover`; secondary → fill with `--surface`; ghost → tint with 10 % primary.

### Badges

Pill-shaped status indicators using `radius-full` and a tinted background derived from a semantic color (`color-mix(in srgb, var(--success) 15%, transparent)`). Available variants: `primary`, `success`, `warning`, `danger`, `neutral`.

### Stats

Compact metric tiles in an `auto-fit` grid. Each stat uses `surface` background, `radius-lg`, `space-xl` padding, and an `h2`-sized value in `--primary`.

## Usage Notes

Always reference tokens by name in code (CSS variables, Tailwind config, or design-token JSON) rather than hard-coding hex values, so a theme switch is a single root-class change. When a component appears in more than one theme, verify contrast (WCAG AA: 4.5:1 for body, 3:1 for large text) against the active `bg` and `surface` tokens — Odyssey and Agentic AI surfaces in particular need the lighter `text` token, never `text-muted`, for primary copy.
