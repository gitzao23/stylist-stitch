---
name: Aureate Noir
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#444748'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#5d5f5f'
  on-secondary: '#ffffff'
  secondary-container: '#dfe0e0'
  on-secondary-container: '#616363'
  tertiary: '#735c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#cca730'
  on-tertiary-container: '#4f3e00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style

The design system is anchored in high-fashion editorial aesthetics, blending **Minimalism** with **Modern Corporate** precision. It targets a sophisticated audience seeking a premium, curated styling experience. The emotional response should be one of exclusivity, clarity, and timeless elegance.

The visual language relies on high-quality photography as a primary design element, supported by generous whitespace (le chic "breathing room") and a restricted color palette. Transitions should be fluid and understated, mimicking the movement of luxury fabrics.

## Colors

This design system utilizes a high-contrast monochromatic base punctuated by a metallic accent.

- **Deep Charcoal (#1A1A1A):** Used for primary typography, icons, and high-impact backgrounds to ground the design.
- **Crisp White (#FFFFFF):** The primary surface color, ensuring a clean, gallery-like feel.
- **Accent Gold (#D4AF37):** Reserved strictly for interactive highlights, primary CTAs, and premium indicators.
- **Soft Neutral (#F9F9F9):** Used for subtle section breaks and input backgrounds to maintain softness against the stark charcoal.

## Typography

The typography strategy employs a classic serif/sans-serif pairing. **Playfair Display** provides an authoritative, editorial voice for headings, while **Inter** ensures maximum legibility for functional text and body copy. 

For large display headings, use tight letter-spacing to create a "locked" editorial look. For functional labels and navigation, use uppercase Inter with increased tracking to evoke luxury brand signaling.

## Layout & Spacing

This design system follows a **Fixed Grid** model for desktop to maintain the integrity of photographic compositions. A 12-column grid is used with generous 64px external margins to push content toward the center, creating a "boutique" feel.

Vertical rhythm is intentionally loose. Sections are separated by large gaps (120px+) to ensure the user focuses on one "look" or "story" at a time. On mobile, the layout shifts to a 4-column fluid grid with reduced margins, prioritizing vertical scroll speed and full-width imagery.

## Elevation & Depth

Hierarchy is achieved through **Tonal Layers** and **Ambient Shadows**. 

1. **Surface Level:** The base layer is always `#FFFFFF`.
2. **Interactive Depth:** Floating elements like cards or dropdowns use a very soft, highly diffused shadow (15% opacity Deep Charcoal, 30px blur, 10px Y-offset).
3. **Ghost Depth:** Subtle depth is created using 1px borders in `#E5E5E5` rather than shadows for a cleaner, flatter aesthetic on secondary components.

## Shapes

The shape language is "Soft-Modern." While the layout is structured and architectural, individual components use a medium corner radius to prevent the design from feeling too aggressive or "brutalist." This softens the high-contrast color palette, making the experience more approachable and chic.

## Components

- **Buttons:** Primary CTAs are solid `Deep Charcoal` with `White` text, transitioning to `Accent Gold` on hover. Use a subtle 300ms ease-in-out for all state changes.
- **Input Fields:** Minimalist design with only a bottom border (1px) that thickens and changes to `Deep Charcoal` on focus.
- **Cards:** Used for product displays. Use "borderless" cards with images that extend to the top-left-right edges. Text remains below the image with generous padding.
- **Chips/Tags:** Small, pill-shaped elements using the `Soft Neutral` background with `label-caps` typography.
- **Imagery:** All images should feature a subtle inner-glow or 1px inset border to ensure they feel integrated into the UI.
- **Navigation:** Top-tier navigation uses `label-caps` without icons to maintain a sophisticated, text-heavy luxury aesthetic.