---
name: Esk Design System
version: 2.0.0
description: >
  A general-purpose web application design system. A warm amber brand core on a
  cool slate structural neutral, with vivid semantic accents for state and
  emphasis. Built for dashboards, SaaS products, marketplaces, content platforms,
  admin tools, and marketing surfaces alike.

meta:
  baseGrid: 4px
  baseRadius: 0.5rem
  maxContentWidth: 1360px
  defaultDensity: comfortable
  defaultTheme: light

colors:
  primitives:
    brand:
      50: '#fff8eb'
      100: '#ffefc7'
      200: '#ffddb8'
      300: '#ffc97a'
      400: '#ffb95f'
      500: '#f59e0b'
      600: '#d97706'
      700: '#b45309'
      800: '#855300'
      900: '#653e00'
      950: '#2a1700'
    neutral:
      0: '#ffffff'
      50: '#f8fafc'
      100: '#f1f5f9'
      200: '#e2e8f0'
      300: '#cbd5e1'
      400: '#94a3b8'
      500: '#64748b'
      600: '#475569'
      700: '#334155'
      800: '#1e293b'
      900: '#0f172a'
      950: '#020617'
    red:
      50: '#fef2f2'
      100: '#fee2e2'
      500: '#ef4444'
      600: '#dc2626'
      700: '#b91c1c'
      900: '#7f1d1d'
    emerald:
      50: '#ecfdf5'
      100: '#d1fae5'
      500: '#10b981'
      600: '#059669'
      700: '#047857'
    blue:
      50: '#eff6ff'
      100: '#dbeafe'
      500: '#3b82f6'
      600: '#2563eb'
      700: '#1d4ed8'
    violet:
      50: '#f5f3ff'
      100: '#ede9fe'
      500: '#7c3aed'
      600: '#6d28d9'
      700: '#5b21b6'
    indigo:
      500: '#6366f1'

  semantic:
    light:
      surface-canvas: '#f8fafc'
      surface-raised: '#ffffff'
      surface-sunken: '#f1f5f9'
      surface-hover: '#f1f5f9'
      surface-selected: '#ffefc7'
      surface-inverse: '#0f172a'
      surface-scrim: 'rgba(15, 23, 42, 0.48)'
      border-subtle: '#e2e8f0'
      border-strong: '#cbd5e1'
      border-inverse: '#334155'
      text-primary: '#0f172a'
      text-secondary: '#64748b'
      text-tertiary: '#94a3b8'
      text-inverse: '#ffffff'
      text-on-brand: '#0f172a'
      text-link: '#855300'
      brand: '#f59e0b'
      brand-hover: '#d97706'
      brand-active: '#b45309'
      brand-subtle: '#fff8eb'
      brand-ink: '#855300'
      brand-ring: 'rgba(245, 158, 11, 0.35)'
      danger: '#dc2626'
      danger-hover: '#b91c1c'
      danger-subtle: '#fef2f2'
      danger-ink: '#b91c1c'
      success: '#059669'
      success-hover: '#047857'
      success-subtle: '#ecfdf5'
      success-ink: '#047857'
      warning: '#d97706'
      warning-subtle: '#fff8eb'
      warning-ink: '#855300'
      info: '#2563eb'
      info-subtle: '#eff6ff'
      info-ink: '#1d4ed8'
      accent: '#7c3aed'
      accent-subtle: '#f5f3ff'
      accent-ink: '#5b21b6'

    dark:
      surface-canvas: '#020617'
      surface-raised: '#0f172a'
      surface-sunken: '#020617'
      surface-hover: '#1e293b'
      surface-selected: '#3f2d0a'
      surface-inverse: '#f8fafc'
      surface-scrim: 'rgba(2, 6, 23, 0.72)'
      border-subtle: '#1e293b'
      border-strong: '#334155'
      border-inverse: '#cbd5e1'
      text-primary: '#f8fafc'
      text-secondary: '#94a3b8'
      text-tertiary: '#64748b'
      text-inverse: '#0f172a'
      text-on-brand: '#0f172a'
      text-link: '#ffc97a'
      brand: '#f59e0b'
      brand-hover: '#ffb95f'
      brand-active: '#ffc97a'
      brand-subtle: '#2a1700'
      brand-ink: '#ffc97a'
      brand-ring: 'rgba(245, 158, 11, 0.45)'
      danger: '#ef4444'
      danger-hover: '#dc2626'
      danger-subtle: '#450a0a'
      danger-ink: '#fca5a5'
      success: '#10b981'
      success-hover: '#059669'
      success-subtle: '#022c22'
      success-ink: '#6ee7b7'
      warning: '#f59e0b'
      warning-subtle: '#2a1700'
      warning-ink: '#ffc97a'
      info: '#3b82f6'
      info-subtle: '#0b1e3d'
      info-ink: '#93c5fd'
      accent: '#a78bfa'
      accent-subtle: '#1e1038'
      accent-ink: '#c4b5fd'

