---
name: Studio Clarity
colors:
  surface: '#f9f9fb'
  surface-dim: '#d9dadc'
  surface-bright: '#f9f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f5'
  surface-container: '#eeeef0'
  surface-container-high: '#e8e8ea'
  surface-container-highest: '#e2e2e4'
  on-surface: '#1a1c1d'
  on-surface-variant: '#414753'
  inverse-surface: '#2f3132'
  inverse-on-surface: '#f0f0f2'
  outline: '#717785'
  outline-variant: '#c1c6d6'
  surface-tint: '#005cbb'
  primary: '#0059b5'
  on-primary: '#ffffff'
  primary-container: '#0071e3'
  on-primary-container: '#fcfbff'
  inverse-primary: '#abc7ff'
  secondary: '#5f5e60'
  on-secondary: '#ffffff'
  secondary-container: '#e2dfe1'
  on-secondary-container: '#636264'
  tertiary: '#5a5b5f'
  on-tertiary: '#ffffff'
  tertiary-container: '#737378'
  on-tertiary-container: '#fcfaff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d7e2ff'
  primary-fixed-dim: '#abc7ff'
  on-primary-fixed: '#001b3f'
  on-primary-fixed-variant: '#00458f'
  secondary-fixed: '#e4e2e4'
  secondary-fixed-dim: '#c8c6c8'
  on-secondary-fixed: '#1b1b1d'
  on-secondary-fixed-variant: '#474649'
  tertiary-fixed: '#e3e2e7'
  tertiary-fixed-dim: '#c7c6cb'
  on-tertiary-fixed: '#1a1b1f'
  on-tertiary-fixed-variant: '#46464b'
  background: '#f9f9fb'
  on-background: '#1a1c1d'
  surface-variant: '#e2e2e4'
typography:
  display-hero:
    fontFamily: Inter
    fontSize: 64px
    fontWeight: '600'
    lineHeight: 68px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Inter
    fontSize: 38px
    fontWeight: '600'
    lineHeight: 42px
    letterSpacing: -0.025em
  headline-xl:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 52px
    letterSpacing: -0.025em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 19px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.012em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.006em
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: -0.005em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  eyebrow:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.06em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
  space-3xl: 6rem
---

## Brand & Style

This design system delivers an ultra-refined, architectural digital space inspired by contemporary industrial design, high-end hardware showcases, and precision editorial layouts. The experience communicates uncompromising craft, quiet confidence, and optical purity.

### Key Tenets
- **Optical Precision:** Every alignment, typography scale, and spatial gap adheres to mathematical discipline with optical adjustments.
- **Atmospheric Whitespace:** Space is treated not as empty void, but as structural luxury. Generous breathing room gives artifacts authority and gravitas.
- **Restraint Over Decoration:** Zero non-functional ornaments. Visual separation is achieved through tone shifts, hairline borders, and subtle typographic weights rather than aggressive drop shadows or decorative motifs.
- **Physicality and Glass:** Interactive states leverage whisper-quiet backdrop blurs (`backdrop-filter: blur(20px)`), frosted surfaces, and refined micro-transitions (180ms ease-out) that mimic precision-milled glass and anodized aluminum.

## Colors

The palette is anchored in surgical neutrals with deliberate single-point emphasis. 

### Canvas & Surfaces
- **Canvas Base (`#ffffff`):** Pure white for core content panes, editorial focus fields, and hero display panels.
- **Canvas Secondary (`#fbfbfd`):** Atmospheric wash applied to structural page backgrounds and secondary panels.
- **Surface Elevation (`#f5f5f7`):** Component fill for grouped item containers, cards, pill badges, and input troughs.
- **Surface Translucent (`rgba(255, 255, 255, 0.8)`): Glassmorphic navigation bars and floating overlays paired with `backdrop-filter: saturate(180%) blur(20px)`.

### Typography & Structure
- **Text Primary (`#1d1d1f`):** Deep carbon for primary headlines, body text, and structural focal points.
- **Text Emphatic (`#000000`):** Absolute black reserved for ultra-large hero statements and high-contrast wordmarks.
- **Text Secondary (`#86868b`):** Neutral gray for supporting copy, timestamps, metadata labels, and inactive tab links.
- **Border Subtle (`#e5e5ea`):** Hairline container divides and subtle card bounds.
- **Border Structural (`#d2d2d7`):** Interactive element boundaries, input outlines, and defined sectional dividers.

### Accent & Action
- **Interactive Blue (`#0071e3`):** Clean, deliberate focus blue for hyperlinks, active toggles, and primary call-to-action buttons.

## Typography

Typography relies on geometric, low-contrast grotesque proportions rendered with tight negative tracking at larger display scales and relaxed, readable metrics for continuous reading.

### Rules of Application
- **Tracking Discipline:** Headings from 24px and above must systematically apply negative letter-spacing (`-0.015em` to `-0.03em`) to mimic tight Swiss typesetting and optical kerning.
- **Eyebrow Headers:** Feature tags and kicker texts use `eyebrow` styling: all-caps, `0.06em` tracking, weighted at semi-bold (600), rendered in `#86868b`.
- **Text Rendering:** Implement `-webkit-font-smoothing: antialiased` and `-moz-osx-font-smoothing: grayscale` globally to retain hair-thin stems against stark light backgrounds.

## Layout & Spacing

Layouts follow an asymmetric 12-column grid system bounded by generous dynamic margins, prioritizing vertical pacing and breathable editorial framing.

