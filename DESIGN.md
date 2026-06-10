---
name: Ethereal Form
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#4e4541'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#807570'
  outline-variant: '#d1c4be'
  surface-tint: '#675c58'
  primary: '#675c58'
  on-primary: '#ffffff'
  primary-container: '#f5e6e0'
  on-primary-container: '#716662'
  inverse-primary: '#d2c4be'
  secondary: '#7a564a'
  on-secondary: '#ffffff'
  secondary-container: '#fdccbe'
  on-secondary-container: '#795549'
  tertiary: '#5e5e5c'
  on-tertiary: '#ffffff'
  tertiary-container: '#ebe9e5'
  on-tertiary-container: '#696966'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#eedfda'
  primary-fixed-dim: '#d2c4be'
  on-primary-fixed: '#211a17'
  on-primary-fixed-variant: '#4e4541'
  secondary-fixed: '#ffdbd0'
  secondary-fixed-dim: '#ebbcae'
  on-secondary-fixed: '#2e150c'
  on-secondary-fixed-variant: '#603f34'
  tertiary-fixed: '#e4e2de'
  tertiary-fixed-dim: '#c8c6c3'
  on-tertiary-fixed: '#1b1c1a'
  on-tertiary-fixed-variant: '#474744'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  caption:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: '1.4'
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

The brand personality is rooted in quiet confidence and empowerment through refinement. It avoids the aggressive aesthetics of traditional athletic wear, opting instead for a "Soft Tech" approach that merges high-performance compression with a high-fashion, editorial sensibility. 

The design style is **Minimalism** with a **Tactile** edge. It utilizes generous whitespace to create a sense of breathability and premium positioning. Every interaction should feel intentional and smooth, evoking the sensation of high-quality fabric against the skin. The goal is to make the user feel supported, not restricted, through a UI that is as seamless as the products it represents.

## Colors

The palette is a curated spectrum of skin-adjacent tones and soft neutrals designed to feel inclusive and sophisticated.

- **Primary (#F5E6E0):** A soft nude that serves as the foundation for large surfaces and secondary backgrounds.
- **Secondary (#E8B9AB):** A muted blush pink used for interactive highlights and brand accents.
- **Tertiary (#FFFDF9):** A warm cream used as the primary background color to ensure the UI feels airy and light.
- **Neutral (#2D2D2D):** A deep charcoal, used exclusively for typography and high-contrast call-to-actions to ensure legibility and a premium anchor.
- **Accent (#D4A395):** A deeper rose-clay tone for hovered states and active indicators.

## Typography

This design system employs a classic typographic contrast. **Playfair Display** provides an editorial, high-fashion authority for headings, while **Plus Jakarta Sans** offers a soft, modern, and highly legible experience for functional text.

All "Label" styles should be treated with slight letter spacing and uppercase styling to provide a structural contrast against the organic curves of the serif headlines. Body text should maintain a generous line-height to preserve the minimalist, airy aesthetic.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** on desktop (12 columns) and a **Fluid Grid** on mobile (4 columns). 

Whitespace is treated as a core design element, not just a separator.
- **Vertical Rhythm:** Use a base 8px increment. Section gaps should be aggressive (120px+) to allow the eye to rest between content blocks.
- **Desktop:** 1280px max-width container centered with 64px outer margins.
- **Mobile:** 20px margins with a 16px gutter.
- **Reflow:** On tablet, gutters should remain at 24px while margins compress to 40px.

## Elevation & Depth

Depth is conveyed through **Tonal Layers** and **Ambient Shadows**. This design system avoids harsh dropshadows.

1.  **Level 0 (Base):** The Cream background (#FFFDF9).
2.  **Level 1 (Cards):** Soft Nude (#F5E6E0) with no shadow, or White with a very diffused, low-opacity shadow (Color: #2D2D2D at 4% opacity, 20px blur, 4px Y-offset).
3.  **Level 2 (Interactive):** Floating elements like navigation bars or cart drawers use a backdrop blur (12px) combined with a subtle inner border (1px, 10% Neutral) to simulate transparency.

Transitions between levels should be soft and slow (300ms ease-in-out) to mimic the fluidity of fabric.

## Shapes

The shape language is defined by **Rounded** geometry. This mirrors the organic curves of the human body.

- **Standard Elements:** Buttons, input fields, and small cards use a 0.5rem (8px) radius.
- **Large Elements:** Featured product cards and imagery containers use 1rem (16px) radius.
- **Selection Controls:** Radio buttons and checkboxes should be fully circular to maintain a soft appearance.
- **Images:** All lifestyle photography should utilize the `rounded-lg` (16px) or `rounded-xl` (24px) token to prevent the design from feeling too "sharp" or clinical.

## Components

- **Buttons:** Primary buttons are Solid Charcoal (#2D2D2D) with White text, using `rounded-md`. Secondary buttons use an outline style with the Secondary color (#E8B9AB).
- **Chips/Filters:** Pill-shaped with a Primary color (#F5E6E0) background and Neutral text. When active, transition to Secondary color.
- **Input Fields:** Use a subtle Cream background (#FFFDF9) with a 1px border in Nude (#F5E6E0). Focus states transition the border to Secondary (#E8B9AB).
- **Cards:** Product cards should be "Ghost" style—clean backgrounds with no border, using a subtle shadow on hover to indicate interactivity.
- **Lists:** Product specification lists should use customized bullet points (a small "soft-plus" icon) in the Secondary color.
- **Checkboxes/Radios:** Softened circles. Avoid square checkboxes entirely to maintain the feminine shape language.
- **Additional Components:** "Size Guides" should be presented in modal drawers with a heavy backdrop blur to keep the user focused on the selection process.