typography:
  families:
    display: 'Plus Jakarta Sans'
    body: 'Inter'
    mono: 'JetBrains Mono'
  scale:
    display-lg:
      fontFamily: Plus Jakarta Sans
      fontSize: 56px
      fontWeight: '800'
      lineHeight: 64px
      letterSpacing: -0.025em
    display-md:
      fontFamily: Plus Jakarta Sans
      fontSize: 44px
      fontWeight: '800'
      lineHeight: 52px
      letterSpacing: -0.02em
    headline-xl:
      fontFamily: Plus Jakarta Sans
      fontSize: 32px
      fontWeight: '800'
      lineHeight: 40px
      letterSpacing: -0.02em
    headline-lg:
      fontFamily: Plus Jakarta Sans
      fontSize: 24px
      fontWeight: '700'
      lineHeight: 32px
      letterSpacing: -0.015em
    headline-md:
      fontFamily: Plus Jakarta Sans
      fontSize: 20px
      fontWeight: '700'
      lineHeight: 28px
      letterSpacing: -0.01em
    headline-sm:
      fontFamily: Plus Jakarta Sans
      fontSize: 16px
      fontWeight: '700'
      lineHeight: 24px
      letterSpacing: 0em
    body-lg:
      fontFamily: Inter
      fontSize: 16px
      fontWeight: '400'
      lineHeight: 24px
    body-md:
      fontFamily: Inter
      fontSize: 14px
      fontWeight: '400'
      lineHeight: 20px
    body-sm:
      fontFamily: Inter
      fontSize: 12px
      fontWeight: '400'
      lineHeight: 16px
    label-lg:
      fontFamily: Plus Jakarta Sans
      fontSize: 14px
      fontWeight: '600'
      lineHeight: 20px
    label-md:
      fontFamily: Plus Jakarta Sans
      fontSize: 12px
      fontWeight: '600'
      lineHeight: 16px
    label-sm:
      fontFamily: Plus Jakarta Sans
      fontSize: 11px
      fontWeight: '700'
      lineHeight: 14px
      letterSpacing: 0.04em
    numeric-xl:
      fontFamily: Plus Jakarta Sans
      fontSize: 36px
      fontWeight: '800'
      lineHeight: 40px
      letterSpacing: -0.02em
      fontVariantNumeric: tabular-nums
    numeric-lg:
      fontFamily: Plus Jakarta Sans
      fontSize: 24px
      fontWeight: '800'
      lineHeight: 28px
      letterSpacing: -0.02em
      fontVariantNumeric: tabular-nums
    numeric-md:
      fontFamily: Plus Jakarta Sans
      fontSize: 16px
      fontWeight: '700'
      lineHeight: 22px
      fontVariantNumeric: tabular-nums
    numeric-sm:
      fontFamily: Inter
      fontSize: 12px
      fontWeight: '500'
      lineHeight: 16px
      fontVariantNumeric: tabular-nums
    mono-md:
      fontFamily: JetBrains Mono
      fontSize: 13px
      fontWeight: '400'
      lineHeight: 20px

rounded:
  xs: 0.25rem
  sm: 0.375rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px

spacing:
  '0': 0
  '1': 0.25rem
  '2': 0.5rem
  '3': 0.75rem
  '4': 1rem
  '5': 1.25rem
  '6': 1.5rem
  '8': 2rem
  '10': 2.5rem
  '12': 3rem
  '16': 4rem
  '20': 5rem
  '24': 6rem

breakpoints:
  sm: 640px
  md: 768px
  lg: 1024px
  xl: 1200px
  '2xl': 1440px

