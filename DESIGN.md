---
name: PocketLedger Minimalist Design System
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#3f4947'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#707977'
  outline-variant: '#bfc9c6'
  surface-tint: '#2a685f'
  primary: '#00352f'
  on-primary: '#ffffff'
  primary-container: '#044e46'
  on-primary-container: '#81beb3'
  inverse-primary: '#95d2c7'
  secondary: '#006a63'
  on-secondary: '#ffffff'
  secondary-container: '#99efe5'
  on-secondary-container: '#006f67'
  tertiary: '#25312b'
  on-tertiary: '#ffffff'
  tertiary-container: '#3b4841'
  on-tertiary-container: '#a8b6ad'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#b0efe3'
  primary-fixed-dim: '#95d2c7'
  on-primary-fixed: '#00201c'
  on-primary-fixed-variant: '#085048'
  secondary-fixed: '#9cf2e8'
  secondary-fixed-dim: '#80d5cb'
  on-secondary-fixed: '#00201d'
  on-secondary-fixed-variant: '#00504a'
  tertiary-fixed: '#d8e6dc'
  tertiary-fixed-dim: '#bccac0'
  on-tertiary-fixed: '#121e18'
  on-tertiary-fixed-variant: '#3d4a43'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display:
    fontFamily: Plus Jakarta Sans
    fontSize: 3rem
    fontWeight: '700'
    lineHeight: 3.5rem
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 2rem
    fontWeight: '600'
    lineHeight: 2.5rem
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.625rem
    fontWeight: '600'
    lineHeight: 2.125rem
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.375rem
    fontWeight: '600'
    lineHeight: 1.875rem
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '600'
    lineHeight: 1.625rem
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.625rem
    letterSpacing: 0em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.5rem
    letterSpacing: 0em
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: 1.25rem
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '500'
    lineHeight: 1rem
    letterSpacing: 0.02em
  currency-display:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: 2.75rem
    letterSpacing: -0.03em
  currency-display-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.875rem
    fontWeight: '700'
    lineHeight: 2.25rem
    letterSpacing: -0.025em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1.25rem
  margin-tablet: 2rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system is tailored for Indonesian university students navigating independent financial life, budgeting allowances, shared living costs, and micro-savings. The visual tone fuses Scandinavian restraint with Japanese functional minimalism (muji-esque clarity meets modern fintech discipline).

### Core Principles
- **Clarity Over Decoration:** Elimination of non-functional graphic flourishes, heavy drop shadows, and visual noise. Every element on the canvas serves an informational or transactional purpose.
- **Cognitive Relief:** Financial tracking often triggers stress. The canvas uses ample negative space, calm botanical greens, and gentle structural delineation to induce composure rather than anxiety.
- **Glanceable Hierarchy:** Designed for rapid mobile scanning on campus—checking remaining daily balances, splitting cafe bills, or logging warung expenses in seconds.

## Colors

The palette is anchored in deep botanical teals paired with crisp, high-luminance canvas backgrounds and ultra-soft containment borders.

### Color Tokens & Usage
- **Primary (`#044E46`):** Deep Forest Emerald. Reserved for high-priority interactive states, primary actions, and key anchor points.
- **Secondary (`#0F766E`):** Brightened Deep Teal. Applied to secondary interactive triggers, active navigation items, and focus indicators.
- **Tertiary (`#E6F4EA`):** Soft Pastel Sage. Used for positive financial feedback, surplus indicators, and selected category backgrounds.
- **Neutral Dark (`#0F172A`):** Deep Slate. Strict default for headings, primary ledger amounts, and high-contrast numerical readouts.
- **Neutral Muted (`#64748B`):** Mid Slate. Used for metadata, category timestamps, secondary currencies, and helper text.
- **Canvas Base (`#FAFBFC`):** Pure crisp off-white for the main background layer.
- **Surface Elevation (`#FFFFFF`):** Crisp pure white for cards, bottom sheets, and input fields.
- **Subtle Outline (`#F1F5F9`):** Ghost border stroke applied to isolate cards cleanly without cast shadows.
- **Contextual Status Tones:**
  - Gentle Amber (`#FEF3C7`) / Warning Slate (`#92400E`): Budget limit proximity notices.
  - Subtle Rose (`#FEE2E2`) / Expense Slate (`#991B1B`): Outflow transactions and debt alerts.

## Typography

The type hierarchy is powered exclusively by Plus Jakarta Sans to deliver an approachable yet geometrically balanced typographic structure. 

