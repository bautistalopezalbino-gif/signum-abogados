---
name: Signum Sovereign Editorial
colors:
  surface: '#fdf9f3'
  surface-dim: '#ddd9d4'
  surface-bright: '#fdf9f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3ed'
  surface-container: '#f1ede7'
  surface-container-high: '#ebe8e2'
  surface-container-highest: '#e6e2dc'
  on-surface: '#1c1c18'
  on-surface-variant: '#44474c'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f4f0ea'
  outline: '#74777d'
  outline-variant: '#c4c6cc'
  surface-tint: '#525f71'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#0f1c2c'
  on-primary-container: '#778598'
  inverse-primary: '#bac8dc'
  secondary: '#755b00'
  on-secondary: '#ffffff'
  secondary-container: '#fed977'
  on-secondary-container: '#785d00'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#051d31'
  on-tertiary-container: '#71869e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e4f9'
  primary-fixed-dim: '#bac8dc'
  on-primary-fixed: '#0f1c2c'
  on-primary-fixed-variant: '#3a4859'
  secondary-fixed: '#ffe08f'
  secondary-fixed-dim: '#e6c364'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#584400'
  tertiary-fixed: '#d0e4ff'
  tertiary-fixed-dim: '#b3c8e3'
  on-tertiary-fixed: '#051d31'
  on-tertiary-fixed-variant: '#34485f'
  background: '#fdf9f3'
  on-background: '#1c1c18'
  surface-variant: '#e6e2dc'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.4'
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '300'
    lineHeight: '1.6'
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: DM Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: DM Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
  container-max: 1440px
---

## Brand & Style

The design system is anchored in the concept of "Legal Majesty"—a fusion of timeless jurisprudential authority and cutting-edge digital luxury. It targets a high-net-worth and corporate clientele who value precision, heritage, and discretion. The aesthetic direction is **Refined Luxury Editorial**, a style that prioritizes generous white space, high-contrast serif typography, and a "physical paper" tactile quality.

The visual language balances **Minimalism** with **Glassmorphism**. While the core layouts are clean and structured, modern 2026 accents appear in the navigation and interactive layers through frosted surfaces and subtle grain. The emotional response is one of absolute trust, calm, and premium exclusivity.

## Colors

The palette utilizes a "Continental Cream" base (#F7F3ED) to differentiate from standard sterile white, creating a warmer, more prestigious atmosphere. **Primary Navy** serves as the anchor for text and high-authority blocks, while **Main Gold** is reserved for highlights, thin separators, and call-to-action iconography.

A subtle **5% opacity noise texture** is applied over the Cream Background and Dark Cream surfaces to mimic premium stationery. **WhatsApp Green** is used exclusively for the floating contact utility, ensuring immediate recognition without disrupting the luxury aesthetic.

## Typography

This design system uses a high-contrast typographic scale typical of prestige journals. **Playfair Display** provides the editorial voice, used for narrative headlines and section titles. The use of a 300 weight for **DM Sans** in large body copy blocks enhances the "lightness" of the layout.

Key UI labels and small metadata must be set in **DM Sans (600)** with increased letter spacing and uppercase styling to maintain legibility against the ornate headlines.

## Layout & Spacing

The system follows a **Fixed Grid** model on desktop (12-column) and a fluid model on mobile (4-column). A core feature is the **Bento Grid** layout used specifically for metrics and legal expertise clusters. These bento boxes should have varied sizes (e.g., 2x2, 1x1, 2x1) to create visual interest.

Vertical rhythm is driven by the 8px base unit. Section spacing should be generous (120px–160px) to allow the "editorial" feel to breathe. Separation between thematic blocks is achieved through **0.5pt Main Gold lines** rather than heavy shadows or background shifts.

## Elevation & Depth

Hierarchy is established through **Glassmorphism** and layering rather than traditional elevation.
- **Level 1 (The Desk):** The Cream Background with noise texture.
- **Level 2 (The Documents):** White cards (#FFFFFF) with 12px radii.
- **Level 3 (The Overlay):** Navigation headers and modal backdrops use a 20px Backdrop Blur with a semi-transparent White (80% opacity) or Navy (90% opacity) tint.

Shadows are avoided in favor of **low-contrast outlines** (1px stroke in #F0ECE6) and gold separators to maintain a flat, modern, and sophisticated "magazine" profile.

## Shapes

The shape language is "Geometric-Soft." 
- **4px (Small):** Used for input fields and selection controls.
- **12px (Cards):** The standard for all informational containers and bento items.
- **20px (Pills):** Reserved for buttons and status tags.
- **24px (Hero):** Used for large-scale media containers or primary "Call to Action" sections to provide a friendly, modern entry point.

## Components

### Buttons
Primary buttons are **Pill-shaped (20px)** with a Primary Navy background and White text. Secondary buttons use a transparent background with a 1px Main Gold border and Gold text. Micro-interactions should include a subtle scale-down effect (0.98).

### Cards & Bento Grid
Cards use the 12px radius. In a Bento Grid configuration, ensure that different card heights align to a common baseline. Use **Subtle Noise** on all card surfaces to maintain texture consistency.

### Input Fields
Fields use the 4px radius with a Dark Cream background. The active state is signaled by a 1px Main Gold bottom border only, emphasizing the editorial, "underline" feel.

### Navigation Header
The header must be a **Glassmorphic floating bar**. It should use a 20px blur and a subtle 1px border at the bottom in Light Gold (#E8C46A).

### Separators
Horizontal and vertical rules should be #C9A84C at 0.5px thickness. Use these to frame high-importance quotes or to bisect bento sections.