layout:
  maxWidth: 1360px
  gutter: 1rem
  gutter-md: 1.5rem
  margin: 1rem
  margin-lg: 2.5rem
  sectionGap: 2.25rem
  sidebarWidth: 260px
  sidebarWidthCollapsed: 72px
  topBarHeight: 56px
  topBarHeightLg: 64px

elevation:
  0: 'none'
  1: '0 1px 2px 0 rgba(15, 23, 42, 0.05)'
  2: '0 1px 3px 0 rgba(15, 23, 42, 0.06), 0 1px 2px -1px rgba(15, 23, 42, 0.06)'
  3: '0 10px 25px -5px rgba(15, 23, 42, 0.08), 0 8px 10px -6px rgba(15, 23, 42, 0.04)'
  4: '0 4px 12px -2px rgba(15, 23, 42, 0.08), 0 2px 4px -2px rgba(15, 23, 42, 0.05)'
  5: '0 20px 25px -5px rgba(15, 23, 42, 0.12), 0 10px 10px -5px rgba(15, 23, 42, 0.04)'
  ring: '0 0 0 3px rgba(245, 158, 11, 0.35)'
  ring-danger: '0 0 0 3px rgba(220, 38, 38, 0.30)'

zIndex:
  base: 0
  sticky: 100
  dropdown: 200
  stickyNav: 300
  drawer: 400
  modal: 500
  popover: 600
  toast: 700
  tooltip: 800
  commandPalette: 900

motion:
  duration:
    instant: 80ms
    fast: 120ms
    base: 180ms
    moderate: 240ms
    slow: 320ms
  easing:
    standard: 'cubic-bezier(0.2, 0, 0, 1)'
    decelerate: 'cubic-bezier(0, 0, 0, 1)'
    accelerate: 'cubic-bezier(0.3, 0, 1, 1)'
    spring: 'cubic-bezier(0.34, 1.36, 0.64, 1)'
---

# Z System — General Web Application Design System

## 1. Brand & Style

### 1.1 Design Principles

| Principle | Meaning in practice |
|---|---|
| **Clarity over decoration** | Hierarchy comes from type weight, spacing, and one accent — not from shadows, gradients, or borders everywhere. |
| **Warm energy, cool structure** | Amber drives action and personality; cool slate neutrals carry density and reading. Never let amber exceed ~10% of a view's surface area. |
| **One primary action per view** | Each screen has exactly one visually dominant action. Everything else is secondary, ghost, or link. |
| **Density with breathing room** | Data-dense layouts are acceptable; cramped ones are not. Every dense block is separated by `space-xl` (36px). |
| **States are designed, not defaulted** | Every interactive element has defined default / hover / active / focus / selected / disabled / loading states. |

### 1.2 Emotional Intent

Confident, fast, trustworthy, a little energetic. The system should feel **modern and pragmatic** — a tool people use daily, not a landing page they visit once. Urgency (red) is reserved for genuine states, never for decoration, so it retains its signal value across every product surface.

### 1.3 Visual Language

- **Crisp surface framing.** White/raised containers on a slightly tinted canvas, separated by 1px `border-subtle`. Resting cards carry **no** shadow.
- **Warm kinetic accent.** Amber is the only "loud" color in the default state. Semantic accents (red, emerald, violet, blue) appear only when they *mean* something.
- **Editorial typography.** Plus Jakarta Sans for headers, labels, and numbers; Inter for reading. Tight negative tracking on large sizes, tabular numerals for all metrics.
- **Approachable curvature.** 8px for controls, 12–16px for containers, full pills for tags and floating actions.

---

## 2. Color

### 2.1 Role Assignment

| Role | Token | Use for |
|---|---|---|
| Brand fill | `brand` (`#f59e0b`) | Primary buttons, active tab indicator, selected controls, progress fills |
| Brand text | `brand-ink` (`#855300`) | Links, inline emphasis, icon accents on white |
| Brand subtle | `brand-subtle` (`#fff8eb`) | Selected rows, highlight backgrounds, icon containers |
| Danger | `danger` (`#dc2626`) | Destructive buttons, errors, negative deltas, critical alerts |
| Success | `success` (`#059669`) | Confirmation, positive deltas, completed states |
| Info | `info` (`#2563eb`) | Neutral informational banners, help links |
| Accent | `accent` (`#7c3aed`) | Premium tier, AI features, "special" blocks — never for core navigation |
| Neutral text | `text-primary` / `text-secondary` / `text-tertiary` | Body / supporting / metadata |