### Typographic Rules
- **Numerical Primacy:** Monetary balances (`Rp`) must utilize negative letter spacing (`-0.02em` to `-0.03em`) and tabular figure settings (`tnum`) to keep rapidly updating figures aligned.
- **Airy Line Heights:** Generous line heights are enforced across all sizes to prevent typographic compression and maintain a clean editorial feel.
- **Contrast Consistency:** Use `headline-sm` and `body-md` for quick ledger list entries, pairing strict 600 weight for amounts with 400 weight for merchant descriptions.

## Layout & Spacing

The layout leverages a fluid 4-column structure on mobile devices, expanding to 8 columns on tablets and 12 columns on desktop web layouts.

### Structural Flow
- **Mobile First:** Primary interactions sit within a unified container with `1.25rem` outer margins, ensuring edge-to-edge breathing room while keeping thumb zones naturally centered.
- **Rhythm & Gaps:** Component internal padding adheres to an 8pt step rhythm. Outer container gaps rely strictly on `space-md` (cards/lists) and `space-xl` (section breaks).
- **Edge Containment:** Content containers are capped at `640px` max-width for single-column ledger workflows on wide displays to retain the personal notebook feel of the product.

## Elevation & Depth

Visual separation relies on flat, quiet boundaries rather than artificial drop shadows or physical skeuomorphism.

### Depth Mechanics
- **Ghost Outlines:** Containers and cards are delineated by a crisp `1px` border using `#F1F5F9`.
- **Canvas Contrast:** Separation is established solely between `#FFFFFF` cards resting on `#FAFBFC` canvases. Drop shadows (`box-shadow: none`) are completely avoided in standard card states.
- **Transient Elements:** Modals, toast notifications, and pull-up bottom sheets employ a soft, diffuse ambient anchor: `0 12px 32px -8px rgba(15, 23, 42, 0.06)`, keeping the overlay light, breathable, and grounded.

## Shapes

The design system incorporates intentional, gentle curves that soften dense financial data while preserving architectural order.

### Corner Radii Guidelines
- **Base Components (`0.5rem` / 8px):** Applied to form fields, nested micro-chips, and inline badges.
- **Cards & Ledger Containers (`1rem` / 16px):** Applied to main summary cards, expense group clusters, and persistent banners.
- **Overlay Sheets & Buttons (`1.5rem` / 24px):** Applied to bottom action drawers and primary standalone button pills for natural tactile ergonomics.

## Components

### Buttons
- **Primary:** Full fill `#044E46` with `#FFFFFF` text. Height `48px` minimum for mobile touch targets. Hover state transitions softly to `#0F766E`. Corner radius `1rem`. No bevels, gradients, or shadows.
- **Secondary / Ghost:** Transparent background with `#044E46` text and a subtle `#E2E8F0` border. Active press activates a light wash of `#E6F4EA`.
- **Tertiary:** Flat link styling with zero border, using `#0F766E` with strict inline vertical padding.

### Cards
- Pure white background (`#FFFFFF`), `1px` solid `#F1F5F9` border, `1rem` corner radius, `space-md` internal padding. 
- Disallow nested borders inside a parent card; child transaction items separate via clean whitespace or `1px` `#F8FAFC` hairline separators.

### Chips & Filter Tags
- Height `36px`, rounded `1rem`. Default state features transparent fill with `#E2E8F0` border and `#64748B` typography. Selected state features `#E6F4EA` fill with `#044E46` text and no border stroke.

### Input Fields
- Flat `#FFFFFF` container with `1px` `#E2E8F0` border. Text in `#0F172A` with label positioned consistently above in `label-md` (`#64748B`). Active focus state applies a crisp `1.5px` border of `#044E46` without outer ring glow. Height: `48px`.

### Checkboxes & Radio Selectors
- `20px` width/height. Subtle `#CBD5E1` border stroke on unselected states. Selected state transitions to solid `#044E46` with white micro-icon check. Smooth `150ms` ease-in-out transition.

### Transaction Row Item (Specialized Component)
- Horizontal layout with `space-sm` vertical padding. Left section holds a circular category glyph (`36px`, `#F8FAFC` background, monochrome slate icon). Middle holds title (`headline-sm`, 14px) and date subtitle (`body-md`, 12px). Right holds tabular numeric amount with positive inflows marked in `#044E46` and outflows marked in `#0F172A`.