### Breakpoints & Adaptive Rhythm
- **Desktop (1200px+):** Max-width container of `1280px` or `1440px` centered. 12 columns, `1.5rem` gutters, and `3rem` lateral page margins. Vertical section gaps scale between `space-2xl` (64px) and `space-3xl` (96px).
- **Tablet (768px – 1199px):** 8 columns, `1.5rem` gutters, and `2rem` page margins.
- **Mobile (Up to 767px):** 4 columns, `1rem` gutters, and `1.25rem` outer canvas padding. Section gaps contract down to `space-xl` (40px) to maintain continuous narrative momentum.

### Spatial Discipline
All component padding operates on an 8-point rhythmic step (`space-xs` = 4px, `space-sm` = 8px, `space-md` = 16px, `space-lg` = 24px, `space-xl` = 40px). Micro spacing inside buttons, badges, and segmented switches strict-locks to 4px increments.

## Elevation & Depth

This design system avoids dark or heavy shadows, relying on layered surface tones, hairline borders, and translucent blur planes.

### Depth Hierarchy
1. **Base Tier (Ground):** `#fbfbfd` or `#ffffff` canvas surface.
2. **Container Tier (Subsurface):** `#f5f5f7` solid fills without borders, used to nest cards or control groups directly into the canvas.
3. **Card & Panel Tier (Floating Plane):** `#ffffff` solid background framed by a 1px border of `#e5e5ea`. Optionally paired with an ambient diffuse shadow: `0 8px 30px rgba(0, 0, 0, 0.04)`.
4. **Overlay Tier (Frosted Translucency):** `rgba(255, 255, 255, 0.82)` with `backdrop-filter: blur(20px) saturate(180%)`, delineated on the lower or outer edge by a 1px border of `rgba(0, 0, 0, 0.08)`.
5. **Modal & Floating Focus Tier:** Ambient studio illumination: `0 20px 48px rgba(0, 0, 0, 0.08), 0 0 1px rgba(0, 0, 0, 0.12)`.

## Shapes

Corner geometry prioritizes the Apple "squircle" aesthetic (continuous curvature / smooth corner transitions). Standard border radii use `0.5rem` (8px) for low-profile components up to `1rem` (16px) and `1.5rem` (24px) for expansive content cards.

### Shape Assignment
- **Interactive Controls (Buttons, Inputs, Selectors):** `0.5rem` (8px) to `0.625rem` (10px).
- **Segmented Controls & Action Pills:** Full pill contour (`9999px`).
- **Cards, Preview Modules, and Media Enclosures:** `1rem` (16px) for compact tiles; `1.25rem` (20px) or `1.5rem` (24px) for prominent showcase canvases.
- **Modal Dialogs:** `1.5rem` (24px).

## Components

### Buttons
- **Primary:** High-fill `#0071e3` background, `#ffffff` text, or high-contrast deep charcoal `#1d1d1f` with `#ffffff` text. Padding: `12px 22px`. Border radius: `9999px` (pill) or `8px`. Hover: `filter: brightness(1.05)`. Active: `transform: scale(0.98)`.
- **Secondary / Soft:** Subtle fill `#f5f5f7`, `#1d1d1f` text. 1px border `#e5e5ea`. Hover: `#e8e8ed` background.
- **Ghost / Text:** `#0071e3` or `#1d1d1f` text with an inline trailing chevron (`›`). No background fill. Hover: subtle opacity fade to 0.7.

### Input Fields
- **Container:** Solid `#f5f5f7` or `#ffffff` with a hairline 1px border `#d2d2d7`. Height: 44px. Internal padding: `0 14px`. Radius: `8px`.
- **States:** Focus replaces the border with `#0071e3` and adds a subtle halo: `0 0 0 4px rgba(0, 113, 227, 0.15)`. Typography: `15px`, `#1d1d1f`. Placeholder: `#86868b`.

### Cards & Showcase Modules
- **Editorial Cards:** Pure `#ffffff` surface, 1px border `#e5e5ea`, rounded to `20px` (`rounded-2xl`). Internal padding: `32px`. Visual content is framed flush to the edge or floated within a neutral `#f5f5f7` inner frame.
- **Interactive Hover:** Cards maintain absolute stillness; interactions manifest through internal image scaling (1.02x scale with 400ms cubic-bezier transition) while the frame remains rigid.

### Segmented Controls & Pills
- **Trough:** Pill-shaped (`9999px`) background in `#f5f5f7`, padded by `3px`.
- **Active Segment:** Floating `#ffffff` pill, with crisp `0 2px 6px rgba(0, 0, 0, 0.08)` shadow and 1px border `rgba(0, 0, 0, 0.04)`. Text shifts from `#86868b` to `#1d1d1f` with a weight transition from 400 to 500.

### Checkboxes & Radios
- **Checkbox:** `18px` square, `5px` corner radius. Unchecked: `#ffffff` with 1.5px border `#d2d2d7`. Checked: `#0071e3` fill with a crisp white hairline checkmark.
- **Radio Button:** `18px` circular control. Checked state displays a solid white dot centered in a `#0071e3` disc.

### Lists & Key-Value Spec Rows
- Separated strictly by full-bleed or inset 1px dividers `#e5e5ea`.
- Row height: 48px minimum. Label positioned on the left in `#86868b` (`body-sm`), values aligned to the right in `#1d1d1f` (`label-md`).