### 2.2 Hard Rules

1. **Amber always takes dark text.** `#f59e0b` + `#ffffff` fails contrast (~2.2:1). Use `text-on-brand` (`#0f172a`) → ~8:1.
2. **Never use amber for text on white.** Use `brand-ink` (`#855300`, ~6.5:1).
3. **One semantic color per surface.** An error banner doesn't also get a success chip and an info link in the same visual block.
4. **Color is never the only signal.** Pair every status color with an icon or a text label.
5. **Gradients are exclusive to "Spotlight" components** (premium CTA, AI assistant, upgrade banner). Nowhere else.

### 2.3 Signature Gradients

| Name | Value | Use |
|---|---|---|
| Spotlight-Violet | `linear-gradient(135deg, #7c3aed 0%, #6366f1 100%)` | Premium / AI / membership CTA |
| Spotlight-Emerald | `linear-gradient(135deg, #059669 0%, #10b981 100%)` | Sustainability, savings, positive programs |
| Masthead-Dark | `linear-gradient(180deg, #0f172a 0%, #1e293b 100%)` | Global header, hero bands, footer |

### 2.4 Dark Theme

- Applied via `[data-theme="dark"]` on `<html>`; all semantic tokens swap, primitives do not.
- Surfaces invert to `#020617` / `#0f172a`; borders become `#1e293b`/`#334155`.
- Brand fills stay `#f59e0b` with dark text; brand **text** lightens to `#ffc97a`.
- Elevation in dark mode is expressed with **lighter surfaces + 1px borders**, not heavier shadows.
- Never auto-invert images, logos, or illustrations — supply dark variants.

---

## 3. Typography

### 3.1 Families

| Family | Weights | Role |
|---|---|---|
| **Plus Jakarta Sans** | 600, 700, 800 | Headings, buttons, nav labels, badges, all numerals |
| **Inter** | 400, 500 | Body copy, descriptions, helper text, table cells |
| **JetBrains Mono** | 400, 500 | IDs, code, tokens, timestamps |

Load via `font-display: swap`. Fallback stack: `ui-sans-serif, system-ui, -apple-system, "Segoe UI", sans-serif`.

### 3.2 Scale Usage

| Style | Applied to |
|---|---|
| `display-lg` / `display-md` | Marketing heroes only (1 per page) |
| `headline-xl` | Page titles in app shells |
| `headline-lg` | Section headers, modal titles |
| `headline-md` | Card titles, panel headers |
| `headline-sm` | List item titles, form group headers |
| `body-lg` | Long-form reading, primary form input text |
| `body-md` | Default UI text, table cells, descriptions |
| `body-sm` | Helper text, timestamps, metadata |
| `label-lg` / `label-md` | Buttons, tabs, nav items, form labels |
| `label-sm` | Badges, overlines, table column headers (uppercase) |
| `numeric-xl` / `numeric-lg` | KPI values, dashboard metrics |
| `numeric-md` | Prices, counts, inline stats |
| `numeric-sm` | Secondary values, deltas, strikethrough comparisons |

### 3.3 Rules

- **Max measure:** 72ch for body copy; 48ch for centered marketing copy.
- **Heading tracking:** negative tracking only at ≥20px. Never track out headings.
- **Tabular numerals** on every number that aligns in a column (`numeric-*` handles this).
- **Truncation:** list/table titles clamp to 2 lines; card titles to 2 lines; never truncate a heading below 1 line.
- **Minimum body size:** 14px for interactive UI, 12px only for metadata and badges.

---

## 4. Layout & Spacing

### 4.1 Grid

12-column fluid grid, `max-width: 1360px`, centered, `margin-lg` (40px) horizontal padding on desktop.

| Breakpoint | Columns | Gutter | Typical layout |
|---|---|---|---|
| `<640px` | 4 | 16px | 1-col stack, 2-col compact cards, bottom nav |
| `640–767px` | 4 | 16px | 2-col cards |
| `768–1023px` | 8 | 16px | 3-col cards, sidebar becomes drawer |
| `1024–1199px` | 12 | 24px | Sidebar + content, 3-col cards |
| `≥1200px` | 12 | 24px | Sidebar + content, 4-col cards |

