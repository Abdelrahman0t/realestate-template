---
name: Desert Modernist Luxury
colors:
  surface: '#fbf9f8'
  surface-dim: '#dbd9d9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f3'
  surface-container: '#efeded'
  surface-container-high: '#eae8e7'
  surface-container-highest: '#e4e2e2'
  on-surface: '#1b1c1c'
  on-surface-variant: '#444748'
  inverse-surface: '#303030'
  inverse-on-surface: '#f2f0f0'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#5e5e5b'
  on-secondary: '#ffffff'
  secondary-container: '#e1dfdb'
  on-secondary-container: '#63635f'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#291800'
  on-tertiary-container: '#9c7f59'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#e4e2dd'
  secondary-fixed-dim: '#c8c6c2'
  on-secondary-fixed: '#1b1c19'
  on-secondary-fixed-variant: '#474744'
  tertiary-fixed: '#ffddb2'
  tertiary-fixed-dim: '#e3c196'
  on-tertiary-fixed: '#291800'
  on-tertiary-fixed-variant: '#5a4321'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e2'
typography:
  display-lg:
    fontFamily: Bodoni Moda
    fontSize: 80px
    fontWeight: '400'
    lineHeight: 90px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Bodoni Moda
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-md:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0.01em
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style
The brand personality is rooted in "Architectural Editorial"—a blend of high-end Mediterranean minimalism and Riyadh’s contemporary urban sophistication. The target audience consists of high-net-worth individuals seeking curated, exclusive properties. 

The design style utilizes **Minimalism** with an **Editorial** flair. It prioritizes expansive whitespace to evoke a sense of quiet luxury and spatial freedom. Visuals should feel "considered" and "collected," avoiding cluttered UI in favor of large-scale photography and deliberate typographic scales. The emotional response is one of calm confidence, professional prestige, and timelessness.

## Colors
The palette is inspired by the textures of high-end architecture and the Saudi landscape. 

- **Primary (Charcoal):** Used for typography and structural elements. It provides a sharp, authoritative contrast against the base.
- **Secondary (Bone/Off-White):** The canvas of the design system. This warm neutral replaces pure white to create a softer, more expensive feel.
- **Tertiary (Muted Gold/Deep Sand):** An accent color used sparingly for high-value CTAs, active states, or subtle iconography.
- **Neutral:** Mid-tone grays for secondary information and borders to ensure the hierarchy remains sophisticated and legible.

## Typography
The typographic system relies on a high-contrast pairing. **Bodoni Moda** provides the editorial authority for property titles and section headers, behaving like a masthead. **Hanken Grotesk** offers a clean, technical counterpoint for property details, UI labels, and long-form descriptions. 

Uppercase styling is reserved for labels and small navigational elements to maintain an organized, museum-label aesthetic. Line heights are intentionally generous to ensure readability and a "breathing" layout.

## Layout & Spacing
The layout follows a **Fluid Grid** model with an emphasis on asymmetry. While most content aligns to a 12-column grid, key imagery and headlines should intentionally "break" the grid or use offset columns to create an architectural, rhythmic feel.

- **Desktop:** Large margins (80px) frame the content, acting as a matte for the UI. Section gaps are wide (120px) to prevent the user from feeling rushed.
- **Mobile:** Margins tighten to 20px, and asymmetric elements reflow into a singular, elegant vertical stack. 
- **Rhythm:** Use multiples of 8px for internal component spacing, but prioritize visual "white space" over dense information packing.

## Elevation & Depth
In this design system, depth is achieved through **Tonal Layers** and **Ambient Shadows** rather than heavy 3D effects. 

- **Surfaces:** Use subtle shifts between Bone (#F9F7F2) and a slightly darker "Paper" tint to define card areas.
- **Shadows:** Only used on primary floating elements (like a "Book a Viewing" card). Shadows must be extremely diffused, using the primary charcoal color at 5-8% opacity with a large blur radius (20px+) to mimic natural gallery lighting.
- **Outlines:** Use 1px borders in a soft neutral for input fields and dividers to maintain a crisp, architectural structure.

## Shapes
The shape language is primarily rectilinear, reflecting modern architectural lines. However, to avoid a "cold" feeling, a **Soft** roundedness (0.25rem/4px) is applied to buttons and cards. This small radius is just enough to take the edge off the sharp corners while maintaining a disciplined, professional appearance. Imagery should remain sharp-edged (0px radius) to feel like framed photographs within the layout.

## Components
- **Buttons:** Primary buttons are solid Charcoal with Bone text. Secondary buttons use a Ghost style with a 1px Charcoal border. Labels are always `label-sm` (uppercase).
- **Cards:** Property cards use a "Full Bleed" image style with typography placed either below or overlaid on a semi-transparent Bone background. Avoid heavy shadows; use a 1px subtle border for definition.
- **Inputs:** Minimalist bottom-border only or a fully boxed light-neutral background. Focus states use the Muted Gold accent for the border color.
- **Chips/Labels:** Used for property status (e.g., "JUST LISTED"). These should be small, high-kerning uppercase text with no background fill, just a thin border.
- **Lists:** Clean, horizontal dividers (0.5pt thickness) with generous padding between property features.
- **Navigation:** A minimalist top bar with high-transparency blur when scrolling. The logo should be the focal point, utilizing the serif display font.