### 4.2 Spacing Rhythm

- 4px base unit. Only use tokens from the scale — no arbitrary values.
- Component internal padding: **12px** (compact) / **16px** (default) / **24px** (spacious).
- Vertical gap between major page sections: `36px` (`space-xl`); between related blocks: `16–24px`.
- Form field vertical rhythm: `20px` between fields, `8px` between label and input, `6px` between input and helper text.

### 4.3 Density Modes

| Mode | Row height | Card padding | Use |
|---|---|---|---|
| Comfortable (default) | 48px | 16px | Marketing, consumer apps, most SaaS |
| Compact | 40px | 12px | Admin tables, console views, power-user tools |

Toggle via `[data-density="compact"]` on a container — never mix densities within one view.

---

## 5. Elevation & Depth

Depth communicates **interaction layer**, not importance.

| Level | Shadow | Applied to |
|---|---|---|
| 0 | none | Canvas background |
| 1 | `elevation.1` | Resting inputs, subtle separations, sticky table headers |
| 2 | `elevation.2` | Resting cards **only if** they sit on a raised surface; dropdown triggers |
| 3 | `elevation.3` | **Hover** on interactive cards (+ `translateY(-2px)`) |
| 4 | `elevation.4` | Sticky top bar, sticky table header, popovers |
| 5 | `elevation.5` | Modals, drawers, toasts, floating assistant button |

Rules:

- A resting card on `surface-canvas` uses **1px border, no shadow**. Adding shadow at rest is a hierarchy error.
- Hover elevation is reserved for genuinely clickable containers.
- Modals always pair `elevation.5` with `surface-scrim`.
- Never stack more than two elevation levels in one visual region.

---

## 6. Shapes

| Radius | Token | Applied to |
|---|---|---|
| 4px | `xs` | Micro tags, inline chips, kbd |
| 6px | `sm` | Nested elements inside controls, progress bars |
| 8px | `DEFAULT` | **Buttons, inputs, selects, checkboxes** |
| 12px | `md` | Cards, tiles, popovers, dropdown menus, toasts |
| 16px | `lg` | Modals, drawers, panels, media containers |
| 24px | `xl` | Hero banners, feature surfaces |
| 9999px | `full` | Badges, avatars, chips, FAB, pill toggles, assistant trigger |

Nesting rule: a child's radius ≤ parent's radius. An 8px control inside a 12px card is correct; a 16px child inside an 8px parent is not.

---

## 7. Motion

| Token | Duration | Use |
|---|---|---|
| `fast` | 120ms | Hover, color/opacity changes, icon swaps |
| `base` | 180ms | Button press, checkbox toggle, tooltip |
| `moderate` | 240ms | Dropdown open, accordion, tab switch |
| `slow` | 320ms | Modal/drawer enter, page transition |

Easing: `standard` for almost everything; `decelerate` for entering elements; `accelerate` for exiting; `spring` only for the assistant FAB and toasts.

Rules:

- Animate `transform` and `opacity` only — never `width`, `height`, or `top/left`.
- Drawers slide from their anchor edge (right drawer enters from the right).
- Toasts fade + slide 8px.
- Under `prefers-reduced-motion: reduce`, all durations → `80ms` and transforms are removed (opacity only).

---

## 8. Interaction States

Every interactive element must define all seven:

| State | Visual treatment |
|---|---|
| **Default** | Base token values |
| **Hover** | Background darkens one step (`brand` → `brand-hover`); text stays; add `elevation.3` only on cards |
| **Active / Pressed** | One more step (`brand-active`); `transform: scale(0.98)` on buttons (no scale on cards) |
| **Focus** | **Always visible** for keyboard: `box-shadow: 0 0 0 2px #ffffff, 0 0 0 4px #d97706` (offset ring). Never remove outlines without a replacement. |
| **Selected** | `brand-subtle` background + `brand` 1.5px border or left indicator bar |
| **Disabled** | `opacity: 0.45`, `cursor: not-allowed`, no shadow, no hover response, `aria-disabled="true"` |
| **Loading** | Spinner replaces label (width locked); container is `aria-busy`, non-interactive |

---

## 9. Components

### 9.1 Buttons

| Size | Height | Padding-x | Text | Radius | Icon |
|---|---|---|---|---|---|
| `sm` | 32px | 12px | `label-md` | 8px | 14px |
| `md` (default) | 40px | 16px | `label-lg` | 8px | 16px |
| `lg` | 48px | 20px | `label-lg` | 8px | 18px |

**Variants**

- **Primary** — `brand` fill, `text-on-brand`, hover `brand-hover`, active `brand-active`.
- **Secondary** — `surface-raised` fill, 1px `border-subtle`, `text-primary`, hover `surface-hover`.
- **Ghost** — transparent, `text-primary`, hover `surface-hover`.
- **Danger** — `danger` fill, white text, hover `danger-hover`.
- **Spotlight** — signature gradient fill, white text, hover adds a soft glow (`0 8px 24px -8px rgba(124,58,237,0.5)`). Reserve for one upgrade/AI action per view.
- **Link** — no fill, `text-link`, underline on hover only.

**Rules:** one Primary per view; Primary is full-width inside cards and forms, auto-width in toolbars; icon-only buttons are 40×40 with `rounded-full` or 8px and require `aria-label`.

### 9.2 Form Controls

- **Height:** 32 / 40 / 48 matching button sizes. Radius 8px.
- **Field anatomy (top to bottom):** label (`label-lg`, `text-primary`, optional `*` in `danger`) → control → helper text (`body-sm`, `text-secondary`) *or* error text (`body-sm`, `danger-ink`, with icon).
- **Border states:** default `border-strong` → hover `neutral-400` → focus `brand-active` + 3px `brand-ring` → error `danger` + `ring-danger` → disabled `surface-sunken` + `text-tertiary`.
- **Textarea:** min 3 rows, resizes vertically only, same border states.
- **Select:** native on mobile, custom listbox on desktop; chevron 16px, `text-secondary`.
- **Checkbox / Radio:** 18px, radius 4px / full, checked = `brand` fill with white check, focus ring on the box.
- **Switch:** 36×20 track, 16px thumb, on = `brand`, off = `neutral-300`.
- **Search:** leading magnifier icon, optional clear button, optional scope dropdown on the left (segmented style).
- **File dropzone:** dashed 2px `border-strong`, radius 12px, `surface-sunken`, `brand` border on drag-over.
- **Validation timing:** validate on blur, re-validate on change after first error. Never validate on first keystroke.

### 9.3 Cards

- **Base card:** `surface-raised`, 1px `border-subtle`, `rounded-md` (12px), `padding: 16px` (or `24px` spacious).
- **Interactive card:** adds `cursor: pointer`, hover → `elevation.3` + `translateY(-2px)` + border `border-strong`, `transition: 180ms standard`.
- **Media card:** full-bleed media at top (`aspect-ratio: 16/9` or `1/1`), content block below, corner radius clipped by parent `overflow: hidden`.
- **Stat/KPI card:** overline label (`label-sm`, uppercase, `text-secondary`) → `numeric-xl` value → delta chip (`success`/`danger` subtle) → optional sparkline.
- **Card meta stack:** overline (`label-sm`, uppercase, `text-tertiary`) → 2-line clamped title (`headline-sm`) → supporting line (`body-sm`, `text-secondary`) → footer (action row, separated by `border-subtle`).
- **Overlay chips:** absolute top-left stack, `rounded-full`, `label-sm`, 6px gap. Top-right holds a circular icon button (`surface-raised`, 32px, `elevation.1`).

### 9.4 Navigation

**Top app bar** — height 56px (64px ≥lg). Contains: brand mark, primary nav or page title, global search, and a right cluster (notifications, help, avatar). Sticky with `elevation.4` and a 1px bottom border.

**Side navigation** — 260px expanded / 72px collapsed (icons only, tooltips on hover). Collapses to a drawer below 1024px. Active item: `brand-subtle` background, `brand` 3px left indicator, `label-lg` `text-primary`.

**Tabs** — horizontal, 40px tall, 2px active indicator in `brand`, `label-lg`; inactive `text-secondary`, hover `surface-hover`. Scrollable on mobile with edge fades.

**Breadcrumbs** — `body-sm`, separator `/` in `text-tertiary`, current page `text-primary` and non-interactive, 3 items max before collapsing to `…`.

**Mobile bottom nav** — max 5 destinations, 56px, active item in `brand-ink`, icon 24px + `label-sm`.

**Command palette** — triggered by `⌘K`/`Ctrl K`; centered modal, 640px max, `elevation.5`, grouped results, `rounded-lg`, 44px rows.

**Pagination** — `sm` buttons in a row, current page filled `brand` with dark text, "Showing 1–25 of 480" in `body-sm` `text-secondary`.

### 9.5 Data Display

- **Table:** header row `label-sm` uppercase `text-secondary` on `surface-sunken`, sticky with `elevation.1`; rows 48px (40px compact), 1px `border-subtle` dividers, hover `surface-hover`, selected `surface-selected`; numeric columns right-aligned with `numeric-md`.
- **List row:** 56px, leading avatar/icon 32–40px, title `label-lg`, subtitle `body-sm` `text-secondary`, trailing action or metadata.
- **Badges / status pills:** `rounded-full`, 11px `label-sm`, 3px×8px padding. Variants: Neutral (`surface-sunken` / `text-secondary`), Brand (`brand-subtle` / `brand-ink`), Danger (`danger-subtle` / `danger-ink`), Success, Info, Accent. Always include a text label.
- **Avatar:** circle, sizes 24/32/40/48; initials fallback on `brand-subtle` with `brand-ink`; group stacks overlap by 8px with a 2px `surface-raised` ring.
- **Progress:** 6px track `neutral-200`, fill `brand` with 6px radius; determinate preferred; indeterminate uses a 240ms looped sweep.
- **Skeleton:** base `neutral-100` with a `neutral-200` shimmer (1.4s, ease-in-out); shapes must match final layout; never more than 3 rows of skeletons per block.
- **Empty state:** 48px icon in a 96px `brand-subtle` circle, `headline-sm` title, `body-sm` description, one primary action, optional secondary link. Center-aligned in the empty container.

### 9.6 Feedback & Overlays

- **Modal:** max-widths 480 / 640 / 800px, `rounded-lg`, `elevation.5`, scrim `surface-scrim`, 24px padding, header (`headline-lg` + close button) / body / footer (right-aligned actions, primary last). Focus trap + `Esc` close.
- **Drawer / Sheet:** right-anchored 400px (mobile: full-width bottom sheet, `rounded-t-xl`), slides in `slow` `decelerate`. Used for detail views, filters, and settings.
- **Popover / Dropdown:** 8px offset from trigger, `rounded-md`, `elevation.4`, 4px padding, items 36px with 8px radius and hover `surface-hover`, max-height 320px with scroll.
- **Tooltip:** `surface-inverse` fill, `text-inverse`, `body-sm`, `rounded-sm`, 8px offset, 400ms open delay, 0ms close.
- **Toast:** bottom-right desktop / top-center mobile, `rounded-md`, `elevation.5`, 16px padding, left accent border by status, auto-dismiss 5s (persist for errors), max 3 stacked.
- **Inline alert / banner:** full-width, `{status}-subtle` background, `{status}-ink` text, `rounded-md`, 12px padding, leading 20px status icon, optional action link on the right.
- **Assistant trigger:** 56px `rounded-full` FAB, Spotlight-Violet gradient, white icon, `elevation.5`, bottom-right with 24px offset. One per app; may expand into a 360px panel.

### 9.7 Structural Patterns

- **Value-prop row:** 4-up grid on desktop → 2-up tablet → 1-up stacked mobile. Each item: 40px icon in a `brand-subtle` circle, `headline-sm` title, `body-sm` sub-detail. White cards with `border-subtle` or a plain divided row — not both.
- **Icon nav tiles:** 64×64 `rounded-md` tile on `surface-sunken` (or a pastel tint) housing a 32px icon, with a 12px `label-md` truncated label below. Grid on desktop, horizontally scrollable row on mobile with edge fade.
- **Section header:** `headline-lg` title + optional `body-md` subtitle on the left, "View all →" link (`label-lg`, `text-link`) on the right, 24px bottom margin.
- **App shells:**
  - *Marketing shell:* top bar + centered content + footer, max 1360px, generous `space-xl` section gaps.
  - *Dashboard shell:* top bar + fixed sidebar + scrollable content grid (12-col, 24px gutters).
  - *Workspace shell:* top bar + collapsible sidebar + content + optional right inspector panel (320px).
  - *Marketplace shell:* top bar + search masthead + filter rail + card grid.

---

## 10. Accessibility

- **Contrast:** 4.5:1 for body text, 3:1 for ≥18px bold / ≥24px regular, 3:1 for UI component boundaries and focus indicators.
- **Focus:** always visible, 2px offset ring, `brand-active` color. Never `outline: none` without a replacement.
- **Target size:** 44×44px minimum on touch, 24×24px minimum for desktop-only controls.
- **Semantics:** native elements first (`<button>`, `<a>`, `<input>`, `<table>`); ARIA only to fill gaps.
- **Labels:** every input has a visible label (placeholder is not a label); icon-only buttons require `aria-label`.
- **Announcements:** errors via `aria-live="polite"`; toasts via `role="status"`.
- **Color independence:** status is always icon + text + color.
- **Motion:** honor `prefers-reduced-motion`; no auto-playing animation over 5s.
- **Zoom:** layouts must hold at 200% zoom and 320px width without horizontal scroll.

---

## 11. Content & Tone

- **Voice:** direct, helpful, human. Second person. Active voice.
- **Casing:** sentence case for headings, labels, and buttons — not Title Case.
- **Buttons:** verb + object ("Save changes", "Create project"), never "OK"/"Submit".
- **Numbers:** always specific ("Saves 12 min/week") over vague ("Saves time").
- **Errors:** what happened + why + what to do next. No blame, no error codes alone.
- **Empty states:** explain the value of filling the space, then offer the action.
- **Confirmations:** destructive actions require an explicit verb button ("Delete project") plus a cancel, never "Yes/No".

---

## 12. Implementation Notes

### CSS variable naming

```css
:root {
  --z-surface-canvas: #f8fafc;
  --z-surface-raised: #ffffff;
  --z-border-subtle: #e2e8f0;
  --z-text-primary: #0f172a;
  --z-brand: #f59e0b;
  --z-brand-ink: #855300;
  --z-radius-md: 0.75rem;
  --z-elevation-4: 0 4px 12px -2px rgba(15,23,42,.08), 0 2px 4px -2px rgba(15,23,42,.05);
  --z-duration-base: 180ms;
  --z-ease-standard: cubic-bezier(0.2, 0, 0, 1);
}
[data-theme="dark"] { /* override semantic tokens only */ }
```

### Tailwind mapping (excerpt)

```js
theme: {
  extend: {
    colors: {
      brand: { DEFAULT: '#f59e0b', hover: '#d97706', active: '#b45309', ink: '#855300', subtle: '#fff8eb' },
      surface: { canvas: '#f8fafc', raised: '#ffffff', sunken: '#f1f5f9' },
    },
    borderRadius: { DEFAULT: '0.5rem', md: '0.75rem', lg: '1rem', xl: '1.5rem' },
    fontFamily: { display: ['Plus Jakarta Sans', 'sans-serif'], body: ['Inter', 'sans-serif'] },
    boxShadow: { e3: '0 10px 25px -5px rgba(15,23,42,.08), 0 8px 10px -6px rgba(15,23,42,.04)' },
  }
}
```

### Adoption checklist

1. Import the two font families + mono.
2. Wire semantic tokens as CSS variables; switch themes via `data-theme`.
3. Build `Button`, `Input`, `Select`, `Checkbox`, `Card`, `Badge`, `Modal`, `Toast`, `Table` first — they cover ~80% of screens.
4. Audit every page for: one primary action, visible focus ring, no amber-on-white text, no resting shadows on canvas cards.

---

## 13. Do / Don't

| Do | Don't |
|---|---|
| Use amber for the single primary action | Use amber for links, borders, or decorative fills |
| Keep resting cards border-only | Add drop shadows to every card |
| Pair status color with icon + text | Rely on a red dot alone |
| Keep one accent gradient per view | Mix violet and emerald gradients in the same section |
| Use `body-md` (14px) as the UI baseline | Drop below 12px for anything interactive |
| Animate `transform`/`opacity` | Animate `height` or `width` |
| Collapse sidebar to a drawer below 1024px | Squeeze a 260px sidebar into a 768px viewport |
| Define all seven interaction states | Ship with browser-default focus styles |
| Clamp titles to 2 lines | Let long titles break card grid alignment |
